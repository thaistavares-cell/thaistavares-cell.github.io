# Monitor de Editais

Sistema que acompanha automaticamente a publicação de editais de contratação
pública e mantém um histórico do que foi publicado. É meu primeiro projeto de
coleta e extração de dados.

## Como funciona

1. **Coleta:** duas vezes por dia, consulta a API do PNCP (Portal Nacional de
   Contratações Públicas).
2. **Filtragem:** seleciona os editais por palavras-chave.
3. **Arquivamento:** o próprio robô grava os resultados na pasta `historico/`
   e faz um commit a cada captura. O histórico do Git vira o registro do que
   foi publicado e quando.
4. **Agendamento:** tudo roda no GitHub Actions, sem servidor próprio.

## Estado atual

Rodando desde julho de 2026, com centenas de editais arquivados.

**Desafio em aberto:** a conexão com o PNCP falha de forma intermitente, e
algumas execuções que falham aparecem como bem-sucedidas. Próximo passo:
tentar de novo automaticamente e fazer a execução acusar erro quando a
coleta não acontecer.

## Próximas etapas

- **Análise do histórico:** distribuição dos editais por categoria, valor e
  tendência ao longo do tempo.
- **Refinamento do filtro:** com base no volume real, ajustar as
  palavras-chave ou construir um classificador que reduza os falsos
  positivos (editais que passam pelo filtro sem ser relevantes).

## O que este projeto me ensina

- Consumir uma API pública e lidar com respostas instáveis
- Automatizar tarefas com agendamento
- Tratar erros sem esconder falhas
- Usar o próprio Git como registro histórico de dados

## Tecnologias

TypeScript · GitHub Actions · API do PNCP

**Repositório:** O código está em repositório privado.

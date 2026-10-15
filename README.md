# Debriefing Pablo — Setembro/26

Dashboard estático do debriefing do lançamento pago de setembro/26: investimento, métricas pré e pós-abertura de carrinho (com referências Baldan e comparação com agosto/26), públicos quente/frio, campanhas, páginas e criativos. Vendas do carrinho (Método P3P, P3P - AV e Combo 4 em 1) cruzadas por e-mail com os compradores de ingresso e orderbumps.

- `index.html`: página completa, com os dados agregados já embutidos (sem nomes, e-mails ou telefones).
- `vercel.json`: configuração da Vercel (pede para buscadores não indexarem a página).

## Deploy na Vercel

Importe este repositório em [vercel.com/new](https://vercel.com/new). Framework: **Other**. Não há comando de build nem diretório de saída. Cada push na `main` publica de novo.

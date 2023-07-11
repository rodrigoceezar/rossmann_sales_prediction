# ROSSMANN STORE SALES

## Dataset Description
### Files

- train.csv - dados históricos, incluindo vendas
- test.csv - dados históricos excluindo vendas
- sample_submission.csv - um arquivo de envio de amostra no formato correto
- store.csv - informações complementares sobre as lojas

### Data fields

- Id: um Id que representa uma duplicata (Store, Date) dentro do conjunto de teste
- Loja: um ID exclusivo para cada loja
- Vendas: o volume de negócios para um determinado dia (isto é o que você está prevendo)
- Clientes: o número de clientes em um determinado dia
- Aberto: um indicador para saber se a loja estava aberta: 0 = fechado, 1 = aberto
- StateHoliday: indica um feriado estadual. Normalmente todas as lojas, com poucas exceções, fecham nos feriados estaduais. Observe que - todas as escolas fecham nos feriados e fins de semana. a = feriado, b = feriado da Páscoa, c = Natal, 0 = nenhum
- SchoolHoliday: indica se o (Store, Date) foi afetado pelo fechamento das escolas públicas
- StoreType: diferencia entre 4 modelos de loja diferentes: a, b, c, d
- Sortimento: descreve um nível de sortimento: a = básico, b = extra, c = estendido
- CompetitionDistance: distância em metros até a loja concorrente mais próxima
- CompetitionOpenSince[Month/Year]: fornece o ano e o mês aproximados da hora em que o concorrente mais próximo foi aberto
- Promo: indica se uma loja está realizando uma promoção naquele dia
- Promo2: Promo2 é uma promoção contínua e consecutiva para algumas lojas: 0 = loja não está participando, 1 = loja está participando
- Promo2Since[Year/Week]: descreve o ano e a semana em que a loja começou a participar do Promo2
- PromoInterval: descreve os intervalos consecutivos em que o Promo2 é iniciado, nomeando os meses em que a promoção é reiniciada. Por exemplo, "fevereiro, maio, agosto, novembro" significa que cada rodada começa em fevereiro, maio, agosto, novembro de qualquer ano para essa loja

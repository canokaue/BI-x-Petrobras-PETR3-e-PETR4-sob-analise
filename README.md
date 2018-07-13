# BI x Petrobras PETR3 e PETR4 sob analise


Arquivo QVF baseado nas cotações de ambos os tipos de ações nacionalmente negociadas da Petrobras no período de 02/01/2016 a 29/09/2010.

Primeiramente, são ressaltadas as diferenças de concepção e uso entre a PETR3 e a PETR4, assim como a razão simplificada da existência desta divisão em tipos distintos de ações. Em paralelo, as cotações médias de ambos os ativos são disponibilizados ao usuário (o qual pode especificar um período de análise) tanto em plot temporal, quanto em gauge limitados pelo máximo e mínimo histórico de cada ação. 

No Dashboard do Analista, a ideia dos gauges é evoluída para comparar a média do período selecionado com o máximo e mínimo local e também é introduzida a diferença percentual entre as duas Petro. Adicionalmente, cada ativo tem sua variação absoluta e percentual exibida em KPI, também tendo sua média em questão comparada ao mesmo período de 1 ou 12 meses anteriores. No plot temporal em linha, PETR3, PETR4 e a diferença absoluta entre elas são representadas conjuntamente. As 5 maiores altas e baixas de cada Petro no período analisado são indicadas por meio de gráficos de barra e, pelo mesmo meio, as médias anuais das cotações são comparadas. Por fim, dois treemaps indicam em quais meses cada ativo variou mais na seleção.

Na Dashboard do Investidor, por meio da extensão Variable de Erik Wett (https://github.com/erikwett/qsVariable), o usuário é capaz de especificar quantos shares de PETR3 e PETR4 possui em seu portfolio e, ao selecionar uma data, é exibido em "Valor total" qual o capital equivalente de seus investimentos. O usuário pode armazenar este valor no campo "Valor em shares atual" para que, posteriormente ao selecionar uma data de venda, consiga simular imediatamente qual seria o saldo deste trade. 

Dados disponibilizados por Pedro A. Morettin (https://www.ime.usp.br/~pam/ef.html - "d-petro06.10.dat").

Desenvolvido por Kauê Cano (github.com/kauecano) com Qlik Sense Desktop entre 04/07/18 e 08/07/18.
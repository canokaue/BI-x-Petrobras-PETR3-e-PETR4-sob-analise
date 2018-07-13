# BI x Petrobras PETR3 e PETR4 sob analise


Arquivo QVF baseado nas cota��es de ambos os tipos de a��es nacionalmente negociadas da Petrobras no per�odo de 02/01/2016 a 29/09/2010.

Primeiramente, s�o ressaltadas as diferen�as de concep��o e uso entre a PETR3 e a PETR4, assim como a raz�o simplificada da exist�ncia desta divis�o em tipos distintos de a��es. Em paralelo, as cota��es m�dias de ambos os ativos s�o disponibilizados ao usu�rio (o qual pode especificar um per�odo de an�lise) tanto em plot temporal, quanto em gauge limitados pelo m�ximo e m�nimo hist�rico de cada a��o. 

No Dashboard do Analista, a ideia dos gauges � evolu�da para comparar a m�dia do per�odo selecionado com o m�ximo e m�nimo local e tamb�m � introduzida a diferen�a percentual entre as duas Petro. Adicionalmente, cada ativo tem sua varia��o absoluta e percentual exibida em KPI, tamb�m tendo sua m�dia em quest�o comparada ao mesmo per�odo de 1 ou 12 meses anteriores. No plot temporal em linha, PETR3, PETR4 e a diferen�a absoluta entre elas s�o representadas conjuntamente. As 5 maiores altas e baixas de cada Petro no per�odo analisado s�o indicadas por meio de gr�ficos de barra e, pelo mesmo meio, as m�dias anuais das cota��es s�o comparadas. Por fim, dois treemaps indicam em quais meses cada ativo variou mais na sele��o.

Na Dashboard do Investidor, por meio da extens�o Variable de Erik Wett (https://github.com/erikwett/qsVariable), o usu�rio � capaz de especificar quantos shares de PETR3 e PETR4 possui em seu portfolio e, ao selecionar uma data, � exibido em "Valor total" qual o capital equivalente de seus investimentos. O usu�rio pode armazenar este valor no campo "Valor em shares atual" para que, posteriormente ao selecionar uma data de venda, consiga simular imediatamente qual seria o saldo deste trade. 

Dados disponibilizados por Pedro A. Morettin (https://www.ime.usp.br/~pam/ef.html - "d-petro06.10.dat").

Desenvolvido por Kau� Cano (github.com/kauecano) com Qlik Sense Desktop entre 04/07/18 e 08/07/18.
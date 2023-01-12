# Automation_DividendYield

_________________________________________________________________________________________________________
ATENÇÃO! ESSA FERRAMENTA NÃO É  UMA INDICAÇÃO DE COMPRA, O PROPÓSITO DO CÓDIGO É EDUCACIONAL E ANALÍTICO, 
AS DECISÕES DE INVESTIMENTOS SÃO 100% RESPONSABILIDADE DO USUÁRIO.
________________________________________________________________________________________________________

A função desse código é automatizar a obtenção de dados das ações brasileiras e aplicar métricas baseadas nos dividendos 
pagos pelas empresas, a matemática financeira utilizada é inspirada em Décio Bazin, que consiste em determinar um preço teto 
a se pagar pela ação com base nos proventos distribuidos nos últimos anos.

Automação de obtenção de dados e estipulação do preço teto das ações brasileiras com base na distribuição de proventos pagos aos acionistas.
COMO USAR: Abra o arquivo DividendExecute em Python, instale as bibliotecas caso não possua (Incluso no código).
Execute o código e aguarde o download dos dados das ações, após baixar todos os dados um DataFrame irá ser printado.

LEGENDAS:
TICKER: Código de negoiciação da ação na B3.
DATA: Data do último fechamento de mercado.
PREÇO ATUAL: Preço atual da ação com base na data de último fechamento.
PREÇO TETO: Preço máximo a se pagar na ação com base no dividendo mínimo alvo determinado (padrão 6%).
MARGEM DE SEGURANÇA: Diferença percentual entre o Preço atual e o Preço teto da ação.
DY_Médio: Dividend Yield médio dos últimos 6 anos distribuídos pela empresa.
DY% Atual: Dividend Yield cálculado com base nos proventos pagos nos últimos 12 meses.

DIVIDEND YIELD = Lucro percentual financeiro pago ao acionista em forma de proventos distríbuidos.

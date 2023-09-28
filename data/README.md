## Dicionário de dados

Dados pessoais

- `ID`: Identificador único do cliente
- `Year_Birth`: Ano de nascimento do cliente
- `Education`: Nível de educação do cliente
- `Marital_Status`: Estado civil do cliente
- `Income`: Renda anual da família do cliente
- `Kidhome`: Número de crianças na casa do cliente
- `Teenhome`: Número de adolescentes na casa do cliente
- `Dt_Customer`: Data de inscrição do cliente na empresa
- `Recency`: Número de dias desde a última compra do cliente
- `Complain`: 1 se o cliente reclamou nos últimos 2 anos, 0 caso contrário

Dados de produtos

- `MntWines`: Valor gasto em vinho nos últimos 2 anos
- `MntFruits`: Valor gasto em frutas nos últimos 2 anos
- `MntMeatProducts`: Valor gasto em carne nos últimos 2 anos
- `MntFishProducts`: Valor gasto em peixe nos últimos 2 anos
- `MntSweetProducts`: Valor gasto em doces nos últimos 2 anos
- `MntGoldProds`: Valor gasto em produtos *gold* nos últimos 2 anos

Dados de campanha

- `NumDealsPurchases`: Número de compras feitas com desconto
- `AcceptedCmp1`: 1 se o cliente aceitou a oferta na 1ª campanha, 0 caso contrário
- `AcceptedCmp2`: 1 se o cliente aceitou a oferta na 2ª campanha, 0 caso contrário
- `AcceptedCmp3`: 1 se o cliente aceitou a oferta na 3ª campanha, 0 caso contrário
- `AcceptedCmp4`: 1 se o cliente aceitou a oferta na 4ª campanha, 0 caso contrário
- `AcceptedCmp5`: 1 se o cliente aceitou a oferta na 5ª campanha, 0 caso contrário
- `Response`: 1 se o cliente aceitou a oferta na última campanha (piloto), 0 caso contrário (*target*)

Dados de local de compra

- `NumWebPurchases`: Número de compras feitas através do site da empresa
- `NumCatalogPurchases`: Número de compras feitas usando um catálogo
- `NumStorePurchases`: Número de compras feitas diretamente nas lojas
- `NumWebVisitsMonth`: Número de visitas ao site da empresa no último mês

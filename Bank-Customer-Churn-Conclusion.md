# Bank Customer Churn - Project Conclusion

# Conclusion (English)

## 1. Which attributes are more common among customers who cancel the service? Is it possible to predict churn?

The main attributes analyzed were **Age, Tenure, NumOfProducts,
CreditScore, Gender, IsActiveMember, and HasCrCard**.

### Conclusion

The attribute that stands out the most is **Age**: customers who churned
have an average age of **44.84 years**, compared with **37.41 years**
among customers who remained.

Another important indicator is **IsActiveMember**. Among customers who
churned, approximately **65.7% were classified as inactive**, compared
with approximately **44% among customers who remained**.

**Credit Card Ownership** also shows an interesting difference.
Approximately **63.89% of churned customers did not have a credit
card**, compared with **44.55% of retained customers**. This represents
a difference of approximately **19.34 percentage points** between the
two groups.

These findings suggest an association between credit card ownership and
customer retention, although they do not establish a causal
relationship.

## 2. What is the overall demographic profile of the bank's customers?

The dataset contains **10,002 customers** distributed across:

-   **France:** approximately 5,020 customers
-   **Germany:** approximately 2,510 customers
-   **Spain:** approximately 2,480 customers

Regarding gender, there is a **predominance of male customers** in the
dataset.

The average age by country is:

-   **Germany:** 39.77 years
-   **Spain:** 38.89 years
-   **France:** 38.51 years

### Conclusion

The overall customer profile is predominantly **male**, with an average
age of approximately **39 years**. Germany has the highest average
customer age among the three countries.

## 3. Is there any difference in the behavior of German, French, and Spanish customers?

The main attributes analyzed were **Tenure, IsActiveMember,
NumOfProducts, and Balance**.

### Tenure

-   France: **5.00 years**
-   Germany: **5.01 years**
-   Spain: **5.03 years**

The values are practically identical.

### NumOfProducts

-   France: **1.53**
-   Germany: **1.52**
-   Spain: **1.54**

Again, the values are very similar.

### Customer Activity

Based on the analysis:

-   France: approximately **51.8% active**
-   Germany: approximately **48% active**
-   Spain: approximately **52% active**

There is a small difference: **Germany has a slightly lower proportion
of active customers**, while Spain has a slightly higher proportion.

### Balance

The total balance was approximately:

-   France: **R\$ 28.5 billion**
-   Germany: **R\$ 27.4 billion**
-   Spain: **R\$ 14.0 billion**

However, this value should be interpreted carefully. **We cannot
conclude that French customers have more money simply because France has
a higher total balance**, since France also has approximately twice as
many customers as Germany and Spain.

### Conclusion

**No major behavioral differences were identified among the three
countries.** Tenure and average number of products are practically the
same. Customer activity shows a small difference, with Germany having a
slightly lower proportion of active customers.

## 4. What types of customer segments exist within the customer base?

For this analysis, the main focus was on **behavioral segmentation**,
particularly the relationship between **NumOfProducts** and
**IsActiveMember**.

The results show:

-   **1 product:** relatively balanced distribution between active and
    inactive customers.
-   **2 products:** slightly higher proportion of active customers.
-   **3 products:** higher proportion of **inactive customers**.
-   **4 products:** relatively balanced distribution again.

### Conclusion

The customer base can be segmented primarily according to **the number
of products held and the customer's activity level**.

One group that stands out is the group of customers with **three
products**, where inactive customers represent the larger share.
Customers with one, two, and four products show a more balanced
distribution between active and inactive customers.

## Overall Conclusion

**The analysis of the customer base revealed that age, customer
activity, and credit card ownership are the attributes with the most
noticeable differences in relation to churn.** Customers who churned
have a considerably higher average age, show a lower level of activity,
and are more likely not to have a credit card.

In contrast, variables such as tenure, number of products, and
CreditScore present relatively small differences between customers who
remained and those who churned.

**Regarding the overall customer profile, the database has a
predominance of male customers, with an average age close to 39 years.**
Among France, Germany, and Spain, no major behavioral differences were
identified, with similar values for tenure and average number of
products.

**Finally, behavioral segmentation shows that the combination of the
number of products and customer activity can be used to identify
different customer groups.** Customers with three products stand out
because they have a higher proportion of inactive customers.

------------------------------------------------------------------------

# Conclusão (Português)

## 1. Quais características são mais comuns entre os clientes que cancelam o serviço? É possível prever o churn?

As principais características analisadas foram **Age, Tenure,
NumOfProducts, CreditScore, Gender, IsActiveMember e HasCrCard**.

### Conclusão

A característica que mais se destaca é a **idade (Age)**: os clientes
que cancelaram o serviço apresentam idade média de **44,84 anos**,
enquanto aqueles que permaneceram possuem idade média de **37,41 anos**.

Outro indicador importante é a **atividade do cliente
(IsActiveMember)**. Entre os clientes que cancelaram o serviço,
aproximadamente **65,7% foram classificados como inativos**, em
comparação com aproximadamente **44% entre os clientes que
permaneceram**.

A **posse de cartão de crédito (HasCrCard)** também apresenta uma
diferença interessante. Aproximadamente **63,89% dos clientes que
cancelaram o serviço não possuíam cartão de crédito**, em comparação com
**44,55% dos clientes que permaneceram**. Isso representa uma diferença
de aproximadamente **19,34 pontos percentuais** entre os dois grupos.

Esses resultados sugerem uma associação entre a posse de cartão de
crédito e a retenção de clientes, embora não estabeleçam uma relação de
causa e efeito.

## 2. Qual é o perfil demográfico geral dos clientes do banco?

A base de dados contém **10.002 clientes**, distribuídos entre:

-   **França:** aproximadamente 5.020 clientes
-   **Alemanha:** aproximadamente 2.510 clientes
-   **Espanha:** aproximadamente 2.480 clientes

Em relação ao gênero, existe uma **predominância de clientes do sexo
masculino** na base de dados.

A idade média por país é:

-   **Alemanha:** 39,77 anos
-   **Espanha:** 38,89 anos
-   **França:** 38,51 anos

### Conclusão

O perfil geral dos clientes é predominantemente **masculino**, com idade
média próxima de **39 anos**. A Alemanha apresenta a maior idade média
entre os três países analisados.

## 3. Existem diferenças no comportamento dos clientes alemães, franceses e espanhóis?

As principais características analisadas foram **Tenure, IsActiveMember,
NumOfProducts e Balance**.

### Tempo de relacionamento (Tenure)

-   França: **5,00 anos**
-   Alemanha: **5,01 anos**
-   Espanha: **5,03 anos**

Os valores são praticamente idênticos.

### Número de produtos (NumOfProducts)

-   França: **1,53**
-   Alemanha: **1,52**
-   Espanha: **1,54**

Novamente, os valores são muito semelhantes.

### Atividade dos clientes (Customer Activity)

Com base na análise:

-   França: aproximadamente **51,8% de clientes ativos**
-   Alemanha: aproximadamente **48% de clientes ativos**
-   Espanha: aproximadamente **52% de clientes ativos**

Existe uma pequena diferença: a **Alemanha apresenta uma proporção
ligeiramente menor de clientes ativos**, enquanto a Espanha apresenta
uma proporção um pouco maior.

### Saldo dos clientes (Balance)

O saldo total foi de aproximadamente:

-   França: **R\$ 28,5 bilhões**
-   Alemanha: **R\$ 27,4 bilhões**
-   Espanha: **R\$ 14,0 bilhões**

Entretanto, esse resultado deve ser interpretado com cautela. **Não
podemos concluir que os clientes franceses possuem mais dinheiro
simplesmente porque a França apresenta um saldo total maior**, uma vez
que o país também possui aproximadamente o dobro de clientes em relação
à Alemanha e à Espanha.

### Conclusão

**Não foram identificadas diferenças comportamentais expressivas entre
os clientes dos três países.** O tempo de relacionamento e o número
médio de produtos são praticamente iguais. A atividade dos clientes
apresenta uma pequena variação, com a Alemanha registrando uma proporção
ligeiramente menor de clientes ativos.

## 4. Quais tipos de segmentos de clientes existem na base analisada?

Nesta análise, o foco principal foi a **segmentação comportamental**,
especialmente a relação entre **NumOfProducts e IsActiveMember**.

Os resultados mostram:

-   **1 produto:** distribuição relativamente equilibrada entre clientes
    ativos e inativos.
-   **2 produtos:** proporção ligeiramente maior de clientes ativos.
-   **3 produtos:** maior proporção de clientes inativos.
-   **4 produtos:** distribuição novamente relativamente equilibrada.

### Conclusão

A base de clientes pode ser segmentada principalmente de acordo com **a
quantidade de produtos contratados e o nível de atividade dos
clientes**.

Um grupo que se destaca é o de clientes com **três produtos**, no qual
os clientes inativos representam a maior parcela. Já os clientes com um,
dois e quatro produtos apresentam uma distribuição mais equilibrada
entre ativos e inativos.

## Conclusão Geral

**A análise da base de clientes revelou que idade, atividade e posse de
cartão de crédito são as características que apresentam as diferenças
mais perceptíveis em relação ao churn.** Os clientes que cancelaram o
serviço possuem uma idade média consideravelmente maior, apresentam um
nível de atividade inferior e têm maior probabilidade de não possuir
cartão de crédito.

Em contrapartida, variáveis como tempo de relacionamento, número de
produtos e pontuação de crédito (CreditScore) apresentam diferenças
relativamente pequenas entre os clientes que permaneceram e aqueles que
cancelaram o serviço.

**Em relação ao perfil geral dos clientes, a base de dados apresenta
predominância de clientes do sexo masculino, com idade média próxima de
39 anos.** Entre França, Alemanha e Espanha, não foram identificadas
diferenças comportamentais expressivas, com valores semelhantes de tempo
de relacionamento e número médio de produtos.

**Por fim, a segmentação comportamental demonstra que a combinação entre
quantidade de produtos e nível de atividade permite identificar
diferentes grupos de clientes.** Os clientes com três produtos se
destacam por apresentar uma proporção maior de clientes inativos.

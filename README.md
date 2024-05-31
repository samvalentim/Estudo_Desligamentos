# Estudo Desligamentos

Estudo do perfil dos desligados usando a Metodologia CRISP-DM 

## Entendimento do Negócio
Para tentar entender quais as características que fazem um funcionário ficar ou deixar uma empresa de Tecnologia, o RH desta empresa catalogou informações de 1470 funcionários que deixaram ou permaneceram na companhia no último ano. O resultado desse levantamento gerou 19 possíveis fatores que explicam o comportamento do turnover, que estão disponíveis no arquivo Base_RH.xlsx.
### Problema do Negócio 
Quais políticas/fatores da empresa deveriam mudar de forma a minimizar o turnover?

## Entendimento dos Dados
Base em planilha de Excel com duas abas, sendo a primeira a base de dados propriamente dita com 19 colunas e 1470 linhas e a segunda, uma tabela auxiliar de metadados. 
### Metadados
![image](https://github.com/samvalentim/Power_BI/assets/106708930/8795d1af-c93b-4499-8c78-f7975cee0ca6)


## Preparação dos Dados
### Identificação das variáveis mais relevantes
Utilizou-se o Information Value para identificar quais variáveis tem associação mais forte com os desligamentos, servindo como primeiro norte para direcionamento da construção do Dashboard e Análise de Dados.
Utilizou-se como índice de classificação: 
•	< 0,02 : Muito Fraco
•	0,02 a 0,1: Fraco
•	0,1 a 0,3: Médio
•	0,3 a 0,5: Forte
•	> 0,5: Forte demais pra ser verdade
Obteve-se os seguintes IVs: 
 ![image](https://github.com/samvalentim/Power_BI/assets/106708930/5db2d9ec-6549-4c11-8e2b-b498acb2487b)


### Memória de Cálculo
Information Value =  , onde Pi é a proporção de casos bons e Qi, a de maus casos. Expliquei melhor sobre o IV no Artigo do LinkedIn (Clique aqui). 
Taxa de Desligamento = n° desligamento / n° funcionários

## Modelagem e Análise
- Escolha de técnicas, desenvolvimento do modelo e estudo analítico


### Data Viz. 


### Insights





# Dados sobre as Carteiras de Créditos - Taxas, Inadimplência, Saldos, e mais comparativos.
Extração de dados através da Lib e relatórios divulgados do Banco Central para Análise dos dados referente a:
<br>
* Taxa de juros das operações de crédito entre PJ e PF.
* Inadimplência da carteira de crédito entre PJ e PF.
* Concessões de crédito para tomadores PJ e PF.
* Spread das operações de crédito entre tomadores PJ e PF
* Analisando os principais players da linha de Financimentos.
* Analisando as Receitas Operacionais dos Bancos.
* Agrupando o % de Carteira de Crédito entre PF e PJ dos Bancos.
* Prevendo o saldo da Carteira de Crédito para os próximos 2 anos.
* Classificando a carteira de crédito dos Bancos por Região.

<br>
Fonte de dados:
<br>

[SGS - Sistema Gerenciador de Séries Temporais - Banco Central](https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries). 
<br>

[Sobre o Portal do Banco Central](https://dadosabertos.bcb.gov.br/pages/sobre-o-portal)

[Banco Central - IF Data](https://www3.bcb.gov.br/ifdata/#!)

<br>
<br>
<b>Modulos utilizados:</b> Numpy, Pandas, Matplotlib, Seaborn, Pycaret, BCB.
<br>
<br>

<b>Passo a passo:</b>  

<b>LIB Banco Central e Relatórios abertos<b>
<br>
<b>Tarefa 1:</b> Identificação de Dados.
<br>
<b>Tarefa 2:</b> Coleta de Dados.
<br>
<b>Tarefa 3:</b> Pré-processamento de dados.
<br>
<b>Tarefa 4:</b> Análise e representação dos conjuntos de dados processados.
<br>
<br>

<b>Notebook:</b> [Mercado de Crédito](https://github.com/mamedevitor/Teste_Dados/blob/master/Teste_Dados.ipynb)
<br>



# Concessões Mensais de Crédito, Taxa a.a média de juros, Inadimplência e Spread  PJ vs. PF
<br>

Aqui podemos ter os seguintes insights:
* Em 2022, a concessão de crédito para PF ultrapassou e disparou em relação as concessões de créditos para PJ;
* A taxa média de juros a.a é quase que o drobro para PF do que para PJ;
* O percentual de inadimplência de também é bem maior de PF quando comparado a PJ;
* Hoje o percentual de Spread médio está quase o triplo maior para PF do que para PJ. 


![image](https://user-images.githubusercontent.com/83721127/214052384-1402ed63-1611-44e6-a8bd-44d63969aa24.png)
<br>
<br>
![image](https://user-images.githubusercontent.com/83721127/214054788-67c7e930-65f0-4b52-b411-f4f5c2b64692.png)
<br>
<br>
![image](https://user-images.githubusercontent.com/83721127/214054982-2b337776-a48e-4674-a809-b26c00a46c32.png)
<br>
<br>
![image](https://user-images.githubusercontent.com/83721127/214055051-1346a963-943d-4ed1-a733-d83c451d22d5.png)


<br>
<br>
<br>
<br>

# Conclusões das Concessões, Juros, Inadimplência e Spread.
A concessão de crédito é a operação no qual uma instituição financeira ou bancária, analisa a liberação de crédito para uma pessoa física ou jurídica, podendo ser na forma de cartão de crédito, empréstimos, financiamentos, cheques, entre outros.


Com os insights dos gráficos acima, podemos ver que a maioria das concessões de créditos acontecem para pessoa física, os juros são mais altos e os spreads também, em contra partida, vemos o risco onde a inadimplência nos créditos de pessoa física, hoje está o dobro quando comparado a pessoa jurídica.
<br>
<br>
<br>
<br>
 
# Banco especialistas em Finaciamentos
Podemos notar que nessa amostra 3 meses do ano de 2022, o saldo da carteira de crédito de Financiamentos do BV, está em R$23Bi, disparado dos outros grandes players do Mercado de Crédito.
  
![image](https://user-images.githubusercontent.com/83721127/214063865-c913d995-bba0-4c88-b738-df2969229298.png)
<br>
<br>
<br> 

  
# Bancos que se destacaram por Receita Operacional nos meses de 08/22 à 10/22.

Classificando os Bancos por Receita Operacional dos últimos 3 meses de 2022 divulgado pelo Bacen, podemos ver o Banco Santander com aproximadamente R$170Bi a mais que o segundo colocado.


![image](https://user-images.githubusercontent.com/83721127/214066752-cf64f247-b623-4a2e-98b7-5c2e415a77d7.png)
<br>
<br>
<br>
  
 # Principais Bancos comparados por Carteira de Crédito (PF x PJ) - 01/22 à 09/22 (Último tri ainda não divulgado pelo Bacen).

Este gráfico, nos apresenta os principais Bancos classificados pelo Total Geral da carteira de crédito em 2022, separando o total entre Pessoa Física vs. Pessoa Jurídica.
<br>
<br>
Podemos notar que o Banco Itaú e o Banco Bradesco, são os que mais diversificam sua carteira entre PF x PJ, tendo a carteira quase divida em 50/50.
<br>
<br>
Podemos ver também, que o principais Bancos com as carteiras em grande maioria de Pessoa Física, é a Caixa, Banco do Brasil e Santander.
E em maioria de carteira com Pessoa Júridica, "desconsiderando" o BNDES, vemos o Safra e o BTG com grande maoria de carteira em PJ.
<br>
<br>
![image](https://user-images.githubusercontent.com/83721127/214068084-fceb7a67-0d78-4ba3-a637-244c4752ccad.png)

<br>
<br>


# Prevendo o saldo total de Crédito para os próximos 2 anos.
Hoje o saldo total de crédito está em aproximadamente R$5tri.
  
![image](https://user-images.githubusercontent.com/83721127/214071991-c0ffd334-15c0-4a3d-ae34-10446b8e3f55.png)

<br>

Com o auxílio da lib de Auto Machine Learning, Pycaret, chegamos a uma previsão de aproximadamente R$6,50 tri em novembro de 2024.

![image](https://user-images.githubusercontent.com/83721127/214077004-c8c824e3-8f1c-4b45-9620-cd70ba5d6de0.png)
  
<br> 
  
![image](https://user-images.githubusercontent.com/83721127/214077133-5a1e8cdc-283b-42d8-9740-3d892c89b736.png)

<br> 
  
# Classificação da Carteira de Crédito por Região
No gráfico abaixo, separei a carteira de crédito de 2022 dos Bancos, por região.
<br>
<br> 
Dessa forma, nota-se a concentração das operações na região Sudeste e Sul do País, concentrando ~61,91% da carteira de crédito do País, nessas regiões.
<br>
Percebe-se também, o baixo percentual de operações na região Norte do país, apenas 4,42%.
<br>
<br> 
![image](https://user-images.githubusercontent.com/83721127/214078767-3c0c1978-7537-43ef-ac5f-ab267b717ac0.png)
 

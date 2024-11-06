# Análise do preço do combustível no Brasil De Janeiro a Junho de 2024

### 1. Os dados da análise foram pegos diretamente na base de dados do governo [(Clique para ir ao link)](https://dados.gov.br/dados/conjuntos-dados/vendas-de-derivados-de-petroleo-e-biocombustiveis)

### 2. Para realizar essa análise, usei a biblioteca PandaSQL para simular querys que seriam feitas em um banco de dados para realizar a análise, só que nesse caso foram feitas dentro da biblioteca Pandas usando um arquivo xlsx como base de dados
    - O foco principal foi demonstrar minhas habilidades com querys em SQL e com Dataviz no tableau.

### 3. Aqui no repositório há uma análise apenas dos preços da gasolina para que não ficasse repetitivo a análise, já que bastaria apenas alterar o nome do produto para que a mesma análise fosse feita; 

### 4. Para completar essa análise e deixa-lá mais completa, criei uma visualização dos dados na ferramenta Tableau onde além do produto gasolina, podem ser selecionados outros produtos em datas diferentes e também em métricas diferentes (preço Máx, Mín e Méd);

### 5. Segue alguns dos resultados:

        - O preço médio geral de venda da gasolina entre os meses de Janeiro e Junho de 2024 foi de R$ 5,78 no Brasil.

        - Quando fazemos uma análise geral entre o preço médio e os meses, vemos que com o passar dos meses os preços tendem a aumentar, tanto para os estados isoladamente, como os preços no geral.

        - Existe uma variação notável nos preços médios da gasolina entre os estados. Entretanto, o que mais chama a atenção é a diferença entre os preços mínimo e máximo dentro de cada estado. Em muitos estados, essa diferença supera os 20% (em valores absolutos, superam a casa dos RS 1,40), indicando variação considerável nos preços de revenda;

        - Quando paramos para olharmos, dentro do mesmo estado, há uma grande diferença entre o menor preço e o maior. A menor diferença está dentro do estado de Roraima, onde a diferença é de 8% (RS 0,55), ou seja, uma diferença baixa;

        - No entanto, a maior expressividade dessa diferença entá dentro do estado de São Paulo, onde a diferença percentual entre maior e menor preço é de  43,05% (RS 3,44) como apontado na análise

        - Referente aos preços médios, o ACRE (AC) possui o maior preço médio, de 6,99 Reais, sendo seguido pelo Amazonas (AM), com preço médio de 6,44 Reais. A diferença entre os dois é de 7,87%, ou seja,	diferença de RS 0,55

        - A diferença mais expressiva é entre o estado com maior preço médio ACRE (AC) de RS 6,99 e o estado com menor preço médio, o Píaui com preço médio de R$ 5,57. A diferença entre os dois em porcentagem é de 20,32%, ou seja, valor absoluto de RS 1,42.

        - Na análise podemos ver que o estado com maiores preços se é o Acre com um preço médio de RS 6,99. No entanto, quando paramos para olhar o municipio que possui o preço médio mais alto de todo o Brasil é o município de Tefé do estado do Amazonas. Tefé é considerado o meior preço da gasolina do país, com um preço médio de RS 7,68.

        - Quando paramos para olhar o município do Acre com menor preço médio (Rio Branco com preço médio de RS 6,76), ele fica acima de quase todos os outros município de outros estados que possuem o maior preço médio em relação ao seu estado. 

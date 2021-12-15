# Case de Estudo: Empresa Blocker Fraud Company

# 1.0 Contexto


# 2.0 Problema de Negócio

A Blocker Fraud Company é uma empresa especializada na detecção de fraudes com transações financeiras feitas através de dispositivos móveis. A empresa tem um serviço chamado "Blocker Fraud" no qual garante o bloqueio de transações financeiras.

O modelo de negócio da empresa é do tipo serviço com a monetização feita por performance do serviço prestado, ou seja, o usuário paga uma taxa fixa sobre o sucesso na detecção de fraude das transações do cliente. Porém, a Blocker Fraud Company está em fase de expansão no Brasil e para adquirir clientes mais rapidamente, ela adotou uma estratégia muito agressiva. A estratégia funciona da seguinte maneira:

- A empresa vai receber 25% do valor de cada transação detectada verdadeiramente como fraude.
- A empresa vai receber 5% do valor de cada transação detectada como fraude, porém a transação é verdadeiramente legítima.
- A empresa vai devolver 100% do valor para o cliente, a cada transação detectada como legítima, porém a transação é verdadeiramente uma fraude.

Com essa estratégia agressiva, a empresa assume os riscos em falhar na detecção de fraude e é remunerada na detecção assertiva das fraudes.

<h2> O Desafio </h2>

A Block Fraud Company solicitou uma consultoria em Ciência de Dados para criar um modelo de alta precisão e acurácia na detecção de fraudes de transações feitas através de dispositivos móveis.

Ao final da consultoria, precisa-se entregar ao CEO da Block Fraud Company um modelo em produção no qual seu acesso será feito via API, ou seja, os clientes enviarão suas transações via API para que o modelo as classifique como fraudulentas ou legítimas. Além disso, precisará ser entregue um relatório reportando a performance e os resultados do modelo em relação ao lucro e prejuízo  que a empresa terá ao usar o modelo produzido. No relatório deve conter as respostas para as seguintes perguntas:

- Qual a precisão e acurácia do modelo?
- Qual a confiabilidade do modelo em classificar as transações como legitimas ou fraudulentas?
- Qual o faturamento esperado pela empresa, se classificarmos 100% das transações com o modelo ?
- Qual o prejuízo esperado pela empresa em caso de falha do modelo ?
- Qual o lucro esperado pela Blocker Fraud Company ao utilizar o modelo ?

<h2> Apresentando os Dados </h2>

O conjunto de dados que será utilizado para criar a solução da Blocker Fraud Company está disponível no Kaggle.

<h2> Objetivos </h2>

- Criar um modelo de machine learning para detectar fraudes.
- Colocar o modelo em Produção.
- Criar um relatório do modelo respondendo as perguntas.

# 3.0 Solução




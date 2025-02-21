<h1> Análise RFM para E-commerce </h1>

<h3> 📚 Sobre o Projeto </h3>
<p> Este projeto foi desenvolvido no Google Colab utilizando Python para realizar a análise de clientes de um e-commerce com base na métrica RFM (Recency, Frequency, Monetary). O objetivo é transformar os dados brutos de compras em insights acionáveis sobre o comportamento dos clientes, permitindo segmentação e estratégias personalizadas para retenção e engajamento. </p>

<h3> ⚡ Desafio </h3>
<p> A empresa contratante solicitou um estudo baseado em RFM, onde: </p>
<p> Recency (R): Tempo desde a última compra do cliente (em dias); </p>
<p> Frequency (F): Quantidade de compras realizadas pelo cliente; </p>
<p> Monetary (M): Ticket médio gasto pelo cliente. </p>
<p> O resultado final é um arquivo CSV contendo a identificação dos clientes e seus respectivos valores RFM.</p>

<h3> 📁 Base de Dados </h3>
<p> A base utilizada contém informações de compras realizadas em 37 países e possui as seguintes colunas principais: </p> 
<p> CustomerID: Identificação do cliente </p>
<p> InvoiceNo: Código da fatura </p>
<p>InvoiceDate: Data da compra</p>
<p> Quantity: Quantidade de itens comprados </p>
<p> UnitPrice: Preço unitário do produto </p>
<p> Country: País da compra </p>

<h2> 🔄 Processo de Desenvolvimento </h2>
<h3> 1. Leitura e Inspeção dos Dados </h3>
<p> Leitura do dataset </p>
<p> Uso de describe() para entender a distribuição dos dados</p>
<p>Verificação dos tipos de dados</p>


<h3> 2. Tratamento de Dados </h3>
<p></p>
<p></p>
<p></p>
<p></p>

<h3> </h3>
<p>Remoção de valores nulos no CustomerID </p>
<p> Filtragem de valores de Quantity e UnitPrice menores ou iguais a zero </p>
<p> Exclusão de linhas duplicadas </p>
<p> Conversão dos tipos de dados de CustomerID e InvoiceDate </p>

<h3> 3. Identificação e Remoção de Outliers </h3>
<p> Remoção de compras com Quantity > 10.000 ou UnitPrice > 5.000 </p>

<h3> 4. Cálculo do Total Gasto </h3>
<p> Criada uma nova coluna TotalPrice = Quantity * UnitPrice </p>

<h3> 5. Definição da Data de Referência </h3>
<p> Identificação da última data de compra no dataset </p>

<h3> 6. Geração de Gráficos para Insights </h3>
<p> Top 10 países com maior valor em vendas </p>
<p> Top 10 produtos mais vendidos </p>
<p> Evolução do valor total de vendas por mês </p>
<p>Evolução do valor total de vendas por mês e por país (Top 10) </p>

<h3> 7. Cálculo dos Indicadores RFM </h3>
<p> Recency (R): Diferença entre a última compra do cliente e a data de referência </p>
<p> Frequency (F): Número de compras feitas pelo cliente </p>
<p> Monetary (M): Média do valor gasto por compra </p>

<h3> 8. Exportação dos Resultados </h3>
<p> O dataset final com as métricas RFM é salvo em um novo arquivo CSV. </p>

<h3> 🚀 Tecnologias Utilizadas </h3>
<p> Python: Pandas, NumPy, Matplotlib, Seaborn </p>
<p> Google Colab: Ambiente de execução </p>

<h3> 📄 Resultado Final </h3>
<p> O projeto entregou uma base limpa e estruturada com os indicadores RFM para cada cliente, permitindo que a empresa identifique padrões de consumo e elabore estratégias de marketing direcionadas. </p>






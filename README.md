# 📊 **Análise de Vendas e Performance Comercial com SQL no Databricks: `Foco em CRM`** 🚀

Em um cenário empresarial competitivo, as empresas estão constantemente buscando **otimizar suas estratégias comerciais** para aumentar a eficiência e maximizar os resultados. A utilização de sistemas de **Customer Relationship Management (CRM)** se tornou crucial para monitorar as interações com clientes, o andamento das oportunidades de vendas e o desempenho das equipes comerciais.

Este projeto explora um conjunto de dados de CRM e utiliza **SQL no Databricks** para extrair **insights valiosos**, oferecendo uma visão estratégica sobre o processo de vendas, o comportamento do cliente e o desempenho da equipe comercial.


## **🎯 Objetivos do Projeto**

- **Avaliar o Desempenho da Equipe de Vendas:** Analisar o desempenho individual dos vendedores, destacando os que geram mais oportunidades e os produtos que têm melhor aceitação nas negociações.
- **Identificar Oportunidades de Expansão:** Detectar produtos e segmentos de vendas que estão sendo subutilizados ou não explorados de maneira otimizada.
- **Identificar e Otimizar Estratégias para Aumentar a Conversão:** Analisar o desempenho comercial e o comportamento dos clientes para melhorar as taxas de conversão de oportunidades de vendas.
- **Desenvolver Dashboards Interativos:** Criar relatórios dinâmicos e dashboards que facilitem a **tomada de decisões**, oferecendo uma visão clara e intuitiva sobre o desempenho comercial e as métricas de vendas.


## **📂 Conjunto de Dados**

O dataset contém informações detalhadas sobre contas de clientes, oportunidades de vendas, atividades comerciais e desempenho da equipe de vendas. Ele é composto por cinco arquivos principais:

📊 **accounts.csv** – Informações sobre os clientes, incluindo dados demográficos e firmográficos.

📊 **sales_pipeline.csv** – Registro das oportunidades de vendas, incluindo estágio, valor e probabilidade de conversão.

📊 **products.csv** – Lista de produtos e serviços oferecidos pela empresa.

📊 **agents.csv** – Informações sobre os vendedores e métricas de desempenho.

📊 **data_dictionary.csv** – Este arquivo contém a documentação detalhada sobre as colunas presentes nos arquivos mencionados. Ele serve como um dicionário de dados que descreve as variáveis, seus tipos de dados, significados e valores possíveis. Ele é essencial para a compreensão do conjunto de dados e para a correta manipulação e análise dos dados.


## **🔍 Resultados Obtidos**

1. **Produtos Mais Vendidos por Cada Conta:**  
   O *GTX Plus Pro* lidera as vendas, com Kan-code sendo o maior comprador (92.402 unidades). O *MG Advanced* possui boa aceitação, com Konex e Rangreen como principais clientes. O *GTK 500* tem menor demanda, mas apresenta oportunidades de crescimento, especialmente com contas como Cheers. Isso sugere que, enquanto o *GTX Plus Pro* é o principal produto da empresa, estratégias para aumentar a penetração do *GTK 500* são necessárias.
![image](https://github.com/user-attachments/assets/1ab572e2-18b7-4382-abe8-ce3f514919de)

2. **Valor Total de Vendas Fechado por Cada Produto:**  
   *GTX Plus Pro* e *MG Advanced* se destacam, com mais de 4,8 milhões em vendas. Já *GTX Plus Basic* e *GTX Basic* apresentam vendas mais baixas, sugerindo que o mercado prefere as versões Pro. O *MG Special* apresenta o menor valor de vendas, possivelmente devido à baixa demanda ou um posicionamento de nicho. Para otimizar, seria interessante considerar estratégias promocionais ou ajustes no posicionamento e preço.
![image](https://github.com/user-attachments/assets/83808c82-813d-417e-ae73-81a5cc2b86d6)

3. **Agentes de Vendas que Mais Fecharam Vendas:**  
   Darcel Schlecht se destaca, com vendas de 1.153.214, seguida por Vicki Laflamme e Kary Hendrixson com 478.396 e 454.298, respectivamente. Há uma grande variação de desempenho entre os agentes, sugerindo que fatores como treinamento, suporte e estratégias de vendas precisam ser analisados para melhorar os resultados dos agentes com baixo desempenho.

| #  | Vendedores         | Total de Vendas |
|----|--------------------|-----------------|
| 1  | Anna Snelling      | 275.056         |
| 2  | Boris Faz          | 261.631         |
| 3  | Cassey Cress       | 450.489         |
| 4  | Cecily Lampkin     | 229.800         |
| 5  | Corliss Cosme      | 421.036         |
| 6  | Daniell Hammack    | 364.229         |
| 7  | Darcel Schlecht    | 1.153.214       |
| 8  | Donn Cantrell      | 445.860         |
| 9  | Elease Gluck       | 289.195         |
| 10 | Garret Kinder      | 197.773         |
| 11 | Gladys Colclough   | 345.674         |
| 12 | Hayden Neloms      | 272.111         |
| 13 | James Ascencio     | 413.533         |
| 14 | Jonathan Berthelot | 284.886         |
| 15 | Kami Bicknell      | 316.456         |
| 16 | Kary Hendrixson    | 454.298         |
| 17 | Lajuana Vencill    | 194.632         |
| 18 | Markita Hansen     | 328.792         |
| 19 | Marty Freudenburg  | 291.195         |
| 20 | Maureen Marcano    | 350.395         |

4. **Perfil de Clientes que Geram Maior Valor de Vendas:**  
   Os setores *medical*, *retail* e *tecnologia* são os principais responsáveis pelas maiores vendas, com empresas como Condax, Singletechno e Kan-code gerando os melhores resultados. Focar nessas indústrias pode proporcionar uma forte expansão e crescimento no futuro.
![image](https://github.com/user-attachments/assets/696e1a4a-b018-45a7-b9a6-6655a3470e78)

5. **Gargalos no Pipeline de Vendas:**  
   O pipeline apresenta gargalos significativos. Com 4.238 oportunidades "Won" e 2.473 "Lost", muitas vendas estão sendo perdidas. A fase "Engaging" com 1.589 oportunidades sugere que muitas oportunidades não estão avançando para o fechamento, enquanto a fase "Prospecting" tem apenas 500 oportunidades, indicando uma falta de leads qualificados. É essencial qualificar melhor os leads, otimizar o follow-up e treinar melhor a equipe de vendas para aumentar as conversões e reduzir as oportunidades perdidas.
![image](https://github.com/user-attachments/assets/87f4f041-c670-490c-978e-88ac6a1aacb9)

---

## **🛠️ Ferramentas e Tecnologias Utilizadas**

- **Databricks:** Plataforma poderosa para o processamento de grandes volumes de dados, utilizando Apache Spark para realizar consultas complexas e análise de dados em larga escala.
- **SQL:** Linguagem de consulta padrão utilizada para manipulação, extração e análise dos dados.
- **Visualizações no Databricks:** Criação de **dashboards interativos** e **gráficos dinâmicos** para facilitar a visualização e análise de resultados.

## **🎯 Conclusão**

Este projeto demonstrou como a **análise de dados** pode ser um grande diferencial para a **otimização de estratégias comerciais**. O uso de ferramentas como **SQL no Databricks** permite à empresa obter **insights valiosos** para a melhoria contínua dos processos de vendas. A análise não só melhorou o **desempenho da equipe de vendas**, mas também contribuiu para a **eficiência operacional** e o **planejamento estratégico**, resultando em **maiores receitas** e **maior satisfação do cliente**.

---

**📌 Contribua com o Projeto:**  
Sinta-se à vontade para contribuir com melhorias, sugestões ou atualizações! Sua colaboração é sempre bem-vinda.


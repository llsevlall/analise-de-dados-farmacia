# 📊 Análise Comparativa de Vendas: Excel e Power BI

![Gif do projeto final](assets/demo.gif)

#### 📈 Projeto de análise de dados de uma farmácia fictícia
Este projeto demonstra um pipeline completo, desde o começo da extração de dados até os dashboards finais. 
Recebi duas bases de dados sujas, no qual elas se relacionavam. Uma "customers" e outras "orders".

Caso você queira ver todo o processo e as ferramentas que utilizei (Pandas, SQL, Excel e Power BI), é só clicar nos tópicos abaixo:

<details>
<summary>🔍 1. Verificando os dados</summary>

#### Primeiro comecei analisando a base de dados, percebi que nela haviam datas nulas, quantidades negativas, nomes de cidades que não batiam e alguns outros dados que precisam ser tratados
![Screenshot 1](assets/Screenshot_1.png)
![Screenshot 2](assets/Screenshot_2.png)
</details>

<details>
<summary>🧹 2. Começando a limpar</summary>

#### Utilizei Python com Pandas para fazer a limpeza de alguns dados irregulares, comecei deixando as quantidades positivas e preenchi posteriormente os dados que estavam nulos
![Screenshot 3](assets/Screenshot_3.png)
![Screenshot 4](assets/Screenshot_4.png)
![Screenshot 5](assets/Screenshot_5.png)
![Screenshot 6](assets/Screenshot_6.png)
</details>

<details>
<summary>🗄️ 3. Consulta SQL</summary>

#### Após tratar alguns dados, fui fazer a consulta, nela eu juntei as duas tabelas com o relacionamento e procurei somente as vendas feitas a partir de 2024. Depois disso salvei como tabela_final em .xlsx
![Screenshot 7](assets/Screenshot_7.png)
</details>

<details>
<summary>⚙️ 4. Terminando limpeza (Power Query)</summary>

#### Fui e enviei o arquivo tabela_final para o Power Query, e lá eu terminei de tratar alguns dos dados sujos que faltaram, como nomes de cidades irregulares 'São Paulo' e 'sao paulo', 'Curitiba ' e 'Curitiba', e mais alguns ajustes
![Screenshot 8](assets/Screenshot_8.png)
</details>

<details>
<summary>📉 5. Excel</summary>

#### Após ter todos os dados tratados, fui para o Excel, lá eu criei uma nova tabela 'Total', criei algumas tabelas dinâmicas e um dashboard contendo as principais informações
![Screenshot 9](assets/Screenshot_9.png)
![Screenshot 10](assets/Screenshot_10.png)
![Screenshot 11](assets/Screenshot_11.png)
</details>

<details>
<summary>💎 6. Power BI</summary>

#### E por final, fui para o Power BI para criar um último gráfico e criei alguns DAX essenciais para o projeto
![Screenshot 12](assets/Screenshot_12.png)
![Screenshot 13](assets/Screenshot_13.png)
</details>
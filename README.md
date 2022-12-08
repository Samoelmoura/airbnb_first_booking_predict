### Olá, seja bem vindo ao meu diretório. Esta página é somente um relatório do projeto, para acessar as análises na íntegra clique na pasta "notebooks" e em seguida no arquivo "notebook.ipynb" :smiley:
# Airbnb Predict First Booking

## Recomendação assertiva para novos clientes

![](img/capa_readme.jpg)

#### This project was made by Samoel de Moura.

# 0. Context
Em vez de acordar com sinais esquecidos de "Não perturbe", os viajantes do Airbnb se veem acordando com os pássaros em uma casa na árvore caprichosa, tomando seu café da manhã no convés de uma casa flutuante ou cozinhando um café da manhã regional compartilhado com seus anfitriões.

Novos usuários no Airbnb podem reservar um lugar para ficar em mais de 34.000 cidades em mais de 190 países. Ao prever com precisão onde um novo usuário reservará sua primeira experiência de viagem, o Airbnb pode compartilhar conteúdo mais personalizado com sua comunidade, diminuir o tempo médio para a primeira reserva e prever melhor a demanda.

# 0.1 Problema de Negócio:

Neste desafio, você recebe uma lista de usuários junto com seus dados demográficos, registros de sessão da web e algumas estatísticas resumidas. Você é solicitado a prever em qual país será o primeiro destino de reserva de um novo usuário. Todos os usuários neste conjunto de dados são dos EUA.

## 0.2 GLossary:

#### train_users.csv - the training set of users

- id: user id
- date_account_created: the date of account creation
- timestamp_first_active: timestamp of the first activity, note that it can be earlier than date_account_created or date_first_booking because a user can search before signing up
- date_first_booking: date of first booking
- gender
- age
- signup_method
- signup_flow: the page a user came to signup up from
- language: international language preference
- affiliate_channel: what kind of paid marketing
- affiliate_provider: where the marketing is e.g. google, craigslist, other
- first_affiliate_tracked: whats the first marketing the user interacted with before the signing up
- signup_app
- first_device_type
- first_browser
- country_destination: this is the target variable you are to predict

### sessions.csv - web sessions log for users

- user_id: to be joined with the column 'id' in users table
- action
- action_type
- action_detail
- device_type
- secs_elapsed

# 1. Business Problem.
1. Qual será o primeiro destino que um novo usuário irá escolher?
2. Quais são as características dos clientes que viajam para cada destino?

## 1.1 Motivação:

- Modelo de Negócio

    - Marketplace - Conectar pessoas que oferecem acomodações, com pessoas que estão procurando acomodações
    
        - Oferta (Pessoas oferecendo acomodações)
            - Tamanho do portifólio
            - Diversidade do portifólio
            - Preço Médio
            
        - Demanda (Pessoas buscando se acomodar)
            - Número de usuários
            - LTV (Life-time value)
            - CAC (Cliente aquisition cost)
            
        - Gross Revenue (Margem - CAC)

# 2. Business Assumptions.

# 3. Solution Strategy

## 3.1 Inputs:

* Problema de negócio
* Dados com características dos clients com 21mil+ amostras e 12 dimensões e ações dos clientes no site da plataforma com 1milhão+ amostras e 6 dimensões.

## 3.2 Outputs:
1. API Request:
* Em uma situação real este projeto teria a seguinte entrega:
Entrega do algorítmo treinado, disponível em núvem, com requisições automatizadas em tempo real direto no portal da Airbnb
* Tratando-se de um projeto de estudos a entrega se dará da seguinte forma:
Entrega do algorítmo treinado, disponível em núvem, com requisições através de uma planilha de Google Sheets do tipo:

           client_id | gender | age | action 1 | action 2 | destiny (target)
               10001 | male   | 56  | click    | open link|     US
               10002 | female | 31  | visualize| buy      |     FR
                 ... | male   | 56  | click    | open link|     other
 
 2. Resposta ao time de negócio:
 Resposta direta textual com gráficos inclusos em uma apresentação por Jupyter Notebook
 
## 3.3 Tasks:

**Step 01. Data Description:**

**Step 02. Feature Engineering:**

**Step 03. Data Filtering:**

**Step 04. Exploratory Data Analysis:**

**Step 05. Data Preparation:**

**Step 06. Feature Selection:**

**Step 07. Machine Learning Modelling:**

**Step 08. Hyperparameter Fine Tunning:**

**Step 09. Convert Model Performance to Business Values:**

**Step 10. Deploy Modelo to Production:**

# 4. Top 3 Data Insights

# 5. Machine Learning Model Applied

# 6. Machine Learning Modelo Performance

# 7. Business Results

# 8. Conclusions

# 9. Lessons Learned

# 10. Next Steps to Improve

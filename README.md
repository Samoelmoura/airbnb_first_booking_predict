### Olá, seja bem vindo ao meu diretório. Esta página é somente um relatório do projeto, para acessar as análises na íntegra clique na pasta "notebooks" e em seguida no arquivo "notebook.ipynb" :smiley:
# Airbnb Predict First Booking

## Construção de uma API que fará a predição de compra de novos clientes na plataforma

#### This project was made by Samoel de Moura.
# 0.0 Context
Em vez de acordar com sinais esquecidos de "Não perturbe", os viajantes do Airbnb se veem acordando com os pássaros em uma casa na árvore caprichosa, tomando seu café da manhã no convés de uma casa flutuante ou cozinhando um café da manhã regional compartilhado com seus anfitriões.

Novos usuários no Airbnb podem reservar um lugar para ficar em mais de 34.000 cidades em mais de 190 países. Ao prever com precisão onde um novo usuário reservará sua primeira experiência de viagem, o Airbnb pode compartilhar conteúdo mais personalizado com sua comunidade, diminuir o tempo médio para a primeira reserva e prever melhor a demanda.

Nesta competição de recrutamento, o Airbnb desafia você a prever em qual país um novo usuário fará sua primeira reserva. Os Kagglers que impressionarem com sua resposta (e uma explicação de como chegaram lá) serão considerados para uma entrevista para a oportunidade de ingressar na equipe de ciência e análise de dados do Airbnb.

In this challenge, you are given a list of users along with their demographics, web session records, and some summary statistics. You are asked to predict which country a new user's first booking destination will be. All the users in this dataset are from the USA.

There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. Please note that 'NDF' is different from 'other' because 'other' means there was a booking, but is to a country not included in the list, while 'NDF' means there wasn't a booking.

The training and test sets are split by dates. In the test set, you will predict all the new users with first activities after 7/1/2014 (note: this is updated on 12/5/15 when the competition restarted). In the sessions dataset, the data only dates back to 1/1/2014, while the users dataset dates back to 2010. 

File descriptions
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
- sessions.csv - web sessions log for users
- user_id: to be joined with the column 'id' in users table
- action
- action_type
- action_detail
- device_type
- secs_elapsed
# 1. Business Problem.
- Imput
    - Business Problem
        - Previsão do primeiro destino que um novo usuário irá escolher.
    - Datasete
    - Motivação
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
- Output
    - Modelo de predições com requisição através de um arquivo Jupyter Notebook do tipo:
        - Input = características do usuário
        - Output = usuário com suas características com a predição do destino    

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

**Hypothesis 01:**

**True/False.**

**Hypothesis 02:**

**True/False.**

**Hypothesis 03:**

**True/False.**

# 5. Machine Learning Model Applied

# 6. Machine Learning Modelo Performance

# 7. Business Results

# 8. Conclusions

# 9. Lessons Learned

# 10. Next Steps to Improve

# LICENSE

# All Rights Reserved - Comunidade DS 2022

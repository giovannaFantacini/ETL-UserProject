
# User Analysis
#### Projeto desenvolvido durante o curso da Santander Dev Week 2023

O objetivo principal do projeto é a utilização do modelo ETL para captura, transformação e carregamento dos novos dados. O projeto a seguir propõe que a API do Chat GPT crie campanhas de marketing voltadas ao usuário de acordo com o seu nome, trabalho e produto de interesse.

Para isso foi utilizada uma API desenvolvida através do site [https://mockapi.io/](https://mockapi.io/), onde é possível criar uma API com valores aleatórios, nessa API foram criados diversos usuários seguindo o modelo: 

     {
      "createdAt": "",
      "name": "",
      "job": "",
      "gender": "",
      "companyName": "",
      "product": "",
      "marketing": {},
      "id": ""
     }

Após a criação dos usuários, foram realizados os seguintes passos: 

 1. Extract: A partir da requisição Get foram recuperados os usuários existentes.
 2. Transform: A partir dos dados dos usuários foram criadas campanhas de marketing especificas para cada usuário.
 3. Load: A mensagem de marketing criada para cada usuário foi inserida no item "marketing" de cada usuário.

  

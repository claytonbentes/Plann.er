# Plann.er

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

Aplicação para gerenciamento e organização de viagens de trabalho ou lazer, 
desenvolvida para ajudar usuários a planejar e acompanhar suas próximas viagens. 
Permite criar viagens com nome, data de início e fim, convidar participantes, organizar 
atividades diárias e salvar links importantes.

Projeto desenvolvido durante evento da Rocketseat


## API Endpoints
A API fornece os seguintes endpoints:

```markdown
API Disponível na porta http://localhost:8080

POST /trips - Criar viagem

POST /trips/{id}/invite - Convida pariticipante

POST /trips/{id}/activities - Registra atividade

POST /trips/{id}/links - Registra link

POST - /participants/{id}/confirm - Confirma participante

GET - /trips/{id}/confirm - Confirma viagem

GET - /trips/{id}/participants - Recupera participantes da viagem

GET - /trips/{id}/activities - Recupera atividades da viagem

GET - /trips/{id}/links - Recupera links da viagem

GET - /trips/{id} - Recupera detalhes da viagem

PUT - /trips/{id} - Atualiza viagem

```

## Contato

[![](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/claytonbentes/)
[![](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:claytonjhony.bentes@gmail.com)

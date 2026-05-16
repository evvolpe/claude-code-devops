# Criar Dockerfile

Essa aplicação precisa ser executada utilizando o container Docker então o próximo passo é fazer a criação do Dockerfile e do Docker Compose. 
- Analise o projeto para entender as tecnologias e dependências
- O Dockerfile deve seguir as boas práticas
- O Docker compose será utilizado para desenvolvimento

---

Essa aplicação precisa ser executada utilizando o container Docker então o próximo passo é fazer a criação do Dockerfile e do Docker Compose. 
- Analise o projeto para entender as tecnologias e dependências
- O Dockerfile deve seguir as boas práticas
- O Docker compose será utilizado para desenvolvimento

Boas práticas
- Não utilizar multi stage build em projetos nodejs
- No Docker compose sempre que utilizar volumes, utilize bind mount para a pasta .docker_vol na raiz do projeto


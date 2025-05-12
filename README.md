# django-empty

Este repositório serve como um template base para projetos Django, permitindo iniciar rapidamente um novo projeto com uma estrutura pré-configurada.

## Propósito

O `django-empty` foi criado para ser um ponto de partida para projetos Django. Pode clonar este repositório e importar o seu projeto Django existente, aproveitando a configuração inicial já preparada.

## Conteúdo

- **.github/workflows**: Contém os ficheiros de configuração para o pipeline CI/CD, que automatiza o build, push e deploy da imagem Docker.
- **.gitignore**: Define os ficheiros e pastas a serem ignorados pelo Git, como ficheiros temporários e ambientes virtuais.
- **Dockerfile**: Ficheiro de configuração para construir a imagem Docker da aplicação Django.
- **docker-compose.yml**: Configuração para orquestrar serviços com Docker Compose, útil para desenvolvimento local.
- **requirements.txt**: Lista as dependências Python necessárias para o projeto.

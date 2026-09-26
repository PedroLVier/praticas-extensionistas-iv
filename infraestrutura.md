# Infraestrutura de Deploy e Publicação

A solução será publicada no Render. O frontend será uma aplicação React no formato PWA, o backend será desenvolvido com Node.js e Express e o banco de dados será PostgreSQL.

## Estrutura prevista

- Frontend PWA publicado como Static Site no Render;
- Backend / API publicado como Web Service no Render;
- Banco de dados PostgreSQL;
- Código e documentação armazenados no GitHub;
- GitHub Actions para testes, build e publicação;
- GitHub Secrets e variáveis de ambiente para dados sensíveis;
- Comunicação por HTTPS.

## Justificativa

O Render foi escolhido porque permite manter frontend, backend e banco de dados em uma mesma plataforma e possui integração com o GitHub. Para um projeto acadêmico de pequeno porte, isso deixa a publicação mais simples e reduz a quantidade de configurações necessárias.

AWS, Microsoft Azure e Google Cloud também poderiam ser utilizados e oferecem mais recursos de infraestrutura. Porém, para o escopo atual do projeto, exigiriam mais configuração e administração. Por isso, o Render foi considerado mais adequado para esta etapa.

Para a implantação posterior, o grupo deverá criar e configurar os serviços necessários no Render e conectar o repositório do GitHub.

Projeto Base de Aplicação Web em PHP
Arquitetura MVC Leve para Fins Acadêmicos

Apresentação

Este projeto consiste no desenvolvimento de uma estrutura base de aplicação web em PHP, organizada segundo o padrão MVC (Model–View–Controller) em sua forma leve, com o objetivo de servir como referência acadêmica para disciplinas relacionadas a programação web, arquitetura de software e boas práticas de desenvolvimento.

O sistema não representa um TCC oficial, mas foi desenvolvido com os mesmos critérios técnicos, organizacionais e conceituais exigidos em trabalhos de conclusão de curso, podendo ser utilizado como modelo de estudo, base para projetos futuros ou demonstração de conhecimento técnico.

Objetivo Geral

Desenvolver uma aplicação web em PHP com foco em:

Organização de código

Separação de responsabilidades

Segurança básica

Escalabilidade

Clareza arquitetural

Objetivos Específicos

Aplicar o padrão MVC sem uso de frameworks

Demonstrar a separação entre lógica de negócio, controle e apresentação

Utilizar variáveis de ambiente para configuração sensível

Estruturar o projeto de forma compreensível e reutilizável

Criar uma base sólida para aplicações web acadêmicas ou profissionais

Arquitetura Utilizada

O projeto utiliza uma arquitetura MVC Leve, onde:

Model: Responsável pela comunicação com o banco de dados e representação dos dados

View: Responsável pela apresentação visual ao usuário

Controller: Responsável por intermediar requisições e respostas

Services: Camada adicional para regras de negócio

Routes: Centralização das rotas da aplicação

Front Controller: Um único ponto de entrada (public/index.php)

Essa abordagem foi escolhida por sua simplicidade, clareza didática e proximidade com padrões utilizados no mercado.

Estrutura de Pastas

/app
 ├── Controllers   → Controle das requisições
 ├── Models        → Manipulação de dados
 ├── Services      → Regras de negócio
 ├── Views         → Interface do usuário
 └── Helpers       → Funções auxiliares

/config            → Configurações do sistema
/routes            → Definição das rotas
/public            → Arquivos acessíveis via navegador
/storage           → Logs e arquivos temporários

Segurança e Boas Práticas

Utilização de arquivo .env para dados sensíveis

Separação entre arquivos públicos e privados

Evita exposição direta de lógica PHP ao navegador

Organização voltada à manutenção e crescimento do sistema

Tecnologias Utilizadas

PHP (sem frameworks)

HTML5

CSS3

JavaScript

Servidor Apache ou Nginx

MySQL (opcional / simulado)

Status do Projeto

Projeto acadêmico / base estrutural

Não possui foco em funcionalidades completas, mas sim na arquitetura e organização do código.

Considerações Acadêmicas

Este projeto foi desenvolvido como exercício prático e conceitual, simulando um trabalho de conclusão de curso, com o intuito de demonstrar:

Capacidade de planejamento estrutural

Conhecimento em arquitetura de software

Boas práticas de desenvolvimento web

Organização e documentação de projetos

Licença

Este projeto é de uso educacional, podendo ser adaptado e reutilizado para fins de estudo.

Observação Final

Este repositório não tem como objetivo competir com frameworks consolidados, mas sim demonstrar domínio dos conceitos fundamentais que sustentam tais ferramentas.
# API com NodeJS - Canal Maransatto

Este projeto foi criado seguindo a série de vídeos tutoriais do canal Maransato

<br>

## O que foi visto nas aulas e o que aprendi com elas?

<hr/>

Vídeo 1: Introdução (O que é uma REST API?)<br>
* O que é REST API?
    * Representational State Transfer ou Estado de Transferência Representativo, em português.
    * A ideia do REST é ser uma forma alternativa de transferir dados entre o servidor e o cliente.
    * No sistema tradicional de transferência de dados, o cliente solicita (request) uma página e o servidor responde (response) essa requisição com páginas HTML formadas.
    * Porém caso o cliente não precise de uma página HTML, mas sim apenas dos dados que estão no servidor, o modelo tradicional falha em atender a essa demanda, já que só transfere páginas HTML completas.
    * Foi para atender essa demanda que o padrão REST API surgiu. Ele transfere apenas os dados entre o cliente e o servidor, deixando a responsabilidade de tratar e mostrar esses dados com o cliente.
    * Existem algumas formas de tansferir dados, são elas:
        * JSON;
        * XML;
        * URLEncoded;
        * FormData; etc.
    * Restrições do REST
        * Funciona no padrão cliente-servidor
        * Interface de usuário não é importante
        * Não armazena Sessões, ou seja, não guarda nenhum contexto sobre o cliente que está acessando a API
        * Pode ou não ser construído em um sistema de camadas, ou seja, uma API REST pode consumir outro serviç
        * Os recursos da requisição, por exemplo uma rota /listaprodutos, são desacoplados do banco de dados. Ou seja, não possuem relação direta com os schemas do banco de dados.<br><br>

<hr/>

Vídeo 2: Criando o ambiente
* Instalação do Node.js.
* Iniciando um repositório git.
* Iniciando um projeto Node.
* Criação de um servidor básico que retorna uma mensagem de ok.

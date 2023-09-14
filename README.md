# Thanos E-commerce
Este repositório contem o meu E-commerce para estudos de JS, HTML, CSS, Vite, Tailwind e outras linguagens 


## Como Iniciar:
Para iniciar o projeto é importante que tenham as seguintes ferramentas instaladas

 - [Node.JS](https://nodejs.org/en/): Runtime Build para renderização do Javascript em ambiente;
 - [NPM](https://www.npmjs.com/): Gerenciador de pacotes para o Node, trazendo a maioria das funcionalidades do projeto;

Ao instalar as duas ferramentas, você já está apto a seguir com a instalação de qualquer projeto. Para os próximos passos você precisa de algum terminal com linha de comando:

1. Clone o repositório: https://github.com/EnzoShiotuqui/E-commerce.git

2. Vá até a pasta que você acabou de clonar e utilize os comandos para instalar as dependências necessárias para o funcionamento de cada pasta:

    cd .\nome-da-pasta-em-que-clono\    
     cd .\E-commerce\
       cd .\ecommerce\
        npm install

4. Com a pasta "node-modules" criada basta rodar o projeto com o seguinte comando 

   npm run dev 

Prontinho, caso esteja tudo certo o terminal ira mostrar uma mensagem com o link, basta acessar e desfrutar do site :)

## Estrutura do Projeto:

    pasta_base\
    	|-- public\ ➡️ pasta com todos os visuais\estilos
          |-- assets\ ➡️ pasta com fotos usadas
              |-- img\ ➡️ pasta com as imagens gerais do site 
              |-- logo\ ➡️ pasta com Logo do site
    	|-- src\ ➡️ pasta principal com todos os scripts necessarios
    	    |-- cartaoProduto.js\ ➡️ Script que valida dados do cartão do usuário 
          |-- filtroCatalogo.js\ ➡️ Script que realiza o filtro no catalógo, deixando uma melhor exp ao usuário 
          |-- menuCarinho.js\ ➡️ Script que simula a ação do carinho, adicionar produtos, remover, e ir para área de compra
          |-- utlidades.js\ ➡️ Script que exporta os array de produtos e guarda as informações do usuario o local-storage e no banco de dados
      
      |-- checkout.html\ ➡️ Arquivo Html da área de cartão, para o usuário realizar a "compra"
      |-- index.html\ ➡️ Arquivo Html da área de principal, que seria a área de catalógo 
      |-- main.js\ ➡️ Arquivo js principal que realiza funcionalidades da área do catalógo 
      
      
      
        
 

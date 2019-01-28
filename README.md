# desafio-api
Desafio-solutis.

Como parte do processo seletivo, gostaríamos que você fizesse uma pequena tarefa. O problema proposto é uma situação fictícia e você não estará desenvolvendo uma solução para nossa empresa neste teste.

Durante o desenvolvimento da aplicação você pode usar a linguagem Java e Spring Boot.

Os fontes da aplicação, os scripts e arquivos de configuração, se você os utilizar, criados para a execução da aplicação e do container deverão ser versionados para avaliação. Também deve ser versionado um arquivo README com instruções para a execução de seu projeto.

Crie um projeto no seu Github para que vejamos os passos feitos através dos commits para resolver a tarefa.

O desafio!

1 - Você deverá desenvolver uma API (Restful) simples que receba uma requisição HTTP com uma string, e encontre o primeiro caractere Vogal, após uma consoante, onde a mesma é antecessora a uma vogal e que não se repita na string.

Premissas: Não será possível reiniciar o fluxo da leitura da string. Não poderá ser utilizado nenhum framework Java, apenas código nativo na identificação da vogal.

Exemplo: Input: aAbBABacafe Output: e No exemplo, ‘e’ é o primeiro caractere Vogal da stream que não se repete após a primeira Consoante ‘f’o qual tem uma vogal ‘a’ como antecessora.

O resultado do processamento deverá ser igual á:

{ "string": " aAbBABacafe", "vogal": "e", "tempoTotal": "10ms" }

Pontos adicionais:

Usar JavaSE 8. Usar banco (em memória, ex.: H2) para armazenar o resultado de cada requisição; Criar projeto em Angular 5 ou 6 para invocar a API e mostrar o resultado na tela.

Para este projeto foram utilizados as seguites tecnologias:

Spring Boot.
JavaSE 8.
banco H2.
maven.

para executar:
Utilizando o Eclipse use a opção Import do menu, selecione Maven->Existing Maven Project e clique em Next. Clique no botão Browse e localize a pasta, logo apos execute o comando mvc clean install dentro do diretório do projeto Para baixar as dependências.

Para Testar:
Utilize o postman para fazer o request.


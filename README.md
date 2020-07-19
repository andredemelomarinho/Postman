# Postman
Foram realizados testes  de GET,POST,PUT,DELETE positivos e negativos
Foi utilizados a biblioteca BDD
Foram realizados scripts de pre-request para utilzar dados pré definidos
Foram utilizados variávies globais além de variáveis de ambiente para realização dos request
Foi criado um arquivo de configuração com as variáveis de ambiente.
Foi criado um collection com os testes criados.
Foi criado um arquivo .bat para rodar os teste no newman
-Para utlizar o newman deve-se
  1. Instalar npm install -g newman
  2. Instalar  npm install -g newman-reporter-html para gerar relatório html.
  Utilzando esse comando será executado todos os testes da collection criada e gerado um relatório em html.
  newman run Desafio_SOUTHSYSTEM.postman_collection.json -r htmlextra --reporter-htmlextra-export report.html




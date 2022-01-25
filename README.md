# configServer

Trabalho da disciplina Serviços em Nuvem e Projeto de Bloco do Instituto Infnet. Este trabalho consiste em fazer um jogo rpg, em que cada funcionalidade do jogo é realizado através de um micro-serviço.

O projeto configServer é pra ser usado em conjunto com eurekaServer, batalha e rolldice.

configServer tem o objetivo de buscar algumas informações utilizadas pelo projeto batalhas, tais como credenciais de acesso ao banco, driver, etc. O arquivo acessado pelo configServer está dentro da pasta infnet.

Para utilizá-lo, será necessário um ambiente java para subir a aplicação, e caso necessário, alterar o caminho da pasta infnet (dentro do projeto configServer) e o arquivo dentro da pasta infnet(conforme as suas configurações), além de ter o MySql instalado.

É necessário que esse serviço seja iniciado antes dos serviços de batalha e rolldice.

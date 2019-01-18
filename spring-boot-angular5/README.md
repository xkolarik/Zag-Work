# spring-boot-angular5

Teste Zag-Work

Projeto de Formulario de Clientes:

1. Spring Boot v1.5.9
2. Angular v5.0.0
3. Maven

Esse projeto destina-se a um formulario de clientes - Que por si so fazem operações com seus cartões de credito,
para essa aplicação seguir a arquitetura microsservicos foi separado o front-end do backend, onde podemos deixar o servico "backend" funcionando em um container escaldo com banco de dados mongoDB pois as requisições são feitas em REST que tem o objetivo de trabalhar escaldo no kubernet ou docker swarm. Mantendo a aplicação com codigo legivel sem assustar os desenvolvedores pois caso essa aplicação tenha mudancas daqui 5 anos teremos um grande gap para conseguir manter a aplicação em alta sem muitos problemas, e tambem poderiamos ter muitas requisições pois daqui 5 anos mais clientes estariam entrando na instituição financeira o que causaria o acumulo de requisições tornando trabalhoso para os serviços funcionando, gerando um alto numero de maquitas e gastos para manter a aplicação.
Ja no conceito dos microsserviços teremos controle separadamente de cada modulo utilizado pelos usuarios com mais agilidade a atendimento tanto para os usuarios quanto a praticidade para os desenvolvedores que forem fazer novas atualizações.

Para realizar a subida da aplicação:
-Necessario Ter instalado o node-js para estartar o NPM server.
-Startar o Spring Boot
-Buildar a aplicação
-Acessar a URL: http://localhost:4200/

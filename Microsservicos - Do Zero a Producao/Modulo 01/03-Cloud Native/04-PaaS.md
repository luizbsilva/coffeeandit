# PaaS
   > PaaS — Platform as a Service — em computação, consiste no serviço propriamente dito de hospedagem e implementação de hardware e software, que é usado para prover aplicações (software como serviço) por meio da Internet.

## Características

* PaaS pode ser considerada IaaS adicionada uma camada middleware e/ou componentes prontos.
* Uma camada de abstração entre seu aplicativo em nuvem e seu provedor de IaaS.
* É um ambiente de execução escalável e com alta disponibilidade para aplicações customizadas.
* PaaS, é uma categoria de computação em nuvem que fornece uma plataforma e um ambiente para permitir que os desenvolvedores criem aplicativos e serviços pela Internet.
* Fornece fundamentalmente escala elástica do seu aplicativo.

## Benefícios

* Infraestrutura na nuvem, escalável e com alta disponibilidade nativa.
* Alta produtividade no desenvolvimento e manutenção de aplicações sob demanda.
* Resumindo: baixo custo (TCO), confiabilidade e diminuição do tempo de entrega.

## Vantagens

* Desenvolvimento 100% focado no negócio: Por direcionar a arquitetura lógica e administrar a arquitetura física de forma bem transparente, é possível desenvolver uma aplicação que vá demandar uma requisição por minuto ou 10 mil requisições por segundo da mesma forma, com o mesmo nível de preocupação do ponto de vista técnico: apenas a lógica de negócio.
* Produtividade: O simples fato de não se gerenciar balanceamento de carga, replicação,cluster, instalando e configurando middlewares(servidores de aplicação, banco de dados, etc.) já é um grande ganho. Além disso, os grandes fornecedores estão criando camadas de componentes prontos para uso, APIs e aceleradores de desenvolvimento nessas plataformas.

## Decisões

* A plataforma por trás do PaaS foi criada justamente para trazer benefícios e acelerar o desenvolvimento. Existe esforço dos fornecedores para deixar essa camada o mais padrão possível, mas ainda existe uma boa parte que é proprietária.
* Ao adotar PaaS, é natural que se adote também essa camada proprietária, caso contrário, poderia se trabalhar direto na infraestrutura. 
* É esta camada que permite dar um salto de produtividade e lidar com escalabilidade e disponibilidade de forma transparente.
* A decisão a ser tomada é: menos custo e mais entregas contra o efeito “lock-in” das aplicações construídas nessa abordagem.!


## Restrições

* Plataformas são muito eficientes para construção de novas aplicações.
* A migração de aplicações já existentes para elas é um processo custoso ou mesmo inviável (dependendo da tecnologia atual e da plataforma almejada).
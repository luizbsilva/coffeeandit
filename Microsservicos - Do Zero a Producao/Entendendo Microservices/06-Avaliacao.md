# Avaliação Microsserviços - Do Zero à Produção

## Questão 1

>Correto: Atingiu 2,00 de 2,00

> Sobre SOA. SOA é uma arquitetura que permite a criação de serviços interoperáveis que podem ser reutilizados e compartilhados entre aplicações.

> Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso

> Feedback:  A resposta correta é 'Verdadeiro'.

## Questão 2

>Correto: Atingiu 2,00 de 2,00

> Sobre as vantagens da Arquitetura SOA. É correto afirmar que: 
>  Escolha uma ou mais:

>  [ ] a. É uma arquitetura com protocolo e chema XML próprio denominado SOAP 
>
>  [✔] b. Suporta serviços independentemente de tecnologia e protocolos. 
>
>  [✔] c. Permite a Reutilização de serviços 
>
>  [✔] d. Permite Desacoplamento com Integrações inteligentes, flexibilidade e alinhamento com o negócio. 

> Feedback Sua resposta está correta.
> As respostas corretas são: 
>
> Permite Desacoplamento com Integrações inteligentes,  flexibilidade e alinhamento com o >negócio., Permite a Reutilização de serviços, Suporta serviços >independentemente de tecnologia e protocolos.

## Questão 3

> Correto Atingiu 1,00 de 1,00

> Sobre as vantagens da arquitetura monolítica. Selecione as alternativas corretas.

> Escolha uma ou mais:

>  [ ] a. Facilidade de  colocar alterações em produção, sem risco de pequenas modificações causarem grande impacto.
>
>  [✔] b. Fácil de desenvolver em seu início. 
>
>  [✔] c. Tráfego de rede baixo 
>
>  [✔] d. Apenas um deploy por instalação 

> Feedback :
> Sua resposta está correta.
>
> As respostas corretas são: 
>  Fácil de desenvolver em seu início., Apenas um deploy por instalação, Tráfego de rede baixo

## Questão 4
> Correto Atingiu 1,00 de 1,00

> Sobre a arquitetura de Microserviços. Selecione as alternativas corretas.

> Escolha uma ou mais:
>  [ ] a. Baixa latência de rede
>
>  [✔] b. Facilidade de colocar alterações em produção 
>
>  [✔] c.  Serviços com baixo nível de acoplamento e interdependência 
>
>  [] d. Como os sistemas são distribuidos aumenta a facilidade da coordenação entre os times.
>

> Feedback :
> Sua resposta está correta.
>
>As respostas corretas são:  Serviços com baixo nível de acoplamento e interdependência, Facilidade de colocar alterações em produção

### Questão 5

> Correto Atingiu 1,00 de 1,00

> Sobre Event Sourcing Pattern. É correto afirmar que Event Sourcing Pattern cria eventos relacionados às alterações no estado do aplicativo. 
>
> Estes eventos são armazenados como uma sequência de eventos para ajudar os desenvolvedores a rastrear quais alterações foram feitas quando. Portanto, você sempre pode ajustar o estado do aplicativo para lidar com as alterações anteriores.

>Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso

> Feedback
>
> A resposta correta é 'Verdadeiro'.

### Questão 6
> Correto Atingiu 1,00 de 1,00

> Sobre o pattern de Command Query Pattern. É correto afirmar que é uma variação do Agregador. Nesse caso, nenhuma agregação precisa ocorrer no cliente, mas um microsserviço diferente pode ser chamado com base nas necessidades de negócios. Assim como o Agregador, o Proxy também pode ser dimensionado independentemente. Você pode fazer isso onde cada serviço individual não precisa ser exposto ao consumidor e, ao invés vez disso, deve passar por uma interface de acesso.

>Escolha uma opção:

>  [ ] Verdadeiro [✔] Falso 

> Feedback
> Command Query Pattern o aplicativo será dividido em duas partes: Comando e Consulta. A parte do comando tratará de todas as solicitações relacionadas a CREATE, UPDATE, DELETE, enquanto a parte da consulta cuidará das visualizações materializadas. As visualizações materializadas são atualizadas por meio de uma sequência de eventos que são criados usando o Event Pattern apresentado anteriormente.
>
> A resposta correta é 'Falso'.

### Questão 7
> Correto Atingiu 1,00 de 1,00

> Sobre o pattern de Microserviços Chain Pattern. É correto afimar que Chain or Chained Pattern se refere a uma cadeia síncrona de requisições entre serviços para atender uma necessidade específica de negócio. 
>
>Um aspecto mais importante que você precisa entender é que a solicitação do Serviço A para o Serviço B pode parecer diferente do Serviço B para o Serviço C. Da mesma forma, a resposta do Serviço C para o Serviço B pode parecer completamente diferente do Serviço B para o Serviço A.

>Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso 

> Feedback
>
>A resposta correta é 'Verdadeiro'.

### Questão 8
> Correto Atingiu 1,00 de 1,00

> Sobre o pattern API Gateway. É correto afirmar que API Gateway Pattern provê uma fachada de acesso para seus clientes. Você esconde seu negócio e só disponibiliza um entrypoint para os clientes preservando sua infra-estrutura e tendo um melhor controle no seu domínio de negócio.

>Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso 

> Feedback
>
>A resposta correta é 'Verdadeiro'.
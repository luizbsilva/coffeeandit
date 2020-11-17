# Avaliação APIs

## Questão 1

>Correto: Atingiu 2,00 de 2,00

> Selecione as alternativas corretas abaixo:: 
>  Escolha uma ou mais:

>  [✔] a. 201 Created - Indica que a requisição foi bem sucedida e um novo recurso foi criado como resultado. Esta é uma tipica resposta enviada após uma requisição POST 
>
>  [✔] b. 404 Not Found - O servidor não pode encontrar o recurso solicitado. Este código de resposta talvez seja o mais famoso devido à frequência com que acontece na web. 
>
>  [✔] c. 400 Bad Request - Essa resposta significa que o servidor não entendeu a requisição pois está com uma sintaxe inválida. 
>
>  [ ] d. 204 No Content - Estas requisição foi bem sucedida. O significado do sucesso varia de acordo com o método HTTP

> Feedback Sua resposta está correta.
> As respostas corretas são: 
>
> 01 Created - Indica que a requisição foi bem sucedida e um novo recurso foi criado como resultado. Esta é uma tipica resposta enviada após uma requisição POST., 400 Bad Request - Essa resposta significa que o servidor não entendeu a requisição pois está com uma sintaxe inválida., 404 Not Found - O servidor não pode encontrar o recurso solicitado. Este código de resposta talvez seja o mais famoso devido à frequência com que acontece na web.

## Questão 2

>Correto: Atingiu 2,00 de 2,00

> OpenAPI define um formato JSON com campos padronizados (através de um JSON Schema) para que você descreva recursos, modelo de dados, URIs, Content-Types, métodos HTTP aceitos e códigos de resposta.

> Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso

> Feedback:  A resposta correta é 'Verdadeiro'.

## Questão 3

>Correto: Atingiu 0,00 de 1,00

> Para habilitarmos o Swagger em Spring para WebFlux ou Rest é necessário colocarmos as seguintes anotações @EnableSwagger2WebFlux  e @EnableSwagger e opcionalmente configurarmos os detalhes da implementação criando um bean do tipo springfox.documentation.spring.web.plugins.Docket descrevendo os paths da API, descrições, versões e tags ao qual essas APIs irão representar.

> Escolha uma opção:

>  [ ] Verdadeiro [✔] Falso

> Feedback:  A resposta correta é 'Verdadeiro'.

## Questão 4

>Correto: Atingiu 2,00 de 2,00

> O @RestController é uma anotação de conveniência para a criação de controladores Restful,  nada mais é do que uma combinação das annotations @Controller e @ResponseBody, ou seja retorna o objeto e os dados do objeto diretamente na resposta HTTP como JSON ou XML.
>
>É uma especialização do @Component e é detectada automaticamente através da verificação do caminho de classe.

> Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso

> Feedback:  A resposta correta é 'Verdadeiro'.

### Questão 5

>Correto: Atingiu 1,00 de 1,00

> Selecione quais alternativas estão corretas abaixo:

>  [✔] a. Usamos a anotação @RequestBody para acessar o corpo da requisição HTTP ou seja o conteúdo do corpo é convertido no tipo de argumento do método declarado usando implementações como HttpMessageConverter. 
>
>  [ ] b. @RequestParam é usado para podermos acessarmos para os cabeçalhos da requisição, os valores do cabeçalho são convertidos no tipo de argumento do método declarado. 
>
>  [ ] c. @RequestHeader é usado para acessar os parâmetros de solicitação do Servlet, incluindo multipart files. Os valores dos parâmetros são convertidos no tipo de argumento do método declarado. 

> Feedback Sua resposta está correta.
> As respostas correta é: 
>
> Usamos a anotação @RequestBody para acessar o corpo da requisição HTTP ou seja o conteúdo do corpo é convertido no tipo de argumento do método declarado usando implementações como HttpMessageConverter.

### Questão 6
> Correto Atingiu 2,00 de 2,00

> Se anotarmos um método como @PostMapping para um disparo de Post é correto afirmar que essa anotação tem a mesma finalidade se anotassemos o mesmo método com  @RequestMapping(method =  RequestMethod.POST) ?

>Escolha uma opção:

>  [✔] Verdadeiro [ ] Falso 

> A resposta correta é 'Verdadeiro'.
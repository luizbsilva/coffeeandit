## Monolito x Microservices
   > O que você entende por monolito? Sabe o que é? Nesta seção mostraremos como o tipo de desenvolvimento muda do antigo estilo tradicional para o novo formato de microserviços.

## Monolito
   > Uma arquitetura monolítica típica de um sistema complexo pode ser representada pela figura abaixo, onde todas as funções do negócio estão implementadas em um único processo.

### Vantagens de um monolito
   * Fácil de desenvolver
   * Fácil manutenção
   * Apenas um deploy
   * Tráfego de rede baixo


### Problemas de um monolito
   * Aumento de complexidade e tamanho ao longo do tempo
   * Alta dependência de componentes de código
   * Escalabilidade do sistema é limitada
   * Falta de flexibilidade
   * Dificuldade para colocar alterações em produção

>O monolito tem vantagens e desvantagens. Uma das grandes desvantagens é que é muito difícil escalar o sistema. Muito comum que cada cliente que você tiver, vai ter que replicar/duplicar o servidor, isso duplicando o custo. Quando mais clientes tiver, mais servidor vai ser preciso, mais caro vai ficar.

## Microserviço
   > Russ Mile define microservice como “um serviço com um único propósito e que execute bem a sua tarefa dentro de um nível de granularidade e suporte as mudanças do sistemas que são consideradas importantes tanto em tempo de projeto quanto em tempo de execução. O foco principal é tentar construir software que pode se adaptar e isto só é possível de ser feito se as partes forem pequenas suficientes para se ajustar às diferenças nas mudanças de sua arquitetura.”

### Vantagens
   * Manutenção e evolução dos serviços mais estáveis
   * Serviços com baixo nível de acoplamento e interdependência
   * Escalabilidade do sistema
   * Redução de custos
   * Flexibilidade de tecnologia
   * Facilidade de colocar alterações em produção
   * Resiliencia
   * Aumento da produtividade
   * Implementação de entrega contínua
   * Monitoramento e automação de processos
   * Foco na entrega de valor ao cliente

### Riscos
   * Aumento da complexidade da coordenação.
   * Comunicação entre os micro serviços.
   * Governança.   
## Cloud Friendly;

> Os aplicativos cloud-friendly possuem algumas capacidades de cloud computing e para se tornarem cloud resilient ou cloud native necessitam de refatoração.
>
> Serviços Cloud-Friendly possuem as seguintes características:

* Composto por serviços vagamente acoplados, ou seja chamadas diretas entre serviços podem ocorrer usando o protocolo HTTP.
* Os serviços podem ser descobertos pelo nome, através de service discoverys como eureka, consul e outros pode-se localizar componentes.
* Os componentes são projetados para padrões de nuvem, as aplicações já olham conceitos de nuvem aonde serviços por exemplo não usam recursos de discos do nodo de computação  local.
* A computação e o armazenamento são separados, ou seja bancos de dados, caches têm-de se a ser distribuídos porém em alguns casos ocupam até o mesmo nodo computacional.

> Essa arquitetura implementa soluções de negócios (em vez de aplicativos de TI, porque os limites dos aplicativos de TI não são mais relevantes) como uma coleção coordenada de componentes autônomos.
>
> Cada componente autônomo é uma unidade de funcionalidade que pode ser executada em seu próprio processo de computação (portanto, uma unidade de implantação que pode ser implantada em um host separado em algum lugar).
>
> Em geral, os ACs são estruturalmente interdependentes, comportamentais (ou operacionalmente) independentes e dependentes contratualmente.
 
## Tornando -se Cloud-friendly;

###  Gestão de estado:

1. Um serviço de persistência (ou serviço de backup) para o estado de toda a solução (mesmo solução distribuída).
2. Estado predefinido que é criado ao incorporar o estado em uma cópia individualizada do micro serviço (mas o conhecimento em tempo de execução sobre o contexto é obrigatório).
3. Idempotência é a propriedade que algumas operações têm de poderem ser aplicadas várias vezes sem que o valor do resultado se altere após a aplicação inicial.

### Performance

>  Técnicas potenciais para melhoria de desempenho (principalmente a latência da rede):

1. Fácil mover uma cópia individualizada do microsserviço entre nós (mover um micro serviço para perto do consumidor até o dispositivo móvel).
2. Sob demanda, criando uma cópia em contêiner individual do micro serviço (mas o conhecimento em tempo de execução sobre o contexto é obrigatório).
3. Criar uma cópia individualizada do micro serviço para um consumidor específico para diminuir a sobrecarga de segurança (mas o conhecimento em tempo de execução sobre o contexto é obrigatório).

### Segurança Leve

> Estado predefinido que é criado incorporando chaves de segurança em uma cópia individualizada do micro serviço (mas o conhecimento em tempo de execução sobre o contexto é obrigatório), obtendo, assim, a auto-contenção de RBACs, scopes, roles ou profiles.
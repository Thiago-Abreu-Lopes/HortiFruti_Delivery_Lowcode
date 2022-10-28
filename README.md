
# TRABALHO FINAL - ENGENHARIA DE SOFTWARE 2021.2 - UFC Campus Sobral
## SOLUÇÃO PARA UM MERCADO/EMPRESA AFETADO PELA PANDEMIA

### SUMÁRIO
* [INTRODUÇÃO](#introdução)
* [OBJETIVO](#objetivo)
* [METODOLOGIA](#metodologia)
  * [PLANEJAMENTO](#planejamento)
  * [ORÇAMENTO](#orçamento)
  * [MODELAGEM](#modelagem)
* [RESULTADO](#resultado)
  * [PROTÓTIPO](#protótipo)
  * [TESTES](#testes)
* [CONCLUSÃO](#conclusão)

# INTRODUÇÃO
A engenharia de software é uma área da computação voltada ao desenvolvimento e manutenção de sistemas de software,  
como aplicação de tecnologia e práticas de gerência de projetos e o trabalho a seguir visa demonstrar essas habilidades  
aprendidas ao longo do semestre. 

O objetivo desse trabalho é apresentar uma solução para qualquer ramo de mercado, seja ele local, nacional ou internacional e,  
a partir disso, assumir o desenvolvimento de um software que atenda esses usuários para quantas áreas considerar relevante e viável.

O desenvolvimento do software em questão apresenta em sua etapa de metodologia todo o orçamento, planejamento e modelagem do software  
e na etapa de resultado a
apresentação de um protótipo viável para testes.


# OBJETIVO
 - Aplicar os conhecimentos em engenharia de software para modelar uma solução para um problema empresarial resultado pela pandemia.

# METODOLOGIA

A estrutura deste trabalho está subdividida em três partes: Planejamento, Orçamento e Modelagem. Em cada uma delas foram aplicados   
conceitos que viabilizem o desenvolvimento de uma solução para o problema proposto.

### PLANEJAMENTO
O primeiro passo para este projeto é estabelecer qual setor econômico será contemplado com a solução a ser desenvolvida. Foi estabelecida   
a criação de uma empresa fictícia de hortifruti que estava com problemas com o numero de vendas, dado o impedimento e seus clientes de   
deixar o ambiente domestico para efetuar comprar. Uma solução desejada pelo dono da empresa foi o desenvolvimento de um software de delivery  
para realizar a entrega de seus produtos para o cliente que faria o pedido em sua casa cumprindo os requisitos de isolamento social.

Dado o contexto a cima fez-se necessário realizar o levantamento de requisitos para o software em questão. Primeiramente estabeleceremos   
um diagrama de caso de uso para tornar evidente as funções possíveis desse software, diagrama este apresentado a seguir:

#### Figura 01:diagrama de Caso de Uso
![Caso de Uso](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/imgs%20md/Untitled.png)
#### Fonte: Criado pelos autores

Estabelecido as funcionalidades requisitadas pelo cliente podemos estabelecer alguns requisitos funcionais e não funcionais.

#### Tabela 01: Requisitos Funcionais e Não Funcionais

|Funcionais|Não Funcionais|
| -------- | -------- |
|[RF01]O Cliente deve poder visualizar todos os dados dos produtos a ser comprados|[RNF01]O aplicativo será desenvolvido na plataforma Kodular.
|[RF02] O Cliente deve poder comprar com dinheiro ou com cartão. |[RNF02]Os produtos devem ser dispostos em categorias diferentes|
|[RF03] Todos os pedidos são enviados para o WhatsApp do dono do aplicativo para que o pedido seja direcionado aos entregadores| [RNF03]O Cliente deve conseguir entrar em contato direto com o WhatsApp do administrador|

#### Fonte: Criado pelos autores

Com os requisitos estabelecidos pode-se seguir para a etapa de orçamento.

### ORÇAMENTO

O orçamento estabelecido levou em consideração os custos do processo de desenvolvimento, os impostos associados ao serviço  
e por fim o tempo estimado de produção desse software levando em consideração o nível de experiencia dos membros envolvidos.  
Os valores referentes aos tópicos acima e o valor final são apresentados na tabela abaixo:

#### Tabela 02: Calculo do Orçamento

|Referência dos Valores|Valores|
|------------------|-----------|
|Custos do Processo(luz, internet, deslocamento...)|R$200,00|
|Impostos associados|R$120,00|
|Nível de experiência dos membros envolvidos (Junior R$30,00/h) em um tempo total de 18hs de produção|R$ 1080,00|
|**VALOR TOTAL**|R$1400,00|

#### Fonte: Criado pelos autores

Tendo estabelecido o orçamento do desenvolvimento e munido da aprovação do cliente inicia-se a etapa de modelagem do produto.

### MODELAGEM

A modelagem do processo se deu através do diagrama de classes UML, pois estes mapeiam de forma clara a estrutura de um sistema   
apresentado as classes do modelo, se atributos, operações e relações. Tendo isso em conta e levando em consideração os requisitos  
apresentados pelo cliente e os requisitos levantados pela equipe de planejamento se fez viável o desenvolvimento do seguinte diagrama:

#### Figura 02:diagrama de Classes UML
![Classes UML](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/imgs%20md/Classe%20UML_page-0001.jpg)
#### Fonte: Criado pelos autores

O modelo acima apresenta as classes de usuários que engloba tanto o cliente que irá efetuar as comprar quanto o administrador do sistema   
que irá realizar os cadastros de produtos e demais serviços. 

Relaciona-se com o cliente a classe Carrinho que engloba toda a operação de verificação final dos produtos a serem comprado e da forma de   
pagamento a ser realizada enquanto que para o administrador, relaciona-se a classe Catalogo que refere-se ao processode inclusão, exclusão e   
descrição dos produtos e a classe Entregador que se refere a uma possível feature que consiga conectar diretamente o administrador   
aos entregadores, não sendo esse ultimo recurso um requisito cobrado, mas um ideia apresentado ao longo do desenvolvimento do modelo.

Finalizado o processo de modelagem inicia-se a etapa de Resultados onde serão demonstrados o protótipo do projeto juntamente   
com um feedback para o aplicativo.

# RESULTADO

### PROTÓTIPO

O processo de desenvolvimento do protótipo se deu com o uso da ferramenta Kodular, que permite que o desenvolvimento seja realizado online  
e ao fim do processo gera um arquivo em formato .apk para teste em dispositivos moveis. 

O protótipo construído é constituído pelas seguintes partes:

#### Tabela 03: Parte e Funções do Protótipo

|Parte|Função|
|------------------|-----------|
|**[PT01]Tela de Boas Vindas**|Recepção do usuário.|
|**[PT02]Tela de Produtos**|Apresenta os produtos e ofertas.|
|**[PT03]Tela de Descrição**|Apresenta a descrição do produto, preço e recebe o valor da quantidade de um determinado produto deve ser direcionado ao carrinho.|
|**[PT04]Tela de Carrinho**|Apresenta os produtos escolhidos, contabiliza a quantidade de produtos e o preço, oferece as opções de compra e permite encerrar a compra|
|**[PT05]Tela de Entrega**|Recebe as informações do usuário, como endereço e nome para que seja enviado ao administrador e este direcionar a entregas ao entregador|

#### Fonte: Criado pelos autores

###

A seguir serão apresentadas as imagens referentes a cada parte:

#### Figura 03: [PT01]Tela de Boas Vindas
![Boas Vindas](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/Arquivos%20do%20Trabalho/Imagens%20da%20Aplica%C3%A7%C3%A3o/Tela%20de%20Splash%20-%20Boas%20Vindas.png)
#### Fonte: Criado pelos autores

#### Figura 04: [PT02]Tela de Produtos
![Produtos](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/Arquivos%20do%20Trabalho/Imagens%20da%20Aplica%C3%A7%C3%A3o/Tela%20de%20Produtos%20-%20Home.png)
#### Fonte: Criado pelos autores

#### Figura 05: [PT03]Tela de Descrição
![Descrição](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/Arquivos%20do%20Trabalho/Imagens%20da%20Aplica%C3%A7%C3%A3o/Tela%20de%20Produtos%20-%20Descri%C3%A7%C3%A3o.png)
#### Fonte: Criado pelos autores

#### Figura 06: [PT04]Tela de Carrinho
![Carrinho](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/Arquivos%20do%20Trabalho/Imagens%20da%20Aplica%C3%A7%C3%A3o/Tela%20de%20Carrinho%20-%20Cesta.png)
#### Fonte: Criado pelos autores

#### Figura 07:[PT05]Tela de Entrega
![Entrega](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/Arquivos%20do%20Trabalho/Imagens%20da%20Aplica%C3%A7%C3%A3o/Tela%20de%20Carrinho%20-%20Entrega.png)
#### Fonte: Criado pelos autores

Com o protótipo finalizado inicia-se a etapa de testes com usuários e a coleta de feedbacks.

### TESTES

O aplicativo foi testado por um grupo de 10 acadêmicos de diferentes áreas de atuação, ao fim do teste foram feitos os seguintes   
questionamentos e respectivamente os seguintes resultados:

**1. Caso você fosse usuário desse aplicativo qual seu nível de satisfação com o protótipo apresentado?**

#### Gráfico 01: Referente ao questionamento 1
![Gráfico 1](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/imgs%20md/grafico%2001.png)
#### Fonte: Criado pelos autores

**2. Caso você fosse administrador de um hortifruti qual seu nível de satisfação com o protótipo apresentado?**

#### Gráfico 02: Referente ao questionamento 2
![Gráfico 2](https://github.com/Thiago-Abreu-Lopes/HortiFruti_Delivery_ES/blob/main/imgs%20md/grafico%2002.png)
#### Fonte: Criado pelos autores

**3. Quais sugestões você daria pra melhorar o protótipo apresentado?**

#### Tabela 04: Sugestões de melhorias

|[SG01] deveria haver uma tela de login para organizar as preferências dos usuários|[SG02] um sistema que mostra o status da compra, se já está saindo pra entrega e a estimativa do tempo de chegada dos produtos para o usuário|
|------------------|-----------|
|[SG03] sugiro a criação de uma tela apenas com promoções e um sistema de cupons.|[SG04] a opção de pagamento por pix|
|[SG05] sugiro a criação de uma área dedicada ao administrador para que o catalogo seja atualizado mais rapidamente.|[SG06] um sistema de avaliação dos produtos para que o feedback dos produtos e das entregas cheguem ate o dono do hortifruti|
|[SG07] uma tela de cadastro para não haver a necessidade de reinserir informações|[SG08] um sistema de cupons|

#### Fonte: Criado pelos autores

Por fim, ao concluir a etapas de testes e de feedbacks concluímos a avaliação do protótipo apresentado tendo como razoável o   
resultado dessa etapa avaliativa, além disso as sugestões apresentadas passam a ser um norte para possíveis mudanças e futuras  
implementações.

# CONCLUSÃO

O processo de desenvolvimento de softwares requer muito mais etapas do que simplesmente o processo de programação e a partir do   
trabalho apresentado foi possível entender conceitos que vão além do escopo técnico da área de engenharia de softwares.

Primeiramente, foi apresentado o processo de levantamento de requisitos que tornou permissível o entendimento das vontades do   
cliente em questão, das capacidades técnicas dos indivíduos associados à etapa de desenvolvimento e dos custos do processo de  
desenvolvimento. Além de permitir a aplicação de ferramentas como o Diagrama de Casos de Uso e Diagrama de Classes, muito comum   
no setor de desenvolvimento.

Por fim, munidos de um protótipo desenvolvido pela ferramenta Kodular foi possível enxergar o processo técnico associado à engenharia   
de software, unindo isto ao envolvimento de indivíduos que testaram o protótipo e apresentaram os devidos feedbacks, resultando, assim  
no entendimento da expectativa do usuário para com o produto final, tornando mais evidente as necessidades que deverão ser sanadas e   
implementadas do produto final.

#

## Referências

BOOCH G., RUMBAUGH J., JACOBSONI. The Unified Modeling Language User Guide. 2ª
Ed. Addison-Wesley Professional, Maio de 2005.

SOMMERVILLE Ian. Engenharia de Software. 9ªEd. Pearson Universidades, Junho de 2011.

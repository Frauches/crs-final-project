# Template para a Entrega do Projeto Final

# Estrutura de Arquivos e Pastas

A seguir é apresentada a estrutura de pastas esperada para entrega do projeto:

~~~
├── README.md  <- arquivo com o relatório do projeto
│
├── images     <- arquivos de imagens usadas no documento
│
└── resources  <- outros recursos (se houver)
~~~

Na raiz deve haver um arquivo de nome `README.md` contendo a apresentação da equipe e relatório do projeto, como detalhado na seção seguinte.

# Modelo para Apresentação da Equipe e Relatório do Projeto

Segue abaixo o modelo de como devem ser documentadas as entregas. Tudo o que for indicado entre `<...>` indica algo que deve ser substituído pelo indicado.
> Além disso, tudo o que aparecer neste modo de citação também se refere algo que deve ser substituído pelo indicado. No modelo são colocados exemplos ilustrativos, que serão substituídos pelos da sua apresentação.

Para a construção dos diagramas, devem ser usados modelos disponíveis em: [Diagramas de Referência do Projeto Final](https://docs.google.com/presentation/d/1HWiTx0HU781sf3A7sdAda_LQeMHqbvIXkh-uSRDo0Js/edit?usp=sharing). Há versões em PPT e ODT no diretório [resources/](resources/).

# Modelo para Apresentação da Equipe e Relatório do Projeto

# Projeto `CRS - Marketplace`

# Equipe
* `Daniela Bouwman Codeceira`
* `Matheus Raposo Frauches Vieira Sias`
* `Vitor Corrêa Oliveira`

# Nível 1

> Apresente aqui o detalhamento do Nível 1 conforme detalhado na especificação com, no mínimo, as seguintes subseções:

## Diagrama Geral do Nível 1

![Modelo de diagrama no nível 1](images/N1-diagrama-barramento.jpg)

### Detalhamento da interação de componentes

> O detalhamento deve seguir um formato de acordo com o exemplo a seguir:

* O componente `Leilão` inicia o leilão publicando no barramento a mensagem de tópico "`auction/{auctionId}/start`" através da interface `AuctionStart`, iniciando um leilão.
* Os componentes Loja assinam no barramento mensagens de tópico "`auction/+/start`" através da interface `AuctionEngage`. Quando recebe uma mensagem…

> Para cada componente será apresentado um documento conforme o modelo a seguir:

## Componente `<Nome do Componente>`

> Resumo do papel do componente e serviços que ele oferece.

> Diagrama do componente, conforme exemplo a seguir:

![Componente](N1-message-01.jpg)

**Interfaces**
> Listagem das interfaces do componente.

As interfaces listadas são detalhadas a seguir:

## Detalhamento das Interfaces

### Interface `FindProducts`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)

### Interface `ShowProduct`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)

### Interface `AnalyzeSearches`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)

### Interface `ReceiveOffer`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)

### Interface `CreateOffer`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)


### Interface `RequestBuy`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-02.jpg)


### Interface `CreateOrder`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-01.jpg)

### Interface `FollowOrder`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-02.jpg)

### Interface `SendOrder`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-02.jpg)

### Interface `SendPayment`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-03.jpg)

### Interface `ReceivePayment`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-03.jpg)

### Interface `Order`

> Resumo do papel da interface.

> Dados da interface podem ser apresentados em formato texto, conforme exemplo:

* Type: `sink`
* Topic: `pedido/+/entrega`
* Message type: `Order`

> Ou em formato de imagem, conforme exemplo:

![Diagrama de Interface de Mensagens](images/N1-topicos-1.jpg)
![Diagrama de Interface de Mensagens](images/N1-topicos-2.jpg)

> Diagrama representando o esquema das mensagens JSON utilizadas na interface:

![Diagrama de Mensagens JSON](images/N1-message-02.jpg)

# Nível 2

> Apresente aqui o detalhamento do Nível 2 conforme detalhado na especificação com, no mínimo, as seguintes subseções:

## Diagrama do Nível 2

> Apresente um diagrama conforme o modelo a seguir:

> ![Modelo de diagrama no nível 2](images/diagrama-subcomponentes.png)

### Detalhamento da interação de componentes

> O detalhamento deve seguir um formato de acordo com o exemplo a seguir:

* O componente `Entrega Pedido Compra` assina no barramento mensagens de tópico "`pedido/+/entrega`" através da interface `Solicita Entrega`.
  * Ao receber uma mensagem de tópico "`pedido/+/entrega`", dispara o início da entrega de um conjunto de produtos.
* Os componentes `Solicita Estoque` e `Solicita Compra` se comunicam com componentes externos pelo barramento:
  * Para consultar o estoque, o componente `Solicita Estoque` publica no barramento uma mensagem de tópico "`produto/<id>/estoque/consulta`" através da interface `Consulta Estoque` e assina mensagens de tópico "`produto/<id>/estoque/status`" através da interface `Posição Estoque` que retorna a disponibilidade do produto.

> Para cada componente será apresentado um documento conforme o modelo a seguir:

## Componente `<Nome do Componente>`

> Resumo do papel do componente e serviços que ele oferece.

![Componente](images/diagrama-componente.png)

**Interfaces**
> Listagem das interfaces do componente.

As interfaces listadas são detalhadas a seguir:

## Detalhamento das Interfaces

### Interface `<nome da interface>`

![Diagrama da Interface](images/diagrama-interface-itableproducer.png)

> Resumo do papel da interface.

Método | Objetivo
-------| --------
`<id do método>` | `<objetivo do método e descrição dos parâmetros>`

## Exemplos:

### Interface `ITableProducer`

![Diagrama da Interface](images/diagrama-interface-itableproducer.png)

Interface provida por qualquer fonte de dados que os forneça na forma de uma tabela.

Método | Objetivo
-------| --------
`requestAttributes` | Retorna um vetor com o nome de todos os atributos (colunas) da tabela.
`requestInstances` | Retorna uma matriz em que cada linha representa uma instância e cada coluna o valor do respectivo atributo (a ordem dos atributos é a mesma daquela fornecida por `requestAttributes`.

### Interface `IDataSetProperties`

![Diagrama da Interface](images/diagrama-interface-idatasetproperties.png)

Define o recurso (usualmente o caminho para um arquivo em disco) que é a fonte de dados.

Método | Objetivo
-------| --------
`getDataSource` | Retorna o caminho da fonte de dados.
`setDataSource` | Define o caminho da fonte de dados, informado através do parâmetro `dataSource`.

## Diagrama do Nível 3

> Interface de compra de um produto

![Captura de Tela do Protótipo](images/crs-marketplace-product-interface.png)

> Apresente o diagrama referente ao protótipo conforme o modelo a seguir:

![Diagrama Nivel 3](images/N3-diagrama.png)

### Detalhamento da interação de componentes

> * O componente `Retrieve Product Info` assina no barramento mensagens de tópico "`product/+/find`" através da interface `ShowProduct`.
  * Ao receber uma mensagem de tópico "`product/+/find`", dispara a busca das informações de um determinado produto.
* O componente `Purchase and Info` se comunica com componentes externos pelo barramento:
  * Para consultar o estoque e a descrição do produto, o componente `Purchase and Info` publica no barramento uma mensagem de tópico "`product/+/find`" através da interface `FindProducts` e assina mensagens de tópico "`product/{productId}/find`" através da interface `ShowProducts` que retorna a disponibilidade e descrição do produto.
  * Para a realização da compra o componente `Purchase and Info` publica no barramento uma mensagem de tópico "`product/{productId}/buy`" através da interface "CreateOrder", que cria uma ordem de compra.

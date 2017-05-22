# Web Services e APIs
## API
- A API ou Application Programming Interface é uma interface das aplicações que é voltada para outras aplicações.
![api](http://i.imgur.com/a9nwXqw.png)
## WebService
> “Web service provê uma interface de serviço que permite a clientes interagirem com servidores de uma maneira mais geral que os navegadores. Os clientes acessam as operações em uma interface de um web service por meio de requisições e respostas formatadas em XML e usualmente transmitidas sobre o protocolo HTTP." - Coulouris
![webservice](http://i.imgur.com/gWZp94s.png)
- Características Gerais
  - Utilizam o protocolo HTTP como forma de comunicação
  - Podem ser utilizados em ambientes protegidos com firewall sem a abertura de portas adicionais
  - É baseado em padrões abertos mantido pelo W3C
  - Permite interoperabilidade com diversas plataformas e linguagens
  - Oferece baixo acoplamento das aplicações
- Arquitetura - SOAP
  - SOAP – Protocolo de troca de dados baseado em XML para envio e recebimento de mensagens na Internet
  - XML – Linguagem de marcação para descrição dos dados
  - WSDL – Descritor de serviços baseado em XML
  - UDDI – Registro e descoberta de serviços
![arquitetura-api](http://i.imgur.com/A4TPwlH.png)
- SOAP 
  - Protocolo de troca de dados baseado em XML para envio e recebimento de mensagens na Internet
  - Independente de plataforma ou linguagem
  - Estrutura da Mensagem SOAP
    - Envelope
      - Define o início e o final da mensagem
      - É obrigatório
    - Header (Cabeçalho)
      - Traz atributos opcionais da mensagem utilizada para o seu processamento
      - É opcional
    - Body (Corpo)
      - Possui o conteúdo da mensagem em formato XML
      - É obrigatório
  - Web Services Description Language (WSDL)
    - Linguagem de descrição de um web service baseada em XML
    - Define os seguintes objetos:
      - Tipos de dados suportados pelo serviço
      - Padrão de mensagens de entrada e saída
      - Protocolos de comunicação permitidos pelo Web Service (binding)
      - Serviços e portas de comunicação onde operações são disponibilizadas pelo Web Service
      - Definições sobre schemas e namespaces utilizados no contexto do Web Service
      ![wsdl](http://i.imgur.com/hLetuRU.png)
  - Universal Description and Discovery Interface (UDDI)
    - Serviço de diretório que mantem referência para os Web Services registrados
    - Funcionam como páginas amarelas para localização dos Web Services
    - Reúne informações como:
      - Nomes endereços e números de telefones dos fornecedores de serviços
      - Serviços oferecidos por cada fornecedor, bem como informações técnicas sobre a interface de cada um
  - Universal Description and Discovery Interface (UDDI)
    - Serviço de diretório que mantem referência para os Web Services registrados
    - Funcionam como páginas amarelas para localização dos Web Services
    - Reúne informações como:
      - Nomes endereços e números de telefones dos fornecedores de serviços
      - Serviços oferecidos por cada fornecedor, bem como informações técnicas sobre a interface de cada um
-SOA (Service Oriented Architecture)
  - Estilo de arquitetura de software cujo princípio fundamental está baseado em funcionalidades implementadas por aplicação e disponibilizadas na forma de serviços.
  - Camadas
    - Interface de Usuário
    - Processos de Negócios
    - Serviços
    - Componentes de Serviços
    - Sistemas Operacionais
    ![soa-camadas](http://i.imgur.com/eHTc9DW.png)
- REST - REpresentational State Transfer
  - é um estilo arquitetural para construção de web services escaláveis que define um conjunto de regras
  - Regras REST
    - Cliente e Servidor
    - Sem Estado (stateless)
    - Interface Uniforme
    - Permite cache (cacheable)
    - Sistema em camadas
  - Regras REST – Cliente e Servidor
    - O cliente se preocupa com a apresentação para o cliente e o estado da aplicação
    - O servidor se preocupa com o armazenamento dos dados e a lógica do negócio
    - Benefícios
      - Portabilidade da interface de usuário (Desktop, Mobile, API)
      - Escalabilidade (Múltiplos servidores e clientes)


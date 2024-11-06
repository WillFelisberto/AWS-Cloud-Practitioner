# Sumário

- [Certificação AWS Cloud Practitioner](#certificação-aws-cloud-practitioner)
  - [Tópicos](#tópicos)
  - [Sobre a prova ](#sobre-a-prova)
  - [Módulo 1 - Introdução à Amazon Web Services](#módulo-1---introdução-à-amazon-web-services)
  - [Módulo 2 - Computação em nuvem](#módulo-2---computação-em-nuvem)
  - [Módulo 3 - Infraestrutura global e confiabilidade](#módulo-3---infraestrutura-global-e-confiabilidade)
      - [Acesso](#acesso)
  - [Módulo 4 - Redes](#módulo-4---redes)
      - [Amazon Virtual Private Cloud ou Amazon VPC](#amazon-virtual-private-cloud-ou-amazon-vpc)
      - [Gateway de internet](#gateway-de-internet)
      - [Gateway privado virtual](#gateway-privado-virtual)
      - [AWS Direct Connect](#aws-direct-connect)
      - [Sub-redes](#sub-redes)
      - [ACLs de rede - (Access Control List)](#acls-de-rede---access-control-list)
      - [Grupos de segurança](#grupos-de-segurança)
      - [Redes globais](#redes-globais)
        - [Sistema de nomes de domínio (DNS)](#sistema-de-nomes-de-domínio-dns)
        - [Amazon Route 53](#amazon-route-53)
      - [Amazon CloudFront](#amazon-cloudfront)
  - [Módulo 5 - Armazenamento e banco de dados](#módulo-5---armazenamento-e-banco-de-dados)
      - [Armazenamentos de instância ](#armazenamentos-de-instância)
      - [Amazon Elastic Block Store (Amazon EBS)](#amazon-elastic-block-store-amazon-ebs)
      - [Amazon Simple Storage Service (Amazon S3)](#amazon-simple-storage-service-amazon-s3)
      - [Amazon Elastic File System (Amazon EFS)](#amazon-elastic-file-system-amazon-efs)
      - [Amazon Relational Database Service (Amazon RDS)](#amazon-relational-database-service-amazon-rds)
        - [Amazon Aurora](#amazon-aurora)
      - [Amazon DynamoDB](#amazon-dynamodb)
      - [Amazon Redshift](#amazon-redshift)
      - [AWS Database Migration Service (AWS DMS)](#aws-database-migration-service-aws-dms)
      - [Neptune](#neptune)
      - [Relational Database Service - RDS](#relational-database-service---rds)
      - [Amazon DocumentDB](#amazon-documentdb)
  - [Módulo 6 - Segurança](#módulo-6---segurança)
      - [Modelo de responsabilidade compartilhada da AWS](#modelo-de-responsabilidade-compartilhada-da-aws)
      - [AWS Identity and Access Management (IAM)](#aws-identity-and-access-management-iam)
        - [Usuário-raiz da conta AWS](#usuário-raiz-da-conta-aws)
      - [Usuários do IAM](#usuários-do-iam)
      - [Políticas do IAM](#políticas-do-iam)
      - [Grupos do IAM](#grupos-do-iam)
      - [Perfis do IAM](#perfis-do-iam)
    - [AWS Organizations](#aws-organizations)
      - [Unidades organizacionais](#unidades-organizacionais)
    - [Conformidade](#conformidade)
      - [AWS Artifact](#aws-artifact)
      - [Centro de conformidade para o cliente](#centro-de-conformidade-para-o-cliente)
    - [Ataques de negação de serviço](#ataques-de-negação-de-serviço)
    - [Ataques distribuídos de negação de serviço](#ataques-distribuídos-de-negação-de-serviço)
    - [AWS Shield](#aws-shield)
    - [AWS Key Management Service (AWS KMS)](#aws-key-management-service-aws-kms)
    - [AWS WAF](#aws-waf)
    - [Amazon Inspector](#amazon-inspector)
    - [Amazon GuardDuty](#amazon-guardduty)
  - [Módulo 7: Monitoramento e Análise](#módulo-7-monitoramento-e-análise)
      - [Amazon CloudWatch](#amazon-cloudwatch)
      - [AWS CloudTrail](#aws-cloudtrail)
        - [CloudTrail Insights](#cloudtrail-insights)
      - [AWS Trusted Advisor](#aws-trusted-advisor)
  - [Módulo 8 - Definição de preços e suporte](#módulo-8---definição-de-preços-e-suporte)
    - [Nível gratuito da AWS](#nível-gratuito-da-aws)
      - [Três tipos de ofertas estão disponíveis:](#três-tipos-de-ofertas-estão-disponíveis)
    - [Sempre gratuito](#sempre-gratuito)
    - [12 meses gratuitos](#12-meses-gratuitos)
    - [Versão de testes](#versão-de-testes)
    - [Conceitos de definição de preço da AWS](#conceitos-de-definição-de-preço-da-aws)
    - [Calculadora de Preços da AWS](#calculadora-de-preços-da-aws)
    - [Cobrança consolidada](#cobrança-consolidada)
    - [AWS Budgets](#aws-budgets)
    - [AWS Cost Explorer](#aws-cost-explorer)
    - [AWS Support](#aws-support)
    - [AWS Marketplace](#aws-marketplace)
  - [Módulo 9: Migração e Inovação](#módulo-9---migração-e-inovação)
    - [AWS Cloud Adoption Framework (AWS CAF)](#aws-cloud-adoption-framework-aws-caf)
    - [Seis estratégias de migração](#seis-estratégias-de-migração)
    - [AWS Snow Family](#aws-snow-family)
    - [Amazon SageMaker](#amazon-sagemaker)
    - [Amazon CodeWhisperer](#amazon-codewhisperer)
  - [Módulo 10: A jornada para a nuvem](#módulo-10---a-jornada-para-a-nuvem)
    - [AWS Well-Architected Framework](#aws-well-architected-framework)
    - [Vantagens da computação em nuvem](#vantagens-da-computação-em-nuvem)

<hr>


# Certificação AWS Cloud Practitioner
Compilado de todas as anotações que fiz durante o estudo para tirar a certificação **[AWS Certified Cloud Practitioner](https://aws.amazon.com/pt/certification/certified-cloud-practitioner).**
<hr>

## Tópicos

| Domínio                                 | Porcentagem do exame |
|-----------------------------------------|-----------------------|
| Domínio 1: Conceitos de nuvem           | 26%                  |
| Domínio 2: Segurança e conformidade     | 25%                  |
| Domínio 3: Tecnologia                   | 33%                  |
| Domínio 4: Faturamento e definição de preço | 16%             |
| **Total**                               | **100%**             |

### Domínio 1: Conceitos de Nuvem
1.1 Definir a AWS Cloud e sua proposta de valor  
1.2 Identificar aspectos econômicos da AWS Cloud  
1.3 Listar os diferentes princípios de design de arquitetura em nuvem  

### Domínio 2: Segurança e Conformidade
2.1 Definir o modelo de responsabilidade compartilhada da AWS  
2.2 Definir os conceitos de segurança e conformidade da AWS Cloud  
2.3 Identificar as capacidades de gerenciamento de acesso da AWS  
2.4 Identificar recursos de suporte à segurança  

### Domínio 3: Tecnologia
3.1 Definir métodos de implantação e operação na AWS Cloud  
3.2 Definir a infraestrutura global da AWS  
3.3 Identificar os serviços principais da AWS  
3.4 Identificar recursos para suporte tecnológico  

### Domínio 4: Faturamento e Definição de Preço
4.1 Comparar e contrastar os vários modelos de precificação da AWS  
4.2 Reconhecer as diversas estruturas de conta em relação ao faturamento e preços da AWS  
4.3 Identificar recursos disponíveis para suporte de faturamento  


<hr>

## Sobre a prova 

* A Prova vale de 0 a 1000 pontos, para ganhar o certificado, você deve tirar a cima de 700 pontos

* Os pesos estão listados a cima

* São questões de multipla escolha e escolha múltipla

* A prova é assistida por um instrutor da AWS

<hr>

## Módulo 1 - Introdução à Amazon Web Services

Cloud computing (Computação em nuvem), empresas de grande poder de compra que alugam seus data centers para terceiros, onde provem serviços já configurados para o consumidor final, como backup, processamento sob demanda, etc. Então o usuário que precise de serviços de computação, não precisa mais comprar seu servidor e manter localmente, nem tenha que fazer upgrade físico toda vez que precise aumentar recursos, tudo se torna mais fácil.

É a entrega sob demanda (on demand) de recursos de computação, banco de dados, armazenamento, aplicações ou qualquer outro recurso de tecnologia que é entregue através de uma plataforma via internet, onde o pagamento e preço é baseado em consumo (pay as you go).

**Vantagens**

*  **Mudança na modalidade gastos**: muda da modalidade de despesas de capital, [CAPEx](https://pt.wikipedia.org/wiki/CAPEX), para modelo de despesa variável, [OPEx](https://pt.wikipedia.org/wiki/OPEX).

*  **Economia de escala**: com a computação em nuvem, você pode chegar a um custo variável menor do que seria possível por conta própria. Como o uso de centenas de milhares de clientes é agregado na nuvem, os fornecedores como a AWS podem ter maiores economias em escala, o que se converte em um menor preço pago conforme o uso.

*  **Capacidade**: você cresce ou diminui a capacidade necessária para atender suas demandas, pagando apenas o que consumir. 
*  **Agilidade e velocidade**: recursos estão disponíveis imediatamente.
*  **Economia**: você deixa de gastar dinheiro para comprar e manter data centers.
*  **Global em poucos minutos**: permite que você tenha recursos disponíveis globalmente em poucos minutos com baixa latência e custo, melhorando a experiência do cliente.


## Módulo 2 - Computação em nuvem
**Auto Scaling**
O [Auto Scaling](https://aws.amazon.com/pt/autoscaling) é um serviço que monitora os aplicativos e ajusta automaticamente a capacidade para manter um desempenho constante e previsível pelo menor custo possível.

**Lambda**
O [Lambda](https://aws.amazon.com/pt/lambda) é um serviço de computação sem servidor e orientado a eventos que permite executar código para praticamente qualquer tipo de aplicação ou serviço de backend sem provisionar ou gerenciar servidores.  

Lambda functions é um microsserviço (código) que roda na plataforma do AWS Lambda baseado em eventos, também conhecido como Function as a Service - FaaS.

**Fargate**
O [Fargate](https://aws.amazon.com/pt/fargate) é um mecanismo de computação sem servidor para contêineres. Ele funciona com o Amazon ECS e o Amazon EKS. Ao usar o Fargate, você não precisa provisionar ou gerenciar servidores. O AWS Fargate gerencia sua infraestrutura de servidor para você.

**Elastic BeanStalk**
O [Elastic BeanStalk](https://aws.amazon.com/pt/elasticbeanstalk) é um serviço que permite a implantação de aplicações apenas fornecendo o código fonte, sem conhecimento ou definição prévia da infraestrutura.

**Elastic Compute Cloud - EC2**
O [EC2](https://aws.amazon.com/pt/ec2) é um serviço web que disponibiliza capacidade computacional segura e redimensionável na nuvem.

**Características**
* Máquina virtual.
* Windows/Linux.
* Baixo custo.
* Configurações e tamanhos variados.
* Seguro.
* Escalável.


* Usado para Big data, ERP, e-commerce e outros.
  
**Modalidade de gastos**

|  Modalidade   |    Características                                                                                                                     |
|     :---      |       :---                                                                                                                             |
| `Spot` |  - Leilão. <br> - O cliente define um preço a pagar pela capacidade ociosa da AWS, se o preço é aceito, a instância é provisionada.    |
| `Dedicado` |  - Servidor dedicado. <br> - Preços por hora. <br> - Descontos de até 70%.                                                             |
| `Reservada` |  - Reserva por 01 ou 03 anos. <br> - Descontos de até 75%. <br> - Pagamento à vista, ou com entrada e o restante pago em mensalidades. |
| `On demand` |  - Sob demanda. <br> - Pay as you go. <br> - Preços por hora.                                                                          |

**Tipos de instância**

Os tipos de instância EC2 são otimizados para tarefas diferentes.

|  Tipos                            |    Características                                                                                                                                         |
|     :---                          |       :---                                                                                                                                                 |
| `Uso geral` |  Fornecem um equilíbrio de recursos de computação, memória e rede.                                                                                         |
| `Computação acelerada` |  Usam aceleradores de hardware, ou coprocessadores, para executar algumas funções de forma mais eficiente do que é possível no software executado em CPUs. |
| `Otimizada para memória` |  São projetadas para fornecer rápida performance para cargas de trabalho que processam grandes conjuntos de dados na memória.                              |
| `Otimizada para computação` |  São ideais para aplicações vinculadas à computação que se beneficiam de processadores de alta performance.                                                |
| `Otimizada para armazenamento` |  São projetadas para cargas de trabalho que exigem alto acesso sequencial de leitura e gravação a grandes conjuntos de dados no armazenamento local.       |


**Elastic Load Balancing - ELB**
O [ELB](https://aws.amazon.com/pt/elasticloadbalancing) é um serviço que distribui automaticamente o tráfego de aplicações de entrada entre vários destinos e dispositivos virtuais em uma ou mais zonas de disponibilidade (AZ).

**Elastic Container Service - ECS**
O [ECS](https://aws.amazon.com/pt/ecs) é um serviço de orquestração de contêineres totalmente gerenciado que facilita a implantação, o gerenciamento e a escala de aplicações em contêineres.

**Elastic Kubernetes Service - EKS**
O [EKS](https://aws.amazon.com/pt/eks) é um serviço de contêiner gerenciado para executar e escalar aplicações do Kubernetes na nuvem ou on-premises.

## Módulo 3 - Infraestrutura global e confiabilidade

A [infraestrutura global da AWS](https://aws.amazon.com/pt/about-aws/global-infrastructure) é uma plataforma de nuvem e oferece mais de 200 serviços completos de datacenters em todo o mundo. 

*  **Regiões (Regions)**: são as localidades físicas onde a AWS está disponível ao redor do mundo.
*  **Zonas de disponibilidades (Availability Zone - AZ)**: é a quantidade de datacenter que a AWS tem em cada uma das regiões para prover serviços e produtos. No mínimo são duas zonas de disponibilidade por região, a fim de proporcionar alta disponibilidade, tolerância a falhas e escalabilidade.
*  **Pontos de presença (Edge locations)**: uma edge location é basicamente um pequeno servidor de cache. Eles estão localizados na maioria das principais cidades do mundo e são usados especificamente pelo CloudFront (CDN) para distribuir conteúdo ao usuário final e reduzir a latência do acesso. 
#### Acesso
*  **Management Console**: interface gráfica com suporte para a maioria dos serviços da AWS. Pode ser usada via navegador ou aplicativo.
*  **Command Line Interface - CLI**: acesso aos serviços via linha de comando.
*  **Software Development Kit - SDK**: suporta diversas linguagens de programação e permite a incorporação de serviços AWS em aplicações.

  

## Módulo 4 - Redes
#### **Amazon Virtual Private Cloud ou Amazon VPC**
O Amazon VPC permite que você provisione uma seção isolada da nuvem AWS. Nessa seção isolada, você pode executar os recursos em uma rede virtual que definir. Em uma Virtual Private Cloud (VPC), você pode organizar seus recursos em sub-redes. Uma sub-rede é uma seção de uma VPC que pode conter recursos como instâncias do Amazon EC2.

#### Gateway de internet
Para permitir que o tráfego público da internet acesse sua VPC, é preciso anexar um gateway de internet à **VPC**.
Um gateway da internet é uma conexão entre uma VPC e a internet. Você pode pensar em um gateway da internet como sendo semelhante a uma porta que os clientes usam para entrar na cafeteria. Sem um gateway da internet, ninguém pode acessar os recursos em sua VPC.

#### Gateway privado virtual
O gateway privado virtual é o componente que permite que o tráfego protegido da internet ingresse na **VPC**. Mesmo que sua conexão com a cafeteria tenha proteção extra, os engarrafamentos são possíveis porque você usa o mesmo caminho que outros clientes.

#### AWS Direct Connect
O [AWS Direct Connect](https://aws.amazon.com/directconnect/) é um serviço que permite estabelecer uma conexão privada dedicada entre seu data center e uma **VPC**, A conexão privada do **AWS Direct Connect** ajuda a reduzir os custos de rede e a aumentar a quantidade de largura de banda que pode trafegar pela rede.

#### Sub-redes
Uma sub-rede é uma seção de uma **VPC** na qual você pode agrupar recursos com base em necessidades operacionais ou de segurança. As sub-redes podem ser públicas ou privadas.

 - **Sub-redes públicas**: contêm recursos que precisam ser acessíveis ao público, como o site de uma loja on-line.
 - **Sub-redes privadas**: contêm recursos que devem ser acessíveis apenas pela sua rede privada, como um banco de dados que contém informações pessoais dos clientes e históricos de pedidos. 

Em uma VPC, as sub-redes podem se comunicar entre si. Por exemplo, um aplicativo que envolve instâncias do Amazon EC2 em uma sub-rede pública que se comunicam com bancos de dados localizados em uma sub-rede privada.

#### ACLs de rede - (Access Control List)
Uma ACL de rede é um firewall virtual que controla o tráfego de entrada e saída no nível de sub-rede.
As ACLs de rede executam a filtragem de pacotes **stateless**. Elas não se lembram de nada e verificam os pacotes que atravessam a fronteira da sub-rede em todos os sentidos: entrada e saída. 
Por padrão, a ACL-padrão de rede da conta permite todo o tráfego de entrada e saída, mas você pode adicionar suas regras
#### Grupos de segurança

Um grupo de segurança é um firewall virtual que controla o tráfego de entrada e saída de uma instância do Amazon EC2.
Por padrão, um grupo de segurança nega todo o tráfego de entrada e permite todo o tráfego de saída. Você pode adicionar regras personalizadas para configurar o tráfego que será permitido.
**StateFull** - Eles se lembram de decisões anteriores tomadas para pacotes recebidos.

#### Redes globais
##### **Sistema de nomes de domínio (DNS)**
##### Amazon Route 53
O [**Amazon Route 53**](https://aws.amazon.com/route53) é um serviço da web de DNS. Oferece aos desenvolvedores e empresas uma maneira confiável de rotear os usuários finais para aplicativos da internet hospedados na AWS.

#### **Amazon CloudFront**
Rede de entrega de conteúdo

## Módulo 5 - Armazenamento e banco de dados

#### Armazenamentos de instância 
Um [**armazenamento de instância**](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html) é um meio temporário de armazenamento a nível de bloco para uma instância do Amazon EC2. Um armazenamento de instância é o armazenamento em disco fisicamente anexo ao computador host para uma instância do EC2 e, portanto, tem a mesma vida útil da instância. Quando a instância for terminada, você perderá todos os dados no armazenamento de instância.

#### Amazon Elastic Block Store (Amazon EBS)
O  [**Amazon Elastic Block Store (Amazon EBS)**](https://aws.amazon.com/ebs)  é um serviço que fornece volumes de armazenamento a nível de bloco que você pode usar com instâncias do Amazon EC2. Se você interromper ou terminar uma instância do Amazon EC2, todos os dados no volume do EBS anexo permanecerão disponíveis.

Para criar um volume do EBS, defina a configuração (como tamanho e tipo do volume) e a provisão. Depois de criado, o volume do EBS pode ser anexado a uma instância do Amazon EC2.

Diversos tamanhos e tipos.

**Snapshots**: Backup incremental do EBS, Isso significa que o primeiro backup de um volume copia todos os dados. Nos backups subsequentes, somente os blocos de dados que foram alterados desde o snapshot mais recente são salvos.

#### Amazon Simple Storage Service (Amazon S3)

 - Armazene dados como objetos
 - Armazene dados em buckets
 - Tamanho máximo de 5 TB
 - Versionamento de objetos
 - Possível criar diversos buckets 
 
 Para criar um bucket, o nome do bucket deve:
-   Ser único em todo o Amazon S3.
-   Ter entre 3 e 63 caracteres.
-   Não possuir caracteres maiúsculos.
-   Começar com uma letra minúscula ou um número.

**Classes de armazenamento**  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html):

-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Standard - Uso geral(o que vimos até aqui)
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Infrequent Access(IA) - para arquivos pouco utilizados
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  One Zone Infrequent Access - para arquivos pouco utilizados que podem ser recriados ou que não são críticos, pois existe risco de perda.
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Intelligent Tiering - Sistema inteligente que determina para qual tipo de classe seus buckets devem ir.
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Glacier - Para armazenamento de arquivos mortos e backups.
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Glacier Deep Archive - Para armazenamento de arquivos mortos e backups que você entende que ficarão muito tempo sem serem lidos(estilo aqueles que acumularão poeira e teia de aranha no porão).
-   [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Reduced Redudancy Storage(RRS) -  **Depreciado**  - Sistema legado que não será solicitado no exame.

Conceitos e Garantias da AWS:

-   Durabilidade:
-   A AWS garante que o  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  manterá 99,999999999% (11 9s) dos objetosentreas AZs. Isso significa que em média existe o risco de você perder um objetoacada 10000 anos. Esta regra é válida para todas as classes.
-   Disponibilidade
-   A medida de o quão disponível o  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  é.
-   A AWS garante que o  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  estará disponível em 99,99% do tempo, o quesignifica que ela assume uma indisponibilidade de até 53 minutos por ano.Essagarantia varia de acordo com a classe  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html).

[**S3**](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  **Standard**:

-   Disponibilidade de 99,99%
-   Usado para dados acessados frequentemente.
-   Baixa latência e alta taxa de transferência.
-   Suporta falha de até 2 instalações(facilities) simultaneamente.

Usado para: Big Data Analytics, mobile, gaming, distribuição de conteúdos, etc...

**S3 Standard - Infrequent Access (IA)**

-   Para arquivos pouco acessados mas que precisam de uma latência rápida, quando acessados.
-   Disponibilidade de 99,9%
-   Custo menor, se comparado com  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  Standard, porém, há um custo maior por acesso.
-   Suporta falha de até 2 instalações(facilities) simultaneamente. Usado para: Data store para recuperação de desastres, backups, etc...

**S3 Intelligent-Tiering**

-   Disponibilidade de 99,9%
-   Mesma baixa latência e alta performance de taxa de transferência do  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  standard.
-   Otimizado para custar menos pois automaticamente move objetos entre as outras 2 classes  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)(acesso frequênte/infrequênte) baseado em padrões de acesso.

Usado para: Resiliência de eventos que impactem diretamente a AZ. Sistemas que exijam comprovantes, como compras que são muito acessados nas primeiras semanas após serem gerados e cada vez menos ao longo do tempo.

**S3 One Zone - Infrequent Access (IA)**

-   Igual ao IA, contudo, desta vez, armazenado em uma única AZ.
-   99,5% de disponibilidade.
-   Baixa latência e alta performance de taxa de transferência.
-   Baixo custo se comparado com  [S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)-IA (cerca de 20%) Usado para: Armazenamento de backups secundários de dados on-premisse, dados que podem ser recriados, thumbs, etc...

**S3 Glacier e Glacier Deep Archive**

-   Armazenamento de backups para períodos longos.
-   Custo alto para obter esses dados, uma vez armazenados.
-   Custo baixo para armazenar os dados.
-   Amazon Glacier - barato:
-   Consulta expedited - 1 a 5 minutos
-   Consulta standard - 3 a 5 horas
-   Consulta Bulk - 5 a 12 horas
-   Amazon Glacier Deep Archive - O mais barato:
-   Consulta Standard - 12 horas
-   Consulta Bulk - 48 horas

#### Amazon Elastic File System (Amazon EFS)
[**O Amazon Elastic File System (Amazon EFS)**](https://aws.amazon.com/efs/) é um sistema de arquivos dimensionável usado com os AWS Cloud Services e recursos on-premises. À medida que você adiciona e remove arquivos, o Amazon EFS expande e retrai automaticamente. Ele pode dimensionar sob demanda para petabytes sem interromper os aplicativos.

#### Amazon Relational Database Service (Amazon RDS)
[**O Amazon Relational Database Service (Amazon RDS)**](https://aws.amazon.com/rds/) é um serviço que permite executar bancos de dados relacionais na nuvem AWS.

**Mecanismos de banco de dados do Amazon RDS**

O Amazon RDS está disponível em seis mecanismos de banco de dados, que otimizam memória, desempenho ou entrada/saída (E/S). Os mecanismos de banco de dados compatíveis são:

-   Amazon Aurora
-   PostgreSQL
-   MySQL
-   MariaDB
-   Oracle Database
-   Microsoft SQL Server

##### **Amazon Aurora**
O [**Amazon Aurora**](https://aws.amazon.com/rds/aurora/) é um banco de dados relacional de nível empresarial. É compatível com os bancos de dados relacionais MySQL e PostgreSQL. É até cinco vezes mais rápido do que os bancos de dados MySQL comuns e até três vezes mais rápido do que os bancos de dados PostgreSQL comuns.

#### Amazon DynamoDB
O [**Amazon DynamoDB**](https://aws.amazon.com/dynamodb/) é um serviço de banco de dados de chave-valor. Ele oferece um desempenho de um dígito de milissegundo em qualquer scaling. **Não relacional**.

#### Amazon Redshift
[**O Amazon Redshift**](https://aws.amazon.com/redshift) é um serviço de data warehouse que você pode usar para análise de Big Data. Ele oferece a capacidade de coletar dados de muitas fontes além de ajudar a entender relações e tendências em todos os seus dados.

#### AWS Database Migration Service (AWS DMS)

O [**AWS Database Migration Service (AWS DMS)**](https://aws.amazon.com/dms/) permite migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados.

Com o AWS DMS, você move dados entre bancos de dados de origem e de destino. [Os bancos de dados de origem e de destino](https://aws.amazon.com/dms/resources) podem ser do mesmo tipo ou de tipos diferentes. Durante a migração, o banco de dados de origem permanece operacional, reduzindo o tempo de inatividade em qualquer aplicativo que dependa do banco de dados.

#### **Neptune**

O  [Neptune](https://aws.amazon.com/pt/neptune)  é um serviço de banco de dados gráfico rápido, confiável e totalmente gerenciado que facilita a criação e a execução de aplicativos.

#### **Relational Database Service - RDS**

O  [RDS](https://aws.amazon.com/pt/rds)  é um serviço de banco de dados relacional gerenciado, escalável e de alta disponibilidade. O RDS oferece seis mecanismos de bancos de dados comuns, incluindo Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database e SQL Server.

#### Amazon DocumentDB

O  [**Amazon DocumentDB**](https://aws.amazon.com/documentdb)  é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB. (MongoDB é um programa de banco de dados de documentos.)


## Módulo 6 - Segurança

#### Modelo de responsabilidade compartilhada da AWS
O modelo de responsabilidade compartilhada divide-se em responsabilidades do cliente (chamadas de “segurança na nuvem”) e responsabilidades da AWS (chamadas de “segurança da nuvem”).

#### AWS Identity and Access Management (IAM)

O  [**AWS Identity and Access Management (IAM)**](https://aws.amazon.com/iam/)  permite que você gerencie o acesso aos serviços e recursos da AWS com segurança.

O IAM oferece a flexibilidade de configurar o acesso com base nas necessidades operacionais e de segurança específicas da sua empresa. Você pode fazer isso usando uma combinação dos recursos do IAM, que vamos conhecer melhor nesta lição:

-   Usuários, grupos e perfis do IAM
-   Políticas do IAM
-   Autenticação multifator

##### **Usuário-raiz da conta AWS**
Ao criar uma conta AWS pela primeira vez, você começa com uma identidade conhecida como  [**usuário-raiz**](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html).

O usuário-raiz é acessado ao entrar com o endereço de e-mail e a senha usados para criar a conta AWS. Pense no usuário-raiz como sendo parecido com o proprietário da cafeteria: Ele tem acesso completo a todos os serviços e recursos AWS na conta.
**não use o usuário-raiz para tarefas cotidianas**

#### Usuários do IAM

Um **usuário do IAM** é uma identidade que você cria na AWS. Ele representa a pessoa ou o aplicativo que interage com os serviços e recursos AWS. Consiste em um nome e credenciais.

Por padrão, ao criar um novo usuário do IAM na AWS, não há permissões associadas a ele. Para permitir que o usuário do IAM execute ações específicas na AWS, como iniciar uma instância do Amazon EC2 ou criar um bucket do Amazon S3, você deve conceder ao usuário do IAM as permissões necessárias.

recomendamos que crie usuários individuais do IAM para cada pessoa que precisa acessar a AWS.

#### Políticas do IAM

Uma **política do** **IAM** é um documento que concede ou nega permissões para serviços e recursos AWS.

As políticas do IAM permitem que você personalize os níveis de acesso dos usuários aos recursos. Por exemplo, você pode permitir que os usuários acessem todos os buckets do Amazon S3 em sua conta AWS ou apenas um bucket específico.

siga o princípio de segurança de  **menor privilégio**  ao conceder permissões.

#### Grupos do IAM

Um grupo do IAM é um conjunto de usuários do IAM. Quando você atribui uma política do IAM a um grupo, todos os usuários do grupo recebem permissões especificadas pela política.

#### Perfis do IAM
Um perfil do IAM é uma identidade que você pode assumir para obter acesso temporário a permissões.

Antes que um usuário, aplicação ou serviço do IAM possa assumir um perfil do IAM, ele precisa receber permissões para alternar para o perfil. Quando alguém assume uma função do IAM, ele abandona todas as permissões anteriores que tinha em uma função anterior e assume as permissões da nova função.


### AWS Organizations
No AWS Organizations, você pode controlar de maneira centralizada as permissões para as contas em sua organização usando as [**políticas de controle de serviço (SCPs)**](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps.html). As SCPs permitem que você coloque restrições nos serviços AWS, recursos e ações individuais de API que os usuários e funções em cada conta podem acessar.

#### Unidades organizacionais
No AWS Organizations, você pode agrupar contas em unidades organizacionais (UO) para facilitar o gerenciamento de contas com requisitos de negócios ou segurança semelhantes. Ao aplicar uma política a uma UO, todas as contas na UO herdam automaticamente as permissões especificadas na política.


### Conformidade

#### AWS Artifact

O [**AWS Artifact**](https://aws.amazon.com/artifact) é um serviço que concede acesso sob demanda a relatórios de segurança e conformidade da AWS e a contratos on-line selecionados. O AWS Artifact consiste em duas seções principais: AWS Artifact Agreements e o AWS Artifact Reports.

 - **AWS Artifact Agreements**: No AWS Artifact Agreements, você pode ver, aceitar e gerenciar contratos para uma conta individual e para todas as suas contas no AWS Organizations. Diferentes tipos de acordos são oferecidos para atender às necessidades dos clientes sujeitos a regulamentações específicas, como a Lei de Portabilidade e Responsabilidade dos Provedores de Saúde dos EUA (HIPAA).
 - **AWS Artifact Reports**:O AWS Artifact Reports oferece relatórios de conformidade por auditores terceirizados. Esses auditores testaram e verificaram se a AWS está em conformidade com diversas normas e regulamentações de segurança globais, regionais e específicas do setor. O AWS Artifact Reports se mantém atualizado com os relatórios publicados mais recentes. Você pode fornecer os artefatos de auditoria da AWS aos auditores ou reguladores como evidência dos controles de segurança da AWS.

#### Centro de conformidade para o cliente

O centro de conformidade para o cliente contém recursos que ajudam você a saber mais sobre a conformidade da AWS. 

No centro de conformidade para o cliente, você pode ler histórias de conformidade dos clientes para descobrir como as empresas de setores regulamentados resolveram vários desafios de conformidade, governança e auditoria.

### Ataques de negação de serviço
Um ataque de negação de serviço (DoS) é uma tentativa deliberada de tornar um site ou aplicação indisponível para os usuários.

### Ataques distribuídos de negação de serviço

Em um ataque distribuído de negação de serviço (DDoS), várias origens são usadas para iniciar um ataque que visa tornar um site ou aplicação indisponível. O ataque pode ser feito por um grupo de invasores, ou até mesmo um único invasor. O único invasor pode usar vários computadores infectados (também conhecidos como “bots”) para enviar tráfego excessivo a um site ou aplicação.

Para ajudar a minimizar o efeito de ataques DoS e DDoS em suas aplicações, você pode usar o  [**AWS Shield**](https://aws.amazon.com/shield).

### AWS Shield
  
O AWS Shield é um serviço que protege aplicações contra ataques DDoS. O AWS Shield oferece dois níveis de proteção: **Standard** e **Advanced**.

 - **AWS Shield Standard**: O  **AWS Shield Standard**  protege automaticamente todos os clientes AWS sem nenhum custo. Ele protege seus recursos AWS contra os tipos de ataques DDoS mais comuns e frequentes.
 -**AWS Shield Advanced**: O  **AWS Shield Advanced**  é um serviço pago que fornece diagnósticos detalhados de ataques e a capacidade de detectar e mitigar ataques elaborados de DDoS.

### **AWS Key Management Service (AWS KMS)**

O [**AWS Key Management Service (AWS KMS)**](https://aws.amazon.com/kms) permite que você execute operações de criptografia usando **chaves de criptografia**. Uma chave de criptografia é uma cadeia aleatória de dígitos usada para bloquear (criptografar) e desbloquear (descriptografar) dados. Você pode usar o AWS KMS para criar, gerenciar e usar chaves de criptografia. Você também pode controlar o uso de chaves em uma ampla gama de serviços e em suas aplicações.

### AWS WAF

O  [**AWS WAF**](https://aws.amazon.com/waf)  é um firewall de aplicação web que permite monitorar solicitações de rede que entram em aplicações web.

O AWS WAF trabalha em conjunto com o Amazon CloudFront e um Application Load Balancer. Lembre-se das listas de controle de acesso de rede que você aprendeu em um módulo anterior. O AWS WAF funciona de forma semelhante para bloquear ou permitir o tráfego. No entanto, ele faz isso usando uma  [**lista de controle de acesso (ACL) da web**](https://docs.aws.amazon.com/waf/latest/developerguide/web-acl.html)  para proteger seus recursos da AWS.

### Amazon Inspector

O Amazon Inspector ajuda a melhorar a segurança e a conformidade das aplicações executando avaliações de segurança automatizadas. Ele verifica os aplicativos quanto a vulnerabilidades de segurança e desvios das práticas recomendadas de segurança, como acesso aberto a instâncias do Amazon EC2 e instalações de versões de software vulneráveis.

### Amazon GuardDuty

O [**Amazon GuardDuty**](https://aws.amazon.com/guardduty) é um serviço que realiza detecção inteligente de ameaças para sua infraestrutura e seus recursos AWS. Ele identifica ameaças monitorando continuamente a atividade da rede e o comportamento da conta no seu ambiente AWS.

## Módulo 7: Monitoramento e Análise

#### Amazon CloudWatch
O  [**Amazon CloudWatch**](https://aws.amazon.com/cloudwatch/)  é um serviço da web que permite monitorar e gerenciar várias métricas e configurar ações de alarme de acordo com os dados dessas métricas.

O CloudWatch usa  [**métricas**](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)  para representar os pontos de dados para seus recursos. Os serviços AWS enviam as métricas ao CloudWatch. Em seguida, o CloudWatch usa essas métricas para criar automaticamente gráficos que mostram como o desempenho mudou ao longo do tempo.

#### AWS CloudTrail
O [**AWS CloudTrail**](https://aws.amazon.com/cloudtrail/) registra as chamadas de API realizadas na sua conta. As informações gravadas são identidade do chamador da API, hora da chamada da API, endereço IP de origem do chamador da API e muito mais. Você pode pensar no CloudTrail como uma “trilha” (ou um log de ações) que alguém criou. Normalmente, os eventos são atualizados no CloudTrail dentro de 15 minutos após uma chamada de API.

##### CloudTrail Insights
No CloudTrail, você também pode ativar o CloudTrail Insights. Esse recurso opcional permite que o CloudTrail detecte automaticamente atividades de API incomuns em sua conta AWS. 

#### AWS Trusted Advisor
O  [**AWS Trusted Advisor**](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/)  é um serviço da web que inspeciona seu ambiente AWS e faz recomendações em tempo real de acordo com as práticas recomendadas da AWS.

O Trusted Advisor compara as descobertas com as práticas recomendadas da AWS em cinco categorias: otimização de custos, desempenho, segurança, tolerância a falhas e limites de serviço. Para as verificações em cada categoria, o Trusted Advisor oferece uma lista de ações recomendadas e recursos adicionais para saber mais sobre as práticas recomendadas da AWS.

5 pilares:

 - Otimização de custos
 - Performance
 - Segurança
 - Tolerância a falhas
 - Cotas de serviço

## Módulo 8 - Definição de preços e suporte

### Nível gratuito da AWS
#### Três tipos de ofertas estão disponíveis:
-   Sempre gratuito
-   12 meses gratuitos
-   Versões de teste

### Sempre gratuito
Essas ofertas não expiram e estão disponíveis para todos os clientes AWS.
Por exemplo, o AWS Lambda permite um milhão de solicitações gratuitas e até 3,2 milhões de segundos de tempo de computação por mês. O Amazon DynamoDB libera 25 GB de armazenamento gratuito por mês.

### 12 meses gratuitos
Essas ofertas são gratuitas por 12 meses após sua data de inscrição inicial na AWS.
Quantidades específicas de armazenamento do Amazon S3 Standard, limites para horas mensais de tempo de computação do Amazon EC2 e quantidades de transferência de dados do Amazon CloudFront para fora são alguns exemplos.

### Versão de testes

As versões de teste gratuitas de curto prazo começam na data em que você ativa determinado serviço. A duração de cada teste pode variar de acordo com o número de dias ou a quantidade de uso do serviço.

Por exemplo, o Amazon Inspector oferece uma versão gratuita de 90 dias. O Amazon Lightsail (um serviço que permite que você execute servidores virtuais privados) oferece 750 horas de uso gratuitas em um período de 30 dias.


### Conceitos de definição de preço da AWS
A AWS oferece diversos serviços de computação em nuvem com modelos de pagamento conforme o uso. 

### Calculadora de Preços da AWS
A [**Calculadora de Preços da AWS**](https://calculator.aws/#/) permite explorar os serviços da AWS e gerar uma estimativa de custo de seus casos de uso na AWS. Você pode organizar as suas estimativas da AWS por grupos que definir. Um grupo pode refletir como sua empresa está organizada, por exemplo, realizar estimativas por centro de custo.

### Cobrança consolidada
O recurso de cobrança consolidada do AWS Organizations permite que você receba uma única fatura para todas as contas AWS na sua organização. Ao consolidar, você pode rastrear facilmente os custos combinados de todas as contas vinculadas em sua organização. O número máximo de contas-padrão permitido para uma organização é quatro, mas você pode entrar em contato com o AWS Support para aumentar sua cota, se necessário.

### AWS Budgets
No  [**AWS Budgets**](https://aws.amazon.com/aws-cost-management/aws-budgets), você pode criar orçamentos para planejar o uso do serviço, os custos de serviço e as reservas de instâncias.

As informações do AWS Budgets são atualizadas três vezes por dia. Isso ajuda você a definir com precisão a proximidade entre seu uso e os valores orçados ou limites de nível gratuito da AWS.

No AWS Budgets, você também pode definir alertas personalizados para quando seu uso exceder (ou estiver prestes a exceder) o valor orçado.

### AWS Cost Explorer
O  [**AWS Cost Explorer**](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/)  é uma ferramenta que permite visualizar, interpretar e gerenciar seus custos e uso da AWS ao longo do tempo.

O AWS Cost Explorer inclui um relatório-padrão dos custos e do uso dos cinco principais serviços da AWS de acúmulo de custos. Você pode aplicar filtros e grupos personalizados para analisar seus dados. Por exemplo, você pode exibir o uso de recursos no nível por hora.

### AWS Support
A AWS oferece quatro  [**planos de suporte**](https://aws.amazon.com/premiumsupport/plans/)  diferentes para ajudar você a solucionar problemas, reduzir custos e usar os serviços da AWS de maneira eficiente.

Você pode escolher entre os seguintes planos do Support para atender às necessidades de sua empresa:

-   Basic
-   Desenvolvedor
-   Empresarial
-   Empresarial Rápido
-   Empresarial de Grande Porte

Recursos do plano de suporte  **AWS Basic Support Plan**:**Customer Service and Communities**: Acesso 24/7 aos serviços do cliente, documentações, whitepappers e fóruns de suporte.**AWS Trusted Advisor**: Acesso às 7 verificações do  **Trusted Advisor**  padrões e guias para que você provisione seus recursos seguindo as melhores práticas e melhorar a sua performance e segurança.**AWS Personal Health Dashboard**: Uma visão personalizada da saúde dos serviços da AWS e alertas de quando seus recursos serão impactados.

Recursos do plano de suporte  **AWS Developer Support Plan**:Todos os recursos do  **Basic Support Plan**  +Acesso direto ao suporte da AWS com possibilidade de abertura de ticket com a equipe de suporte.Contato direto com a equipe de suporte da AWS.Tempo de resposta Em caso de incidentes:

-   Incidentes gerais: < 24 horas úteis
-   Incidentes com impacto no sistema: < 12 horas úteis

Recursos do plano de suporte  **AWS Business Support Plan**:Todos os recursos do  **Basic Support Plan**  +Útil para ser utilizado em trabalhos em ambiente produtivo.Trusted Advisor com acesso completo a todas as verificações + acesso à API.Telefone 24/7, email e acesso a chat com a equipe de Suporte da AWS.Tickets e contatos ilimitados.Acesso ao Infrastructure Event Management por um custo adicional.Tempo de resposta Em caso de incidentes:

-   Incidente geral: < 24 horas úteis
-   Sistema impactado: < 12 horas úteis
-   Sistema PRODUTIVO impactado: < 4 horas
-   Sistema PRODUTIVO fora do ar: < 1 hora

Recursos do plano de suporte  **AWS Enterprise Support Plan**  : Todos os recursos do  **Business Support Plan**  +Ideal para empresas grandes que possuem risco de grande impacto em ambiente produtivo. Acesso ao  **Technical Account Manager (TAM)**  Acesso ao  **Concierge Support Team**  - Para dar conselhos para utilização da conta e billing.Acesso ao Infrastrucutre Event management, Will-Architected and Operation Reviews.Tempo de resposta Em caso de incidentes:

-   Incidente geral: < 24 horas úteis
-   Sistema impactado: < 12 horas úteis
-   Sistema PRODUTIVO impactado: < 4 horas
-   Sistema PRODUTIVO fora do ar: < 1 hora
-   Sistema PRODUTIVO CRÍTICO fora do ar: < 15 minutos

### AWS Marketplace

O [**AWS Marketplace**](https://aws.amazon.com/marketplace) é um catálogo digital com milhares de ofertas de software de provedores independentes de software. Você pode usar o AWS Marketplace para encontrar, testar e comprar software que pode ser executado na AWS.

## Módulo 9 - Migração e Inovação

### AWS Cloud Adoption Framework (AWS CAF)

o  [**AWS Cloud Adoption Framework (AWS CAF)**](https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf)  organiza orientações em seis áreas de foco chamadas  **perspectivas**. Cada perspectiva aborda responsabilidades distintas. O processo de planejamento ajuda as pessoas certas em toda a organização a se prepararem para as mudanças futuras.

Em geral, as perspectivas de  **negócio**,  **pessoas**  e  **governança**  se concentram nos recursos comerciais, enquanto as perspectivas de  **plataforma**,  **segurança**  e  **operações**  se concentram em capacidades técnicas.

 **perspectiva de negócio**: A perspectiva de negócio garante que a TI esteja alinhada às necessidades de negócio e que os investimentos em TI estejam vinculados aos principais resultados dos negócios.
Use a perspectiva de negócio para criar um caso de negócio sólido para adoção da nuvem e priorizar as iniciativas de adoção da nuvem. Garanta que suas estratégias e metas de negócios estejam alinhadas com suas estratégias e metas de TI. 

**perspectiva de pessoas**: A  **perspectiva de pessoas**  promove o desenvolvimento de uma estratégia de gerenciamento de alterações em toda a organização para a adoção bem-sucedida da nuvem.

Use a perspectiva de pessoas para avaliar estruturas e perfis organizacionais, novos requisitos de habilidades e processos e identificar lacunas. Isso ajuda a priorizar treinamento, pessoal e mudanças organizacionais.

**perspectiva de governança**: A  **perspectiva de governança**  se concentra nas habilidades e processos para alinhar a estratégia de TI à estratégia de negócios. Isso garante que você maximize o valor comercial e minimize os riscos.

Use a perspectiva de governança para entender como atualizar as habilidades e os processos da equipe necessários para garantir a governança de negócios na nuvem. Gerencie e mensure os investimentos em nuvem para avaliar os resultados de negócios.

**perspectiva de plataforma**: A  **perspectiva de plataforma**  inclui princípios e padrões para implementação de novas soluções na nuvem e migração de cargas de trabalho on-premises para a nuvem.  

Use uma variedade de modelos arquitetônicos para entender e comunicar a estrutura dos sistemas de TI e suas relações. Descreva a arquitetura do ambiente de destino em detalhes.

**perspectiva de segurança** : A  **perspectiva de segurança**  garante que a organização atenda aos objetivos de segurança de visibilidade, auditoria, controle e agilidade. 

Use o AWS CAF para estruturar a seleção e a implementação de controles de segurança que atendam às necessidades da organização.

**perspectiva de operações** : A  **perspectiva de operações**  ajuda você a ativar, executar, usar, operar e recuperar cargas de trabalho de TI para o nível definido com os stakeholders da empresa.

Defina como os negócios diários, trimestrais e anuais são conduzidos. Alinhe e dê suporte às operações do negócio. O AWS CAF ajuda os stakeholders a definir os procedimentos operacionais atuais e identificar mudanças de processo e treinamento necessários para implementar a nuvem com sucesso.

### **Seis estratégias de migração**

Ao migrar aplicações para a nuvem, seis das  [estratégias de migração](https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/)  mais comuns que você pode implementar são:

-   redefinição de hospedagem (nenhuma mudança)
-   redefinição de plataforma (mudança mínima, sem código. ex: alterar tipo de banco para do AWS)
-   refatoração/rearquitetura: (refatorar o código)
-   recompra (mudar a licença para modelo de serviço)
-   retenção ( mantem aplicações no ambiente de origem, mover só necessário)
-   retirada (remoção de aplicações que não são mais necessários)

### AWS Snow Family
A  [**AWS Snow Family**](https://aws.amazon.com/snow)  é uma coleção de dispositivos físicos para transporte físico de até exabytes de dados para dentro e para fora da AWS.

A AWS Snow Family consiste nos serviços  **AWS Snowcone**,  **AWS Snowball**  e  **AWS Snowmobile**.

 - [**AWS Snowcone**](https://aws.amazon.com/snowcone):  é um dispositivo pequeno, robusto e seguro para transferência de dados e computação de borda.
 - **[**AWS Snowball**](https://aws.amazon.com/snowball/)**: O  [**AWS Snowball**](https://aws.amazon.com/snowball/)  oferece dois tipos de dispositivos: os dispositivos

 -   **Snowball Edge Storage Optimized** são ideais para migrações de dados de grande escala e fluxos de trabalho de transferência recorrentes, em além da computação local com necessidades maiores de capacidade.
    -   Armazenamento: 80 TB de capacidade de disco rígido (HDD) para volumes de blocos e armazenamento de objeto compatível com o Amazon S3, além de unidade de estado sólido (SSD) do SATA de 1 TB para volumes de blocos.
    -   Computação: 40 vCPUs e 80 GiB de memória para dar suporte a instâncias sbe1 do Amazon EC2 (equivalente a C5).
 -   **O Snowball Edge Compute Optimized** fornece recursos de computação poderosos para casos de uso, como machine learning, análise de vídeo em movimento completo, análise e pilhas de computação locais.
    -   Armazenamento: capacidade de HDD utilizável de 80 TB para armazenamento de objeto compatível com o Amazon S3 ou volumes de blocos compatíveis com o Amazon EBS e também 28 TB de capacidade de SSD NVMe utilizável para volumes de blocos compatíveis com o Amazon EBS.
    -   Computação: 104 vCPUs, 416 GiB de memória e uma GPU NVIDIA Tesla V100 opcional. Os dispositivos executam as instâncias sbe-c e sbe-g do Amazon EC2, que são equivalentes às instâncias C5, M5a, G3 e P3.
   
 - O [**AWS Snowmobile**](https://aws.amazon.com/snowmobile) é um serviço de transferência dados na escala de exabytes usado para mover grandes quantidades de dados para a nuvem AWS. Você pode transferir até 100 petabytes de dados por Snowmobile, um contêiner de transporte reforçado com 13,71 metros de comprimento puxado por um caminhão semirreboque.

### Amazon SageMaker
Com ele você consegue criar, treinar e implantar rapidamente modelos de machine learning em escala ou então criar modelos personalizados com suporte para todas as estruturas de códigos aberto convencionais. Nossas capacidades são criadas na plataforma de nuvem mais abrangente, otimizada para machine learning, com computação de alto desempenho, sem comprometer a segurança e analytics.

### Amazon CodeWhisperer
Ele analisa e completa o código conforme o desenvolvedor  o escreve no ambiente de desenvolvimento integrado.  Ele vai além do preenchimento de código usando o processamento de linguagem natural  para compreender os comentários no código do desenvolvedor.  Por meio do entendimento de comentários em inglês,  o CodeWhisperer gera funções e blocos de código completos  que se alinham com as descrições de um desenvolvedor.


## Módulo 10 - A jornada para a nuvem

### AWS Well-Architected Framework

O [**AWS Well-Architected Framework**](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) ajuda você a entender como projetar e operar sistemas confiáveis, seguros, eficientes e econômicos na nuvem AWS. Com ele, é possível avaliar de maneira consistente suas arquiteturas em relação às práticas recomendadas e aos princípios de projeto e a identificar áreas para melhorias.

O Well-Architected Framework se baseia em seis pilares:

-   Excelência operacional
-   Segurança
-   Confiabilidade
-   Eficiência de desempenho
-   Otimização de custos
-   Sustentabilidade

### Vantagens da computação em nuvem

Operar na nuvem AWS oferece muitos benefícios em relação à computação em ambientes on-premises ou híbridos. 

Nesta seção, você aprenderá sobre seis vantagens da computação em nuvem:

 - Trocar despesa antecipada por despesas variáveis. 
 - Benefícios de enormes economias de escala. 
 - Parar de tentar adivinhar a capacidade.
 - Aumentar a velocidade e a agilidade. 
 - Parar de gastar dinheiro com execução e manutenção de data centers. 
 - Ter alcance global em minutos.

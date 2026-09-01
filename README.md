# AWS Certified Cloud Practitioner — Guia Completo CLF-C02

Guia de estudos em português para a certificação **AWS Certified Cloud Practitioner (CLF-C02)**.

> **Atualização:** setembro de 2026<br>
> **Fonte principal:** [guia oficial do exame CLF-C02](https://docs.aws.amazon.com/pdfs/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.pdf)<br>
> A lista de serviços e o conteúdo do exame podem mudar. Antes da prova, confira a versão mais recente do [guia do exame](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html) e dos [serviços no escopo](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/clf-02-in-scope-services.html).

Este material é voltado ao nível **Foundational**. O objetivo é entender conceitos, reconhecer serviços e escolher a alternativa adequada para um caso de uso. A prova não exige escrever código, implementar arquiteturas, solucionar falhas complexas ou decorar configurações avançadas.

---

## Sumário

- [1. Visão geral da prova](#1-visão-geral-da-prova)
- [2. Domínio 1 — Conceitos de nuvem](#2-domínio-1--conceitos-de-nuvem-24)
- [3. Domínio 2 — Segurança e conformidade](#3-domínio-2--segurança-e-conformidade-30)
- [4. Domínio 3 — Tecnologia e serviços de nuvem](#4-domínio-3--tecnologia-e-serviços-de-nuvem-34)
- [5. Domínio 4 — Faturamento, preços e suporte](#5-domínio-4--faturamento-preços-e-suporte-12)
- [6. Comparações essenciais](#6-comparações-essenciais)
- [7. Serviços no escopo da CLF-C02](#7-serviços-no-escopo-da-clf-c02)
- [8. Pegadinhas frequentes](#8-pegadinhas-frequentes)
- [9. Checklist de revisão](#9-checklist-de-revisão)
- [10. Recursos oficiais](#10-recursos-oficiais)

---

# 1. Visão geral da prova

| Item | Informação |
|---|---|
| Código | **CLF-C02** |
| Nível | Foundational |
| Duração | 90 minutos |
| Questões | 65 |
| Questões pontuadas | 50 |
| Questões não pontuadas | 15, não identificadas durante a prova |
| Formato | Múltipla escolha e múltiplas respostas |
| Pontuação | Escala de 100 a 1.000 |
| Aprovação | Mínimo de **700 pontos** |
| Penalidade por erro | Não há; questões em branco contam como incorretas |
| Modelo de pontuação | Compensatório: é necessário passar no resultado geral, não em cada domínio |
| Aplicação | Centro Pearson VUE ou prova online supervisionada |
| Idioma | Disponível em português do Brasil, entre outros idiomas |

## Pesos dos domínios

| Domínio | Peso |
|---|---:|
| 1. Conceitos de nuvem | 24% |
| 2. Segurança e conformidade | 30% |
| 3. Tecnologia e serviços de nuvem | 34% |
| 4. Faturamento, preços e suporte | 12% |
| **Total** | **100%** |

Segurança e Tecnologia representam juntas **64%** da pontuação. Priorize esses domínios.

## Objetivos oficiais por domínio

| Código | Objetivo |
|---|---|
| 1.1 | Definir os benefícios da AWS Cloud. |
| 1.2 | Identificar princípios de design da AWS Cloud. |
| 1.3 | Entender benefícios e estratégias de migração para a AWS Cloud. |
| 1.4 | Entender conceitos de economia da nuvem. |
| 2.1 | Entender o modelo de responsabilidade compartilhada da AWS. |
| 2.2 | Entender segurança, governança e conformidade na AWS Cloud. |
| 2.3 | Identificar recursos de gerenciamento de acesso. |
| 2.4 | Identificar componentes e recursos de segurança. |
| 3.1 | Definir formas de implantar e operar na AWS Cloud. |
| 3.2 | Definir a infraestrutura global AWS. |
| 3.3 | Identificar serviços de computação. |
| 3.4 | Identificar serviços de banco de dados. |
| 3.5 | Identificar serviços de rede. |
| 3.6 | Identificar serviços de armazenamento. |
| 3.7 | Identificar serviços de IA/ML e analytics. |
| 3.8 | Identificar serviços das demais categorias no escopo. |
| 4.1 | Comparar modelos de preço AWS. |
| 4.2 | Entender recursos de faturamento, orçamento e gestão de custos. |
| 4.3 | Identificar recursos técnicos e opções do AWS Support. |

## Tipos de questão

- **Múltipla escolha:** uma resposta correta e três distratores.
- **Múltiplas respostas:** duas ou mais respostas corretas entre cinco ou mais alternativas.
- Os distratores costumam ser serviços reais que resolvem problemas parecidos. A chave é identificar a palavra do cenário: fila, auditoria, métrica, vulnerabilidade, dados sensíveis, DNS, CDN, conexão dedicada, estimativa de custo e assim por diante.

## O que está fora do nível da prova

- Programação.
- Implementação detalhada.
- Troubleshooting avançado.
- Desenho completo de arquitetura.
- Testes de carga e performance.
- Memorização de comandos, APIs, limites ou preços exatos que mudam com frequência.

---

# 2. Domínio 1 — Conceitos de nuvem (24%)

## 2.1 O que é computação em nuvem

Computação em nuvem é a entrega sob demanda de recursos de TI pela internet, com preços baseados no consumo. Em vez de comprar e manter servidores, redes e data centers, o cliente provisiona recursos quando precisa e paga pelo que utiliza.

### Seis vantagens clássicas da nuvem AWS

1. **Trocar despesas fixas por variáveis:** reduzir investimento antecipado em infraestrutura e pagar conforme o uso.
2. **Beneficiar-se de economias de escala:** a AWS agrega o consumo de muitos clientes e reduz custos unitários.
3. **Parar de adivinhar a capacidade:** aumentar ou reduzir recursos conforme a demanda.
4. **Aumentar velocidade e agilidade:** provisionar recursos em minutos.
5. **Parar de gastar com operação de data centers:** transferir à AWS atividades de infraestrutura física.
6. **Ter alcance global em minutos:** implantar aplicações em diversas regiões próximas dos usuários.

## 2.2 Conceitos que não devem ser confundidos

| Conceito | Significado |
|---|---|
| **Escalabilidade** | Capacidade de aumentar ou reduzir recursos para atender ao crescimento ou à redução da carga. Pode ser vertical ou horizontal. |
| **Elasticidade** | Ajuste dinâmico, geralmente automático, dos recursos conforme a demanda atual. Evita capacidade ociosa e falta de capacidade. |
| **Agilidade** | Velocidade para experimentar, provisionar e lançar soluções. |
| **Alta disponibilidade** | Manter o serviço acessível apesar da falha de componentes, normalmente usando múltiplas AZs. |
| **Tolerância a falhas** | Continuar operando mesmo quando um componente falha, com pouca ou nenhuma interrupção. |
| **Resiliência** | Capacidade de resistir e recuperar-se de falhas. |
| **Durabilidade** | Probabilidade de os dados permanecerem íntegros ao longo do tempo. |

### Escalabilidade vertical e horizontal

- **Vertical (scale up/down):** mudar o tamanho de uma máquina, adicionando ou removendo CPU e memória.
- **Horizontal (scale out/in):** adicionar ou remover instâncias. É a abordagem normalmente associada ao Auto Scaling e à elasticidade.

## 2.3 Modelos de implantação

| Modelo | Descrição | Exemplo |
|---|---|---|
| **Cloud** | Recursos executados integralmente na nuvem. | Aplicação e banco na AWS. |
| **On-premises** | Recursos executados no data center do cliente. | Servidores mantidos pela empresa. |
| **Híbrido** | Integra recursos locais e de nuvem. | Data center conectado à AWS por VPN ou Direct Connect. |

## 2.4 Modelos de serviço

| Modelo | Cliente gerencia | Provedor gerencia | Exemplo conceitual |
|---|---|---|---|
| **IaaS** | Sistema operacional, aplicações e dados | Hardware e virtualização | Amazon EC2 |
| **PaaS** | Aplicação e dados | Infraestrutura, sistema e plataforma | AWS Elastic Beanstalk |
| **SaaS** | Configuração e uso do software | Aplicação e toda a infraestrutura | Software pronto adquirido no AWS Marketplace |

Quanto mais gerenciado o serviço, menos componentes de infraestrutura ficam sob responsabilidade operacional do cliente.

## 2.5 Economia da nuvem

### CAPEX e OPEX

- **CAPEX:** investimento de capital antecipado, como compra de servidores e construção de data centers.
- **OPEX:** despesa operacional variável, como pagar mensalmente pelos recursos consumidos.
- A nuvem ajuda a trocar grandes despesas antecipadas por despesas variáveis.

### Custos que existem on-premises

- Compra e depreciação de hardware.
- Energia, refrigeração e espaço físico.
- Rede e conectividade.
- Licenças e contratos de suporte.
- Equipe para manutenção.
- Capacidade ociosa adquirida para picos futuros.
- Renovação e descarte de equipamentos.

### Conceitos econômicos importantes

| Conceito | Explicação |
|---|---|
| **Pay as you go** | Pagar pelo consumo, sem aquisição antecipada de hardware. |
| **Economia de escala** | O grande volume agregado da AWS permite menor custo variável. |
| **Rightsizing** | Adequar tipo e tamanho dos recursos à carga real. |
| **Automação** | Reduz esforço manual, erros e tempo de provisionamento. |
| **BYOL** | Bring Your Own License: usar uma licença já adquirida, quando permitido. |
| **License included** | O preço do serviço inclui a licença do software. |
| **TCO** | Custo total de propriedade, considerando infraestrutura, operação, pessoal e manutenção. |

## 2.6 AWS Well-Architected Framework

O [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) ajuda a avaliar arquiteturas e tomar decisões com base em boas práticas.

### Os seis pilares

| Pilar | Pergunta principal | Exemplos |
|---|---|---|
| **Excelência operacional** | Como operar, observar e melhorar continuamente? | Automação, observabilidade, procedimentos e aprendizado com falhas. |
| **Segurança** | Como proteger dados, sistemas e ativos? | Menor privilégio, rastreabilidade, criptografia e resposta a incidentes. |
| **Confiabilidade** | Como se recuperar de falhas e atender à demanda? | Multi-AZ, backups, recuperação e gerenciamento de mudanças. |
| **Eficiência de performance** | Como usar os recursos mais adequados e eficientes? | Seleção de tecnologia, monitoramento e experimentação. |
| **Otimização de custos** | Como evitar gastos desnecessários? | Rightsizing, desligamento de ociosos e modelos de compra adequados. |
| **Sustentabilidade** | Como reduzir impactos ambientais? | Maximizar utilização, usar serviços gerenciados e reduzir recursos ociosos. |

### Princípios gerais de projeto na nuvem

- Parar de adivinhar a capacidade.
- Testar sistemas em escala de produção.
- Automatizar para facilitar experimentos.
- Permitir evolução da arquitetura.
- Usar decisões baseadas em dados.
- Melhorar por meio de simulações e análises de falhas.

## 2.7 AWS Cloud Adoption Framework (AWS CAF)

O [AWS CAF](https://aws.amazon.com/cloud-adoption-framework/) ajuda organizações a preparar pessoas, processos e tecnologia para a transformação pela nuvem.

### Resultados de negócio esperados

- Redução de riscos de negócio.
- Melhoria de desempenho ambiental, social e de governança (ESG).
- Aumento de receita.
- Maior eficiência operacional.

### Seis perspectivas

| Perspectiva | Foco |
|---|---|
| **Negócios** | Garantir que investimentos em nuvem gerem resultados de negócio. |
| **Pessoas** | Cultura, estrutura organizacional, liderança, habilidades e treinamento. |
| **Governança** | Alinhar iniciativas, riscos, portfólio e investimentos. |
| **Plataforma** | Arquitetura, provisionamento e modernização da plataforma. |
| **Segurança** | Confidencialidade, integridade, disponibilidade e controles de segurança. |
| **Operações** | Operar, monitorar, manter e recuperar cargas de trabalho. |

As perspectivas **Negócios, Pessoas e Governança** estão mais ligadas às capacidades de negócio. **Plataforma, Segurança e Operações** concentram-se nas capacidades técnicas.

## 2.8 Jornada de migração

Uma jornada de migração costuma ser tratada em três etapas:

1. **Avaliar (Assess):** entender inventário, dependências, custos e prontidão.
2. **Mobilizar (Mobilize):** preparar governança, competências, landing zone e plano de migração.
3. **Migrar e modernizar (Migrate and Modernize):** mover as cargas e aproveitar serviços nativos da nuvem.

### As sete estratégias de migração — 7 Rs

| Estratégia | Também chamada | O que acontece |
|---|---|---|
| **Rehost** | Lift and shift | Move a aplicação sem mudanças relevantes. |
| **Replatform** | Lift, tinker and shift | Faz pequenas otimizações sem alterar a arquitetura principal. |
| **Refactor/Re-architect** | Rearquitetar | Modifica a aplicação para aproveitar recursos nativos da nuvem. |
| **Repurchase** | Drop and shop | Substitui por outro produto, frequentemente SaaS. |
| **Relocate** | Hypervisor-level lift and shift | Move grande quantidade de VMs sem redesenhar as aplicações. |
| **Retain** | Manter | Mantém temporariamente a carga no ambiente atual. |
| **Retire** | Desativar | Remove aplicações que não são mais necessárias. |

### Serviços de migração e transferência

| Serviço | Caso de uso principal |
|---|---|
| **AWS Application Discovery Service** | Descobrir servidores, utilização e dependências do ambiente local. |
| **Migration Evaluator** | Criar análise e business case para migração. |
| **AWS Migration Hub** | Acompanhar migrações em um painel central. |
| **AWS Application Migration Service (MGN)** | Migrar servidores para a AWS com replicação contínua. |
| **AWS Database Migration Service (DMS)** | Migrar e replicar bancos com baixo tempo de indisponibilidade. |
| **AWS Schema Conversion Tool (SCT)** | Converter esquemas e código quando os mecanismos de banco são diferentes. |
| **AWS Snow Family** | Transferir fisicamente grandes volumes de dados ou executar edge computing em locais desconectados. |

### AWS Snow Family

- **Snowcone:** dispositivo pequeno e portátil para transferência e edge computing.
- **Snowball Edge:** transferência em escala maior e processamento local.
- Para a prova, memorize o cenário: **muito dado, rede lenta/indisponível ou transferência física necessária**.
- Capacidades e modelos mudam; não vale a pena decorar especificações de hardware.

---

# 3. Domínio 2 — Segurança e conformidade (30%)

## 3.1 Modelo de responsabilidade compartilhada

A segurança e a conformidade são compartilhadas entre AWS e cliente:

- **AWS — segurança da nuvem:** protege a infraestrutura que executa os serviços.
- **Cliente — segurança na nuvem:** protege dados, identidades, aplicações e configurações sob seu controle.

### Divisão geral

| AWS é responsável por | Cliente é responsável por |
|---|---|
| Data centers e segurança física | Dados e classificação dos dados |
| Hardware, armazenamento e rede física | Identidades, credenciais e permissões |
| Infraestrutura global | Configurações de rede e firewall sob seu controle |
| Camada de virtualização | Sistema operacional convidado no EC2 |
| Disponibilidade da infraestrutura dos serviços | Aplicações e código |
| Descarte de discos e equipamentos | Criptografia e proteção dos dados conforme o serviço |
| Controles da infraestrutura | Conformidade da própria carga e do próprio negócio |

### Responsabilidades compartilhadas

Alguns controles têm participação das duas partes:

- **Gerenciamento de patches:** AWS corrige a infraestrutura; o cliente corrige sistema operacional e aplicações quando estão sob seu controle.
- **Gerenciamento de configuração:** AWS configura a infraestrutura; o cliente configura recursos e aplicações.
- **Conscientização e treinamento:** AWS treina seus colaboradores; o cliente treina os próprios colaboradores.

### A responsabilidade muda conforme o serviço

| Camada | Amazon EC2 | Amazon RDS | AWS Lambda |
|---|---|---|---|
| Data center, hardware e virtualização | AWS | AWS | AWS |
| Sistema operacional | **Cliente** | AWS | AWS |
| Instalação e patches do mecanismo/plataforma | Cliente | AWS | AWS |
| Código e aplicação | Cliente | Cliente | **Cliente** |
| Dados | Cliente | Cliente | Cliente |
| IAM e permissões | Cliente | Cliente | Cliente |
| Configuração de rede disponível ao cliente | Cliente | Cliente | Cliente |

**Regra mental:** quanto mais gerenciado o serviço, mais tarefas operacionais são assumidas pela AWS, mas o cliente continua responsável por dados, identidades, permissões e uso seguro.

## 3.2 Princípios fundamentais de segurança

- Aplicar o **menor privilégio**.
- Habilitar **MFA**, especialmente para o usuário root.
- Preferir credenciais temporárias por meio de roles.
- Não armazenar access keys no código.
- Criptografar dados em repouso e em trânsito.
- Registrar, monitorar e auditar ações.
- Automatizar controles de segurança.
- Proteger todas as camadas, não apenas o perímetro.
- Preparar resposta a incidentes.
- Evitar uso cotidiano do usuário root.

## 3.3 AWS Identity and Access Management (IAM)

O **IAM** gerencia autenticação e autorização para recursos AWS. É um serviço global e não regional.

### Autenticação e autorização

- **Autenticação:** comprovar quem você é.
- **Autorização:** definir o que você pode fazer.

### Componentes do IAM

| Componente | Função |
|---|---|
| **Usuário** | Identidade de longo prazo para uma pessoa ou aplicação. Sempre que possível, prefira federação e credenciais temporárias. |
| **Grupo** | Conjunto de usuários. Facilita conceder permissões iguais a vários usuários. Grupos não contêm outros grupos. |
| **Role (função)** | Identidade assumida temporariamente por usuário, serviço ou conta. Fornece credenciais temporárias. |
| **Política** | Documento JSON que permite ou nega ações em recursos sob determinadas condições. |

> **Role não é instance profile.** Uma IAM Role contém permissões que podem ser assumidas. Um instance profile é o contêiner usado para disponibilizar uma role a uma instância EC2.

### Avaliação de políticas

- Por padrão, tudo é negado: **implicit deny**.
- Uma permissão precisa de um **Allow** aplicável.
- Um **Explicit Deny** sempre prevalece sobre um Allow.
- Políticas podem ser gerenciadas pela AWS, gerenciadas pelo cliente ou inline.
- Políticas baseadas em identidade são anexadas a usuários, grupos e roles.
- Políticas baseadas em recurso são anexadas ao recurso, como uma bucket policy do S3.

### Usuário root

O usuário root é criado com a conta e tem acesso total. Boas práticas:

1. Usar senha forte e exclusiva.
2. Habilitar MFA.
3. Não criar access keys para o root.
4. Guardar as credenciais de forma segura.
5. Não usar o root em tarefas diárias.
6. Usá-lo somente em tarefas que realmente exigem essa identidade, como determinadas configurações da conta.

### Credenciais

| Credencial | Uso |
|---|---|
| **Senha** | Acesso interativo ao AWS Management Console. |
| **Access key ID + secret access key** | Acesso programático por CLI, SDK ou API. Não devem ser inseridas no código. |
| **Credenciais temporárias** | Fornecidas ao assumir uma role; são preferíveis às chaves de longo prazo. |
| **MFA** | Segundo fator que reduz o risco de comprometimento da conta. |

### IAM Identity Center

O **AWS IAM Identity Center** fornece acesso centralizado de usuários a múltiplas contas AWS e aplicações. É a opção principal para workforce access e single sign-on.

- Integra identidades internas ou provedores externos.
- Permite atribuir conjuntos de permissões a usuários e grupos.
- Evita criar um usuário IAM separado em cada conta.
- É usado com AWS Organizations para acesso multiaccount.

### Federação e acesso entre contas

- **Federação:** usa identidades existentes de um provedor externo para acessar a AWS.
- **Cross-account role:** permite que uma identidade de uma conta assuma uma role em outra conta.
- Roles fornecem credenciais temporárias e são preferíveis ao compartilhamento de chaves.

### Armazenamento de segredos

| Serviço | Uso principal |
|---|---|
| **AWS Secrets Manager** | Armazenar, recuperar e rotacionar segredos, como senhas de banco e chaves de API. |
| **AWS Systems Manager Parameter Store** | Armazenar configurações e parâmetros; também pode armazenar valores criptografados. |
| **AWS KMS** | Criar e controlar chaves usadas para criptografia; não é um gerenciador de senhas. |

## 3.4 AWS Organizations e governança multiaccount

O **AWS Organizations** permite gerenciar múltiplas contas de forma centralizada.

### Componentes

- **Management account:** conta que administra a organização.
- **Member accounts:** contas participantes.
- **Organizational Units (OUs):** agrupam contas por área, ambiente ou requisito.
- **Service Control Policies (SCPs):** definem o limite máximo de permissões das contas e OUs.
- **Cobrança consolidada:** reúne os custos em uma fatura e pode compartilhar benefícios de preço.

### Atenção às SCPs

- SCP **não concede** permissões.
- SCP define o que poderá ser permitido por políticas IAM dentro da conta.
- Uma negação em SCP limita as contas afetadas, mesmo que uma política IAM tenha Allow.
- A management account não é restringida por SCPs da organização.

### Serviços relacionados à governança

| Serviço | Caso de uso |
|---|---|
| **AWS Control Tower** | Configurar e governar um ambiente AWS multiaccount (landing zone) com controles predefinidos. |
| **AWS Service Catalog** | Publicar produtos de TI aprovados para que usuários provisionem somente soluções permitidas. |
| **AWS Resource Access Manager (RAM)** | Compartilhar recursos compatíveis entre contas ou dentro de uma organização. |
| **AWS Config** | Registrar configurações, histórico e conformidade de recursos. |
| **AWS Audit Manager** | Automatizar a coleta de evidências para auditorias. |

## 3.5 Criptografia e proteção de dados

### Em repouso e em trânsito

- **Criptografia em repouso:** protege dados armazenados em discos, bancos, buckets e backups.
- **Criptografia em trânsito:** protege dados durante a comunicação, normalmente com TLS.
- A criptografia não substitui controle de acesso, backup ou monitoramento.

### Serviços de criptografia

| Serviço | Função |
|---|---|
| **AWS Key Management Service (KMS)** | Criar e controlar chaves de criptografia integradas a diversos serviços AWS. |
| **AWS CloudHSM** | Hardware Security Module dedicado e controlado pelo cliente para necessidades específicas de conformidade. |
| **AWS Certificate Manager (ACM)** | Provisionar e gerenciar certificados TLS/SSL usados por serviços integrados. |
| **AWS Secrets Manager** | Proteger e rotacionar credenciais e segredos de aplicações. |

**KMS x CloudHSM:** KMS é gerenciado e integrado aos serviços AWS; CloudHSM fornece appliances HSM dedicados e maior controle direto sobre o material criptográfico.

## 3.6 Segurança de rede e aplicações

### Security Groups e Network ACLs

| Característica | Security Group | Network ACL |
|---|---|---|
| Aplicado a | Interface/recurso, como EC2 | Sub-rede |
| Estado | **Stateful** | **Stateless** |
| Regras | Somente Allow | Allow e Deny |
| Retorno do tráfego | Permitido automaticamente | Precisa de regra correspondente |
| Padrão | Entrada negada; saída permitida | NACL padrão permite tráfego; NACL personalizada começa negando |
| Uso | Controle principal no nível do recurso | Camada adicional no nível da sub-rede |

### Serviços de proteção

| Serviço | O que faz | Palavra-chave de prova |
|---|---|---|
| **AWS WAF** | Filtra requisições HTTP/HTTPS com regras de aplicação. | SQL injection, XSS, web ACL |
| **AWS Shield Standard** | Proteção automática contra ataques DDoS comuns, sem custo adicional. | DDoS básico |
| **AWS Shield Advanced** | Proteção DDoS avançada, suporte especializado e recursos adicionais pagos. | DDoS sofisticado |
| **AWS Firewall Manager** | Gerencia centralmente regras de firewall e políticas de segurança em múltiplas contas. | Regras centralizadas |

## 3.7 Detecção, postura e investigação de segurança

| Serviço | Função principal | Não confundir com |
|---|---|---|
| **Amazon GuardDuty** | Detecta ameaças e comportamento malicioso analisando fontes de logs e eventos. | Inspector, que encontra vulnerabilidades |
| **Amazon Inspector** | Verifica vulnerabilidades de software e exposição não intencional em recursos compatíveis. | GuardDuty, que detecta ameaças |
| **Amazon Macie** | Descobre e protege dados sensíveis no Amazon S3 usando ML e pattern matching. | GuardDuty |
| **AWS Security Hub** | Agrega, normaliza e prioriza achados de segurança de vários serviços e contas. | GuardDuty, que é uma fonte de achados |
| **Amazon Detective** | Ajuda a investigar a causa e o contexto de eventos de segurança. | Security Hub, que centraliza achados |
| **AWS Trusted Advisor** | Recomenda melhorias segundo boas práticas, inclusive verificações de segurança. | Scanner de ameaças em tempo real |

### Fluxo mental de segurança

1. **GuardDuty detecta** atividade suspeita.
2. **Inspector encontra** vulnerabilidades.
3. **Macie encontra** dados sensíveis no S3.
4. **Security Hub centraliza** os achados.
5. **Detective investiga** relações e causa provável.

## 3.8 Monitoramento, auditoria e conformidade

| Serviço | O que responde |
|---|---|
| **Amazon CloudWatch** | Como recursos e aplicações estão se comportando? Métricas, logs, alarmes e dashboards. |
| **AWS CloudTrail** | Quem fez qual chamada de API, quando e de onde? Auditoria de ações. |
| **AWS Config** | Como um recurso estava configurado e ele está em conformidade com as regras? |
| **AWS Audit Manager** | Como coletar e organizar evidências para uma auditoria? |
| **AWS Artifact** | Onde baixar relatórios de conformidade da AWS e gerenciar determinados acordos? |

### AWS Artifact

- **Artifact Reports:** relatórios e documentos de conformidade produzidos por auditores.
- **Artifact Agreements:** visualização, aceitação e gerenciamento de determinados contratos.
- O Artifact não audita a aplicação do cliente e não torna uma carga automaticamente compatível.

### Conformidade e localização de dados

- A AWS fornece infraestrutura, controles e documentação; o cliente decide como configurar sua carga de acordo com as próprias obrigações.
- Requisitos variam por país, região, setor e tipo de dado.
- O cliente escolhe as regiões em que armazena e processa os dados, respeitando os serviços disponíveis.
- **Data residency:** local físico/geográfico em que os dados são armazenados.
- **Compliance inherited:** o cliente pode herdar determinados controles da infraestrutura AWS, mas continua responsável pela conformidade de sua aplicação e operação.

### Fontes oficiais de informações de segurança

- [AWS Security Center](https://aws.amazon.com/security/)
- [AWS Security Blog](https://aws.amazon.com/blogs/security/)
- [AWS Compliance](https://aws.amazon.com/compliance/)
- [AWS Knowledge Center](https://repost.aws/knowledge-center/)
- Relatórios no AWS Artifact.
- Produtos de segurança de terceiros no AWS Marketplace.

## 3.9 Outros serviços de identidade e segurança

| Serviço | Caso de uso |
|---|---|
| **Amazon Cognito** | Adicionar cadastro, login e controle de acesso para usuários de aplicações web e móveis. |
| **AWS Directory Service** | Usar diretórios gerenciados e integrar cargas com Microsoft Active Directory. |
| **AWS IAM Identity Center** | Acesso centralizado da força de trabalho a contas e aplicações. |
| **AWS Certificate Manager** | Certificados TLS/SSL. |
| **AWS Resource Access Manager** | Compartilhamento seguro de recursos entre contas. |

## 3.10 Trusted Advisor

O **AWS Trusted Advisor** avalia o ambiente e apresenta recomendações de boas práticas.

### Seis categorias atuais

1. Otimização de custos.
2. Performance.
3. Segurança.
4. Tolerância a falhas.
5. Service limits/cotas de serviço.
6. Excelência operacional.

O acesso ao conjunto completo de verificações depende do plano de suporte. O Basic oferece verificações principais e acesso limitado; planos pagos elegíveis oferecem o conjunto completo e recursos adicionais.

---

# 4. Domínio 3 — Tecnologia e serviços de nuvem (34%)

## 4.1 Formas de acessar e provisionar a AWS

| Forma | Quando usar |
|---|---|
| **AWS Management Console** | Interface gráfica, exploração e tarefas manuais. |
| **AWS CLI** | Comandos e scripts no terminal. |
| **AWS SDKs** | Acessar serviços AWS a partir de linguagens de programação. |
| **APIs** | Interface programática exposta pelos serviços. |
| **Infrastructure as Code (IaC)** | Criar ambientes repetíveis, versionados e automatizados. |

### AWS CloudFormation

O **AWS CloudFormation** provisiona recursos a partir de templates declarativos.

- Infraestrutura como código.
- Criação consistente e repetível.
- Templates podem ser versionados.
- Gerencia recursos como uma **stack**.
- É preferível a passos manuais quando o processo precisa ser repetido.

**Operação única e exploratória:** console pode ser suficiente.<br>
**Implantações repetíveis e consistentes:** prefira IaC.

## 4.2 Infraestrutura global AWS

### Região

Uma **AWS Region** é uma área geográfica que contém múltiplas Availability Zones isoladas. A escolha da região considera:

- Proximidade dos usuários e latência.
- Requisitos legais e soberania dos dados.
- Disponibilidade de serviços e recursos.
- Custo, que pode variar entre regiões.
- Continuidade de negócio e disaster recovery.

### Availability Zone (AZ)

- Uma AZ é formada por **um ou mais data centers discretos** com energia, rede e conectividade redundantes.
- As AZs de uma região são fisicamente separadas e conectadas por redes privadas de baixa latência.
- Uma sub-rede pertence a somente uma AZ.
- Distribuir recursos entre AZs aumenta a disponibilidade e evita um único ponto de falha.

### Edge locations e Regional Edge Caches

- Pontos de presença aproximam conteúdo e serviços dos usuários.
- São usados por serviços como CloudFront e Route 53.
- Reduzem latência e carga sobre a origem.
- Edge location não é uma Availability Zone e não hospeda uma aplicação EC2 comum.

### Multi-AZ e Multi-Region

| Estratégia | Objetivo comum |
|---|---|
| **Multi-AZ** | Alta disponibilidade dentro de uma região. |
| **Multi-Region** | Disaster recovery, continuidade de negócio, alcance global, baixa latência ou soberania de dados. |

### Escopo dos serviços

- Alguns serviços são **globais**, como IAM, Route 53 e CloudFront.
- Muitos recursos são **regionais**, como uma VPC.
- Alguns recursos são vinculados a uma **AZ**, como uma sub-rede e um volume EBS.
- Sempre identifique o escopo do recurso ao pensar em disponibilidade e recuperação.

## 4.3 Computação

### Amazon EC2

O **Amazon Elastic Compute Cloud (EC2)** fornece servidores virtuais redimensionáveis.

O cliente escolhe:

- Amazon Machine Image (AMI).
- Tipo e tamanho da instância.
- Rede, sub-rede e security groups.
- Armazenamento.
- Modelo de compra.
- Sistema operacional e aplicações.

### Famílias de instâncias EC2

| Família | Otimizada para | Exemplos de uso |
|---|---|---|
| **Uso geral** | Equilíbrio entre CPU, memória e rede | Servidores web e aplicações comuns |
| **Compute optimized** | Processamento intensivo | Batch, jogos e HPC |
| **Memory optimized** | Grandes volumes em memória | Bancos e caches em memória |
| **Storage optimized** | Alto desempenho de armazenamento local | Data warehouse e processamento de logs |
| **Accelerated computing** | GPU e aceleradores de hardware | ML, gráficos e cálculos especializados |

### Opções de compra de computação

| Opção | Compromisso | Melhor cenário | Observação |
|---|---|---|---|
| **On-Demand** | Nenhum | Carga nova, irregular ou imprevisível | Paga por segundo ou hora, conforme o recurso. |
| **Savings Plans** | Compromisso de uso por 1 ou 3 anos | Uso previsível de computação | Desconto em troca de compromisso monetário por hora. |
| **Reserved Instances (RI)** | 1 ou 3 anos | Uso estável de uma configuração compatível | É um benefício de faturamento; uma RI regional não garante capacidade. |
| **Spot Instances** | Nenhum | Carga tolerante a interrupção e flexível | Capacidade ociosa, até 90% de desconto, pode ser recuperada pela AWS. |
| **Dedicated Hosts** | On-Demand ou compromisso | Servidor físico dedicado, compliance e BYOL por host/socket | Dá visibilidade e controle de posicionamento no host. |
| **Dedicated Instances** | Conforme compra da instância | Isolamento de hardware de outras contas | Sem o mesmo controle do host físico. |
| **Capacity Reservations** | Sem prazo mínimo obrigatório | Garantir capacidade em uma AZ para eventos ou DR | Garante capacidade, mas por si só não oferece desconto. |

#### Savings Plans

- **Compute Savings Plans:** mais flexíveis; podem aplicar-se a EC2, Fargate e Lambda compatíveis.
- **EC2 Instance Savings Plans:** compromisso com uma família de instância em uma região, com desconto potencial maior e menos flexibilidade.
- Savings Plan oferece **desconto**, não uma reserva de capacidade.

#### Reserved Instances

- **Standard RI:** maior desconto potencial e menor flexibilidade.
- **Convertible RI:** pode ser trocada por outra configuração elegível; oferece maior flexibilidade e desconto geralmente menor.
- Uma RI regional aplica o desconto a uso correspondente na região.
- Uma RI zonal pode incluir reserva de capacidade na AZ especificada.
- Benefícios de RI podem ser compartilhados entre contas com cobrança consolidada, conforme as preferências da organização.

#### Spot Instances

- Não funcionam mais como um leilão em que o cliente define o preço vencedor.
- Usam capacidade EC2 ociosa.
- Podem ser interrompidas quando a AWS precisa da capacidade.
- São adequadas para batch, CI/CD, big data, renderização e cargas stateless ou tolerantes a falha.
- Não são adequadas como única opção para uma carga crítica que não pode ser interrompida.

### Amazon EC2 Auto Scaling

- Ajusta automaticamente o número de instâncias.
- Usa políticas, métricas ou agendamentos.
- Ajuda a obter elasticidade, disponibilidade e eficiência de custo.
- Pode substituir instâncias não saudáveis.

### Elastic Load Balancing (ELB)

- Distribui tráfego entre múltiplos destinos, como instâncias EC2.
- Pode operar em múltiplas AZs.
- Executa health checks e deixa de enviar tráfego para destinos não saudáveis.
- Trabalha com Auto Scaling: ELB distribui; Auto Scaling aumenta ou reduz capacidade.

### Outros serviços de computação

| Serviço | Caso de uso |
|---|---|
| **AWS Elastic Beanstalk** | Implantar aplicações enviando o código; o serviço provisiona e gerencia a infraestrutura subjacente. |
| **Amazon Lightsail** | Servidores virtuais e aplicações simples com configuração e preço previsíveis. |
| **AWS Batch** | Executar e escalar trabalhos em lote, provisionando a computação necessária. |
| **AWS Outposts** | Levar infraestrutura e serviços AWS para instalações on-premises, com experiência híbrida consistente. |

## 4.4 Contêineres e serverless

### Contêineres

| Serviço | Função |
|---|---|
| **Amazon ECR** | Registro gerenciado para armazenar imagens de contêiner. |
| **Amazon ECS** | Orquestrador de contêineres nativo da AWS. |
| **Amazon EKS** | Kubernetes gerenciado. |
| **AWS Fargate** | Computação serverless para contêineres ECS e EKS; dispensa gerenciar servidores. |

### ECS x EKS x Fargate

- **ECS/EKS** definem como os contêineres são orquestrados.
- **Fargate** é uma opção de capacidade para executá-los sem gerenciar instâncias EC2.
- Se a empresa exige Kubernetes, a resposta tende a ser **EKS**.
- Se deseja orquestração nativa AWS, a resposta tende a ser **ECS**.
- Se não quer administrar servidores do cluster, use **Fargate**.

### AWS Lambda

O **AWS Lambda** executa código em resposta a eventos sem provisionar servidores.

- Serverless e orientado a eventos.
- Escala automaticamente.
- Cobrança baseada em solicitações e duração de execução.
- Adequado para processamento de eventos, automações, APIs e tarefas curtas.
- O cliente continua responsável pelo código, dependências, dados e permissões.

### Serverless não significa “sem servidores”

Servidores continuam existindo, mas são provisionados e gerenciados pela AWS. O cliente concentra-se no código, nos dados ou nos contêineres.

## 4.5 Redes e entrega de conteúdo

### Amazon VPC

O **Amazon Virtual Private Cloud (VPC)** cria uma rede virtual logicamente isolada.

Componentes importantes:

| Componente | Função |
|---|---|
| **CIDR** | Intervalo de endereços IP da VPC ou sub-rede. |
| **Subnet** | Segmento da VPC localizado em uma AZ. |
| **Route table** | Define para onde o tráfego da sub-rede é direcionado. |
| **Internet Gateway (IGW)** | Permite comunicação entre a VPC e a internet, quando as rotas e endereços permitem. |
| **NAT Gateway** | Permite que recursos em sub-rede privada iniciem conexões para fora sem aceitar conexões iniciadas da internet. |
| **Security Group** | Firewall stateful no nível do recurso/interface. |
| **Network ACL** | Firewall stateless no nível da sub-rede. |
| **VPC endpoint** | Acesso privado a serviços compatíveis sem usar internet pública. |

### Sub-rede pública e privada

- Uma sub-rede é considerada **pública** quando sua tabela de rotas possui rota para um Internet Gateway.
- Uma sub-rede **privada** não possui rota direta para o Internet Gateway.
- Ter endereço IP público sozinho não substitui a rota e o Internet Gateway.
- Bancos de dados e serviços internos normalmente ficam em sub-redes privadas.

### Conectividade híbrida e entre redes

| Serviço/recurso | Caso de uso |
|---|---|
| **AWS Site-to-Site VPN** | Conexão criptografada entre rede local e VPC pela internet. |
| **AWS Client VPN** | Acesso VPN gerenciado para usuários e dispositivos clientes. |
| **AWS Direct Connect** | Conexão de rede privada dedicada entre instalações do cliente e AWS. |
| **AWS Transit Gateway** | Hub central para conectar várias VPCs e redes on-premises. |
| **AWS PrivateLink** | Expor ou consumir serviços privadamente por endpoints, sem atravessar internet pública. |
| **VPC Peering** | Conexão privada direta entre duas VPCs; não é transitiva. |

#### VPN x Direct Connect

- **VPN:** mais rápida de configurar, criptografada, usa a internet e pode ter desempenho variável.
- **Direct Connect:** link dedicado e previsível, não usa a internet pública como caminho; criptografia não é implícita em todo cenário.
- É possível usar os dois para requisitos de segurança e resiliência.

### Amazon Route 53

Serviço de **DNS** altamente disponível e escalável.

- Registro de domínios.
- Resolução DNS.
- Roteamento de usuários para endpoints.
- Health checks e políticas de roteamento.
- O nome Route 53 faz referência à porta 53 usada pelo DNS.

### Amazon CloudFront

Rede de entrega de conteúdo (**CDN**).

- Mantém conteúdo em cache em edge locations.
- Reduz latência para usuários globais.
- Reduz carga na origem.
- Pode usar S3, load balancers e outros endpoints como origem.
- Integra-se com AWS WAF e Shield.

### AWS Global Accelerator

- Melhora disponibilidade e performance de aplicações globais usando a rede global AWS.
- Fornece endereços IP estáticos anycast e direciona tráfego ao endpoint regional saudável mais adequado.
- É adequado para aplicações TCP/UDP e não depende de cache.

### CloudFront x Global Accelerator

| CloudFront | Global Accelerator |
|---|---|
| CDN, atua principalmente com HTTP/HTTPS | Aceleração de rede para TCP/UDP |
| Usa cache em edge locations | Não é serviço de cache |
| Ideal para conteúdo web e APIs | Ideal para aplicações globais que precisam de IPs estáticos e menor latência de rede |

### Amazon API Gateway

- Cria, publica, protege e monitora APIs.
- É frequentemente usado com Lambda em arquiteturas serverless.
- Pode controlar autenticação, throttling e versões de API.

## 4.6 Armazenamento

### Tipos de armazenamento

| Tipo | Serviço principal | Uso |
|---|---|---|
| **Objeto** | Amazon S3 | Arquivos, backups, data lakes e conteúdo estático |
| **Bloco** | Amazon EBS | Disco para EC2 e cargas que precisam de volumes |
| **Arquivo** | Amazon EFS / Amazon FSx | Sistema de arquivos compartilhado |
| **Efêmero** | EC2 Instance Store | Dados temporários ligados ao host da instância |

### Amazon S3

O **Amazon Simple Storage Service (S3)** armazena dados como objetos em buckets.

Características:

- Armazenamento de objetos, não disco de bloco nem sistema de arquivos tradicional.
- Buckets são criados em uma região, mas seus nomes precisam ser globalmente únicos na partição AWS.
- Um objeto pode ter até 5 TB.
- Alta durabilidade; as classes comuns são projetadas para 99,999999999% (onze noves) de durabilidade.
- Escala automaticamente.
- Suporta versionamento, lifecycle, replicação, políticas de acesso, criptografia e eventos.
- Bloqueia acesso público por padrão em novos buckets/configurações modernas; o cliente continua responsável por permissões.

#### Recursos importantes do S3

| Recurso | Uso |
|---|---|
| **Versioning** | Manter várias versões e ajudar na recuperação de exclusões/sobrescritas. |
| **Lifecycle policies** | Mover objetos entre classes ou excluí-los automaticamente. |
| **Replication** | Copiar objetos para outro bucket na mesma região ou em outra região. |
| **S3 Object Lock** | Impedir exclusão ou alteração durante um período, atendendo cenários WORM. |
| **Bucket policy** | Política baseada em recurso que controla acesso ao bucket e objetos. |
| **Presigned URL** | Dar acesso temporário a um objeto sem torná-lo público. |

#### Classes de armazenamento S3

| Classe | Caso de uso |
|---|---|
| **S3 Standard** | Acesso frequente, baixa latência e alta disponibilidade em múltiplas AZs. |
| **S3 Intelligent-Tiering** | Padrão de acesso desconhecido ou variável; move objetos automaticamente entre tiers elegíveis. |
| **S3 Standard-IA** | Acesso infrequente, mas recuperação rápida; múltiplas AZs e cobrança de recuperação. |
| **S3 One Zone-IA** | Dados infrequentes, recriáveis e armazenados em uma única AZ. |
| **S3 Glacier Instant Retrieval** | Arquivo raramente acessado que precisa de recuperação em milissegundos. |
| **S3 Glacier Flexible Retrieval** | Arquivamento com recuperação de minutos a horas. |
| **S3 Glacier Deep Archive** | Menor custo para retenção muito longa; recuperação em horas. |

**Durabilidade não é disponibilidade.** Durabilidade mede a preservação dos dados; disponibilidade mede a possibilidade de acessá-los em determinado momento.

### EC2 Instance Store

- Armazenamento de bloco fisicamente ligado ao host.
- Muito rápido em cenários compatíveis.
- **Efêmero:** os dados são perdidos quando a instância é encerrada e em determinados eventos do host.
- Adequado para cache, buffers e dados temporários que podem ser recriados.

### Amazon EBS

O **Amazon Elastic Block Store (EBS)** fornece volumes de bloco para EC2.

- Um volume pertence a uma AZ e deve ser anexado a uma instância compatível na mesma AZ.
- Persiste ao parar uma instância.
- Ao encerrar a instância, a exclusão depende de `DeleteOnTermination`.
- Por padrão, o volume raiz criado no lançamento normalmente é excluído no encerramento; volumes de dados podem persistir conforme a configuração.
- Snapshots são backups incrementais gerenciados e podem ser usados para recriar volumes.
- Volumes podem ser criptografados com KMS.

### Amazon EFS

O **Amazon Elastic File System (EFS)** fornece sistema de arquivos compartilhado e elástico para cargas Linux.

- Interface NFS.
- Pode ser montado por múltiplas instâncias simultaneamente.
- Cresce e reduz automaticamente.
- Pode ter mount targets em múltiplas AZs.
- Adequado para conteúdo compartilhado, diretórios de usuários e aplicações que precisam de sistema de arquivos Linux.

### Amazon FSx

Família de sistemas de arquivos gerenciados para necessidades específicas:

- **FSx for Windows File Server:** compartilhamentos Windows/SMB e integração com Active Directory.
- **FSx for Lustre:** computação de alto desempenho e processamento intensivo.
- **FSx for NetApp ONTAP:** recursos e protocolos do NetApp ONTAP.
- **FSx for OpenZFS:** sistema de arquivos gerenciado baseado em OpenZFS.

### AWS Storage Gateway

Conecta ambientes on-premises ao armazenamento AWS.

- **File Gateway:** apresenta interface de arquivos e armazena objetos no S3.
- **Volume Gateway:** volumes de bloco com integração ao armazenamento AWS.
- **Tape Gateway:** substitui bibliotecas de fitas físicas por fitas virtuais na AWS.

### AWS Backup

- Centraliza e automatiza políticas de backup de diversos serviços.
- Permite retenção, agendamento e cópias entre contas/regiões compatíveis.
- Ajuda em governança e conformidade de backups.

### AWS Elastic Disaster Recovery

- Replica servidores continuamente para uma área de staging de baixo custo na AWS.
- Permite recuperação rápida de aplicações em caso de desastre.
- É voltado a disaster recovery, enquanto AWS Backup concentra-se na proteção e retenção de backups.

---

## 4.7 Bancos de dados

### Banco em EC2 x banco gerenciado

| Banco instalado no EC2 | Banco gerenciado, como RDS |
|---|---|
| Cliente instala e administra o mecanismo | AWS automatiza tarefas administrativas comuns |
| Cliente gerencia sistema operacional e patches | AWS gerencia sistema operacional e patches da plataforma |
| Maior controle | Menor esforço operacional |
| Adequado quando há requisitos especiais de acesso ao host | Adequado para mecanismos e configurações suportadas |

O cliente continua responsável pelos dados, contas do banco, consultas, schema, permissões e configuração segura da aplicação.

### Amazon RDS

O **Amazon Relational Database Service (RDS)** facilita criar, operar e escalar bancos relacionais.

- Automatiza tarefas como provisionamento, backups, manutenção e patches da plataforma.
- Suporta RDS para IBM Db2, MariaDB, Microsoft SQL Server, MySQL, Oracle Database e PostgreSQL.
- Amazon Aurora é acessado por meio do RDS, mas é um mecanismo criado pela AWS.
- Suporta opções de alta disponibilidade, réplicas de leitura, snapshots e recuperação point-in-time conforme o mecanismo.

#### Multi-AZ x Read Replica

| Multi-AZ | Read Replica |
|---|---|
| Principal objetivo: **alta disponibilidade** | Principal objetivo: **escalar leituras** |
| Réplica standby para failover | Réplica pode receber consultas de leitura |
| Normalmente replicação síncrona | Normalmente replicação assíncrona |
| Não é usada como solução principal de aumento de leitura | Pode ser promovida em cenários compatíveis |

### Amazon Aurora

- Banco relacional criado pela AWS.
- Compatível com MySQL ou PostgreSQL.
- Armazenamento distribuído e alta disponibilidade.
- Escala leituras por meio de réplicas Aurora.
- Indicado quando se deseja desempenho e disponibilidade de banco comercial com compatibilidade de mecanismos open source.

### Amazon DynamoDB

- Banco NoSQL totalmente gerenciado e serverless.
- Modelo key-value e documento.
- Baixa latência em qualquer escala.
- Escala automaticamente e não exige gerenciar servidores.
- Adequado para carrinhos, sessões, jogos, IoT e aplicações de grande escala.
- Não é substituto direto de um banco relacional quando joins e transações relacionais complexas são o requisito principal.

### Amazon ElastiCache

- Cache gerenciado em memória.
- Compatível com mecanismos como Valkey, Redis OSS e Memcached, conforme a oferta atual.
- Reduz carga e latência de bancos e aplicações.
- Adequado para cache de consultas, sessões e dados acessados com frequência.

### Amazon DocumentDB

- Banco de documentos gerenciado.
- Compatível com cargas e APIs do MongoDB.
- Indicado para dados JSON/documentos e aplicações que usam o modelo de documentos.

### Amazon Neptune

- Banco de grafos gerenciado.
- Adequado para relacionamentos altamente conectados.
- Casos de uso: redes sociais, detecção de fraude, recomendação e knowledge graphs.

### Escolha rápida de banco

| Requisito | Serviço provável |
|---|---|
| SQL e relacionamentos | RDS ou Aurora |
| Key-value/documento em grande escala e baixa latência | DynamoDB |
| Cache em memória | ElastiCache |
| Documentos compatíveis com MongoDB | DocumentDB |
| Relacionamentos em grafo | Neptune |
| Data warehouse e análise | Redshift |

## 4.8 Analytics

| Serviço | Função principal | Palavra-chave |
|---|---|---|
| **Amazon Athena** | Consultas SQL serverless diretamente em dados no S3. | SQL no S3 |
| **Amazon EMR** | Processar big data com frameworks como Apache Spark e Hadoop. | Cluster big data |
| **AWS Glue** | Integração de dados serverless, ETL e catálogo de dados. | ETL/Data Catalog |
| **Amazon Kinesis** | Coletar e processar dados de streaming em tempo real. | Streaming |
| **Amazon OpenSearch Service** | Busca, análise de logs e observabilidade. | Search/log analytics |
| **Amazon QuickSight** | Business intelligence, visualizações e dashboards. | BI/dashboard |
| **Amazon Redshift** | Data warehouse gerenciado para analytics em escala. | Data warehouse |

### Amazon Athena

- Executa SQL sobre dados no S3.
- Serverless: não exige provisionar cluster.
- Paga-se principalmente pela quantidade de dados consultados.
- Formatos colunares e particionamento podem reduzir os dados lidos e o custo.

### AWS Glue

- Descobre, prepara, move e integra dados.
- **Glue Data Catalog:** metadados e definição de tabelas usados por serviços como Athena.
- **Glue ETL:** transforma e carrega dados sem gerenciar servidores.
- Crawlers podem descobrir schemas e preencher o catálogo.

### Amazon Kinesis

- Trabalha com eventos e dados que chegam continuamente.
- Casos: telemetria, logs, cliques, IoT e analytics em tempo real.
- Diferente do SQS: Kinesis é voltado a streaming e processamento de sequência de registros; SQS é fila para desacoplamento de mensagens.

### Amazon Redshift

- Data warehouse colunar e gerenciado.
- Adequado para consultas analíticas sobre grandes volumes.
- Não é o banco transacional padrão de uma aplicação web.

### Amazon QuickSight

- Cria dashboards, análises e visualizações de BI.
- Conecta-se a diversas fontes de dados AWS e externas.
- É a resposta típica quando o cenário pede **visualização de dados de negócio**.

## 4.9 Inteligência artificial e machine learning

| Serviço | Capacidade |
|---|---|
| **Amazon SageMaker AI** | Criar, treinar e implantar modelos de machine learning. |
| **Amazon Comprehend** | Processamento de linguagem natural: sentimento, entidades e tópicos. |
| **Amazon Kendra** | Busca empresarial inteligente em conteúdo corporativo. |
| **Amazon Lex** | Interfaces conversacionais, chatbots e voz; tecnologia relacionada à Alexa. |
| **Amazon Polly** | Converter texto em fala. |
| **Amazon Rekognition** | Analisar imagens e vídeos, detectando objetos, pessoas, texto e conteúdo. |
| **Amazon Textract** | Extrair texto, formulários e tabelas de documentos digitalizados. |
| **Amazon Transcribe** | Converter fala em texto. |
| **Amazon Translate** | Tradução automática de idiomas. |
| **Amazon Q** | Assistente de IA generativa para trabalho e desenvolvimento, conforme a experiência/produto. |

### Como escolher

- **Texto → voz:** Polly.
- **Voz → texto:** Transcribe.
- **Um idioma → outro idioma:** Translate.
- **Sentimento e entidades em texto:** Comprehend.
- **Texto, tabelas e campos de documentos escaneados:** Textract.
- **Imagem ou vídeo:** Rekognition.
- **Chatbot:** Lex.
- **Busca em documentos corporativos:** Kendra.
- **Construir e treinar modelo próprio:** SageMaker AI.

> O antigo **Amazon CodeWhisperer** foi incorporado ao **Amazon Q Developer**. Use a nomenclatura atual, mas reconheça o nome antigo caso apareça em um material desatualizado.

## 4.10 Integração de aplicações

### Amazon SQS

O **Simple Queue Service (SQS)** fornece filas gerenciadas.

- Desacopla produtores e consumidores.
- Armazena mensagens até que sejam processadas.
- Ajuda a absorver picos e aumenta a resiliência.
- **Standard Queue:** alta escala, entrega pelo menos uma vez e ordenação best effort.
- **FIFO Queue:** preserva ordem e oferece recursos para evitar duplicidade no processamento.

### Amazon SNS

O **Simple Notification Service (SNS)** fornece publicação e assinatura (**pub/sub**).

- Um publicador envia uma mensagem a um tópico.
- Vários assinantes podem recebê-la.
- Entrega para destinos compatíveis, como SQS, Lambda, HTTP/S, e-mail e SMS.
- Adequado para fan-out e notificações.

### Amazon EventBridge

- Barramento de eventos serverless.
- Recebe eventos de serviços AWS, aplicações próprias e parceiros SaaS.
- Aplica regras e encaminha eventos para destinos.
- Adequado para arquiteturas orientadas a eventos e roteamento por conteúdo.

### AWS Step Functions

- Orquestra workflows por meio de máquinas de estado.
- Coordena Lambda e outros serviços.
- Representa etapas, decisões, paralelismo, tentativas e tratamento de erros.
- Adequado quando o cenário exige controlar uma sequência de tarefas.

### Comparação de mensageria

| Necessidade | Serviço |
|---|---|
| Desacoplar e processar cada mensagem | SQS |
| Enviar uma mensagem para muitos assinantes | SNS |
| Rotear eventos por regras e integrar fontes | EventBridge |
| Orquestrar uma sequência de etapas | Step Functions |

É comum combinar serviços: SNS pode distribuir mensagens para várias filas SQS; EventBridge pode acionar Lambda ou Step Functions.

## 4.11 Aplicações de negócio

| Serviço | Caso de uso |
|---|---|
| **Amazon Connect** | Contact center omnichannel na nuvem. |
| **Amazon SES** | Envio e recebimento de e-mails em escala por aplicações. |

**SES x SNS:** SES é serviço de e-mail; SNS é pub/sub e notificações para múltiplos protocolos.

## 4.12 Ferramentas de desenvolvimento

| Serviço | Função |
|---|---|
| **AWS CLI** | Administrar e automatizar a AWS por linha de comando. |
| **AWS CodeBuild** | Compilar código, executar testes e produzir artefatos. |
| **AWS CodePipeline** | Orquestrar etapas de entrega contínua em um pipeline. |
| **AWS X-Ray** | Rastrear requisições em aplicações distribuídas e identificar gargalos/erros. |

**CodeBuild executa o build; CodePipeline coordena o fluxo.**

## 4.13 Computação para usuário final

| Serviço | Caso de uso |
|---|---|
| **Amazon AppStream 2.0** | Transmitir aplicações desktop para o navegador sem reescrevê-las. |
| **Amazon WorkSpaces** | Desktops virtuais gerenciados. |
| **Amazon WorkSpaces Secure Browser** | Acesso seguro a sites e aplicações web por navegador isolado gerenciado. |

## 4.14 Frontend, mobile e IoT

| Serviço | Caso de uso |
|---|---|
| **AWS Amplify** | Criar, integrar, hospedar e implantar aplicações web e mobile. |
| **AWS AppSync** | Criar APIs GraphQL gerenciadas e sincronização de dados. |
| **AWS IoT Core** | Conectar, autenticar e trocar mensagens com dispositivos IoT. |

## 4.15 Gerenciamento e operações

### Amazon CloudWatch

- Coleta métricas, logs e eventos.
- Cria dashboards e alarmes.
- Pode executar ações quando um limite é atingido.
- Exemplo: alarme de CPU alta que inicia uma política de Auto Scaling.

### AWS CloudTrail

- Registra atividade da conta e chamadas de API.
- Mostra quem fez a ação, quando, a origem e quais parâmetros foram usados.
- É fundamental para auditoria, governança e investigação.
- **CloudTrail Insights** ajuda a identificar padrões incomuns de atividade de API quando habilitado.

### AWS Config

- Mantém inventário e histórico de configuração de recursos compatíveis.
- Avalia recursos com regras de conformidade.
- Responde como um recurso estava configurado em determinado momento.
- Não substitui CloudTrail nem CloudWatch.

### AWS Systems Manager

- Centraliza gerenciamento operacional de recursos AWS e híbridos.
- Oferece recursos para inventário, patching, automação, execução de comandos e armazenamento de parâmetros.
- Ajuda a operar frotas sem depender apenas de acesso manual aos servidores.

### AWS Health Dashboard e AWS Health API

- Fornecem visão personalizada de eventos AWS que podem afetar recursos e contas.
- Diferem da página pública de status porque apresentam contexto específico do ambiente do cliente.
- A API permite integrar eventos de saúde a ferramentas e automações, conforme elegibilidade.

### Ferramentas de gestão

| Serviço | Função |
|---|---|
| **AWS Compute Optimizer** | Recomenda configurações e rightsizing com base em métricas de utilização. |
| **AWS License Manager** | Gerencia uso de licenças de software e regras de licenciamento. |
| **Service Quotas** | Exibe e permite solicitar ajustes de cotas de serviços. |
| **AWS Well-Architected Tool** | Avalia cargas em relação aos pilares do Well-Architected Framework. |
| **AWS Management Console** | Interface gráfica para acessar serviços. |
| **AWS CloudFormation** | Provisionamento por infraestrutura como código. |
| **AWS Control Tower** | Landing zone e governança multiaccount. |
| **AWS Organizations** | Gerenciamento central de contas e cobrança consolidada. |
| **AWS Service Catalog** | Catálogo de produtos de TI aprovados. |
| **AWS Trusted Advisor** | Recomendações de boas práticas. |

---

# 5. Domínio 4 — Faturamento, preços e suporte (12%)

## 5.1 Princípios de preço AWS

Três ideias aparecem com frequência:

1. **Pagar conforme o uso:** sem grandes contratos ou investimentos antecipados para muitos serviços.
2. **Economizar com compromisso:** preços menores ao assumir compromisso de uso, como Savings Plans e RIs.
3. **Pagar menos por unidade com maior volume:** alguns serviços aplicam preços em faixas ou benefícios agregados.

O preço depende do serviço e pode considerar:

- Tempo ou capacidade de computação.
- Quantidade e classe de armazenamento.
- Número de solicitações.
- Dados processados.
- Transferência de dados.
- Região.
- Licenças.
- Nível de performance e recursos adicionais.

### Transferência de dados

Regras gerais, sujeitas a exceções por serviço:

- Entrada de dados da internet para a AWS costuma ser gratuita.
- Saída da AWS para a internet costuma ser cobrada.
- Transferência entre regiões normalmente é cobrada.
- Transferência entre AZs ou serviços pode ser cobrada, dependendo do caminho e do serviço.
- CloudFront pode reduzir custo e latência ao servir conteúdo em cache próximo do usuário.

Não memorize valores: reconheça que **data transfer out** é um componente importante de custo.

## 5.2 Revisão dos modelos de compra EC2

| Cenário | Melhor ponto de partida |
|---|---|
| Uso curto, novo ou imprevisível | On-Demand |
| Uso previsível com compromisso flexível de computação | Savings Plans |
| Uso estável e compatível com atributos de uma RI | Reserved Instances |
| Trabalho tolerante a interrupção | Spot |
| Garantia de capacidade em uma AZ | Capacity Reservation |
| Hardware físico dedicado e BYOL ligado ao servidor | Dedicated Host |
| Isolamento de hardware sem controle do host | Dedicated Instance |

### Desconto não é capacidade

- Savings Plans oferecem desconto, não reserva de capacidade.
- RI regional oferece benefício de faturamento, mas não reserva capacidade.
- RI zonal pode fornecer reserva de capacidade.
- On-Demand Capacity Reservation garante capacidade, mas não fornece desconto automaticamente.
- É possível combinar uma Capacity Reservation com descontos compatíveis, como Savings Plans.

## 5.3 AWS Free Tier

O Free Tier mudou para novas contas a partir de julho de 2025. No modelo atual:

- Novos clientes podem receber até **US$ 200 em créditos**: US$ 100 no cadastro e até US$ 100 adicionais ao concluir atividades elegíveis.
- É possível iniciar com um **Free account plan**, que dura até seis meses ou até o esgotamento dos créditos, conforme as regras do programa.
- O **Paid account plan** dá acesso completo e cobra o uso que ultrapassar créditos/ofertas gratuitas.
- Existem ofertas **Always Free** com limites mensais para serviços elegíveis.
- Contas antigas podem estar sujeitas às regras do modelo anterior.

O Free Tier não significa que toda a AWS é gratuita. Sempre configure orçamento e alertas e consulte a página atual do [AWS Free Tier](https://aws.amazon.com/free/).

## 5.4 Ferramentas de custos e faturamento

| Ferramenta | Pergunta que responde |
|---|---|
| **AWS Pricing Calculator** | Quanto uma arquitetura planejada poderá custar? |
| **AWS Cost Explorer** | Quanto gastei, onde gastei e qual é a tendência? |
| **AWS Budgets** | O custo ou uso real/previsto está chegando ao limite definido? |
| **AWS Cost and Usage Report (CUR)** | Onde obtenho o conjunto mais detalhado de dados de custo e uso? |
| **Cost allocation tags** | Como atribuo custos a projeto, equipe, aplicação ou centro de custo? |
| **AWS Compute Optimizer** | Os recursos estão super ou subdimensionados? |
| **AWS Trusted Advisor** | Que boas práticas podem melhorar custo, segurança, performance e resiliência? |
| **AWS Marketplace** | Como adquirir software e serviços de terceiros com cobrança integrada à AWS? |

### AWS Pricing Calculator

- Cria estimativas antes da implantação.
- Permite comparar configurações, regiões e modelos de compra.
- Organiza estimativas por grupos.
- Uma estimativa não é uma garantia de fatura; consumo real, impostos e preços podem variar.

### AWS Cost Explorer

- Visualiza e analisa custos e uso históricos.
- Filtra e agrupa por serviço, conta, região, tags e outras dimensões.
- Exibe tendências e previsões disponíveis.
- É usado para investigar gasto já realizado ou projetado com base no histórico.

### AWS Budgets

- Cria orçamentos de custo, uso e compromissos compatíveis.
- Envia alertas quando um limite real ou previsto é alcançado.
- Pode iniciar ações em cenários configurados.
- Alerta não significa que o recurso será automaticamente desligado.

### AWS Cost and Usage Report

- Fonte mais detalhada de dados de faturamento e uso.
- Pode entregar arquivos em um bucket S3.
- Permite análises próprias e integração com ferramentas analíticas.

### Cost allocation tags

- **AWS-generated tags:** criadas pela AWS.
- **User-defined tags:** criadas pelo cliente.
- Precisam ser ativadas como tags de alocação de custos para aparecer em relatórios de cobrança aplicáveis.
- Ajudam em chargeback, showback e divisão por projeto, equipe ou ambiente.

## 5.5 Cobrança consolidada no AWS Organizations

- A management account recebe uma fatura consolidada das member accounts.
- Cada conta continua separada para recursos, permissões e limites operacionais.
- O uso agregado pode gerar benefícios de preço por volume em serviços elegíveis.
- Benefícios de Reserved Instances e Savings Plans podem ser compartilhados entre contas, de acordo com compatibilidade e preferências configuradas.
- Contas podem ser organizadas em OUs, mas OUs não são centros de custo por si só; tags e categorias de custo ajudam a classificar gastos.
- SCPs tratam de permissões máximas, não de faturamento.

## 5.6 AWS Marketplace e parceiros

### AWS Marketplace

Catálogo digital para encontrar, testar, comprar e implantar ofertas de terceiros.

- Software, dados e serviços profissionais elegíveis.
- Cobrança pode ser integrada à fatura AWS.
- Facilita aquisições, contratos, licenças e entitlement.
- Produtos de terceiros continuam tendo condições e responsabilidades próprias.

### AWS Partner Network (APN)

Rede global de parceiros AWS.

- **Independent Software Vendors (ISVs):** desenvolvem produtos de software.
- **System Integrators (SIs):** ajudam a planejar, migrar, integrar e operar soluções.
- Parceiros podem receber treinamento, certificações, programas, eventos e benefícios comerciais conforme o nível e programa.

### AWS Professional Services e Solutions Architects

- **AWS Professional Services:** equipes que ajudam clientes em projetos e transformações complexas.
- **AWS Solutions Architects:** orientam arquitetura e uso de serviços AWS.
- Não devem ser confundidos com o suporte reativo de um plano do AWS Support.

## 5.7 Recursos técnicos e de suporte

| Recurso | Uso |
|---|---|
| **AWS Documentation** | Guias técnicos e referências oficiais. |
| **AWS Whitepapers** | Boas práticas, arquitetura, segurança e estratégia. |
| **AWS Prescriptive Guidance** | Padrões e orientações práticas para migração, modernização e operação. |
| **AWS Knowledge Center** | Respostas oficiais para dúvidas e problemas recorrentes, disponibilizadas no re:Post. |
| **AWS re:Post** | Comunidade de conhecimento e perguntas e respostas sobre AWS. |
| **AWS Support Center** | Criar e acompanhar casos de suporte e cobrança. |
| **AWS Health Dashboard** | Eventos personalizados que podem afetar contas e recursos. |
| **AWS Health API** | Acesso programático a eventos de saúde, conforme plano/elegibilidade. |
| **AWS Trusted Advisor** | Recomendações de boas práticas para o ambiente. |
| **AWS Trust & Safety** | Canal para denunciar abuso de recursos AWS, como spam, malware e conteúdo ilícito. |

## 5.8 Planos do AWS Support

> **Atenção à transição de 2026:** o guia oficial CLF-C02 ainda cita Developer, Business, Enterprise On-Ramp e Enterprise como exemplos. A AWS anunciou uma nova carteira formada por Business Support+, Enterprise Support e Unified Operations, enquanto planos legados passam por transição. Para a prova, reconheça os nomes do guia oficial e entenda também a carteira atual. Confira novamente este ponto próximo à data do exame.

### Basic Support

Incluído para todos os clientes:

- Atendimento a conta e faturamento.
- Documentação, whitepapers e AWS re:Post.
- AWS Health.
- Verificações principais/limitadas do Trusted Advisor.
- Não inclui suporte técnico completo de Cloud Support Engineers para arquitetura e troubleshooting.

### Planos legados ainda referenciados no guia CLF-C02

| Plano | Perfil e principais características |
|---|---|
| **Developer Support** | Desenvolvimento inicial; contato principal por e-mail em horário comercial; orientação geral. Descontinuação anunciada para 1º de janeiro de 2027. |
| **Business Support** | Cargas de produção; suporte técnico 24x7 por telefone, chat e web; contatos e casos ilimitados; conjunto completo do Trusted Advisor. Descontinuação anunciada para 1º de janeiro de 2027. |
| **Enterprise On-Ramp Support** | Cargas críticas em crescimento; recursos proativos e orientação de TAM compartilhada/pool; resposta mais rápida para incidentes críticos. |
| **Enterprise Support** | Cargas business-critical; Technical Account Manager designado, orientação proativa e menor tempo de resposta crítico. |

### Carteira atual anunciada pela AWS

| Plano | Indicado para | Diferencial principal |
|---|---|---|
| **Business Support+** | Produção | Suporte técnico 24x7 e resposta crítica mais rápida que o Business legado. |
| **Enterprise Support** | Cargas business-critical | TAM designado, orientação estratégica e recursos proativos. |
| **Unified Operations** | Cargas mission-critical | Equipe especializada, monitoramento e resposta crítica de maior prioridade. |

Não é necessário decorar preços exatos. Memorize a progressão:

- Basic: autoatendimento, conta/faturamento, Health e verificações básicas.
- Produção: suporte técnico 24x7.
- Enterprise: TAM e orientação proativa.
- Nível mais alto: suporte especializado para cargas de missão crítica.

---

# 6. Comparações essenciais

## 6.1 Observabilidade, auditoria e recomendações

| Se a questão pedir... | Resposta provável |
|---|---|
| Métrica, log, alarme ou dashboard | CloudWatch |
| Histórico de chamadas de API e ações do usuário | CloudTrail |
| Histórico de configuração e compliance de recurso | AWS Config |
| Evento AWS que afeta meus recursos | AWS Health Dashboard |
| Recomendações de boas práticas | Trusted Advisor |
| Rightsizing baseado em utilização | Compute Optimizer |
| Evidências para auditoria | Audit Manager |
| Relatórios de conformidade da AWS | Artifact |

## 6.2 Serviços de segurança

| Necessidade | Serviço |
|---|---|
| Controlar usuários, roles e políticas | IAM |
| SSO da força de trabalho em várias contas | IAM Identity Center |
| Login de clientes em aplicação web/mobile | Cognito |
| Chaves de criptografia gerenciadas | KMS |
| HSM dedicado | CloudHSM |
| Certificados TLS/SSL | ACM |
| Armazenar e rotacionar senhas/chaves de API | Secrets Manager |
| Detectar ameaças | GuardDuty |
| Encontrar vulnerabilidades | Inspector |
| Descobrir dados sensíveis no S3 | Macie |
| Centralizar achados | Security Hub |
| Investigar achados | Detective |
| Filtrar requisições web | WAF |
| Proteger contra DDoS | Shield |
| Centralizar políticas de firewall multiaccount | Firewall Manager |

## 6.3 Computação

| Necessidade | Serviço |
|---|---|
| Máquina virtual com controle do sistema | EC2 |
| Executar função orientada a evento | Lambda |
| Implantar aplicação a partir do código | Elastic Beanstalk |
| VPS simples com pacote previsível | Lightsail |
| Orquestração de contêiner nativa AWS | ECS |
| Kubernetes gerenciado | EKS |
| Executar contêiner sem gerenciar servidor | Fargate |
| Armazenar imagem de contêiner | ECR |
| Processamento em lote | AWS Batch |
| Infraestrutura AWS no data center do cliente | Outposts |

## 6.4 Armazenamento

| Critério | S3 | EBS | EFS | FSx | Instance Store |
|---|---|---|---|---|---|
| Tipo | Objeto | Bloco | Arquivo | Arquivo | Bloco efêmero |
| Uso comum | Arquivos, backup, data lake | Disco de EC2 | Compartilhamento Linux | Windows/Lustre/ONTAP/OpenZFS | Cache temporário |
| Compartilhado | Via API/HTTP | Normalmente uma instância por vez | Sim | Sim | Não |
| Escopo | Regional | Uma AZ | Regional/múltiplas AZs | Conforme o tipo | Host físico |
| Crescimento automático | Sim | Não, precisa redimensionar | Sim | Conforme configuração | Não |
| Persiste ao encerrar EC2 | Sim | Depende da configuração | Sim | Sim | Não |

## 6.5 Bancos e analytics

| Necessidade | Serviço |
|---|---|
| Relacional gerenciado | RDS |
| Relacional compatível com MySQL/PostgreSQL criado pela AWS | Aurora |
| NoSQL key-value/documento serverless | DynamoDB |
| Cache em memória | ElastiCache |
| Documento compatível com MongoDB | DocumentDB |
| Grafo | Neptune |
| Data warehouse | Redshift |
| SQL serverless sobre S3 | Athena |
| ETL e catálogo | Glue |
| Streaming | Kinesis |
| BI e dashboards | QuickSight |
| Big data com Spark/Hadoop | EMR |
| Busca e análise de logs | OpenSearch Service |

## 6.6 Redes

| Necessidade | Serviço/recurso |
|---|---|
| Rede virtual isolada | VPC |
| Dar internet a recurso público | Internet Gateway + rota + endereço apropriado |
| Saída de internet para sub-rede privada | NAT Gateway |
| DNS e registro de domínio | Route 53 |
| CDN e cache | CloudFront |
| Aceleração TCP/UDP sem cache | Global Accelerator |
| Conexão híbrida criptografada pela internet | Site-to-Site VPN |
| Conexão privada dedicada | Direct Connect |
| Conectar muitas VPCs/redes como hub | Transit Gateway |
| Acesso privado a serviços | PrivateLink/VPC endpoint |
| Firewall stateful do recurso | Security Group |
| Firewall stateless da sub-rede | Network ACL |

## 6.7 Custos

| Momento/necessidade | Ferramenta |
|---|---|
| Antes de implantar | Pricing Calculator |
| Depois de gastar/analisar tendência | Cost Explorer |
| Definir limite e alerta | Budgets |
| Dados mais granulares para análise | Cost and Usage Report |
| Separar custo por projeto/equipe | Cost allocation tags |
| Recomendar tamanho de recurso | Compute Optimizer |
| Recomendações em várias categorias | Trusted Advisor |

---

# 7. Serviços no escopo da CLF-C02

Esta é a checklist oficial de serviços **in scope** na versão consultada do guia. A lista é não exaustiva e pode mudar. Para cada item, saiba pelo menos a categoria e o caso de uso principal.

## Analytics

- [ ] Amazon Athena
- [ ] Amazon EMR
- [ ] AWS Glue
- [ ] Amazon Kinesis
- [ ] Amazon OpenSearch Service
- [ ] Amazon QuickSight
- [ ] Amazon Redshift

## Application Integration

- [ ] Amazon EventBridge
- [ ] Amazon Simple Notification Service (SNS)
- [ ] Amazon Simple Queue Service (SQS)
- [ ] AWS Step Functions

## Business Applications

- [ ] Amazon Connect
- [ ] Amazon Simple Email Service (SES)

## Cloud Financial Management

- [ ] AWS Budgets
- [ ] AWS Cost and Usage Reports
- [ ] AWS Cost Explorer
- [ ] AWS Marketplace

## Compute

- [ ] AWS Batch
- [ ] Amazon EC2
- [ ] AWS Elastic Beanstalk
- [ ] Amazon Lightsail
- [ ] AWS Outposts

## Containers

- [ ] Amazon Elastic Container Registry (ECR)
- [ ] Amazon Elastic Container Service (ECS)
- [ ] Amazon Elastic Kubernetes Service (EKS)

## Customer Enablement

- [ ] AWS Support

## Database

- [ ] Amazon Aurora
- [ ] Amazon DocumentDB
- [ ] Amazon DynamoDB
- [ ] Amazon ElastiCache
- [ ] Amazon Neptune
- [ ] Amazon RDS

## Developer Tools

- [ ] AWS CLI
- [ ] AWS CodeBuild
- [ ] AWS CodePipeline
- [ ] AWS X-Ray

## End User Computing

- [ ] Amazon AppStream 2.0
- [ ] Amazon WorkSpaces
- [ ] Amazon WorkSpaces Secure Browser

## Frontend Web and Mobile

- [ ] AWS Amplify
- [ ] AWS AppSync

## Internet of Things (IoT)

- [ ] AWS IoT Core

## Machine Learning

- [ ] Amazon Comprehend
- [ ] Amazon Kendra
- [ ] Amazon Lex
- [ ] Amazon Polly
- [ ] Amazon Q
- [ ] Amazon Rekognition
- [ ] Amazon SageMaker AI
- [ ] Amazon Textract
- [ ] Amazon Transcribe
- [ ] Amazon Translate

## Management and Governance

- [ ] AWS Auto Scaling
- [ ] AWS CloudFormation
- [ ] AWS CloudTrail
- [ ] Amazon CloudWatch
- [ ] AWS Compute Optimizer
- [ ] AWS Config
- [ ] AWS Control Tower
- [ ] AWS Health Dashboard
- [ ] AWS License Manager
- [ ] AWS Management Console
- [ ] AWS Organizations
- [ ] AWS Service Catalog
- [ ] Service Quotas
- [ ] AWS Systems Manager
- [ ] AWS Trusted Advisor
- [ ] AWS Well-Architected Tool

## Migration and Transfer

- [ ] AWS Application Discovery Service
- [ ] AWS Application Migration Service
- [ ] AWS Database Migration Service (DMS)
- [ ] Migration Evaluator
- [ ] AWS Migration Hub
- [ ] AWS Schema Conversion Tool (SCT)
- [ ] AWS Snow Family

## Networking and Content Delivery

- [ ] Amazon API Gateway
- [ ] Amazon CloudFront
- [ ] AWS Direct Connect
- [ ] AWS Global Accelerator
- [ ] AWS PrivateLink
- [ ] Amazon Route 53
- [ ] AWS Transit Gateway
- [ ] Amazon VPC
- [ ] AWS VPN
- [ ] AWS Site-to-Site VPN
- [ ] AWS Client VPN

## Security, Identity and Compliance

- [ ] AWS Artifact
- [ ] AWS Audit Manager
- [ ] AWS Certificate Manager (ACM)
- [ ] AWS CloudHSM
- [ ] Amazon Cognito
- [ ] Amazon Detective
- [ ] AWS Directory Service
- [ ] AWS Firewall Manager
- [ ] Amazon GuardDuty
- [ ] AWS Identity and Access Management (IAM)
- [ ] AWS IAM Identity Center
- [ ] Amazon Inspector
- [ ] AWS Key Management Service (KMS)
- [ ] Amazon Macie
- [ ] AWS Resource Access Manager (RAM)
- [ ] AWS Secrets Manager
- [ ] AWS Security Hub
- [ ] AWS Shield
- [ ] AWS WAF

## Serverless

- [ ] AWS Fargate
- [ ] AWS Lambda

## Storage

- [ ] AWS Backup
- [ ] Amazon Elastic Block Store (EBS)
- [ ] Amazon Elastic File System (EFS)
- [ ] AWS Elastic Disaster Recovery
- [ ] Amazon FSx
- [ ] Amazon S3
- [ ] Amazon S3 Glacier
- [ ] AWS Storage Gateway

> Não tente decorar uma enciclopédia de cada serviço. Se você consegue explicar o serviço em uma frase e diferenciá-lo dos dois serviços mais parecidos, está no nível esperado para a maior parte das questões Foundational.

---

# 8. Pegadinhas frequentes

1. **700 pontos não significa necessariamente 70% de acertos.** A pontuação é escalonada.
2. **Uma AZ não é apenas um data center.** Ela pode conter um ou mais data centers.
3. **Edge location não é AZ.** Edge aproxima conteúdo; AZ hospeda recursos regionais.
4. **Multi-AZ normalmente busca alta disponibilidade; Multi-Region atende também DR, alcance global e soberania.**
5. **Escalabilidade não é elasticidade.** Elasticidade responde dinamicamente à demanda.
6. **ELB não aumenta instâncias.** Ele distribui tráfego; Auto Scaling ajusta capacidade.
7. **Security Group é stateful e só possui regras Allow.** Network ACL é stateless e aceita Allow/Deny.
8. **Uma sub-rede não é pública apenas por ter nome ou IP público.** Precisa de rota para Internet Gateway.
9. **NAT Gateway permite saída da sub-rede privada.** Ele não torna o recurso diretamente acessível da internet.
10. **VPN usa a internet; Direct Connect é conexão dedicada.** Direct Connect não implica criptografia automática em todos os cenários.
11. **Route 53 é DNS; CloudFront é CDN; Global Accelerator melhora o caminho de rede e não faz cache.**
12. **ECS e EKS são orquestradores; Fargate é capacidade serverless para contêineres.**
13. **Lambda executa código; Fargate executa contêineres.**
14. **Serverless não remove a responsabilidade sobre código, dados e IAM.**
15. **Parar EC2 não é encerrar EC2.** O comportamento de cobrança e persistência é diferente.
16. **EBS não é sempre preservado ao encerrar uma instância.** Verifique `DeleteOnTermination`.
17. **Instance Store é efêmero; EBS é persistente conforme configuração.**
18. **EBS é bloco em uma AZ; EFS é sistema de arquivos compartilhado.**
19. **O nome do bucket S3 é globalmente único, mas o bucket é criado em uma região.**
20. **Durabilidade não é disponibilidade.** Onze noves referem-se à durabilidade projetada do S3.
21. **S3 One Zone-IA não é apropriado para a única cópia de dados críticos.**
22. **RDS Multi-AZ é principalmente disponibilidade; Read Replica é principalmente escala de leitura.**
23. **Redshift é analytics/data warehouse, não o banco transacional padrão.**
24. **DMS move/replica dados; SCT converte schema e código.**
25. **SQS é fila; SNS é pub/sub; EventBridge roteia eventos; Step Functions orquestra etapas.**
26. **CloudWatch monitora; CloudTrail audita APIs; Config acompanha configuração e compliance.**
27. **GuardDuty detecta ameaças; Inspector encontra vulnerabilidades; Macie encontra dados sensíveis.**
28. **Security Hub centraliza achados; Detective ajuda a investigá-los.**
29. **WAF protege a camada web; Shield protege contra DDoS.**
30. **Artifact fornece relatórios/acordos; Audit Manager coleta evidências de auditoria.**
31. **IAM Identity Center atende workforce/SSO; Cognito atende usuários de aplicações.**
32. **Role fornece credenciais temporárias.** Não compartilhe access keys entre pessoas ou serviços.
33. **Explicit Deny prevalece sobre Allow.**
34. **SCP não concede acesso.** Ela limita o que políticas das contas podem permitir.
35. **KMS administra chaves de criptografia; Secrets Manager administra segredos.**
36. **Pricing Calculator estima; Cost Explorer analisa; Budgets alerta.**
37. **Savings Plans fornecem desconto, não garantia de capacidade.**
38. **Capacity Reservation garante capacidade, não desconto automático.**
39. **Spot não é mais leilão.** É capacidade ociosa com possibilidade de interrupção.
40. **Free Tier não impede cobranças.** Créditos e ofertas têm limites e condições.
41. **Basic Support não oferece o mesmo suporte técnico dos planos pagos.**
42. **A AWS ser responsável pela segurança da nuvem não significa que ela protege automaticamente dados e permissões mal configurados pelo cliente.**
43. **Serviço gerenciado reduz tarefas operacionais, mas não elimina a responsabilidade do cliente.**
44. **AWS Marketplace contém produtos de terceiros.** A AWS facilita aquisição e cobrança, mas o fornecedor e o cliente mantêm responsabilidades próprias.

---

# 9. Checklist de revisão

## Domínio 1 — Conceitos de nuvem

- [ ] Explico as seis vantagens clássicas da nuvem.
- [ ] Diferencio CAPEX e OPEX.
- [ ] Diferencio escalabilidade, elasticidade, alta disponibilidade, tolerância a falhas e durabilidade.
- [ ] Conheço os seis pilares do Well-Architected Framework.
- [ ] Conheço as seis perspectivas e os resultados de negócio do AWS CAF.
- [ ] Diferencio cloud, híbrido e on-premises.
- [ ] Conheço as sete estratégias de migração.
- [ ] Associo Discovery Service, Migration Evaluator, Migration Hub, MGN, DMS, SCT e Snow Family aos respectivos casos.
- [ ] Entendo rightsizing, automação, economia de escala, BYOL e license included.

## Domínio 2 — Segurança e conformidade

- [ ] Explico segurança **da** nuvem e segurança **na** nuvem.
- [ ] Comparo responsabilidades em EC2, RDS e Lambda.
- [ ] Diferencio usuário, grupo, role e política IAM.
- [ ] Sei que Explicit Deny prevalece e que SCP não concede permissão.
- [ ] Conheço as boas práticas do usuário root, MFA e credenciais temporárias.
- [ ] Diferencio IAM Identity Center e Cognito.
- [ ] Diferencio KMS, CloudHSM, ACM e Secrets Manager.
- [ ] Diferencio GuardDuty, Inspector, Macie, Security Hub e Detective.
- [ ] Diferencio WAF e Shield.
- [ ] Diferencio CloudWatch, CloudTrail e Config.
- [ ] Sei quando usar Artifact e Audit Manager.
- [ ] Entendo criptografia em repouso e em trânsito.
- [ ] Entendo Organizations, OUs, SCPs, Control Tower, RAM e Service Catalog.

## Domínio 3 — Tecnologia e serviços

- [ ] Diferencio console, CLI, SDK, API e CloudFormation.
- [ ] Diferencio região, AZ e edge location.
- [ ] Sei quando usar Multi-AZ e Multi-Region.
- [ ] Conheço famílias de EC2 e opções de compra.
- [ ] Diferencio EC2, Lambda, Elastic Beanstalk, Lightsail, Batch e Outposts.
- [ ] Diferencio ECS, EKS, ECR e Fargate.
- [ ] Entendo VPC, sub-redes, rotas, IGW, NAT, SG e NACL.
- [ ] Diferencio VPN, Direct Connect, Transit Gateway e PrivateLink.
- [ ] Diferencio Route 53, CloudFront e Global Accelerator.
- [ ] Diferencio S3, EBS, EFS, FSx e Instance Store.
- [ ] Conheço as classes S3 pelo caso de uso.
- [ ] Diferencio RDS, Aurora, DynamoDB, ElastiCache, DocumentDB, Neptune e Redshift.
- [ ] Associo Athena, Glue, Kinesis, EMR, OpenSearch e QuickSight aos casos corretos.
- [ ] Associo os serviços de IA/ML às modalidades de texto, voz, imagem, documento, tradução e modelos próprios.
- [ ] Diferencio SQS, SNS, EventBridge e Step Functions.
- [ ] Revisei todos os serviços da checklist de escopo ao menos em uma frase.

## Domínio 4 — Faturamento, preços e suporte

- [ ] Diferencio On-Demand, Savings Plans, RI, Spot, Dedicated Hosts e Capacity Reservations.
- [ ] Entendo custos gerais de transferência de entrada e saída.
- [ ] Diferencio Pricing Calculator, Cost Explorer, Budgets e CUR.
- [ ] Entendo cost allocation tags.
- [ ] Entendo cobrança consolidada e compartilhamento de descontos.
- [ ] Conheço o AWS Marketplace, APN, Professional Services e Solutions Architects.
- [ ] Conheço Documentation, Whitepapers, Prescriptive Guidance, Knowledge Center, re:Post e Support Center.
- [ ] Diferencio AWS Health e Trusted Advisor.
- [ ] Reconheço os planos de suporte citados no guia e a transição atual da carteira.

## Glossário rápido

| Sigla | Significado |
|---|---|
| **AMI** | Amazon Machine Image |
| **API** | Application Programming Interface |
| **AZ** | Availability Zone |
| **BYOL** | Bring Your Own License |
| **CAPEX** | Capital Expenditure |
| **CDN** | Content Delivery Network |
| **CIDR** | Classless Inter-Domain Routing |
| **DDoS** | Distributed Denial of Service |
| **DNS** | Domain Name System |
| **DR** | Disaster Recovery |
| **ETL** | Extract, Transform, Load |
| **HSM** | Hardware Security Module |
| **IaC** | Infrastructure as Code |
| **IAM** | Identity and Access Management |
| **MFA** | Multi-Factor Authentication |
| **NACL** | Network Access Control List |
| **NAT** | Network Address Translation |
| **OPEX** | Operational Expenditure |
| **OU** | Organizational Unit |
| **RPO** | Recovery Point Objective: perda de dados máxima aceitável medida no tempo |
| **RTO** | Recovery Time Objective: tempo máximo aceitável para restaurar o serviço |
| **SCP** | Service Control Policy |
| **SDK** | Software Development Kit |
| **SLA** | Service Level Agreement |
| **TAM** | Technical Account Manager |
| **TCO** | Total Cost of Ownership |
| **TLS** | Transport Layer Security |
| **VPC** | Virtual Private Cloud |

## Estratégia para responder às questões

1. Identifique exatamente o que foi pedido: **menor custo**, **menor esforço operacional**, **alta disponibilidade**, **auditoria**, **tempo real**, **conexão privada** etc.
2. Destaque as restrições: sem servidor, sem interrupção, acesso infrequente, múltiplas contas, dados sensíveis, tráfego web.
3. Elimine serviços de outra categoria.
4. Entre duas respostas possíveis, escolha a que satisfaz todos os requisitos com menor complexidade.
5. Em questões com múltiplas respostas, confirme quantas alternativas devem ser selecionadas.
6. Não deixe questões em branco: não há penalidade adicional por chute.
7. Marque questões demoradas para revisão e preserve tempo para o final.

---

# 10. Recursos oficiais

## Exame e preparação

- [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/)
- [Guia oficial CLF-C02 em HTML](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html)
- [Guia oficial CLF-C02 em PDF](https://docs.aws.amazon.com/pdfs/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.pdf)
- [Serviços no escopo](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/clf-02-in-scope-services.html)
- [Serviços fora do escopo](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/clf-02-out-of-scope-services.html)
- [AWS Skill Builder](https://skillbuilder.aws/)
- [Preparação e questões práticas oficiais](https://aws.amazon.com/certification/certification-prep/)

## Arquitetura e segurança

- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- [AWS Architecture Center](https://aws.amazon.com/architecture/)
- [AWS Cloud Adoption Framework](https://aws.amazon.com/cloud-adoption-framework/)
- [AWS Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)
- [AWS Security Center](https://aws.amazon.com/security/)
- [AWS Compliance](https://aws.amazon.com/compliance/)

## Custos e suporte

- [AWS Pricing Calculator](https://calculator.aws/)
- [AWS Free Tier](https://aws.amazon.com/free/)
- [AWS Support Plans](https://aws.amazon.com/premiumsupport/plans/)
- [AWS re:Post Knowledge Center](https://repost.aws/knowledge-center/)

---

## Observação final

A lista oficial de serviços é não exaustiva e sujeita a alterações. Faça a última revisão diretamente no guia oficial perto da data da prova, principalmente para:

- Serviços renomeados.
- AWS Free Tier.
- Planos do AWS Support.
- Serviços adicionados ou removidos do escopo.
- Características comerciais, percentuais de desconto e limites.

Boa prova! ☁️

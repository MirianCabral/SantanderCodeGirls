# Livro de Feitiços 🪄
![Gif Harry Potter](/Gif/giphy.gif)
#### O Livro de feitiços funciona como um guia de conceitos dos meus projetos, inspirado em Harry Potter. 

## 1️⃣ **Conceitos de Nuvem e AWS**

- AWS (Amazon Web Services): uma plataforma de serviços de computação em nuvem oferecida pela Amazon
- Cloud Computing: É a entrega sob demanda de recursos computacionais
- Workloads: Quantidade de processamento que um sistema executa em um determinado período
- Regions (Regiões): É uma área geográfica específica onde a AWS implanta sua infraestrutura de nuvem
- Availability Zones (Zonas de Disponibilidade): É um ou mais data centers isolados dentro de uma AWS Region
- Serviços Gerenciados: É um serviço que a AWS opera e gerencia, cuidando de tarefas como infraestrutura subjacente, atualizações, backups e replicação.
- Cluster: É um grupo de servidores interconectados que trabalham juntos como um único sistema para processar tarefas, oferecendo alta disponibilidade, escalabilidade e balanceamento de carga

----------

## 2️⃣ **Modelos de Computação na Nuvem**

-   IaaS (Infrastructure as a Service): É um modelo de computação em nuvem que fornece recursos de TI como servidores, armazenamento e rede pela internet, sob demanda e com pagamento pelo uso.
-   PaaS (Platform as a Service): É um modelo de computação em nuvem que oferece um ambiente completo para o desenvolvimento, execução e gerenciamento de aplicações sem a necessidade de gerenciar a infraestrutura subjacente.
-   SaaS (Software as a Service): É um modelo de distribuição de software baseado na nuvem em que os usuários acessam o aplicativo pela internet através de uma assinatura, em vez de instalá-lo localmente.

----------

## 3️⃣ **EC2 – Elastic Compute Cloud**

-   Instância EC2: É um servidor virtual na nuvem da AWS que permite executar aplicativos sem precisar de hardware físico.
-   On-Demand: Instâncias sob demanda são um modelo de preços da AWS que permite pagar pela capacidade computacional por hora ou por segundo, sem compromissos de longo prazo.

----------

## 4️⃣ **Armazenamento**

### Amazon EBS

-   Elastic Block Store (EBS): É um serviço da AWS que fornece armazenamento em blocos de alto desempenho e alta disponibilidade para instâncias do Amazon EC2

### Amazon S3

-   Buckets: É um contêiner para armazenar objetos no serviço de armazenamento na nuvem da AWS, o Amazon S3.
-   Classes de Armazenamento: Standard, Intelligent-Tiering, Glacier

### Amazon Glacier

-   Arquivamento de Dados: É um serviços de armazenamento de baixo custo projetado para arquivamentos de dados de longo prazo e acesso pouco frequente.

----------

## 5️⃣ **Otimização de Recursos**

-   Escalar Horizontalmente: É adicionar mais máquinas ou nós ao sistema para distribuir a carga.
-   Escalar Verticalmente: É aumentar recursos (como CPU e RAM) de um servidor existente.

----------

## 6️⃣ **Serverless / Lambda**

-   Serverless: É um modelo de computação que permite aos desenvolvedores criar e executar aplicações sem precisar gerenciar servidores ou infraestrutura
-   Lambda Function: Permite executar código sem precisar provisionar ou gerenciar servidores.
-   Execução Sob Demanda: É um modelo de precificação flexível onde você paga pela capacidade de computação conforme a usa.
-   Escalonamento Automático: É um serviço que ajusta a capacidade de recursos como instâncias do EC2 e outros serviços.

----------

## 7️⃣ **Redes AWS**

-   Virtual Private Cloud (VPC): É uma seção isolada da nuvem AWS onde você pode lançar recursos em uma rede virtual que você define, com controle total sobre sua configuração.
-   Subnets (Sub-redes): É uma divisão lógica de uma rede de computadores maior em redes e menos gerenciáveis.
-   Grupos de Segurança (Security Groups): São um firewall virtual que controla o tráfego de entrada e saída das instâncias EC2, especificando quais portas e protocolos são permitidos
-   Route 53: é um serviço de DNS escalável e altamente disponível da AWS que traduz nomes de sites em endereços IP numéricos.
-   CloudFront: É uma rede de entrega de conteúdo (CDN) da AWS que acelera a entrega de sites, vídeos, aplicações e APIs aos usuários finais.
-   Elastic Load Balancer: É um serviço que distribui automaticamente o tráfego de rede de aplicações entre múltiplos destinos, como servidores no Amazon EC2, contêineres ou endereços IP.
-   Application Load Balancer (ALB): Roteia o tráfego para solicitações baseadas em HTTP/HTTPS.
-   Network Load Balancer (NLB): Ideal para tráfego de rede de alta performance, distribuindo conexões baseadas em TCP, UDP e TLS.
-   Gateway Load Balancer (GLB): Roteia o tráfego para dispositivos virtuais de terceiros, como firewalls, para otimizar e escalar o uso desses dispositivos.
-   Classic Load Balancer (CLB): Funciona em redes do EC2 clássicas e é ideal para balancear o tráfego para servidores da mesma rede.

----------

## 8️⃣ **Banco de Dados AWS**

-   Relational Database Service (RDS): É um serviços gerenciamento que simplifica a configuração, operação e escalabilidade de bancos de dados relacionais na nuvem.
-   Amazon DynamoDB: É um serviço de banco de dados NoSQL gerenciado e sem servidor que suporta modelos de dados chave-valor e de documentos
-   NoSQL: Refere-se a um tipo de banco de dados não relacional que armazena dados em formatos flexíveis, em vez de tabelas rígidas

----------

## 9️⃣ **Backup e Recuperação**

-   Plano de Recuperação de Desastres (DR): É um conjunto de politicas e procedimentos que uma organização usa para restaurar seus sistemas de TI, dados e operações após um evento disruptivo, como um ataque cibernético ou desastre natural.
-   Backup Drill: Conduz exercícios de simulação de desastres para validar a eficácia dos planos de recuperação.
-   Criptografia de Dados (TLS, S3 Encryption, RDS Encryption): É o processo de proteger dados, tanto em trânsito quanto em repouso, usando algoritmos de criptografia e chaves.
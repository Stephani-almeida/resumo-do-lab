Resumo do Lab DIO: Meus Primeiros Passos na Nuvem com Azure 🚀
______________________________________________________________________________________________________________________________________________________________

Olá! Este repositório é como um diário de bordo do meu aprendizado no laboratório da Digital Innovation One (DIO), onde mergulhei nos Fundamentos da Computação em Nuvem com Microsoft Azure. Aqui, vou compartilhar o que aprendi e como essa experiência me ajudou a dar os primeiros passos nesse universo fascinante.
______________________________________________________________________________________________________________________________________________________________

☁️ Como a Computação em Nuvem Funciona?
Comecei entendendo que a computação em nuvem é uma forma super prática e flexível de usar recursos de tecnologia. Em vez de comprar e manter servidores e data centers caríssimos, a gente "aluga" esses recursos (como armazenamento, poder de processamento, softwares) de grandes empresas pela internet. É como ter um supercomputador à disposição, mas pagando só pelo que usa! Essa flexibilidade é um game-changer para empresas e projetos.
______________________________________________________________________________________________________________________________________________________________

🏗️ Infraestrutura: Do "Aqui" ao "Na Nuvem"
Entendi as três principais formas de lidar com a infraestrutura de TI:

🏢💻 On-Premise (Local): É o jeito tradicional. A empresa compra, instala e cuida de tudo: servidores, softwares, rede... tudo dentro das suas próprias instalações. Tem muito controle, mas o investimento inicial e a manutenção são bem altos, exigindo espaço e gente especializada.

Ponto Forte: Controle total.

Ponto Fraco: Caro e exige muita manutenção própria.
______________________________________________________________________________________________________________________________________________________________

☁️🌐 Modelo Cloud (Nuvem): Aqui, a gente não tem nada físico. Usamos os recursos de TI (como servidores e bancos de dados) que são de provedores como Microsoft Azure, AWS ou Google Cloud. A grande sacada é a escalabilidade: se precisar de mais recursos, é só pedir e a nuvem entrega na hora, sem precisar comprar nada novo. Isso barateia o custo, acelera os projetos e dá acesso a tecnologias de ponta.

Ponto Forte: Custos mais baixos, flexibilidade e escalabilidade (cresce e diminui conforme a sua necessidade).

Ponto Fraco: Dependemos da internet para acessar tudo.
______________________________________________________________________________________________________________________________________________________________

🌍🔗 Modelo Hybrid (Híbrido): É a melhor dos dois mundos! Combinamos o que temos "em casa" (on-premise) com o que usamos na nuvem. Por exemplo, informações super confidenciais podem ficar nos nossos servidores, enquanto aplicativos que precisam de muita flexibilidade vão para a nuvem. Oferece bastante flexibilidade para escolher o que fica onde, mas exige um pouco mais de organização para gerenciar os dois ambientes.

Ponto Forte: Muita flexibilidade para otimizar custos e segurança.

Ponto Fraco: A gestão pode ser mais complexa.
______________________________________________________________________________________________________________________________________________________________

🛠️ Serviços na Nuvem: Como a Nuvem me Serve?

Aprendi que os provedores de nuvem oferecem serviços em diferentes "níveis", cada um com um controle e responsabilidade diferentes pra gente:

IaaS (Infrastructure as a Service - Infraestrutura como Serviço): É a base. O provedor me dá a infraestrutura (servidores virtuais, armazenamento, rede), e eu cuido do sistema operacional, dos softwares e dos meus dados. É como ter um terreno e construir a casa do meu jeito.

Exemplos: Máquinas Virtuais (VMs) no Azure, armazenamento de dados.

Ponto Forte: Muita flexibilidade e controle.

Ponto Fraco: Maior responsabilidade sobre o gerenciamento.
______________________________________________________________________________________________________________________________________________________________
PaaS (Platform as a Service - Plataforma como Serviço): Aqui, o provedor já entrega uma "plataforma" pronta para eu desenvolver e rodar meus aplicativos, sem me preocupar com o sistema operacional ou o servidor. É como ter uma casa já construída, onde eu só preciso mobiliar.

Exemplos: Azure App Services (para rodar sites e aplicativos), Azure SQL Database.

Ponto Forte: Facilita muito o desenvolvimento, foco no meu código.

Ponto Fraco: Menos controle sobre a infraestrutura por baixo.
______________________________________________________________________________________________________________________________________________________________

SaaS (Software as a Service - Software como Serviço): É a forma mais "pronta". Eu acesso um software completo pela internet, e o provedor cuida de tudo (infraestrutura, manutenção, atualizações). É como alugar uma casa já mobiliada e com tudo funcionando.

Exemplos: Microsoft 365 (Word, Excel online), Gmail, Slack.

Ponto Forte: Super fácil de usar, sem nenhuma preocupação com gestão ou instalação.

Ponto Fraco: Menor controle sobre o software e os dados.
______________________________________________________________________________________________________________________________________________________________

BaaS (Backend as a Service - Backend como Serviço): Focado em quem desenvolve apps. O BaaS oferece recursos de "backend" prontos, como gestão de usuários, bancos de dados, e notificações, sem eu ter que construir isso do zero.

Exemplos: Firebase, AWS Amplify.

Ponto Forte: Agiliza muito o desenvolvimento de aplicativos.

Ponto Fraco: Você depende das funcionalidades que o provedor oferece.
______________________________________________________________________________________________________________________________________________________________

FaaS (Function as a Service - Função como Serviço): Também conhecido como "Serverless". Aqui, eu só escrevo pequenos trechos de código (funções) que executam uma tarefa específica, e a nuvem se encarrega de rodá-los quando necessário, sem eu me preocupar com servidores. Eu pago apenas pelo tempo que meu código está executando.

Exemplos: Azure Functions, AWS Lambda.

Ponto Forte: Escalabilidade automática, pago só pelo uso real, sem gerenciar servidores.

Ponto Fraco: Pode ser mais complexo para aplicações grandes ou com tempo de execução muito longo.
______________________________________________________________________________________________________________________________________________________________

DBaaS (Database as a Service - Banco de Dados como Serviço): Oferece bancos de dados prontos para usar e gerenciar na nuvem. O provedor cuida da infraestrutura, backups, atualizações, etc.

Exemplos: Azure SQL Database, Amazon RDS.

Ponto Forte: Facilita a gestão de bancos de dados, escalabilidade fácil.

Ponto Fraco: Menor controle sobre as configurações mais profundas do banco.
______________________________________________________________________________________________________________________________________________________________

🔵 Fundamentos da Microsoft Azure
Minha jornada com o Azure começou entendendo que ele é a plataforma de nuvem da Microsoft, um universo de serviços que nos ajuda a construir, implantar e gerenciar desde simples sites até sistemas complexos. Basicamente, o Azure me permite usar a gigantesca infraestrutura global da Microsoft para minhas próprias necessidades, pagando só pelo que consumo.
______________________________________________________________________________________________________________________________________________________________

🔑 Criando uma Conta Microsoft e Assinatura Azure para Estudos
Para colocar a mão na massa, o lab me guiou no processo de criar uma conta Microsoft e, em seguida, ativar uma assinatura gratuita do Azure (ou Azure for Students). Isso foi crucial, pois me deu acesso ao Portal do Azure, que é a interface principal onde a gente visualiza, cria e gerencia todos os recursos na nuvem. É por lá que vou poder, por exemplo, criar minhas primeiras Máquinas Virtuais, configurar armazenamento, e explorar os diversos serviços que o Azure oferece para aprender na prática.
______________________________________________________________________________________________________________________________________________________________

🎯 Conclusão
Este laboratório foi um mergulho essencial no mundo da computação em nuvem, com um foco especial no Microsoft Azure. Entender os conceitos de infraestrutura, os diferentes modelos de serviço e, finalmente, ter a chance de configurar minha própria conta no Azure, me deu uma base sólida para continuar explorando e aplicando esses conhecimentos em futuros desafios. Estou animado(a) para aprofundar ainda mais e construir soluções incríveis na nuvem!


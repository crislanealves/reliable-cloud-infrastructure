**Módulo 1: Visão Geral do Módulo**

Neste módulo, exploraremos como definir serviços em um novo projeto de desenvolvimento, começando com as fases de planejamento e design. Isso requer a coleta de informações, inicialmente concentrando-se nos requisitos de negócios. Depois de definir esses requisitos, é crucial avaliar se eles agregam valor ao negócio. No decorrer deste módulo, abordaremos técnicas para coletar requisitos e métodos para avaliar o impacto dessas soluções.

Durante este módulo, você aprenderá a descrever os usuários de um sistema com base nos papéis e personas associados. Esses usuários desempenham um papel fundamental na definição e refinamento dos requisitos qualitativos, que serão coletados na forma de histórias de usuários. Isso contextualiza o design da arquitetura e as decisões técnicas que você tomará como arquiteto de nuvem.

Exemplos de requisitos de negócios incluem, dentre outras coisas:

    - Acelerar o desenvolvimento de software;
    - Reduzir despesas; e,
    - Diminuir o tempo de recuperação de incidentes. 

Além disso, os requisitos técnicos de um sistema abrangem as demandas de recursos funcionais e não funcionais. Para identificar os requisitos mais críticos e medir seu impacto, você aprenderá como avaliar o sucesso usando indicadores principais de desempenho, ou KPIs. Também discutiremos a importância de usar critérios inteligentes ao definir KPIs. Por fim, abordaremos a definição adequada de objetivos de nível de serviço, ou SLOs, indicadores de nível de serviço, ou SLIs, e contratos de nível de serviço, ou SLAs.

**Módulo 2: Requisitos, Análise e Design**

Começaremos abordando requisitos, análise e design. Estas são perguntas úteis que podem ser feitas ao arquiteto de nuvem para ajudar a definir os requisitos: quem, o quê, por quê, quando e como. A pergunta "quem" visa identificar o usuário do sistema, incluindo desenvolvedores e partes interessadas. O objetivo é criar uma visão abrangente dos impactados direta e indiretamente pelo sistema.

A pergunta "o que" procura estabelecer as principais áreas de funcionalidade necessárias, sem ambiguidades. Entender "por que" o sistema é necessário é crucial para evitar requisitos extras e ajuda na definição de KPIs, SLOs e SLAs.

A pergunta "quando" ajuda a determinar um cronograma realista e pode limitar o escopo do projeto, enquanto "como" contribui para definir requisitos não funcionais, como capacidade de usuário simultâneo, tamanho das solicitações de serviço e requisitos de latência.

É essencial definir esses requisitos com clareza, pois influenciam a solução que você, como arquiteto de nuvem, desenvolverá.

Na atividade de design anterior, você definiu papéis de usuários para o seu aplicativo. Os papéis representam o objetivo de um usuário em um contexto específico. É importante observar que um papel não se limita a uma pessoa, mas pode ser um agente no sistema, como o cliente de um microsserviço acessando outro microsserviço.

O papel deve descrever o objetivo do usuário no sistema. Por exemplo, o papel de um comprador em um aplicativo de e-commerce define claramente o que o usuário deseja realizar.

Existem várias formas de definir papéis para atender aos requisitos. Um processo eficaz envolve pensar em um conjunto inicial de papéis, escrever o máximo de papéis possível, cada um representando um usuário único. Em seguida, organize esses papéis, identificando papéis com objetivos comuns ou relacionados e agrupando-os. Por fim, consolide os papéis para remover duplicações. Você também pode incluir outras informações, como o nível de experiência do usuário ou a frequência de uso do software proposto.

A identificação de papéis de usuários é uma técnica útil no processo de definição de requisitos. Outra técnica importante, principalmente para os papéis mais relevantes, é a criação de personas para representar os papéis de usuário. Uma persona é uma representação fictícia de um papel de usuário e ajuda os arquitetos e desenvolvedores a considerar características de usuários por meio da personalização.

Uma pessoa pode ter várias personas. Por exemplo, no contexto de requisitos para um aplicativo bancário, você pode pensar nos usuários do sistema e definir vários requisitos dessa forma. O uso de personas oferece uma visão mais completa dos requisitos e ajuda a entender como as características dos usuários afetam o design e a latência do serviço.

No exemplo, quando um arquiteto ou desenvolvedor tem uma dúvida, é mais fácil encontrar a resposta pensando no que a persona gostaria de ouvir.

As histórias de usuários descrevem o que um usuário deseja que o sistema faça. Elas são escritas de forma estruturada, geralmente no formato "como" um tipo de usuário, "eu quero" fazer algo "para" obter um benefício. Outra abordagem comum é: "dado" um contexto, "quando" eu faço algo, "então" isso deve acontecer.

Ao escrever histórias, é importante usar títulos que indiquem a finalidade inicial de cada uma. Em seguida, adicione uma descrição concisa da história em uma única frase, usando uma das formas mencionadas. Essa estrutura ajuda a explicar o papel do usuário, o que ele deseja fazer e por quê.

Por exemplo, imagine um sistema bancário e uma história de usuário para verificar o saldo disponível em uma conta. O título da história pode ser "Consulta de saldo", e a descrição da história seria algo como: "Como titular de uma conta corrente, eu quero consultar meu saldo a qualquer hora do dia para evitar ficar no vermelho."

As histórias de usuários são uma maneira simples e eficaz de comunicar requisitos e expectativas entre a equipe de desenvolvimento e as partes interessadas. Elas mantêm o foco no usuário final e são uma ferramenta valiosa para o desenvolvimento ágil e a gestão de projetos.

Além disso, ao avaliar histórias de usuários, é útil aplicar critérios INVEST, que são critérios de qualidade para histórias de usuário:

- **Independente**: A história deve ser independente de outras histórias, o que significa que ela pode ser desenvolvida e entregue separadamente.

- **Negociável**: A história deve ser negociável entre a equipe de desenvolvimento e as partes interessadas, para que possa ser ajustada conforme necessário.

- **Valiosa**: A história deve fornecer valor real ao usuário final ou ao negócio.

- **Estimável**: A equipe deve ser capaz de estimar o tempo e os recursos necessários para concluir a história.

- **Pequena**: A história deve ser pequena o suficiente para ser desenvolvida em um único ciclo de desenvolvimento.

- **Testável**: Deve ser possível criar testes que verifiquem se a história foi implementada com sucesso.

Esses critérios ajudam a garantir que as histórias de usuário sejam claras, gerenciáveis e orientadas para resultados.

**Atividades 2A e 2B**

As atividades 2A e 2B estão relacionadas à criação de personas e à escrita de histórias de usuários. A criação de personas envolve a definição detalhada dos diferentes tipos de usuários que interagem com o sistema. Cada persona representa um conjunto específico de características e necessidades.

A atividade 2A se concentra em criar essas personas, definindo seus objetivos, comportamentos e características distintivas. Isso ajuda a equipe a compreender melhor para quem estão desenvolvendo o sistema e quais são as expectativas desses usuários.

A atividade 2B, por outro lado, envolve a escrita de histórias de usuários com base nas personas criadas. Cada história descreve uma tarefa específica que um usuário deseja realizar no sistema. Essas histórias são essenciais para documentar os requisitos do sistema de forma clara e compreensível, garantindo que a equipe de desenvolvimento esteja alinhada com as necessidades dos usuários.

**Módulo 3: SLOs, SLIs e SLAs**

Neste módulo, você mergulhará na medição do cumprimento dos requisitos técnicos e comerciais. Você aprenderá a usar indicadores principais de desempenho (KPIs) para medir o sucesso de projetos de desenvolvimento. Entenderá a diferença entre KPIs comerciais e técnicos e como eles são aplicados no contexto do design da arquitetura de nuvem.

Uma parte crítica deste módulo é a definição de indicadores de nível de serviço (SLIs) e objetivos de nível de serviço (SLOs). Os SLIs representam métricas específicas que medem o desempenho do sistema, como tempo de resposta ou disponibilidade. Os SLOs, por outro lado, estabelecem metas para esses SLIs, definindo o nível de serviço que você deseja alcançar.

Além disso, você aprenderá sobre a importância dos contratos de nível de serviço (SLAs) na comunicação e na garantia de que os requisitos sejam atendidos. Os SLAs são acordos formais que estipulam os níveis de serviço acordados entre os provedores de serviço e os clientes.

Outra consideração crucial ao escolher indicadores e métricas é o uso de percentagens para métricas que refletem valores extremos. Isso ajuda a evitar distorções nos dados e a manter uma visão precisa do desempenho do sistema.

Por fim, você discutirá a importância de escolher a periodicidade adequada para a medição, garantindo que os dados coletados sejam relevantes e úteis para a tomada de decisões.


**Visão Geral**

Olá, sou Priyanka Vergadia, mediadora de desenvolvedores do Google Cloud. Neste módulo, vamos conhecer a arquitetura de aplicativos e o projeto de microsserviços. Em especial, você aprenderá sobre arquiteturas de microsserviços e como decompor aplicativos monolíticos em microsserviços. Os benefícios da arquitetura de microsserviços para aplicativos nativos da nuvem são abordados e comparados aos monolíticos. Vamos analisar como decompor aplicativos em microsserviços com limites definidos para dar suporte a unidades implantáveis independentes. Você vai aprender como fazer projetos para alguns dos maiores desafios técnicos da arquitetura de microsserviços, como gerenciamento de estado, confiabilidade e escalonabilidade. Ao escolher a arquitetura de microsserviço nativa da nuvem, as práticas recomendadas para desenvolver e implantar são introduzidas com base nas reconhecidas práticas de 12 fatores. No fim do módulo, vamos ver um componente principal da arquitetura de microsserviços, que é o design de interfaces de serviços consistentes e acopladas com flexibilidade.

**Microsserviços**

Vamos começar analisando os detalhes de um microsserviço. Microsserviços dividem um programa grande em vários serviços independentes menores, como mostrado à direita, ao contrário de um aplicativo monolítico, que implementa todos os recursos em uma única base de código com um banco de dados para todos os dados, como mostrado à esquerda. Microsserviços são a tendência atual do setor. Mas é importante ter um bom motivo para escolher essa arquitetura. O principal motivo é permitir que equipes trabalhem independentemente e entreguem para a produção no ritmo de cada uma. Isso suporta escalonar a organização, pois ter mais equipes aumenta a velocidade. Também há o benefício de poder escalonar microsserviços independentemente, com base nos requisitos deles.

Quanto à arquitetura, um aplicativo projetado como um monolítico ou com base em microsserviços é composto de componentes modulares com limites claramente definidos. Com o monolítico, todos os componentes são empacotados no momento da implantação e implantados juntos. Com microsserviços, componentes individuais são implantáveis. O Google Cloud fornece vários serviços de computação que facilitam a implantação de microsserviços, como o App Engine, o Cloud Run, o GKE e o Cloud Functions. Cada um deles oferece níveis de granularidade e controle diferentes. Vamos vê-los posteriormente neste curso.

Para serviços serem independentes, cada um deles precisa ter o próprio repositório de dados. Isso permite a melhor solução de armazenamento de dados para o serviço que será selecionado, e também mantém os serviços independentes. Não queremos introduzir acoplamento entre serviços por um repositório de dados. Uma arquitetura de microsserviços projetada corretamente ajuda a alcançar os objetivos a seguir:

- Definir contratos entre os diversos microsserviços.
- Permitir ciclos de implantação independentes, incluindo reversões.
- Facilitar testes A/B de lançamentos simultâneos em subsistemas.
- Minimizar automação de teste e sobrecarga de controle de qualidade.
- Melhorar a clareza da geração de registros e do monitoramento.
- Fornecer contabilidade dos custos detalhada.
- Aumentar a escalonabilidade geral do aplicativo e a confiabilidade com unidades de escalonamento menores.

Mas as vantagens precisam ser equilibradas com os desafios que esse estilo de arquitetura introduz. Alguns desses desafios incluem:

- Pode ser difícil definir limites claros entre serviços para dar suporte à implantação e ao desenvolvimento independentes.
- Maior complexidade da infraestrutura, com serviços distribuídos tendo mais pontos de falha.
- A latência maior introduzida pelos serviços de rede e a necessidade de criar resiliência para lidar com possíveis atrasos e falhas.
- Devido à rede envolvida, é necessário fornecer segurança para comunicação serviço a serviço, o que torna a infraestrutura mais complexa.
- Requisitos complexos para gerenciar e fazer a versão de interfaces com serviços implantáveis independentes.
- Maior necessidade de manter compatibilidade com versões anteriores.

Decompor aplicativos em microsserviços é um dos maiores desafios técnicos do design de aplicativos. Aqui, técnicas como design voltado a domínio são muito úteis para identificar agrupamentos funcionais lógicos.

A primeira etapa é decompor o aplicativo por recursos ou agrupamento funcional, a fim de minimizar dependências. Considere, por exemplo, um aplicativo de loja on-line. Agrupamentos funcionais lógicos podem ser: gerenciamento de produtos, análises, contas e pedidos. Esses agrupamentos compõem miniaplicativos, os quais expõem uma API. Cada um desses miniaplicativos será implementado, potencialmente, por vários microsserviços internamente. Internamente, esses microsserviços são organizados por camada de arquitetura, e cada um precisa ser escalonável e implantável independentemente.

As análises também vão identificar serviços compartilhados, como autenticação, que depois são isolados e implantados separadamente dos vários aplicativos. Ao projetar microsserviços, serviços que não retêm estados, mas os obtêm do ambiente ou dos serviços sem estado, são mais fáceis de gerenciar. Ou seja, são mais fáceis de escalonar, de administrar e de migrar para novas versões, porque não têm estado. Porém, geralmente não é possível evitar o uso de serviços com estado em algum ponto em um aplicativo com base em microsserviços. Portanto, é importante compreender as consequências de ter serviços com estado na arquitetura do sistema. Isso inclui introduzir desafios significativos na capacidade de escalonar e fazer upgrade dos serviços. É importante saber como o estado será gerenciado nos estágios iniciais do design do aplicativo de microsserviço. 

Na memória, o estado compartilhado tem implicações que afetam e negam muitos dos benefícios de uma arquitetura de microsserviços. O potencial de escalonamento automático de microsserviços individuais é atrasado porque solicitações posteriores do cliente precisam ser enviadas ao mesmo servidor em que a solicitação inicial foi feita. Adicionalmente, isso exige configurar os balanceadores de carga para usar sessões fixas, o que é chamado de afinidade da sessão no Google Cloud.

Uma prática recomendada para projetar serviços com estado é usar serviços de armazenamento de back-end compartilhados por serviços sem estado do front-end. Por exemplo, para estado permanente, os serviços de dados gerenciados pelo Google Cloud, como o Firestore ou Cloud SQL, podem ser úteis. Depois, para melhorar a velocidade do acesso aos dados, eles podem ser armazenados em cache. O Memorystore, que é um serviço com base em Redis altamente disponível, é ideal para isso.

Este diagrama mostra uma solução geral para a separação das etapas de processamento de front-end e back-end. Um balanceador de carga distribui a carga entre os serviços de back-end e front-end. Isso permite que o back-end escalone, se necessário, para acompanhar a demanda do front-end. Adicionalmente, os serviços ou os servidores com estado também são isolados. Os serviços com estado podem usar os serviços de armazenamento permanente e armazenamento em cache, como explicado anteriormente. Esse layout permite que uma grande parte do aplicativo use a escalonabilidade e a tolerância a falhas padrão dos serviços do Google Cloud como serviços sem estado. Isolando os serviços e servidores com estado, os desafios de escalonar e fazer upgrades ficam limitados a um subconjunto do conjunto geral dos serviços.

**Práticas Recomendadas de Microsserviços**

Vamos falar sobre práticas recomendadas para microsserviços. O "App de 12 fatores" é um conjunto de práticas recomendadas para criar aplicativos para a Web ou software como serviço. O projeto de 12 fatores ajuda a desacoplar componentes do aplicativo para que cada componente possa ser implantado na nuvem usando implantação contínua e escalonado verticalmente ou ter a escala vertical reduzida. Os princípios de projeto também maximizam a portabilidade para ambientes diferentes. Como os fatores são independentes de linguagens de programação ou de pilha de software, o projeto de 12 fatores pode ser aplicado em diversos tipos de aplicativos. Vamos ver essas práticas recomendadas.

**1. Base de Código:**
- A base de código precisa ser rastreada em um controle de versão, como o Git.
- Os Cloud Source Repositories fornecem repositórios privados com todos os recursos.

**2. Dependências:**
- As dependências precisam ser declaradas explicitamente e armazenadas em controle de versões.
- O rastreamento de dependências é feito com ferramentas específicas da linguagem, como Maven para Java e Pip para Python.
- Empacotar dependências em contêineres pode isolar o aplicativo.
- O Container Registry pode ser usado para armazenar as imagens e fornecer controle de acesso detalhado.

**3. Configuração:**
- Cada aplicativo tem uma configuração para cada ambiente, como de teste, de produção e de desenvolvimento.
- Essa configuração precisa ser externa ao código e manter variáveis de ambiente para flexibilidade da implantação.

**4. Serviços de Suporte:**
- Cada serviço de suporte, como banco de dados, cache ou mensagens, precisa ser acessado por URLs e definido pela configuração.
- Os serviços de suporte atuam como uma abstração para recursos subjacentes.
- O objetivo é poder trocar um serviço de suporte por uma implementação diferente com facilidade.

**5. Build, Lançamento e Execução:**
- O processo de implantação do software é dividido em três etapas: build, lançamento e execução.
- Cada etapa resulta em um artefato que tem uma identificação exclusiva.
- Isso permite fazer reversões facilmente e ter uma trilha de auditoria do histórico de cada implantação de produção.

**6. Processos:**
- Aplicativos são executados como um ou mais processos sem estado.
- Se um estado for exigido, a técnica discutida anteriormente neste módulo para gerenciamento de estados é a mais adequada.
- Cada serviço precisa ter os próprios armazenamentos de dados e cache, por exemplo, memória armazenada no cache e dados comuns compartilhados entre serviços usados.

**7. Vinculação de Portas:**
- Serviços são expostos usando um número de porta.
- O aplicativo empacota o servidor da Web como parte do aplicativo, não exigindo um servidor separado, como o Apache.
- No Google Cloud, esses apps podem ser implantados em serviços de plataforma, como o Compute Engine, o GKE, o App Engine ou o Cloud Run.

**8. Simultaneidade:**
- O aplicativo precisa ter a capacidade de escalonar horizontalmente, iniciando novos processos, e de retornar ao tamanho original para cumprir a demanda ou as cargas.

**9. Descartabilidade:**
- Aplicativos precisam ser escritos para ser mais confiáveis do que a infraestrutura em que são executados.
- Eles precisam ser capazes de lidar com falhas temporárias na infraestrutura subjacente e de desligar e reiniciar rapidamente.
- Aplicativos também têm que escalonar verticalmente e reduzir a escala vertical rapidamente, obtendo e lançando recursos conforme necessário.

**10. Paridade entre Desenvolvimento/Produção:**
- O objetivo é que os mesmos ambientes usados no desenvolvimento e no teste ou preparação sejam usados na produção.
- A infraestrutura como código e os contêineres do Docker facilitam isso.
- O Google Cloud oferece várias ferramentas que podem ser usadas para criar fluxos de trabalho que mantêm os ambientes consistentes.

**11. Registros:**
- Registros permitem ver a integridade dos aplicativos.
- É importante dissociar a coleta, o processamento e a análise de registros da lógica principal dos aplicativos.
- Os registros precisam ser gerados como uma saída padrão e agregados em uma só fonte.

**12. Processos do Administrador:**
- Geralmente, os processos do administrador são realizados uma vez e precisam estar desacoplados do aplicativo.
- Eles precisam ser automatizados e reproduzíveis, em vez de processos manuais.
- No Google Cloud, há várias opções para fazer isso, incluindo cron jobs no GKE, tarefas de nuvem no App Engine e o Cloud Scheduler.

## Revisão da atividade: Como criar microsserviços para seu aplicativo

Nesta atividade de projeto, você vai realizar a Atividade 4 da apostila de projeto. Você será responsável por projetar os microsserviços para o seu aplicativo. O principal objetivo é criar um diagrama que represente os microsserviços necessários para o aplicativo do estudo de caso. Certifique-se de considerar os limites dos microsserviços, o gerenciamento de estado e os serviços compartilhados. Utilize os princípios que foram abordados até o momento neste módulo como diretrizes. Para auxiliar no processo, você pode consultar um exemplo de diagrama de microsserviços de um serviço de banco online, tanto para o site quanto para o aplicativo móvel, e criar um diagrama semelhante para o seu estudo de caso.


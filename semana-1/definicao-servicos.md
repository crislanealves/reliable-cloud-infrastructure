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

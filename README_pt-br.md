# ArcOS: O último paradigma em sistemas de código aberto ARChitecture

## Quem Somos

Somos uma organização voltada para a comunidade, dedicada a promover a inovação, empoderar indivíduos e construir um futuro sustentável. Acreditamos no poder da colaboração e no potencial da tecnologia para transformar vidas. Nossa missão é criar um mundo onde:

* **Indivíduos** tenham as ferramentas e o conhecimento para realizar todo o seu potencial.
* **Comunidades** prosperem por meio do conhecimento compartilhado e da ação coletiva.
* **Tecnologia** é usada para resolver problemas do mundo real e criar impacto positivo.

Estamos comprometidos com:

* **Abertura:** Compartilhar conhecimento e recursos livremente.
* **Inclusão:** Acolher pessoas de todas as origens e perspectivas.
* **Sustentabilidade:** Construir um futuro ambiental e socialmente responsável.

## Nossa Missão

Acreditamos em:

* **Centralidade no Usuário:** Criar tecnologia acessível e amigável para todos.

* **Desenvolvimento Orientado pela Comunidade:** Aproveitando o poder da colaboração de código aberto.
* **Impacto no Mundo Real:** Atendendo às necessidades críticas de infraestrutura do mundo real.
* **Descentralização:** Promovendo a distribuição equitativa de recursos e propriedade.
* **Crescimento Sustentável:** Promovendo o desenvolvimento harmonioso de indivíduos e instituições.
* **Inovação:** Impulsionando avanços de ponta para enfrentar desafios futuros.

## O Cenário

O cenário atual enfrenta desafios significativos:

* **Fragmentação:** A comunidade de código aberto carece de unidade e foco para competir efetivamente no mercado.
* **Acesso Limitado:** A propriedade de hardware é restringida por tecnologias proprietárias e processos de fabricação complexos.
* **Propriedade de Dados:** O sistema atual de propriedade de dados é pouco claro e frequentemente injusto.

## Visão

**Visualizamos um futuro onde:**

* A interação humano-computador seja fluida e intuitiva, permitindo uma conexão humana verdadeira e significativa em todo o mundo.
* O cenário de código aberto é revolucionado pelo estabelecimento de um ecossistema colaborativo onde tecnologias inovadoras são acessíveis e moldadas por uma comunidade global.
* Queremos criar um modelo sustentável para o desenvolvimento de código aberto, capacitando os usuários com controle sem precedentes sobre sua experiência computacional.
* Nosso objetivo é ser o meta-sistema operacional de referência no mundo do código aberto, permitindo que a comunidade crie seus próprios sistemas personalizados.

O "Arc OS" não é apenas mais uma distribuição; Pretende-se que seja um ecossistema unificado que promova a colaboração, fornecendo uma base e práticas de desenvolvimento comuns. Essa abordagem reduz a duplicação de esforços e inconsistências entre projetos, garantindo a integração perfeita de recursos inovadores, preservando a privacidade do usuário e a sustentabilidade a longo prazo.

## Problemas Principais Abordados

- **Fragmentação:** O projeto aborda a fragmentação dos esforços de código aberto criando um sistema coeso e modular.
- **Acessibilidade:** O objetivo é melhorar a acessibilidade para usuários não técnicos com interfaces amigáveis, instalação simplificada e documentação abrangente.
- **Dependência de Fornecedor:** O "Arc OS" busca reduzir a dependência de código proprietário por meio de alternativas de código aberto e desenvolvimento orientado pela comunidade.

## Objetivos

* Construir uma comunidade global próspera de usuários e colaboradores.
* Fornecer um sistema modular seguro, estável e personalizável, onde os usuários possam escolher cada componente e recurso para atender a quaisquer requisitos específicos.
* Oferecer uma rede descentralizada para compartilhamento de recursos e inovação.
* Desenvolver tecnologias assistivas para tornar o projeto acessível a usuários sem conhecimento técnico e pessoas com deficiência.

## Principais Entregas

1. **Desenvolvimento do "Arc OS":**
* **SO Base Modular:** Um sistema operacional personalizável baseado na abordagem Unix, permitindo que os usuários selecionem componentes do kernel para aplicativos de usuário.
* **Recursos Principais (Alfa):** Inicialização segura, proteção do sistema, drivers básicos para x86_64, ARM e RISC-V, gerenciamento de recursos, rede, gerenciador de pacotes modular e uma interface de usuário avançada para desenvolvimento e testes.
* **Acessibilidade:** O "Arc OS" será projetado com acessibilidade em mente, garantindo que possa ser usado por pessoas com deficiência.

* **Documentação:** Documentação completa para desenvolvedores, manuais do usuário e guias de instalação nos principais idiomas dos membros da comunidade.
* **Opções de Base Técnica:**

* **Firmware:** Coreboot/Libreboot (para segurança e personalização).
* **Bootloader:** GRUB, Refind ou Limine (para flexibilidade e facilidade de uso).
* **InitRamFS:** dracut ou booster (para eficiência).
* **Kernel:** Linux (para amplo suporte a drivers).
* **Daemon:** OpenRC/runit/s6 (alternativas leves ao systemd).
* **Sistema de arquivos:** ext4, xfs, btrfs ou ZFS.
* **Shell:** bash, zsh, fish ou dash.
* **Utilitários:** toybox, busybox, util-linux, GNU-CoreUtils
* **libc:** glibc ou musl.
* **Compilador C:** GCC ou Clang.
* **Gerenciador de Pacotes:** Guix ou Nix.

2. **Web Archive:**
* Um repositório organizado de projetos de código aberto, artigos de pesquisa, código-fonte e conjuntos de dados, categorizados para fácil acesso.
* Integração com controle de versão usando Git.
* Sistema robusto de metadados com tags, autores, datas e categorias para busca eficiente.

3. **WebApp:**
* **Recursos do MVP:** Registro de usuários, informações do projeto, fórum/chat da comunidade, rastreamento de problemas e compartilhamento básico de arquivos.
* **Ferramentas da Comunidade:** Integração com uma plataforma de comunicação dedicada (Discourse/Matrix), base de conhecimento (wiki) e plataformas de desenvolvimento colaborativo (GitHub/GitLab).

4. **Infraestrutura da Comunidade:**
* Criação de uma rede de desenvolvimento e testes por meio do uso do "Arc OS" na comunidade, utilizando uma arquitetura ponto a ponto descentralizada.
* Sistema de testes automatizado para validar commits de código.
* Comunicação segura entre desenvolvedores e outros membros.
* Acesso remoto a sistemas virtuais e físicos.

## Público-alvo: "Feito para Todos"

O **Arc OS** visa ser um sistema operacional versátil que atende a uma base de usuários diversificada, desde usuários casuais até profissionais experientes. Este resumo descreve os principais públicos-alvo e suas necessidades específicas:

* **Usuários não técnicos:** Buscam uma experiência amigável e confiável com configuração simplificada, interfaces intuitivas e uma seleção criteriosa de aplicativos essenciais.
* **Usuários profissionais:** Exigem um sistema de alto desempenho com recursos avançados, como ambientes de desenvolvimento robustos, segurança avançada e ferramentas de gerenciamento de recursos.
* **Empresas:** Exigem segurança de nível empresarial, escalabilidade, opções de personalização e custo-benefício para suas operações.
* **Desenvolvedores e administradores de sistemas:** Precisam de uma plataforma flexível para desenvolvimento, com acesso a funcionalidades básicas do sistema, ferramentas avançadas e um ambiente colaborativo.
* **Usuários avançados e entusiastas:** Desejam amplas opções de personalização, acesso a recursos de ponta e uma plataforma para exploração e experimentação.

* **Instituições de Ensino:** Exigem uma plataforma segura, personalizável e de código aberto para ensino, pesquisa e criação de ambientes de aprendizagem especializados.
* **Usuários com Foco em Acessibilidade:** Precisam de um sistema compatível com tecnologias assistivas e que possa ser personalizado para atender às necessidades individuais.

**O Arc OS** atenderá às necessidades de cada público-alvo por meio de:

* **Interfaces amigáveis ​​e navegação intuitiva.**
* **Processos simplificados de instalação e configuração.**
* **Documentação e tutoriais abrangentes.**
* **Um design modular para personalização.**
* **Recursos avançados de segurança e ambientes de desenvolvimento robustos.**
* **Recursos de nível empresarial para empresas.**
* **Recursos de acessibilidade e suporte para tecnologias assistivas.**
* **Um forte foco na construção de comunidades e colaboração.**

## Código de Conduta

O projeto Arc OS se dedica a proporcionar um ambiente acolhedor e inclusivo para todos, independentemente de sua origem, identidade ou nível de experiência. Este Código de Conduta se aplica a todos os espaços do projeto, tanto online quanto offline, e visa promover uma comunidade baseada em respeito, colaboração e empatia.

**Esperamos que os membros da comunidade:**

* Sejam respeitosos em todas as formas de comunicação e interação, tanto online quanto offline.
* Sejam acolhedores com os recém-chegados e ofereçam apoio a todos os membros.
* Sejam empáticos e compreensivos com as diversas origens, perspectivas e experiências vividas, e sejam atenciosos ao se comunicar com outras pessoas que possam ter pontos de vista diferentes.
* Forneçam feedback construtivo e estejam abertos a recebê-lo.
* Concentrem-se na colaboração, não na competição, e celebrem o sucesso coletivo.

**Os seguintes comportamentos não são aceitáveis ​​na comunidade Arc OS:**

* Assédio de qualquer tipo, incluindo ataques pessoais, piadas ofensivas, perseguição e intimidação.

* Discriminação com base em raça, etnia, gênero, identidade de gênero, orientação sexual, idade, religião, deficiência ou qualquer outra característica protegida.
* Discurso de ódio, insultos ou qualquer linguagem que promova intolerância ou discriminação.
* Spam, trollagem ou *qualquer comportamento que interrompa o fluxo colaborativo da comunidade, incluindo, entre outros, discussões fora do tópico nos canais do projeto e conversas que constantemente descarrilem*.
* Divulgação pública ou privada de informações privadas de alguém sem o seu consentimento.
* Retaliações contra indivíduos que denunciarem uma violação do Código de Conduta não serão toleradas e resultarão em ação disciplinar.

Se você vivenciar ou testemunhar uma violação deste Código de Conduta, denuncie imediatamente para [endereço de e-mail designado]. Forneça o máximo de detalhes possível, incluindo capturas de tela relevantes, datas, horários, locais e detalhes do incidente. Todos os relatos serão mantidos em sigilo e, se solicitado, a identidade do denunciante permanecerá anônima. As informações do denunciante serão divulgadas somente nos casos em que ele permitir e quando estritamente necessário para concluir a investigação.

A comunidade do Arc OS aplicará ativamente este Código de Conduta. Quaisquer violações serão analisadas pela equipe de fiscalização do Código de Conduta designada, composta pelos mantenedores do projeto ou por uma diretoria eleita pela comunidade. A equipe investigará as violações relatadas, entrará em contato com todas as partes envolvidas e determinará as ações apropriadas.

**Essas ações podem incluir:**

* Uma advertência verbal ou por escrito
* Suspensão temporária dos espaços do projeto.
* Perda de privilégios e acesso a recursos
* Banimento permanente da comunidade.

Este Código de Conduta é um documento dinâmico e pode ser revisado conforme necessário. Agradecemos o feedback da comunidade e sugestões de melhoria. A equipe de fiscalização do Código de Conduta revisará e atualizará este documento periodicamente, conforme necessário, levando em consideração todas as contribuições da comunidade. Quaisquer atualizações serão anunciadas publicamente na comunidade.

Para quaisquer dúvidas ou preocupações sobre este Código de Conduta, entre em contato conosco pelo e-mail [endereço de e-mail designado].

## Plano de Execução

**Fase 1: Estabelecendo as Bases (Prioridades Imediatas)**

1. **Lançar um MVP de Webapp Básico:** Concentre-se nos principais recursos descritos na entrega:
* Registro e autenticação do usuário.
* Informações básicas do projeto (descrição, visão, objetivos e roteiro).
* Um fórum da comunidade (Discourse ou similar) ou integração básica de chat (Matrix/IRC).
* Um sistema básico de rastreamento de problemas (por exemplo, problemas do GitHub em um repositório dedicado).

2. **Definir e Documentar os Princípios Fundamentais:**
* **Documentar um Código de Conduta:** Garantir um ambiente acolhedor e inclusivo.
* **Definir os Princípios Fundamentais do Projeto:** Documentar a visão, os objetivos, a filosofia de desenvolvimento, as considerações éticas e as escolhas técnicas.

* **Ferramentas:** Use um arquivo markdown, um gerador de site estático ou similar para documentar tudo e colocar isso diretamente no webapp básico.

3. **Recrutar a Equipe Principal Inicial:**
* **Prioridade:** Encontrar um pequeno grupo de colaboradores dedicados para ajudar a iniciar o projeto.
* **Ação:**
* **Contatar em canais relevantes:** Anunciar em comunidades de código aberto (fórum NixOS, Reddit, Mastodon, etc.)
* **Buscar habilidades específicas:** Concentre-se em profissionais com experiência em NixOS, administração de sistemas, desenvolvimento web, documentação e testes.
* **Construir um roteiro compartilhado para o projeto:** Envolver essa equipe inicial no planejamento e na estratégia.
* **Por que isso é crucial:** Uma equipe principal ajudará a distribuir o trabalho, garantir a qualidade e criar um ambiente de trabalho dinâmico.
4. **Desenvolver um Ambiente Básico de Desenvolvimento "Arc OS":**

* **Prioridade:** Preparar-se para o desenvolvimento do sistema operacional
* **Ação:**
* **Escolher uma Distribuição Base:** Selecione NixOS. Este deve ser o seu sistema de desenvolvimento alvo.
* **Configurar um ambiente de desenvolvimento básico e reproduzível:** Um método para configurar todas as dependências necessárias para o desenvolvimento (usando Docker, Vagrant ou similar)
* **Documentação Inicial:** Documentar para a equipe como acessar e testar a versão inicial.
* **Por que isso é crucial:** Permite que a equipe principal inicie o desenvolvimento e os testes.
5. **Estabelecer um Arquivo Web Básico:**
* **Prioridade:** Começar a organizar os recursos necessários para P&D
* **Ação:**
* **Configuração inicial da tecnologia para arquivamento de recursos relevantes:** Código-fonte, conjuntos de dados, documentação, etc.
* **Começar a documentar os recursos:** Configurar um sistema básico de metadados (tags, autores, data) para pesquisar os dados
* **Por que isso é crucial:** Este é o ponto de partida do programa de P&D de longo prazo

**Fase 2: Criando Momentum (Metas de Curto Prazo)**

1. **Expandir os Recursos do Webapp:**
* **Prioridade:** Aprimorar o hub de comunicação central.
* **Ação:** Adicionar mais recursos avançados:
* Melhorias no sistema de rastreamento de problemas.
* Perfis de usuário e rastreamento de contribuições aprimorados.
* Recursos básicos de compartilhamento de arquivos.
* Integração com base de conhecimento/wiki para documentação.
* Considere a criação de um painel simples para métricas-chave e monitoramento de contribuições.
2. **Iniciar o Desenvolvimento Inicial do "Arc OS":**
* **Prioridade:** Começar a trabalhar nos componentes principais do SO.
* **Ação:**
* **Foco no MVP Inicial:** Inicialização segura, reforço do sistema, drivers mínimos, rede básica e gerenciador de pacotes
* **Implementar procedimentos básicos de teste:** Usar testes automáticos e integração contínua
3. **Estabelecer a Infraestrutura Principal do Projeto:**
* **Prioridade:** Definir a base para o desenvolvimento contínuo.
* **Ação:**
* **Configurar testes automatizados:** Implementar uma estrutura básica de testes.
* **Configurar um sistema de build:** Implementar builds reproduzíveis.
* **Integrar uma plataforma de código colaborativo:** GitHub ou GitLab para facilitar as contribuições.
4. **Iniciar a divulgação e a construção da comunidade:**
* **Prioridade:** Começar a atrair mais colaboradores.
* **Ação:**
* Começar a anunciar nas comunidades relevantes mencionadas anteriormente.
* Criar documentação mais detalhada para mostrar o projeto e torná-lo mais atraente para iniciantes.
* Criar alguns vídeos ou posts de blog explicando o projeto.
* Configurar métricas básicas para acompanhar o progresso de todos os esforços.
5. **Explorar as opções iniciais de financiamento:**
* **Prioridade:** Começar a tornar o projeto sustentável.
* **Ação:**
* Começar a documentar todas as despesas.
* Começar a desenvolver material para a campanha de financiamento coletivo.
* Explorar outras opções, como subsídios e doações.
   
## Modelo de Financiamento

* **Financiamento Multinível:**
* Campanhas de crowdfunding.
* Patrocínios corporativos de empresas alinhadas.
* Subsídios de fundações relevantes.
* Programa de membros com benefícios escalonados.
* **Transparência Financeira:** Um sistema transparente para acompanhar receitas e despesas.
* **Alocação Orçamentária:** Aproximadamente 58% para salários de desenvolvedores, 32% para infraestrutura e 10% para marketing e eventos/divulgação comunitária.

## Por que se juntar a nós?

* **Assuma a Responsabilidade:** Nós capacitamos você a contribuir e colher os frutos de seus esforços.
* **Descubra o Potencial Oculto:** Incentivamos a exploração e a descoberta de soluções inovadoras.
* **Invista no Seu Futuro:** Acreditamos que seu tempo e suas contribuições são valiosos e contribuirão para um legado significativo.

Convidamos você a se juntar a nós nesta jornada emocionante. Entre em contato conosco hoje mesmo e vamos construir o futuro juntos.

**[Junte-se à Comunidade](#)** | **[Contribua para o Projeto](#)**


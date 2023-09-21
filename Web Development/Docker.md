[[Docker]] é uma plataforma de virtualização de `containers` que permite que você empacote e distribua aplicativos e todas as suas dependências em um contêiner leve e portátil. Essa tecnologia é amplamente utilizada no desenvolvimento de software e na implantação de aplicativos em ambientes de produção. Aqui está uma visão geral completa do [[Docker]]:

**Containers:**

- Um `container` é uma unidade leve e isolada que inclui um aplicativo e todas as suas dependências, como bibliotecas, frameworks e configurações. Os `containers` são executados em um ambiente isolado, chamado de `container runtime`, que garante que eles sejam consistentes e portáteis em diferentes sistemas.

**[[Docker]] Engine:**

- O [[Docker]] Engine é o mecanismo que permite a criação e execução de `containers`. Ele consiste em dois componentes principais: o [[Docker]] `Daemon` (um serviço em segundo plano que gerencia `containers`) e a [[Docker]] [[CLI]] (interface de linha de comando para interagir com o [[Docker]]).

**Imagens [[Docker]]:**

- As imagens [[Docker]] são pacotes prontos para uso que contêm um aplicativo e todas as suas dependências. Você pode criar imagens personalizadas ou usar imagens disponíveis no [[Docker]] Hub, um registro público de imagens [[Docker]] mantido pela [[Docker]], Inc.

**Dockerfile:**

- Um `Dockerfile` é um arquivo de configuração usado para criar imagens [[Docker]] personalizadas. Ele descreve os passos necessários para configurar o ambiente do container e executar o aplicativo.

**Composição de Contêineres:**

- O [[Docker]] `Compose` é uma ferramenta que permite definir e executar aplicativos `multicontainer` usando um arquivo [[YAML]]. Isso é útil para configurar aplicativos compostos por vários `containers` que precisam trabalhar juntos.

**Orquestração de Contêineres:**

- `Orquestradores` de `containers`, como [[Kubernetes]], [[Docker]] Swarm e Amazon ECS, ajudam a gerenciar e escalar aplicativos em contêineres em ambientes de produção distribuídos.

**Portabilidade:**

- Uma das principais vantagens do [[Docker]] é a portabilidade. Os `containers` [[Docker]] podem ser executados em qualquer sistema que tenha o [[Docker]] Engine instalado, tornando-os ideais para ambientes de desenvolvimento, teste e produção consistentes.

**Eficiência de Recursos:**

- Os `containers` compartilham o mesmo kernel do sistema operacional, tornando-os mais eficientes em termos de recursos em comparação com máquinas virtuais tradicionais.

**Isolamento:**

- Os `containers` [[Docker]] são altamente isolados uns dos outros e do host, o que significa que eles não interferem uns com os outros e são mais seguros em termos de segurança.

**Automação:**

-  O [[Docker]] facilita a automação de implantações e integração contínua (CI) e entrega contínua (CD) por meio de scripts e [[Pipelines]] de [[CI & CD]].

**Comunidade Ativa:**

-  O [[Docker]] tem uma comunidade de desenvolvedores ativa e uma ampla variedade de recursos, tutoriais e plugins disponíveis para uso.

**Casos de Uso Comuns:**

-  Desenvolvimento e [[Testes]] de aplicativos. - Implantação de aplicativos em ambientes de produção. - Isolamento de aplicativos e ambientes. - Orquestração de aplicativos distribuídos.


**Segurança:**

-  O [[Docker]] oferece recursos de segurança, como isolamento de recursos, `namespaces` e controle de acesso, para proteger seus `containers` e aplicativos.

**Licenciamento:**

-  O [[Docker]] é distribuído sob a licença de código aberto Apache 2.0, o que significa que é gratuito para uso e personalização.

O [[Docker]] revolucionou a forma como os aplicativos são desenvolvidos e implantados, proporcionando uma maneira eficiente e confiável de empacotar, distribuir e executar software. Ele se tornou uma tecnologia fundamental para [[DevOps]], [[CI & CD]] e ambientes de micro-serviços. Se você está envolvido no desenvolvimento de software ou na administração de sistemas, é provável que encontre o [[Docker]] em seu ambiente de trabalho.
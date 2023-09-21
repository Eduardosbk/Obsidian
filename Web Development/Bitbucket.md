O [[Bitbucket]] é uma plataforma de hospedagem de código baseada em [[Git]] e [[Mercurial]], que oferece recursos de gerenciamento de repositórios, colaboração de equipe e integração contínua. É amplamente utilizado por desenvolvedores e equipes para hospedar, gerenciar e colaborar em projetos de software. Aqui estão os passos básicos para começar a usar o [[Bitbucket]]:

**Criar uma Conta no Bitbucket:**

- A primeira etapa é criar uma conta no [[Bitbucket]], caso ainda não tenha uma. Você pode fazer isso em [https://bitbucket.org/](https://bitbucket.org/). O [[Bitbucket]] oferece planos gratuitos e pagos, dependendo das necessidades do seu projeto.

**Criar um Repositório:**

- Após criar uma conta, você pode criar um novo repositório [[Bitbucket]]. Clique em `Repositórios` no painel esquerdo e, em seguida, em `Criar repositório` para começar.

**Inicializar um Repositório [[Git]] Localmente:**

- Antes de enviar seu código para o [[Bitbucket]], você deve ter um repositório [[Git]] local. Você pode inicializar um repositório [[Git]] em seu computador usando o comando `git init` em um diretório local.

**Adicionar Arquivos e Fazer Commits:**

- Adicione os arquivos do seu projeto ao repositório [[Git]] local e faça commits para registrar suas alterações. Use os comandos `git add` e `git commit` para isso.

**Conectar seu Repositório Local ao Bitbucket:**

- Após criar um repositório [[Bitbucket]] e fazer commits locais, você pode conectar seu repositório local ao [[Bitbucket]] usando o comando `git remote add origin <URL-do-seu-repositório-Bitbucket>`.

**Enviar Commits para o Bitbucket:**

- Use o comando `git push -u origin master` (ou substitua `master` pelo nome da branch que você deseja enviar) para enviar seus commits para o [[Bitbucket]].

**Gerenciar Issues e Pull Requests:**

- O [[Bitbucket]] oferece recursos para gerenciar problemas (`issues`) e solicitações de pull (`pull requests`). Você pode criar, atribuir e acompanhar problemas e revisar as alterações propostas por outros membros da equipe.

**Configurar Integração Contínua:**

- O [[Bitbucket]] oferece integração contínua com várias ferramentas, como [[Jenkins]], [[Bamboo]] e [[Bitbucket]] [[Pipelines]]. Você pode configurar essas ferramentas para automatizar builds e testes do seu projeto.

**Colaboração em Equipe:**

- Você pode convidar outros membros da equipe para colaborar no seu projeto [[Bitbucket]]. Eles podem fazer `commits`, abrir `pull requests` e revisar código.

**Branches e Merge:**

- Use `branches` para trabalhar em novas funcionalidades ou correções separadamente. Quando estiver pronto, você pode criar uma solicitação de `pull` para mesclar suas alterações na `branch` principal.

**Documentação e Wiki:**

- O [[Bitbucket]] permite que você crie documentação para o seu projeto e mantenha uma wiki com informações relevantes.

**Acompanhamento de Atividades:**

- O [[Bitbucket]] rastreia todas as atividades relacionadas ao seu projeto, incluindo `commits`, `pull requests` e comentários.

Estes são os passos básicos para começar a usar o [[Bitbucket]]. À medida que você se familiariza com a plataforma, pode explorar recursos avançados, como integrações com ferramentas de desenvolvimento, configuração de [[Pipelines]] de [[CI & CD]] e muito mais. Certifique-se de consultar a documentação oficial do [[Bitbucket]] ([https://support.atlassian.com/bitbucket-cloud/docs/](https://support.atlassian.com/bitbucket-cloud/docs/)) para obter informações detalhadas e tutoriais específicos.

[[GitHub]] e [[Bitbucket]] são duas das plataformas de hospedagem de código mais populares, ambas baseadas em [[Git]]. Embora compartilhem muitas semelhanças, também têm algumas diferenças significativas que podem influenciar a escolha entre uma ou outra, dependendo das necessidades do projeto ou equipe. Aqui estão algumas das principais diferenças entre [[GitHub]] e [[Bitbucket]]:

**Modelo de Preços:**

- [[GitHub]]:
    - Até setembro de 2021, o [[GitHub]] oferece repositórios públicos gratuitos e repositórios privados pagos.
- [[Bitbucket]]:
    - O [[Bitbucket]] oferece repositórios privados gratuitos para equipes de até 5 usuários. Além disso, ele tem opções de preços competitivas e flexíveis para equipes maiores.

**Suporte para Mercurial:**

- [[GitHub]]:
    - O [[GitHub]] oferece suporte apenas para [[Git]].
- [[Bitbucket]]:
    - Além do [[Git]], o [[Bitbucket]] oferece suporte para repositórios [[Mercurial]], o que pode ser útil se você ou sua equipe estiverem usando [[Mercurial]].

**Integração Contínua e Implantação Contínua ([[CI & CD]]):**

- [[GitHub]]:
    - O [[GitHub]] Actions é uma ferramenta de [[CI & CD]] nativa integrada ao [[GitHub]]. Você pode criar pipelines de integração e entrega contínua diretamente no [[GitHub]].
- [[Bitbucket]]:
    - O [[Bitbucket]] [[Pipelines]] é uma ferramenta de [[CI & CD]] nativa integrada ao [[Bitbucket]]. Ele oferece recursos semelhantes aos do [[GitHub]] Actions.

**Acesso a Recursos Avançados:**

- [[GitHub]]:
    - O [[GitHub]] oferece acesso a recursos avançados, como [[GitHub]] Actions, [[GitHub]] Pages (para hospedagem de sites estáticos), [[GitHub]] Packages (para hospedagem de pacotes) e [[GitHub]] Insights (para análise de código).
- [[Bitbucket]]:
    - O [[Bitbucket]] oferece recursos adicionais, como [[Jira]] Software integrado (um sistema de rastreamento de problemas), [[Bitbucket]] Server (para hospedagem local) e uma extensa lista de integrações com outras ferramentas.

**Escalabilidade:**

- [[GitHub]]:
    - O [[GitHub]] é frequentemente escolhido para projetos de código aberto devido à sua grande base de usuários e à ampla visibilidade que oferece.
- [[Bitbucket]]:
    - O [[Bitbucket]] é frequentemente escolhido por equipes que precisam de repositórios privados e podem aproveitar os preços competitivos.

**Acesso à [[APIs]]:**

- Ambas as plataformas oferecem [[APIs]] para integração com outras ferramentas e personalização.

**Suporte ao Enterprise:**

- [[GitHub]]:
    - O [[GitHub]] oferece [[GitHub]] Enterprise, uma solução de nuvem privada para empresas que desejam hospedar seus próprios repositórios [[Git]].
- [[Bitbucket]]:
    - O [[Bitbucket]] Server é uma versão do [[Bitbucket]] que pode ser hospedada localmente em uma infraestrutura da empresa.

**Experiência do Usuário:**

- A [[UX]], a [[UI]] e os recursos específicos podem variar entre as duas plataformas, e a preferência pessoal desempenha um papel importante na escolha entre elas.

A escolha entre [[GitHub]] e [[Bitbucket]] dependerá das necessidades específicas do seu projeto ou equipe, do modelo de preços desejado e das preferências pessoais. Ambas as plataformas são excelentes opções para o gerenciamento de código-fonte, e a escolha entre elas geralmente envolve a consideração dessas diferenças e a análise de como elas se alinham com as necessidades do seu projeto.
**Conta [[Heroku]]:**

- Primeiro, você precisa criar uma conta no [[Heroku]] em [https://www.heroku.com/](https://www.heroku.com/). A conta gratuita permite implantar aplicativos básicos, enquanto planos pagos oferecem recursos adicionais.

**[[Heroku]] [[CLI]]:**

- Para interagir com a plataforma [[Heroku]] a partir da linha de comando, é necessário instalar a [[Heroku]] Command Line Interface ([[CLI]]). Você pode fazer o download em [https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli).

**[[Git]]:**

- O [[Heroku]] usa o Git para implantação de aplicativos. Certifique-se de ter o [[Git]] instalado e configurado em seu sistema.

**Criar um Aplicativo:**

- Use o comando `heroku create` na linha de comando para criar um novo aplicativo [[Heroku]].

**Implantação de Código:**

- Adicione seus arquivos de aplicativo ao Git, faça o commit das alterações e, em seguida, use o comando `git push heroku master` para implantar seu aplicativo no [[Heroku]].

**Dynos:**

- Os dynos são os contêineres virtuais que executam seu aplicativo no [[Heroku]]. Você pode dimensionar os dynos para atender às necessidades do seu aplicativo.

**Add-ons:**

- Os add-ons são serviços oferecidos pelo [[Heroku]] e por terceiros que podem ser facilmente adicionados ao seu aplicativo. Isso inclui bancos de dados, cache, monitoramento, entre outros.

**[[Variáveis de Ambiente]]:**

- O [[Heroku]] permite configurar variáveis de ambiente para armazenar informações sensíveis, como chaves de [[APIs]] e credenciais de [[Banco de Dados]].

**Logs e Monitoramento:**

- O [[Heroku]] oferece ferramentas para visualizar os logs do seu aplicativo e monitorar seu desempenho.

**Escalonamento:**

- Você pode dimensionar seu aplicativo horizontalmente (adicionando mais dynos) ou verticalmente (usando planos pagos) conforme necessário.

**Domínios Personalizados:**

- Você pode vincular seu próprio domínio personalizado ao seu aplicativo [[Heroku]].

**Segurança e Backup:**

- Mantenha a segurança do seu aplicativo implementando práticas recomendadas e faça backup regularmente dos seus dados.

**[[Integração Contínua]]:**

- O [[Heroku]] se integra facilmente com várias ferramentas de integração contínua (CI), como o Travis CI e o [[CircleCI]].

**Comandos Úteis:**

- Alguns comandos úteis da [[CLI]] do [[Heroku]] incluem `heroku logs`, `heroku ps`, `heroku addons`, `heroku config`, `heroku run`, entre outros.

[[Heroku]] oferece muitos recursos e opções avançadas, e esta é apenas uma visão geral básica. Conforme você começa a usar o [[Heroku]], você pode explorar esses recursos com mais detalhes e personalizar sua implantação de acordo com as necessidades do seu aplicativo. Além disso, a documentação oficial do [[Heroku]] ([https://devcenter.heroku.com/](https://devcenter.heroku.com/)) é uma ótima fonte de informações detalhadas e tutoriais.
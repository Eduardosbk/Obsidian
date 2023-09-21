Amazon [[DynamoDB]] é um serviço de banco de dados [[NoSQL]] totalmente gerenciado oferecido pela Amazon Web Services ([[AWS]]). Ele foi projetado para ser escalável, flexível e altamente disponível, permitindo que os desenvolvedores armazenem e acessem dados com baixa latência e alta performance. Aqui está uma visão geral abrangente do Amazon [[DynamoDB]]:

**[[NoSQL]] e Modelo de Dados:**

- [[DynamoDB]] é um banco de dados [[NoSQL]], o que significa que não segue o modelo relacional tradicional. Em vez disso, ele utiliza um modelo de dados flexível baseado em pares de chave-valor. Cada item é identificado por uma chave única.

**Escalabilidade Automática:**

- Uma das principais vantagens do [[DynamoDB]] é sua capacidade de escalar automaticamente para acomodar cargas de trabalho crescentes. Você não precisa se preocupar com provisionamento de capacidade ou dimensionamento manual.

**Latência Baixa:**

- [[DynamoDB]] é otimizado para oferecer baixa latência de leitura e gravação, tornando-o adequado para aplicativos que exigem acesso rápido aos dados, como aplicativos da web em tempo real.

**Modelagem Flexível:**

- Além do modelo `chave-valor`, [[DynamoDB]] permite que você armazene dados de maneira hierárquica usando tabelas aninhadas e suporta tipos de dados como números, strings, listas, mapas e binários.

**Consistência e Durabilidade:**

- [[DynamoDB]] oferece várias opções de consistência para atender às necessidades do seu aplicativo, incluindo consistência eventual e consistência forte. Além disso, ele fornece durabilidade de dados por meio de replicação síncrona em várias zonas de disponibilidade.

**Escalabilidade Global:**

- [[DynamoDB]] suporta a replicação global, permitindo que você implante suas tabelas em várias regiões da [[AWS]] para garantir baixa latência e alta disponibilidade em todo o mundo.

**Modelos de Pagamento Flexíveis:**

- Você pode optar por pagar pelo uso sob demanda ou provisionar a capacidade de leitura e gravação para garantir um desempenho constante. [[DynamoDB]] também oferece opções de armazenamento aprimorado para cargas de trabalho com requisitos de leitura consistentes.

**Segurança:**

- [[DynamoDB]] oferece controles de segurança robustos, incluindo autenticação, autorização, criptografia de dados em repouso e em trânsito, e monitoramento com o [[AWS]] CloudTrail.

**Integração com Outros Serviços [[AWS]]:**

- [[DynamoDB]] se integra facilmente com outros serviços da [[AWS]], como [[AWS]] , Amazon S3, [[AWS]] AppSync e Amazon API Gateway, tornando-o parte integrante das arquiteturas de aplicativos modernos.

**Modelagem de Dados Avançada:**

 `- Além de tabelas simples, DynamoDB permite a criação de índices globais secundários e locais para consultas avançadas e consultas complexas.`

**Monitoramento e Otimização:**

 `- O AWS CloudWatch e o AWS X-Ray podem ser usados para monitorar o desempenho do DynamoDB e otimizar consultas.`

**Backup e Restauração:**

 `- DynamoDB oferece recursos de backup e restauração para proteger seus dados contra perda acidental.`

**Facilidade de Uso:**

 `- DynamoDB é fácil de começar a usar, com uma API simples e documentação abrangente.`

**Planos de Preços:**

 `- DynamoDB tem planos de preços flexíveis com opções de pagamento sob demanda e provisionamento de capacidade.`

Amazon [[DynamoDB]] é amplamente utilizado em aplicativos da web, móveis e de Internet das Coisas ([[IoT]]) para armazenar e recuperar dados de maneira escalável e confiável. Sua capacidade de dimensionamento automático, latência baixa e integração com outros serviços da [[AWS]] o tornam uma escolha popular para uma ampla variedade de casos de uso.
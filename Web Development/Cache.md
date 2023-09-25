[[Cache]] é uma técnica de armazenamento temporário de dados usada em computação para melhorar o desempenho e a velocidade de acesso a informações frequentemente usadas. O principal objetivo do cache é reduzir a necessidade de acessar fontes de dados mais lentas, como discos rígidos ou servidores remotos, armazenando cópias temporárias desses dados em um local mais rápido e de fácil acesso. Aqui estão alguns aspectos importantes sobre o cache:

**Funcionamento Básico**:

- Quando um sistema precisa de um determinado dado, ele primeiro verifica se ele está no cache. Se estiver, o dado é recuperado rapidamente a partir do [[Cache]].
- Se o dado não estiver no cache (um `cache miss`), o sistema buscará a informação na fonte original e a armazenará no cache para uso futuro.

**Tipos de [[Cache]]**:

- **[[Cache]] de Memória**: Usado para armazenar cópias de dados da memória principal (RAM) para acelerar o acesso à memória.
- **[[Cache]] de Disco**: Armazena partes de dados frequentemente acessados de discos rígidos ou dispositivos de armazenamento para acelerar o acesso a esses dados.
- **[[Cache]] de Navegador**: Usado no [[Desenvolvimento Web]] para armazenar temporariamente recursos, como imagens, scripts e páginas da web, para acelerar o carregamento de sites.
- **[[Cache]] de CPU**: Refere-se aos caches internos de uma unidade central de processamento (CPU) que armazenam instruções e dados frequentemente usados para acelerar a execução de programas.

**Vantagens**:

- Melhora significativamente o desempenho e a capacidade de resposta do sistema, reduzindo os atrasos de acesso a dados.
- Reduz a carga nos recursos mais lentos, como discos rígidos ou servidores, aliviando a pressão sobre esses componentes.

**Desvantagens**:

- O gerenciamento inadequado do cache pode levar a inconsistências de dados, quando o cache não reflete com precisão o estado dos dados na fonte original.
- A gestão do cache requer alocação de recursos, como memória, que poderiam ser usados ​​para outros fins.

**Políticas de Substituição**:

- Quando o cache está cheio e uma nova informação precisa ser armazenada, é necessário escolher qual dado existente no cache será substituído. Isso é feito por meio de políticas de substituição, como LRU (`Least Recently Used`), FIFO (First-In, First-Out) e LFU (`Least Frequently Used`).

**[[Cache]] na Web**:

- Em navegadores da web, o cache é usado para armazenar temporariamente recursos de páginas da web, como imagens, scripts e folhas de estilo, para evitar o download repetido desses recursos, melhorando a velocidade de carregamento.

**Invalidação de [[Cache]]**:

- É importante gerenciar a invalidação de cache para garantir que as informações armazenadas no cache estejam atualizadas. Isso pode ser feito manualmente ou automaticamente, dependendo do sistema.

**[[Cache]] de Hardware e Software**:

- O cache pode ser implementado tanto em hardware (como CPUs e controladores de disco) quanto em software (como sistemas de gerenciamento de cache em sistemas operacionais).

**[[Cache]] em Redes**:

- Em redes de computadores, os caches de proxy e CDN (Content Delivery Network) são usados para armazenar cópias de conteúdo da web em locais geograficamente distribuídos para melhorar a entrega de conteúdo aos usuários finais.


**Cache em [[Banco de Dados]]**:

- Os sistemas de gerenciamento de banco de dados (DBMS) usam cache para armazenar em memória consultas frequentemente executadas e seus resultados, acelerando as operações de leitura.

O uso eficaz de [[Cache]] é fundamental para otimizar o desempenho de sistemas de computador e redes, melhorando a experiência do usuário e reduzindo a carga em recursos críticos. No entanto, é importante equilibrar o uso do cache com estratégias de invalidação e gerenciamento para garantir que os dados estejam sempre atualizados e consistentes.
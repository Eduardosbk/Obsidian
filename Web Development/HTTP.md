O Protocolo de Transferência de Hipertexto ([[HTTP]]), é um protocolo de comunicação usado para transferir dados pela World Wide Web (WWW). Ele é fundamental para a troca de informações na internet e é a base da maioria das operações na web. Aqui estão os principais conceitos e características relacionados ao [[HTTP]]:
### **Protocolo Cliente-Servidor:**

O [[HTTP]] segue um modelo cliente-servidor, onde um cliente (geralmente um navegador web) faz solicitações a um servidor web para acessar recursos (como páginas da web) hospedados no servidor.

### **Métodos [[HTTP]]:**

- O [[HTTP]] define vários métodos (ou verbos) que indicam a ação que o cliente deseja executar no servidor. Os métodos [[HTTP]] mais comuns são:
    - **GET:** Solicita um recurso do servidor.
    - **POST:** Envia dados para o servidor, geralmente para criar ou atualizar recursos.
    - **PUT:** Substitui ou atualiza um recurso no servidor.
    - **DELETE:** Remove um recurso do servidor.
    - **HEAD:** Solicita apenas os cabeçalhos de resposta, sem o corpo do recurso.
    - **OPTIONS:** Pede ao servidor informações sobre os métodos [[HTTP]] suportados e outras opções.
    - **PATCH:** Aplica modificações parciais a um recurso.

### **URLs (Uniform Resource Locators):**

- As [[URLs]] são usadas para identificar recursos na web. Elas consistem em um esquema (como "[[http]]" ou "https"), um domínio (como "[www.example.com](http://www.example.com/)") e um caminho para o recurso específico (como "/pagina.html").
### **Headers [[HTTP]]:**

- Os cabeçalhos [[HTTP]] são usados para transmitir informações adicionais nas solicitações e respostas [[HTTP]]. Por exemplo, o cabeçalho `User-Agent` informa ao servidor qual navegador ou agente do usuário está sendo usado.

### **Status HTTP:**

- As respostas HTTP incluem um código de status que indica o resultado da solicitação. Alguns códigos de status comuns incluem 200 (OK), 404 (Não encontrado) e 500 (Erro interno do servidor).

### **[[Cookie]] e Sessões:**

- Os [[Cookie]] são pequenos pedaços de dados armazenados no navegador do cliente e enviados com cada solicitação [[HTTP]] subsequente. Eles são frequentemente usados para rastrear a autenticação do usuário e o estado da sessão.

### **Segurança e HTTPS:**

- O [[HTTP]] não é seguro por padrão, o que significa que as informações transmitidas entre o cliente e o servidor podem ser interceptadas por terceiros. O HTTPS ([[HTTP]] Secure) é uma versão segura do [[HTTP]] que criptografa as comunicações entre o cliente e o servidor usando SSL/TLS.
### **Cache e Controle de Cache:**

- O [[HTTP]] suporta recursos em cache para reduzir a sobrecarga do servidor. Os cabeçalhos [[HTTP]], como `Cache-Control` e `Expires`, são usados para controlar o cache no lado do cliente e do servidor.

### **Redirecionamento:**

- O [[HTTP]] permite que os servidores redirecionem o cliente para outra URL. Isso é comumente usado para redirecionar [[URLs]] antigas para novas, ou para realizar encaminhamentos.

### **HTTP/1.1 e HTTP/2:**

- O [[HTTP]]/1.1 é a versão mais comum do [[HTTP]], mas o [[HTTP]]/2 é uma versão mais recente e eficiente que oferece melhor desempenho por meio de várias otimizações, como `multiplexação` de solicitações e compactação de cabeçalhos.

### **Web [[APIs]]:**

- Muitos serviços e aplicativos web fornecem [[APIs]] baseadas em [[HTTP]] que permitem a integração com suas funcionalidades por meio de solicitações [[HTTP]].

### **[[REST]] e RESTful [[APIs]]:**

- REST (Representational State Transfer) é uma arquitetura de estilo que utiliza [[HTTP]] para criar APIs web. As APIs RESTful são projetadas em torno dos princípios [[REST]] e são amplamente utilizadas para [[Desenvolvimento Web]].

[[HTTP]] é um protocolo fundamental que permite a interação e a transferência de dados na web. Compreender seus princípios básicos é essencial para o desenvolvimento e a operação de aplicativos e serviços web.
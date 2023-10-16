[[Axios]] é uma biblioteca [[JavaScript]] popular usada para fazer requisições [[HTTP]] a [[APIs]] web e receber dados. Ele funciona tanto em navegadores quanto em servidores, tornando-o versátil para desenvolvedores [[Front-End]] e [[Back-End]].

### **Configuração Básica**

Para começar a usar o [[Axios]], primeiro, você precisa instalá-lo e importá-lo no seu projeto:

```bash
npm install axios # ou yarn add axios
```

Depois, importe o [[Axios]] no seu arquivo [[JavaScript]]:

```js
const axios = require('axios');
```

### **Fazendo Requisições GET**

```js
axios.get('https://api.example.com/data') .then(response => { console.log(response.data); }) .catch(error => { console.error(error); });
```

### **Fazendo Requisições POST**

```js
axios.post('https://api.example.com/data', { key: 'value' }) .then(response => { console.log(response.data); }) .catch(error => { console.error(error); });
```

### **Interceptar Requisições e Respostas**

Interceptar requisições e respostas permite que você adicione configurações personalizadas antes de enviar uma requisição ou após receber uma resposta.

```js
axios.interceptors.request.use(request => {/* Adicione configurações à requisição antes de ser enviada*/ return request; }, error => { return Promise.reject(error); }); axios.interceptors.response.use(response => { /* Faça algo com a resposta antes de ser entregue ao código que fez a chamada*/ return response; }, error => { return Promise.reject(error); });
```

### **Configurações Avançadas**

```js
const instance = axios.create({ baseURL: 'https://api.example.com', timeout: 5000, /* Tempo limite para a requisição*/ headers: {'Authorization': 'Bearer YOUR_ACCESS_TOKEN'} }); instance.get('/data') .then(response => { console.log(response.data); }) .catch(error => { console.error(error); });
```

### **Trabalhando com Assincronia**

Você pode usar o [[Axios]] com `async/await` para lidar com operações assíncronas de forma mais limpa:

```js
async function fetchData() { try { const response = await axios.get('https://api.example.com/data'); console.log(response.data); } catch (error) { console.error(error); } } fetchData();
```

### **Cancelando Requisições**

```js
const source = axios.CancelToken.source();  axios.get('https://api.example.com/data', {   cancelToken: source.token })   .then(response => {     console.log(response.data);   })   .catch(thrown => {     if (axios.isCancel(thrown)) {       console.log('Requisição cancelada: ', thrown.message);     } else {       console.error(thrown);     }   });  /* Para cancelar a requisição*/ source.cancel('Requisição cancelada pelo usuário.');`
```

### **Tratamento de Erros Globais**

Configure um manipulador de erro global para lidar com erros em todas as requisições [[Axios]]:

```js
axios.interceptors.response.use(response => response, error => { console.error('Erro global de requisição:', error); return Promise.reject(error); });
```

Este guia deve cobrir desde o básico até alguns conceitos avançados do [[Axios]]. Lembre-se de que a prática é crucial ao trabalhar com qualquer [[Bibliotecas e Frameworks]]. Experimente esses exemplos em seu próprio ambiente de desenvolvimento para aprimorar suas habilidades no [[Desenvolvimento Web]].
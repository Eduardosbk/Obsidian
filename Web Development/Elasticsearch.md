[[Elasticsearch]] é um mecanismo de busca e análise de código aberto, amplamente utilizado para pesquisar, analisar e visualizar dados em tempo real. Ele é baseado no [[Apache]] Lucene e é desenvolvido em [[Java]]. [[Elasticsearch]] é altamente escalável e pode lidar com grandes volumes de dados.

**Principais Conceitos:**

**Cluster:** Um `cluster` [[Elasticsearch]] é composto por um ou mais nós (servidores) que armazenam dados e cooperam entre si para garantir a disponibilidade e a escalabilidade do sistema.

**Nó (Node):** Um nó é uma instância única de [[Elasticsearch]] que faz parte de um `cluster`. Cada nó armazena dados e participa das operações de indexação e pesquisa.

**Índice (Index):** Um índice é uma coleção de documentos com características similares. Ele é armazenado como um conjunto de `shards` para garantir a escalabilidade.

**Shard:** Um `shard` é uma unidade básica de armazenamento no [[Elasticsearch]]. Cada índice pode ser dividido em múltiplos `shards` para melhorar a eficiência e a distribuição de dados.

**Documento (Document):** Um documento é uma unidade básica de informação em [[Elasticsearch]] e é expresso em JSON. Todos os dados em [[Elasticsearch]] são armazenados como documentos.

**Operações Básicas:**

**Indexação de Documentos:**

Para indexar um documento em um índice chamado `meu_indice`, você pode usar a seguinte requisição [[HTTP]]:

```bash
PUT /meu_indice/_doc/1
{
  "campo1": "valor1",
  "campo2": "valor2"
}
```

**Recuperando Documentos:**

Para recuperar um documento pelo seu ID:

```bash
GET /meu_indice/_doc/1
```

**Consulta Simples:**

Para realizar uma consulta simples, onde você está buscando documentos que correspondem a um termo específico:

```bash
GET /meu_indice/_search
{
  "query": {
	"match": {
	  "campo1": "valor1"
	}
  }
}
```

**Exemplos de Consultas Avançadas:**

**Consulta de Correspondência Parcial:**

Para encontrar documentos que correspondem a parte de um termo:

```bash
GET /meu_indice/_search { "query": { "wildcard": { "campo1": "va*" } } }
```

**Consulta de Correspondência de Frase:**

Para encontrar documentos que correspondem a uma frase específica:

```bash
GET /meu_indice/_search { "query": { "match_phrase": { "campo1": "termo específico" } } }
```
**Consulta de Intervalo:**

Para encontrar documentos com um campo dentro de um intervalo específico:

```bash
GET /meu_indice/_search { "query": { "range": { "campo_numérico": { "gte": 10, "lte": 100 } } } }
```

**Conclusão:**

Este é apenas um breve `overview` do [[Elasticsearch]]. Ele é uma ferramenta poderosa com uma vasta gama de funcionalidades e opções de consulta. Para explorar completamente o [[Elasticsearch]], é recomendável consultar a [documentação oficial do Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html), que fornece uma compreensão profunda de seus recursos e capacidades.

Lembre-se de que este é um campo vasto, então pratique e experimente para realmente entender como o [[Elasticsearch]] pode beneficiar seus casos de uso específicos.
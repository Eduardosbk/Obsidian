[[TypeScript]] é um superconjunto tipado de JavaScript que compila para JavaScript puro. Desenvolvido pela Microsoft, o [[TypeScript]] adiciona tipagem estática opcional ao [[JavaScript]], o que significa que você pode declarar tipos para suas variáveis, parâmetros de função e retornos de função. Isso ajuda a detectar erros durante o desenvolvimento e fornece ferramentas de desenvolvimento mais robustas.

Principais Características do [[TypeScript]]:
Tipagem Estática: Você pode especificar o tipo de uma variável usando a notação : tipo. Isso ajuda a capturar erros comuns antes mesmo de executar o código.

Exemplo:

```typescript
	let numero: number = 5;
	let nome: string = 'Alice';
```

**Interfaces**: As interfaces são usadas para definir contratos para objetos em [[TypeScript]]. Elas ajudam a definir a estrutura de um objeto, incluindo os tipos de seus membros.

Exemplo:

```typescript
	interface Pessoa {
	    nome: string;
	    idade: number;
	}

	let pessoa: Pessoa = { nome: 'João', idade: 30 };
```

**Classes**: [[TypeScript]] suporta classes com suporte completo para herança e modificadores de acesso.

Exemplo:

```typescript
	class Animal {
    constructor(public nome: string) {}

    fazerBarulho() {
        console.log(`${this.nome} faz algum barulho.`);
    }
}

let gato = new Animal('Whiskers');
```

**Tipos Genéricos**: Você pode criar funções e classes que trabalham com um tipo genérico, permitindo maior reutilização de código.

Exemplo:

```typescript
	function imprimirArray<T>(arr: T[]): void {
    arr.forEach(item => console.log(item));
}

imprimirArray([1, 2, 3]);
```

**`Enums`**: `Enums` são uma maneira de dar nomes mais amigáveis a conjuntos de valores numéricos.

Exemplo:

```typescript
	enum DiaDaSemana {
    Segunda,
    Terca,
    Quarta,
    Quinta,
    Sexta,
    Sabado,
    Domingo
}

let hoje: DiaDaSemana = DiaDaSemana.Quarta;
```

### Exemplo de Aplicação Simples em [[TypeScript]]:

Agora, vamos criar uma aplicação simples que utiliza [[TypeScript]] para exibir uma saudação personalizada com base no nome inserido pelo usuário em um campo de entrada.

- Instale o [[TypeScript]] globalmente se ainda não estiver instalado:

```shell
	npm install -g typescript
```

Crie um arquivo chamado `app.ts` com o seguinte código:

```typescript
// app.ts
interface Saudacao {
    nome: string;
    mensagem: string;
}

function saudar({ nome, mensagem }: Saudacao): void {
    console.log(`${mensagem}, ${nome}!`);
}

let usuario: Saudacao = { nome: 'Alice', mensagem: 'Olá' };

saudar(usuario);
```

Compile o código [[TypeScript]] para [[JavaScript]]:

```shell
tsc app.ts
```

Isso gerará um arquivo `app.js`. Agora, você pode executá-lo usando o [[Node.js]]:

```shell
node app.js
```

Este é um exemplo simples para ilustrar como o [[TypeScript]] adiciona tipos à linguagem, fornecendo benefícios adicionais durante o [[Desenvolvimento Web]]. Você pode explorar mais recursos e usos avançados à medida que se aprofunda no [[TypeScript]].
## Evoluindo no [[Typescript]]:

**Explore os Recursos Avançados de Tipagem**:
- [[TypeScript]] oferece recursos avançados de tipagem, como uniões (`union types`), interseções (`intersection types`), tipos condicionais (`conditional types`) e tipos genéricos condicionais. Explore esses recursos para criar tipos mais precisos e flexíveis.

**Use Mapeamento de Tipos**:
- O mapeamento de tipos permite criar novos tipos com base em tipos existentes. Isso é útil para transformar tipos, criar tipos utilitários e realizar operações complexas de tipo.

**Type Inference**:
- Aproveite a capacidade de inferência de tipos do [[TypeScript]] sempre que possível. O [[TypeScript]] pode inferir os tipos com base nos valores atribuídos, reduzindo a necessidade de anotações de tipo explícitas.

**Strict Mode**:
- Ative o modo estrito (`strict`) no seu arquivo `tsconfig.json`. Isso habilita verificações mais rigorosas, como verificação de tipos nulos (`strictNullChecks`) e checagem estrita de propriedades (`strictPropertyInitialization`), que ajudam a evitar erros comuns.

**Decorators**:
- Use decoradores para adicionar metadados e funcionalidade a classes, métodos e propriedades. Isso é especialmente útil em estruturas como [[Angular]].

**Integração com IDEs**:
- Configure seu ambiente de desenvolvimento integrado (IDE) para obter o máximo benefício do [[TypeScript]]. A maioria dos IDEs modernos oferece suporte ao [[TypeScript]] com recursos de `autocompletar`, realce de sintaxe e verificação de tipo em tempo real.

**Documentação**:
- Documente seu código [[TypeScript]] usando comentários de JSDoc. Isso não apenas ajuda outras pessoas a entenderem seu código, mas também permite que as ferramentas IDE forneçam informações úteis sobre tipos e parâmetros de função.

**Integração com JavaScript**:
- O [[TypeScript]] pode ser integrado perfeitamente com código [[JavaScript]] existente. Use a opção `allowJs` no `tsconfig.json` para permitir a compilação de arquivos [[JavaScript]].

**Testes Unitários**:
- Use estruturas de teste como [[Jest]] ou Mocha junto com [[TypeScript]] para escrever testes unitários robustos. O [[TypeScript]] torna mais fácil testar seu código, pois fornece informações claras sobre tipos.

**Validação em Tempo de Compilação**:
- Aproveite ao máximo a verificação de tipos em tempo de compilação. Isso ajuda a pegar erros antes de executar o código, tornando-o mais seguro e eficiente.

**Ferramentas de Terceiros**:
- Explore bibliotecas e ferramentas de terceiros que são específicas para [[TypeScript]], como `tslint`, `ts-node`, `tsdx`, e outras que podem simplificar tarefas de desenvolvimento.

**Preste Atenção às Atualizações**:
- O [[TypeScript]] continua evoluindo, com novos recursos e melhorias em cada versão. Mantenha-se atualizado com as últimas atualizações e aproveite as melhorias.

**Comunidade e Recursos Online**:
- Participe da comunidade [[TypeScript]] online, siga tutoriais, leia documentação e participe de fóruns para aprender com outros desenvolvedores e obter ajuda quando necessário.

Lembrando que o [[TypeScript]] é uma ferramenta poderosa para aumentar a qualidade e a manutenibilidade do seu código JavaScript, mas também pode ter uma curva de aprendizado íngreme, especialmente ao se trabalhar com recursos avançados de tipagem. Portanto, pratique e explore gradualmente os recursos do [[TypeScript]] à medida que ganha mais confiança e experiência.
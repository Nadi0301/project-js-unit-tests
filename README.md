# JavaScript Unit Tests

Projeto desenvolvido para praticar o desenvolvimento orientado a testes (TDD) e a escrita de testes unitários em JavaScript utilizando o framework **Jest**.

## Sobre o Projeto

O objetivo deste projeto é implementar funções em JavaScript seguindo requisitos específicos e desenvolver suítes de testes unitários para garantir o comportamento esperado, o tratamento de exceções e a cobertura de casos de borda.

### Funcionalidades e Testes Implementados

- **`average`**: Calcula a média aritmética de um array de números, validando tipos não numéricos e arrays vazios.
- **`vqv`**: Retorna uma frase formatada com nome e idade, tratando entradas ausentes.
- **`numbers`**: Verifica se todos os elementos de um array são do tipo numérico.
- **`circle`**: Calcula área e circunferência de um círculo a partir do raio informado.
- **`createStudent`**: Cria um objeto representando uma pessoa estudante com método de feedback.
- **`productDetails`**: Retorna uma lista estruturada de objetos com detalhes de dois produtos.
- **`objPlayground`**: Realiza operações de cálculo e conversão de objetos (`Object.keys`, `Object.values`, `Object.entries`).
- **`myCounter`**: Executa loops aninhados para geração sequencial de valores.
- **`getCharacter`**: Busca informações e frases de personagens a partir do nome (case-insensitive).
- **`restaurant`**: Gerencia pedidos de um restaurante e calcula o valor total da conta com acréscimo de 10%.

## Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **Node.js**
- **Jest** (Testes Unitários)
- **ESLint** (Padronização de código)

## Estrutura do Projeto

``text
├── src/          # Implementação das funções
├── tests/        # Suítes de testes unitários (*.spec.js)
├── package.json  # Dependências e scripts de execução
└── README.md     # Documentação do projeto
``

## Como Executar Localmente

1. Clone este repositório:
   ``bash
   git clone [https://github.com/Nadi0301/project-js-unit-tests.git](https://github.com/Nadi0301/project-js-unit-tests.git)
   ``

2. Acesse a pasta do projeto:
   ``bash
   cd project-js-unit-tests
   ``

3. Instale as dependências:
   ``bash
   npm install
   ``

4. Execute a suíte de testes:
   ``bash
   npm test
   ``

---

Desenvolvido por **Nadijane Souza** — [GitHub](https://github.com/Nadi0301)

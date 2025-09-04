Exercícios de Lógica e Programação com JavaScript.
Os exercícios fazem parte das aulas de Lógica e Programação da Mentoria em Testes de Software do Júlio de Lima. 
Objetivo: Treinar a implemescrita de funções em JavaScript, implementando funções de somar dois números e de calcular a média desses dois números. 
Foram criados testes automatizados para ambas as funções utilizando Mocha e Chai, além de testes manuais.

Funcionalidades
Soma de Dois Números
Função que recebe dois números e retorna a soma deles.

Cálculo de Média
Função que recebe dois números e retorna a média entre eles.

Arquivo principal: src/calculadora.js Testes: test/calculadora.test.js (testes automatizados com Mocha e Chai para soma e média) 

Configuração:
package.json para dependências e scripts
.gitignore para arquivos ignorados pelo Git
Estrutura do Projeto
logica-e-programacao/
├── src/
│   └── calculadora.js
├── tests/
│   └── calculadora.test.js
├── package.json
└── .gitignore
Como Testar
Os testes automatizados das funções estão no arquivo test/calculadora.test.js

Para executar todos os testes com Mocha, utilize:
npx mocha tests

Observações
Este exercício é simples e agora conta com testes automatizados para as funções.

Licença
Este projeto está sob a licença MIT.

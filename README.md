# 💻 Commits Semânticos

De acordo com o que já vi ser mais utilizado em lugares onde atuei e também usado em projetos específicos.

## 📕 Formato
O seguinte formato para os commits devem ser observados, é obrigatório o uso do _type_, ele pode ser consultado no tópico abaixo, já a descrição, retrata qual a ação que o atual commit irá realizar:

`<type>: <description>`

## 🔷 Type
Os _types_ são os seguintes:

| Prefixo | Definição           | Sentido                                        |
|---------|---------------------|------------------------------------------------|
| build   | Builds              | Mudanças que afetam o sistema de build ou dependências externas (exemplos de escopos: npm, gulp) |
| chore   | Tarefas             | Mudanças que não modificam arquivos de teste ou de código-fonte |
| ci      | Integrações Contínuas | Alterações em nossos arquivos e scripts de configuração de CI (exemplos de escopos: BrowserStack, Circle, Travis) |
| docs    | Documentação        | Somente mudanças na documentação               |
| feat    | Features            | Alguma nova funcionalidade                        |
| fix     | Correções de Erros  | Correção de bug                            |
| perf    | Melhorias de Performance | Alteração de código que melhora o desempenho |
| refactor| Refatoração de Código | Alteração de código que não adiciona uma funcionalidade nem corrige um bug |
| revert  | Reverter            | Reverte um commit anterior                    |
| style   | Estilos             | Alterações com relação à estilização              |
| test    | Testes              | Correção de testes existentes ou adição de testes faltantes |

## ✒️ Autor

* **[Thomas Ribeiro](https://github.com/thribeiro8)** 

## 📌 Referências

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Karma Runner](https://karma-runner.github.io/6.3/dev/git-commit-msg.html)

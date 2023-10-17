# Projeto_BDD_Alura

## :information_source: BDD

O Behavior Driven Development (BDD) é uma metodologia ágil tem como objetivo fazer um processo de entendimento do projeto com todas as áreas que vão atuar no mesmo, seja cliente, desenvolvedor, PO. Após reunir todos para entender os objetivos do projeto é feito um documento para formalizar todo o projeto, o mesmo não necessariamente precisa ser técnico. Posterior a isso é dado início ao desenvolvimento do projeto e como ultima etapa é realizada as validações pelo cliente.

---

## :information_source: Cucumber

Como queremos integrar todos os envolvidos no projeto, incluindo aqueles que não conhecem programão como por exemplo o cliente. Nosso objetivo ao implementar o cucumber é facilitar  o entendimento de todos utilizando uma linguagem mais natural e não uma linguagem de código para criar as regras e funcionalidades do sistema.

---

## Funcionalidades do Cucumber

### :one: Scenario Outline

Após aprendermos os conceitos básicos do cucumber, como criar e implementar os teste automatizados. Utilizamos o **Scenario Outline** para aprimorar os teste, pois utilizando ele conseguimos realizar um teste que tenha a mesma estrutura mas que precise de valores diferentes para serem avaliados. Com isso não é necessário a duplicidade, pois podemos construir um único teste passando uma “lista” de múltiplos valores por meio do Scenario Outline, assim aumentando a dinamicidade do mesmo.

### :two: DataTables

As DataTables tem o mesmo intuito do **Scenario Outline** mas ambos tem uma diferença na hora de execução. Com o DataTables só ocorre uma execução e o intuito é passar os dados de um só vez e fazer com que o teste trabalhe com eles. Já o Scenario Outline o teste é executado varias vezes, o equivalente a quantidade de dados que você deseja passar por meio dele.


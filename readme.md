### *Desafio Renner API*
<br/>
Testes de Usuário através da API https://reqres.in/api/users

#### *Automatizando os testes:*
- Cadastro de usuário
- Consulta de usuário
- Consulta lista de usuário
- Update de usuário
<br/><br/>

#### *Com as seguintes tecnologias*<br/>
- Java
- Cucumber
- RestAssured
- JUnit
- Maven
<br/>

#### *Motivo da escolha do cucumber:*
- Pra uma boa escrita de código e podendo reutilizar os métodos criados,
o qual é um dos pontos fortes do Cucumber + Gherkin
<br/><br/>
#### *RestUtils*
- Uma classe criada para utilização dos métodos comuns do RestAssured
- Facilitando o uso de diversos métodos

#### *UsersSteps*
- Classe que contém os passos que devem ser executados
- Nele estão os métodos que foram gerados pelo cucumber*

#### *RunnerTest*
- Classe responsável para executar os testes
- É uma classe com execução JUnit
- Podendo utilizar tags criadas para direcionar a sua execução



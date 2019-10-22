# Teste (Trabalhe Conosco)

O objetivo é validar o formulário da página [Trabalhe Conosco](https://www.envolti.com.br/contato), discordâncias devem ser apontadas em um documento "Bug's" e deverá ser enviado junto com o fonte do projeto. 

Caso sejam criados casos de teste, os mesmos deverão ser armazenados em um documento "Casos de Teste" e deverá ser enviado juntamente com o fonte do projeto.

Deverá ser levado em consideração as diretrizes:

> Este formulário tem o objetivo de ser enviado currículos e dados de futuros candidatos, logo o mesmo deverá possuir um campo para que o candidato possa inserir o nome, este campo não poderá ser permitido ficar vazio e nem deverá possuir mais de 50 caracteres. Também será necessário e obrigatório o e-mail do candidato, este e-mail deverá ser válido e com um domínio válido. Um telefone poderá ser informado, além disso poderá ser internacional. Uma mensagem ou observação poderá ser descrita, não passando de 720 caracteres. Poderá ser anexado um documento .docx ou .pdf contendo o currículo do candidato, não podendo passar de 15Mb.

> Ao ter todos os dados necessários, um botão descrito "Enviar" deverá enviar a mensagem e uma mensagem de sucesso deverá ser exibida (Sucesso!), caso os dados não forem válidos então o campo com problema deverá ser focado (Caso ocorra erro interno, o botão deverá ficar bloqueado com a descrita "Erro.").

# Definição da Automação

Utilizar a ferramenta [WebDriver.IO](https://webdriver.io/) juntamente com [Mocha](https://mochajs.org/). 

Utilizar POM ([Page Object Model](https://medium.com/tech-tajawal/page-object-model-pom-design-pattern-f9588630800b)) junto com qualquer meio necessário para automatizar a rotina, afim de validar os dados acima de maneira sustentável atendendo a prática F.I.R.S.T.(Rápido, Isolado, Repetível, Auto-Verificável e Oportuno).

Fonte deverá ser enviado aqui neste projeto do GitHub.

# Definição dos Casos de Testes

Os casos de testes deverão ser feitos a sua maneira, porém utilizando a ferramenta Gherkin (Podendo ser o [Cucumber.io](https://cucumber.io/docs/gherkin/reference/)), porém deverão ser armazenados no Git.

É desejado que tenham casos de testes positivos e negativos, visando também que os mesmos sejam futuramente utilizados para automação.

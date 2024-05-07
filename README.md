# front-end
Atividade ( Expressões Regulares):

Este código JavaScript é executado quando a página da web é totalmente carregada, garantindo que todos os elementos HTML estejam disponíveis para serem manipulados pelo JavaScript.
Ele seleciona o primeiro elemento <form> na página e o armazena em uma variável chamada form. Em seguida, adiciona um ouvinte de evento ao formulário que é acionado quando o formulário é enviado.
Dentro da função do ouvinte de evento, os valores dos campos do formulário são obtidos e armazenados em variáveis separadas. Em seguida, são definidas expressões regulares para validar os campos do formulário e armazenadas em variáveis correspondentes.
As próximas três seções do código verificam se os valores dos campos do formulário correspondem às expressões regulares usando o método test(). Se algum dos campos não corresponder à expressão regular correspondente, uma mensagem de alerta é exibida e a submissão do formulário é impedida usando event.preventDefault().

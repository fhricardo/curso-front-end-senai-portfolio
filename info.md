# Formulários
São utilizado para envio de informações

## Atributos
*action*: informa qual arquivo será responsável pelo processamento do formulário - Apenas funciona em back-end
`exemplos`: envio de e-mail, cadastro de usuários etc.
*method*: Método de envio dos dados do formulário:
`get`: envia os dados pela URL.
Ex.: https://meusite.com.br/pagina.html?nome=Ana&sobrenome=Silva&senha=123456
? indica início dos parâmetros enviados
nome= é o nome do parâmetro
& indica que existe mais de um parâmetro
Ana é valor passado no parâmetro
*Pontos negativos do GET*: Expõe o conteúdo enviado
*Pontos positivos*: É possível compartilhar link já com parâmetros, funciona no front-end
`post`: envia os dados de forma encapsulada pelo navegador
não expõe os dados na URL, carrega as informações na requisição HTTP
*Pontos Negativos*: não pode ser compartilhado ou acessado diretamente pelo front-end
*Pontos Positivos*: Aumenta a segurança no envio de formulários para tratamento pelo back-end

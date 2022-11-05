# revis_not

# arrow_functions

São funções anonimas 
Exemplo
var sum =(a, b) => a + b;
console.log(sum(5, 5));

pode se usar retorno implicito 

pode se omitir tambem os  () dos argumentos se tiver apenas um argumento
Exemplo
var sum = a => a + b;

função construtora
function car(){
this.foo = 'bar';
console.log(new Car());

# APIS

Application Program Interface

apis são como a camada que esconde regras e possibilita a uma comunicação externa

facilita muito a integração

existem várias metedologias (ou arquiteturas)
como por exemplos: SOA, rest , uso por de SDK 

Http Methods

Get:
sempre obtém os dados
Post:
Cria um novo registro ou Recurso
Put:
Atualiza um registro existente 
Delete:
Remove um registro existente

Padrões 
Get:
/api/dev/user
Post:
/api/dev/user
Put:
/api/dev/user/{id}
delete:
/api/dev/user/{id}

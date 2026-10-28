# atividade02-pool-alexandre
Atividades
PHP com POO: Atividade 2
Vence hoje às 12:00

Vários envios permitidos
Instruções
Objetivo 



Completar o PHP de uma página que apresenta dois veículos disponíveis para aluguel. 



O HTML e o CSS já estão prontos. 

Você deverá implementar as classes e criar os objetos. 



Conceitos praticados 



Classes e objetos; 
propriedades e métodos; 
encapsulamento com private; 
método construtor __construct(); 
herança com extends; 
classe abstrata e método abstrato; 
polimorfismo. 
O que a página deve mostrar 



A página apresenta um carro e uma moto. Cada card mostra marca, modelo, ano, uma característica específica e o preço da diária. 



Carro: 4 portas e diária de R$ 150,00. 
Moto: 300 cilindradas e diária de R$ 70,00. 
Organização dos arquivos 



As classes devem ficar em arquivos PHP separados, dentro da pasta src.  

No final, sua estrutura de pastas e arquivos deve ficar assim: 



src/Veiculo.php: classe abstrata Veiculo. 
src/Carro.php: classe Carro. 
src/Moto.php: classe Moto. 
index.php: carregue os arquivos das classes com require_once e crie/exiba os objetos. 
Tarefas 



No arquivo src/Veiculo.php, crie a classe abstrata Veiculo. 
Declare como private as propriedades marca, modelo e ano. 
Crie um construtor que receba e armazene esses três valores. 
Crie getters para consultar as três propriedades. 
Declare na classe Veiculo o método abstrato calcularDiaria(), com retorno float. 
No arquivo src/Carro.php, crie a classe Carro, que herda de Veiculo. Ela deve ter a propriedade privada quantidadePortas, seu construtor e um getter. 
Implemente em Carro o método calcularDiaria(), retornando 150.00. 
No arquivo src/Moto.php, crie a classe Moto, que herda de Veiculo. Ela deve ter a propriedade privada cilindradas, seu construtor e um getter. 
Implemente em Moto o método calcularDiaria(), retornando 70.00. 
No index.php, carregue os arquivos das classes, crie um objeto de cada classe concreta e use os métodos para preencher os cartões da página. 
Atenção 



Não crie um objeto da classe abstrata Veiculo. 
Mantenha cada classe no arquivo indicado dentro de src; o index.php deve cuidar da criação dos objetos e da exibição HTML. 
Use parent::__construct() nos construtores das classes filhas para inicializar as propriedades herdadas. 
Não repita nas classes filhas as propriedades marca, modelo e ano. 
O método calcularDiaria() deve existir nas duas classes filhas, com o mesmo nome, mas pode retornar valores diferentes. 
Não é necessário usar banco de dados, formulários ou outros recursos de programação além dos já mencionados. 
Altere o HTML/CSS apenas se for necessário. 


Antes de começar a programar:

Crie um novo repositório público chamado atividade02-php-poo
Pegue os arquivos index.php e estilo.css aqui no Teams
Coloque estes arquivos no repositório atividade02-php-poo
Abra o repositório no VSCode
Execute o servidor neste repositório
Comece a programar
### Comandos gerais
- Console.log('texto') // Para exibir oq for escrito
- + - / * = // Para fazer operaçoes
- '  ,  ' // virgula utilizada para dar continuação
- && // Adicionar algo ao codigo anterior, ex. 'expressao' >=5 && 'expressao' <=7 para ser entre 5 e 7
- .toUpperCase() para ser em maiusculo
- const 'nomeConstante' = [ function () { codigo }, function () { codigo 2 } // criar array 
- 'nomeDaConstante[ 0 ](), 'nomeDaConstante[ 1 ]() // para puxar array
- 'texto ${} texto // ${} serve para colcoar constantes e variaveis no meio do texto
### Variaveis
- Let 'nome' = // Para criar uma variavel
- Const 'nome' = // Para criar uma constante
- Var 'nome' = // Criar variavel
### Condicionais
- If (condiçao){oq sera feito} // Para criar uma condicional
- If (!condiçao){oq sera feito} // Condicional com condiçao ao contrario
- '!' é utilizado para determinar o oposto/contrario de algo
- If (condiçao){oq sera feito} Else {oq sera feito caso a condiçao anterior nao se cumpra
- Else serte como continuaçao
- true
- false
- condicionais < > <= >= // '%' resto da divisão
- || Para adicionar 2 condicionais
### Matematica
- Math.pow('numero' , 'numero para elevar ou fazer raiz') 0.5 ou 1/2 para raiz quadrada, e 1/3 raiz cubica
- (Variavel ?? 'numero ou nome') // caso n seja expecificado a variavel sera utilizado o segundo parametro
- 'variavel' = 'parametro' // Para criar um parametro padrão
### Funções
- function 'nomeDaFunção'(parametro){codigo} // criar função
- fn // função, vai ser usado nos parametros
- var/const 'nomeVariavel' = function(){} // atribuir variavel a função/função anonima
- var/const 'nomeVariavel' = (parametro)=> {return a+b}/return a+b/ a+b // versões da função de seta
- function 'nomeDaFunçao'(){ function 'nomeDaFunção2'() { codigo }   'nomeDaFunção2()  } // Função dentro de função
- function 'nomeDaFunção'(parametro1){ function 'nomeDaFunção2'(parametro2) { codigo } return 'nomeDaFunção2' // Para retornar uma funçao usando um parametro para usar depois
- EX: const nome = 'nomeDaFunção'(parametro1 definido)    ,     console.log('nomeDaFunção2'(parametro2 definido) // Assim pode criar uma constante para um unico parametro
### Objetos
- const 'nome do objeto' = {dados do objeto} / Ex: const marcos = { nome: 'Marcos Silva de Oliveira', idade: 18 }
- marcos.nome / marcos.idade
- Da para colocar funções dentro de um objeto tipo: descrever // Para chamar ex: marcos.descrever
- this / this. // Serve para falar de algo dentro do contexto // Ex: this.nome
### Classes
- class 'nome da classe' {informacoes e funcoes} // serve para armazenar varios objetos com informaçoes iguais, tipo lista de pessoas
- cont 'nome constante ou coisa' = new 'nome da classe'(nada ou parametros)
- Da pra colocar um construtor // Ex: construtor(parametros) { this.nome = nome; this.idade = idade }
- Construtor serve para facilitar na criação futura de novos objetos 
- Da pra colcoar funçoes, n usar const nem function no inicio
### Listas/Array
- const 'nome da lista' = [objetos/strings da lista]
- console.log('nome da lista'[posiçao na lista]) // lista começa no 0
- 'nome da lista'.push('nome') // Para adicionar algo a lista
- 'nome da lista'[posição] = 'nome' // Para adicionar algoa  lista ma posição indicada
- 'nome da lista'.pop // pushar ultimo da lista
- 'nome da lista'.shift // pushar primeiro da lista
- 'nome da lista'.length // tamanho da lista
- for (let index = 0; index 'condicional < > =' 'nome da lista'.lenght; index++) {codigo} // onde variavel incia; condicional; oq vai acontecer dps do primeiro for
- i++ pode ser substituida por outras tipo i = i + 2
### Depuração
- Serve para testar o codigo
- Localizado na barra lateral
### Exportação/Importação
- modele.exports = {codigo} // Exportar algo
- const 'nome' = require('local do arquivo') // Importar algo
- 'nome'.'parte do codigo'() // usar parte do codigo importado
- {objetos importados} = require('local do arquivo') // Importar objetos
- objetos importados podem ser usados diretamente
- const entradas = [5.5];
let i = 0;

function gets() {
    const valor = entradas[i];
    i++;
    return valor;
}

function print(texto) {
    console.log(texto);
}

module.exports = { gets, print };




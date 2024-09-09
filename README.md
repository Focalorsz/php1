# php
 codigo aula php
//<?php
/*usado pra iniciar o codigo*/
//ECHO - Mostra nosso código no navegador
/*
TIPOS DE DADOS
-STRING [são caracteres que formam palavras e textos]
-INTEGER - [números inteiros - / +]
-FLOAT -[números decimais]
-BOOLEAN - [TRUE OR FALSE]
-ARRAY - [Matrizes]
-NULL - [Nulo]
SUPERGLOBAIS - [global]
OBJECT - [OBJETO]

SERVER
STRING
echo"funcionando corretamente";
*/
//INTEGER - INT
/*$num1 = 10;$num2 = 5;$total= $num1 + $num2;
echo $num1 . '
' .$num2;
echo '
' .$total;

~//FLOAT

$numm1 = 2.5;
$numm2 = 4;
$totall = $numm1 * $numm2;

echo '
' .$totall;

var_dump($totall);*/

//ARRAY-mais de um tipo de dado
//$carros = array("celta","lancer", "gol", "uno", 147);

//OBJECT
/*

class carro {
public $cor;
public $modelo;
public function __construct($cor,$modelo){
$this-> cor = $cor;
$this-> modelo = $modelo;
}
function mensagem(){
return "O carro é $this->cor e o modelo é $this->modelo";
}
}

$carro1 = new carro("Azul","celta");
$carro2 = new carro("Preto","lancer");
$carro3 = new carro("Vermelho","uno");
$carro4 = new carro("Branco","gol");

echo $carro1->mensagem();echo "
";
echo $carro2->mensagem();echo "
";
echo $carro3->mensagem();echo "
";
echo $carro4->mensagem();echo "
";*/

/*NULL - [NULO]
$x = "oi";
$x = null;
var_dump($x); */

//BOOLEAN - [VERDADEIRO OU FALSO]

/*$turma_inteligente = true;
$turma_burra = false;

var_dump($turma_inteligente);"
";
var_dump($turma_burra);*/

//STRING [funções]

/*strlen
$palavra = "oi tudo bem";
echo strlen("$palavra");*/

//echo str_word_count()
//echo str_word_count - conta as palavras
/*$palavra = "oi tudo bem";
echo str_word_count($palavra);*/

//echo strrev("Rafael");

//echo strpos - aponta a posição
/*echo strpos("Rafael Nicolas Freitas", "Nicolas");
$palavra = "oi tudo bem com você?";*/
//str_replace [vai substituir a palavra]
/*$frase = ("Olá Mundo");

echo str_replace("Mundo", "turma", $frase);*/
/*$data = ("19-08-2024"); //19/08/2024
$data_formatada = str_replace("-","/",$data);*/

/*echo $data_formatada;
echo "a data antiga é: $data
A data formatada é $data_formatada";*/

//MANIPULAÇÃO DE NUMEROS

/*$valor = 150 * 25;
$valor_convertido = (int) $valor;
//var_dump($valor_convertido);

$valor1 = 100;
$valor2 = 3.75;
$valor3 = "123a";
var_dump(is_numeric($valor3));*/

/*FUNÇÕES MATEMÁTICAS
$a = 10;
$b = 5;

$soma= $a + $b;
$subtração = $a - $b;
$multiplicação = $a * $b;
$divisão = $a / $b;
echo "A soma é: ". $soma ."
";
echo "A subtração é: $subtração
";
echo "A multiplicação é: $multiplicação
";
echo "A divisão é: $divisão
";*/

//echo pi();

/*$numeros = [1,10,-40,5000,200,20];
echo min($numeros)."
";
echo max($numeros);*/

//$numeros = 10.5;
//echo abs($numeros);//transforma numero em positivo

//echo sqrt(81); //raiz quadrada

//echo round($numeros);//arredondamento

//echo rand(0,1000);//aleatório ou randomico

//CONSTANTES

/*define("teste","oi");
//echo(teste);

function teste(){
echo teste;
}
teste();*/

/*define("carros",["fusca","gol","fiesta"]);
echo carros [2];*/

//Condicionais: IF,ELSE,ELSEIF

/*$hora = 19;

if ($hora < 12){
echo "Bom dia!";
}elseif($hora <18){
echo "Boa tarde!";
}else{
echo "Boa noite!";
}*/

//SWITCH
/*$cor = "azul";
switch($cor){
case "azul":
echo "A cor é azul";
break;

case "amarelo":
echo "A cor é amarelo";
break;

case "preto":
echo "A cor é preto";
break;

case "branco":
echo "A cor é branco";
break;
case "vermelho":
echo "A cor é vermelho";
break;
default;
echo "a cor ". $cor ." não existe";
}*/

//CONSTANTES

//WHILE
/*
$x = 0;

while  ($x <= 1000){
    echo "O número é: $x <br>";
    $x+=10;
}
*/

//DO WHILE
/*
$X = 1;

do{
    echo "O número é:$X <br>";
    $X++;
}while($X <=5);*/

//FOR
/*for ($x = 0; $x<=10000; $x+=100){
    echo "O qi do anderson é:-$x <br>";
}
*/

/*FOREACH

$cores= ["transparente", "branco", "albino","invisivel"];

foreach ($cores as $anderson){
    echo "O anderson é $anderson <br>";
}
*/
/*
//FUNÇÕES

function EscreverMensagem($nome){
    echo "¡¡ZA WARUDO!! $nome<br>";
}

EscreverMensagem("DIOOO");
EscreverMensagem("JOTAROO");
EscreverMensagem("JOSUKEE");
EscreverMensagem("KIRAAAAA");
EscreverMensagem("SODAA");

?>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Meu projeto PHP?</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="">
    </head>
    <body>
        <div id="teste">
            </div>
        body {
            background-color: #082767;
        }
    <?php 
    function soma ($valor1,$valor2){
        echo"o valor da soma é: ".
        $valor1 + $valor2,"<br>";

    }
    soma(7,4);
    function multiplica ($valor3,$valor4){
        echo"o valor da multiplicação é: ".
        $valor3 * $valor4,"<br>";
    }    
    multiplica(7,5);

    function divide ($valor5,$valor6){
        echo"o valor da divisão é: ".
        $valor5 / $valor6,"<br>";
    }
    divide(9,3);

    function subtração($valor7,$valor8,$valor9){
        echo"o valor da subtração é: ".
        $valor7-($valor8+$valor9),"<br>";
    }
    subtração(900,369,31);
    echo "<hr>";    
    
    function FazerCafe($tipo = "cappuccino"){
        return "Fazendo um café do tipo $tipo <br>";
    }  

    echo FazerCafe();
    echo FazerCafe("descafeinado");
    echo FazerCafe("chá");
    echo FazerCafe("latte");
    ?>
    </body>
</html>
*/
/*
$carros = ["buggati ChironSuper Sport 300+","cherry","lamborguini Aventador SVJ","corolla","mitsubishi Eclipse"];
$qtd = count($carros);
//echo $carros[0];

for ($i = 0;$i < $qtd; $i++){
    echo $carros[$i];
    echo "<br>";
}*/

//ARRAY ASSOCIATIVO

/*$idade = ["daniel"=>"30","Wayner"=>"20","pedro"=>"50"];

echo $idade["pedro"];*/

/*
$GLOBALS
$_SERVER
$_REQUEST
$_POST
$_GET
$_FILES
$_ENV
$_COOKIE
$_SESSION

*/
//variavel=$
//GLOBALS
$a = 10;
$b = 20;

function soma(){
    global $a,$b,$c;
   // $c = $a + $b;
}

soma();
echo"<br><hr>";
//$_SERVER
echo $_SERVER['PHP_SELF'];//apresenta o arquivo e pasta do usuário
echo"<br>";
echo $_SERVER['SERVER_NAME'];//apresenta o nome do servidor
echo"<br>";
echo $_SERVER['HTTP_HOST'];//NOME DO CABEÇALHO DA URL
echo"<br>";
echo $_SERVER['REMOTE_ADDR'];//MOSTRA O NUMERO DE IP
echo"<br>";
echo $_SERVER['HTTP_USER_AGENT'];//Mostra detalhes dos aplicativos utilizados
echo"<br>";
echo "<br><hr>";
?>


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Superglobais</title>
</head>
<body <?php if ($nome == "daniel"){echo "style='background:red; color:white'";}?>
>
    <h2> Olá <?php echo $_GET['nome']; 
    //?nome=pedro?></h2>

    <a href=""index.php?nome=daniel">Ir pra daniel</a>
    <a href=""index.php?nome=maria">Ir pra maria</a>
    <a href=""index.php?nome=lucas">Ir pra lucas</a>
</body>
</html>
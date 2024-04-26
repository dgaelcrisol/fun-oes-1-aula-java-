# fun-oes-1-aula-java-

function calculadoraIMC (peso , altura) {
'var imc = peso / (altura ** 2);
VM1275:2 Uncaught SyntaxError: Invalid or unexpected token
function calculadoraIMC (peso , altura) {
    var imc = peso / (altura ** 2); 
    return imc;
}
undefined
calculadoraIMC(70, 175)
0.002285714285714286

-----------------------------------------------------

calculadoraIMC(prompt("digite seu peso: "), pro
VM1576:1 Uncaught SyntaxError: missing ) after argument list
calculadoraIMC(prompt("digite seu peso: "), prompt("digite sua altura: "))

NaN
calculadoraIMC(prompt("digite seu peso: "), prompt("digite sua altura: "))
0.003111111111111111

------------------------------------------------------------

function dado() {
    var numeroAleatorio Math.r
VM1763:2 Uncaught SyntaxError: Unexpected identifier 'Math'
function dado() {
    var numeroAleatorio Math.floorMath.random() * 6) + 1;
VM1835:2 Uncaught SyntaxError: Unexpected identifier 'Math'
function dado() {
    var numeroAleatorio Math.floor(Math.random() * 6) + 1;
VM1843:2 Uncaught SyntaxError: Unexpected identifier 'Math'
function dado() {
    var numeroAleatorio Math.floor(Math.random() * 6) + 1;
VM1866:2 Uncaught SyntaxError: Unexpected identifier 'Math'
function dado() {
    var numeroAleatorio (Math.floor)(Math.random() * 6) + 1;
VM1873:2 Uncaught SyntaxError: Unexpected token '('
function dado() {
    var numeroAleatorio  = Math.floor(Math.random() * 6) + 1;
}
undefined
dado(prompt("pressione enter para jogar o dado:))
VM2021:1 Uncaught SyntaxError: Invalid or unexpected token
dado(prompt("pressione ENTER para jogar o dado: "))
undefined
dado(prompt("pressione ENTER para jogar o dado: "))
undefined
dado(prompt("pressione ENTER para jogar o dado: "))
undefined
FUNCTION
VM2071:1 Uncaught ReferenceError: FUNCTION is not defined
    at <anonymous>:1:1
(anonymous) @ VM2071:1
function expectativaDeVida(idade){
    var expectativaDeVidaEm Dias = (92 - idade) * 365;
VM2313:2 Uncaught SyntaxError: Unexpected identifier 'Dias'
function expectativaDeVida(idade){
    var expectativaDeVidaEmDias = (92 - idade) * 365;
    var expectativaDeVidaEmMeses = (92 - idade) * 12;
    var expectativaDeVidaEmSemanas = (92 - idade) * 52
    var expectativaDeVidaEmHoras = (92 - idade) * 8766
    return (" voce tem " + expectativaDeVidaEmDias + "dias , " + expectativaDeVidaEmHoras + "horas" + expectativaDeVidaEmMeses + "meses" + expectativaDeVidaEmSemanas + "semanas") }
undefined
expectativaDeVida(prompt("digite sua idade: "))
' voce tem 21170dias , 508428horas696meses3016semanas'

--------------------------------------------------------------------------

function calculadoraIMC (peso , altura) {
    var imc = peso / (altura ** 2); 
    if(imc <18.5) {
        return "voce está raquitico!";
    } else if  (imc >= 18.5 && imc <= 24.9) {
        return " voce está nop shape!";
    } else { 
        return "faça dieta e academia!";

        

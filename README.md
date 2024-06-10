const botaosoma = document.getElementById("btnsoma") 
botaosoma.onclick=function(){
    const numeroum = document.getElementById("numero1")
    const numerodois = document.getElementById("numero2")
    var soma = Number(numeroum.value) + Number(numerodois.value)
    console.log (soma)
    const resultado = document.getElementById("resultado")
    resultado.value = soma

}

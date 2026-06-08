# valentinna-agrinho  
                                                                                      AGRINHO
https://canva.link/59itvlppjpxcii0
                                                                                  
function iniciarSistema() {

const quantidade = document.getElementById("qtd").value;

const preco = document.getElementById("preco").value;

const total = quantidade * preco;

if (total > 1000) {

alert("Valor alto!");

}

document.getElementById("resultado").innerText = total;

}

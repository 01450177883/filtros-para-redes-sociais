//Voce  esta trabalhando numa empresa que desenvolveu um aplicativo que cria filtros para redes sociais. Neste aplicativo, para aplicar o filtro adequadamente, é necessário identificar se a foto foi tirada no modo retrato, paisagem, ou se a foro é quadrada.
//Voce ficou com a tarefa de desenvolver essa finalidade.

//Input Format
//Imprima na tela RETRATO caso altura seja maior que largura
//Imprima na tela PAISAGEM caso largura seja maior que altura
//Imprima na tela QUADRADA caso largura e altura sejam iguais

const altura = 10
const largura = 5

if(largura > altura) {
  console.log("PAISAGEM")
} else if(largura < altura) {
  console.log("RETRATO")
} else {
  console.log("QUADRADO")
}

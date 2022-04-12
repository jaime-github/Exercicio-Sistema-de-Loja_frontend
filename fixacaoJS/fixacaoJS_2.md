``` javascript
function calculaPrecoTotal(quantidade) {
  // Escreva seu código aqui
  let valorDuzia = 1.00
  let valorUnitario = 1.30
  
  if(quantidade < 12){
    return valorUnitario * quantidade
  }else {
    return valorDuzia * quantidade
  }
}
```

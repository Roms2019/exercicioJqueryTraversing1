# exercicioJqueryTraversing1
1. No arquivo page1.html, faça uma instrução jQuery que selecione todos elementos img da página que possuem alt e os imprima no log do console.


filter()
O método filter() permite que você especifique um critérios. Apenas elementos que satisfazem a condição serão retornados.

$(document).ready(function(){
    $("p").filter(".intro");
});

$(document).ready(function(){
    $("p.intro");
});

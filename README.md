# testeCombinacaoHtml-JS
Pequeno algoritmo usando tag "script" no html.


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Teste de combinação</title>
</head>
<body>

<h1>TESTE DE COMBINAÇÃO!</h1>
<script>

    var n1 = prompt('Digite seu nome: ');
    var n2 = prompt('Digite o nome do seu namorado: ')

    if(n1 == 'Camilla' && n2 == 'Mateus'){
        alert('Parabéns ' + n1 + ' e ' + n2 + ' Vocês formam um lindo casal! <3');
    }else{
        alert('Combinação imperfeita')
    }

</script>

</body>
</html>

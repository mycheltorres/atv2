<?php
// Função para calcular e imprimir as notas necessárias
function calcularNotas($valor) {
    $notas = [100, 50, 20, 10, 5, 2, 1];
    
    echo $valor . "\n";

    foreach ($notas as $nota) {
        $quantidade = intval($valor / $nota);
        echo $quantidade . " nota(s) de R$ " . number_format($nota, 2, ',', '.') . "\n";
        $valor %= $nota;
    }
}

// Leitura do valor inteiro
$valor = intval(readline());

// Chamada da função para calcular e imprimir as notas necessárias
calcularNotas($valor);
?>

$valor_A = $_POST['A']; 


$valor_B = $_POST['B']; 


$valor_C = $_POST['C']; 


$delta = ($valor_B**2)-(4*$valor_A*$valor_C); 


if ($delta < 0) { 

    echo "A equação não possui raizes reais <br><br>";

} elseif ($delta == 0 ) {

    echo "A equação possui apenas um resultado real ou possui dois resultados iguais <br><br>";

} elseif ($delta > 0) {

    echo " A equação possui dois resultados distintos reais <br><br>";
}

$valorX1 = (-$valor_B) + (sqrt($delta))/ (2*$valor_A); 


$valorX2 = (-$valor_B) - (sqrt($delta))/ (2*$valor_A);

echo "O resultado do x1 foi $valorX1 <br><br>"; 


echo "O resultado do x2 foi $valorX2 <br><br>";

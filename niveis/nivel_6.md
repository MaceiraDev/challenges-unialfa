# CÓDIGO DE CONNECTION.PHP
˜˜˜ 
<?php
$servidor = "localhost";
$usuario  = "root";
$senha    = "root";
$banco    = "ex6";

try {
    $pdo = new PDO("mysql:host={$servidor};dbname={$banco};port=8888;charset=utf8;", $usuario, $senha);
} catch (Exception $e) {
    echo "<p>Erro ao conectcar banco</p>";
    echo $e->getMessage();
}  
˜˜˜

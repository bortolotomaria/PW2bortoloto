EU NAO TENHO CERTEZA DE NENHUMA (DA 5 MUITO MENOS)

2-
<?php
function pegarCupomPorNome($id) {
    $sql = "SELECT * FROM usuario WHERE nome= $Nome";
    $resultado = mysqli_query(conn(), $sql);
    $Cupom = mysqli_fetch_assoc($resultado);
    return $Cupom;
}

3-
n sei
    
5- <?php
function adicionar($id)
{
    if (!isset($_SESSION["carrinho"])) {
        $_SESSION["carrinho"] = array();
    }

$id = $_POST["id"];
$nome = $_POST["nome"];
$descricao = $_POST["descricao"];
$preco = $_POST["preco"];
 alert(adicionarUsuario($id, $nome, $descricao, $preco));
    
redirecionar("carrinho");
}

?>

6-
<h2>Cupons</h2>

<table class="table">
    <thead>
        <tr>
            <th>Cupom</th>
            <th>Desconto</th>
            <th>DELETE</th>
    </tr>
        </tr>
    </thead>
    <?php foreach ($cupom as $cupom): ?>
    <tr>
        <td><?=$cupom['cupom']?></td>
        <td><?=$cupom['Desconto']?></td>
        <td><a href="./cupom/deletarCupomComID/<?=$cupom['id']?>" class="btn btn-danger">del</a></td>
    </tr>
    <?php endforeach; ?>
</table>

<a href="./cupom/adicionarNovoCupom" class="btn btn-primary">Adicionar novo cupom</a>

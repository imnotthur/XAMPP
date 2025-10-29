<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: aliceblue;
            text-align: center;
        }
        label {
            font-weight: bold;
        }
        input, select {
            margin-top: 5px;
            margin-bottom: 15px;
            padding: 8px;
            width: 300px;
            max-width: 100%;
        }
        input[type="submit"] {
            width: auto;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            padding: 10px 20px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    
    <?php
    if ($_SERVER["REQUEST_METHOD"] == "POST")
        $nome = $_POST["nome"];
        $telefone = $_POST["telefone"];
        $aparelho = $_POST["aparelho"];
        $atendimento = $_POST["data"];
        $descricao= $_POST["problema"];

        echo "<h3> Nova demanda 🛠️</h3>";
        echo "Nome do cliente: $nome <br>";
        echo "telefone: $telefone <br>";
        echo "aparelho: $aparelho <br>";
        echo "atendimento: $atendimento <br>";
        echo "descrição: $descricao <br><br>";
    ?>
    <form action="nomedoarquivo.php?pagina=controlealuno&&versa0=1.0" method="POST">
        <input type="submit" value="Voltar">
    </form>
    
</body>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
</html>

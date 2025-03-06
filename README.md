<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apresentação - Simone Zua</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            text-align: center;
            padding: 20px;
        }

        .info {
            background: #007BFF;
            color: white;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 20px;
            font-size: 18px;
        }

        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .tab {
            background: #007BFF;
            color: white;
            padding: 12px 20px;
            border-radius: 8px 8px 0 0;
            cursor: pointer;
            margin: 0 5px;
            transition: background 0.3s;
        }

        .tab:hover {
            background: #0056b3;
        }

        .tab-content {
            display: none;
            padding: 20px;
            background: white;
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.2);
            border-radius: 0 0 10px 10px;
        }

        .tab-content.active {
            display: block;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background: white;
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            overflow: hidden;
        }

        th, td {
            padding: 12px;
            border: 1px solid #ccc;
            text-align: center;
        }

        th {
            background: #007BFF;
            color: white;
        }

        tr:nth-child(even) {
            background: #f2f2f2;
        }

        a {
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
        }

        a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>

    <div class="info">
        <h2>Simone Zua</h2>
        <p>Instituto Médio Comercial de Luanda</p>
        <p>Turma: BNI | Sala: 18 | Nº 19 | Turno: Diurno</p>
        <p>Curso: Informática de Gestão</p>
    </div>

    <h1>Meus Trabalhos</h1>

    <div class="tabs">
        <div class="tab" onclick="showTab(1)">T.1</div>
        <div class="tab" onclick="showTab(2)">T.2</div>
        <div class="tab" onclick="showTab(3)">T.3</div>
        <div class="tab" onclick="showTab(4)">T.4</div>
    </div>

    <div id="tab1" class="tab-content active">
        <h2>Trabalho 1</h2>
        <table>
            <tr>
                <th>Nome</th>
                <th>Descrição</th>
                <th>Link</th>
            </tr>
            <tr>
                <td>Projeto 1</td>
                <td>: Personalizando Títulos e Parágrafos</td>
                <td><a href=https://simone-zua17.github.io/T.1/>Acessar</a></td><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício 1</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            text-align: center;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: blue;
            font-size: 30px;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 5px rgba(0, 0, 255, 0.3);
        }

        p {
            background-color: lightgray;
            color: black;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
            width: 50%;
            margin: 20px auto;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>ZUN´S FM STYLE</h1>
    <p>Este é um parágrafo formatado com CSS.</p>
</body>
</html>

                
            </tr>
        </table>
    </div>

    <div id="tab2" class="tab-content">
        <h2>Trabalho 2</h2>
        <table>
            <tr>
                <th>Nome</th>
                <th>Descrição</th>
                <th>Link</th>
            </tr>
            <tr>
                <td>Projeto 2</td>
                <td> Criando um Card Simples</td>
                <td><a href=https://simone-zua17.github.io/T.2/>Acessar</a></td>
            </tr>
        </table>
    </div>

    <div id="tab3" class="tab-content">
        <h2>Trabalho 3</h2>
        <table>
            <tr>
                <th>Nome</th>
                <th>Descrição</th>
                <th>Link</th>
            </tr>
            <tr>
                <td>Projeto 3</td>
                <td>: Criando uma Lista Personalizada</td>
                <td><a href=https://simone-zua17.github.io/T.3/>Acessar</a></td>
            </tr>
        </table>
    </div>

    <div id="tab4" class="tab-content">
        <h2>Trabalho 4</h2>
        <table>
            <tr>
                <th>Nome</th>
                <th>Descrição</th>
                <th>Link</th>
            </tr>
            <tr>
                <td>Projeto 4</td>
                <td>: Estilizando um Formulário</td>
                <td><a href=https://simone-zua17.github.io/T.4/>Acessar</a></td>
            </tr>
        </table>
    </div>

    <script>
        function showTab(tabIndex) {
            let contents = document.querySelectorAll(".tab-content");
            contents.forEach(content => content.classList.remove("active"));
            document.getElementById("tab" + tabIndex).classList.add("active");
        }
    </script>

</body>
</html>

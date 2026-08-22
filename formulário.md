<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulários</title>
    <style>
        label{display: block; margin-bottom: 10px;}
    </style>
</head>
<body>
    <form action="" method="GET">
        <label>Nome
            <input type="text" name="nome"">
        </label>
    
        <label>E-mail
            <input type="email" name="email">
        </label>

        <label>Idade
            <input type="number" name="idade" min="1" max="120">
        </label>

        <label>Data de Nascimento
            <input type="date" name="data de Nasc">
        </label>

        <label>Senha
            <input type="password" name="Senha">
        </label>

        <label>Arquivo
            <input type="file" name="Arquivo">
        </label>

        <label>Gênero</label>
        <label><input type="radio" name="genero" value="masculino">Masculino</label>
        <label><input type="radio" name="genero" value="feminino">Feminino</label>
        <label><input type="radio" name="genero" value="outros">Outros</label>

        <label>Esportes</label>
        <label><input type="checkbox" name="Esportes" value="futebol">Futebol</label>
        <label><input type="checkbox" name="Esportes" value="volei">Vôlei</label>
        <label><input type="checkbox" name="Esportes" value="natacao">Natação</label>
        <label><input type="checkbox" name="Esportes" value="ciclismo">Ciclismo</label>

        <label>Uf
            <select name="uf">
                <optgroup label="Centro-Oeste">
                    <option value="DF">DF</option>
                    <option value="GO">GO</option>
                </optgroup>
                <optgroup label="Nordedeste">
                    <option value="MA">MA</option>
                    <option value="PI">PI</option>
                </optgroup>
            </select>
        </label>

        <label>Mensagem
            <textarea name="Mensagem" rows="5" cols="40"></textarea>
        </label>

        <input type="hidden" name="variavel-oculta" value="qqcoisa">

        <button type="submit"></button>
    </form>
</body>
</html>

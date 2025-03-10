<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Sua logo</title>
</head>
<body>
    <header>
        <h1>Sua® logo</h1>
        <nav>
            <div class="nav-square">Principal</div>
            <div class="nav-square">Página 1</div>
            <div class="nav-square">Página 2</div>
            <div class="nav-square">Página 3</div>
            <div class="nav-square">Página 4</div>
            <div class="nav-square">Contato</div>
        </nav>
    </header>
    <section style="background-color: lightblue; padding: 20px;">
        <h2>FORMULÁRIO DE CONTATO</h2>
        <input type="text" placeholder="Nome" />
        <input type="email" placeholder="Email" />
        <input type="text" placeholder="Assunto" />
        <textarea placeholder="Mensagem" rows="4"></textarea>
        <button>Enviar sua mensagem</button>
        <h3>Endereço</h3>
        <p>Telefone</p>
        <img src="https://th.bing.com/th/id/OIP.js2UqAwM4jqK3iniCaxiJwHaHp?w=182&h=187&c=7&r=0&o=5&pid=1.7" alt="">
    </section>
    <div class="pepe">
    <section style="background-color: green; color: white; text-align: center; padding: 10px;">
        <p>TODOS OS DIREITOS RESERVADOS</p>
        <p>Endereço + Telefone</p>
    </section>
</div>
    </section>
</body>
</html>





body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f8f8f8;
    padding: 20px;
}

h1 {
    margin: 0;
}

nav {
    display: flex;
}

.nav-square {
    background-color: #007bff;
    color: white;
    padding: 10px 15px;
    margin-left: 10px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.nav-square:hover {
    background-color: #0056b3;
}

section {
    background-color: lightblue;
    padding: 20px;
}

input, textarea {
    display: block;
    width: 40%;
    margin: 10px 0;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    
}

h2, h3 {
    margin: 10px 0;
}

.green-section {
    background-color: green;
    color: white;
    text-align: center;
    padding: 10px;
}
.pepe {
    background-size: ;
}

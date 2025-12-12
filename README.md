<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Potiê • Link de Acesso</title>

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
    font-family: 'Poppins', sans-serif;
    background: #FFFBF8;
    color: #4A2F27;
    text-align: center;
    padding: 20px;
}

.container {
    max-width: 440px;
    margin: auto;
}

.logo {
    width: 200px;
    height: 200px;
    display: block;
    margin: 30px auto;
    animation: fadeIn 1s ease-out;
    border-radius: 50%;   /* redondo */
    object-fit: cover;    /* imagem centralizada */
}

p.subtitle {
    color: #6B4A3C;
    font-size: 17px;
    margin: 8px 0 25px 0;
}

.btn {
    display: block;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
    padding: 16px 0;
    margin: 12px 0;
    border-radius: 10px;
    transition: 0.35s;
    color: white;
}

.btn-ifood { background: #D92D20; }
.btn-ifood:hover { background: #B62218; }

.btn-whatsapp { background: #25D366; }
.btn-whatsapp:hover { background: #1DAF56; }

.btn-cardapio { background: #8A5A3B; }
.btn-cardapio:hover { background: #6E452E; }

.btn span {
    margin-right: 8px;
    font-size: 22px;
}

footer {
    margin-top: 28px;
    font-size: 14px;
    color: #7A5E50;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-15px); }
    to { opacity: 1; transform: translateY(0); }
}
</style>
</head>

<body>

<div class="container">

    <img class="logo" src="https://i.imgur.com/sxJWrx8.jpeg" alt="Logo Potiê">

    <p class="subtitle">Doçura artesanal direto no seu celular!</p>

    <a class="btn btn-ifood" href="https://www.ifood.com.br" target="_blank">
        <span></span> Nada de fome — pedir no iFood
    </a>

    <a class="btn btn-whatsapp" href="https://wa.me/5512999999999?text=Olá!%20Quero%20pedir%20um%20Potiê!" target="_blank">
        <span></span> Pedir direto no WhatsApp
    </a>

    <a class="btn btn-cardapio" href="https://seucardapio.com" target="_blank">
        <span></span> Quero revender Potiê
    </a>

    <footer>© 2025 Potiê • Todos os direitos reservados</footer>

</div>

</body>
</html>

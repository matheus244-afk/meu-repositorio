<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Repositório no GitHub</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="background-overlay"></div>

    <header>
        <h1>🚀 Bem-vindo ao meu Repositório!</h1>
        <p>Aqui você encontra meus principais projetos.</p>
    </header>

    <main class="container">
        <section class="repositorios fade-in">
            <div class="repositorio">
                <h2><a href="https://github.com/seu-usuario/nome-do-repo" target="_blank">📁 Projeto 1</a></h2>
                <p>Descrição do projeto 1.</p>
            </div>

            <div class="repositorio">
                <h2><a href="https://github.com/seu-usuario/nome-do-repo2" target="_blank">📁 Projeto 2</a></h2>
                <p>Descrição do projeto 2.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 - Desenvolvido por Seu Nome</p>
    </footer>
    * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Inter', sans-serif;
    background: url('https://images.unsplash.com/photo-1527689368864-3a821dbccc34?auto=format&fit=crop&w=1400&q=80') no-repeat center center fixed;
    background-size: cover;
    color: #fff;
    position: relative;
}

.background-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(13, 17, 23, 0.85);
    z-index: -1;
}

header {
    text-align: center;
    padding: 60px 20px 40px;
    background-color: rgba(0,0,0,0.3);
}

h1 {
    font-size: 2.8em;
    margin-bottom: 10px;
}

p {
    font-size: 1.2em;
    color: #c9d1d9;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}

.repositorios {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    margin-top: 40px;
}

.repositorio {
    background-color: rgba(255, 255, 255, 0.08);
    padding: 20px;
    border-radius: 10px;
    backdrop-filter: blur(6px);
    transition: transform 0.3s ease;
}

.repositorio:hover {
    transform: translateY(-5px);
}

a {
    color: #58a6ff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: rgba(255,255,255,0.1);
    margin-top: 60px;
    border-top: 1px solid #333;
}

.fade-in {
    animation: fadeIn 1s ease-in forwards;
    opacity: 0;
}

@keyframes fadeIn {
    to {
        opacity: 1;
    }
}
</body>
</html>

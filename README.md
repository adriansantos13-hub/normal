# normal
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu blog tech</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Cabeçalho do Blog -->
    <header class="blog-header">
        <h1>Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>

    <!-- Conteúdo Principal -->
    <main class="blog-container">
        
        <!-- Primeiro Post -->
        <article class="post">
            <div class="post-icon">📘</div>
            <div class="post-content">
                <h2>Meu primeiro post</h2>
                <p class="post-author">Por: adrian renan</p>
                <p class="post-text">Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.</p>
                <div class="post-actions">
                    <button class="action-btn">❤️ 59</button>
                    <button class="action-btn">💬 34</button>72 languages
Article
Talk

                </div>
            </div>
        </article>

        <!-- Segundo Post -->
        <article class="post">
            <div class="post-icon">📘</div>
            <div class="post-content">
                <h2>Meu segundo post</h2>
                <p class="post-author">Por:adrian renan </p>
                <p class="post-text">Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.</p>
                <div class="post-actions">
                    <button class="action-btn">❤️ +99</button>
                    <button class="action-btn">💬 40</button>
                </div>
            </div>
        </article>

    </main>

</body>
</html>
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #ffffff;
    color: #333333;
    line-height: 1.6;
}

/* Cabeçalho */
.blog-header {
    background-color: #0d3b66;
    color: #ffffff;
    text-align: center;
    padding: 40px 20px;
}

.blog-header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.blog-header p {
    font-size: 1.1rem;
    opacity: 0.9;
}

/* Container dos Posts */
.blog-container {
    max-width: 800px;
    margin: 40px auto;
    padding: 0 20px;
}

/* Estrutura do Post */
.post {
    display: flex;
    align-items: flex-start;
    margin-bottom: 40px;
}

.post-icon {
    font-size: 2.5rem;
    margin-right: 20px;
    padding-top: 5px;
}

.post-content h2 {
    color: #0d3b66;
    font-size: 1.8rem;
    margin-bottom: 5px;
}

.post-author {
    font-size: 0.9rem;
    color: #666666;
    font-style: italic;
    margin-bottom: 15px;
}

.post-text {
    font-size: 1rem;
    color: #444444;
    margin-bottom: 15px;
}

/* Botões de Reação */
.post-actions {
    display: flex;
    gap: 10px;
}

.action-btn {
    background-color: #f0f0f0;
    border: 1px solid #dddddd;
    padding: 5px 12px;
    border-radius: 4px;
    cursor: pointer;
    font-size: 0.9rem;
    display: flex;
    align-items: center;
    gap: 5px;
    transition: background 0.2s;
}

.action-btn:hover {
    background-color: #e5e5e5;
}

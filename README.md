## Iai, como vai? Sou o PH
**Desenvolvedor Front e Back-end**
🛠️ Linguagens
<p> <img src="https://skillicons.dev/icons?i=html,css,javascript,react,nodejs,cs,mysql,git,github,vscode,azure" /> </p>

Olá! Sou Pedro Henrique (PH)
Neste portfólio ire compartilhar projetos, estudos e experiências que demonstram minhas habilidades e meu crescimento na área de tecnologia.

📚 Tecnico em Desenvolvimento de Sistemas pela Instituiçaõ Etec Prof. Biagio Carmine Tundisi
🎓 Estudante de Análise e Desenvolvimento de istemas
💻 Desenvolvedor Front-end e Back-end
🎯 Focado em construir soluções úteis e escaláveis

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevPH</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1 class="typing">DevPH__</h1>
        <p class="subtitle">Front-End • Back-End • ADS</p>
    </div>

</body>
</html>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#0d1117;
    font-family:Consolas, monospace;
    overflow:hidden;
}

.container{
    text-align:center;
}

.typing{
    color:#00ff88;
    font-size:5rem;
    white-space:nowrap;
    overflow:hidden;
    border-right:4px solid #00ff88;
    width:0;
    animation:
        typing 3s steps(8) forwards,
        blink .8s infinite;
}

.subtitle{
    margin-top:20px;
    color:white;
    font-size:1.2rem;
    opacity:0;
    animation:fadeIn 1s ease forwards;
    animation-delay:3s;
}

@keyframes typing{
    from{
        width:0;
    }
    to{
        width:8ch;
    }
}

@keyframes blink{
    50%{
        border-color:transparent;
    }
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

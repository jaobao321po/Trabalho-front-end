index.html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocket League</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="banner">
        <h1>Bem-vindo ao Rocket League</h1>
    </header>

    <section class="topicos">
        <div class="topico">
            <h2>Gameplay</h2>
            <p>Jogue partidas intensas com carros no futebol!</p>
        </div>
        <div class="topico">
            <h2>Competição</h2>
            <p>Enfrente jogadores de todo o mundo em torneios!</p>
        </div>
        <div class="topico">
            <h2>Personalização</h2>
            <p>Personalize seus carros e conquiste vitórias!</p>
        </div>
    </section>

    <section class="introducao">
        <h2>Introdução ao Rocket League</h2>
        <p>Rocket League é um jogo eletrônico que combina futebol com carros em um ambiente futurista, criando uma experiência única e empolgante. Desenvolvido pela Psyonix, o título foi lançado em 2015 e rapidamente conquistou uma base de fãs global. O objetivo é simples: duas equipes de carros, cada uma composta por até quatro jogadores, competem para marcar gols em um grande estádio, usando seus veículos para impulsionar uma bola gigante até a meta adversária. O jogo se destaca pela mecânica de movimento acrobático, permitindo aos jogadores realizar manobras aéreas, saltos e até mesmo "flips" para controlar a bola com precisão.
         Além de ser um jogo divertido e dinâmico, Rocket League também se tornou um fenômeno nos eSports, com torneios internacionais que atraem grandes audiências e profissionais de alto nível. O título oferece uma jogabilidade acessível, mas desafiadora, permitindo aos novatos se divertir enquanto os veteranos buscam aperfeiçoar suas habilidades em jogos de alta velocidade e estratégias. Com atualizações constantes e uma comunidade ativa, Rocket League continua sendo uma das principais escolhas para quem busca ação e competitividade no mundo dos jogos online.</p>
    </section>

    <section class="video">
        <h2>Assista ao nosso vídeo</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/XzM5j4TxM7Y?si=te-uG6JZsG08UpIs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </section>
    <selection class="imagem">
        <h3>Veja esta imagem</h3>    
    </selection>
    <div class="imagem">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbhZTPP6e2MtAOqMqmLVKlQS9BdLQix-2ABA&s" alt="rocketleague" width="600px">
    </div>
</body>
</html>





style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #282828;
    color: white;
}

.banner {
    background-color: #1a1a1a;
    color: #ffcc00;
    text-align: center;
    padding: 20px 0;
}

.topicos {
    display: flex;
    justify-content: space-between;
    margin: 20px;
}

.topico {
    background-color: #333;
    border: 1px solid #444;
    padding: 20px;
    width: 30%;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

.topico h2 {
    font-size: 1.5rem;
    color: #ffcc00;
}

.introducao {
    background-color: #333;
    padding: 20px;
    margin: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}
.introducao h2{
    font-size: 1.5rem;
    color: #ffcc00;
}
.video {
    text-align: center;
    margin: 20px;
}

.video h2 {
    font-size: 1.5rem;
    color: #ffcc00;
}
.imagem{
    text-align: center;
    margin: 20px;
}
.imagem h3{
    font-size: 1.5rem;
    color: #ffcc00;
}

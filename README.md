<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghost Moon - Centro de Histórias</title>
    
    <style>
        /* CSS RESET & GERAIS */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #F5E1FF; /* Cor de fundo suave */
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Alinhamento ao topo para não sumir */
            min-height: 100vh;
            margin: 0;
            padding: 40px 10px;
        }

        /* CARD PRINCIPAL */
        .card-container {
            max-width: 600px;
            width: 100%;
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            padding: 30px;
            box-sizing: border-box;
            text-align: center;
        }

        /* PERFIL */
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 5px solid #8A2BE2; /* Roxo Blue Violet */
            object-fit: cover;
            margin-bottom: 15px;
        }

        h1 {
            color: #4B0082; /* Roxo escuro */
            margin-top: 0;
            font-size: 2em;
        }

        /* MÍDIAS SOCIAIS (BOTÕES DE TOPO) */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 25px;
        }

        .social-links a {
            display: inline-block;
            padding: 10px 15px;
            background-color: #9932CC;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.2s;
        }

        .social-links a:hover {
            background-color: #8A2BE2;
            transform: translateY(-2px);
        }

        /* ABAS (TABS) */
        .tabs {
            display: flex;
            margin-bottom: 20px;
            border-bottom: 2px solid #e0e0e0;
        }

        .tab-button {
            flex-grow: 1;
            padding: 15px 10px;
            background-color: #f0f0f5;
            border: none;
            border-bottom: 3px solid transparent;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: bold;
            color: #555;
            transition: all 0.3s;
        }

        .tab-button:hover:not(.active) {
            background-color: #e8e8f0;
            color: #4B0082;
        }

        .tab-button.active {
            background-color: #fff;
            color: #4B0082;
            border-bottom: 3px solid #4B0082;
        }

        /* CONTEÚDO DAS ABAS */
        .tab-content {
            text-align: left;
            padding: 10px 0;
        }

        .story-section {
            background-color: #f9f9f9;
            border: 1px solid #eee;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
        }

        .story-section h3 {
            color: #9932CC;
            margin-top: 0;
        }

        .story-link {
            display: block;
            margin: 5px 0;
            color: #007bff;
            text-decoration: none;
            font-weight: 500;
        }

        .story-link:hover {
            text-decoration: underline;
        }

        .status-badge {
            display: inline-block;
            padding: 3px 8px;
            border-radius: 5px;
            font-size: 0.8em;
            font-weight: bold;
            margin-left: 10px;
        }

        .status-badge.andamento {
            background-color: #ffcc00;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="card-container">
        
        <img src="https://i.pinimg.com/736x/3a/ee/52/3aee5242a829aef1326de28672c01cfa.jpg" 
             alt="Foto de Perfil" 
             class="profile-pic" /> 
        
        <h1>✩ Ghost Moon ✩</h1>
        <div class="bio-section">
    <p>
        ꒰՞. .՞꒱
        <br>
         Oioi Sou a Ghost Moon (ou Nanda)
        <br>
        tanto faz os pronomes 
        <br>
        escrevo algumas coisas desde 2020. 
        <br>
        ⋆˚࿔ espero que gostem do conteudo que eu escrevo 
        <br>
        e estou aberto a escrever sugestoes ⋆˚࿔
        <br>
        ps:só não crio um universó proprio por pura preguiça
    </p>
</div>
        
        <div class="social-links">
            <a href="https://www.instagram.com/xgh0stmoonx/" target="_blank">Instagram</a>
            <a href="https://www.tiktok.com/@xghost.moonx" target="_blank">TikTok</a>
            <a href="https://x.com/xgh0stmoonx" target="_blank">X</a>
        </div>
        
        <div class="tabs">
            <button class="tab-button active" onclick="mostrarAba('publicadas')">
                Histórias Publicadas
            </button>
            <button class="tab-button" onclick="mostrarAba('em-andamento')">
                Em Andamento
            </button>
        </div>

        <div id="publicadas" class="tab-content">
            <h2>⋆｡‧˚ʚHistorias Já concluidasɞ˚‧｡⋆</h2>
            <p>
                vocês podem ler tanto pelos links que estão disponiveis em cada historia,quanto por aqui e fazerb os comentarios, por sinal eu amo ler os comentarios hehe
            </p>

            <div class="story-section">
                <h3>O Would You Fall In Love With Me Again</h3>
                <p>Onde jorel se questiona se Leandro o amaria mesmo depois de tudo que ele fez,mesmo das coisas que ele não poderia desfazer.
<br>
<br>
Onde Leandro está disposto a se apaixonar de novo e de novo pelo outro garoto.</p>
                <a href="https://x.com/xgh0stmoonx/status/1874150128065585463?s=20" target="_blank" class="story-link">X
                    <br>
                    ⤷Leia aqui </a>
                <a href="https://www.wattpad.com/story/387100338-would-you-fall-in-love-with-me-again" target="_blank" class="story-link"> Wattpad 
                    <br>
                    ⤷Leia aqui </a>
            </div>

            <div class="story-section">
                <h3>O Guardião do Tempo</h3>
                <p>Ficção científica e romance intergaláctico.</p>
                <a href="URL_DA_SUA_HISTORIA_COMPLETA_2" target="_blank" class="story-link">Leia Agora!</a>
            </div>
        </div>

        <div id="em-andamento" class="tab-content" style="display: none;">
            <h2>⋆｡‧˚ʚHistórias Em Andamentoɞ˚‧｡⋆</h2>
            <p>
                ⊹₊ ˚‧︵‿₊୨aqui tem plots que estão em andamentos e 
                <br>
                que ainda seram escritos୧₊‿︵‧ ˚ ₊⊹
            </p>

            <div class="story-section">
                <h3>Iris <span class="status-badge andamento"></span></h3>
                Onde Felix não sabe como seu mundo se tornou tão apático e cansativo
                <p><br>
                   
                    Onde Hyunjin,um voluntário na clínica psiquiátrica,acaba por notar os olhinhos castanhos que demonstrar apatía e um cansaço extremo
.</p>
                <a href="https://x.com/xgh0stmoonx/status/1968991787130761563?s=20" target="_blank" class="story-link">X </a>
            </div>
        </div>
    </div>

    <script>
        function mostrarAba(idAba) {
            // 1. Oculta todos os conteúdos das abas
            document.getElementById('publicadas').style.display = 'none';
            document.getElementById('em-andamento').style.display = 'none';

            // 2. Remove o destaque (classe 'active') de todos os botões
            document.querySelectorAll('.tab-button').forEach(btn => {
                btn.classList.remove('active');
            });

            // 3. Mostra o conteúdo da aba clicada
            document.getElementById(idAba).style.display = 'block';

            // 4. Adiciona o destaque (classe 'active') ao botão clicado
            // Esta linha encontra o botão que foi clicado com base no seu atributo 'onclick'
            document.querySelector(`.tab-button[onclick*="${idAba}"]`).classList.add('active');
        }

        // Garante que a primeira aba ('publicadas') esteja visível quando a página carregar
        window.onload = function() {
            mostrarAba('publicadas');
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assents/css/style.css">
    <title>Meu Portfolio - Kaio</title>
    <link rel="shortcut icon" href="favicon.png" type="image/x-icon">
</head>
<body onload="checkCookie()">

    
    <header>
        <div class="logo">
            <img src="assents/img/PORFOLIO DO KAIO.png" alt="...Error">
        </div>
        <input type="checkbox" id="nav_check" hidden>
        <nav>
           <div class="logo">
                <img src="assents/img/PORFOLIO DO KAIO.png" alt="...Error">
            </div>
            <ul>
                <li>
                    <a href="index.html" class="active">Home</a>
                </li>
                <li>
                    <a href="#quemsou">Quem Sou</a>
                </li>
                <li>
                    <a href="#meus-rpojetos">Meus Projetos</a>
                </li>
                <li>
                    <a href="#contato">Contato</a>
                </li>
            </ul>
        </nav>

        <label for="nav_check" class="hamburger">
            <div></div>
            <div></div>
            <div></div>
        </label>
    </header>

    
    
    <div class="container-cabecario">
        <div class="informacoes">
            <h1 id="quemsou">Olá, me chamo <span class="titulo-principal">Kaio</span></h1>
            <p>Sejam bem-vindos, me chamo Kaio, sou designer gráfico há mais de 3 anos. Durante esses 3 anos já fiz diversos trabalhos, desde logos até banners, já trabalhei em gráfica e realizei diversos trabalhos em Freelancer. Recentemente tenho me interessado por programação Web, fiz alguns projetos de programação visual e no ano de 2022 comecei a ter interesse na área de programação, com o apoio de professores e dos meus pais, estou conseguindo e me aperfeiçoando cada vez mais nos códigos.</p>
        </div>
        
    </div>

    <div class="quadrado"></div>


    <div class="meusprojetos">
        <h1>Meus Projetos</h1>
    </div>
    
        <div class="meus-rpojetos" id="meus-rpojetos">
            <img src="assents/img/EA-Sportes-Neymar.png" alt="...Error">
            <img src="assents/img/Fitness.png" alt="...Error">
            <img src="assents/img/Flyer-Apple-Watch-6.png" alt="...Error">
            <img src="assents/img/MI 11 LITE.jpg" alt="...Error">
            <img src="assents/img/Prancheta 1.png" alt="...Error">
            <img src="assents/img/Sem-Título-1.png" alt="...Error">
            <img src="assents/img/Sem-Título-2.png" alt="...Error">
            <img src="assents/img/águia-flyer.png" alt="...Error">
        </div>
    </div>

    <div class="form" id="contato">
        <form action="#">
            <h1>Contato</h1>
            <input type="text" placeholder="Seu nome:" required>
            <input type="email" placeholder="Digite seu e-mail:" required>
            <br>
            <textarea name="text-area" id="" cols="30" rows="5" style="resize: none;" required></textarea>
            <br>
            <button>Enviar ></button>
            <br>
        </form>
        <img src="assents/img/5799685.png" alt="...Error">
      </div>

      <a href="https://wa.me/5544997249833?text=?" style="position:fixed;width:60px;height:60px;bottom:40px;right:40px;background-color:#25d366;color:#FFF;border-radius:50px;text-align:center;font-size:30px;box-shadow: 1px 1px 2px #888;
                    z-index:1000;" target="_blank">
                    <i style="margin-top:16px" class="fa fa-whatsapp"></i>
                </a>
    

                <footer>
                    <div class="aplicativo">
                        <ul>
                            <h3>Aplicativo</h3>
                            <li><a href="index.html">Home</a></li>
                            <li><a href="#quemsou">Quem Sou</a></li>
                            <li><a href="#meus-rpojetos">Meus Projetos</a></li>
                        </ul>
            
                    </div>
                    <div class="social">
                        <h3>Social</h3>
                        <li><a href="https://instagram.com/eiikaiosilva">Instagram</a></li>
                        <li><a href="https://github.com/KaioYt">GitHub</a></li>
                        <li><a href="politica-privacidade.html">Política - Privacidade</a></li>
                    </div>
                    <div class="contato">
                        <a href="#contato">Contato</a>
                    </div>
                </footer>
                

    <script src="assents/js/script.js"></script>
</body>
</html>

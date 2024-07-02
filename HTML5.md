<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- FIM GOOGLE FONTES -->
    <!-- BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <!-- FIM BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="style.css">

    <script src="menu.js" defer></script>

    <title>Agência GAB</title>
</head>
<body>
    
    <header>
        <div class="interface">
            <div class="logo">
                <a href="#">
                    <img src="Agencia.png" alt="Logo da Agência BRN">
                </a>
            </div><!--logo-->

            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#portfolio">Projetos</a></li>
                </ul>
            </nav>

            <div class="btn-contato">
                <a href="https://www.linkedin.com/in/gabriel-moura-a8bab520a/" target="_blank">
                    <button>Contato</button>
                </a>
            </div><!--btn-contato-->

            <div class="btn-abrir-menu" id="btn-menu">
                <i class="bi bi-list"></i>
            </div>

            <div class="menu-mobile" id="menu-mobile">
                <div class="btn-fechar">
                    <i class="bi bi-x-lg"></i>
                </div>

                <nav>
                    <ul>
                        <li><a href="#">Início</a></li> 
                        <li><a href="#sobre">Sobre</a></li>
                        <li><a href="#portfolio">Projetos</a></li>
                    </ul>
                </nav>

            </div><!--menu-mobile-->
            <div class="overlay-menu" id="overlay-menu"></div>
        </div><!--interface-->
    </header>

    <main>
        <section class="topo-do-site">
            <div class="interface">
                <div class="flex">
                    <div class="txt-topo-site">
                        <h1>TRANSFORMANDO IDEIAS EM REALIDADE DIGITAL<span>.</span></h1>
                        <p>Criatividade e inovação andam lado a lado. Com uma combinação única de design impactante, funcionalidade intuitiva e otimização para resultados, estou pronto(a) para criar a presença online dos seus sonhos.</p>

                        <div class="btn-contato">
                            <a href="https://www.linkedin.com/in/gabriel-moura-a8bab520a/" target="_blank">
                                <button>Entre em contato</button>
                            </a>
                        </div>
                    </div><!--txt-topo-site-->

                    <div class="img-topo-site">
                        <img src="eu redondo.png" alt="">
                    </div><!--img-topo-site-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--topo-do-site-->

        <section class="sobre" id="sobre">
            <div class="interface">
                <div class="flex">
                    <div class="img-sobre">
                        <img src="foto.png" alt="">
                    </div><!--img-sobre-->

                    <div class="txt-sobre">
                        <h2>MUITO PRAZER, <span>SOU Gabriel Moura Veiga.</span></h2>
                        <p>Sou estudante de Análise e Desenvolvimento de Sistemas na Universidade Cruzeiro do Sul, atualmente no 2º semestre. Durante minha trajetória acadêmica e profissional, tive a oportunidade de estagiar como Analista de Rede na FLERC por 6 meses, onde adquiri experiência prática e desenvolvi habilidades valiosas na área de TI.</p>
                        <p>Considero-me ágil e consistente na aprendizagem de novas habilidades e na adaptação a qualquer tipo de mudança. Estou sempre pronto para enfrentar novos desafios!</p>
                        <div class="btn-social">
                            <a href="https://www.instagram.com/gaveigaa/" target="_blank"><button><i class="bi bi-instagram"></i></button></a>
                            <a href="https://www.linkedin.com/in/gabriel-moura-a8bab520a/" target="_blank"><button><i class="bi bi-linkedin"></i></button></a>
                        </div><!--btn-social-->
                    </div><!--txt-sobre-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--sobre-->

        <section class="portfolio" id="portfolio">
            <div class="interface">
                <h2 class="titulo">MEU <span>PORTFÓLIO.</span></h2>
                <div class="flex">
                    <div class="img-port">
                        <a href="https://github.com/mourauz/Calculadora" target="_blank">
                            <div class="overlay">Projeto 1</div>
                        </a>
                    </div>
                    <!--<div class="img-port" style="background-image: url(images/imagem.jpg);">
                        <div class="overlay">Projeto 2</div>
                    </div>
                    <div class="img-port" style="background-image: url(images/imagem.jpg);">
                        <div class="overlay">Projeto 3</div>
                    </div>
                -->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--portfolio-->

        <section class="formulario">
            <div class="interface">
                <h2 class="titulo">FALAR <span>COMIGO.</span></h2>

                <form action="">
                    <input type="text" name="" id="" placeholder="Seu nome completo:" required>
                    <input type="email" name="" id="" placeholder="Seu e-mail:" required>
                    <input type="tel" name="" id="" placeholder="Seu celular:">
                    <textarea name="" id="" placeholder="Sua mensagem" required></textarea>
                    <div class="btn-enviar"><input type="submit" value="ENVIAR"></div>
                </form>
            </div><!--interface-->
        </section><!--formulario-->

    </main>

    <footer>
        <div class="interface">
            <div class="line-footer">
                <div class="flex">
                    <div class="logo-footer">
                        <img src="Agencia.png" alt="Logotipo Agência BRN">
                    </div><!--logo-footer-->
                    <div class="btn-social">
                        <a href="https://www.instagram.com/gaveigaa/"><button><i class="bi bi-instagram"></i></button></a>
                        <a href="https://www.linkedin.com/in/gabriel-moura-a8bab520a/"><button><i class="bi bi-linkedin"></i></button></a>
                    </div><!--btn-social-->
                </div>
            </div><!--line-footer-->

            <div class="line-footer borda">
                <p><i class="bi bi-envelope-fill"></i> <a href="#">gmveiga10@gmail.com</a></p>
            </div><!--line-footer-->
        </div><!--interface-->
    </footer>

</body>
</html>
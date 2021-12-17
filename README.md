# teste
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amigo Virtual</title>
    <!-- Fonte-->
    <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700&display=swap" rel="stylesheet">
  <!-- Estilos -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link rel="stylesheet" href="css/styles.css">
  <!-- Scripts (jQuery não pode ser o slim que vem do Boostrap) -->
  <script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="  crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
    <!-- Fontawesome-->
    <script src="https://kit.fontawesome.com/ccc12782e8.js" crossorigin="anonymous"></script>
    <!-- Progress Bar -->
    <script src="js/progressbar.min.js"></script>
    <!--Parallax-->
    <script src="https://cdn.jsdelivr.net/parallax.js/1.4.2/parallax.min.js"></script>

<body>
    <header>
        <div class="container" id="nav-container">
        <nav class="navbar navbar-expand-lg fixed-top">
            <a href="#" class="navbar-brand">
                <img id ="logo" src="img/cacto.png" alt="Portifolio Friend">Secret Friend</a>
            <button class="navbar-toggler" type="button" data-toggler="collapse" data-target="#navbar-links"  area-controls="navbar-links" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span></button>

            <div class="collapse navbar-collapse justify-content-end" id="navbar-links">
                <div class="navbar-nav">
                    <a class="nav-item nav-link" id="home-menu">Home</a>
                    <a class="nav-item nav-link" id="about-menu">Paraíbe-se</a>
                    <a class="nav-item nav-link" id="services-menu">Amiga Oculta</a>
                    <a class="nav-item nav-link" id="team-menu">Fotos</a>
                    <a class="nav-item nav-link" id="portfolio-menu">Sobre Ela</a>
                    <a class="nav-item nav-link" id="contact-menu">Contato</a>
                </div>
            </div>
        </nav>
        </div>
    </header>

    <main>
        <div class="container-fluid">
            <div id="mainSlider" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#mainSlider" data-slide-to="0" class="active "></li>
                    <li data-target="#mainSlider" data-slide-to="1"></li>
                    <li data-target="#mainSlider" data-slide-to="2"></li>
                </ol>

            <!-- slide 1-->
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="img/jampa9.jpg" class="d-block w-100" alt = "Projetos e-commerce">
                            <div class="carousel-caption  d-md-block">

                                <h2>Rio Sanhauá</h2>
                                <p>Banha os municípios de Bayeux e Jampa</p>
                             <!--   <a href="#" class="main-btn">Ver Portifólio</a>-->
                            </div>
                        </div>
             <!-- slide 2-->
        
            <div class="carousel-item ">
                <img src="img/jampa6.jpg" class="d-block w-100" alt = "Engenharia de Software">
                <div class="carousel-caption  d-md-block">

                    <h2>Praia de Tambaú, João Pessoa-PB</h2>
                    <p>Tambaú é nome de origem Tupi que quer dizer "Rio das Conchas" </p>
                    
                </div>
            </div>
    
            <!-- slide 3 -->
           
            <div class="carousel-item ">
            <img src="img/jampa4.jpg" class="d-block w-100" alt = "Manutenção em Software">
            <div class="carousel-caption d-md-block">

                <h2>Caminhos do Frio</h2>
                <p>Evento em Areia, Brejo da Paraíba </p>
              <!-- <a href="#" class="main-btn">Entre em contato</a>--> 
            </div>
          
             </div>
         </div>
      <!-- Setas -->
      <a href="#mainSlider" class="carousel-control-prev" role="button" data-slide="prev"> 
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>

    <a href="#mainSlider" class="carousel-control-next" role="button" data-slide="next"> 
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
        </div>
        <!-- Sobre a empresa   -->
        <div id="about-area">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h3 class="main-title">Curiosidades da Paraíba</h3>
                </div>
                <div class="col-md-6">
                    <img class="img-fluid" src= "img/jampa5.jpg" alt="Agencia HDC">
                </div>

                <div class="col-md-6">
                    <h3 class="about-title"> Intrepida ab origine ('Heróicos desde a origem')</h3>
                    <p>Paraíba, um estado no nordeste do Brasil, é conhecido pela linha da costa tropical e pela arquitetura colonial portuguesa. A capital, João Pessoa, possui praias como a Manaíra e Tambaú, além de locais de mergulho repletos de corais ao largo da costa. João Pessoa é uma cidade costeira próxima da foz do rio Paraíba, no leste do Brasil.</p>
                    <ul id="about-list">
                        <li><i class="fas fa-check"></i>João Pessoa é a cidade que amanhece primeiro no Brasil. A Ponta de Seixas, localizada no extremo oriente da América do Sul, é a primeira a receber a luz do sol.</li>
                        <li><i class="fas fa-check"></i> Atrás apenas de Paris, a cidade de João Pessoa é considerada a segunda capital mais verde do globo, um índice de quase 55 árvores por habitante. </li>
                        <li><i class="fas fa-check"></i> A maior comemoração de São João (em junho, com duração de 30 dias) acontece na cidade de Campina Grande, distante 130 km da capital.</li>
                        <li><i class="fas fa-check"></i> Fundada em 1585, João Pessoa é a terceira capital mais antiga de todo o Brasil.</li>
                        <li><i class="fas fa-check"></i>Sim, na Paraíba você também pode visitar um importante sítio paleontológico, com pegadas de mais de 80 espécies de dinossauros. Ele fica na cidade de Sousa, no sertão, a cerca de 430 km da capital.</li>
                        <li><i class ="fas fa-check"></i>Dicionário local, Quer um exemplo? Depois de dar um frexeiro, que tal comer um sanduíche montado em um aguado? Não se avexe  e curta com calma todas as belezas da Paraíba!é difícil alguém ficar borocoxô . </li>

                    </ul>
                </div>
            </div>
        </div>
    </div>

    <!--Serviços da empresa -->
    <div id="services-area">
    <div class="container">
     <div class="row">
        <div class="col-12">
    <h3 class="main-title">Jess</h3>
        </div>
        <div class="col-md-4 service-box">
            <i class="fas fa-mobile-alt"> </i>
            <h4>Antenada</h4>
            <p>Sempre atrás de uma boa fofoca na internet</p>
        </div>

        <div class="col-md-4 service-box">
            <i class="fas fa-grin-tongue-wink"></i>
            <h4>Muito Engraçada!</h4>
            <p>Melhores aúdios do twitter.</p>
        </div>

        <div class="col-md-4 service-box">
            <i class="fas fa-paint-brush"> </i>
            <h4>Criativa</h4>
            <p>Alguns dizem que é fanfiqueira, fica no ar?</p>
        </div>

        <div class="col-md-4 service-box">
            <i class="fa fa-book"></i> 
             <h4>Estudiosa?</h4>
            <p>Parece pelo menos </p>
        </div>

        <div class="col-md-4 service-box">
            <i class="fas fa-hands-helping"> </i>
            <h4>Excelente Amiga</h4>
            <p>"Amizade é um amor que nunca morre", M.Quintana</p>
        </div>

        <div class="col-md-4 service-box">
            <i class="fas fa-music"></i>          
                 <h4>Cantora sim ou claro?</h4>
            <p>Na horas vagas principalmente</p>
        </div>
    </div>
    </div>
 </div>
<!-- CARDS DA EMPRESA-->
  <div id="team-area">   
      <div class="container">
        <div class="row"> 
            <div class="col-12">
            <h3 class="main-title">Fotos da Fanfiqueira</h3>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="img/profile1.jpeg"  class="img-class-top" alt="Imagem de Perfil 1">
                    <div class="card-body">
                        <h5 class="class-title">Pessoa 1</h5>
                        <p class="card-text"> From João Pessoa</p>
                    </div>
                </div>
            </div>

             <div class="col-md-3">
            <div class="card">
                    <img src="img/profile2.jpeg"  class="img-class-top" alt="Imagem de Perfil 2">
                    <div class="card-body">
                        <h5 class="class-title">Pessoa 2</h5>
                        <p class="card-text">Estudante de Direito</p>
                    </div>
             </div>
         </div>


         <div class="col-md-3">
           <div class="card">
                        <img src="img/profile3.jpg"  class="img-class-top" alt="Imagem de Perfil 3">
                        <div class="card-body">
                            <h5 class="class-title">Pessoa 3</h5>
                            <p class="card-text">Ela também</p>
                        </div>
            </div>
        </div>

        <div class="col-md-3">
          <div class="card">
                            <img src="img/profile4.jpg"  class="img-class-top" alt="Imagem de Perfil 4">
                            <div class="card-body">
                                <h5 class="class-title">Pessoa 4</h5>
                                <p class="card-text">Modelo</p>
                            </div>
                </div>

            </div> 

            </div>
        </div>
      </div>
      <!-- Trabalhe conosco -->
      <div id="apply-area">
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-6 apply-box" id="company-img"></div>
            <div class="col-md-6 apply-box" id="pattern-img">
              <h4>Notas sobre ela</h4>
              <p>Ela tem necessidade de movimento, o mundo é grande e desde cedo ela aprendeu que a vida é curta.
             <p> Por isso a urgência!!</p>  
             <p> Por isso ela não demora onde há dor.</p>
             <p> Feito girassol ela vai em direção a luz, buscando o calor da vida.</p>
            
         

               
              <a href="#" class="main-btn" id="apply-btn">Home</a>
            </div>
          </div>
        </div>
      </div>
      <!--Portifólio-->
      <div id="portfolio-area">
      <div class="container">
        <div class="row">
            <div class="col-md-12">
                <h3 class="main-title"> Conheça mais sobre ela</h3>
                </div>
                <div class="col-md-12" id="filter-btn-box">
                    <button class="main-btn filter-btn active" id="all-btn">Tudo</button>
                    <button class="main-btn filter-btn " id="dev-btn">Sariette Stan</button>
                    <button class="main-btn filter-btn " id="dsg-btn">Quase Advogada</button>
                    <button class="main-btn filter-btn" id ="seo-btn">Caprichete Enrustida</button>
                </div>

                <div class="col-md-4 project-box dev">
                    <img src="img/proj1.jpg" class="img-fluid" alt="Projeto 1">
                </div>

                <div class="col-md-4 project-box dsg">
                    <img src="img/proj2.jpg" class="img-fluid" alt="Projeto 2">

                </div>

                <div class="col-md-4 project-box seo">
                   <img src="img/proj3.jpg" class="img-fluid" alt="Projeto 3">
                </div>
                
                <div class="col-md-4 project-box dev">
                    <img src="img/proj4.jpg" class="img-fluid" alt="Projeto 4">
                </div>

                <div class="col-md-4 project-box dsg">
                    <img src="img/proj5.jpg" class="img-fluid" alt="Projeto 5">
                </div>

                <div class="col-md-4 project-box seo">
                    <img src="img/proj6.jpeg" class="img-fluid" alt="Projeto 6">
                </div>
                
            </div>
        </div>
    </div>
      </div>
</div>

    </main>

    <!-- Rodapé -->
    <footer>
        <div id="contact-area">
          <div class="container">
              <div class="row">
                <div class="col-md-12">
                  <h3 class="main-title">Entre em contato </h3>
                </div>
                <div class="col-md-4 contact-box">
                  <i class="fas fa-phone"></i>
                  <p><span class="contact-tile">Ligue para:</span> (83)99999-9999</p>
                  <p><span class="contact-tile">Horários:</span> 8:00 - 19:00</p>
                </div>
                <div class="col-md-4 contact-box">
                  <i class="fas fa-envelope"></i>
                  <p><span class="contact-tile">Envie um email: </span>jthalita20@gmail.com </p>
                </div>
                <div class="col-md-4 contact-box">
                  <i class="fa fa-twitter" aria-hidden="true"></i> 
                  <p><span class="contact-tile">Venha fanficar com ela: </span>@JssicaThalita7</p>
                </div>
                <div class="col-md-6" id="msg-box">
                  <p>Deixe a sua mensagem:</p>
                </div>  
                <div class="col-md-6" id="contact-form">
                  <form action="">
                    <input type="text" class="form-control" placeholder="E-mail" name="email">
                    <input type="text" class="form-control" placeholder="Assunto" name="subject">
                    <textarea class="form-control" rows="3" placeholder="Sua mensagem..." name="message"></textarea>
                    <input type="submit" class="main-btn">
                  </form>
                </div>
              </div>
          </div>
        </div>
        <div id="copy-area">
          <div class="container">
            <div class="row">
                <div class="col-md-12">
                  <p>Desenvolvido por <a href="https://github.com/raquelsimoesrogerio/teste/edit/master/amigo_oculto.html" target="_blank">Raquel Simões</a> &copy; 2021</p>
                </div>
            </div>
          </div>
        </div>
      </footer>
    <!--Scripts do projeto-->
    <script src="js/scripts.js"></script>
</body>
</html>

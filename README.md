# netflix-clone
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/main.css">

    <!--responsividade-->
    <link rel="stylesheet" href="style/responsive.css">

<!--owl css-->
    <link rel="stylesheet" href="style/owl/owl.carousel.min.css">
    <link rel="stylesheet" href="style/owl/owl.theme.default.min.css">

    <title>NETFLIX CLONE</title>
</head>
<body>
    <HEader>
        <dIv class="container">
         <h2 class="logo">NETFLIX</h2>
         <NAv>
             <a href="#">INICIO</a>
             <a href="#">SÉRIES</a>
             <a href="#">FILMES</a>
             <a href="#">DOCUMENTARIOS</a>
         </NAv>
        </DIv>
    </HEader>

    <main>
        <div. class="filme-principal">
            <div class="container">
                <h3 class="TITULO">HOUSE OF CARDS</h3>
                <P class="DESCRICAO">nada pode impedir o politico sem escrúpulos Frank Underwood de conquistar whashington, assista agora a nova temporada de House of Cards que esta imperdivel</P>
            <div class="botoes">
            <button role="button" class="botao">
                <i class="fa-solid fa-play"></i>
             </button>
                ASSISTIR AGORA
            </button>
            <button role="button" class="botao">
                <i class="fa-solid fa-circle-info"></i>
                MAIS INFORMACOES
            </button>
        </div.>
    </main>

    <div class="carrossel-filmes"> 
       <div class="owl-carousel owl-theme">
           <div class="item">
               <img class="box-filme" src="img/mini1.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini2.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini3.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini4.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini5.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini6.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini7.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini8.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini9.jpg" alt="">
           </div>
           <div class="item">
               <img class="box-filme" src="img/mini10.jpg" alt="">
           </div>
           

       </div>
    </div>

      :root{
    --vermelho: #E50914;
    --preta: #141414;
}

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/*elementos base*/
body{
    background: var(--preta);
    font-family: 'arial ', Times, serif;
    color: white;
}

header .container{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

header .logo{
    margin-left: 5px;
    color: var(--vermelho);
    font-family: 'Arial Black', Times;
    font: size 40px;
}

header nav a{
    text-decoration: none;
    color: #AAA;
    margin-right: 10px;
}


header nav a:hover{
    color: #fff;
}

/*filme principal*/
.filme-principal{
    font-size: 16px;
    background: linear-gradient(rgba(0,0,0,.50),rgba(0,0,0,.50)100%), url('/img/capa-house.jpg');
    
    height: 400px;
    background-size: cover;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}

.filme-principal .DESCRICAO{
   margin-top: 10px;
   margin-bottom: 40px;
}

.filme-principal .titulo{
    margin-top: 15%;
    font-size: 40px;
    font-family: 'Trebuchet MS', Arial, sans-serif;
}

.botao{
    background-color: rgba(0,0,0,.50);
    border: none;
    color: white;

    padding: 15px 30px;
    margin-right: 15px;
    font-size: 12px;
    
    cursor: pointer;
    transition: 3s ease all;

}

.botao:hover{
    background-color: white;
    color: black;
}

.botao i{
    margin-right: 8px;
}

.container{
    margin-left: 20px;
}

.filme-principal .container{
    width: 70%;
}

.box-filme{
height: 100%;
width: 100%;
display: block;
}

.carrosel-filmes{
    margin-top: 5px;
}

    <scrip src="https://kit.fontawesome.com/f4d1e2c32f.js"></script>
    <script src="js/owl/jquery.min.js"></script>
    <script src="js/owl/owl.carousel.min.js"></script>
    <script src="js/owl/setup.js"></script>


</body>
</html>
  
  @media screen and (max-width:700px){
    header .container{
        display: flex;
        flex-direction: column;
    }   

    .botao{
        margin-top: 5px;
        width: 300px;
    }
}

@media screen and (min-width:1000px){
    .descricao{
        width: 50%;
    }
}

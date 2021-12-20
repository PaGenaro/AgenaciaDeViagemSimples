# AgenaciaDeViagemSimples
<!DOCTYPE html>
<html lang="pt-br">
   
    <head>
        <meta charset="UTF-8">
          <title>Agencia de Viagem</title>
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <link rel="stylesheet" href="viagemRecode.css"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
     
     <style>  
         body{
            background-color: rgb(235, 186, 130);
            margin: 25px; 
           }
     </style>
   
    </head>
   <body>
     <header class="topo" id="topo">
        <div class="logomarca";>
          <h1><P>Infinito</P></h1>
        </div>
     
       <nav class="topo-menu">
          <a href="#banner">HOME</a>
            <a href="#destino">DESTINO</a>
            <a href="#passagens">PASSAGENS</a>
            <a href="#ofertas">PROMOÇÕES</a>
            <a href="#hospedagem">HOSPEDAGEM</a>
            <a href="#contato">CONTATO</a>
     </nav>
     
     </header>
   
 
      <main class="conteudo ">
           <!-- banner e texto-->
           <selection class="banner" id="banner">
             <div class="banner-img">
               <div class="banner-text">
               <h2><p> <b> Bem vindos ao nosso site!</b><p></h2>
              </div>
              <figure>
                <img class="imagem-banner" src="https://j7e9e8a2.stackpathcdn.com/wp-content/uploads/2019/12/passagem-a%C3%A9rea_1.jpg" alt="banner";>
              </figure>
             </div>
             <div class="banner-texto">
                 <p> <br>Somos um site de viagens e turismo que informa e inspira outras pessoas como nós.<br>
                  Divulgamos conteúdos e notícias para fazer nossos leitores viajarem cada vez mais, mostrando que viajar pode ser mais fácil.<br>
                  Aqui você fica por dentro de dicas de lugares, pontos turísticos, passagens aéreas em promoção, indicação de hotéis, agências de passeios,<br>
                   dicas gastronômicas e muitas outras sugestões para você aproveitar ainda mais sua próxima viagem.
                         </p>
              </div>
           </selection>
     </main>
     
       <!--Sobre o Destino-->
      <div class= "destino">
         <div>
          <h2 class="headline";> Destino</h2>
         </div>
          <div class="menuafasta";>
           <nav class="menu";>
            
             <li><a href= "#" style="color: #ffff"><b>NACIONAL<b></a></li>
              <select id="nacional">
                 <option selected disabled volue=""><b>Selecione<b></option>
                 <option>Bahia</option>
                 <option>Lençois</option>
                 <option>FortalezA</option>
              </select> <br>
            
             </nav>
          </div>

         <div class="menu1afasta";>
           <nav class="menu1";>
             
             <li><a href= "#" style="color: #ffff">INTERNACIONAL</a></li>
              <select id="internacional">
                 <option selected disabled volue="">Selecione</option>
                 <option>NEW YOURK</option>
                 <option>lASVEGAS</option>
                 <option>TURQUIA</option>
                 <option>JAPAO</option>
              </select> <br>
              
            </nav>
          </div>
    
       </div>

    <div class="data">
        <h2 class="comprar" style= "color: #fff;"><b>Escolher data:<b> <button><b>comprar<b></button></h2>
            
        <form  method="post">
          
         <table  style="background: rgba(67, 48, 236, 0.787);" >
             <tr >
                 <td style="background: #fff">
                   <b> IDA: <b>
                 </td>
                 <td>
                     <input type="date">
                 </td>
 
                  <td style="background: #fff">
                     <b>Retorno: <b>
                  </td>
                  <td>
                      <input type="date">
                  </td>
                    </tr>
        </form>

          </div>

        <!--Sobre a Promoção-->
        <table class="tabela"> 

          <th>
              
                <div class="promocao1" style="width: 19rem;">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Porto_de_Galinhas-003.jpg/1200px-Porto_de_Galinhas-003.jpg" style="width: 250px; height: 180px;" alt="Porto de Galinhas">

                    <div class="promocao-body">
                        <h2 class="promocao-title" style= "color: #fff;">Porto de Galinhas</h2><br>
                        <p class="promocao-text" style= "color: #fff" >Lugar onde só pode 1 Galo</p>
                        <p> DE R$500 por <br> R$350</p><br>
                        <a href="#" class="btn-primary ">Selecionar</a>
                    </div>
                  </div>
              
            </th>

            <th>
                <div class="promocao2" style="width: 19rem;">
                    <img src="https://www.melhoresdestinos.com.br/wp-content/uploads/2019/02/passagens-aereas-paris-capa2019-02.jpg"  style="width: 250px; height: 180px;" alt="Paris">

                    <div class="promocao-body">
                        <h2 class="promocao-title"  style= "color: #fff;">París</h2><br>
                        <p class="promocao-text" style= "color: #fff">Não é a filha do Michael Jackson</p>
                        <p> DE R$500 por <br> R$350</p><br>
                        <a href="#" class="btn-primary ">Selecionar</a>
                    </div>
                </div>
            </th>


            <th>
                <div class="promocao3" style="width: 19rem;">
                    <img src="https://letouristeblog.com/wp-content/uploads/2015/08/capa-len%C3%A7ois.jpg" style="width: 250px; height: 180px;" class="card-img-top" alt="Lencois">

                    <div class="promocao-body" >
                        <h2 class="promocao-title"  style= "color: #fff;">Lençois</h2><br>
                        <p class="promocao-text" style= "color: #fff">Lugar que não é cama </p>
                        <p> DE R$500 por <br> R$350</p><br>
                        <a href="#" class="btn-primary ">Selecionar</a>
                    </div>
                </div>
            </th>


            <th>
                <div class="promocao4" style="width: 19rem;">
                    <img src="https://monarchairgroup.ru/wp-content/uploads/2019/11/kappadokiya-arenda-chastnogo-samoleta-vozdushnyj-charter.jpg" style="width: 250px; height: 180px;" class="card-img-top" alt="Turquia">
                    <div class="promocao-body"> 
                        <h2 class="promocao-title"  style= "color: #fff;">Turquia</h2><br>
                        <p class="promocao-text" style="color: #fff"><b>Lugar Com atraçoes Baloneis <b></p>
                        <p> DE R$500 por <br> R$350</p><br>
                        <a href="#" class="btn-primary">Selecionar</a>
                    </div>
                </div>
            </th>
        </table>
       
        <!--Sobre a Hospedagem-->
        
       <table class="tabela1"> 

        <th>
            
              <div class="hotel1" style="width: 19rem;">
                  <img src="https://villageportodegalinhas.com.br/village/wp-content/uploads/2020/03/village-porto-de-galinhas-detalhe-bangalo-luxo-frente.jpg" style="width: 250px; height: 180px;" alt="bolo de chocolate">

                  <div class="promocao-body">
                      <h2 class="promocao-title" style= "color: #fff;">Hotel Bungalows</h2>
                      <p class="promocao-text"style= "color: #fff">Porto de Galinhas</p><br>
                      <p> Diarias R$400,00</p><br>
                      <a href="#" class="btn-primary ">Saiba mais</a>
                  </div>
                </div>
            
          </th>

          <th>
              <div class="hotel2" style="width: 19rem;">
                  <img src="https://cf.bstatic.com/xdata/images/hotel/270x200/304092051.jpg?k=a558ff416219a8e5a1423103d1939a46430ba1b2c532542707ccccba9ce2224d&o="  style="width: 250px; height: 180px;" alt="bolo de cenoura">

                  <div class="promocao-body">
                      <h2 class="promocao-title" style= "color: #fff;">Hotel Ibis París</h2>
                      <p class="promocao-text" style= "color: #fff">Paris s</p><br>
                      <p> Diarias R$498,00></p><br>
                      <a href="#" class="btn-primary ">Saiba mais</a>
                  </div>
              </div>
          </th>


          <th>
              <div class="hotel3" style="width: 19rem;">
                  <img src="https://portalbarreirinhas.com.br/home/media/com_mtree/images/listings/m/619.jpg" style="width: 250px; height: 180px;" class="card-img-top" alt="bolo de milho">

                  <div class="promocao-body">
                      <h2 class="promocao-title" style= "color: #fff;">Hotel Barreirinha</h2>
                      <p class="promocao-text" style= "color: #fff">Lençois Maranhence.</p><br>
                      <p> Diarias R$400,00</p><br>
                      <a href="#" class="btn-primary ">Saiba mais</a>
                  </div>
              </div>
          </th>


          <th>
              <div class="hotel4" style="width: 19rem;">
                  <img src="https://guiaviajarmelhor.com.br/wp-content/uploads/2017/11/hotel-carverna-capadocia-25.jpg" style="width: 250px; height: 180px;" class="card-img-top" alt="bolo de coco">
                  <div class="promocao-body"> 
                      <h2 class="promocao-title"  style= "color: #fff;">Hotel Gamirasu</h2>
                      <p class="promocao-text" style= "color: #fff">Turquia</p> <br>
                      <p> Diarias R$400,00</p><br>
                      <a href="#" class="btn-primary">Saiba mais</a>
                  </div>
              </div>
          </th>
      </table>
        
     <div class="contato";>
        <form>
          <label for="nome">Nome: </label>
          <input name="nome" type="text">

          <label for="email">E-mail: </label>
          <input name="email" type="text">
          
          <button>Enviar</button>

        </form>
    </div>
    <div class="link";> 
        <p>
          Links:
          <a href="">Google</a>
          <a href="">Yahoo!</a>
          <a href="">You tube</a>
        </p>
     </div>

    </body>
</html>

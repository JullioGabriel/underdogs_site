# VELOZ FRETES - PROPOSTA DE SITE


Trabalho de faculdade da matéria front-end frameworks
"""

Fiz um a funcao para mudar o banner fiz com modulo.
=======

# header

no header eu criei uma div para fazer a faixa azul que apacere no código.

<div style="width: 100vw; height: 2vh; background-color: rgba(5, 5, 173, 0.774);"></div>

e o restante do menu do header eu coloquei todos os outros elementos dentro de uma div só pra facilitar o posicionamento dos itens do menu

<div id="header-flex-container-1" class="bg-light">
        <div id="menu-header">
          <img id="logo" src="" alt="" class="rounded-circle" style="width: 70px; height: 70px; background-color: orange;">
          <p style="color: orange; padding-top: 1vh;">Empresa</p>
        </div>
        <ul id="menu-header">
            <li><a href="">Sobre nós</a></li>
            <li><a href="">Serviços</a></li>
            <li><a href="">Galeria/frota</a></li>
            <li><a href="">Depoimentos</a></li>
            <li><a href="">Contato</a></li>
        </ul>
    </div>

as id que eu criei foram so pra poder chamar no css sem interferir no bootstrap ja que o bootstrap usa classes, então se eu usasse classes poderia ter algum tipo de interferencia nos nomes das classes.



# baner


pra fazer o baner criei uma div com a <id="fundo"> e dentro dessa div eu coloquei a imagem com uma opacidade de 30% pra ficar igual ao protótipo. fiz isso pra imagem ficar com um tom azulado entao fiz a imagem tranparente ficar por cima do fundo azul

<div id="fundo">
    <img id="baner" src="/imagens/iStock-480652712.jpg" alt="">


    depois dentro da <div id="fundo"> eu criei a ul que contem o texto do banner, fiz isso pra organizar o texto que fica em cima e em baixo, adicionei a id="text-baner" pra organizar as dimençoes do tamanho da letra e posicionamento

        <div id="text-baner">
            <ul>
                <li><p>[Empresa]</p></li>
                <li><p>Fretes</p></li>
                <li><div id="linha"></div></li>
            </ul>
        </div>


    copiei e colei o código e coloquei o conteudo do outro texto do baner, e organizei do outro lado


    <div id="text-baner-span">
    <ul>
        <li><p>Os melhores fretes</p></li>
        <li><p>são com a gente!</p></li>
    </ul>
</div>



# sobre nos



criei 3 div pra fazer o texto do "sobre nós" uma div que vai servir de barra lateral na direita, uma div central com o texto, e uma div do outro lado como uma outra barra lateral



<div id="sobre-nos">
    <div id="barra-lateral">
    </div>
    <div id="span-box">
        <h1 id="titulo-span-box">Sobre nós</h1>
        <span id="text-span-box">Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard dummy text ever since the
            1500s, when an unknown printer took a galley of type and scrambled it to
            make a type specimen book. It has survived not only five centuries, but also
            the leap into electronic typesetting, remaining essentially unchanged Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard dummy text ever since the
            1500s, when an unknown printer took a galley of type and scrambled it to
            make a type specimen book. It has survived not only five centuries, but also
            the leap into electronic typesetting, remaining essentially unchanged.</span>
    </div>
    <div id="barra-lateral">



# divisão 



 a linha que uso para dividir o conteudo do site é uma div onde eu apenas programei as suas dimenções posicionamento e cor pra funcionar como linha.

 <div id="divisao"></div>




 # titulo


 pra criar o titulo eu usei uma h1 e estilizei ela


 <h1 id="titulo-span-box">Serviços</h1>




# serviços



pra criar a parte de serviços, eu usei o título que eu ja havia feito

<h1 id="titulo-span-box">Serviços</h1>


e em baixo dessa div, eu adicionei uma div com id="serviços" com duas div dentro, uma da imagem e outra com o texto

<div id="servicos">
        <div id="transp-veiculo-container" >
            <img id="transp-veiculo" src="/imagens/fretes/transporte-de-motos-espresso-car.png" alt="">
        </div>
        <div id="transp-veiculo-text">
            <p>Frete de</p>
            <p>Motocicletas</p>
        </div>
    </div>


fiz isso pra organizar o posicionamento de "row" da imagem e do texto com mais facilidade aplicando isso na <div id="servicos"> apos isso eu so copiei e colei o codigo para fazer as outras imagens e textos e fui mudando os elementos conforme o protótipo



# depoimentos



usei o mesmo título que eu havia programado mais cedo no código 

<h1 id="titulo-span-box">Depoimentos</h1>


e criei uma div (<div id="depoimentos">) que contem o tutulo e o texto de dois depoimentos.

<div id="text-depoimentos-1">
        <div id="titulo-depoimentos">
            <p>Carla Rodrigues</p>
        </div>
        <div>
            <p id="text-span-box-depoimentos">“Lorem Ipsum is simply dummy
                text of the printing and typesetting
                industry. Lorem Ipsum has been
                the industry's standard dummy
                text ever since the 1500s.”</p>
        </div>
    </div>


e tambem:



<div id="text-depoimentos-2">
        <div id="titulo-depoimentos">
            <p>João André</p>
        </div>
        <div>
            <p id="text-span-box-depoimentos">“Lorem Ipsum is simply dummy
                text of the printing and typesetting
                industry. Lorem Ipsum has been
                the industry's standard dummy
                text ever since the 1500s.”</p>
        </div>
    </div>

fiz isso para aplicar a <div id="depoimentos"> códigos de css para posicionar os elementos da <div id="text-depoimentos-1"> e <div id="text-depoimentos-2">com mais facilidade, ja que aplicar regras css a div pai afeta diretamente as divs filhos


para fazer os outros dois depoimentos eu apenas copiei o código e colei mudando seus conteúdos divergentes




# contato


pra fazer a parte de contato, eu criei a <div id="contato"> e coloquei todos os seus elementos dentro dessa div


titulo:

<div>
        <h1 id="titulo-span-box">Contato</h1>
    </div>


campos de formlário:

<div>
        <div class="col-12">
            <label for="email" id="text-form" class="form-label">Nome: <span class="text-body-secondary"></span></label>
            <input type="email" class="form-control" id="email" placeholder="">
          </div>
    </div>
    <div>
        <div class="col-12">
            <label for="email" id="text-form" class="form-label">Email: <span class="text-body-secondary"></span></label>
            <input type="email" class="form-control" id="email" placeholder="">
          </div>
    </div>
    <div>
        <div class="col-12">
            <label for="email" id="text-form" class="form-label">Telefone: <span class="text-body-secondary"></span></label>
            <input type="email" class="form-control" id="email" placeholder="">
          </div>
    </div>
    <div class="mb-3">
        <label for="exampleFormControlTextarea1" id="text-form" class="form-label">Mensagem</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" style="height: 200px;"></textarea>
    </div>
    




e icones:



<div>
        <div id="icon-container">
            <div id="icon-box"><img id="icon" src="/imagens/social/whatsapp.png" alt=""></div>
            <div id="icon-box"><img id="icon" src="/imagens/social/facebook.png" alt=""></div>
            <div id="icon-box"><img id="icon" src="/imagens/social/instagram.png" alt=""></div>
            <div id="icon-box"><img id="icon" src="/imagens/social/phone-call.png" alt=""></div>
        </div>
    </div>

fiz isso para ter mais facilidade pra estilizar e posicionar seus elementos.




todas os formulários da parte de contato foram importados da biblioteca de css bootstrap e personalizados na página /estilos.css



# mapa



para fazer o mapa, eu criei uma div pra colocar o link da API dentro, e utilizei uma API do google maps com a localização da cidade de Barreiras, apenas compiei o link da API com a opçao "personalizada" e colei no em baixo da div <div id="contato"> e personalizei suas dimençoes no css



# footer



pra criar o roda-pé do site eu criei a div <footer> e dentro dessa div eu criei a div  <div id="footer-contato"> onde coloquei todos os elementos da primeira parte do roda-pé. La eu coloquei a logo 

<div id="logo-footer">

e o texto


<div id="contato-footer-text">
            <ul id="footer-ul">
                <li id="footer-list"><p id="text-negrito">Email:</p><p id="text-footer">nomedaempresa@gmail.com</p></li>
                <li id="footer-list"><p id="text-negrito">Horário de atendimento:</p><p id="text-footer">Segunda à sexta das 6h00 às 19h00</p></li>
                <li id="footer-list"><p id="text-negrito">Endereço:</p><p id="text-footer">Rua ABC, 01 - Alfa</p></li>
                <li id="footer-list"><p id="text-negrito">Fone/Whatsapp:</p><p id="text-footer">(xx) xxxx-xxxx / (xx) x-xxxx-xxxx</p></li>
            </ul>
        </div>

    depois dessa div, ainda dentro do <div id="footer-contato"> eu criei a segunda parte do roda-pé colocando seus elementos dentro da div 

    <div id="footer-logodogs">
        <p id="text-logodogs">Desenvolvido por</p>
        <img id="logo-oficial" src="/imagens/fretes/logo2Oficial.png" alt="">
    </div> 

    e finalizei a construção do site.
    

### CRIANDO O JS DO SITE.

25/03/2024 14H 25m Comecei a criar o carrossel e implementei o botao flutuante do Whatsapp.

25/03/2024 17H 30m Tornei a passagem das imagens do carrossel para que fique lenta.

26/03/2024 10H 43m Adicionei o botao de atalho que aparece apos rolar a pagina e ao ser clicado mostra as sessoes que podem ser acessadas mais rapidamente.

26/03/2024 14 35m Corrigi a distancia que o botao de atalho deve aparecer e desaparecer.

26/03/2024 15H 10m Atualizei a imagem e redirecionamento do botao de whatsapp.

26/03/2024 15H 40m Coloquei uma animaçao ao clicar no botao de whatsapp.


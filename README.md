
<!DOCTYPE html>
<html>
    <head>
        <style>
            body{
    display: flex;
    justify-content: center;
    align-items: center;
    
}
.container{
    width: 100%;
    
    background-size:cover;
    box-sizing: border-box;
    position: relative;
    display: flex;
    
    flex-wrap: wrap;

}
.navbar{
    background-color: #dd2c1d;
    width: 100%;
    height: 20vh;
    display:flex;
    align-items: center;
    
}
#logo{
    width: 120px;
    height: 100px;
    cursor: pointer;
}

.navbar ul li{
    display: inline-block;
    list-style: none;
    
    padding: 17px;
    
}
.navbar ul li a{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-decoration: none;
    color: #ffff;
    font-size: 18px;
    padding: 5px;
    
}
.foto{
    width: 100%;
    
    display: flex;
}
.foto  img{
    
    position: relative;
   width: 100%;
   height: 60vh;
   float: left;
}

.araMenu{
    background-color: #dd2c1d;
    width: 100%;
    height: 13vh;
    display:flex;
    align-items: center;
}
.araMenu ul li{
    display: inline-block;
    list-style: none;
    margin: auto;
    
}

.araMenu ul li a{
    text-decoration: none;
    border: none;

    margin-left: 40px;
    margin-right: 40px;
    padding-left: 20px;
    padding-right: 20px;

    
}
.araMenu ul li p{
    border: none;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #ffff;
    font-size: 12px;
    padding-left: 42px;
    padding-right: 50px;
    margin-right: 10px;
    
}

.duyurular{
    background-color: #f9f6ef;
    width: 100%;
    height: 70vh;
    display:flex;
    
    
}
.duyurular p{
    display: flex;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #555555;
    font-size: 30px;
    margin-left: 42%;
    margin-right: 45%;
    
}
 #line1{
    
        width: 210px;
        height: 47px;
        border-bottom: 3px solid #555555;
        position:absolute;
        margin-top: 30px;
        margin-left: 42%;
        margin-right: 45%;
}
.duyurular #Bhaber{
    width: 350px;
    height: 250px;
    position:absolute;
    margin-top: 150px;
    margin-left: 60px;
}
.Khaber{
    width: 100%;
    
    position: absolute;
}
.Khaber ul{
    margin-top: 150px;
    margin-left: 400px;
}
.Khaber ul li{
    display: inline-block;
    list-style: none;
   
    
}
.Khaber ul li a{
    text-decoration: none;
    margin-left: 30px;
    padding-right: 20px;
    
    
}
#Khaber{
    width: 200px;
    height: 200px;
    
    

}
#line2{
    
    width: 65%;
    height: 40px;
    border-bottom: 3px solid #555555;
    position:absolute;
    margin-top: 360px;
    margin-left: 31%;
    margin-right: 2%;
}
#buton{
    position: absolute;
    width: 180px;
    height: 50px;
    margin-top: 460px;
    color: white;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 13px;
    padding-left: 52px;
    padding-top: 8px;
    background-color: #dd2c1d;
    display: flex;
    margin-left: 80%;
    border-radius: 8%;
   
}
#line3{
    width: 100%;
    height: 40px;
    border-bottom: 3px solid #dd2c1d;
    position:absolute;
    margin-top: 485px;
}

.tan??t??m{
    background-color: #f9f6ef;
    width: 100%;
    height: 70vh;
    display:flex;

}
.tan??t??m p{
    display: flex;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #555555;
    font-size: 30px;
    margin-left: 40%;
    margin-right: 35%;

}
#line6{
    
    width: 315px;
    height: 47px;
    border-bottom: 3px solid #555555;
    position:absolute;
    margin-top: 25px;
    margin-left: 40%;
    margin-right: 45%;
}
.tan??t??m #video{
    position: absolute;
    width: 100%;
    height: 550px;
    margin-top: 0%;
    margin-left: 0%;

}
.footer{
    background-color: #dd2c1d;
    width: 100%;
    height: 70vh;
    display:flex;

}
.footer #Footer1 {
    position: absolute;
    margin-top: 5%;
    margin-left: 30px;
}
.footer #Footer2 {
    position: absolute;
    margin-top: 5%;
    margin-left: 320px;
}
.footer #Footer3 {
    position: absolute;
    margin-top: 5%;
    margin-left: 650px;
}
.footer #Footer4 {
    position: absolute;
    margin-top: 5%;
    margin-left: 950px;
}
.footer #Footer5 {
    position: absolute;
    margin-top: 5%;
    margin-left: 1200px;
}
.footer ul li{
    list-style: none;
}
.footer ul li a{
    text-decoration: none;
    color: #ffff;
    
}
.Fbuyuk {
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #ffff;
    font-size: 23px;
    
    
}
.Fkucuk{
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #ffff;
    font-size: 18px;
    padding-bottom: 20px;
    
}
#line7{
    
    width: 220px;
    
    border-bottom: 3px solid #ffff;
    position:absolute;
}
#line8{
    width: 100%;
    height: 40px;
    border-bottom: 3px solid #ffff;
    position:absolute;
    margin-top: 400px;
}
#footerimg1 {
    width: 30px;
    height: 30px;
    position: absolute;
    margin-left: 70px;
    margin-top: 470px;
}
#p1{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 16px;
    color: #ffff;
    margin-left: 150px;
    margin-top: 460px;
}
#footerimg2{
    width: 30px;
    height: 30px;
    position: absolute;
    margin-left: 620px ;
    margin-top: 470px;

}
#p2{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 16px;
    color: #ffff;
    margin-left: 320px;
    margin-top: 475px;
}
.iletisimRsm{
    width: 30px;
    height: 30px;
}
#iletisim{
    margin-left: 250px;
}
  #iletisim  li {
    display: inline-block;  
    list-style: none;
    margin-top: 450px;
    padding-right: 20px;
    
}

        </style>

    </head>
    <body>
       <div class="container">
           <!--bu alan navbard??r-->
        <div class="navbar">
            <img id="logo" src="http://yaz.mf.firat.edu.tr/assets/front/images/firat-white.png" alt="" >
            <ul>
                <li><a href="">KURUMSAL</a></li>
                <li><a href="">????RENC??</a></li>
                <li><a href="">AKADEM??K</a></li>
                <li><a href="">ARA??TIRMA</a></li>
                <li><a href="">B??LG?? S??STEMLER??</a></li>
                <li><a href="">KAMP??S</a></li>
                <li><a href="">??LET??????M</a></li>
                

            </ul>
          
        </div>
        <div class="foto">
            <img src="http://www.firat.edu.tr//images/news/1635329056.jpg" alt="">
            
        </div>
        <!--bu alan h??zl?? linkler i??indir-->
        <div class="araMenu">
            <ul>
                <li> <a href=""><p>ONL??NE E????T??M</p></a></li>
                <li> <a href=""><p>OBS</p></a></li>
                <li> <a href=""><p>ABS</p></a></li>
                <li> <a href=""><p>M??SAF??RHANE</p></a></li>
                <li> <a href=""><p>K??T??PHANE</p></a></li>
                <li> <a href=""><p>YEMEKHANE</p></a></li>
                <li> <a href=""><p> MEZUN ????RENC??</p></a></li>
                <li> <a href=""> <p>COV??D 19</p></a></li>
            </ul>
        </div>
        <div class="duyurular">
            <p>DUYURULAR</p>
            <div id="line1"></div>
            <a href=""></a> <img id="Bhaber" src="http://www.firat.edu.tr//images/news/1635142769.jpg" alt=""> </a>      
            <div class="Khaber">
                <ul>
                    <li><a href=""><img id ="Khaber"src="http://www.firat.edu.tr//images/news/1634908287.jpg" alt=""></a> </li>
                    <li><a href=""><img id ="Khaber"src="http://www.firat.edu.tr//images/news/1634814471.jpg" alt=""></a></li>
                    <li><a href=""><img id ="Khaber"src="http://www.firat.edu.tr//images/news/1634908287.jpg" alt=""></a> </li>
                    <li><a href=""><img id ="Khaber"src="http://www.firat.edu.tr//images/news/1634814471.jpg" alt=""></a></li>
                </ul>

            </div>   
            <div id="line2"></div>
            <button id="buton">  DAHA FAZLA <br> DUYURU </button>
            <div id="line3"></div>

        </div>
        
        <div class="tan??t??m">
            <p>FIRAT TANITIM F??LM??</p>
            <div id="line6"></div>
            <iframe id="video"  src="https://www.youtube.com/embed/NRUZqr2mvdA" title="YouTube video player"  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
            <button id="buton">  DAHA FAZLA <br> V??DEO </button>

        </div>
        <div class="footer">
            <ul id="Footer1">
                <li ><a class="Fbuyuk"  href="">Y??NET??M</a></li>
                <div id="line7"></div>
                <br>
                <li ><a class="Fkucuk"href="">Rekt??r</a></li>
                <li ><a class="Fkucuk" href="">Rekt??r Yard??mc??lar??</a></li>
                <li><a class="Fkucuk" href="">Genel Sekreter</a></li>
                <li><a class="Fkucuk" href="">Y??netim Kurulu</a></li>
                <li><a class="Fkucuk" href="">Senato</a></li>
                <li><a class="Fkucuk" href="">Kurullar</a></li>
                <li><a class="Fkucuk" href="">Komisyonlar</a></li>  
            </ul>
            <ul id="Footer2">
                <li ><a class="Fbuyuk"href="">??N??VERS??TEM??Z</a></li>
                <div id="line7"></div>
                <br>
                <li ><a class="Fkucuk" href="">Misyon ve Vizyon</a></li>
                <li ><a class="Fkucuk" href="">Temel De??erler</a></li>
                <li ><a class="Fkucuk" href="">Tarih??e</a></li>
                <li ><a class="Fkucuk" href="">Kurumsal Kimlik</a></li>
                <li ><a class="Fkucuk"href="">Foto??raflarla F??rat</a></li>
                <li ><a  class="Fkucuk"href="">D??k??manlar</a></li>
                <li ><a class="Fkucuk" href="">Adresler</a></li>  
            </ul>
            <ul id="Footer3">
                <li ><a class="Fbuyuk"href="">????RENC??LER??M??Z</a></li>
                <div id="line7"></div>
                <br>
                <li ><a class="Fkucuk" href="">??nternational Students</a></li>
                <li ><a class="Fkucuk" href="">Akademik Takvim</a></li>
                <li><a class="Fkucuk"href="">????renci ????eleri</a></li>
                <li ><a class="Fkucuk" href="">Yaz Okulu</a></li>
                <li ><a class="Fkucuk"href=""> D???? ??li??kiler Birmi</a></li>
                <li><a  class="Fkucuk"href="">Burs ??mkanlar??</a></li>
                <li ><a class="Fkucuk"href="">????renci Kl??pleri</a></li>  
            </ul>
            <ul id="Footer4">
                <li ><a class="Fbuyuk" href="">ARA??TIRMA</a></li>
                <div id="line7"></div>
                <br>
                <li ><a class="Fkucuk" href="">Ara??t??rma Projeler Birimi</a></li>
                <li ><a class="Fkucuk" href=""> F??rat Teknokent</a></li>
                <li ><a class="Fkucuk" href="">??niversitenin Yay??nlar?? </a></li>
                <li ><a class="Fkucuk" href="">K??t??phane</a></li>
                <li ><a class="Fkucuk" href=""> Teknoloji Transfer Ofisi  </a></li>
                <li ><a  class="Fkucuk"href="">Harput ???? Kale Kaz??s??</a></li>
                <li ><a  class="Fkucuk"href=""> Merlab</a></li>  
            </ul>
            <ul id="Footer5">
                <li><a class="Fbuyuk" href="">KAMP??STE YA??AM</a></li>
                <div id="line7"></div>
                <br>
                <li ><a class="Fkucuk" href="">Etkinlikler</a></li>
                <li ><a class="Fkucuk" href=""> ??niversite Evi</a></li>
                <li ><a class="Fkucuk" href=""> F??rat Haber </a></li>
                <li><a  class="Fkucuk"href="">F??rat Televiyon</a></li>
                <li ><a class="Fkucuk" href=""> ??leti??im</a></li>
                <li ><a clas
                    s="Fkucuk" href="">K??t??phane</a></li>
                <li ><a  class="Fkucuk" href=""> Sosyal Merkez</a></li>  
            </ul>
            <div id="line8"></div>
            <p id="p1"> 
                ADRES: <br>
                ??niversite,F??rat ??nv. 23119 <br>
                Elaz???? Merkez/Elaz???? 
            </p>
            <p id ="p2"> (0424) 237 00 00 </p>
            
            

        </div>
        

       </div>
    </body>
</html>

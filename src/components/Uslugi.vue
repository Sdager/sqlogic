<template>
  <div class="custom_container row">
    <div class="card sopli col-4">
      <div class="text-overlay">
        <div class="bigtxt">
          администрирование <br />
          серверов
        </div>
        <div class="minitxt">
          Настройка служб DHCP, DNS, FTP, веб-<br />серверы (IIS, Apache),
          развертка леса <br />Active Directory, и многое другое
        </div>
      </div>
      <img class="sopliimg" src="/src/assets/sopli.svg" alt="Sopli Image" />
    </div>
    <div class="card ochko col-4">
      <div class="text-overlay">
        <div class="bigtxt">обслуживание компьютеров</div>
        <div class="minitxt">
          развертывание и перенос рабочих мест,<br />
          а также их настройка, установка ПО<br />
          и подключение оборудования
        </div>
      </div>
      <img class="ochkoimg" src="/src/assets/ochko.svg" alt="Ochko Image" />
    </div>
    <div class="card line col-4">
      <div class="text-overlay">
        <div class="bigtxt">
          <span> подключение</span><br />
          телефонии
        </div>
        <div class="minitxt">
          подключение оборудования телефонной<br />
          связи, настройка правил распределения<br />
          звонков, правил переадресации
        </div>
      </div>
      <img class="lineimg" src="/src/assets/line.svg" alt="Ochko Image" />
    </div>
  </div>
  <div class="row custom_container_buttom">
    <div class="card polosa col-9">
      <div class="up_text">
        обслуживание <br />
        <strong>локальной сети </strong>
      </div>
      <span></span>
      <div class="buttom_text">
        полное сопровождение вашей локальной<br> вычислительной сети, мониторинг,<br>
        конфигурация и установка оборудования
      </div>
    </div>
    <div class="card knopki col-3 "> <div class="text_overlay"><div class="up_text1"><strong>поддержка \ support <br>
      пользователей</strong></div>
    <div class="buttom_text1">консультирование<br> пользователей по всем<br> вопросам</div>
</div>
<img class="knopkiimg" src="/src/assets/knopki.svg" alt="">
    </div>
  </div>

</template>

<script></script>

<style scoped>
.up_text1{
  color: white;
  font-size: 24px;
  text-align: center;

}
.buttom_text1{
  text-align: center;
color: #999898;
margin-bottom: 10em;
font-size: 19px;
}
.knopki {
  position: relative; 
  display: flex;
  flex-direction: column;
  justify-content: center; 
  align-items: center;
  height: 100%;
  background-color: #000000;
  padding: 20px;
}

.knopkiimg {
  position: absolute;
  bottom: 0; 
  left: 50%; 
  transform: translateX(-50%); 
  width: 80%; 
}
.col-3{
  border: none;
  background-color:#000000 ;
}
.up_text{
  font-size: 24px;
}
.buttom_text{
  font-size: 19px;
  display: flex;
  
  text-align: center;
  
}
.col-9{
  gap: 1em;
  border: none;
  background-color:#dad7d7 ;
}
span {
  border-left: 1px solid #1b1b1b;
  height: 100px;
}
.custom_container_buttom {
  display: flex;
  flex-wrap: nowrap;
  margin: 0.6em 10em 1em 9em;
  gap: 1em;
  height: auto; 
}
span {
  background: #dde2ff;
}
.line {
  background: #dad7d7 ;
  border: none;
}

.lineimg {
  margin-bottom: 14em;
  margin-right: 5em;
  height: 23%;
}
.bigtxt {
  font-size: 44px;
  line-height: 110%;
  padding-bottom: 0.4em;
}
.minitxt {
  font-size: 19px;
  color: #999898;
}
.custom_container {
  display: flex;
  flex-wrap: nowrap;
  margin: 4em 11em 0 8.9em;
  gap: 1em;
}

.card {
  border-radius: 35px;
  position: relative;
  height: 55vh;
  background-size: cover;
  background-position: center;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.sopli {
  background: black;
  color: white;
}

.ochko {
  background: #dad7d7 ;
  border: none;
}

.sopliimg,
.ochkoimg {
  height: 100%;
  object-fit: cover;
}

.text-overlay {
  position: absolute;

  text-align: center;

  z-index: 1;
}

@media (max-width: 768px) {
  .custom_container {
    margin: 2em 1em;
  }

  .card {
    height: auto;
  }

  .sopliimg,
  .ochkoimg {
    width: 100%;
    height: auto;
  }

  .text-overlay {
    font-size: 1em;
  }
}

@media (max-width: 1800px){
.card{
  height: 35vh;
}
  .bigtxt{
    font-size: 30px;
  }
  .minitxt{
    font-size: 15px;
  }
  .buttom_text1{
    font-size: 15px;

  }
  .buttom_text{
    font-size: 15px;
    
  }
}
@media (max-height:900px) {
  .card{
    height: 55vh;
  }
  
}
@media (max-width: 1350px){
  .custom_container{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 2em;
    margin: 3em 4em 1em 9em;
  }
  .card{
    width: 45%;
   
   
  }
  .custom_container_buttom{
    display: flex;
    flex-direction: row;
    margin-right: 11.2em;
 
  }
  .polosa{
    width: 56%;
  }
  .knopki{
    width: 49%;
  }
  .knopkiimg{
    height: 13em;
  }
  .line{
    width: 95%;
  }
  
}
@media (max-width: 1200px){
 
  .knopki{
    width: 50%;
   
  }

}
@media (max-width: 1000px){
 
  .knopki{
   width: 55%;
  
 }
.polosa{
  width: 55%;
}
}

@media (max-width: 890px){
  .card{
    width: 100%;
    height: 25em;
  }
  .custom_container{
    margin-right: 6em;
  }
  .custom_container_buttom{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: 0.6em 6em 1em 9em;
}
.polosa{
  width: 100%;
}
.knopki{
  width: 100%;

}
.sopliimg{
  height: 100%;
}
.lineimg{
  height: 19%;
}

}


@media (max-width: 550px){
  .bigtxt{
   font-size: 20px;
  }
  .minitxt{
    font-size: 14px;
  }
  .buttom_text{
    font-size: 14px;
    
  }
  .buttom_text1{
    font-size: 14px;
    
  }
  .card{
    width: 100%;
    height: 25em;
    
  }
  .sopliimg{
    width: 18em;
  }
  .ochkoimg{
  width: 18em;
  }
  .custom_container{
    margin-left: 1em;
    margin-right: 1em;
  }
  .custom_container_buttom{
    margin-left: 1em;
    margin-right: 1em;
  
  }


}


</style>

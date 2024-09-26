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
    <div class="card col-9">
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
    <div class="card knopki col-3"> <div class="text_overlay"><div class="up_text1"><strong>поддержка \ support <br>
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
font-size: 16px;
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
  font-size: 16px;
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
  margin: 0.6em 5em 1em 4em;
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
  font-size: 18px;
  color: #999898;
}
.custom_container {
  display: flex;
  flex-wrap: nowrap;
  margin: 4em 6em 0 4em;
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
</style>

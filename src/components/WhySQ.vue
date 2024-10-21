<template>
  <div class="con">
    <div class="up">
      <h1><strong>Почему SQLogic?</strong></h1>
      <div class="buttom_text">
        мы предлагаем комплексное сопровождение
        инфраструктуры вашего бизнеса.
      </div>
    </div>
    <div class="cards row">
      <div class="card col-3">
        <img src="/src/assets/bez.svg" alt="" /><div class="card_text">
        <h4>безопасность</h4> 
        <div class="mini_text">
          обеспечиваем защиту данных<br />
          клиентов на каждом этапе, внедряя<br />
          актуальные системы безопасности
        </div></div>
      </div>
      <div class="card col-3">
        <img src="/src/assets/opit.svg" alt="" />
        
        <div class="card_text"><h4>опытные специалисты</h4>
        <div class="mini_text">
          вы получаете целый штат<br />
          опытных IT-специалистов,<br />
          которые в кратчайшие сроки
        </div>
    </div>
      </div>
      <div class="card col-3">
        <img src="/src/assets/zatrat.svg" alt="" />
        <div class="card_text">
        <h4>снижение затрат</h4>
        <div class="mini_text">
          вы платите только за те услуги,<br />
          которые вам нужны, что помогает<br />
          оптимизировать бюджет
        </div>
    </div>
      </div>
      <div class="card col-3">
        <img src="/src/assets/world.svg" alt="" />  <div class="card_text">
        <h4>удаленные решения</h4>
        <div class="mini_text">
          все задачи решаем удаленно, вам<br />
          не придется содержать отдельное<br />
          рабочее место
        </div>
      </div></div>
    </div>
  </div>
</template>

<style scoped>
h4{
  font-size: 28px;
}
.mini_text{
  font-size: 20px;
}
.card{
    display: flex;
    gap: 1.2em;
    border-radius: 25px;
  height: 23em;
  width: 30em;
    padding: 3.5em;
}
img {
  height: 25%;
width: 15%;
}
.buttom_text {
  padding-bottom: 1.5em;
  font-size: 22px ;
}
.cards {
  gap: 4em;
  flex-wrap: nowrap;
  
  margin-right: 0em;
}

.con {
  background-color: #c9d1ff;
  height: 55vh;
  margin-left: 8.7em;
   margin-right: 8.7em;
  padding: 5em;
  border-radius: 35px;
  
}
@media (max-width: 2500px) {
  .card{

    gap: 1em;
    border-radius: 25px;
height: 20em;
 width: 24%;
    padding: 2em;
}

h4{
  font-size: 26px;
}
.mini_text{
  font-size: 19px;
}
.cards {
  gap: 2em;
  flex-wrap: nowrap;
  
  margin-right: 0em;
  
}
.con{
  height: 40em;
}
}
@media (max-width: 1700px) {
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 32%;
 width: 24%;
    padding: 2em;
}
h4{
  font-size: 24px;
}
.mini_text{
  font-size: 17px;
}
.cards {
  gap: 2em;
  flex-wrap: nowrap;
  
  margin-right: 0em;
  
}
.con{
  height: 40em;
}
}

@media (max-width: 1500px) {
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 32%;
 width: 47%;
 padding: 2em;
}
h4{
  font-size: 28px;
}
.mini_text{
  font-size: 20px;
}
.cards {

  flex-wrap: wrap;
  justify-content: space-between;


  margin-right: 0em;
  
}.con{
  height: 67em;
  padding: 8em; margin-left: 8.1em;
  margin-right: 7.6em;
}
}
@media (max-width: 1200px) {
  .buttom_text{
    font-size: 20px;
  }
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 32%;
 width: 88%;
 padding: 2em;


}
h4{
  font-size: 28px;
}
.mini_text{
  font-size: 21px;
}
.cards {

  flex-wrap: wrap;
  justify-content: space-between;


  margin-right: 0em;
  
}.con{
  height: 108em;
  padding: 8em; margin-left: 8.8em;
  margin-right: 6.8em;
}
}
@media (max-width: 1000px) {
  .buttom_text{
    font-size: 18px;
  }
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 32%;
 width: 88%;
 padding: 2em;


}
h4{
  font-size: 25px;
}
.mini_text{
  font-size: 18px;
}
.cards {

  flex-wrap: wrap;
  justify-content: space-between;


  margin-right: 0em;
  
}.con{
  height: 108em;
  padding: 3em; margin-left: 8.8em;
  margin-right: 6.2em;
}
}

@media (max-width: 700px) {
  .buttom_text{
    font-size: 18px;
  }
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 32%;
 width: 100%;
 padding: 2em;


}
h4{
  font-size: 25px;
}
.mini_text{
  font-size: 18px;
}
.cards {

  flex-wrap: wrap;
  justify-content: space-between;


  margin-right: 0em;
  
}
.con {
  background-color: #c9d1ff;

  margin-left: 9em;
   margin-right: 6em;

  border-radius: 35px;
  height: 108em;
  padding: 2em;
}
}@media (max-width: 600px) {
  .buttom_text{
    font-size: 18px;
  }
  h1{
    font-size: 22px;
  }
  .card{

    gap: 1em;
    border-radius: 25px;
  max-height: 17em;
 width: 100%;
 padding: 2em;


}
h4{
  font-size: 22px;
}
.mini_text{
  font-size: 17px;
}
.cards {

  flex-wrap: wrap;
  justify-content: space-between;


  margin-right: 0em;
  
}
.con {
  background-color: #c9d1ff;

  margin-left: 1em;
   margin-right: 1em;

  border-radius: 35px;
  height: 88em;
  padding: 2em;
}
}
</style>

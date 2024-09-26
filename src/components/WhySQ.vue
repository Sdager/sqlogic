<template>
  <div class="con">
    <div class="up">
      <h1><strong>Почему SQlogic?</strong></h1>
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
.card{
    display: flex;
    gap: 1.2em;
    padding: 3.5em;
}
img {
  height: 25%;
width: 15%;
}
.buttom_text {
  padding-bottom: 1.5em;
}
.cards {
  gap: 1em;
  flex-wrap: nowrap;
}
.card {
  border-radius: 25px;
  height: 18em;
  width: 27em;
}
.con {
  background-color: #dad7d7;
  height: 60vh;
  width: 100vw;
  padding: 5em;
}
</style>

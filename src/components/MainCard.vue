
<script></script>



<template>
  <div>
    <div class="card row">
      
        <div class="left col-6">
          <div class="up_text">SQLogic — это <br> эффективный <br> аутсорсинг</div>
          <div class="txt">
          <div class="bottom_text">IT-отдел по цене одного <br> специалиста</div>
         <button>Связаться с нами!</button>
        </div>
      </div>       

        <div class="col-6 ">
            <div class="time"></div>
            <div class="plusi row">
                <div class="icons col-1">
                    <img src="/src/assets/res.svg" alt="">
                    <img src="/src/assets/kach.svg" alt="">
                    <img src="/src/assets/stab.svg" alt="">
                </div>
                <ol  class="col-11">
                    <li>стабильность <br>наши решения играют в долгую</li>
                    <li>качество <br>высокие стандарты обслуживания</li>
                    <li>результат <br>помогаем вашему бизнесу расти</li>
                </ol>
            </div>
           <div class="icon_bottom"></div>

        </div>
      </div>
    </div>

</template>
<style scoped>
.icons{
    padding: 0px;
    margin: 0px;
}
img{
    height: 40px
}
.card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #c9d1ff;
  height: 53vh;
  margin-left: 9em;
  margin-right: 9em;
  margin-top: 1em;
  user-select: none;
  border-radius: 25px;
  overflow: hidden;
  position: relative; /* Чтобы псевдо-элемент был относительно родительского элемента */
  border: none;
}

.card::before {
  content: ''; 
  position: absolute;
  top: 75px; 
  bottom: 75px; 
  left: 50%; 
  transform: translateX(-50%); 
  width: 1px;
  background-color: rgb(129, 129, 129); 
}


.left {
  display: flex;
  flex-direction: column;
  align-items: flex-end; 
  gap: 2em;
 
  padding-right: 1em;
  min-width: 300px; 
  max-width: 100%;
  padding-right:2em ;
}

.col-6 {
  display: flex;
  flex-direction: column;
  justify-content: center; 
  height: 100%;
}

.icons {
  display: flex;
  flex-direction: column;
  gap: 2.7em;
  padding-top: 0.35em;
  padding-left: 2em;
}

.up_text {
    line-height: 100%;
    font-size: 6vw; 
    font-weight: bold;
}

.bottom_text {
    font-size: 3vw; 
    padding-right: 2.1em;
}

button {
  color: white;
  background-color: black;
  border-radius: 7px;
  border: none;
  height: 2.4em;
  font-size: 16px;
  width: 60%;
  margin-top:2em ;
}

ol {
  display: flex;
  flex-direction: column;
  gap: 2.2em;
  list-style-type: none;
}

/* Медиазапрос для широких экранов (больше 1200px) */
@media (min-width: 1200px) {
  .up_text {
    font-size: 64px; 
  }

  .bottom_text {
    font-size: 28px; 
  }
  button{
    width: 50%;

  }
  .left{
    gap: 3em;
  }
}

/* Медиазапросы для адаптивности */
@media (max-width: 768px) {
  .card {
    flex-direction: column; /* Блоки друг под другом на маленьких экранах */
    height: auto; /* Автоматическая высота */
    margin-left: 1em;
    margin-right: 1em;
  }

  .left {
    align-items: center; /* Центрируем контент на маленьких экранах */
    text-align: center;
   
    border-bottom: 2px solid grey; /* Добавляем черту снизу */
    padding-right: 0;
    padding-bottom: 1em;
  }

  .up_text {
    font-size: 8vw; /* Увеличиваем относительно ширины экрана */
  }

  .bottom_text {
    font-size: 5vw;
    padding-right: 0;
  }

  button {
    width: 80%;
    font-size: 14px;
  }

  .col-6 {
    align-items: center;
    text-align: center;
  }
}

@media (max-width: 480px) {
  .up_text {
    font-size: 10vw; /* Для маленьких экранов увеличиваем масштаб */
  }

  .bottom_text {
    font-size: 6vw;
  }

  button {
    width: 100%; /* Увеличиваем кнопку на маленьких экранах */
    font-size: 12px; /* Уменьшаем размер текста на кнопке */
  }
}


</style>

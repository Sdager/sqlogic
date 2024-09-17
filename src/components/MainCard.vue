
<script></script>



<template>
  <div>
    <div class="card row">
      
        <div class="left col-6 d-flex flex-column justify-content-center align-items-end">
          <div class="up_text">sqlogic — это <br> эффективный <br> аутсорсинг</div>
          <div class="bottom_text">IT-отдел по цене одного <br> специалиста</div>
         <button>Связаться с нами!</button>
        </div>
        
        <div class="col-6  d-flex flex-column justify-content-center align-items-start">
            <div class="time"></div>
            <div class="plusi row">
                <div class="icons col-2">
                    <img src="/src/assets/res.svg" alt="">
                    <img src="/src/assets/kach.svg" alt="">
                    <img src="/src/assets/stab.svg" alt="">
                </div>
                <ol  class="col-10">
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
<style>
.card {
  background-color: #c9d1ff;
  height: 60vh;
  margin-left: 4em;
  margin-right: 4em;
  margin-top: 1em;
  user-select: none;
gap: 2em;
}
.icons{
    display: flex;
    flex-direction: column;
    gap: 2.7em;
    padding-top: 0.35em;
}
.left{
    gap: 2em;
}
.col-6{
    height: 100%;
}
.up_text{
    line-height: 100%;
    font-size:64px ;
    font-weight: bold;
}
.bottom_text{
    font-size:32px ;
    padding-right: 2.1em;
}
button{
    color: white;
    background-color: black;
    border-radius: 7px;
    border: none;
    height: 2.4em;
    font-size: 16px;
    width: 60%;
}
ol{
 display: flex;
 flex-direction: column;
  gap: 1.7em;
    list-style-type: none;


}
</style>

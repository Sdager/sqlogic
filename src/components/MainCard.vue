<script>
import Modal from "./Modal.vue";
export default {
    name: 'app',
    components: {
      Modal,
    },
    data () {
      return {
        isModalVisible: false,
      };
    },
    methods: {
      showModal() {
        this.isModalVisible = true;
      },
      closeModal() {
        this.isModalVisible = false;
      }
    },
  };
</script>

<template>
  <div>
    <div class="card row">
      <div class="left col-6">
        <div class="up_text">
          SQLogic — это <br />
          эффективный <br />
          аутсорсинг
        </div>
        <div class="txt">
          <div class="bottom_text">
            IT-отдел по цене одного <br />
            специалиста
          </div>
          <button type="button" class="btn" @click="showModal">
            Связаться с нами!
          </button>
          <Modal
      v-show="isModalVisible"
      @close="closeModal"
    />
        </div>

      </div>

      <div class="col-6 bot">
        <div class="time"></div>
        <div class="plusi row">
          <div class="icons col-2">
            <img src="/src/assets/res.svg" alt="" />
            <img src="/src/assets/kach.svg" alt="" />
            <img src="/src/assets/stab.svg" alt="" />
          </div>
          <ol class="col-10">
            <li>стабильность <br />наши решения играют в долгую</li>
            <li>качество <br />высокие стандарты обслуживания</li>
            <li>результат <br />помогаем вашему бизнесу расти</li>
          </ol>
        </div>
        <div class="icon_bottom"></div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.icons {
  padding: 0px;
  margin: 0px;
}
img {
  height: 40px;
}
.card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #c9d1ff;
  height: 65vh;
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
  content: "";
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
  gap: 2.5em;

  padding-right: 1em;
  min-width: 300px;
  max-width: 100%;
  padding-right: 2em;
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
  padding-right: 4em;
}

button {
  color: white;
  background-color: black;
  border-radius: 7px;
  border: none;
  height: 2.4em;
  font-size: 16px;
  width: 100%;
  margin-top: 1em;
}

ol {
  display: flex;
  flex-direction: column;
  gap: 2.2em;
  list-style-type: none;
}

/* Медиазапрос для широких экранов (больше 1200px) */
@media (min-width: 1500px) {
  .card{
height: 40em;
  }
  .up_text {
    font-size: 54px;
  }
  img {
    height: 3em;
  }
 

  .bottom_text {
    font-size: 24px;
  }
  button {
    width: 100%;
    height: 3em;
    font-size: 20px;
  }
  .left {
    gap: 3em;
  }
  img{
    height: 40px;
  }
}
@media (max-width: 1500px) {
  .up_text {
    font-size: 45px;
  }
  .bottom_text {
    font-size: 20px;
  }
  .card {
    height: 28em;
  }
  img {
    gap: 2em;
  
  }
}

@media (max-width: 1150px) {
  .up_text {
    font-size: 30px;
  }
  .bottom_text {
    font-size: 13px;
  }
  .card {
    height: 40em;
    margin-right: 7.5em;
  }
  img {
    gap: 2em;
    height: 50;
  }
  ol {
    font-size: 13px;
    gap: 3.5em;
    list-style-type: none;
  }
}
/* Медиазапросы для адаптивности */
@media (max-width: 890px) {
  .up_text {
    font-size: 37px;
  }
  .bottom_text {
    font-size: 16px;
    width: 100%;
    padding: 0px;
  }
  .card {
    padding: 1em;
    display: flex !important;
    flex-direction: column; /* Блоки друг под другом на маленьких экранах */
    height: auto; /* Автоматическая высота */
    margin-left: 9em;
    margin-right: 6.2em;
    gap: 2em;
  }

  .icons {
    padding: 0px;
    margin: 0px;
  }
  img {
    height: 30px;
  }

  .txt {
    width: 100%;
  }
  button {
    width: 100%;
  }

  .left {
    display: flex;
    justify-content: start;
  }
  .icons {
    gap: 2.5em;
  }

  ol {
    gap: 2em;
  }

  .card::before {
    content: none;
    position: absolute;
    top: 0px;
    bottom: 0px;
    left: 0%;
    transform: none;
    width: 0px;
    background-color: none;
  }

  .up_text {
    align-content: start;
    text-align: start;
    display: flex;
    height: 100%;
  }
}

@media (max-width: 580px) {
  .up_text {
    font-size: 38px; /* Для маленьких экранов увеличиваем масштаб */
  }

  .bottom_text {
    font-size: 4vw;
  }

  button {
    width: 100%; /* Увеличиваем кнопку на маленьких экранах */
    font-size: 12px; /* Уменьшаем размер текста на кнопке */
  }
  ol {
    gap: 1.2em;
    width: 70%;
  }
  .icons {
    gap: 1.5em;
    padding-top: 10px;
    margin-left: 0em;
    width: 20px;
  }
  .card {
    margin-left: 1em;
    margin-right: 1em;
  }
  .bot {
    text-align: start;
    width: 100%;
    display: flex;
    flex-direction: center;
  }
  .plusi {
    margin: 0;
  }
}
</style>

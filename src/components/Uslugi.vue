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
    <div class="card col-4">
      <div class="text-overlay">Текст для пустой карточки</div>
      <img class="lineimg" src="/src/assets/line.svg" alt="Ochko Image" />
    </div>
  </div>
</template>

<script></script>

<style scoped>
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
  margin-bottom: 100px;
}

.sopli {
  background: black;
  color: white;
}

.ochko {
  background: #f4f4f4;
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

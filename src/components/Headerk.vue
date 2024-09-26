<template>
  <div class="row custom_container">
    <div class="col-2 ">
      <ol>
        <li>Контакты</li>
        <li>Услуги</li>
      </ol>
    </div>
    <div class="col-9 d-flex justify-content-center align-items-center"><img src="/src/assets/logo.svg" alt=""></div>
    <div class="right col-1 d-flex justify-content-start">О компании</div>
  </div>
</template>

<style scoped>
*{
  font-size: 16px;
  
}
.custom_container {
  padding: 0px;
  margin: 0px;
  user-select: none; 
  

}
.col-2, .col-1 {
  margin-top: 0.6em;
}
.right{
  padding-right: 0.2em;
}
img{
  cursor: pointer;
}
ol{
  cursor: pointer;
  
    list-style-type: none;
    display: flex;
    flex-direction: row;
    gap: 1.7em;
}
</style>
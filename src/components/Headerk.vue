<template>
  <div class="row custom_container">
    <div class="col-2 col-md-2 col-sm-3 col-xs-4">
      <ol>
        <li>Контакты</li>
        <li>Услуги</li>
      </ol>
    </div>
    <div class="col-9 col-md-8 col-sm-6 col-xs-3 d-flex justify-content-center align-items-center"><img src="/src/assets/logo.svg" alt=""></div>
    <div class="right col-1  col-md-2 col-sm-3  col-xs-5 d-flex justify-content-start">О компании</div>
  </div>
</template>

<style scoped>
*{
  font-size: 16px;
  
}
.custom_container {
  padding: 0px;
margin-left: 6em;
margin-right:6em ;
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
  height: 60px;
}
ol{
  cursor: pointer;
  
    list-style-type: none;
    display: flex;
    flex-direction: row;
    gap: 1.7em;
}
@media (max-width: 1500px) {
  .custom_container {
  padding: 0px;
margin-left: 6em;
margin-right:8em ;
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
  height: 60px;
}
ol{
  cursor: pointer;
  
    list-style-type: none;
    display: flex;
    flex-direction: row;
    gap: 1.7em;
}
 }
 @media (max-width: 900px) {
  .custom_container {
  padding: 0px;
margin-left: 1em;
margin-right:0em ;
  user-select: none; 
  

}
.col-2, .col-1 {
  margin-top: 0.6em;
}

img{
  cursor: pointer;
  height: 50px;
}
ol{
  cursor: pointer;
  
    list-style-type: none;
    display: flex;
    flex-direction: row;
    gap: 1.7em;
}
 }
 @media (max-width: 590px) {
  .custom_container {
  padding: 0px;


  user-select: none; 
  

}


img{
  cursor: pointer;
  height: 40px;
}
ol{
  cursor: pointer;
  
    list-style-type: none;
    display: flex;
    flex-direction: row;
    gap: 1.7em;
}
 }
</style>
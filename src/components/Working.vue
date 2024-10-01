<template><div class="con">
    <div class="custom_container row" >
        <div class="col-3 up"><div class="logo"><img src="/src/assets/company/hs.svg" alt=""></div></div>
        <div class="col-3 up "><div class="logo"><img src="/src/assets/company/rddm.svg" alt=""></div></div>
        <div class="col-3 up "><div class="logo"><img src="/src/assets/company/ros.svg" alt=""></div></div>
        <div class="col-3 up "><div class="logo"><img src="/src//assets/company/avc.svg" alt=""></div></div>
    </div>  <div class="line"></div> <div class="custom_container row" >
        <div class="col-3 bottom"> <div class="logo"><img src="/src/assets/company/bchp.svg" alt=""></div></div>
        <div class="col-3 bottom"><div class="logo"><img src="/src/assets/company/rosmol.svg" alt=""></div></div>
        <div class="col-3 bottom"><div class="logo"><img src="/src/assets/company/peremena.svg" alt=""></div></div>
        <div class="col-3 bottom"><div class="logo"><img src="/src/assets/company/cemak.svg" alt=""></div></div>
    </div>
</div>
</template>

<style scoped>
.con{
    
    padding-top: 2em;
display: flex;
flex-direction: column;
gap:3em;
    padding-bottom: 2em;
   

}
.line{
    border-bottom: 1px solid grey;
    margin-left: 4em;
    margin-right: 4em;
}
.up{
    border-left: 1px solid grey ;
    border-right: 1px solid grey ;
}
.bottom{
    border-left: 1px solid grey ;
    border-right: 1px solid grey ;
}
.col-3{
   
    display: flex;
 height: 17vh;   
justify-content: center;  
align-items: center;
}

.custom_container{
    margin-left: 4em;
    margin-right: 4em;
    align-items: center;
   display: flex;
   justify-content: center;
    text-align: center;
}
</style>
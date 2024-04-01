<template>
    <div id="contact">
        <h1>Contacts</h1>        
        <div class="Container">   
            <div class="c">
                <img src="@/assets/gmail.svg" alt="gmail logo">
            <p>vins.rendon@gmail.com</p>
            </div>
            <div class="c">
                <img src="@/assets/phone.svg" alt="phone logo">
            <p>+639123456789</p>
            </div>         
        </div>         
    </div>  
    <h1>Socials</h1>
        <div class="Container">            
            <a href="https://www.facebook.com/vinsoy.rendon" target="_blank"><img src="@/assets/facebook.svg" alt="Facebook logo that redirects to the website author's facebook profile"></a>
            <a href="https://twitter.com/VincentRendon6" target="_blank"><img src="@/assets/x-logo.svg" alt="Twitter logo that redirects to the website author's twitter profile"></a>
            <a href="https://www.artstation.com/rendonrenders" target="_blank"><img src="@/assets/artstation_logo.svg" alt="Artstation logo that redirects to the website author's artstation profile"></a>
        </div>  
</template>

<style scoped>
h1{
text-align: center;
margin-top: 20px;
font-size: 80px;
}
#contact{
    box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    -webkit-box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    -moz-box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    padding-bottom: 50px;
}
#contact p{
    text-align: center;
    font-size: 20px;
}
.Container{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 0px 50px 0px 50px;
}
.Container img{
    filter: invert(1);
    width: 150px;
}
a, .Container img{
    z-index: -1;
}
.c{
    width: 200px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
@media screen and (max-width: 800px) {
    .Container img{
        width: 80px;
    }
}
</style>
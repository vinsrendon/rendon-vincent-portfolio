<template>
    <div id="contact">
        <h1>Contacts</h1>        
        <div class="Container">            
            <p>
                <img src="@/assets/gmail.svg" alt="gmail logo">
                <br>vincent.rendon@gmail.com
            </p>
            <p>
                <img src="@/assets/phone.svg" alt="phone logo">
                <br>+639123456789
            </p>
        </div>         
    </div>  
    <h1>Socials</h1>
        <div class="Container">            
            <p><a href="https://www.facebook.com/vinsoy.rendon" target="_blank"><img src="@/assets/facebook.svg" alt="Facebook logo that redirects to the website author's facebook profile"></a></p>
            <p><a href="https://twitter.com/VincentRendon6" target="_blank"><img src="@/assets/x-logo.svg" alt="Twitter logo that redirects to the website author's twitter profile"></a></p>
            <p><a href="https://www.artstation.com/rendonrenders" target="_blank"><img src="@/assets/artstation_logo.svg" alt="Artstation logo that redirects to the website author's artstation profile"></a></p>
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
    justify-content: space-evenly;
    padding: 0px 50px 0px 50px;
}
.Container img{
    filter: invert(1);
    width: 150px;
}
@media screen and (max-width: 800px) {
    .Container img{
        width: 150px;
    }
}
</style>
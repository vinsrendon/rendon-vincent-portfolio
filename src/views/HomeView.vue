<script setup>
import About from '@/components/AboutComponent.vue'
import Skills from '@/components/SkillsComponent.vue'
import Works from '@/components/WorksComponent.vue'
import Contact from '@/components/ContactComponent.vue'
</script>

<template>
    <div id="home"></div>
    <div class="wrapper">       
            <h1>Welcome to my portfolio</h1> 
            <p>
                Hi, my name is <span style="color: yellow;"><b>Vincent Rendon</b></span> a college student from <span style="color: yellow;"><b>Cordova Public College</b></span> <br/> with a passion for Computer Programming and Digital 3D Art
            </p>
    </div>  
    <Works />
    <Skills />
    <About />  
    <Contact />        
</template>

<style scoped>
p{
    color: var(--text); 
    text-shadow: 2px 0px 15px rgba(86,0,251,1);
}
.wrapper{    
    /*Photo by Markus Spiske on Unsplash*/
    background-image: url('https://unsplash.com/photos/computer-coding-screengrab-hvSr_CVecVI');
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size:cover;
    padding: 5px;
}
.wrapper h1{
    text-align: center;
    font-size: 8vw;
    pointer-events: none;
    cursor: default;   
    color: var(--text); 
    text-shadow: 2px 0px 15px rgba(86,0,251,1);
    padding-top: 150px;
}
.wrapper p{
    text-align: center;
    font-size: 2vw;
    padding-top: 100px;
}
@media screen and (max-width: 800px) {
    .wrapper h1{
        font-size: 80px;
    }
.wrapper p{
        font-size: 24px;
    }
}
</style>
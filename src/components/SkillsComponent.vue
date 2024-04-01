<template>    
    <div id="skills">
        <h1>Skills</h1>
        <div class="Container">
            <img src="@/assets/blender.svg" alt="Blender3D logo">
            <img src="@/assets/java.svg" alt="Java logo">
            <img src="@/assets/vue.svg" alt="Vue JS logo">
            <img src="@/assets/php.svg" alt="PHP logo">
            <img src="@/assets/html.svg" alt="HTML logo">
            <img src="@/assets/js.svg" alt="Javascript logo">  
            <img src="@/assets/css.svg" alt="CSS logo">
            <img src="@/assets/cpp.svg" alt="C plus plus logo">
            <img src="@/assets/boot.svg" alt="Boostrap logo">
            <img src="@/assets/tail.svg" alt="TailwindCSS logo">
        </div>            
    </div>
</template>

<style scoped>
#skills{
    box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    -webkit-box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    -moz-box-shadow: -1px 0px 10px 2px rgba(86,0,251,1);
    padding-bottom: 50px;
}
h1{
text-align: center;
margin-top: 20px;
font-size: 80px;
}
.Container{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    padding: 0px 25px 0px 25px;
}
.Container img{
    filter: invert(1);
    width: 20%;
    padding: 25px;
    pointer-events: none;
    z-index: -1;
}
@media screen and (max-width: 800px) {
    .Container img{
        width: 150px;
    }
}
</style>
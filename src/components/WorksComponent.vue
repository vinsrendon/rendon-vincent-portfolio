<template>    
    <div id="works">
        <h1>Works</h1>
        <div class="container">
            <div class="work">                
                <a href="https://github.com/vinsrendon/OS-CPU-Scheduling" target="_blank">
                    <img src="@/assets/fcfs.jpg" alt="first come first serve image">
                </a>
                <h2>First Come First Server CPU scheduling program using Javascript</h2>
            </div>
            <div class="work">
                <a href="https://github.com/vinsrendon/JSCalculator" target="_blank">
                    <img src="@/assets/jscal.jpg" alt="Javascript calculator image">
                </a>
                <h2>Javascript Calculator</h2>
            </div>
            <div class="work">
                <a href="https://github.com/vinsrendon/API_Projects" target="_blank">
                    <img src="@/assets/api.jpg" alt="API image">
                </a>
                <h2>API Projects</h2>
            </div>
        </div>
    </div>
</template>

<style scoped>
h2{
    text-align: center;
}
.container{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}
#works{
    padding-bottom: 50px;
}
.work{
    padding: 10px;
    border: solid;
    border-radius: 10px;
    border-width: 1px;
    border-color: white;
    width: 30%;
    margin: 10px;
}
.work img{
    width: 100%;
    object-fit: cover;
    object-position: center;
}
h1{
text-align: center;
margin-top: 20px;
font-size: 80px;
}

@media screen and (max-width: 800px) {
    .work{        
        width: 300px;
    }
}
</style>
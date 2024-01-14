<section>
    <div class="container">
        <div class="text">
            <h2>Lars Niklas <span>Fornarve</span></h2>
        <p>Hej på er, alla besökare till min hemsida, som har börjat få ett innehåll, men tanken är att det ska komma mycket mer vartefter!</p>
        </div>
        <div class="bild"></div>
    </div>
</section>


<style>
    section{
        height:60vh;
    }
    .container{
        width:80%;
        margin: auto;
        display:flex;
        height:100%;
    }
    .text{
        width:50%;
        color: var(--dark);
        display:flex;
        flex-direction: column;
        justify-content: center;
        
    }
    .text p{
        padding-top: 1.5em;
        line-height: 1.5em;
        font-size: 1.2em;
    }
    .text h2{
        font-size: 2.5em;
    }
    .bild{
        background-image: url("/img/headshot.png");
        background-size: cover;
        background-repeat: no-repeat;
        flex:1;
        
    }   
    span{
        color: var(--purp);
    }
</style>
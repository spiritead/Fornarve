<script>
    let flipped = false;
    function toggleFlip() {
    flipped = !flipped;
    console.log(flipped, 'hej');
  }
//   toggleFlip();
</script>

<div class="background">
    <div class="titel">
        <span></span><h2>Upplägg</h2><span></span>
    </div>
    <div class="content">
        <p class='text'>Alla J ljud är J <br>
            sj-ljud som sjö är x <br>
            sj-ljud som kök är c <br>
            finns inga dubbelkonsonanter istället styr vokalerna. Enkelvokal om "kort" ljud dubbelvokal vid långt ljud.
            Säng och äng och dom ljuden är ett E. Det är för att det är ett mellanting mellan ett ä och ett e.
            ng-ljudet som i regn är ett eget ljud och en speciell bokstav som är ett n med en krok inåt: <a href="https://sv.wikipedia.org/wiki/%C5%8A">Ŋ ŋ</a></p>
        <div class="container">
            <!-- class:flipped={flipped} betyder att om flipped är true så ska den lägga till flipped classen. https://learn.svelte.dev/tutorial/classes -->
            <div class="card" class:flipped={flipped}>
                <div class='frontside'>
                    <p>Om förvirring är första steget
                    mot kunskap så måste jag vara ett geni!
                    - Larry Leissner
                    </p>
                </div>
                <div class='backside'>
                    <p>Om föörviring äär första steeget
                    moot kunskaap såå måste jaag vaara et xenii!
                    - Larry Leissner
                    </p>
                </div>
            </div>
                <div class="button">
                    <button on:click={toggleFlip}>Reformera</button>
                </div>
        </div>
    </div>
</div>


<style>
*{
    box-sizing: border-box;
    padding:0;
    margin:0;
}
.background{
    background-color: var(--dark);
    height:60vh;
    padding-top: 1rem;
}

.titel{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    padding-top: 2rem;
    padding-bottom: 2rem;
}
h2{
    color:white;
}
span{
    background-color: white;
    height: 1px;
    width: 33%;
}
.content{
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width:80%;
    flex-direction: row;
    gap: 1rem;
    padding-top: 2rem;
    padding-bottom: 2rem;
}
.text{
    color:white;
    text-align: left;
    width:55%;
    line-height: 1.5rem;
}
/* cardcontainer */
.container{
    display:flex;
    margin-top: 2em;
    flex-direction: column;
    gap: 6em;
    height: 100%;
    align-items: center;
    justify-content: center;
    width:25%;
}
.card{
    position:relative;
    color:white;
    transition: transform 0.55s ease-in-out;
    transform-style: preserve-3d;
    width:100%;
    height:80%;
    
}
.frontside, .backside{
    box-sizing: border-box;
    padding:3em 2em 3em 2em;
    position:absolute;
    width:100%;
    height:100%;
    border:1px solid white;
    border-radius: 1em 1em 0 0;
    border-bottom: none;
    left:0;
    top:0;
    backface-visibility: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
}
.backside{
    transform:rotateY(180deg);
}
.button{
    width:100%;
}
button{
    padding:0.6em;
    width:100%;
    background-color: var(--yell);
    font-family: 'shift', serif;
    font-weight: 600;
    font-size: 1em;
    border:none;
    cursor:pointer;
}
.card.flipped{
    transform:rotateY(180deg);
}
a{
    text-decoration: underline;
}
</style>
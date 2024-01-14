<div class="container">
    <div class="titel">
        <span></span><h2>Lars Niklas Fornarve</h2><span></span>
    </div>
    <div class="content">
        <p>Jag är utbildad mellanstadielärare, 
            och har också jobbat som sådan en 
            del av mitt liv, men har också provat 
            på en del andra yrken, såsom 
            långtradarchaufför, mejerist, 
            industriarbetare m fl. Jag har också 
            studerat nordiska språk, litteraturvetenskap 
            och allmän språkvetenskap på Stockholms universitet. 
            Jag har även varit lärare för äldre personer än 
            mellanstadieelever, såväl vuxna som tonåringar. 
            Nu är jag dock pensionär sedan jan-18. Jag spelar 
            också musik, ensam och i diverse grupper i olika sammanhang.</p>

            <div class="pic">
                <img src="/img/lasse.jpg" alt="">
            </div>
    </div>
</div>

<style>
    .container{
        background-color: var(--gray);
        height: 60vh;
        padding-top: 1rem;
    }
    .titel{
        display:flex;
        justify-content: center;
        align-items: center;
        gap:2rem;
    }
    span{
        background-color: var(--dark);
        height: 1px;
        width: 21%;
    }
    h2{
        color: var(--dark)
    }
    .content{
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        width:80%;
        flex-direction: row;
        gap: 1rem;
        margin-top: 3rem;
        padding-top: 2rem;
        padding-bottom: 2rem;
        height: 50%;
    }
    p{
        color: var(--dark);
        text-align: left;
        width:55%;
        line-height: 1.5rem;
    }
    .pic{
        width: 25%;
        height:205%;
        
    }
    img{
        width: 100%;
        object-fit: cover;
        object-position: center;
        border-radius: 25px;
        height:100%;
        position:relative;
    }
</style>
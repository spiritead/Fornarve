<section>
    <div class="container">
        <div class="helpside">
            <h2>Hjälp gärna till!</h2>
            <p>Tycker du att det här låter som en bra idé? Lämna gärna din underskrift
                till listan så vi vet att det vi gör är bra! Framöver har vi planerat
                att översätta hela ordboken som självklart är ett stort jobb och varje 
                underskrift ger oss mer motivation! Vi är övertygade om att det här är 
                ett steg i rätt riktning och att svenskan kan bli en förebild som språk!</p>
        </div>
        <div class="form">
            <h2>Namninsamling</h2>
            <p>Namn</p>
            <input type="text" autocomplete="name">
            <p>Epost</p>
            <input type="email" autocomplete='email'> 
            <button>Skriv under!</button>
        </div>
    </div>
</section>

<style>
    h2{
        font-size: 2em;
    }
    .helpside p{
        width:70%;
        padding-top: 1.5em;
    }
    .form p{
        font-size: 1.3em;
        padding-top: 1.5em;
        padding-bottom: 0.2em;
        font-weight: 600;
    }
    section{
        height: 60vh;
        background-color: var(--gray);
    }
    .container{
        width:80%;
        height:100%;
        margin:auto;
        display:flex;
        gap:3em;
        justify-content: space-between;
    }
    input{
        width:90%;
        padding:0.7em;
        font-size: 1.3em;
        border-radius: 0.7em;
        border: 2px solid var(--gray);
        font-family: 'shift', serif;
        transition: 0.3s ease;
    }
    input:focus {
      border-color: dodgerblue;
      outline: none;
    }
    .helpside{
        width:40%;
        height:100%;
        display:flex;
        flex-direction:column;
        justify-content:center;
        /* align-items:center; */
    }
    .form{
        width:60%;
        padding:1.5em;
        padding-right: 0;
    }
    
    
    button{
        width: 90%;
        padding: 0.7em;
        border-radius: 0.7em;
        background-color: var(--yell);
        color: var(--dark);
        font-size: 1.3em;
        font-weight: 600;
        margin-top: 1.5em;
        cursor:pointer;
        font-family: 'shift', serif;
        align-self: flex-end;
    }

</style>


<script>
    function scrollToBottom() {
      window.scrollTo({
        top: document.body.scrollHeight,
        behavior: 'smooth'
      });
    }
  </script>
<div class='hero'>
    <div class="text">
        <h2>Fornee - Stavningsreform</h2>
        <h2>Gör <span>stavningen</span> enklare</h2>
        <p>Vi kan stava som vi pratar <br>och göra språket lättare!</p>
    </div>
    <div class="buttonContainer">
        <div class='button'>
            <button on:click={scrollToBottom}>Skriv under!</button>
            <img src="/img/feather-icon.png" alt="pen">
        </div>
    </div>
</div>

<style>
    .hero{
        background-image: url("/img/hero_bok.jpg");
        height:70vh;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center top 73%;
        position: relative;
        display: flex;
        gap: 15rem;
        padding: 5rem;
        
    }
    span{
        color: var(--purp);
    }
    .text{
        color: var(--yell);
        padding-left: 2.7rem;
        position:relative;
        bottom:2em;
        
    }
    h2{
        line-height: 3.3rem;
    }
    p{
        font-size: 1.3rem;
        padding-top: 0.7rem;
        line-height: 1.6rem;
    }
    .buttonContainer{
        background-color: var(--dark);
        padding:0.9rem;
        height:fit-content;
        border-radius: 0.5rem;
        margin-top: 2.5rem;
        transition:  0.3s ease;
        cursor:pointer;
        
    }
    .buttonContainer:hover{
        padding:1rem;
        border: 2px solid var(--purp);
        
    }
    .button{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    button{
        cursor:pointer;
        border:none;
        background-color: var(--dark);
        color: white;
        font-family: inherit;
        font-weight: 500;
        font-size: 1.5rem;
    }
    img{
        width: 30px;
        filter: invert(100%);
    }

</style>
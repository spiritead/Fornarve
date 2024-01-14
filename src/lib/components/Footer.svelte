  <section>
    <div class="container">
        <div class="name">
            <h2><a href="/">Fornarve</a></h2>
            <p>Här kan ni gå in och ta del av mina tankar om en stavningsreform. Det låter kanske ganska udda, men det är idéer jag haft under många år</p>
        </div>
        <div class="nav">
            <h3>Navigering</h3>
            <ul>
                <li><a href="./ortografi/+page.svelte">Ortografi</a></li>
                <li><a href="./om/+page.svelte">Om</a></li>
                <li><a href="./smakprov/+page.svelte">Smakprov</a></li>
            </ul>
        </div>
        <div class="contact">
            <h3>Kontakt</h3>
            <ul>
                <li><a href="tel:+4670 444 7886">070 444 7886</a></li>
                <li><a href="https://maps.app.goo.gl/L9GEFkmachYQWu9T9">Lingonvägen 13, Oxelösund</a></li>
                <li><a href="mailto:lars.fornarve@gmail.com">lars.fornarve@gmail.com</a></li>
                <li><a href="https://www.facebook.com/groups/470219353474575/"><img src="/img/fb_round.svg" alt="facebook link"></a></li>
            </ul>
        </div>
    </div>
</section>

<style>
section{
    height: 30vh;
    background-color: var(--dark);
    color:white;
}
.container{
    width:80%;
    height:100%;
    margin:auto;
    display:flex;
    justify-content: space-between;
}
h3{
    font-size: 1.5em;
    font-weight: 600;
}
p,ul{
    padding-top: 1em;
}
.name, .nav, .contact{
    width:30%;
    height:100%;
    display:flex;
    flex-direction:column;
    justify-content:center;
   
}
.name p{
    width:70%;
}
.nav{
    padding-left: 4.5em;
}
.contact{
    text-align: right;
    padding-top: 2.1em;
}
img{width: 30px;}

</style>
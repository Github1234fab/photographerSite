
<div class="container">
<div class="hero">
        <h1 class="hero-text">Welcome to my Portfolio</h1>
        <ul class="liste">
                <li>    <a href="/photographer" class="style-link">Portraits</a></li>
                    <li>    <a href="/photographer" class="style-link">Objets</a></li>
                        <li>    <a href="/photographer" class="style-link">Paysages</a></li>
                            <li>    <a href="/photographer" class="style-link">Abstrait</a></li>
                   
        </ul>
</div>
</div>

<style>
        .hero {
                height: 100vh;
                margin-top:-100px;
                background-image: url("../Assets/NYCABlack.png");
                background-size: cover;
                background-position: center;
                background-repeat: no-repeat;
                z-index: 0;
        }
        .hero-text {
                position: absolute;
                top: -100px;
                left: 20%;
                color: black;
                font-size: 3rem;
                text-align: center;
                margin-top: 300px;
                z-index: 0;

        }
        .liste {
                position: absolute;
                top: 27%;
                left: 30%;
                transform: translate(-50%, -50%);
                display: flex;
                gap: 20px;
                z-index: 0;
        }
        .style-link{
                text-decoration: none;
                color: black;
                font-size: 1.3rem;
        }

</style>

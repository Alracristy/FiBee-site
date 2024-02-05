<div class="container">
        <div class="navbar-container"></div>
        
        <nav>
            <a href="#">
                <img src="1agustus_little_bee.jpg" alt="Logo Test" class="logo">
            </a>
            <ul class="navbar-items">
                <li>
                    <a href="#">Apresentação</a>
                </li>
                <li>
                    <a href="#">Projeto</a>
                </li>
                <li>
                    <a href="#">Desenvolvedores</a>
                </li>
                <li>
                    <a href="#">Créditos</a>
                </li>
                <li>
                    <a href="#"></a>
                </li>
            </ul>
        </nav>
        <main>
            <div class="main-banner">
                <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio voluptatem, eaque officiis impedit
                    voluptates quam, inventore voluptas dolorum autem molestias unde odit velit consectetur sunt iusto
                    voluptatibus praesentium fuga assumenda.</h1>
                    <br>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est quibusdam facere earum nesciunt incidunt
                    perferendis asperiores ab tenetur, libero eos molestiae doloremque nostrum natus eligendi sed
                    accusamus rerum impedit corrupti?</p>
            </div>

        </main>


    </div>

    CSS

    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

h1,
h2{
    color: #333;
}

p {
    color: #70747a
}

/* Navbar */
.navbar-container {
    width: 100%;
    height: 100px;
    background-color: #353232;
    padding: 0 2rem;

}
nav{
    position: relative;
}

.logo {
    width: 100px;
    margin-top: 15px;
    position: relative;
    bottom: 115px;
}
.navbar-items{
    position: absolute;
    bottom: 130px;
    right: 30px;
    height: 80px;
    line-height: 80px;
    margin: 0;
    display: inline-block;
}
.navbar-items li{
    display: inline-block;
    text-transform: uppercase;
    margin-left: 25px;

}
.navbar-items a{
    color: rgb(255, 255, 255);
    text-decoration: none;
    
}

/* Main banner */
.main-banner{
    background-image: url(renderizacao-3d-de-fundo-de-textura-hexagonal.jpg);
    padding: 10rem 0;
    background-size: cover;
    background-position: left;
    position: relative;
    bottom: 120px;
    

    
    
}
.main-banner h1,
.main-banner p{
    color: white;
    text-align: center;
    font-weight: bold;
    text-shadow: black 3px 2px 3px;


}

    
 

<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title>Minha pagina</title>
    <link rel="stylesheet" href="estilo.css">
    <style>
header {
 background-color: crimson;
 color: white;
 padding: 20px;
 display: flex;
 justify-content: space-between;
 align-items: center;
 font-size: 24pt;
}
nav {
   font-size: 24pt;
    margin: 0 auto;
}
nav ul {
    background-color: blue;
    justify-content: center;
    display: flex;
    list-style: none;
    gap: 20px;
    max-width: 100%;
}
nav a {
    text-decoration: none;
    color: green;
    font-weight: bold;
}
nav a:hover {
    color: gold;
}
.container {
  display: flex;
  gap: 20px;
}
main {
    background-color: aquamarine;
    flex: 3;
    text-align: center;
    max-width: 35%;
    min-height: 80vh;
    border-radius: 30px;
}
section{
    background-color: blueviolet;
    margin: 10px;
    padding-right: 35px;
    min-height: 35vh;
    border-radius: 25px;
}
article{
    background-color: lightsalmon;
    margin: 10px;
    padding-right: 35px;
    min-height: 35vh;
    border-radius: 25px;
}
footer{
    background-color: rebeccapurple;
    text-align: center;
}
aside{
    background-color: brown;
    flex: 1;
    padding: 15px;
    border-right: 10px;
    border-radius: 45px;
    text-align: center;
}
    </style>
</head>
<body>
    <header>
        <p><h2>Header</h2></p>
    </header>
<nav>
    <ul>
        <li><a href="#teste1">teste1</a></li>
        <li><a href="#teste2">teste2</a></li>
        <li><a href="#teste3">teste3</a></li>
    </ul>
</nav>
<div class="container">
    <main>
        <h1>Main</h1>
        <section><h2>section</h2>
        <p><h5>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec risus ante, blandit eget sagittis ac, venenatis nec urna. Sed sodales lorem vitae ultricies facilisis. Vestibulum ut porttitor leo. Duis mollis nec dolor id imperdiet. Suspendisse in lacinia est, eget ullamcorper leo. Sed varius vel arcu eu semper. Cras dictum tincidunt nulla, et accumsan arcu placerat vitae. Sed efficitur mauris eget sollicitudin porttitor.<br>Praesent commodo nibh id ultricies iaculis. Donec rhoncus lacinia odio, a sollicitudin augue posuere vel. Duis elit lacus, fermentum et ultricies at, aliquet sit amet purus. Suspendisse commodo, velit non lobortis aliquam, nunc sem auctor urna, sit amet porttitor massa sem in ligula. Integer congue sapien sed sodales dapibus. Aenean molestie elit quis turpis interdum convallis. Nulla varius neque vitae lorem iaculis rutrum. Sed a rhoncus ligula, vel porta dui. Suspendisse potenti. Nunc blandit tellus ut lacus lacinia, ac fringilla eros ornare.</h5></p>
        </section>
        <article><h2>article</h2>
        <p><h5>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec risus ante, blandit eget sagittis ac, venenatis nec urna. Sed sodales lorem vitae ultricies facilisis. Vestibulum ut porttitor leo. Duis mollis nec dolor id imperdiet. Suspendisse in lacinia est, eget ullamcorper leo. Sed varius vel arcu eu semper. Cras dictum tincidunt nulla, et accumsan arcu placerat vitae. Sed efficitur mauris eget sollicitudin porttitor.<br>Praesent commodo nibh id ultricies iaculis. Donec rhoncus lacinia odio, a sollicitudin augue posuere vel. Duis elit lacus, fermentum et ultricies at, aliquet sit amet purus. Suspendisse commodo, velit non lobortis aliquam, nunc sem auctor urna, sit amet porttitor massa sem in ligula. Integer congue sapien sed sodales dapibus. Aenean molestie elit quis turpis interdum convallis. Nulla varius neque vitae lorem iaculis rutrum. Sed a rhoncus ligula, vel porta dui. Suspendisse potenti. Nunc blandit tellus ut lacus lacinia, ac fringilla eros ornare.</h5></p>
        </article>
    </main>

    <aside>
        <h1>aside</h1>
        <p><h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec risus ante, blandit eget sagittis ac, venenatis nec urna. Sed sodales lorem vitae ultricies facilisis. Vestibulum ut porttitor leo. Duis mollis nec dolor id imperdiet. Suspendisse in lacinia est, eget ullamcorper leo. Sed varius vel arcu eu semper. Cras dictum tincidunt nulla, et accumsan arcu placerat vitae. Sed efficitur mauris eget sollicitudin porttitor.<br>Praesent commodo nibh id ultricies iaculis. Donec rhoncus lacinia odio, a sollicitudin augue posuere vel. Duis elit lacus, fermentum et ultricies at, aliquet sit amet purus. Suspendisse commodo, velit non lobortis aliquam, nunc sem auctor urna, sit amet porttitor massa sem in ligula. Integer congue sapien sed sodales dapibus. Aenean molestie elit quis turpis interdum convallis. Nulla varius neque vitae lorem iaculis rutrum. Sed a rhoncus ligula, vel porta dui. Suspendisse potenti. Nunc blandit tellus ut lacus lacinia, ac fringilla eros ornare.<br>Quisque vestibulum finibus lobortis. Nam eleifend egestas massa id pellentesque. Maecenas feugiat, leo sit amet ultricies egestas, metus felis lobortis est, ut sollicitudin ipsum dolor volutpat mauris. Nullam sed aliquet eros, eu elementum ante. Aenean vestibulum egestas turpis, ut bibendum tortor egestas vitae. Vestibulum cursus faucibus risus ac facilisis. Morbi vel venenatis lorem, quis congue lectus. Nam erat eros, cursus nec suscipit at, aliquam ac sapien. Maecenas vitae elit velit.<br>Vivamus risus tellus, vestibulum at semper ac, ullamcorper quis orci. Morbi vitae dignissim massa. Ut ac quam nec ligula aliquam dictum eget sed odio. Morbi auctor sagittis leo, et convallis massa elementum sit amet. Sed malesuada purus quis scelerisque rutrum. Pellentesque tincidunt eros eget tristique consectetur. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Phasellus ipsum nulla, bibendum in venenatis consectetur, rhoncus vel felis. Curabitur id faucibus sem. Duis et semper mi. Mauris lacus lorem, accumsan at venenatis et, commodo ut dui. Aenean fringilla diam non sollicitudin viverra.</h2></p>
    
    </aside>
</div>
<footer>
<p><h2>footer</h2></p>
</footer>
</body>
</html>

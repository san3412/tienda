<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi tienda online</title>
    <link rel="stylesheet" href="paginaprincipal.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a nuestra tienda</h1>
        <nav>
    <ul><li><a href="#productos">productos</a></li>
    <li><a href="#contacto">contacto</a></li></ul>
</nav>
</header>
<section id="banner">
    <h2>ofertas exclusivas</h2>
    <p>descubre nuestras ultimas colecciones y ofertas especiales</p>
    </section>
    <section id="productos">
        <h2>productos destacados</h2>
        <div class="producto">
            <h3>Camisa casual</h3>
            <img src="https://i.pinimg.com/736x/ca/4f/44/ca4f447dfa141ef1a568e4eef4097766.jpg" alt="imagen">
        <p>descripcion breve del producto</p>
        <label for="producto1">$59.0</label>
        <button onclick="Agregaralcarrito('imagen1',59)">agregar al carrito</button>
    <div class="producto">
        <h3>Pantalon jean</h3>
        <img src="https://i.pinimg.com/736x/59/5c/b9/595cb96ae560932a998a872845e2a0df.jpg" alt="imagen2">
        <p>descripcion breve del producto</p>
        <label for="producto4">$89.0</label>
    <button onclick="Agregaralcarrito('imagen2',89)">agregar al carrito </button>
    </div>
    <div class="producto">
        <h3>polo</h3>
        <img src="https://i.pinimg.com/564x/9d/74/da/9d74da069f3e619da9694668b5c41246.jpg" alt="imagen3">
    <p>descripcion breve del producto</p>
    <label for="producto3">$57.0</label>
    <button onclick="Agregaralcarrito('imagen3',57)">agregar al carrito </button>
</div>
<div class="producto">
    <h3>Pantalon negro</h3>
    <img src="https://i.pinimg.com/736x/39/ac/d1/39acd1e7faca30c76a5b11cabe9eddcb.jpg" alt="imagen4">
    <p>descripcion breve del producto</p>
    <label for="producto4">$67.0</label>
    <button onclick="Agregaralcarrito('imagen4',67)">agregar al carrito ></button>
</div>
    

</script>
    <section id="contacto">
        <h2>contactanos</h2>
        <p>email: tiendaonline@gmail.com</p>
        <p>telefono : 999999999</p>
    </section>
    <div class="carrito" id="carrito">
        <h2>carrito de compras</h2></div>
        <ul id="totalPrecio">TOTAL:$0.00</ul>

    <footer>
        <p>&copy; 2024 tu tienda online.todos los derechos reservados</p>
    </footer>
    
</body>
</html>

body{
    font-family: 'Times New Roman', Times, serif;
    margin: 0;
    padding: 0;
}
header{
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-align: center;
}
nav ul{
    list-style-type: none;
padding: 0;
}
nav ul li{
    display: inline;
    margin: O 15px;
}
nav ul li a{
    color: #fff;
    text-decoration: none;
}
#banner{
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
}
#productos {
    padding: 20px;
}
#producto{
    border: 1px solid #ccc;
    margin: 10px 0;
    padding: 10px;
}
footer{
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
button{
    background-color: #333;
    color: #ccc;
    text-align: center;
    padding: 10px;
}
.carrito {
    background-color: #333;
    color: #ccc;
    border: 1px solid #ffffff;
    border-radius: 10px;
    padding: 20px;
    margin: 20px;
    max-width: 300px;
    position: fixed;
    right: 25px;
    top: 100px;
    box-shadow: O O 10px rgba(O,O,O,0.1)
}
#listaCarrito {
    list-style: none;
    padding: O;
}

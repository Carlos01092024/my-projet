# my-projet<!DOCTYPE html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CineMax - Películas Online</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">CineMax</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#peliculas">Películas</a></li>
                    <li><a href="#series">Series</a></li>
                    <li><a href="#favoritos">Favoritos</a></li>
                </ul>
            </nav>
            <div class="search-container">
                <input type="text" placeholder="Buscar películas..." id="search-input">
                <button id="search-btn"><i class="fas fa-search"></i></button>
            </div>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="hero-content">
                <h2>Disfruta de las mejores películas</h2>
                <p>Miles de títulos a un solo clic</p>
                <button class="cta-btn">Empieza ahora</button>
            </div>
        </section>

        <section id="featured-movies" class="container">
            <h2>Películas Destacadas</h2>
            <div class="movies-grid" id="movies-container">
                <!-- Las películas se cargarán aquí con JavaScript -->
            </div>
        </section>

        <section id="categories" class="container">
            <h2>Categorías</h2>
            <div class="categories-list">
                <button class="category-btn active">Todas</button>
                <button class="category-btn">Acción</button>
                <button class="category-btn">Comedia</button>
                <button class="category-btn">Drama</button>
                <button class="category-btn">Ciencia Ficción</button>
                <button class="category-btn">Terror</button>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2023 CineMax. Todos los derechos reservados.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>

    <div id="movie-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn">&times;</span>
            <div id="modal-movie-details">
                <!-- Los detalles de la película se cargarán aquí -->
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

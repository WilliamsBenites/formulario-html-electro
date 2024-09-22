## Navegacion
1.Usando la etiqueta al empezar la pagina web con las opciones pricipales
```<nav>
            <ul>
                <li><a href="">Inicio</a></li>
                <li><a href="">Promciones</a></li>
                <li><a href="">Combos</a></li>
                <li><a href="">ProductosconRegalo</a></li>
            </ul>          
            <details>
                <summary>Todas las categorias</summary>
                <ul>
                    <li><a href="">Tecnologia</a></li>
                    <li><a href="">ElectroHogar</a></li>
                    <li><a href="">Hogar</a></li>
                </ul>
            </details>         
        </nav>
```
## IMAGENES
1. Varias imagenes para darle la animacion de un carrucel
2. usando tambien botenes "Derecha izquierda"
```<img src="./img/electro.jpg" alt="carrucel">
                <img src="./img/electro.jpg" alt="carrucel">
                <img src="./img/electro.jpg" alt="carrucel">
                <img src="./img/electro.jpg" alt="carrucel">
                <div>
                    <button type="button">
                        <img src="./img/flecha-izquierda.png" alt="flecha-izquierda">
                    </button>
                    <button type="button">
                        <img src="./img/flecha-derecha.png" alt="flecha-derecha">
                    </button>
```
## SECTION Y ARTICLES
1. Un total de 3 "section" y 4 "article" para maquetar informacion o agrupar elementos 
2. Tambien etiquetas "main" para seńalar el contenido pricipal

## Carpeta
1. Se creo una carpeta donde esta el enlace de "Registro" para el Formulario

## Formulario 
1. Se uso etiquetas para el formulario dividas con la etiqueta "Article"
2. eh iniciando todo con la etiqueta "form"
```<main>
        <article>
            <header><h2>REGISTRATE</h2></header>
            <form action="">
                <div>
                    <label for="name">Nombres(s)</label>
                    <input type="text" id="name" maxlength="20" placeholder="Nombre completo" required >
                </div>
                <br>
                <div>
                    <label for="lastname">Apellidos</label>
                    <input type="text" id="lastname" maxlength="30" required placeholder="Apellido completo">
                </div>
                <br>
                <div>
                    <label for="nac">Fecha de nacimiento</label>
                    <input type="date" id="nac" required>
                </div>
                <br>
                <div>
                    <label for="gen">Genero</label>
                    <select id="gen">
                        <option value="">Seleccionar genero</option>
                        <option value="hombre">Hombre</option>
                        <option value="mujer">Mujer</option>
                    </select>   
                </div>
                <br>
                <div>
                    <label for="passwore">Contraseña</label>
                    <input type="password" id="password" maxlength="8" placeholder="Contraseña" required>
                    <small>Igresa tu contraseña privada</small>
                </div>
                <br>
                <div>
                    <label for="passwore">Repite tu contraseña</label>
                    <input type="password" id="password" maxlength="8" placeholder="Repite tu Contraseña" required>
                    <small>Vuelve a ingresar tu contraseña</small>
                </div>
                <br>
                <p>
                    <small>¿Ya tienes una cuenta?<a href="">Inicar sension</a></small>
                </p>
                <button type="submit">Ingresar</button>
                
            </form>
        </article>

    </main>

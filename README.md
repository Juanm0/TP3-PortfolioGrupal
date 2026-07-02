## 3. Trabajo Practico 3 [TP3]

¡Hola!

Les comparto las consignas del TP N° 3, el desafío no es solo técnico, sino también de coordinación. Vamos a construir un Portfolio Grupal, una única web que nos presente a todos como equipo.

Cada uno de ustedes será responsable de su propia página de presentación (NombreApellido.html), pero el sitio final debe verse como uno solo. 

Tengan en cuenta que cada página debe permitir ir al compañero anterior, al siguiente o volver al inicio. 

¡Para esto es vital que se listen por orden alfabético que les dejo abajo ↓↓ !
Camila Barraza
Nahuel Figueroa
Natalia Gomez
Lázaro Janco
Solange Konrad
Federico Lopez
Elias Reinoso
Juan Navarro
Romero Milagros
Luciano Rossi
Esta ordenada por Apellido, pero pongan Nombre Apellido así no queda tan formal 😁

En las consignas les especifiqué el esquema de carpetas a respetar para que los enlaces no se rompan al unificar el proyecto.

¡Cualquier duda, nos vemos en el laboratorio!


[Ver consigna TP N° 3 (PDF)](./pdf/Portfolio-Grupal.pdf)
![gif-pdf-consignas](./pdf/Portfolio-Grupal.gif)

.navarro {
    --bg-color-radial: radial-gradient(circle, rgba(238, 174, 202, 1) 0%, rgba(148, 187, 233, 1) 100%);
    --text-main: #e2e8f0;
    --text-main: #1f2937;
    --card-bg: #6b447c;
    --color-primario: #5ad7db;
    --color-secundario: #3F5EFB;
}

.navarro img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
    margin: 1rem auto;
    border: 2px solid #334155;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.navarro img:hover {
    transform: scale(1.02);
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
    border-color: var(--color-primario);
}

.navarro section {
    max-width: 900px;
    margin: 2rem auto;
    padding: 2rem 1.5rem;

    background-color: var(--card-bg);
    border-radius: 12px;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.2);
    border: 1px solid #334155;
}

.navarro p {
    margin-bottom: 1rem;
}

.navarro strong {
    color: var(--color-primario);
    font-size: 1.1rem;
    display: block;
    margin-top: 1.5rem;
    margin-bottom: 0.5rem;
    border-left: 4px solid var(--color-primario);
    padding-left: 10px;
}

.navarro h1 {
    font-family: var(--font-heading);
    color: var(--color-primario);
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    /*  text-shadow: 0 0 10px rgba(56, 189, 248, 0.3); */
}

.navarro h2 {
    color: var(--color-secundario);
    text-align: center;
    font-size: 1.2rem;
    font-weight: normal;
    margin-bottom: 2rem;
    letter-spacing: 1px;
    text-transform: uppercase;
}

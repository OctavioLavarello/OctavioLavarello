# ¡Hola! 👋 Soy Octavio Eneas

## Acerca de mí

Soy Full-Dtack Developer aprendiendo una gran variedad de tecnologías y lenguajes de programación. 
Me encanta crear aplicaciones web y soluciones tecnológicas innovadoras.

- 🌐 Full-Stack Developer con experiencia en tecnologías como TypeScript, React, Redux, Node.js, Express, Sequelice, PostgreSQL.
- 💛 Graduado del bootcamp Henry.
- 🚀 Siempre aprendiendo y explorando nuevas tecnologías y enfoques.

## Mis Habilidades

- Front-end: HTML, CSS, Tailwind CSS, TypeScript, React, Redux
- Back-end: Node.js, Express, Sequelize, PostgreSQL

## Proyectos Destacados

- [Henry_Countries](https://github.com/OctavioLavarello/Countries_Lavarello): Mi proyecto individual de busqueda de paises. Utilizando tecnologias aprendidas en el bootcamp de henry: HTML, CSS, JavaScript, React, Redux, Node.js, Express, Sequelize, PostgreSQL. 
- [Craftbeer](https://github.com/OctavioLavarello/CraftBeer): Pagina como punto de encuentro entre marcas de cervezas artesanales y amantes de esta exquisita bebida. Proyecto Final y grupal de henry donde conoci a mis amigos de front.

## Contacto

- [LinkedIn](https://www.linkedin.com/in/octavio-lavarello-175342271/)
- [Intagram](https://www.instagram.com/octavio_lavarello/)

## Juguemos un Truco 🧉

```ts
class Jugador {
    nombre: string;
    mano: number;

    constructor(nombre: string) {
        this.nombre = nombre;
        this.mano = 0;
    }
    decir(mensaje: string) {
        console.log(`${this.nombre}: ${mensaje}`);
    }
}
function jugarTruco() {
    const jugador1 = new Jugador("Vos");
    const jugador2 = new Jugador("Yo");

    jugador1.decir("Falta Envido");
    jugador2.mano = 33;
    jugador2.decir(`quieroooo, ${jugador2.mano}`);
}
jugarTruco();

# Pokémon
## ¿Qué es Pokémon?
**Pokémon** es una franquicia de medios que originalmente comenzó como un videojuego RPG, pero debido a su popularidad ha logrado expandirse a otros medios de entretenimiento como series de televisión, películas, juegos de cartas, ropa, entre otros, convirtiéndose en una marca que es reconocida en el mercado mundial.  
El término **Pokémon** es la contracción de ***Pocket Monsters*** ("*monstruos de bolsillo*"). Los pokémon son unos monstruos que se pueden entrenar para hacerlos más fuertes (*y en muchos casos evolucionan, cambiando de aspecto, mejorando su fuerza y en algunos casos cambian de tipo*) y realizar combates con ellos, y se pueden capturar en **Poke Balls**.

## Ejemplos de Pokémons
Ahora mostraré los tres ejemplos de los pokémons que incluí en la anterior práctica

## [Charizard](https://www.wikidex.net/wiki/Charizard) 
![Imagen_de_Charizard](https://images.wikidexcdn.net/mwuploads/wikidex/thumb/9/95/latest/20160817212623/Charizard.png/260px-Charizard.png)

### Descripción
**Charizard** es la evolución final de **Charmander**. Es un pokémon introducido en la primera generación. Su nombre proviene de las palabras inglesas *char* (carbonizar, incinerar) y *lizard* (lagarto)  
Es de tipo **fuego** y **volador**.  
Es un **pokémon inicial** de la primera generación que te regalan al principio del juego y solo puede ser obtenido de esta manera.

### Estadísticas de combate 

>Las estadísticas funcionan por niveles, es decir, a medida que combates con un pokémon este sube de nivel aumentando sus estadísticas. Yo pondré las estadísticas máximas que puede llegar a tener.

* **Vida**: 360
* **Ataque**: 293
* **Defensa**: 280
* **At. especial**: 348
* **Def. especial**: 295
* **Velocidad**: 328

## [Tropius](https://www.wikidex.net/wiki/Tropius)
![Imagen_de_Tropius](https://images.wikidexcdn.net/mwuploads/wikidex/thumb/c/cd/latest/20210202083827/Tropius.png/260px-Tropius.png)
### Descripción
**Tropius** no dispone de fases evolutivas. Es un pokémon introducido en la tercera generación. Su nombre proviene de las palabras inglesas *tropical* (tropical) y *saurus* (saurio). Es una combinación de un diplodocus y una palmera platanera.
Es de tipo **planta** y **volador**.
Es un pokémon salvaje que se puede encontrar en la **ruta 119**. 

### Estadísticas de combate
* **Vida**: 402
* **Ataque**: 258
* **Defensa**: 291
* **At. especial**: 267
* **Def. especial**: 300
* **Velocidad**: 221

## [Shinx](https://www.wikidex.net/wiki/Shinx)
![Imagen_de_Shinx](https://images.wikidexcdn.net/mwuploads/wikidex/thumb/a/a5/latest/20200720111519/Shinx.png/260px-Shinx.png)
### Descripción 
**Shinx** es el primero de su etapa evolutiva (tiene 2 evoluciones). Es un pokémon introducido en la cuarta generación. Su nombre proviene de las palabras inglesas *shine* (brillo) y *linx* (lince).  
Es de tipo eléctrico.  
Es un pokémon salvaje que puede encontrarse en las **rutas 202**, **203**, **204** y en la **Forja Fuego**.

### Estadísticas de combate
* **Vida**: 294
* **Ataque**: 251
* **Defensa**: 183
* **At. especial**: 196
* **Def. especial**: 183
* **Velocidad**: 207

### Bloques de código json y yaml
#### JSON
```json
{"pokemons":
    [
        {
            "pokedex": "0006",
            "nombre": "charizard",
            "generacion": "I",
            "tipos": ["fuego", "volador"],
            "stats":{"vida": 360, "ataque": 293, "defensa": 280, "at_especial": 348, "def_especial": 295, "velocidad": 328},
            "localizacion": null,
            "evolucion": true
        },
        {
            "pokedex": "0357",
            "nombre": "tropius",
            "generacion": "III",
            "tipos": ["planta", "volador"],
            "stats": {"vida": 402, "ataque": 258, "defensa": 291, "at_especial": 267, "def_especial":300, "velocidad": 221},
            "localizacion": ["ruta 119"],
            "evolucion": false
        },
        {
            "pokedex": "0403",
            "nombre": "shinx",
            "generacion": "IV",
            "tipos": ["electrico"],
            "stats": {"vida": 294, "ataque": 251, "defensa": 183, "at_especial": 196, "def_especial": 183, "velocidad": 207},
            "localizacion": ["ruta 202", "ruta 203", "ruta 204", "Forja_Fuego"],
            "evolucion": true
        }
    ]
}

```
#### YAML
```yaml
pokemons:
  -
    pokedex: "0006"
    nombre: charizard
    generacion: I
    tipos:
      - fuego 
      - volador
    stats:
      vida: 360 
      ataque: 293
      defensa: 280
      at_especial: 348
      def_especial: 295
      velocidad: 328
    localizacion: null
    evolucion: true
  -
    pokedex: "0357"
    nombre: tropius
    generacion: III
    tipos:
      - planta
      - volador
    stats: 
      vida: 402 
      ataque: 258 
      defensa: 291 
      at_especial: 267 
      def_especial: 300 
      velocidad: 221
    localizacion: 
      - ruta 119
    evolucion: false
  -
    pokedex: "0403"
    nombre: shinx
    generacion: IV
    tipos: 
      - electrico
    stats: 
      vida: 294  
      ataque: 251 
      defensa: 183
      at_especial: 196  
      def_especial: 183
      velocidad: 207
    localizacion: 
      - ruta 202
      - ruta 203
      - ruta 204
      - Forja_Fuego
    evolucion: true

```

<h3 align="center">Procesamiento de datos plaforma YELP</h3>

<details open="open">
  <summary>Tabla de contenidos</summary>
  <ol>
    <li>
      <a href="#about-the-project">Sobre el proyecto</a>
      <ul>
        <li><a href="#Construido con">Construido con:</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Empezando</a>
      <ul>
        <li><a href="#prerequisites">Prerrequisitos</a></li>
        <li><a href="#installation">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el proyecto


El proyecto es un software que pueda extraer, transformar y cargar los datos de los negocios de la plataforma YELP.


## Requerimientos: 

<ol>
<li>En primer lugar, descubrir cómo YELP presenta los datos delos negociosy modelar esta estructura de datos para que sepamos cómo interactuar con ella. YELP parece tener el concepto de business, event, category, etc. y debemos descubrir y documentar estos esquemas y relaciones de datos. (Pueden usar esquemas, diagramas, según se considere necesario)</li>
<br/>
<li>En segundo lugar, debemos desarrollar una forma de extraer la información de YELP de los restaurantes de la cuidad de Asheville.</li>
<br/>
<li>Posteriormente se debe extraer los datos del restaurante por el ID del restaurante. </li>
<br/>

<li>Se debe procesar los datos para que sea almacenada en una tabla donde se muestrela información del restaurante. </li>
<br/>

<li>Los datos extraídos deben ser en formato jsony deben ser subidos a un repositorio en Github al igual que la documentación que se debe generar del punto 1.</li>
</ol>


## Construido con:
En esta seccion se especifica las herramientas tecnicas con las que se realizo el proyecto

* [Python](https://www.python.org/)
* [Jupyter](https://jupyter.org/)
* [COLAB](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)

### API Consultado:
En este proyecto se utilizo el API de la plataforma [YELP](https://www.yelp.com/developers/documentation/v3), esta plataforma ofrece una serie de endpoints para consultar datos estructurados en JSON. 

Dejo los links de la documentacion abajo

* [BUSCAR](https://www.yelp.com/developers/documentation/v3/business_search)

* [BUSCAR POR_ID](https://www.yelp.com/developers/documentation/v3/business)

Los datos de los endpoints de arriba son extraidos en forma JSON, y tienen la siguiente estructura:

<a href="https://github.com/othneildrew/Best-README-Template">
   <img src="Esquema_API/Yelp_Estructura.jpeg" alt="Logo" width="100%" height="auto">
</a>
</ol>




## Estructura de los Folders:

Nuestro proyecto tiene la siguiente estructura de folders:

```
|-- Python_Yelp_Request_Data_Cleaning
|   |-- APP
|   |   |--Python_Yelp_Request_Data_Cleaning.ipynb
|   |   |--token.txt
|   |-- Datos_Procesados_CSV
|   |   |--Restaurantes.csv
|   |   |--Restaurante Corner Kitchen.csv
|   |-- Datos_Sin_Procesar_JSON
|   |   |-- restaurante 3nu2FbuN__5LqOaGDRihTQ.json
|   |   |-- Restaurantes.json
|   |-- Esquema_API
|   |-- README.md
```

## Nomenclatura:

La nomenclatura utilizada para los folders es [SNAKE_CASE](https://en.wikipedia.org/wiki/Snake_case)
La nomenclatura utilizada para los files es [Pascal CASE](https://www.theserverside.com/definition/Pascal-case)


<!-- GETTING STARTED -->
## Empezando

El proyecto en realidad corre sobre un jupyter notebook en un Google Colab, preferiblemente se debe de correr en esa plataforma. sin embargo tambien se puede correr desde un ambiente local utilizando ANACONDA. 


### Requisitos

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Instalación

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```



<!-- USAGE EXAMPLES -->
## Uso

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- CONTRIBUTING -->
## Contruibuir

Las contribuciones son lo que hacen que la comunidad de código abierto sea un lugar tan increíble para aprender, inspirar y crear. Cualquier contribución que haga es ** muy apreciada **.

1. Fork the Project
2. Cree un branch con la siguiente estructura: (`git checkout -b feature/AmazingFeature`)
3. Haga comentarios de sus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Haga push del branch (`git push origin feature/AmazingFeature`)
5. Abra un Pull Request


<!-- CONTACT -->
## Contact

William Aguilar - [@Github](https://github.com/william2215) - wil-19-60@live.com

Project Link: [https://github.com/william2215/Python_Yelp_Request_Data_Cleaning/](https://github.com/william2215/Python_Yelp_Request_Data_Cleaning/)






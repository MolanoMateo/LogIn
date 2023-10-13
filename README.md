Ejercicio de LogIn en Angular y .NET

Explicación:
El Login de una pagina es importante debido a que es el filtro que permite autentificar quien usa la pagina, así tambien brinda seguridad y privacidad a los datos y finalmente nos permite filtrar el contenido dependiendo de los gustos o roles que determinado usuario tenga.
Este proyecto se encuentra desarrollado en ANGULAR principalmente para el FRONTEND y para su logica .NET donde en el futuro se conectará a la base de datos, unicamente se valida que el usuario se autentifique con las credenciales adecuadas y de lo contrario no se mostrará la información de inicio

Diagrama del sistema: https://udlaec-my.sharepoint.com/:i:/g/personal/mateo_molano_udla_edu_ec/EVCQ29p39t1CmQnuczpczf8B8eV_hGH_2WIcvkjQktNQNA?e=dBYbd9

El sistema del login al no tener tantas funcionalidades es facil de comprender, existe el usuario y los metodos a los que tiene acceso a travez del front end, por otra parte existe el cliente o pagina web donde tenemos toda la logica del sistema, la validacion del formato y el tipo de los datos que el usuario ingresa, lo realizamos tanto en el front end como en el back end. Por ultimo tenemos la conexion a la base de datos en firebase que nos permite mantener la persistencia de los datos, con este flujo de información comprobamos que el usuario no pueda acceder a la pagina de inicio sin que antes autentifique su identidad con sus credenciales.

Credenciales quemadas:
    Mail: mateo.molano@udla.edu.ec
    password: 1234

Instalación y ejecución de programa:
npm install
ng serve
http://localhost:4200
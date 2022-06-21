# AZ900-WebApp[Wordpress]

"App Service" es un servicio que se utiliza para las aplicaciones de grado empresarial este servivcio es un servicio web.

Guía para crear una Web App dentro de Azure utilizando Wordpress.

Lo primero que debemo hacer, es dirigirnos al portal de Azure.

## Paso 1
En en la vista de Home nos posicionamos en el buscador que se enceuntra en la parte superior y escribimos "wordpress" y seleccionamos la primer opción.

![1](https://user-images.githubusercontent.com/99112892/174724706-daf67cca-0bfb-4abc-b27d-e65722eea6d1.png)

## Paso 2
### Pestaña:Datos básicos
- Nos aseguramos de que la suscripción es de tipo 'student'.
- Creamos un nuevo grupo de recursos, el cual sería un folder donde vamos a guardar nuestra aplicación web dentro de la nube, lo nombramos como: lab03-dr.
- En la Región para esta ocasion utilizamos East US.
- Le damos un nombre a nuestra aplicación web, en este caso la nombro: lab003--dr.
- Para el sistema operativo seleccionamos "Linux" con su plan de hospedaje Básico.

![2](https://user-images.githubusercontent.com/99112892/174724839-6801d337-e485-4bca-b8b5-b5d8e8129fd3.png)

- En el nombre de uruario del administrador nos arroja uno automaticamente pero es mejor cambiarlo por uno que recordemos.
- Ponemos una contraseña y la confirmamos.
- Le damos click en el boton "Avanzados" para acceder a esa sección.

![3](https://user-images.githubusercontent.com/99112892/174724924-af61e1b5-f31e-4bc4-9297-198162dd2613.png)

### Pestaña:Avanzados(Advanced)
- Para el idioma del sitio ocupamos English (United States).
- La distribución de contenido la deshabilitamos.
- Le damos click en el boton "Etiquetas" para acceder a esa sección.

![4](https://user-images.githubusercontent.com/99112892/174725094-b708ccb9-08b1-4209-a386-5da7d1c53ce9.png)

### Pestaña:Etiquetas(Tags)
Las etiquetas nos sirven para cuando hay muchas personas trabajando dentro de una organización,
es importante saber quien esta subiendo que cambios. 

- En el campo nombre es muy usual poner: CreatedBy y para el campo valor ponemos por quien fue 
creado.
- Agregamos otra etiqueta con Nombre:Area y Valor:Rivan.
- Finalizamos con una ultima Nombre:Ciclo y Valor:7maEd.
- Le damos click en el boton "Revisar y crear" y despues de que se analiza y aprueba la implementación le damos en crear.

![5](https://user-images.githubusercontent.com/99112892/174725230-58a7bbda-5c90-458a-8029-97b9188941b2.png)

- Esperaremos la implementación, puede tardar alrededor de 5 minutos.

![6](https://user-images.githubusercontent.com/99112892/174725303-f65cb003-9516-4b99-b895-3a27d8fc0bff.png)

- Lista la implementación, hacemos click en "ir al recurso".

![7](https://user-images.githubusercontent.com/99112892/174725348-330dca55-334b-488f-8fe9-0a708ec240c2.png)


## Paso 3
- En la información esencial de nuestro "lab03--dr" vamos a dirigirnos en donde dice URL, esto nos instalara de forma automatica Wordpres, es decir nos va instalar dentro de nuestra aplicación web un sistema que nos permita poder trabajar con las aplicaciones Web.

![8](https://user-images.githubusercontent.com/99112892/174725548-8d90491c-1369-406b-a647-b3f13e5d614b.png)

- Despues de la intalación exitosa, nos manda a esta página.

![9](https://user-images.githubusercontent.com/99112892/174725625-f51c2d10-fb31-45aa-a8e6-cbf71aa1ff0b.png)

## Paso 4
- Nos dirigimos a la dirección de la página y nos posicionamos al final de la misma, donde agregaremos "/wp-admin" , esto es para que nos mande al login de wordpress.

![10](https://user-images.githubusercontent.com/99112892/174725697-21e8d491-b826-4eb4-a59a-d4f3b4ee4d1a.png)

## Paso 5
- Nos pedira usuario y contraseña, ingresaremos los datos que utilizamos al crear nuestro "lab03--dr".

![11](https://user-images.githubusercontent.com/99112892/174725785-25043641-a6e7-40fc-8973-de0d74bae8c6.png)

- Tendremos acceso a la siguiente interfaz.

![12](https://user-images.githubusercontent.com/99112892/174725843-0019a47b-b509-41cd-8216-477eda86cdae.png)

## Paso 6
- En la pestaña "Appearance" podemos elegir algún tema para nuestra web app.

![13](https://user-images.githubusercontent.com/99112892/174725915-fb74c5b6-f4b1-4637-9dbf-971e1555a519.png)

- Lo instalamos.

![14](https://user-images.githubusercontent.com/99112892/174725972-4fc91098-5c37-4675-a109-601bda9cc4f0.png)

- Lo activamos y ahora solo tenemos que editarlo a nuestro gusto para posteriormente publicarlo.

![15](https://user-images.githubusercontent.com/99112892/174726009-e0d62c59-0c63-4a00-a4c6-7ef1bf5ed372.png)

## Paso 7
- Para asegurarnos de que los cambios se han efectuado, solo tenemos que volver a ingresar a la URL de la implementación y lo verificamos.

![16](https://user-images.githubusercontent.com/99112892/174726090-8916b52c-22ba-40ab-9b3c-449133591128.png)




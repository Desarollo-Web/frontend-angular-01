# Tutorial Angular material

## Prerrequisitos
- NodeJs en su versión más actual.

## Objetivo
- Crear una aplicación Web utilizando Angular Material

## Dependencias a instalar
- npm install -g typescript @angular/cli

## Instrucciones
1. Crear un nuevo proyecto llamadao ng new angular-tutorial
   ~~~
   Would you like to add Angular routing?: Yes
   Which stylesheet format would you like to use?: SCSS
   ~~~
3. Cambiarse al directorio de trabajo.
    ~~~
    cd angular-tutorial
    ~~~
4.  Levantar el servidor
    ~~~
    ng serve -o
    ~~~
5.   Ingresar a la URL [localhost](http://localhost:4200)

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/dd1fe050-c0f1-4b76-9881-28cf89462f6f)

### Instalar Angular Material
Ingresar el siguiente comando
    ~~~
      ng add @angular/material
    ~~~
    
### Agregar módulo para manejar todo lo referente a componentes Angular Material
Se agrega instrucción con la bander --flat para no crear carpeta
~~~
    ng g m material --flat
~~~
Modificar el archivo para organizar componentes Angular Material

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/5a42060c-c310-49a2-b5d7-ed5cd47eb190)

En el archivo app.module.ts agregar MaterialModule en la sección de los imports

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/cb45720b-9b1e-49de-bce4-11be19fc667f)

## Agregar pantalla de Login
Crear módulo Home 
~~~
  ng g m pages/home -m=app --route home
~~~

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/180f3eb1-bacf-428e-9612-a572475608fe)

Crear módulo de inicio de sesión
ng g m pages/login -m=app --route login

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/3329bf2e-0330-4672-90e6-30161289a1f3)


Crear componente Header
ng g c shared/components/header -m=app

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/45e76df4-5710-46df-8380-21b26b1dbc92)

ng g c shared/components/header -m=app

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/01711497-59e9-469b-b069-3a57b98e08c4)


Modificar archivo app.component.html

![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/83560611-ac98-4647-94da-f6835ddf8082)

Observar la página
![imagen](https://github.com/Desarollo-Web/frontend-angular-01/assets/8560750/b2125fd4-55b5-43d7-901e-bc139132c69c)




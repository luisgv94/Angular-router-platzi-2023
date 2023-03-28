# MyStoreRouter

This project was generated with [Angular CLI](https://github.com/angular/angular-cli)

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

API DEL CURSO: https://damp-spire-59848.herokuapp.com/docs

# Modulos de Angular

https://platzi.com/clases/2487-angular-modular/41193-programacion-modular/

## app.module.ts

@NgModule({
imports: [], // Imports de otros módulos.
declarations: [], // Imports de los componentes del módulo.
exports: [], // Exports de componentes u otros para ser utilizados en otros módulos.
providers: [], // Inyección de servicios.
bootstrap: [] // Import del componente principal de la aplicación.
})
export class AppModule { }

Partes del NgModule:
Components, directive, interceptors, models, pages, pipes, services

Root Module: modulo por defecto de angluar
Core Module: son servicios que pueden ser usados en diferentes módulos y componentes recordar que los servicios que se inyecta en el provideIn : ‘root’ se puede usar en cualquier parte.
Routing Module: son módulos especiales que declaran un enrutamiento de la aplicación
Feature Domain Module:son los módulos específicos del negocio
Shared Module:Se usan para componentes pipes y directivas que se quieran usar en toda la aplicación

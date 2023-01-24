# Tipos de Route Guards

### CanActivate
- Decide se uma rota(ou componente) pode ser ativada, ex. como um sistema de login;
### CanDeactivate 
- Decide se um usuário pode navegar para longe de uma rota (ou componente), ex. Solicitar a confirmação de alterações pendentes;
### CanLoad
- Verifica se pode ou não carregar o módulo específico. Geralmente é usado com o Lazy-Load;
### CanActivateChild
- É semelhante a CanActivate, mas se aplica a rotas aninhadas (rotas filhas).

# Resumo da aula de Route Guards

Os Routes Guards do Angula nos permitem controlar a acessibilidade de uma rota com base nas condicoes forncedias na implementação de um serviço.
Basicamente com os Guards é possível controlar o acesso autorizado de uma determinada rota ou adicionar alguma outra lógica para acesso.

# Angular Standard

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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

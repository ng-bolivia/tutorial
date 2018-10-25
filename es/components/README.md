# Componentes

> Para definir un componentes tomaremos como referencia el post [Base para una aplicación Angular](https://academia-binaria.com/base-aplicacion-angular/) de Academia Binaria y el libro: Angular 4 desde cero - Pedro Jiménez Castela

Los componentes son los bloques básicos de construcción de las páginas web en Angular. Contienen una parte visual en html (la Vista) y una funcional en Typescript (el Controlador).

Un componente estará compuesto por tres bloques de código:

**1. Imports**: Las sentencias de importación de los diferentes elementos que
empleará el componente.

**2. Decorador _@Component_**: Con al menos, los siguientes metadatos:

  * **Selector**: Que define la etiqueta html donde se renderiza el componente.

  * **Template**: El archivo html con la vista del componente.

  * **Style**: Con el archivo CSS con los de estilos del componente.

**3. Export de la Clase**: Definición y exportación de la clase con la lógica del componente.

```typescript
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})

export class AppComponent {
  title = 'app';
}
```

## Generación de componentes
Una de las funcionalidades de Angular CLI es la de generar los archivos de, entre otros, un componente, evitándonos tener que escribir el código.

Para crear nuevos componentes vamos a usar de nuevo el CLI con su comando `ng generate component` 
o abreviadamente `ng g c`, por lo que la sintaxis seria:
```sh
ng generate component <nombredelcomponente>
```
Entonces para crear nuestro componente primero nos situamos en alguna consola o terminal en el directorio raíz del proyecto y ejecutamos:
```sh
ng generate component mi-componente-de-prueba
```
> La guía de estilos de Angular nos recomienda separar las palabras con guiones (`-`)

Y listo, acabas de crear tu primer componente en Angular, ya puedes ir modificando los archivos para familiarizarte un poco. :wink:

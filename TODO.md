# Handle Localstorage

## Herramientas para desarrollo de la librería

- [ ] Git (Obligatorio)
- [ ] Instalable desde NPM (Obligatorio)
- [ ] Typescript (Opcional pero recomendado)
- [ ] Linter (Opcional pero recomendado)
- [ ] Testing (Recomendado)

## Requisitos

- [ ] Crear almacenes según se necesite
- [ ] Borrar un almacén (Gestionar si está vacío o no)
- [ ] Obtener todos los datos guardados de un almacén
- [ ] Borrar todos los datos de un almacén
- [ ] Guardar un dato en un almacén
- [ ] Obtener un dato de un almacén
- [ ] Borrar un dato de un almacén
- [ ] Editar un dato de un almacén
- [ ] Ordenar los datos de distintas maneras
  - [ ] Orden cronológico
  - [ ] Orden cronológico inverso
  - [ ] De forma aleatoria
  - [ ] En base a un valor especificado por el usuario

## Esquema

- Crear funciones para manejo de arrays, ordenamiento de items y CRUD de items de arrays.
- Crear una clase nombrada `HandleLocalstorage` que contenga todos los métodos necesarios para un CRUD de almacenes.

```js
class HandleLocalstorage {

  constructor(storeName) {
    this.storeName = storeName
  }

  createItem(item) { /** Do something */ }

  readItem(item) { /** Do something */ }

  updateItem(item) { /** Do something */ }

  deleteItem(item) { /** Do something */ }
}

const storeName = new handleLocalstorage('store-name')

storeName.createItem({ storeItem: 'store-item' })
storeName.readItem({ storeItem: 'store-item' })
storeName.updateItem({ storeItem: 'store-item' })
storeName.deleteItem({ storeItem: 'store-item' })
```

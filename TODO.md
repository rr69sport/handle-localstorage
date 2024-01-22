# Handle Localstorage

## Tools for library development

- [x] Git (Required)
- [x] Typescript (Optional but recommended)
- [x] Linter (Optional but recommended)
- [ ] Testing (Recommended)
- [ ] Installable from NPM (Required)

## Requirements

- [ ] Be able to create stores as needed
- [ ] Delete a store (Manage whether it is empty or not)
- [ ] Get all saved data from a store
- [ ] Delete all data from a store
- [ ] Save a data in a store
- [ ] Obtain data from a store
- [ ] Delete data from a store
- [ ] Edit a store data
- [ ] Sort data in different ways
  - [ ] Chronological order
  - [ ] Reverse chronological order
  - [ ] Randomly
  - [ ] Based on a user-specified value

## Scheme

- Create functions for array management, item ordering and CRUD of array items.
- Create a class named `HandleLocalstorage` that contains all the methods necessary for a warehouse CRUD.

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

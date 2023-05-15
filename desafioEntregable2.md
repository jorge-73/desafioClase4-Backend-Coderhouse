# Funcionalidades principales:
 La clase ProductManager administra una lista de productos almacenados en un archivo JSON. Proporciona métodos para agregar, actualizar, eliminar y recuperar productos del archivo. También valida los productos antes de agregarlos o actualizarlos para garantizar que todos los campos obligatorios estén presentes y que el código del producto sea único.

## Métodos:
 #validateProduct: valida que todos los campos obligatorios estén presentes y que el 'code' del producto sea único.
 getProducts: lee el archivo JSON y devuelve la lista de productos.
 #generateId: genera una nueva identificación para un nuevo producto en función de la última identificación en la lista.
 addProduct: agrega un nuevo producto a la lista después de validarlo.
 getProductsById: recupera un producto de la lista en función de su ID.
 updateProduct: actualiza un producto en la lista en función de su ID y un conjunto de nuevos valores después de validarlos.
 deleteProduct: elimina un producto de la lista en función de su ID.

 ## Campos:
#path: la ruta al archivo JSON que contiene la lista de productos.
#format: el formato del archivo (utf-8).
products: la lista de productos almacenados en la memoria después de ser leídos del archivo.
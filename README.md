# Sistema de Gestión de E-commerce en Golang

Este sistema permite a los administradores gestionar productos y a los clientes realizar compras y confirmar pedidos mediante pagos fuera de línea.

## Instalación

git clone https://github.com/tu_usuario/ecommerce-golang.git
   
cd ecommerce-golang
   
go run cmd/main.go

## Módulos

- **Gestión de Productos**: Agregar, editar y eliminar productos.
- **Carrito de Compras**: Agregar productos al carrito y modificar cantidades.
- **Confirmación de Pedido**: Seleccionar método de pago y confirmar el pedido.
- **Gestión de Pedidos**: Revisar y aprobar pedidos por parte de los administradores.

## API Endpoints

- **GET /products**: Obtiene la lista de productos.
- **POST /cart**: Agrega un producto al carrito.
- **POST /orders**: Crea un nuevo pedido.

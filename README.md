## Usar localmente

### 1. Clonar repositorio

```
$ git clone https://github.com/ProyectoDistribuidos/ECommerceEspol.git
$ cd ECommerceEspol
```

### 2. Configurar MongoDB

- Local MongoDB
  - Instalar desde [here](https://www.mongodb.com/try/download/community)
  - Crear archivo .env en el root folder
  - Setear MONGODB_URL=mongodb://localhost/ecommerceespol  
- Atlas Cloud MongoDB
  - Crear base de datos en [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Crear archivo .env en el root folder
  - Setear MONGODB_URL=mongodb+srv://your-db-connection

### 3. Backend

```
$ npm install
$ npm start
```

### 4. Frontend

```
# En un nuevo terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Usuario y Productos

- En Chrome: http://localhost:5000/api/users/seed
- Retirna email y contraseña deladmin
- En Chrome: http://localhost:5000/api/products/seed
- Crea ejemplos de productos

### 6. Admin Login

- EN Chrome: http://localhost:3000/signin
- Ingresar enail y contraseña para iniciar sesión

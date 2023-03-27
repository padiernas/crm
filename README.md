# CRM

Sistema para gestionar ventas, inventario, empleados, tiendas.

## Desarrollado con

* [React](https://reactjs.org/)
* [Styled Components](https://styled-components.com/)
* [Recharts](https://recharts.org/en-US/)
* [Axios](https://axios-http.com/)

Esto es solo el front-end de la aplicación, para obtener el back-end (API creado en Node), vaya a: [API - CRM](https://github.com/padiernas/api-crm)

Puede ver una demostración del front-end con el back-end simulado [Clic aquí](https://danielmafra.github.io/xarerp/).

### Ejemplo de funcionalidad básica

![Xarerp](https://i.imgur.com/qvl8FZG.gif)

### Tema claro y oscuro

![Xarerp](https://i.imgur.com/5E34E2J.gif)

### Punto de interrupción móvil

![Xarerp](https://i.imgur.com/hdgFLyS.gif)

## SomAlgunas características features

* ✅ Persistencia de las opciones del usuario
* ✅ Persistencia de inicio de sesión (jsonwebtoken)
* ✅ Persistencia de estado con Context API y localStorage
* ✅ Rutas protegidas
* ✅ Rutas con permisos de acceso basados en el usuario conectado
* ✅ CRUD para cada funcionalidad de registro
* ✅ Reglas para no permitir entradas duplicadas
* ✅ Filtros de búsqueda y paginación
* ✅ Gráficos con métricas de los últimos 7, 15 y 30 días
* ✅ Elija entre el tema oscuro y claro
* ✅ Responsive para móviles

## Ejecutando la aplicación

Después de haber clonado el repositorio y accedido a su carpeta a través del terminal, ejecute el comando a continuación

```bash
  npm install
```

* Vaya a /src/services/axios.ts y cambie la baseURL por la URL de su API

* Asegúrese de haber configurado la API y activado, luego ejecute el siguiente comando

```bash
  npm start
```


# 📚 Reportes App Front

Este proyecto es el frontend de una aplicación web desarrollada utilizando **Vue.js**.  Se conecta con el backend en **Laravel** y soporta **autenticación con tokens** y **actualización en tiempo real con WebSockets**.

---

## 🚀 **Tecnologías utilizadas**
Asegúrate de tener instalados los siguientes componentes en tu máquina:

- **Vue.jsr**: Framework de desarrollo frontend.
- **Sass**: Para estilizar la interfaz de usuario.

---

## 🛠️ **Instalación**

Clonar el Repositorio
```sh
git clone https://github.com/hazielace/app-tiendalibro-front.git
cd ReportesTkFront
```

## 🚦 Ejecución del proyecto
Instalar dependencias
```sh
npm install
```
Configurar el entorno, editar el archivo:
```sh
.env
```
Iniciar proyecto front
```sh
npm run dev
```

## Credenciales de acceso a la app

Los usuarios se generan automáticamente al completar la instalación del backend, disponible en el siguiente repositorio:  
👉 **[ReportsTkBack](https://github.com/hazielace/ReportsTkBack)**  

Esto creará múltiples usuarios con correos y contraseñas aleatorias.  
Para obtener las credenciales de uno de estos usuarios, puedes ejecutar la siguiente consulta en la base de datos:  

```sql
SELECT email, password_show FROM users LIMIT 5;
```

# ✈️ Sistema de Reservas de Vuelos - ASP.NET MVC
 
Prototipo académico de un sistema de venta de pasajes aéreos, desarrollado con **ASP.NET 8.0 MVC** sin persistencia en base de datos. Todos los datos se manejan en memoria, simulando el funcionamiento real del sistema.
 
## 🧭 Funcionalidades principales
 
- Gestión de usuarios para administradores y clientes (premium y ocasionales).
- Catálogo simulado de aviones y sus características.
- Registro de aeropuertos, rutas y vuelos, con validaciones de alcance y frecuencia.
- Emisión de pasajes con cálculo dinámico de precio, considerando:
  - Costo del asiento (distancia, costos de aeropuerto y operativos).
  - Tipo de cliente y equipaje.
  - Tasas de salida y llegada.
  - Margen de ganancia.
- Interfaz web construida con ASP.NET 8.0 MVC y control de acceso por roles.
- Simulación completa sin necesidad de SQL Server ni Entity Framework.
## 🔐 Roles de usuario
 
**Administrador:**
- Puede modificar los puntos de clientes premium.
- Puede cambiar la elegibilidad de regalos para clientes ocasionales.
- Tiene acceso a funcionalidades administrativas protegidas.
**Cliente:**
- Puede ver y comprar pasajes.
- Puede acceder a su información personal y reservas.
- Tiene comportamiento distinto según sea premium u ocasional.
## ⚙️ Tecnologías utilizadas
 
- ASP.NET 8.0 MVC
- C# .NET
- CSS
- JavaScript
- Bootstrap 5
- Lógica de negocio en memoria (sin SQL, sin Entity Framework)
- Autenticación y autorización basada en roles
## 🚀 Cómo ejecutar el proyecto
 
1. Cloná el repositorio:
```
   git clone https://github.com/ayelenferrer/p2-ort-2025.git
```
2. Abrí el proyecto en Visual Studio 2022 o superior.
3. Ejecutá la aplicación (F5 o `dotnet run`).
4. Los usuarios y datos de ejemplo se cargan automáticamente desde el código.
---

# 🧾 Aplicación de Ventas para Negocios de Barrio

Aplicación de escritorio desarrollada en **C# con Windows Forms** y **SQL Server**, pensada originalmente para una empresa ficticia llamada **La P.O.12**, dedicada a la venta de bebidas, snacks, cigarrillos y productos similares.  
Su estructura es adaptable a cualquier **negocio de barrio o pequeño comercio**.

---

## ⚙️ Funcionalidades Principales

### 🔐 Sistema de Login
- Registro de usuarios.
- Ingreso mediante **usuario y contraseña**.

### 📦 Gestión de Productos
- Carga de productos con nombre, precio y otros datos.
- Los productos ingresados se importan automáticamente al formulario de ventas mediante **autocompletado**.
- *No se implementa control de stock* para mantener la aplicación simple y ágil.

### 🛒 Formulario de Ventas
- Ingreso de productos.
- Selección de cantidades.
- Eliminación de ítems o limpieza completa del carrito.
- Ventas registradas temporalmente para revisión antes de finalizar.

### 📊 Historial de Ventas
- Al cerrar el día, las ventas temporales se envían a una **tabla histórica**.
- Se guarda la **ganancia total del día**.
- Se identifica el **producto más vendido**.

---

## 🧠 Simplicidad y Eficiencia

Esta app está enfocada en la **facilidad de uso y rapidez**, ideal para quienes desean llevar un control de ventas sin complicarse con inventarios.

---

## 💡 Ideal para:
- 🏪 Almacenes y kioscos  
- 🧃 Tiendas de barrio  
- 🛍 Comercios pequeños que quieran comenzar a **digitalizar sus ventas**

---

## 🖼 Imágenes del Proyecto

<p align="center">
  <img src="https://github.com/user-attachments/assets/b02b84b7-ee29-4423-8989-5360ec2879d6" width="600"/>
  <img src="https://github.com/user-attachments/assets/bc64393d-7ef9-4af0-a2bc-7c4e1ee6716b" width="600"/>
  <img src="https://github.com/user-attachments/assets/16738cbe-6443-4ef3-b4b7-2da425917ad0" width="600"/>
  <img src="https://github.com/user-attachments/assets/0e469e2e-c3a5-4542-a740-6aeb5e53ddd0" width="600"/>
  <img src="https://github.com/user-attachments/assets/63441360-5624-4e53-9877-e250845fa996" width="600"/>
  <img src="https://github.com/user-attachments/assets/ed25cf3d-3b1c-4ded-b603-6ead123bdb5d" width="600"/>
  <img src="https://github.com/user-attachments/assets/0c68d19f-a738-4385-851e-57537705b2b6" width="600"/>
  <img src="https://github.com/user-attachments/assets/6fc0b922-2bdf-43d2-ad1d-f30fad1ed89b" width="600"/>
  <img src="https://github.com/user-attachments/assets/f11ac5bd-6cd5-4d6b-a7cc-06a9c3e3b55d" width="600"/>
</p>

---

## 📄 Generación de PDF Diario

Al finalizar el día, la aplicación **genera automáticamente un PDF** que contiene:

- El detalle de todos los productos vendidos ese día.
- Las cantidades vendidas de cada producto
- El registro de los productos vendidos en ese dia.

Este archivo se guarda de manera **local** en la computadora del usuario, con nombre personalizado por fecha y hora.

📎 Ejemplo de PDF generado:  
[📥 Ventas_2025-04-17_11-11-00.pdf](https://github.com/user-attachments/files/19795959/Ventas_2025-04-17_11-11-00.pdf)


</p>

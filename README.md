###  Pruebas de la aplicación móvil **Urban Lunch**

# Resultados por Área

## 1. Selección del Punto de Recogida  
**Resultados:**  
- Validación de instalación correcta de la app (Caso #2).  
- Validación completa de interacciones con puntos de recogida (Casos #3-6).  
- Subdivisión correcta de validaciones.  
- Validación de estados: no seleccionado, seleccionado, cambio, cancelación.  

---

## 2. Elección de Platillos — Lista de Platillos  
**Resultados:**  
- Validación de elementos visuales de la lista (Casos #7-10):  
  - Nombre del platillo  
  - Botones (+) y (–)  
  - Contador  
  - Flecha  
- Validación de interacciones con botones (Casos #11-13).  
- Validación del progreso del pedido en el pie de página (Casos #14-16).  

---

## 3. Detalles del Platillo  
**Resultados:**  
- Validación de componentes de la descripción (Casos #17-20).  
- Validación de navegación con flecha (Caso #21).  
- Validación del botón “+” (Caso #22).  
- Validación del estado inactivo del botón “Siguiente” (Caso #23).  

---

## 4. Confirmación del Pedido  
**Resultados:**  
- Validación de elementos visuales (Casos #24-27).  
- Validación de scroll (Caso #28).  
- Validación del cálculo del importe total (Caso #29).  
- Validación del progreso del pedido (Casos #30-32).  
- Validación de navegación al siguiente paso (Caso #33).  

---

## 5. Pantalla de Seguimiento de Pedidos  
**Resultados:**  
- Validación de elementos del mapa (Casos #34-36).  
- Validación de scroll (Caso #40).  
- Validación del temporizador (Caso #41).  
- Validación de transición automática (Caso #42).  

**Errores encontrados:**  
- Caso #37 — No muestra el costo de todos los platillos.  
  - Bug: **ULS6-1**  
- Caso #38 — No muestra el tiempo de preparación restante.  
  - Bug: **ULS6-2**  

---

## 6. El Pedido ha sido Enviado  
**Resultados:**  
- Validación del flujo de finalización (Casos #43-46).  

**Error encontrado:**  
- Caso #47 — No redirige automáticamente a selección de punto de recogida.  
  - Bug: **ULS6-3**  

---

## 7. Notificaciones de Error  
**Errores encontrados:**  
- Caso #48 — Falta mensaje de permiso de geolocalización.  
  - Bug: **ULS6-4**  
- Caso #49 — Falta mensaje al intentar pedir sin platillos.  
  - Bug: **ULS6-5**  

---

# Aptitudes

- Android Studio  
- Pruebas de aplicaciones móviles  

---

# 📎 Documento Completo  
https://docs.google.com/spreadsheets/d/1959FosXvknhmpyZktwTTfJ6MYSnJr2DKcrPOcfNfoOQ/edit?usp=drive_link

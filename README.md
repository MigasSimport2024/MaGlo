# 💆‍♀️ MGlo Bioestetic

**Sistema de gestión integral para centros de estética y belleza**  
Desarrollado por [MIGASS Entertainment](mailto:migxben@gmail.com) para **Bioq. María Gloria Sánchez**

---

## ✨ Descripción

**MGlo Bioestetic** es una aplicación web progresiva (PWA) de archivo único `.html`, diseñada para gestionar de forma completa un centro de estética. Funciona **100% offline**, sin necesidad de servidor ni instalación. Los datos se almacenan localmente en el navegador (localStorage) y se pueden respaldar/restaurar mediante archivos `.json`.

---

## 📱 Características principales

### 🏠 Inicio — Dashboard
- Resumen del día: citas programadas, ingresos del mes, clientes activos
- Acceso rápido a las citas del día con envío de confirmación por WhatsApp

### 📅 Agenda
- Calendario mensual interactivo con indicadores de días con citas
- Vista de turnos por día (hora, cliente, servicio, estado, precio)
- Estados: pendiente / completado / cancelado
- Envío de confirmación/recordatorio por WhatsApp desde la cita

### 👥 Clientes
- Ficha completa: nombre, teléfono, email, fecha de nacimiento, notas médicas/alergias
- Historial de citas por cliente
- Gestión de **paquetes de sesiones** (progreso, reagendado, próxima sesión)
- Evolución clínica del cliente
- Contacto directo por WhatsApp

### 🛍️ Productos
- Catálogo con foto, categoría, precio y stock
- Gestión de inventario

### 💅 Servicios
- Alta de servicios individuales y **paquetes de sesiones**
- Configuración de precios

### 🏭 Proveedores
- Registro de proveedores con datos de contacto

### 💰 Finanzas
- **Caja diaria**: ingresos y gastos del día
- **Gastos**: registro por categoría (materiales, alquiler, equipos, capacitación, marketing, etc.)
- **Informes mensuales**: resumen de ingresos vs. gastos
- Configuración de alias de pago (cobro digital)

---

## ⚙️ Configuración

Desde el panel de configuración se puede personalizar:

- Nombre del negocio y datos de contacto
- **Plantillas de WhatsApp** para confirmaciones y recordatorios (con variables dinámicas: `{nombre}`, `{fecha}`, `{hora}`, `{servicio}`, `{precio}`, `{negocio}`)
- Alias de pago digital
- **Backup y restauración** de datos (`.json`)

---

## 🔐 Almacenamiento de datos

> Los datos se guardan **localmente en el navegador** (localStorage).  
> Para transferir entre dispositivos, usá la función de **Backup → Exportar JSON** y luego restaurar en el otro dispositivo.

---

## 🚀 Instalación y uso

1. Descargá el archivo `mglo_bioestetic.html`
2. Abrilo en cualquier navegador moderno (Chrome, Safari, Edge)
3. ¡Listo! No requiere internet ni instalación adicional

> 💡 Para usarlo como PWA en el celular: abrilo en Chrome/Safari → *"Agregar a pantalla de inicio"*

---

## 📐 Tecnologías

- HTML5 / CSS3 / JavaScript vanilla (sin frameworks)
- `localStorage` para persistencia de datos
- Fuentes: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- Integración nativa con WhatsApp (`wa.me`)

---

## 👩‍💻 Créditos

| Rol | Nombre |
|-----|--------|
| Desarrollo principal | Juan Miguel Benítez — MIGASS Entertainment |
| Co-desarrolladora | María Gloria Sánchez |
| Colaboradora especial | Eliana Guadalupe |
| Cliente / Usuaria | Bioq. María Gloria Sánchez |

---

## 📞 Contacto

**MIGASS Entertainment** · Ciudad del Este, Paraguay  
📧 migxben@gmail.com · 📱 +595 985 648 814

---

*© 2025 MIGASS Entertainment — Todos los derechos reservados*

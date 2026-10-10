# Viabilidad técnica Apañao
 
 ## FUNCIONALIDADES PRINCIPALES

**Entre 10 y 20 funcionalidades principales de Apañao:**

1. **Gestión de Autenticación:**  
     El usuario puede registrarse e iniciar sesión en la aplicación

2. **Alta de Ingredientes:**  
     El usuario puede añadir un nuevo ingrediente al inventario de la despensa

3. **Actualización de Alimentos:**
     El usuario puede actualizar la cantidad o la fecha de caducidad de un producto en la despensa o la nevera

4. **Baja de Productos:**  
     El usuario puede eliminar un producto agotado o caducado del inventario

5. **Consulta de la despensa:**  
     El usuario puede consultar la lista completa de alimentos disponibles en su despensa

6. **Planificación de menús:**  
     El usuario puede generar menús semanales personalizados (seguramente con implementación de alguna API)

7. **Sugerencia de recetas:**  
     El usuario puede generar una propuesta de receta basada en los ingredientes disponibles en la despensa.

8. **Gestión de favoritos:**  
     El usuario puede marcar una receta como favorita para consultarla rápidamente

9. **Sincronización con la compra:**  
     El usuario puede añadir automáticamente los ingredientes faltantes de una receta a su lista de la compra

10. **Consulta la lista de la compra:**  
      El usuario puede consultar y editar los productos de su lista de la compra pendiente

11. **Traspaso a Despensa:**  
      El usuario puede marcar los productos de la lista de la compra como comprados para pasarlos directamente a la despensa virtual

12. **Alertas de caducidad:**  
      El usuario puede configurar alertas o avisos de productos próximos a caducar

13. **Configuración del perfil:**  
      El usuario puede configurar su perfil a su gusto, para recibir un trato más personalizado

14. **Gestión de alérgenos:**  
      El usuario puede seleccionar los alimentos a los que es alérgico y añadir sus intolerancias, como pueden ser el gluten o la lactosa

15. **Registro de tuppers:**  
      El usuario puede registrar un nuevo tupper cocinado especificando el plato, las raciones disponibles y la fecha de elaboración

16. **Alertas de descongelación:**  
      El usuario recibirá notificaciónes de descongelar el tupper los días que la app haya decidido que ese día se come tupper.

17. **Consulta de tuppers:**  
      El usuario puede consultar su stock de tuppers guardados en el congelador o la nevera con sus respectiva fecha de consumo preferente

18. **Menús semanales:**  
      El usuario podrá generar semanalmente un horario de comidas de todos los días en base a la comida que haya en la despensa, la nevera o los tuppers disponibles.

19. **Descuento de tupper:**  
      El usuario puede descontar una ración del tupper al incluirlo en la planificación de comida semanal.

20. **Gestión de favoritos:**  
      El usuario puede marcar una receta como favoritapara tenerla siempre accesible rápidamente.

### MUST HAVE

*Obligatorias, sin esto no funciona la app*  

Las funcionalidades escenciales de **Apañao**, son las siguientes:  

- **Registro de usuarios:** Registrarse en la app introduciendo correo y contraseña  

- **Inicio de sesión:** Iniciar sesión para acceder a tu espacio privado  

- **Configuración de un perfil:** Editar los datos personales y las preferencias de configuración de cada usuario  

- **Gestión de alérgenos:** Seleccionar alérgenos e intolerancias para poder filtrar recetas que no puedan comer por los alérgenos

- **Alta de ingredientes:** Añadir un nuevo ingredienteal inventario de la despensa

- **Consulta de despensa:** Consultar la lista completa de alimentos disponibles en la despensa

- **Planificación de menús:** Crear menú semanal personalizado combinando recetas y tuppers.

- **Sincronización con la compra:** Añadir automáticamente los ingredientes faltantes del menú a la lista

- **Consulta lista de la compra:** Consultar y editar lista de la compra pendiente



### SHOULD HAVE

*Aportan bastante valor y completan la experiencia principal, pero la app podría seguir funcionando sin ellas*

* **Cierre de sesión:** Cerrar sesión de manera segura para proteger la información personal

* **Actualización de Alimentos:** Actualizar la cantidad o datos de un alimento existente en la despensa.
- **Baja de Productos:** Eliminar un producto agotado o caducado del inventario.

- **Registro de Tuppers:** Registrar un nuevo tupper cocinado especificando raciones y fecha.

- **Consulta de Tuppers:** Consultar el stock de tuppers guardados en nevera o congelador.

- **Descuento de Tuppers:** Descontar una ración de un tupper al incluirlo en el menú semanal.

- **Sugerencia de Recetas:** Generar propuestas de recetas basadas en los ingredientes y alérgenos.

- **Traspaso a Despensa:** Marcar productos comprados para trasladarlos directamente a la despensa.



### COULD HAVE

*Funcionalidades secundarias o mejoras que mejoran la comodidad del usuario si el calendario de desarrollo lo permite*

- **Gestión de Favoritos:** Marcar una receta como favorita para tenerla accesible rápidamente.

- **Alertas de Caducidad:** Configurar avisos visuales de productos próximos a caducar en la despensa.



### WON'T HAVE

*Características más avanzadas que no se añadirán en esta primera versión*

* **Compartir Inventario o Menús en Red:** Sincronizar la despensa en tiempo real con compañeros de piso o familiares



## DEFINICIÓN DEL MVP

En este apartado definimos el prodcuto mínimo viable de nuestra aplicación ***Apañao***:



* **Entrada y configuración inicial:**  
  El usuario abre la aplicación, realiza el Registro de Usuario, inicia sesión y configura rápido su perfil, añadiendo sus intolerancias, sus alergias y los alimentos que le gustan y los que no

* **Inventario básico:**  
  Añade los pocos ingredientes que tengas ahora mismo en la nevera y revisa lo que hay disponible

* **Cierre del ciclo:**  
La aplicación detecta automáticamente qué alimentos faltan para los menús y te genera una lista de la compra (*por ahora estaría disponible mercadona y carrefour, son las únicas APIs que hemos encontrado hasta el último día que hablamos el equipo*)



### **Requisitos que forman parte del MVP:**

Los requisitos indispensables sin los cuales este recorrido mínimo se rompe y no funciona son exclusivamente nuestras funcionalidades **Must have**:

- Registro de Usuario

- Inicio de Sesión

- Configuración de Perfil

- Gestión de Alérgenos

- Alta de Ingredientes

- Consulta de Despensa

- Planificación de Menús

- Sincronización con la Compra

- Consulta de la Lista de la Compra

*Todo lo demás (como el control de tuppers, las sugerencias automáticas avanzadas de recetas, el histórico o las alertas de caducidad) queda fuera de esta primera versión (MVP), ya que el usuario puede completar su objetivo principal sin ellas.*

## ANÁLISIS DE REQUISITOS TÉCNICOS

### 1. Frontend (React)

Para garantizar una experiencia rápida, reactiva y fluida en dispositivos móviles, utilizaremos (en la medida de lo posible y si es completamente necesario) las siguientes bibliotecas dentro del entorno **React** (vía Vite o Create React App):

| Biblioteca | Función / Ámbitos | Justificación y Por Qué la Necesitamos |
| ----- | ----- | ----- |
| **React Router (v6+)** | Navegación y Enrutamiento | Gestión de rutas dinámicas (pantallas de despensa, planificador, lista de la compra, recetas y tique). Permite la navegación fluida sin recargar la página (*Single Page Application*). |
| **Zustand** (o **Context API**) | Gestión de Estado Global | Manejo simplificado y ligero del estado del cliente (despensa temporal, filtros de recetas y carrito de la compra activo) antes o entre sincronizaciones con la API de Node.js. |
| **Axios** | Cliente HTTP | Gestión de peticiones hacia nuestro backend en Node.js/Express (obtención de recetas, actualización de inventario, registro/login). Facilita interceptores para el envío de tokens (JWT) y manejo centralizado de errores. |
| **TanStack Query (React Query)** | Gestión de Peticiones y Caché | Optimiza las peticiones a la API Express, evitando llamadas repetitivas al servidor, gestionando la caché de recetas/productos y refrescando los datos automáticamente cuando el usuario interactúa. |
| **Tailwind CSS + Lucide React** | Estilos e Iconos | Diseño *mobile-first* ágil, adaptado a interfaces simples para jóvenes, e integración de iconografía ligera y clara para la gestión de Nevera, Táper, Monedas y Presupuesto. |

---

### 2. Backend (Node.js + Express)


---

### 3. Base de Datos (MongoDB)


---

### 4. Infraestructura y Despliegue Cloud (Stack MERN)

Se plantea una arquitectura dividida (*Decoupled Architecture*) con coste **$0/mes** durante la fase de prototipo y validación.

```
                  ┌─────────────────────────────────┐
                  │          Vercel (Free)          │
                  │   Aplicación React (Frontend)   │
                  └────────────────┬────────────────┘
                                   │  Peticiones API (REST/HTTP)
                                   ▼
                  ┌─────────────────────────────────┐
                  │     Render / Railway (Free)     │
                  │    Backend Express (Node.js)    │
                  └────────────────┬────────────────┘
                                   │  (Futuro)
                                   ▼
                   [ MongoDB Atlas - Free Tier ]
```

### Unidades de Despliegue y Planes Gratuitos

#### 1. Frontend (React)
* **Plataforma seleccionada:** **Vercel** *(o Netlify)*.
* **Por qué:** Despliegue continuo automático desde GitHub, CDN global rápida para aplicaciones web estáticas/SPAs.
* **Condiciones del Plan Gratuito (Vercel Hobby):**
  * **Ancho de banda:** 100 GB/mes.
  * **Límites:** Totalmente suficiente para prototipos y miles de usuarios iniciales sin ningún coste.

#### 2. Backend (Node.js / Express API)
* **Plataforma seleccionada:** **Render** *(opción alternativa: Railway / Koyeb)*.
* **Por qué:** Permite desplegar servidores Web Services en Node.js de forma directa desde repositorios Git.
* **Condiciones del Plan Gratuito (Render Free Instance):**
  * **RAM / CPU:** 512 MB RAM, CPU compartida.
  * **Comportamiento:** El servicio entra en "reposo" (*spin down*) tras 15 minutos de inactividad, tardando unos 20-30 segundos en despertar en la primera petición tras el estado de reposo (comportamiento habitual y aceptable en fases de prueba/evaluación académica).

---

### Resumen de Viabilidad Económica

* **Frontend (React):** 0 € / mes (Vercel)
* **Backend (Node.js + Express):** 0 € / mes (Render)
* **Coste Total Operativo:** **0 € / mes**

> **Conclusión técnica:** El uso del stack **MERN** desplegado de forma independiente en plataformas SaaS especializadas (Vercel + Render) garantiza una arquitectura profesional, escalable y con coste cero durante la validación de la idea.





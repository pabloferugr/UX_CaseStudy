## DIU - Practica2, entregables

### Ideación 

* Malla receptora de información
  
  He detectado que muchos usuarios llegan a Granada Cooking buscando talleres gastronómicos, pero abandonan la web al no encontrar información clara, talleres disponibles o alternativas sugeridas.

* Mapa de empatía

  ![Mapa de Empatía](EmpathyCustomerMap.png)
  
  **Juan**, nuestro usuario principal, es una persona mayor interesada en talleres familiares. Se siente confundido cuando ve talleres desactualizados en la portada y decepcionado al no recibir opciones alternativas desde el soporte. Necesita una experiencia fluida, con información clara y actualizada que le permita tomar decisiones sin depender de ayuda externa.
  
* Point of View
  
  *Juan necesita una forma rápida y clara de encontrar talleres disponibles porque al no ver información actualizada ni recibir sugerencias por parte del soporte, abandona la web frustrado.*


### PROPUESTA DE VALOR
* ScopeCanvas:
  
  Lo que hace a mi proyecto diferente es que el sistema de reservas muestra **únicamente talleres activos y con plazas disponibles**. Además, si un taller está completo, se ofrecen automáticamente **sugerencias de otros talleres similares**. Esta mejora evita la pérdida de usuarios como Juan y facilita la navegación de nuevos visitantes.


### TASK ANALYSIS

* User Task Matrix
  
  - **Usuarios sin cuenta**: acceden de forma ocasional. Solo buscan un taller disponible y esperan poder reservar con facilidad.
    
  - **Usuarios con cuenta**: han reservado previamente o planean hacerlo varias veces. Esperan un sistema más personalizado, con sugerencias y gestión de reservas.
* User/Task flow
  
  1. El usuario accede a la web.
  2. Navega por los talleres disponibles (con filtros).
  3. Si un taller está lleno, el sistema le sugiere otros similares.
  4. Puede registrarse para guardar sus reservas o recibir más recomendaciones.

### ARQUITECTURA DE INFORMACIÓN

* Sitemap
  
  La estructura del sitio se ha rediseñado para que los talleres disponibles estén claramente destacados desde la portada. Se prioriza el acceso a filtros por fecha, tipo de cocina o nivel, junto con acceso directo a contacto.
  
* Labelling
  
| Término                 | Significado                                                                 |
|-------------------------|------------------------------------------------------------------------------|
| **Inicio**              | Página principal con talleres destacados y acceso a filtros.                |
| **Talleres disponibles**| Lista filtrada de talleres activos y con plazas disponibles.                |
| **Calendario**          | Vista mensual con fechas de los talleres; solo muestra fechas con plazas.   |
| **Ver disponibilidad**  | Información clara sobre si hay plazas o está completo.                     |
| **Sugerencias**         | Talleres alternativos mostrados automáticamente si el seleccionado está completo. |
| **Buscar taller**       | Barra de búsqueda con filtros por temática, nivel, fecha o idioma.          |
| **Filtrar por...**      | Opciones para acotar resultados por tipo de cocina, nivel, fecha, etc.      |
| **Reservar ahora**      | Botón para iniciar el proceso de reserva si hay plazas.                     |
| **No hay plazas**       | Mensaje visible que muestra que el taller está completo.                    |
| **Ver más talleres**    | Llama a la acción para seguir explorando opciones similares.                |
| **Iniciar sesión / Registrarse** | Acceso para usuarios con cuenta o registro de nuevos.               |
| **Cuenta**              | Sección donde el usuario ve sus datos, reservas, etc.                       |
| **Pagar**               | Página donde se escoge y confirma el método de pago.                        |
| **Formas de pago**      | Desplegable para elegir entre tarjeta, PayPal, Bizum, etc.                  |
| **Idioma**              | Selector visible para cambiar entre español e inglés.                       |
| **RRSS**                | Vista previa y enlaces a redes sociales de Granada Cooking.                 |

### Prototipo Lo-FI Wireframe 


### Conclusiones  

(incluye valoración de esta etapa)

Esta etapa me ha permitido analizar en profundidad los fallos de la web actual de Granada Cooking y pensar mejoras enfocadas directamente en los problemas reales que enfrentan usuarios como Juan.  
Proponer una solución centrada en la información actualizada y la oferta de sugerencias automáticas ha sido clave para mejorar la experiencia general.  
Creo que este rediseño facilita la navegación y aporta confianza al usuario, aumentando así las probabilidades de reserva y fidelización.

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica

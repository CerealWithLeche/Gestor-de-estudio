# Gestor de estudio
Es una aplicación web diseñada para estudiantes que buscan optimizar su organización y potenciar su aprendizaje. A través de un calendario dinámico e intuitivo, los usuarios pueden gestionar sus materias, realizar un seguimiento de su comprensión y consultar a un chatbot-tutor basado en sus propias notas.

## Características Principales

- **Calendario Dinámico:** Visualiza tus materias y actividades diarias configuradas de forma personalizada.
- **Gestión de Materias:** Configura tu semestre, asigna colores a cada asignatura y organiza tu horario semanal.
- **Tutoría con IA:** Un chatbot integrado que analiza tus apuntes del día para resolver dudas, resumir temas o explicar conceptos difíciles.
- **Seguimiento de Aprendizaje:** Sistema de estados (Entendido, Repaso Necesario, Confuso) para priorizar tus sesiones de estudio mediante indicadores visuales.
- **Funcionamiento Local:** No necesitas un servidor complejo, la aplicación se ejecuta directamente en tu navegador, garantizando rapidez y acceso inmediato.
- **Privacidad y Persistencia:** Los datos se almacenan exclusivamente en tu dispositivo. Tus notas y configuraciones son privadas y no se envían a servidores externos.

## Instalación y Uso Rápido
Una de las ventajas de esta aplicación es que es totalmente **portable y ligera**. No necesitas instalar dependencias pesadas ni configurar servidores locales.

Para comenzar a usarla, solo sigue estos dos pasos:

1. **Clona el repositorio** en tu máquina local:
   ```bash
      git clone https://github.com/CerealWithLeche/Gestor-de-estudio.git
2. **Abre el archivo** calendario index desde tu navegador

<div align="center">
   <img width="660" height="350" alt="image" src="https://github.com/user-attachments/assets/7e52189e-d073-4537-ba1f-fd7a1f53f7d0" />

   <p></p>
  <img width="660" height="350" alt="image" src="https://github.com/user-attachments/assets/594b92ad-67d2-4567-acda-cabad237f95a" />

</div>

---
## Configuración y Seguridad
Para comenzar a utilizar el gestor, es necesario completar la configuración inicial en el panel de ajustes:

1. **Conexión con la IA:** Ingresa tu **Google API Key** en la caja de texto dedicada. Esta llave es necesaria para habilitar el servicio de LLM (Gemini) que potencia el chatbot y el análisis de tus notas.
2. **Definición del Semestre:** Establece la **fecha de inicio y fin** de tu periodo escolar. Esto delimita el rango de acción del calendario dinámico.
3. **Carga Académica:**
   - Agrega tus **materias** una a una.
   - Asigna un **color personalizado** a cada materia para una identificación visual rápida en el calendario.
4. **Horario Semanal:** Una vez creadas las materias, selecciona los **días de la semana** en los que tienes clase de cada una para que el sistema organice automáticamente tus entradas diarias.

<div align="center">
   <img width="660" height="350" alt="Screenshot_17-Dec_14-03-07_32211" src="https://github.com/user-attachments/assets/df26c2dd-6863-4eba-8afd-d858b62c4f40" />
   <p></p>
   <img width="660" height="350" alt="Screenshot_17-Dec_14-03-24_23809" src="https://github.com/user-attachments/assets/5d34c117-dd36-4bee-8f77-2eb085a9168e" />
</div>

#### ⚠️ Zona de Peligro
Para garantizar el control total sobre tus datos, la aplicación incluye una sección de **Zona de Peligro** en el panel de configuración:
* **Reset Total:** Un botón diseñado para borrar instantáneamente toda la información guardada (materias, notas, historial del chat y configuraciones). 
* *Nota: Esta acción es irreversible y deja la aplicación como nueva.*

## Próximas Actualizaciones
- **Soporte Multi-Modelo:** Integración para utilizar el chatbot con API Keys de **OpenAI** y **DeepSeek**, permitiendo al usuario elegir su motor de IA preferido.
- **Exportación de Datos:** Opción para descargar tus notas y horarios en formato PDF o JSON.
- **Modo Oscuro:** Interfaz adaptativa para sesiones de estudio nocturnas.



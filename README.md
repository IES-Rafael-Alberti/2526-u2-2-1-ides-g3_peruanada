[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Eil8wls0)
# Entornos de desarrollo. Unidad 2
## Práctica 2: Evaluación de IDEs

**Recurso de apoyo:** [Evaluación. Uso y comparativas de IDEs](https://revilofe.github.io/section3/u02/practica/EDES-U2.-Practica002/)

---

## 👥 Componentes del Grupo

| Nombre y Apellidos | Correo Electrónico | Iniciales |
|-------------------|-------------------|-----------|
| [Nombre Alumno 1] | [email@g.educaand.es] | [XXX] |
| [Nombre Alumno 2] | [email@g.educaand.es] | [XXX] |
| [Nombre Alumno 3] | [email@g.educaand.es] | [XXX] |
| [Nombre Alumno 4] | [email@g.educaand.es] | [XXX] |
| [Nombre Alumno 5] | [email@g.educaand.es] | [XXX] |

---

## 📁 Estructura del Repositorio

Este es un **repositorio compartido** donde cada alumno entregará su trabajo individual siguiendo esta estructura:

```
2526_EDES_u2_IDEs/
├── README.md                          # Este archivo (documentación general)
├── EDES-U2.-Practica002.md           # Documento de la práctica
├── parte_comun/                      # Trabajo colaborativo del grupo (punto 7)
│   ├── tabla_comparativa.md          # Tabla comparativa de IDEs
│   ├── respuestas_grupo.md           # Respuestas a preguntas evaluativas grupales
│   └── recursos/                     # Recursos compartidos (capturas, enlaces)
└── entregas_individuales/            # Trabajos individuales (puntos 1-6)
    ├── [Iniciales_Alumno1]/          # Ej: EFO/
    │   ├── punto1_instalacion.md
    │   ├── punto2_modulos.md
    │   ├── punto3_personalizacion.md
    │   ├── punto4_actualizaciones.md
    │   ├── punto5_multiples_lenguajes.md
    │   ├── punto6_mismo_codigo.md
    │   └── capturas/
    ├── [Iniciales_Alumno2]/
    ├── [Iniciales_Alumno3]/
    ├── [Iniciales_Alumno4]/
    └── [Iniciales_Alumno5]/
```

---

## 📋 Instrucciones para los Alumnos

### 1. **Trabajo Individual (Puntos 1-6)**

Cada alumno debe elegir **2 IDEs** y trabajar individualmente en los 6 puntos:

1. **Crear su carpeta personal** en `entregas_individuales/` usando sus iniciales (Ej: `EFO/`)
2. **Completar los 6 puntos** de la práctica:
   - **Punto 1:** Instalación de IDEs (propietarios y libres)
   - **Punto 2:** Gestión de módulos y extensiones
   - **Punto 3:** Personalización y automatización
   - **Punto 4:** Sistema de actualización
   - **Punto 5:** Ejecutables en diferentes lenguajes (mismo IDE)
   - **Punto 6:** Ejecutables con diferentes IDEs (mismo código)

3. **Documentar cada punto** en archivos separados:
   - `punto1_instalacion.md`
   - `punto2_modulos.md`
   - `punto3_personalizacion.md`
   - `punto4_actualizaciones.md`
   - `punto5_multiples_lenguajes.md`
   - `punto6_mismo_codigo.md`
   - Guardar capturas en carpeta `capturas/`

#### Plantilla para cada punto:
```markdown
# Punto [X]: [Título del punto]

## IDEs utilizados
- **IDE 1:** [Nombre y versión]
- **IDE 2:** [Nombre y versión]

## Descripción de la tarea
[Explicación de lo realizado]

## Respuestas a preguntas evaluativas
### Pregunta 1: [Texto de la pregunta]
[Tu respuesta]

### Pregunta 2: [Texto de la pregunta]
[Tu respuesta]

## Evidencias
![Captura 1](capturas/punto[X]_captura1.png)
![Captura 2](capturas/punto[X]_captura2.png)

## Observaciones
[Comentarios adicionales]
```

### 2. **Trabajo Grupal (Punto 7 - Comparación)**

Todo el grupo debe colaborar en la carpeta `parte_comun/`:

1. **Respuestas Grupales** (`respuestas_grupo.md`):
   - Responder de forma conjunta las preguntas de los puntos anteriores
   - Destacar solo los puntos más relevantes
   - Identificar qué IDEs son mejores para diferentes usos
   - Qué plugins/funcionalidades son más interesantes

2. **Tabla Comparativa** (`tabla_comparativa.md`):
   - Incluir TODOS los IDEs analizados por el grupo (10 IDEs si sois 5 personas)
   - Comparar características comunes y específicas
   - Usar el formato de ejemplo de la práctica (ver sección 4)
   - Incluir al menos 15 características diferentes

3. **Preguntas Evaluativas Grupales**:
   - ¿Qué características comunes comparten los IDEs?
   - ¿Qué diferencias notaron en módulos, personalización y ejecutables?
   - ¿Cuál IDE es más adecuado para proyectos específicos?
   - ¿Qué IDE recomendarían para Python, Java o Kotlin?

4. **Recursos Compartidos** (carpeta `recursos/`):
   - Enlaces útiles
   - Documentación común
   - Capturas relevantes para la exposición

### 3. **Workflow de Trabajo con Git**

```bash
# 1. Clonar el repositorio (solo la primera vez)
git clone [URL_DEL_REPOSITORIO]
cd 2526_EDES_u2_IDEs

# 2. Antes de empezar a trabajar, actualizar tu copia
git pull origin main

# 3. Crear tu carpeta personal (solo la primera vez)
mkdir -p entregas_individuales/[TUS_INICIALES]

# 4. Trabajar en tus archivos...

# 5. Añadir tus cambios
git add entregas_individuales/[TUS_INICIALES]/
git add parte_comun/  # Solo si has trabajado en la parte común

# 6. Hacer commit con mensaje descriptivo
git commit -m "Añadido análisis de [IDE] - [TUS_INICIALES]"

# 7. Subir tus cambios
git push origin main

# 8. Si hay conflictos, resolver y repetir el proceso
```

### 4. **Normas de Colaboración**

✅ **SÍ hacer:**
- Trabajar en tu propia carpeta individual
- Actualizar (`git pull`) antes de empezar a trabajar
- Hacer commits frecuentes con mensajes claros
- Coordinar con el grupo para la parte común
- Respetar la estructura de carpetas establecida

❌ **NO hacer:**
- Modificar archivos de otros compañeros sin permiso
- Hacer commits directos a la parte común sin coordinar
- Subir archivos muy pesados (comprimir capturas si es necesario)
- Ignorar los conflictos de Git

---

## Identificación de la Actividad
- **ID de la Actividad:** 2.2 - P2
- **Módulo:** Entornos de Desarrollo (EDES)
- **Unidad de Trabajo:** UD 2 - Evaluación de IDEs
- **Fecha de Creación:** 28/10/2024
- **Fecha de Entrega:** [Fecha de entrega]
- **Grupo:** 
  - **Integrantes:** [Ver tabla de componentes del grupo arriba]
  - **Número de integrantes:** 5 personas

## Descripción de la Actividad

Esta actividad se centra en los criterios de evaluación:
- **CE 2.a)** Instalación de entornos de desarrollo, propietarios y libres
- **CE 2.b)** Gestión de módulos y extensiones en el entorno de desarrollo
- **CE 2.c)** Personalización y automatización del entorno
- **CE 2.d)** Configuración del sistema de actualización del entorno de desarrollo
- **CE 2.e)** Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE
- **CE 2.f)** Generación de ejecutables con diferentes IDEs a partir del mismo código fuente
- **CE 2.g)** Comparación de las características comunes y específicas de diversos entornos de desarrollo

### Objetivos
- **Trabajo Individual:** Cada estudiante trabaja en los puntos 1-6 con 2 IDEs diferentes
- **Trabajo Grupal:** El grupo (5 personas) compara 10 IDEs en total y crea una tabla comparativa
- **Exposición:** Presentar los resultados del análisis comparativo en clase

## 🔧 IDEs a Evaluar

**Nota:** Solo se puede repetir UNO de estos tres: Visual Studio Code, PyCharm o IntelliJ IDEA.

### IDEs Principales (elegir de aquí)
1. **Fleet** - IDE de nueva generación de JetBrains
2. **PyCharm** - Especializado en Python
3. **Thonny** - Ideal para principiantes en Python
4. **Apache NetBeans** - Código abierto, multi-lenguaje
5. **LiClipse** - Extensión de Eclipse para Python
6. **Visual Studio Code** - Editor flexible y personalizable
7. **Visual Studio** - IDE avanzado de Microsoft

### IDEs Alternativos
- Sublime Text 3 con Anaconda Plugin
- Atom con Atom-python-run
- Wing Python IDE
- Spyder IDE (popular en Data Science)
- Eric Python IDE
- IDLE (Entorno incluido con Python)

## 📝 Desarrollo de la Actividad

### Trabajo Individual (Puntos 1-6)

Cada alumno debe completar los 6 puntos en su carpeta personal:

#### Punto 1: Instalación de IDEs
- Instalar 2 IDEs (uno propietario y uno libre)
- Documentar proceso con capturas
- Responder preguntas evaluativas

#### Punto 2: Gestión de módulos y extensiones
- Instalar extensiones/plugins en ambos IDEs
- Ejemplo: Python en VSCode, Kotlin en IntelliJ
- Documentar beneficios

#### Punto 3: Personalización y automatización
- Personalizar tema y atajos de teclado
- Automatizar tareas (compilación, pruebas)
- Mostrar antes y después

#### Punto 4: Sistema de actualización
- Configurar actualizaciones automáticas/manuales
- Explicar importancia de mantener IDE actualizado

#### Punto 5: Múltiples lenguajes en mismo IDE
- Crear programa "cuenta atrás" (10 a 0, "¡Despegue!")
- Ejecutar en 2 lenguajes diferentes (ej: Java y Kotlin)
- Usar un solo IDE

#### Punto 6: Mismo código en diferentes IDEs
- Crear programa "cuenta atrás" en Python
- Ejecutar en ambos IDEs
- Comparar experiencia

### Trabajo Grupal (Punto 7)

El grupo completa en `parte_comun/`:

#### Tabla Comparativa de IDEs

Usar el ejemplo de la práctica (sección 4 del documento) como referencia. Incluir características como:

| Característica | IDE 1 | IDE 2 | IDE 3 | ... | IDE 10 |
|---------------|-------|-------|-------|-----|--------|
| Lenguajes soportados | | | | | |
| Velocidad de carga | | | | | |
| Soporte extensiones | | | | | |
| Depurador | | | | | |
| Refactorización | | | | | |
| Autocompletado | | | | | |
| Control de versiones | | | | | |
| Automatización | | | | | |
| Personalización | | | | | |
| Integración BD | | | | | |
| Pruebas automatizadas | | | | | |
| Soporte frameworks | | | | | |
| Entornos virtuales | | | | | |
| Análisis de código | | | | | |
| Maven/Gradle | | | | | |
| Precio/licencia | | | | | |

#### Preguntas Evaluativas Grupales
1. Características comunes de los IDEs
2. Diferencias en módulos, personalización y ejecutables
3. IDE más adecuado para proyectos específicos
4. Recomendaciones para Python, Java o Kotlin

## Referencias y Fuentes

- [Documentación oficial de los IDEs evaluados]
- https://revilofe.github.io
- [Otras fuentes consultadas]

---

### Condiciones de Entrega

#### Parte Individual
- **Formato:** Archivos Markdown en carpeta personal del repositorio
- **Ubicación:** `entregas_individuales/[TUS_INICIALES]/`
- **Contenido mínimo:**
  - 6 archivos (punto1 a punto6) con respuestas completas
  - Capturas de pantalla en carpeta `capturas/`
  - Respuestas a TODAS las preguntas evaluativas

#### Parte Grupal
- **Formato:** Archivos Markdown en `parte_comun/`
- **Contenido:**
  - `tabla_comparativa.md` con comparación de 10 IDEs
  - `respuestas_grupo.md` con respuestas a preguntas grupales
  - Preparación para **exposición en clase**
- **Permisos:** Asegurar que el profesor tenga acceso al repositorio

### Criterios de Evaluación

#### Parte Individual (60%)
- Completitud de los 6 puntos (CE 2.a - 2.f)
- Calidad de las respuestas
- Evidencias con capturas de pantalla
- Documentación clara y estructurada

#### Parte Grupal (40%)
- Tabla comparativa completa y detallada (CE 2.g)
- Respuestas grupales fundamentadas
- Calidad de la exposición
- Colaboración y coordinación del equipo

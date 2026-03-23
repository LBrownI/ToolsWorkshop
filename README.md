# ToolsWorkshop
¡Excelente iniciativa! Enseñar estas herramientas a tus compañeros de Ingeniería Civil Informática es un gran aporte. Como ya estás en la recta final de la carrera, sabes por experiencia propia que dominar VSCode y Git es fundamental, y a veces la curva de aprendizaje inicial de Git puede ser frustrante si no se enseña bien.

Aquí te doy una dosis de realidad y franqueza: **1 hora y 20 minutos (80 minutos) es poquísimo tiempo para todo lo que tienes en mente.** El plan que propones es muy completo, pero si intentas enseñar `fork`, `branch`, y `merge` a grupos de 4 personas que recién instalan Git, el taller se va a convertir en una sesión de 40 minutos resolviendo conflictos de fusión (merge conflicts) y errores de "detached HEAD".

Para que el taller sea un éxito y los estudiantes se vayan con una sensación de logro (y no de confusión), te sugiero el siguiente alcance y estructura.

---

### ⏱️ Propuesta de Alcance y Cronograma (80 Minutos)

El objetivo principal de este módulo debe ser el **"Ciclo de Oro"** de Git (`clone`, `add`, `commit`, `pull`, `push`) y la navegación básica en VSCode. Deja `fork` y el manejo avanzado de ramas para un "Taller Parte 2".

**1. Introducción y VSCode (15 Minutos)**
* **Teoría exprés (5 min):** ¿Qué es un IDE/Editor? Por qué VSCode es el rey actual.
* **Práctica guiada (10 min):** * Abrir una carpeta.
    * Explorador de archivos.
    * Instalar extensiones clave (ej. *Python*, *GitLens*, *Spanish Language Pack*).
    * Abrir y usar la terminal integrada (esto es crucial para el paso de Git).

**2. Git y GitHub: Conceptos Base (15 Minutos)**
* **Teoría visual (10 min):** Explica la diferencia entre tu PC (Local) y la nube (GitHub). Usa la analogía de "guardar partida" en un juego para los commits.
* **Demostración rápida (5 min):** Tú en la terminal y tu compañero en GitHub Desktop/Web mostrando el mismo flujo. Así ven que la terminal y la interfaz gráfica hacen exactamente lo mismo.

**3. Práctica Individual (20 Minutos)**
* **El ejercicio:** Que cada uno clone el repositorio de ejemplo que preparaste.
* Que creen un archivo de texto simple con su nombre (ej. `juan_perez.txt` o un script `print("Hola soy Juan")`).
* Que ejecuten: `git add .`, `git commit -m "Agrega archivo de Juan"`, y `git push` a su propio repositorio (si lo bifurcaron/clonaron) o que simplemente vean cómo funciona el registro local.
* *Nota:* Para ahorrar tiempo de permisos, es mejor que clonen tu repo de ejemplo, lo copien a una carpeta nueva, y hagan `git init` para subirlo a un repo *propio* nuevo que ellos creen en su GitHub.

**4. Práctica Colaborativa: El Verdadero Reto (25 Minutos)**
* **Grupos de 2 (Máximo 3, evitar 4):** En grupos de 4, uno teclea y tres miran. En parejas, ambos tienen que interactuar.
* **La misión:** Estudiante A crea un repositorio y da permisos de colaborador al Estudiante B.
* Estudiante B hace `clone`, modifica un archivo compartido (como un `README.md` con los nombres del equipo), hace `commit` y `push`.
* Estudiante A hace `pull` en su VSCode para ver los cambios aparecer en vivo. 
* *Aquí es donde brilla VSCode:* Muéstrales cómo VSCode resalta los cambios y quién los hizo.

**5. Cierre y Preguntas (5 Minutos)**
* Resumen de comandos.
* Qué pasa si se equivocan (darles la tranquilidad de que pueden borrar la carpeta y volver a clonar si el mundo explota).

---

### 🛠️ Requisitos Previos (Lista para los estudiantes)

Para que no pierdas ni un minuto de esos 80, envíales esta lista exacta con un par de días de anticipación. Deben llegar con esto **listo y probado**:

1.  **Cuenta de GitHub Creada:** Deben registrarse en github.com y confirmar su correo electrónico (esto es lo que más tiempo quita si lo hacen en el momento).
2.  **Git Instalado:** Deben descargar e instalar Git. 
    * *Obligatorio:* Que ejecuten estos dos comandos en su terminal antes de ir al taller para configurar sus credenciales:
        * `git config --global user.name "Su Nombre"`
        * `git config --global user.email "su_correo@ejemplo.com"`
3.  **Visual Studio Code Instalado.**
4.  **GitHub Desktop Instalado** (Para la parte de tu compañero).
5.  **Python Instalado** (Como asumiste, es ideal tener un lenguaje para correr un "Hola Mundo" en la terminal y comprobar que todo funciona).

---

¿Te gustaría que diseñemos juntos el archivo exacto (el código de ejemplo) que usarán en el repositorio de prueba para la actividad práctica?

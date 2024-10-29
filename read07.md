# 🧑‍💻 Introducción a Git y Control de Versiones

## 🚀 ¿Qué es el Control de Versiones?
Imagina que estás trabajando en un proyecto, como escribir un libro o desarrollar un software, y quieres tener la capacidad de **volver atrás** si algo sale mal. El **control de versiones** es un sistema que guarda todas las versiones anteriores de un proyecto, lo que te permite ver los cambios que has hecho y recuperar versiones anteriores cuando lo necesites. Es como una “línea de tiempo” de todos los cambios, así puedes experimentar sin miedo a perder algo importante.

## 🛠️ ¿Qué es Git y el comando `clone`?
**Git** es una herramienta popular de control de versiones que ayuda a gestionar los cambios de proyectos, especialmente en equipo. Cuando tienes un proyecto que ya está guardado en algún sitio, como en **GitHub**, puedes usar el comando `git clone` para hacer una copia exacta de ese proyecto en tu computadora. 

> Es como copiar el proyecto en tu espacio de trabajo, para que puedas hacer tus propias modificaciones sin afectar el original de inmediato.

---

## 🔑 Comandos Básicos de Git

Para trabajar en Git, aquí tienes algunos comandos esenciales que debes conocer:

1. ### Agregar archivos a la “zona de preparación” 📝
   Cuando haces cambios en tus archivos, tienes que “prepararlos” para confirmarlos. Usa el comando `git add nombre_del_archivo` o simplemente `git add .` si quieres agregar todos los archivos modificados.

   > Esto le indica a Git que esos archivos están listos para ser guardados en la próxima versión.

2. ### Guardar los cambios en el repositorio 💾
   Una vez que has “preparado” los archivos, usa el comando `git commit -m "mensaje"` para crear una nueva versión en la historia del proyecto.

   👉 En el mensaje, describe brevemente el cambio, como: "arreglé un error en el código" o "agregué nuevas funciones".

3. ### Enviar los cambios a GitHub 🌐
   Finalmente, para guardar los cambios en el repositorio en línea (como GitHub), usa el comando `git push`.

   > Esto sube tu trabajo al repositorio en la nube, permitiendo que otros miembros del equipo puedan ver y colaborar en los cambios.

---

## ✅ Resumen de Preguntas y Respuestas

1. **¿Qué es el control de versiones?**  
   Es un sistema que rastrea todos los cambios hechos en un proyecto, permitiendo recuperar versiones anteriores y colaborar fácilmente con otras personas.

2. **¿Qué es `clone` en Git?**  
   Es el comando que usamos (`git clone`) para hacer una copia de un proyecto que ya existe, en nuestra computadora.

3. **¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?**  
   El comando es `git add nombre_del_archivo` o `git add .` para agregar todos los archivos modificados.

4. **¿Cuál es el comando para enviar la captura de los archivos modificados a GitHub?**  
   El comando es `git push`, y con esto los cambios suben a tu repositorio en GitHub para que estén disponibles en línea.

---

🎉 ¡Y eso es todo! Con estos conceptos básicos, estarás listo para empezar a usar Git y colaborar en proyectos de manera efectiva.

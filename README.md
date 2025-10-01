# 🚀 Guía para colaborar en este proyecto con *Forks* y *Pull Requests*

Instrucciones para añadir código al repositorio.

---

## 1. Haz un **fork** del repositorio

1. Entra en el repositorio principal en GitHub (este).
2. Arriba a la derecha, haz clic en el botón **Fork**.
3. Esto creará una copia del repositorio en **tu cuenta de GitHub**.

---

## 2. Clona tu fork a tu ordenador (con clicks)

1. Ve a tu fork (el repositorio en **tu cuenta**).
2. Haz clic en el botón verde **Code**.
3. Copia la URL que aparece (HTTPS).
4. Abre **Visual Studio Code**.
5. En la barra lateral izquierda, entra en el icono de **Source Control** (el que parece una ramita con puntos).
6. Pulsa en **Clone Repository**.
7. Pega la URL que copiaste de tu fork y elige una carpeta en tu ordenador para guardar el proyecto.

Ya tienes el repositorio en tu PC.

---

## 3. Crea una rama para trabajar (con clicks)

1. En Visual Studio Code, fíjate abajo a la izquierda: verás el nombre de la rama (por defecto `main`).
2. Haz clic en el nombre de la rama.
3. Selecciona **Create new branch…**.
4. Escribe un nombre para tu rama, en nuestro caso preferiblemente: `feature/nueva-pagina` o `fix/bug-header`.
5. Cuando VS Code pregunte desde qué rama crear la nueva, selecciona **dev** (no desde main).

Ahora ya estás trabajando en tu propia rama.
 

---

## 4. Sube tus cambios a tu fork

1. En VS Code, cuando hagas cambios, verás los archivos modificados en la sección **Source Control**.
2. Añade un mensaje de commit y pulsa el ✔️ para confirmar.
3. Luego, en la parte superior de esa misma vista, pulsa en **Sync Changes** (o **Push** si aparece).

Ahora tus cambios están en TU fork.

---

## 5. Haz un Pull Request (PR)

1. Ve a **tu fork en GitHub**.
2. Verás un botón que dice **Contribute → Open Pull Request**.
3. Asegúrate de que el destino (base) sea:

   * **Repositorio original → rama `dev`**
   * Y que la rama de origen sea tu rama en tu fork.
4. Rellena la descripción con lo que has cambiado.
5. Crea el Pull Request.

El administrador del proyecto (yo) revisará el PR y lo aprobará o pedirá cambios.

---

## Flujo de trabajo recomendado (*Git Flow simplificado*)

* La rama **main** → siempre debe estar limpia y lista para producción.
* La rama **dev** → es donde juntamos todo el trabajo en progreso.
* Cada colaborador:

  1. Crea su propia rama desde **dev**.
  2. Trabaja en sus cambios.
  3. Hace commit y push a SU fork.
  4. Abre un Pull Request (PR) hacia la rama **dev** del repositorio original.
2. Hacer cambios → Commit → Push a tu fork.
3. Pull Request → Hacia `dev` del repo principal.

---

¡Listo! 🎉 Así mantenemos el proyecto organizado y fácil de colaborar.

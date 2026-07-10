# Semana 1: Introducción y repositorio

## Introducción a Python


<span class="badge badge-blue">🧑🏻‍💻 Programación</span>
<span class="badge badge-green">🐍 Python</span>

Algunos conceptos sobre el lenguaje de programación de Python....


<div class="course-card book-card">
    <img class="book-cover"
         src="Images/books/python_para_todos.png"
         alt="Python para todos">
    <div class="course-content">
        <h3>Python para todos</h3>
        <p>
            <strong>Autores:</strong>
            Raúl González Duque
        </p>
        <div class="course-links">
            <a class="course-link"
               href="https://drive.google.com/file/d/1NfZvol-egLihav6XIDiVVU242tNbYy_I/view"
               target="_blank">
                📖 Abrir libro
            </a>
        </div>
    </div>
</div>


<div class="course-card book-card">
    <img class="book-cover"
         src="Images/books/aprenda_pensar_como_programador.png"
         alt="Aprenda a Pensar Como un Programador">
    <div class="course-content">
        <h3>Aprenda a Pensar Como un Programador con Python</h3>
        <p>
            <strong>Autores:</strong>
            Allen Downey, Jeffrey Elkner y Chris Meyers
        </p>
        <div class="course-links">
            <a class="course-link"
               href="https://drive.google.com/file/d/1jQ2fEEyt6PO0Ds9k8Vk04mhBjKX95Ms7/view?usp=sharing"
               target="_blank">
                📖 Abrir libro
            </a>
        </div>
    </div>
</div>


<div class="course-card book-card">
    <img class="book-cover"
         src="Images/books/el-libro-de-python.png"
         alt="Aprenda a Pensar Como un Programador">
    <div class="course-content">
        <h3>El Libro De Python</h3>
        <p>
            <strong>Autores:</strong>
            Alvaro Revuelta
        </p>
        <div class="course-links">
            <a class="course-link"
               href="https://ellibrodepython.com/"
               target="_blank">
                📖 Abrir libro
            </a>
        </div>
    </div>
</div>


## ¿Cómo comenzar a programar?

Para desarrollar las actividades del curso necesitarás un entorno en el que puedas escribir y ejecutar código Python.

No todas las opciones que aparecen a continuación cumplen la misma función. Puedes comenzar rápidamente con **Google Colab**, trabajar de manera local con **Visual Studio Code**, organizar las dependencias mediante **entornos virtuales** y guardar tus avances en **GitHub**.

<div class="callout">
<strong>💡 Ruta recomendada para comenzar:</strong><br>
Google Colab → Visual Studio Code → Entornos virtuales → GitHub
</div>



<div class="course-card notebook-card">

<div class="course-icon">
☁️
</div>

<div class="course-content">

<h3>Opción 1 · Google Colab</h3>

<p>
Programa y ejecuta notebooks de Python directamente desde el navegador,
sin instalar software en tu computador.
</p>

<div style="margin:12px 0;">

<span class="badge badge-green">⭐ Recomendada para comenzar</span>
<span class="badge badge-blue">🌐 En la nube</span>
<span class="badge badge-purple">⚡ GPU y TPU</span>

</div>

<h4>Ventajas principales</h4>

<ul>
<li>No requiere configuración inicial.</li>
<li>Permite abrir y compartir notebooks fácilmente.</li>
<li>Puede ofrecer acceso gratuito a GPU y TPU.</li>
<li>Se integra con Google Drive y GitHub.</li>
</ul>

<p>
Ten presente que los recursos gratuitos, los tiempos de ejecución y la
disponibilidad de GPU pueden variar.
</p>

<div class="course-links">

<a class="course-link"
href="https://colab.research.google.com/"
target="_blank">
🚀 Abrir Google Colab
</a>

<a class="course-link"
href="https://www.youtube.com/watch?v=8VFYs3Ot_aA"
target="_blank">
📓 Ver tutorial
</a>

</div>
</div>
</div>


<div class="course-card code-card">

<div class="course-icon">
💻
</div>

<div class="course-content">

<h3>Opción 2 · Visual Studio Code</h3>

<p>
Trabaja localmente con tus archivos Python, notebooks, repositorios y
proyectos completos desde un editor ligero y extensible.
</p>

<div style="margin:12px 0;">

<span class="badge badge-blue">🖥️ Instalación local</span>
<span class="badge badge-green">🐍 Python</span>
<span class="badge badge-yellow">📓 Jupyter Notebooks</span>

</div>

<h4>¿Qué necesitas instalar?</h4>

<ul>
<li>Python.</li>
<li>Visual Studio Code.</li>
<li>La extensión oficial de Python.</li>
<li>La extensión de Jupyter, cuando trabajes con archivos <code>.ipynb</code>.</li>
</ul>

<p>
Para este curso recomiendo principalmente <strong>Visual Studio Code</strong>.
Visual Studio completo puede ser útil para proyectos más grandes, pero resulta
más pesado y no es necesario para comenzar con Python.
</p>

<div class="course-links">

<a class="course-link"
href="https://code.visualstudio.com/"
target="_blank">
⬇️ Descargar VS Code
</a>

<a class="course-link"
href="https://www.youtube.com/watch?v=md2pQj144PA"
target="_blank">
🐍 Configurar Python
</a>

<a class="course-link"
href="https://code.visualstudio.com/docs/datascience/jupyter-notebooks"
target="_blank">
📓 Usar notebooks
</a>

</div>
</div>
</div>


<div class="course-card activity-card">

<div class="course-icon">
📦
</div>

<div class="course-content">

<h3>Opción 3 · Entornos virtuales</h3>

<p>
Crea espacios aislados para instalar las librerías y versiones que necesita
cada proyecto sin afectar los demás proyectos de tu computador.
</p>

<div style="margin:12px 0;">

<span class="badge badge-green">✅ Recomendado</span>
<span class="badge badge-blue">📦 Dependencias aisladas</span>
<span class="badge badge-yellow">🐍 venv</span>

</div>

<h4>¿Por qué utilizarlos?</h4>

<ul>
<li>Evitan conflictos entre versiones de paquetes.</li>
<li>Permiten reproducir el mismo entorno en distintos computadores.</li>
<li>Facilitan el trabajo colaborativo.</li>
<li>Mantienen cada proyecto organizado e independiente.</li>
</ul>

<h4>Comandos básicos</h4>

<pre><code>python -m venv .venv

# Windows
.venv\Scripts\activate

# Linux o macOS
source .venv/bin/activate

pip install nombre-paquete
</code></pre>

<div class="course-links">

<a class="course-link"
href="https://docs.python.org/es/3/tutorial/venv.html"
target="_blank">
📖 Ver documentación
</a>

</div>
</div>
</div>


<div class="course-card resource-card">

<div class="course-icon">
🐙
</div>

<div class="course-content">

<h3>GitHub · Control de versiones</h3>

<p>
GitHub permite almacenar proyectos, conservar el historial de cambios,
colaborar con otras personas y recuperar versiones anteriores del código.
</p>

<div style="margin:12px 0;">

<span class="badge badge-blue">🔄 Control de versiones</span>
<span class="badge badge-green">🤝 Colaboración</span>
<span class="badge badge-purple">☁️ Repositorios remotos</span>

</div>

<p>
Git es el sistema que registra los cambios realizados en los archivos.
GitHub es una plataforma en la nube que permite alojar repositorios Git y
trabajar colaborativamente sobre ellos.
</p>

<h4>En este curso lo utilizaremos para:</h4>

<ul>
<li>Consultar los materiales de cada semana.</li>
<li>Descargar y actualizar notebooks.</li>
<li>Crear bifurcaciones de repositorios.</li>
<li>Guardar versiones de los proyectos.</li>
<li>Compartir resultados y ejercicios.</li>
</ul>

<div class="course-links">

<!-- <a class="course-link"
href="https://github.com/"
target="_blank">
🐙 Abrir GitHub
</a> -->

<a class="course-link"
href="https://docs.github.com/es/get-started/using-git/about-git"
target="_blank">
📖 Introducción a Git
</a>

<a class="course-link"
href="https://docs.github.com/es/get-started/signing-up-for-github/signing-up-for-a-new-github-account"
target="_blank">
👤 Crear cuenta
</a>

<a class="course-link"
href="https://docs.github.com/es/get-started/getting-started-with-git/setting-your-username-in-git"
target="_blank">
👤 Configurar usuario
</a>

<a class="course-link"
href="https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens"
target="_blank">
🔑 Crear token
</a>

<a class="course-link"
href="https://docs.github.com/es/get-started/getting-started-with-git/about-remote-repositories"
target="_blank">
🌐 Repositorios remotos
</a>

<a class="course-link"
href="https://docs.github.com/es/get-started/getting-started-with-git/about-remote-repositories"
target="_blank">
📖 Lenguaje Markdown
</a>

<a class="course-link"
href="https://docs.github.com/es/get-started/getting-started-with-git/about-remote-repositories"
target="_blank">
🔄 Bifurcaciones (Forks)
</a>

</div>
</div>
</div>


## Configurando el repositorio 
# Configuración del repositorio

En esta sección aprenderás a configurar el repositorio de GitHub en Google Colab. Esto te permitirá realizar las actividades del curso, guardar tus cambios y hacer seguimiento a tu código mediante GitHub.

Primero, necesitarás crear una cuenta en [GitHub](https://github.com/) si aún no tienes una. Si ya dispones de una cuenta, puedes comenzar directamente desde el **Paso 1**.

> **NOTA:** Como estudiante, también puedes solicitar una cuenta **GitHub Pro** de manera gratuita mediante el programa **GitHub Education**. Si te interesa, puedes consultar las instrucciones en el siguiente [enlace](https://education.github.com/discount_requests/application).

---

## Paso 1: Crear un *Fork* del repositorio del curso

Para poder realizar tus propias modificaciones sin afectar el repositorio original, primero debes crear un **Fork** del repositorio.

Sigue estos pasos:

- Ve al [repositorio del curso](https://github.com/rubenfonnegra/machine_learning) en GitHub.
- Haz clic en el botón **Fork**, ubicado en la esquina superior derecha.
- Selecciona el propietario del nuevo repositorio. Si perteneces a varias organizaciones, selecciona tu **nombre de usuario**.
- **Recomendación:** No cambies el nombre del repositorio.
- Haz clic en **Create fork**.

> **Nota:** Si necesitas más información sobre los *Forks*, consulta este [enlace](https://docs.github.com/es/get-started/quickstart/fork-a-repo#propose-changes-to-someone-elses-project).

---

## Paso 2: Clonar tu repositorio (*Fork*)

- Ve a tu [Google Drive](https://drive.google.com/drive/u/0/my-drive), crea un nuevo Notebook de Google Colab y ábrelo.
- Monta tu Google Drive desde Colab. Luego, abre una terminal y navega hasta la carpeta donde deseas descargar el repositorio utilizando el comando `cd`.

```bash
cd /content/drive/ruta/a/tu/carpeta/en/drive
```

- Ve a tu *Fork* en GitHub (`github.com/<tu_usuario>/machine_learning`).
- Haz clic en el botón **<> Code**.
- Copia la URL que aparece en la pestaña **HTTPS**.
- Regresa a Colab y ejecuta el comando en la terminal. Esto descargará todo el contenido del repositorio en tu google drive:

```bash
git clone https://github.com/<tu_usuario>/machine_learning.git
```

- Entra a la carpeta del repositorio desde la terminal utilizando el comando `cd`.

```bash
cd machine_learning/
```

> **Nota:** Si necesitas más información sobre el proceso de clonado, consulta este [enlace](https://docs.github.com/es/get-started/quickstart/fork-a-repo#propose-changes-to-someone-elses-project).

---

## Paso 3: Configurar tu repositorio local

- En este punto, cada que abras un nuevo notebook deberás montar el drive y acceder a la carpeta desde la terminal usando el comando `cd`. Despues de esto, verifica que te encuentras en el directorio correcto utilizando `ls`.

```bash
cd /content/drive/ruta/a/tu/carpeta/en/drive/machine_learning/
ls
```

- Verifica el estado del repositorio utilizando el comando `git status`. Como acabas de clonar un *Fork* nuevo, no deberías observar cambios pendientes.

```bash
git status
```

- Configura tu nombre y correo electrónico para poder registrar (*commit*) y subir (*push*) cambios desde Google Colab.
**Importante:** Esta configuración debe realizarse cada vez que trabajes desde un entorno nuevo de Colab.

```bash
git config --global user.email "tu-correo-personal@gmail.com"
 git config --global user.name "Tu nombre o apodo"
```

Una vez completado este paso, ya podrás comenzar a realizar modificaciones sobre tu repositorio local.

---

## Paso 4: Configurar tu repositorio remoto

- Verifica nuevamente que te encuentras dentro del repositorio.

```bash
!ls
```

- Para poder enviar cambios a GitHub necesitarás crear un **Personal Access Token**.
Sigue las instrucciones del siguiente [enlace](https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).
**IMPORTANTE:** GitHub solo mostrará el token una única vez. Guárdalo en un lugar seguro.

- Una vez creado tu token, descarga el archivo `repo_keys_sample.txt` ubicado en la carpeta `Sem_01` en el repositorio y reemplaza el contenido por tu propio token.

```text
GIT_KEY=<tu_token>
```

- Guarda el archivo con el nombre:

```text
repo_keys.txt
```

- Sube el archivo nuevamente a tu Google Drive, en la misma carpeta (`Sem_01`)
**⚠️ IMPORTANTE:** **Nunca** agregues ni sincronices el archivo `repo_keys.txt` con tu repositorio de GitHub.Este archivo contiene un token de acceso personal y tu repositorio es público. Si lo subes accidentalmente, cualquier persona podrá utilizar tu token para acceder a TODOS tus repositorios.

- Crea una celda en el notebook y configura tu nombre de usuario y el nombre del repositorio.

```python
from Sem_01.repo_private import GIT_KEY #importar el token

git_token = GIT_KEY
username = "tu_usuario_github"
repository = "machine_learning"
```

- Ejecuta la siguiente instruccion desde la terminal para agrega el repositorio remoto al que enviarás los cambios.

```bash
git remote set-url origin https://{git_token}@github.com/{username}/{repository}.git
```

---

## Paso 5: Agregar cambios a tu *Fork*

- Crea un archivo llamado:

```text
example.txt
```

- Agrega el archivo al área de seguimiento (*staging area*) utilizando `git add`.

```python
!git add example.txt
```

> También puedes agregar varios archivos o carpetas al mismo tiempo. Solo los archivos agregados mediante `git add` serán incluidos en el siguiente *commit*.

- Crea un *commit* con un mensaje descriptivo.

```python
!git commit -m "Agregando el archivo example.txt"
```

---

## Paso 6: Subir los cambios a GitHub

Para subir los cambios al repositorio remoto utiliza:

```python
!git push -u origin master
```

- Verifica en GitHub que los archivos hayan sido actualizados correctamente.

> **NOTA:** Solo es posible subir cambios que hayan sido previamente registrados mediante un **commit**. Si olvidas ejecutar `git commit`, los cambios no serán enviados al repositorio remoto.

---

# Actualizar tu *Fork*

Esta sección será útil cuando el repositorio original del curso haya recibido cambios y desees sincronizarlos con tu propio *Fork*.

- Primero, monta nuevamente tu Google Drive y navega hasta el repositorio.

```python
%cd /content/drive/path/to/your/folder/
```

- Configura nuevamente tu nombre y correo electrónico.

```python
!git config --global user.email "tu-correo@pascualbravo.edu.co"
!git config --global user.name "Tu nombre o apodo"
```

- Agrega el repositorio original como repositorio **upstream**.

```python
# Agrega el repositorio original
!git remote add upstream https://github.com/rubenfonnegra/machine_learning.git
```

- Descarga los cambios del repositorio original.

```python
# Descarga todas las ramas del repositorio original
!git fetch upstream
```

- Cambia a la rama principal y aplica las actualizaciones.

```python
!git checkout master

# Reescribe la rama master aplicando los cambios del repositorio original
!git rebase upstream/master
```

- Si durante el proceso aparecen conflictos, puedes resolverlos manualmente o continuar utilizando:

```python
!git rebase --skip
```

- Finalmente, sincroniza tu *Fork* con GitHub.

```python
!git push -f origin master
```
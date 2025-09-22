# _Proyecto1_

_Este repositorio es un ejemplo de proyecto en equipo_

## _Cómo contribuir_

1. **_Haz un fork del repositorio_**

   - _Ve a la página principal del repositorio y haz clic en el botón "Fork" en la esquina superior derecha. Esto creará una copia de este repositorio en tu cuenta de GitHub._

2. **_Clona el repositorio forked_**

   - _En Github: Ve a tu perfil de GitHub y encuentra el repositorio forked (con tu nombre de usuario). Haz clic en él para abrirlo._
   - _En tu ordenador personal:para clonarlo con la clave ssh GitHub reconoce tu clave y directamente te deja hacer push o pull._(necesario tener tus claves ssh y asociarlas a tu usuario en github)

     ```bash
     git clone git@github.com:Tu_Usuario/proyecto1.git

     cd Proyecto1
     ```

3. **_Realiza tus cambios_**

   - _En Github: Navega a los archivos que deseas modificar. Realiza los cambios necesarios y luego baja a la parte inferior de la página para confirmar tus cambios, escribiendo un mensaje descriptivo y presionando el botón "Commit changes"._
   - _En tu ordenador personal:_
     1. _Edita los archivos con tu editor favorito (Vscode)_
     2. _Verifica los cambios con:_
     ```bash
     git status
     git diff
     ```
     3. _Agrega los archivos modificados:_
     ```bash
     git add nombre-del-archivo  # Para un archivo específico
     git add .                   # Para todos los cambios
     ```
     4. _Haz un commit descriptivo:_
     ```bash
     git commit -m "Descripción clara de los cambios"
     ```

4. **_Sincroniza tu fork con el repositorio original_**

   - _En Github: Para mantener tu fork actualizado con los cambios más recientes del repositorio original:_
     1. _Ve a la página principal de tu repositorio forked._
     2. _Haz clic en el botón "Sync fork" para sincronizar tu fork con el repositorio original._
   - _En tu ordenador personal: Configura el repositorio original como upstream_
     ```bash
     git remote add upstream https://github.com/bienvenidoconquerx/proyecto1.git
     ```
     _Verifica con_
     ```bash
     git remote -v
     ```
     _Antes de subir tus cambios, sincroniza tu rama desde `upstream`:_
     ```bash
     git fetch upstream
     ```

5. **_Crea un pull request_**

   - _En Github: Si tus cambios están listos, ve a la página principal de tu repositorio forked y haz clic en "Contribute" y posteriormente "Open pull request"._
   - _En tu ordenador personal:_
     ```bash
     git push -u origin main
     # Y tus cambios en local ya se han subido a Github
     ```
     _Ya podemos hacer la pull request en Github haciendo haz clic en "Contribute" y posteriormente "Open pull request"._

6. **_Describe tu pull request_**

- _En Github: Proporciona una descripción detallada de los cambios que has realizado. Incluye cualquier información relevante que pueda ayudar a entender mejor tus contribuciones y haz clic en "Create pull request" para enviar._

7.  **_Espera la revisión_**

- _En Github: Uno de los mantenedores del proyecto revisará tu pull request y te enviará una respuesta._

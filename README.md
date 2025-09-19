# *Proyecto1*
*Este repositorio es un ejemplo de proyecto en equipo*

## *Cómo contribuir*

1. ***Haz un fork del repositorio***
   - *Ve a la página principal del repositorio y haz clic en el botón "Fork" en la esquina superior derecha. Esto creará una copia de este repositorio en tu cuenta de GitHub.*

2. ***Clona el repositorio forked***  
   - *En Github: Ve a tu perfil de GitHub y encuentra el repositorio forked (con tu nombre de usuario). Haz clic en él para abrirlo.*
   - *En tu ordenador personal:*
      ```bash
      git clone https://github.com/TuUsuario/Proyecto1.git
      cd Proyecto1
      ```

3. ***Realiza tus cambios***  
   - *En Github: Navega a los archivos que deseas modificar. Realiza los cambios necesarios y luego baja a la parte inferior de la página para confirmar tus cambios, escribiendo un mensaje descriptivo y presionando el botón "Commit changes".*
   - *En tu ordenador personal:*
      1. *Edita los archivos con tu editor favorito (Vscode)*
      2. *Verifica los cambios con:*  
      ```bash
      git status
      git diff
      ```
      3. *Agrega los archivos modificados:*  
      ```bash
      git add nombre-del-archivo  # Para un archivo específico
      git add .                   # Para todos los cambios
      ```
      4. *Haz un commit descriptivo:*  
      ```bash
      git commit -m "Descripción clara de los cambios"
      ```

4. ***Sincroniza tu fork con el repositorio original***  
   - *En Github: Para mantener tu fork actualizado con los cambios más recientes del repositorio original:*
      1. *Ve a la página principal de tu repositorio forked.*
      2. *Haz clic en el botón "Sync fork" para sincronizar tu fork con el repositorio original.*
   - *En tu ordenador personal: Configura el repositorio original como upstream*
      ```bash
      git remote add upstream https://github.com/bienvenidoconquerx/proyecto1.git
      ```
      *Verifica con* 
      ```bash
      git remote -v
      ```
      *Antes de subir tus cambios, sincroniza tu rama desde `upstream`:*  
      ```bash
      git fetch upstream
      ```
      


5. ***Crea un pull request***  
   - *En Github: Si tus cambios están listos, ve a la página principal de tu repositorio forked y haz clic en "Contribute" y posteriormente "Open pull request".*
   - *En tu ordenador personal:*
      ```bash
      git push -u origin main
      # Y tus cambios en local ya se han subido a Github
      ```
      *Ya podemos hacer la pull request en Github haciendo haz clic en "Contribute" y posteriormente "Open pull request".*

6.  ***Describe tu pull request***  
   - *En Github: Proporciona una descripción detallada de los cambios que has realizado. Incluye cualquier información relevante que pueda ayudar a entender mejor tus contribuciones y haz clic en "Create pull request" para enviar.*


7.  ***Espera la revisión***  
   - *En Github: Uno de los mantenedores del proyecto revisará tu pull request y te enviará una respuesta.*

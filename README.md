# Spam_metricas
# Instrucciones
## 1. Realizar pull de este proyecto
- Clona o realiza un pull del repositorio actual.
## 2. Crear una nueva aplicación en Gmail
- Siguiendo este [este enlace](https://support.google.com/accounts/answer/185833?hl=en) crear una nueva aplicacion con nuestro gmail para obtener la password que luego utilizaremos
## 3. Modificar el archivo `.env`
<img width="534" alt="image" src="https://github.com/user-attachments/assets/cee58568-d2ca-4db8-9044-d6e8c11e72c5">

## 4. Crear una cuenta en [PythonAnywhere](https://www.pythonanywhere.com)
- Accede a la sección de **Consoles** y crea una nueva consola.
- Ejecuta los siguientes comandos para configurar el entorno y las dependencias:
   ```bash
  mkvirtualenv spam_metricas --python=python3.10
  workon spam_metricas
  pip install schedule

<img width="1312" alt="image" src="https://github.com/user-attachments/assets/3751440f-fa9b-48a0-a291-4f9333a5ecdc">

## 6. Subir archivos al directorio
- En PythonAnywhere, dirígete a la sección Files.
- Crea un nuevo directorio llamado spam_metricas.
- Sube los archivos main.py y env.py con las variables actualizadas.
  
<img width="1245" alt="image" src="https://github.com/user-attachments/assets/7da82049-ccee-4933-8a6d-8c2c6b2a3417">

## 7. Crear una tarea en PythonAnywhere
- Accede a la sección **Tasks**.
- Crea una tarea para ejecutar el script diariamente.
- Nota: La tarea utiliza el horario UTC. Se recomienda configurarla a las 08:30 UTC, ya que el primer correo se enviará a las 09:00 UTC.

<img width="1166" alt="image" src="https://github.com/user-attachments/assets/5ae11cd4-10fa-4215-a226-e424c2628d27">

## Consideraciones importantes
- Tarea gratuita: Si usas una cuenta gratuita, la tarea caducará en aproximadamente un mes. Tendrás que recrearla periódicamente.
- Tarea recurrente: Con una cuenta paga, puedes configurar una tarea recurrente sin esta limitación.
- Completar los 3 recipients porque sino fallara y son 3 porque casualmente tenemos 3 supervisores.

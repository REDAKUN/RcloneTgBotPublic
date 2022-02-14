# Commandos del bot 
- subir - subir a la nube 
- copiar - copiar de una nube a la otra
- configuracion - configurar rclone 
- info - info del bot 
- exec - ejecutar comandos linux 
- logs - obtener logs del servidor 
- servidor - obtener info del servidor
- test_velocidad- test velocidad 
- limpiar- limpiar descargas

# Secrets para github
    HEROKU_API_KEY
    HEROKU_APP_NAME
    HEROKU_EMAIL

# Variables Obligatorias 
- API_HASH 
- API_ID 
- BOT_TOKEN 
- OWNER_ID 
- RCLONE_CONFIG    
    
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=)    


# Deploy Manualmente: 
- sudo apt update 
- sudo apt install -y python3.8 
- sudo apt install -y python3-venv 
- python3 -m venv venv 
- source venv/bin/activate 
- pip install -r requirements.txt 
- curl https://rclone.org/install.sh | bash
- chmod 777 start.sh
- ./start.sh




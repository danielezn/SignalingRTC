Node v4.8.4

En carpeta Kurento

# Crear la imagen
sudo docker build -t paychat-rtc:15062017-2 .

# Correr la imagen en puerto 8888
sudo docker run -d --name kurento -p 8888:8888 paychat-rtc:15062017-2

En carpeta App
cd static
bower install
cd ..
npm install
npm start
# Crear la imagen
sudo docker build -t paychat-rtc:15062017-2 .

# Correr la imagen en puerto 8888
sudo docker run -d --name kurento -p 8888:8888 paychat-rtc:15062017-2
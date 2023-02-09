# Despliegue de una aplicación Laravel en un VPS

### 1. Lo primero que tenemos que hacer es ir al panel de control del VPS
![image](https://user-images.githubusercontent.com/115020443/217837697-15fe0504-9fb4-4988-ab89-135d34af3a1b.png)

### 2. Ponemos el nombre de nuestro usuario y le damos a "next"
![image](https://user-images.githubusercontent.com/115020443/217837754-52d1eb93-364c-47ed-bbe6-658cff398d19.png)

### 3. Ponemos la contraseña de nuestro usuario y le damos a "next"
![image](https://user-images.githubusercontent.com/115020443/217837813-b5c975e9-12d6-485f-b320-79d096032fac.png)

### 4. Cuando entramos al panel de control, le damos a "Add Web Domain"
![image](https://user-images.githubusercontent.com/115020443/217837840-b05c8906-d5b8-4bcd-b173-cc551c0b7d16.png)

### 5. En "Domain", ponemos el nombre de dominio que queremos (En mi caso, usé un subdominio "laravel" para la página) y le damos a "Save"
![image](https://user-images.githubusercontent.com/115020443/217837859-f50649d6-ac29-46ef-b204-5eef6449bd2b.png)

### 6. Aquí se ve que se ha creado el dominio, ahora clicamos sobre el dominio
![image](https://user-images.githubusercontent.com/115020443/217837869-4f6c29ec-4d05-431c-88a3-648e10824dac.png)

### 7. Ahora en otra pestaña, nos vamos a la página donde tenemos contratado el dominio (En mi caso, [Namecheap](https://www.namecheap.com/)). Entramos en el dashboard y le damos a "MANAGE"
![image](https://user-images.githubusercontent.com/115020443/217837887-56cd5dd1-442f-4ceb-91d6-0f210166e3cf.png)

### 8. Entramos en "Advanced DNS"
![image](https://user-images.githubusercontent.com/115020443/217837913-b6573a0c-adeb-4752-bd4d-ad7cc27c1025.png)

### 9. La primera cosa que tenemos que hacer es clicar "ADD NEW RECORD", despues seleccionamos que sea un "A Record", ponemos el nombre del subdominio, ponemos la ip del VPS y luego clicamos el tic
![image](https://user-images.githubusercontent.com/115020443/217837943-88c82aec-e0c4-4d39-8958-8ae24667538f.png)

### 10. Ahora volvemos al panel de control del VPS, marcamos todas las opciones que estan señaladas para habilitar SSL en el dominio y luego le damos a "Save"
![image](https://user-images.githubusercontent.com/115020443/217837974-725c44c8-1f86-40fb-845d-b7837ae5d5f2.png)

### 11. Volvemos a la página princial del panel de control, aquí se ve que el dominio tiene SSL activado. Ahora le damos al icono del lápiz
![image](https://user-images.githubusercontent.com/115020443/217837997-316a9c80-d32c-463a-ab39-fbe2bce7c36f.png)

### 12. Le damos a "Quick Install App"
![image](https://user-images.githubusercontent.com/115020443/217838019-ea334c06-7e51-4386-885f-494c0adadb8b.png)

### 13. Donde pone Laravel le damos a "Setup"
![image](https://user-images.githubusercontent.com/115020443/217838040-f39837db-b592-4688-b21a-fde9eb920afe.png)

### 14. Ahora creamos una base de datos para esta aplicación, ponemos un nombre para la base de datos, un nombre para el usuario y una contraseña para el usuario. Despues le damos a "Install", la instalación tardará unos minutos
![image](https://user-images.githubusercontent.com/115020443/217838065-62341a5d-97b8-4f79-8e2d-0ee481ca504c.png)

### 15. Cuando se acaba la instalación, entramos en la aplicación Laravel que hemos creado usando el dominio que hemos creado
![image](https://user-images.githubusercontent.com/115020443/217838088-658d06c7-e994-4867-bec0-da336e74810f.png)

### 16. Aquí se ve que la aplicación Laravel
![image](https://user-images.githubusercontent.com/115020443/217838103-72c52522-efbf-4da0-8bf9-e0bb247c3afb.png)

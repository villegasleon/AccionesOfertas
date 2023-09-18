# AccionesOfertas
Una app de envió de alertas a tu correo electrónico sobre las Acciones que han tenido una variación en su precio de más del 5% respecto al precio de cierre del dia anterior. Con teso podras tener una idea y posteriormente un analisis,  para saber si la acción vale la pena o no comprarla. Esto no es un consejo de compra o venta. Simplemente es una referencia para que tu desarrolles tu analisis por cuenta propia. Las acciones con templadas aca, son solamente las listas en SP&500. 
Para esta app, necesitaras:
1.Abrir una cuenta en : https://iexcloud.io/ , luego ir  a https://iexcloud.io/docs/api/ y obtendras tu token.
2. Correo electronico de gmail
3. Configurar en tu gmail tu password para Apis, esto evitara que expongas directamente tu password en el codigo.
4. Debes instalar algunas librerias en entorno virtual con pip install:
 time
 requests
 smtplib
 MIMEText
 MIMEMultipart
5. Listo, la app recorrera el listado de accione sy si encuentra variaciones significativas de mas del 5% te las enviara al correo que elegiste como destinatario.



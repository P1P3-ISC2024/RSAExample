# RSAExample
Este programa es un ejemplo sobre como utilizar RSA para cifrar o decifrar un texto a traves de la librería crypto de Python

-Características:
  1. Puede generar las llaves RSA (pública y privada) en archivos (.pem).
  2. Cifra un archivo de texto con la llave pública de la persona indicada.
  3. Decifra un archivo que fue envíado para tí con tu llave privada.
  4. Cuenta con interfaz gráfica.
  5. Cuenta con explorador de archivos.

-Notas:
  1. Abre la aplicación ejecutando el archivo **main.py**.
  2. NO COMPARTAS TU LLAVE PRIVADA!!!
  3. Los textos cifrados se guardarán en un txt llamado **mesage_C.txt**.
  4. Los textos decifrados se guardarán en un txt llamado **message_C_D.txt**.

-Pasos para generar las llaves:
  1. Ejecuta **main.py**.
  2. Selecciona la opción GENERATE KEYS.
  3. Presiona SELECT
  4. Presiona el botón GENERATE KEYS.
  5. espera a que generen los archivos **publicKey_A.pem** y **privateKey_A.pem**.

-Pasos para cifrar:
  1. Ejecuta **main.py**.
  2. Selecciona la opción ENCRYPT/DECRYPT.
  3. Presiona el botón SELECT.
  4. Presiona el botón KEY para buscar la llave pública a usar.
  5. Presiona el botón FILE para buscar el archivo de texto a cifrar.
  6. Presiona el botón ENCRYPT.
  7. Espera a que se genere el archivo **mesage_C.txt**.

-Pasos para decifrar:
  1. Ejecuta **main.py**.
  2. Selecciona la opción ENCRYPT/DECRYPT.
  3. Presiona el botón SELECT.
  4. Presiona el botón KEY para buscar tu llave privada.
  5. Presiona el botón ENCRYPTED FILE para buscar el archivo de texto a decifrar.
  6. Presiona el botón DECRYPT.
  7. Espera a que se genere el archivo **mesage_C_D.txt**.

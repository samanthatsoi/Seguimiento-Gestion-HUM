Documentacion por Seguimiento-Gestion-HUM.ipynb
Por: Samantha Tsoi

Resumen:
Este codigo analiza el archivo "Reporte-Seguimiento-Gestion-HUM.xlsx" por examinar la columna "Pregunta" y "Título". 
Este codigo solo analiza los datos de los hojas 'PREGUNTA HUM' y 'PREGUNTA ANTIGUAS' en el archivo 'Reporte-Seguimiento-Gestion-HUM.xlsx'.




Antes de ejecutarlo:
1. Asegúrate tener los archivos "Reporte-Seguimiento-Gestion-HUM.xlsx" y "preguntas_categoria.xlsx" y son actualizados. Los nombres del archivos deben ser exactamente escribido como arriba.
2. Asegúrate que el "Reporte-Seguimiento-Gestion-HUM.xlsx" solo tiene las fechas en la columna "Fecha pregunta", formateado como 'D/MM/YYYY' o 'DD/MM/YYYY'. No deba contener cualquier palabras.
3. Asegúrate que los archivos "Seguimiento-Gestion-HUM.ipynb", "Reporte-Seguimiento-Gestion-HUM.xlsx" y "preguntas_categoria.xlsx" son en la misma carpeta.
4. Asegúrate que tiene el Jupyter Notebook y Python en tu computadora. Si no los tienes, instálalos con está enlace: https://jupyter.org/install

Para ejecutarlo:
1. Abre la Terminal en tu Mac (o Console en tu Windows/PC).

2. Entra la carpeta donde los archivos (Seguimiento-Gestion-HUM.ipynb, Reporte-Seguimiento-Gestion-HUM.xlsx, preguntas_categoria.xlsx) se ubican.
	2a. Usa 'cd <nombre_de_carpeta>' a entrar una carpeta.
	2b. Usa 'cd ..' a regresar a la última carpeta.
	2c. Puede encontrar tu carpeta actual tipeando 'pwd' en tu Terminal (en Windows/PC, el comando es 'cwd').

3. Cuando has llegado a la carpeta donde los archivos se ubican, escribe 'jupyter notebook'. Una pagina web va a abrir con el enlace 'http://localhost:8888/tree'.

4. Haz click en 'Seguimiento-Gestion-HUM.ipynb'. Una otra pagina web va a abrir con el enalce 'http://localhost:8888/notebooks/Seguimiento-Gestion-HUM.ipynb'.

![jupyterhome](https://user-images.githubusercontent.com/8455299/57087836-eefafe00-6cce-11e9-884a-7b3fe33e86ef.png)

5. En tu Terminal, tipea 'pwd' (o 'cwd' en tu Windows/PC Console). Copia el resultado.

![terminal](https://user-images.githubusercontent.com/8455299/57087852-fa4e2980-6cce-11e9-9120-ee7565984d64.png)

6. Pégalo en la primera línea después "currentdirectory =".

![pwd](https://user-images.githubusercontent.com/8455299/57087804-dee31e80-6cce-11e9-8f05-731cf9d7aba5.png)

5. Encuentra y haz click en 'Cell' en la cima de la página.

6. Elige 'Run All' de las siguientes opcciones. Va a tomar cinco a diez minutos hasta está lista.

![runall](https://user-images.githubusercontent.com/8455299/57087732-b5c28e00-6cce-11e9-83d4-4f2c35656d2d.png)

# Sensores

## :trophy: C1.5 Reto en clase

Tipo de sensores de acuerdo con su uso aplicativo.

### :blue_book: Instrucciones

___

- De acuerdo con la información presentada por el asesor referente al tema tipos de sensores, contestar lo que se indica dentro del apartado desarrollo.
- Toda actividad o reto se deberá realizar utilizando el estilo **MarkDown con extension .md** y el entorno de desarrollo VSCode, debiendo ser elaborado como un documento **single page**, es decir si el documento cuanta con imágenes, enlaces o cualquier documento externo debe ser accedido desde etiquetas y enlaces.
- Es requisito que el archivo .md contenga una etiqueta del enlace al repositorio de su documento en Github, por ejemplo **Enlace a mi GitHub**
- Al concluir el reto el reto se deberá subir a github el archivo .md creado.
- Desde el archivo **.md** se debe exportar un archivo **.pdf** con la nomenclatura **C1.5_NombreAlumno_Equipo.pdf**, el cual deberá subirse a classroom dentro de su apartado correspondiente, para que sirva como evidencia de su entrega; siendo esta plataforma **oficial** aquí se recibirá la calificación de su actividad por individual.
- Considerando que el archivo .pdf, fue obtenido desde archivo .md, ambos deben ser idénticos y mostrar el mismo contenido.
- Su repositorio ademas de que debe contar con un archivo **readme**.md dentro de su directorio raíz, con la información como datos del estudiante, equipo de trabajo, materia, carrera, datos del asesor, e incluso logotipo o imágenes, debe tener un apartado de contenidos o indice, los cuales realmente son ligas o **enlaces a sus documentos .md**, _evite utilizar texto_ para indicar enlaces internos o externo.
- Se propone una estructura tal como esta indicada abajo, sin embargo puede utilizarse cualquier otra que le apoye para organizar su repositorio.  
``` 
| readme.md
| | blog
| | | C0.1_x.md
| | | C0.2_x.md
| | | C1.1_x.md
| | | C1.2_x.md
| | | C1.3_x.md
| | | C1.4_x.md
| | | C1.5_x.md
| | img
| | docs
| | | A1.1_x.md
| | | A1.2_x.md
```

### :pencil2: Desarrollo
___

1. Dada la siguiente tabla responda mínimo tres tipos de sensores que se podrían utilizar en función a la variable a medir en cada aplicación

    Usos aplicativos | Tipo de sensor |
    ---------|----------|
    Temperatura | Termopares, termisores y RTD|
    Presencia |Infrarrojos, ultrasónicos y magnético |
    Distancia |Láser, por ultrasonido y magnetostrictivos o de imán|
    Presión |Manómetros digitales , escáneres de presión y sensores diferenciales|
    Iluminación |Fototransistor, fotodiodo y célula fotoeléctrica |

2. Investigue en caso de considerlo, sobre que tipo de sensores pueden ser utilizados para las siguientes condiciones:
  - Que tipo de sensor se requiere para identificar cuantos televisores están siendo manufacturados en una linea producción?    
  - R: **Sensor de proximodad** ,este se utilizaría en la banda deproducción en la cual van pasando los televisores. 
  - Que tipo de sensor se requiere para  detectar cuando una persona entra a un cuarto de seguridad?    
  -  R: **Sensor de presencia infrarojo**
  - Que tipo de sensor se requiere para  encender una lampara durante las noches y durante el dia se apague.    
  - R: **Sensor Fotorresistencia LDR** , este sensor enciende un led o foco dependiendo de la cantidad de luz que este reciba. Si hay ausencia de luz, este encenderia, si sucede lo contrario entonces estará apagado. 
  - Que tipo de sensor se requiere para saber que tanto ha subido el nivel de temperatura en el ambiente en una zona especifica?
  - R: **Sensor DHT22** , es preferible elegir este ya que es más preciso a la hora de tomar pruebas 
  - Que tipo de sensor se requiere para conocer cuanto pesa un producto que se esta vendiendo por kilogramos?   
  - R: **Sensor de peso o celda de carga** es un sensor diseñado para bascula.  
  - Que tipo de sensor se requiere para saber a que distancia esta acercándose un objeto a otro para evitar que halla un impacto?   
  - R: **Sensor fotoeléctrico**

___

### :bomb: Rubrica

| Criterios     | Descripción                                                                                  | Puntaje |
| ------------- | -------------------------------------------------------------------------------------------- | ------- |
| Instrucciones | Se cumple con cada uno de los puntos indicados dentro del apartado Instrucciones?            | 20 |
| Desarrollo    | Se respondió a cada uno de los puntos solicitados dentro del desarrollo de la actividad?     | 80      |

:house: [Ir a mi repositorio](https://github.com/JuanPSG/SistemasProgramables)
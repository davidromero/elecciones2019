![alt text](https://github.com/davidromero/elecciones2019/blob/master/boleta.png "Boleta Ejemplo")

## Description

Con toda la novela en desarrollo llamada Politica de Guatemala, decidi tomar iniciativa...
Repositorio por el momento utilizado como "Archive"

Names.txt contiene el nombre de las boletas en .jpg

Por persona son 5 Boletas

1. Presidente-VicePresidente
2. Diputados listados Nacional
3. Diputados Distritales
4. Corporacion Municipal AKA Alcaldes
5. Diputados al Parlacen

## Code

```
 wget https://resultados2019.blob.core.windows.net/201901/{num_boleta}
```

Las boletas estan numeradas desde la 000011.jpg, 000012.jpg, 000013.jpg, 000014.jpg, 000015.jpg, 000021.jpg, 000022.jpg ...

Las imagenes tienen una resolucion de 1700x2200px

Las imegenes tienen un tama;o aprox de 550 kB
## Notes

El Script en Bash se puede mejorar, disminuir el tiempo de descarga total 

## Files

100 Primeras boletas, el resto se encuentra en S3-AWS en la nube para futuro analisis

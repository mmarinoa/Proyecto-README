<h1 align="center"> Proyecto-README </h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7b121d2b-9cbb-4c01-934e-462edcb64c22" alt="Logo de la app Sky Map" width="300"/>
</p>


[![Version](https://img.shields.io/badge/version-1.4.5-blue?style=flat&logo=github&logoColor=purple)
![License](https://img.shields.io/badge/license-MIT-green) ](https://img.shields.io/badge/version-1.4.5-blue?style=social&logo=yellow&logoColor=black
)

## Índice

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Estado del Proyecto](#estado-del-proyecto)
- [Demostración de funciones y aplicaciones](#demostración-de-funciones-y-aplicaciones)
- [Acceso al Proyecto](#acceso-al-proyecto)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Personas Contribuyentes](#personas-contribuyentes)
- [Personas Desarrolladoras del Proyecto](#personas-desarrolladoras-del-proyecto)
- [Licencia](#licencia)

---

## Descripción del Proyecto
Sky Map es un planetario portátil para tu dispositivo Android. Úselo para identificar estrellas, planetas, nebulosas y más.

## Estado del Proyecto
> [!WARNING]
> El mapa está inestable.

Si tienes un teléfono que no tiene giroscopio, es de esperar que haya algunas vibraciones. Intente ajustar la velocidad y la amortiguación del sensor (en la configuración).
Estamos trabajando en mejoras.

## Demostración de funciones y aplicaciones
<p align="center">
  <img width="1013" height="761" alt="image" src="https://github.com/user-attachments/assets/6fe77895-755e-4558-96c0-042eb269fc98" />
</p>

<p align="center">
  <img width="302" height="474" alt="image" src="https://github.com/user-attachments/assets/f54eaba0-4fca-4d07-91e2-4b0e69d73aa2" />
</p>

<p align="center">
  <img width="1214" height="760" alt="image" src="https://github.com/user-attachments/assets/464ddf67-c3ae-4c00-a1e3-461c1d6fe285" />
</p>

## Acceso al Proyecto
Deberías ver los siguientes
dos directorios:
 * app: código fuente de la aplicación.
 * tools: código fuente para generar datos binarios utilizados por la aplicación.

Para compilar SkyMap, puedes utilizar Android Developer Studio o Gradle.  Comienza por
crear un archivo `local.properties` que contenga la ubicación de tu
instalación de Android:

    sdk.dir=<ruta a tu SDK>

Android Developer Studio puede crearlo por ti.  Puedes regenerar los archivos de datos y
recompilar todo con el script `build_skymap.sh`:

    ./build_skymap.sh
    
(o su equivalente en f-droid).

Si solo desea regenerar rápidamente un apk, consulte las siguientes instrucciones
(nota: assembleRelease no funcionará porque la versión f-droid necesita algunos ajustes que
se realizan mediante el script de shell, así que asegúrese de compilar específicamente la versión Gms).

Traducción realizada con la versión gratuita del traductor DeepL.com

## Tecnologías utilizadas
Enumera los lenguajes, frameworks, librerías o herramientas que usa el proyecto.  

## Personas Contribuyentes
Lista a las personas que han aportado ideas o material al proyecto.  

## Personas Desarrolladoras del Proyecto
Lista a quienes han escrito el código y desarrollado la aplicación.  

## Licencia
Indica bajo qué licencia se distribuye el proyecto (por ejemplo, MIT, GPL, Apache…).




 

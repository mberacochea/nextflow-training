# Orientación

El ambiente de Gitpod contiene todo el software, código y los datos necesarios para poder completar este curso, es por eso que no es necesario que instales nada. Sin embargo, es necesario que tengas una cuenta (gratuita) para poder loguearte, y disponer de unos minutos para familiarizarte con la interfaz.

Si aún no has completado lo anterior, por favor sigue [este link](../../envsetup/) antes de continuar.

## Materiales provistos

A lo largo de este curso, vamos a trabajar en el directorio `hello-nextflow/`, el cual se carga por defecto cuando abres el espacio de trabajo de Gitpod.
Este directorio contiene todos los archivos de código, datos de prueba y archivos accesorios que vas a necesitar.

Siéntete libre de explorar el contenido del directorio; la forma más sencilla es utilizando el explorador de archivos en la izquierda del espacio de trabajo de Gitpod. Alternativamente, puedes utilizar el comando `tree`.

A lo largo de este curso, vamos a utilizar la salida del comando `tree` para representar la estructura de los directorios y sus contenidos de forma legible, algunas veces con ligeras modificaciones para mayor claridad.

Aquí hemos generado una tabla de contenidos limitando hasta el segundo nivel:

```bash
tree . -L 2
```

Si ejecutas esto dentro de `hello-nextflow`, deberías obtener la siguiente salida:

```console title="Contenidos del directorio"
.
├── containers
│   ├── build
│   ├── data
│   ├── results
│   └── scripts
├── data
│   ├── bam
│   ├── greetings.csv
│   ├── ref
│   ├── sample_bams.txt
│   └── samplesheet.csv
├── hello-config
│   ├── demo-params.json
│   ├── main.nf
│   └── nextflow.config
├── hello-containers.nf
├── hello-genomics.nf
├── hello-modules
│   ├── demo-params.json
│   ├── main.nf
│   └── nextflow.config
├── hello-nf-core
│   ├── data
│   └── solution
├── hello-nf-test
│   ├── demo-params.json
│   ├── main.nf
│   ├── modules
│   └── nextflow.config
├── hello-operators.nf
├── hello-world.nf
├── nextflow.config
└── solutions
    ├── hello-config
    ├── hello-genomics
    ├── hello-modules
    ├── hello-nf-test
    ├── hello-operators
    └── hello-world

18 directories, 17 files
```

!!!note

    No te preocupes si esto te parece mucho; iremos paso a paso por las partes relevantes del curso.
    Esto es simplemente para darte un pantallazo general.

**Aquí está el resumen de lo que necesitas para empezar:**

- **Los archivos `.nf`** son scripts de workflows, cuyos nombres están basados en qué parte del curso están siendo utilizados.

- **Los directorios `hello-*`** son utilizados más adelante en el curso donde vamos a trabajar con más de un archivo de workflow.

- **El archivo `nextflow.config`** es de configuración que configura las propiedades mínimas del ambiente.
  Puedes ignorar esto por ahora.

- **El directorio `data`** contiene los datos de entrada que utilizaremos en la mayoría del curso. El conjunto de datos será descrito en detalle en la Parte 3, cuando lo introduzcamos por primera vez.

- **El directorio `solutions`** contiene los scripts de los workflows completos para cada paso del curso.
  Estos deberían ser utilizados como referencia para chequear tu trabajo y para resolver cualquier problema.
  El nombre y número del archivo se corresponde con el paso del curso para el cual es relevante.
  Por ejemplo, el archivo `hello-world-4.nf` es el resultado esperado de completar desde el paso 1 al paso 4 de Part 1: Hello World.

!!!tip

    Si por alguna razón te mueves de este directorio, siempre puedes volver si ejecutas el siguiente comando:
    ```bash
    cd /workspace/gitpod/hello-nextflow
    ```
Ahora, para empezar el curso, haz clic en la flecha en el rincón inferior derecho de esta página.
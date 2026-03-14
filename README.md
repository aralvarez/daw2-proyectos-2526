# DAW2 — Proyectos 2025-26
Instrucciones generales para los proyectos de DAW.

## Paso 1 - Crear repositorio en GitHub para el proyecto
Crea tu repositorio.
* Haz clic en el + de la esquina superior derecha → New repository
* Rellena los campos:
  * Repository name: daw2-proyecto
  * Description: Proyecto DAW2
  * Visibility: Private (o Public, como prefieras)
  * Marca "Add a README file"

## Paso 2 — Crear el archivo readme
Una estructura pordía ser:
    # Nombre del Proyecto
    
    ## Descripción
    Breve descripción del proyecto.
    
    ## Alumno
    Nombre y curso.
    
    ## Tecnologías previstas
    - Frontend: ...
    - Backend: ...
    - BBDD: ...
    
    ## Documentación
    - docu/anteproyecto.pdf
    - docu/memoria.docx
    - src/

## Paso 3 - Crear la estructura del proyecto
Crea dos carpetas desde el navegador: **`src`** para los archivos fuente y **`docu`** para la documentación.

1. En tu repositorio: **Add file → Create new file**
2. En el campo del nombre escribe: `src/.gitkeep` (o `docu/.gitkeep` para la otra carpeta)
   - El `/` crea automáticamente la carpeta
   - El archivo `.gitkeep` es un truco habitual para que la carpeta no esté vacía

## Paso 4 — Sube los documentos que ya tengas
1. Entra en la carpeta **`docu`**
2. **Add file → Upload files**
3. Arrastra el archivo o búscalo en tu PC

## Paso 5 — Haz el primer commit
Puedes darle el texto: Repositorio creado.

## Paso 6 - Comparte el repositorio conmigo
* Dentro del repositorio: Settings → Collaborators → Add people
* Buscar mi usuario de GitHub (aralvarez)
* Seleccionar rol Read
* Se enviará un email de invitación
----
Al terminar estos pasos tendrás algo así:
```
proyecto/
├── README.md
├── docu/
└── src/

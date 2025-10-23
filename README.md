# 🌀 COMMIT

    Un commit es una “captura” o “foto” del estado de tu código en un momento específico dentro de un repositorio de Git.
    Cuando haces un commit, estás guardando los cambios realizados (archivos nuevos, modificados o eliminados) junto con un mensaje que describe qué hiciste.

Un commit podría ser el siguiente:

    git commit -m "mensaje descriptivo"
    git commit -m "agrega función para calcular promedio"


# ⚡ CONVENTIONAL COMMIT

    Es una convención para escribir mensajes de commits (en Git) de forma estructurada y coherente. 
    Es decir, define un formato estándar para los mensajes de commit, de modo que sean fáciles de entender, automatizar y procesar por personas y herramientas.

## ⚡ Estructura básica de un Conventional Commit

    <tipo>(<alcance opcional>): <mensaje breve>

    feat(auth): agrega login con Google
    docs(readme): actualiza instrucciones de instalación
    test(utils): añade pruebas para formato de fechas




## ⚡ Tipos comunes de commits

|   Tipo    |   Significado   |
|-----------|:----------------|
|feat       |Nueva funcionalidad (feature)|
|fix        |Corrección de un bug|
|docs	    |Cambios en documentación
|style	    |Cambios de formato (espacios, comas, etc.), sin afectar el código
|refactor	|Refactorización sin cambiar comportamiento
|perf	    |Mejoras de rendimiento
|test	    |Agregar o modificar pruebas
|chore	    |Tareas de mantenimiento (dependencias, build, etc.)

## Ejemplos para realizar un commit con comandos git

    git commit -m "feat(api): agrega endpoint para usuarios"
    git commit -m "fix(auth): corrige bug de expiración de token"

## ⚡ ¿Por qué es importante usar Conventional Commits?

__💡 Claridad y consistencia:__

Todos los commits siguen la misma estructura, facilitando la lectura del historial de cambios.

__🤖 Automatización:__

Permite automatizar tareas como:

* Generación de changelogs.

* Versionado semántico (SemVer) automático (1.2.3 → 1.3.0, etc.).

* Integración con herramientas de CI/CD (como Semantic Release).


__🔍 Facilidad de búsqueda:__

Puedes filtrar fácilmente commits por tipo (feat, fix, etc.) o módulo (auth, api, etc.).

__👬 Trabajo en equipo más claro:__

Cualquiera en el equipo entiende rápidamente qué tipo de cambio hizo alguien más sin leer el código completo.


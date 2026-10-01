# Control de Buses — Android

Canal oficial de distribución de **Control de Buses para Android**.

Este repositorio se utiliza exclusivamente para publicar versiones instalables de la aplicación Android. El código fuente y los componentes de escritorio/servidor no se distribuyen desde este repositorio.

## Descargar

La versión más reciente estará disponible en **Releases**:

**[Descargar la última versión](https://github.com/JEstrada2007/control-buses/releases/latest)**

Si todavía no existe una release publicada, el enlace mostrará la página de releases hasta que se publique la primera versión.

## Instalación

1. Abre la sección **Releases**.
2. Entra en la versión que quieras instalar.
3. Descarga el archivo `.apk` adjunto.
4. Abre el APK en tu dispositivo Android.
5. Si Android lo solicita, autoriza la instalación desde esa fuente.
6. Completa la instalación.

> Para actualizar la aplicación, instala el APK de la nueva versión sobre la instalación existente. No desinstales la aplicación salvo que sea necesario, ya que hacerlo puede eliminar datos almacenados localmente.

## Versiones

Las publicaciones siguen versionado semántico:

```text
MAJOR.MINOR.PATCH
```

Ejemplos:

- `1.0.0` — primera versión estable.
- `1.1.0` — nuevas funciones compatibles.
- `1.1.1` — correcciones y ajustes menores.
- `2.0.0` — cambios importantes o incompatibles.

Cada release debe incluir:

- número de versión;
- fecha de publicación;
- APK;
- resumen de cambios;
- correcciones relevantes;
- notas de instalación o actualización cuando sean necesarias.

## Canales

### Stable

Versiones destinadas al uso normal. Son las publicaciones recomendadas para los usuarios.

### Pre-release

Versiones de prueba que pueden utilizarse para validar funciones nuevas antes de promoverlas a Stable. GitHub las mostrará marcadas como **Pre-release**.

## Nombre de los APK

Formato recomendado:

```text
ControlBuses-v1.0.0.apk
```

Para versiones de prueba:

```text
ControlBuses-v1.1.0-beta.1.apk
```

## Plantilla de release

```markdown
# Control de Buses vX.Y.Z

## Novedades
- ...

## Correcciones
- ...

## Notas
- ...

### Instalación
Descarga `ControlBuses-vX.Y.Z.apk` desde Assets e instálalo sobre la versión anterior.
```

## Seguridad

Descarga los APK únicamente desde la sección **Releases** de este repositorio para evitar copias modificadas o versiones no oficiales.

## Proyecto

**Control de Buses** es una aplicación Android asociada al sistema de gestión y control de buses. Este repositorio funciona únicamente como su canal oficial de releases para Android.

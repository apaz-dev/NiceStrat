[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

## Descripción

Aquí se encuentran el código fuente (Java), los recursos (layouts, drawables, valores), de la aplicacion `NiceStrat`.

<img src="img/registrar.png" alt="Registrar" width="200px"/> <img src="img/login.png" alt="Registrar" width="200px"/> <img src="img/main.png" alt="Registrar" width="200px"/> <img src="img/Captura de pantalla 2025-11-11 a las 13.46.16.png" alt="Registrar" width="200px"/>


## Requisitos

- JDK (11+ recomendado, según configuración del proyecto).
- Android Studio (obligatorio).

## Características principales

- **Menús contextuales**: Acceso rápido a opciones mediante menús contextuales y de barra de aplicación
- **SwipeRefresh**: Funcionalidad de recarga mediante gesto de deslizamiento
- **Snackbar**: Notificaciones no intrusivas con acciones
- **Navegación entre actividades**: Flujo entre pantallas de login, registro y vista principal
- **Bottom App Bar**: Barra de navegación inferior con botón flotante (FAB) centrado
- **Bottom Sheet Dialog**: Diálogo deslizable desde abajo con opciones de configuración, información y cierre de sesión
- **Soporte multi-idioma**: Español (values-es) e inglés por defecto
- **Modo oscuro**: Soporte completo de tema claro/oscuro con colores adaptados (values-night)

## Dependencias principales

- SwipeRefreshLayout
- Glide

## Estructura principal

- `src/main/java/Login.java` - código fuente del backend de la ventana asociada al inicio de sesión
- `src/main/java/MainActivity.java` - código fuente del backend de la vista principal con WebView, menús y diálogos
- `src/main/java/MainBab.java` - código fuente del backend de la actividad con Bottom App Bar y Bottom Sheet Dialog
- `src/main/java/SingUp.java` - código fuente del backend de la ventana asociada al registro de una cuenta nueva
- `src/main/res/layout/activity_login.xml` - código del frontend de la ventana asociada al inicio de sesión
- `src/main/res/layout/activity_main.xml` - código del frontend de la vista principal con WebView y SwipeRefreshLayout
- `src/main/res/layout/activity_main_bab.xml` - código del frontend con Bottom App Bar y FAB
- `src/main/res/layout/bottom_sheet_layout.xml` - código del frontend del Bottom Sheet Dialog con opciones de menú
- `src/main/res/layout/activity_sing_up.xml` - código del frontend de la ventana asociada al registro de una cuenta nueva
- `src/main/res/menu/menu_context.xml` - menú contextual con opciones de copiar y descargar
- `src/main/res/menu/menu_appbar.xml` - menú de barra de aplicación con configuraciones
- `src/main/res/menu/menu_bottom_appbar.xml` - menú de la barra de navegación inferior
- `src/main/res/values-es/strings.xml` - recursos de texto en español
- `src/main/res/values-night/colors.xml` - paleta de colores para modo oscuro
- `src/main/res/drawable/ico_plus.xml` - ícono vectorial para el Bottom Sheet
- `src/main/AndroidManifest.xml` - manifest del módulo

## BRANCHES

[PULL REQUEST BRANCHS](https://github.com/apaz-dev/NiceStrat/tree/Pull)

[DEV BRANCH](https://github.com/apaz-dev/NiceStrat/tree/Stack)


## Cómo contribuir

1. Crea un branch con un nombre descriptivo (por ejemplo `feature/nombre` o `fix/descripcion`)
2. Abre un Pull Request hacia la rama destino (ej. `develop` o `main`) con una descripción clara de los cambios
3. Incluye screenshots o pasos para reproducir si el cambio afecta la UI
4. Asegúrate de que los nuevos menús y diálogos sigan las pautas de Material Design

## Licencia

Respeta los términos antes de redistribuir o reutilizar código.

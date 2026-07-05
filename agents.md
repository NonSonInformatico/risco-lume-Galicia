# Risco Lume Galicia

## Idioma

Todo el código, documentación y comentarios estarán en inglés.

Toda la interfaz de usuario estará en gallego.

## Arquitectura

- Backend: Python 3.13
- Android: Kotlin + Jetpack Compose
- Material Design 3
- Arquitectura MVVM
- Clean Architecture
- Offline First

## Reglas

- No inventar APIs.
- No hardcodear datos.
- Todo el código debe incluir tests.
- Todo debe compilar.
- Un único cambio por commit.
- No implementar funcionalidades no solicitadas.

## Objetivo

Crear una aplicación Android que:

- muestre el IRDI del concello donde se encuentra el usuario;
- muestre incendios activos obtenidos desde NASA FIRMS;
- funcione sin servidor propio;
- actualice automáticamente los datos mediante GitHub Actions.
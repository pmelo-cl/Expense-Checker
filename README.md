# Expense Checker

Aplicación Android para la gestión y seguimiento de gastos personales, desarrollada en Android Studio con Java y una base de datos relacional local.

---

## Descripción

Expense Checker es una aplicación móvil completamente funcional que permite a los usuarios registrar, visualizar y gestionar sus gastos personales. Utiliza una base de datos relacional local (SQLite) para almacenar y consultar la información de forma eficiente y persistente.

---

## Funcionalidades

- Registro de gastos con categoría, descripción e importe
- Visualización del historial de gastos
- Gestión completa mediante base de datos relacional (CRUD)
- Interfaz intuitiva diseñada con Material Design
- Persistencia de datos local sin necesidad de conexión a internet

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| Java | Lenguaje principal |
| Android Studio | Entorno de desarrollo |
| SQLite | Base de datos local |
| Gradle | Sistema de build |

---

## Instalación

### Requisitos previos

- Android Studio Hedgehog o superior
- JDK 11 o superior
- Android SDK (API 24 mínimo recomendado)

### Pasos

1. Clona el repositorio:
```bash
git clone https://github.com/pmelo-cl/Expense-Checker.git
```

2. Abre el proyecto en Android Studio:
   - `File → Open` y selecciona la carpeta del proyecto

3. Sincroniza las dependencias de Gradle:
   - Android Studio lo hará automáticamente, o ve a `File → Sync Project with Gradle Files`

4. Ejecuta la aplicación:
   - Conecta un dispositivo Android o inicia un emulador
   - Pulsa el botón **Run** (▶) o usa `Shift + F10`

---

## Estructura del proyecto

```
Expense-Checker/
├── app/
│   └── src/
│       └── main/
│           ├── java/          # Código fuente Java
│           └── res/           # Recursos (layouts, strings, drawables)
├── gradle/                    # Configuración de Gradle
├── build.gradle.kts           # Dependencias del proyecto
└── settings.gradle.kts        # Configuración del módulo
```

---

## Autor

**pmelo-cl** — [GitHub](https://github.com/pmelo-cl)

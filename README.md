# Prácticas Temas 9 y 10: Entornos de Desarrollo
## Alumno: Iván del Cid Plaza - 1º DAW

Este repositorio contiene las soluciones a las prácticas de los temas 9 y 10 del módulo de Entornos de Desarrollo.

A lo largo de estos ejercicios, he aplicado técnicas profesionales para mejorar la calidad del código, asegurar su funcionamiento mediante pruebas automáticas y generar documentación técnica siguiendo los estándares de Java.

---

## 🛠️ Ejercicios Realizados y Metodología

### Tarea 1 y 2: Refactorización (Clean Code)
En estos ejercicios me he enfocado en eliminar los denominados "Code Smells" (malos olores del código).
- He simplificado el método `main` extrayendo la lógica a métodos privados especializados, facilitando la reutilización del código.
- He aplicado una refactorización de nombres para que las variables sean autodocumentadas (ej. de `n1` a `dividendo`).
- He limpiado el proyecto de variables e imports innecesarios que ensuciaban el desarrollo.

### Tarea 3: Optimización con JUnit 5
Para garantizar que el software es robusto y libre de errores, he implementado Pruebas Unitarias:
- He configurado la librería **JUnit 5** en el Build Path de Eclipse.
- He creado una clase de test (`CalculadoraTest`) donde compruebo casos de éxito y casos de error (como la división por cero).
- El resultado ha sido satisfactorio, obteniendo la Barra Verde en todos los casos de prueba.

### Tarea 4: Documentación con Javadoc
He generado la documentación técnica del proyecto para que cualquier desarrollador pueda entender el API sin leer el código fuente:
- He generado el informe en formato HTML mediante la herramienta de Eclipse , el cual se encuentra disponible en la carpeta `/doc`.

### Tarea 5: Análisis de Calidad Final
En la última fase, he realizado una revisión crítica del código:
-  He añadido validaciones para evitar errores críticos en tiempo de ejecución.
-  He eliminado los "números mágicos" sustituyéndolos por constantes `static final`, centralizando así la configuración de valores por defecto.

---

## 📂 Estructura del Proyecto
```text
├── src
│   ├── ejercicio1    # Refactorización inicial
│   ├── ejercicio2    # Limpieza de nombres
│   └── ejercicio3    # Código final con JUnit y Javadoc
├── doc               # Documentación HTML generada
└── lib               # Librerías (JUnit 5)

# API E2E Tests con Postman y GitHub Actions

Este repositorio contiene:

- Colección de pruebas Postman (`postman-tests/collection.json`)
- Environment con variables (`postman-tests/environment.json`)
- Archivo CSV con datos de prueba para iteraciones (`postman-tests/data.csv`)
- Workflow de GitHub Actions para ejecutar las pruebas con Newman y generar reportes automáticos (`.github/workflows/postman-tests.yml`)

---

## Estructura del repositorio

├── postman-tests/
│ ├── collection.json
│ ├── environment.json
│ ├── data.csv
│ └── README.md
├── .github/
│ └── workflows/
│ └── postman-tests.yml
└── README.md
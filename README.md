
# Dashboard KPIs – Banco Ejemplo

Este proyecto es un simulador profesional de indicadores clave de desempeño (KPIs) para el Banco Ejemplo.

## 📊 Características

- Filtros dinámicos por Período, Perspectiva, Sucursal y Oficial
- Filtros en cascada (al elegir una sucursal, se filtran oficiales)
- Visualización separada de indicadores para Casa Matriz
- Exportación de resultados a CSV
- Semaforización clara de KPIs: 🟢 >85, 🟡 70-84, 🔴 <70
- Datos simulados para el período junio 2024 a junio 2025

## 🚀 Deploy en Vercel

1. Subí esta carpeta a un repositorio de GitHub
2. Desde Vercel, importá el proyecto
   - Framework: `Other`
   - Output directory: `public`
3. ¡Listo!

## 📁 Estructura del Proyecto

```
dashboard-kpis-banco-ejemplo/
├── public/
│   ├── index.html
│   ├── app.js
│   └── simulacion_kpis_banco_ejemplo.csv
├── vercel.json
├── .vercelignore
└── README.md
```

---

Desarrollado como simulador para presentaciones de alto nivel en el sector bancario.

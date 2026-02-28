
# Budget Tracker Application

## Descripción

Budget Tracker es una aplicación web moderna para gestionar presupuestos y gastos. Permite crear un presupuesto inicial, registrar gastos por categoría, filtrar transacciones y visualizar el estado financiero en tiempo real.

## Indicaciones de Uso

1. **Crear Presupuesto**: Ingresa el monto inicial en la sección de formulario
2. **Registrar Gastos**: Completa el formulario con descripción, monto y categoría
3. **Ver Detalles**: Consulta la lista de gastos registrados
4. **Filtrar**: Utiliza el filtro por categoría para ver gastos específicos
5. **Monitorear**: Visualiza el saldo disponible en el display principal

## Estructura de Carpetas

```
src/
├── components/          # Componentes React reutilizables
│   ├── AmountDisplay.jsx
│   ├── BudgetForm.jsx
│   ├── BudgetTracker.jsx
│   ├── ErrorMessage.jsx
│   ├── ExpenseDetails.jsx
│   ├── ExpenseForm.jsx
│   ├── ExpenseList.jsx
│   ├── ExpenseModal.jsx
│   └── FilterByCategory.jsx
├── context/             # Context API para estado global
│   └── BudgetContext.jsx
├── data/                # Datos estáticos
│   └── categories.js
├── reducers/            # Lógica de reducers
│   └── budget-reducer.js
├── App.jsx
├── main.jsx
└── index.css
```

## Recomendaciones Adicionales

- Valida todos los inputs antes de registrar gastos
- Implementa confirmación antes de eliminar gastos
- Usa localStorage para persistencia de datos
- Agrega alertas visuales cuando el saldo sea bajo
- Considera agregar reportes o gráficos de gastos por categoría


## Instalación y Ejecución Local

### Requisitos previos
- Node.js (v14 o superior)
- npm o yarn

### Pasos de instalación

1. Clona el repositorio:
```bash
git clone <repository-url>
cd practica4
```

2. Instala las dependencias:
```bash
npm install
```

3. Ejecuta el servidor de desarrollo:
```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:5173`

## Sitio Desplegado

Accede a la aplicación en línea: [Budget Tracker Live](<deployment-url>)

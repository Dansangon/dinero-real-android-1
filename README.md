# Dinero Real — Android V0.2

Aplicación Android offline para gestión económica personal, capacidad de ahorro y simulaciones de compra de vivienda.

## V0.2
- Inicio con resumen de ingresos, gastos, capacidad de ahorro y escenario de vivienda.
- Nuevo módulo **Gastos**:
  - gastos fijos por nombre e importe;
  - categorías (vivienda, suministros, comunicaciones, transporte, suscripciones y ocio, salud y deporte, seguros, familia, deudas y otros);
  - clasificación esencial / prescindible;
  - periodicidad mensual, trimestral, semestral o anual;
  - prorrateo automático a equivalente mensual;
  - presupuesto variable mensual;
  - cálculo de capacidad y tasa de ahorro.
- La calculadora de vivienda puede usar automáticamente la capacidad de ahorro calculada.
- Los objetivos también pueden usar automáticamente esa capacidad de ahorro.
- Calculadora de vivienda: precio, financiación, entrada, impuestos, gastos, tipo y plazo.
- Objetivo de ahorro: cantidad objetivo, ahorro actual, aportación mensual y fecha estimada.
- Escenarios de vivienda guardados localmente.
- Sin registro, sin servidor y sin permiso de Internet.

## Privacidad
La aplicación no solicita permisos sensibles ni permiso de Internet. Los datos se guardan en `localStorage` dentro del WebView del dispositivo.

## Compilar
Requiere JDK 17, Android SDK 35 y Gradle 8.9, o puede compilarse con el workflow incluido de GitHub Actions.

```bash
gradle :app:assembleDebug
```

APK resultante:
`app/build/outputs/apk/debug/app-debug.apk`

## Estado
Prototipo V0.2 para validación funcional. No destinado todavía a publicación en Google Play.

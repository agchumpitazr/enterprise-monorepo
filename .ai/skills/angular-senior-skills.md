# Angular Senior & Architecture Skills

## 1. Clean Architecture & DDD (Domain-Driven Design)
- Aislamiento estricto en `libs/`. Cada dominio debe encapsular sus propias features, modelos y servicios.
- Prohibida la comunicación circular entre librerías de dominio.

## 2. Signals & RxJS Strategy
- Migración progresiva a Angular Signals (`signal`, `computed`, `effect`) para el estado local y reactividad de componentes.
- Uso avanzado de RxJS (`switchMap`, `shareReplay`, manejo robusto de errores) exclusivamente para flujos asíncronos complejos y peticiones HTTP.

## 3. Testing Standards
- Cobertura obligatoria con pruebas unitarias (Jest/Vitest).
- Automatización de flujos de usuario críticos mediante E2E con Playwright.

## 4. Code Quality
- Tipado estricto en TypeScript (cero uso de `any`, uso de Generics avanzados).
- Enfoque orientado a rendimiento (Change Detection `OnPush`, lazy loading).

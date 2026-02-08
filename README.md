# Calculator App · Expo React Native

Calculadora móvil desarrollada con **Expo y React Native**, enfocada en una arquitectura limpia, lógica desacoplada mediante custom hooks y una interfaz minimalista inspirada en iOS.

## ✨ Características

- ➕➖✖️➗ Operaciones aritméticas básicas
- 🧠 Lógica central desacoplada con `useCalculator`
- 📱 UI responsiva tipo iOS
- 🎯 Validaciones de entrada numérica
- 📳 Feedback háptico en botones
- 🔤 Tipografía personalizada (Space Mono)
- 🎨 Componentes reutilizables
- 🌙 Estilo oscuro (dark mode)

## 🧱 Arquitectura

- UI desacoplada de la lógica
- Custom Hook para manejo del estado y operaciones
- Componentes reutilizables (`CalculatorButton`, `ThemeText`)
- Estilos globales centralizados
- Expo Router como entry point

### Estructura del proyecto

app/
├── _layout.tsx
│ └── index.tsx
assets/
├── fonts/
│ └── images/
components/
├── CalculatorButton.tsx
│ └── ThemeText.tsx
constants/
│ └── theme.ts
hooks/
│ └── useCalculator.tsx
styles/
│ └── global-styles.ts


## 🛠️ Stack Tecnológico

- React Native
- Expo
- Expo Router
- TypeScript
- Bun (gestor de paquetes)
- Expo Haptics
- Expo Font

## 🚀 Instalación y ejecución

> Este proyecto utiliza **Bun** como gestor de dependencias.

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/calculator-app.git
cd calculator-app
```

### 2️⃣ Instalar dependencias

```bash
bun install
```

### 3️⃣ Ejecutar el proyecto
```bash
bun run start
```

### O directamente por plataforma:
```bash
bun run android
bun run ios
bun run web
```

Desarrollado con ❤️ usando Expo y React Native
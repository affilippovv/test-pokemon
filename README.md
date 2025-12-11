# 🐾 Test Pokémon App

Simple React Native application built with **Expo**, featuring:

- Pokémon list & detail screens  
- Power level calculation  
- Step tracking module  
- Local storage  
- Custom hooks & navigation  
- Unit-tested logic  

---

## 🚀 Features

### 📌 Pokémon List & Details  
- Fetches Pokémon data from API  
- Shows details such as stats, types, and images  
- Smooth navigation between screens  

### 💥 Power Level Calculation  
- Logic implemented in `powerCalculation.ts`  
- Displayed in `PowerLevelDisplay`  
- Covered with unit tests  

### 🚶 Step Tracking  
- Custom native-like module: `StepTrackerModule.ts`  
- Real-time movement tracking with `useStepTracking`  

### 💾 Local Storage  
Lightweight wrapper around AsyncStorage inside:

```
src/services/storage.ts
```

---

## 📁 Folder Structure

```
src/
  components/
  hooks/
  modules/
  navigation/
  screens/
  services/
  types/
  utils/
```

---

## ▶️ How to Run the Project

### 1. Install dependencies
```
npm install
```

### 2. Start Metro bundler (Expo)
```
npm start
```

### 3. Run on a device or simulator
Inside Expo CLI:

- Press **i** → launch iOS Simulator  
- Press **a** → launch Android Emulator  
- Scan QR code with Expo Go on your phone  

> iOS Simulator works only on macOS with Xcode installed.

---

## 🧪 Running Tests

```
npm test
```

Tests are stored in:

```
src/utils/__tests__/
```

---

## 🔧 Tech Stack

- Expo (React Native)
- TypeScript
- React Navigation
- AsyncStorage
- Jest (Testing)

---

## 👤 Author

Created by **affilippovv**

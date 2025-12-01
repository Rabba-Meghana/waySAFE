# waySAFE 🛡️  
Your intelligent safety companion for safer routes and smarter decisions.
<img width="452" height="452" alt="image" src="https://github.com/user-attachments/assets/deab018e-3b8e-4bca-a198-1ea910b0155f" />


---

## 🚀 Overview  
waySAFE analyzes environments, detects risks, and guides users toward safer routes using AI agents and a modern dashboard interface.  
Its goal is simple: **protect every step you take.**


---

## 🌍 1. Introduction  
waySAFE uses multi agent intelligence and environmental signals to compute safety scores and show safer path recommendations.

---

## ⚡ 2. Core Features  

### 🔐 2.1 Safety Intelligence  
- AI safety score  
- Poor lighting detection  
- Low crowd density alerts  
- Time based risk adjustments  
- Historical incident signal analysis  

### 🧭 2.2 Route Guidance  
- Safer route alternatives  
- Explanation and reasoning agent  
- Hazard overlay on map  

### 🖥️ 2.3 Dashboard  
- Chart visualizations  
- Memory timeline  
- Metrics and logs  
- Clean and responsive UI  

---

## 🏗️ 3. System Architecture

### 3.1 ASCII Architecture Diagram  
```

```
            ┌───────────────────────────┐
            │       Frontend UI         │
            │  (waysafe-dashboard)      │
            └───────────┬───────────────┘
                        │
                        ▼
            ┌───────────────────────────┐
            │     API Interaction       │
            │  (frontend to backend)    │
            └───────────┬───────────────┘
                        │
                        ▼
            ┌───────────────────────────┐
            │  Multi Agent System       │
            │  • Safety Agent           │
            │  • Risk Detection Agent   │
            │  • Recommendation Agent   │
            └───────────┬───────────────┘
                        │
                        ▼
            ┌───────────────────────────┐
            │  Safety Computation Core  │
            │ (implementation.ipynb)    │
            └───────────────────────────┘
```

```

### 3.2 Architecture Description  
- **Frontend**: Vite React, Tailwind, shadcn  
- **Backend Logic**: Jupyter notebook with safety scoring algorithms  
- **Agents**: three collaborating reasoning units  
- **Visuals**: charts, maps, logs  

---

## 📂 4. Folder Structure  

```

waySAFE/
│
├── implementation.ipynb
├── technology.pdf
└── waysafe-dashboard/
├── src/
│   ├── components/
│   ├── pages/
│   ├── api/
│   ├── hooks/
│   ├── lib/
│   └── main.tsx
├── public/
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts

````

---

## ⚙️ 5. Installation & Setup  

### Frontend  
```bash
cd waysafe-dashboard
npm install
npm run dev
````

### Backend

Open `implementation.ipynb` in Jupyter Notebook, VSCode, or Google Colab and run all cells.

---

## 🔍 6. How It Works

1. User enters a start location
2. Safety agent calculates base safety score
3. Risk agent evaluates lighting, crowd level, isolation
4. Recommendation agent chooses safer alternate routes
5. Dashboard displays:

   * metrics
   * charts
   * logs
   * reasoning timeline

---

## 🔄 7. Workflow Diagram

```
User Input
     │
     ▼
Safety Score Engine
     │
     ▼
Risk Detection Agent
     │
     ▼
Recommendation Agent
     │
     ▼
Dashboard Visualization
```

---

## 📊 8. Sample Dashboard Metrics Table

| Metric            | Description                        |
| ----------------- | ---------------------------------- |
| Safety Score      | Overall safety rating              |
| Light Level Index | Measures lighting quality          |
| Isolation Factor  | Detects low population areas       |
| Crowd Density     | Evaluates how populated an area is |
| Hazard Count      | Number of detected risks           |

---

## 🌱 9. Future Enhancements

* Real time GPS
* Open data integration
* Push notifications
* Mobile app with React Native
* Advanced anomaly detection

---

## 💫 10. Purpose & Vision

waySAFE aims to help people feel safer wherever they go by combining intelligence, empathy, and environment awareness.

**Mission:**
🛡️ *Protect every step.*

---

## 🤝 11. Credits

Designed and built with care and clarity.
waySAFE is your safety companion powered by intelligent route reasoning.

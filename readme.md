### 📂 Project Structure

```text
SentryCore/
├── lib/
│   ├── LiteDB.dll              <-- v5.0.21 (netstandard2.0)
│   └── LiteDB.xml              <-- IntelliSense Documentation
├── bin/
│   └── Custom/
│       ├── Common/
│       │   └── TradeResult.cs      <-- Data Model (MAE/MFE/Pnl)
│       ├── AddOns/
│       │   └── Services/
│       │       ├── DatabaseService.cs   <-- Persistence Engine
│       │       └── PerformanceBreaker.cs <-- Risk Logic (Semaphore)
│       └── Strategies/
│           └── SentryAlpha_Template.cs  <-- Example Implementation
├── .gitignore                  <-- Temp/Build file filter
└── README.md                   <-- Main documentation

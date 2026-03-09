SentryCore/
├── README.md                 <-- Documentación principal
├── .gitignore                <-- Filtro de archivos basura/temporales
├── lib/
│   ├── LiteDB.dll            <-- v5.0.21 (netstandard2.0)
│   └── LiteDB.xml            <-- Documentación IntelliSense
└── bin/
    └── Custom/
        ├── Common/
        │   └── TradeResult.cs      <-- Modelo de datos (MAE/MFE)
        ├── AddOns/
        │   └── Services/
        │       ├── DatabaseService.cs   <-- Motor de persistencia
        │       └── PerformanceBreaker.cs <-- Lógica de riesgo (Semáforo)
        └── Strategies/
            └── SentryAlpha_Template.cs  <-- Implementación de ejemplo

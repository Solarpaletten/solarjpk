**Roadmap Solar VAT Bridge:**
```
v0.2  ✅ NrKontrahenta, NrDostawcy, GTU
v0.3  ✅ P_39, P_48, P_53, P_62
v0.4  → 📂 Import poprzedniego JPK → auto P_39 ← P_62
v0.5  → ✅ Validator XML: ewidencja vs deklaracja
v1.0  → 📊 Annual JPK Audit
         załaduj 12 plików
         tabela: miesiąc | P_39 | P_48 | P_51 | P_53 | P_62 | status
         wykryj: przerwanie ciągłości P_62→P_39
         wykryj: niezgodność SprzedazCtrl vs P_38
         wykryj: niezgodność ZakupCtrl vs P_48
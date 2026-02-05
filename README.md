# 🤖 Autonomous AI Agent Framework

Bu proje, karmaşık iş görevlerini otonom bir şekilde planlayıp icra edebilen modüler bir yapay zeka asistanı çekirdeğidir. Model Context Protocol (MCP) standartlarını kullanarak dış araçlarla konuşabilir.

## ✨ Özellikler
- **Otonom Karar Mekanizması:** Hedef odaklı planlama ve dinamik strateji geliştirme.
- **MCP Entegrasyonu:** Google Search, Database, ve Local Filesystem ile doğrudan etkileşim.
- **Sandbox Execution:** Güvenli bir ortamda kod oluşturma ve test etme yeteneği.
- **Context Management:** Uzun vadeli bellek ve proje bazlı bağlam takibi.

## 🚀 Hızlı Başlangıç

```python
from antigravity.core import Agent

# Ajanı başlat
agent = Agent(name="Antigravity", model="gemini-2.0-flash")

# Görev tanımla
task = "YouTube'daki en popüler AI trendlerini analiz et ve bir rapor hazırla."

# Ajanı çalıştır
agent.run(task)
```

---

## 🛠️ Mimari
Ajan, "Beyin", "Duyular" ve "Araçlar" olmak üzere üç ana katmandan oluşur. Her katman bağımsız olarak ölçeklendirilebilir.

---
*Bu repo, Nihat'ın Upwork portfolyosu için örnek bir teknik çalışma olarak hazırlanmıştır.*

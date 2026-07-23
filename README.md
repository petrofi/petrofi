# Tarık Sağlıcak

Backend sistemleri ve uygulamalı makine öğrenmesi projeleri geliştiriyorum. C#/.NET ve Python ile servisler; PyTorch, OpenCV ve yerel modellerle çalışan prototipler üretiyorum. Projelerimde tekrarlanabilir testlere, ölçülebilir sonuçlara ve sınırları açıkça belgelenmiş sistemlere önem veriyorum.

İstanbul, Türkiye · [darklove.io](https://darklove.io)

## Seçilmiş çalışmalar

| Proje | Kapsam | Doğrulanmış sonuç |
| --- | --- | --- |
| [DarkDrive AI Simulation](https://github.com/petrofi/darkdrive-ai-simulation) | Unity simülatöründe davranış klonlama, veri seti dengeleme ve kapalı çevrim direksiyon kontrolü | **141 test**; 20,328 saniyelik aktif koşuda **1.724 başarılı tahmin**, **0 operasyonel çıkarım hatası** ve **7,958 ms** ortalama CPU gecikmesi |
| [Darklove Local AI Module](https://github.com/petrofi/darklove-local-ai-module) | ASP.NET Core üzerinde yerel ve gizlilik odaklı Türkçe duygu analizi; LM Studio/Ollama entegrasyonu ve kural tabanlı fallback | Birim ve HTTP entegrasyon senaryolarını kapsayan **46 otomatik test**; CI ile doğrulanan build ve test akışı |
| [DarkMind-30M](https://github.com/petrofi/darkmind-30m) | PyTorch ile sıfırdan decoder-only Transformer, özel tokenizer, eğitim ve çıkarım hattı | DarkMind v2 için **50 milyon karakterlik** tokenizer corpus'u; **4 adayın** karşılaştırılması ve **24k BPE** tokenizer seçimi |
| [MeritTrace](https://github.com/petrofi/merittrace) | FastAPI, React ve SQLite ile yerel çalışan; açıklanabilir puanlama, RBAC ve denetim kaydı sunan aday inceleme MVP'si | **37 backend**, **17 frontend** ve **5 E2E** testi; doğrulanmış lint ve production build |

## Diğer projeler

- [Autonomous UAV Simulation](https://github.com/petrofi/Autonomous-UAV-Simulation) — PX4 SITL ve Gazebo üzerinde kontrollü kalkış, sabit hover, iniş ve otomatik disarm doğrulaması; yatay uçuş henüz kapsam dışında.
- [XTTS Voice Cloning Demo](https://github.com/petrofi/xtts-voice-cloning-demo-tr-en) — Türkçe/İngilizce ses koşullandırma ve TTS için FastAPI tabanlı yerel demo.
- [BloomForMom](https://github.com/petrofi/bloom-for-mom) — React ve TypeScript ile, backend ve harici medya bağımlılığı olmadan çalışan paylaşılabilir web deneyimi.

## Teknik kapsam

- **Backend:** C#, .NET, ASP.NET Core, Python, FastAPI
- **Makine öğrenmesi:** PyTorch, OpenCV, yerel LLM çalışma ortamları
- **Web:** TypeScript, JavaScript, React, Next.js
- **Altyapı:** Docker, GitHub Actions, PostgreSQL, SQLite

> Sonuçlar ilgili depolardaki test kayıtları ve doğrulama raporlarına dayanır. Deneysel veya henüz doğrulanmamış özellikler ayrıca belirtilmiştir.

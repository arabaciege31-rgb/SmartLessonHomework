
# 🎓 EduVideoAI

EduVideoAI, **“video ile anlat”** komutunu gerçekten eğitim odaklı kullanan,
YouTube videolarını **akıllı şekilde seçen** bir **Python tabanlı eğitim AI prototipidir**.

> ⚠️ Not:  
> Bu proje bir **web sitesi değildir**.  
> GitHub üzerinden tıklanarak çalışmaz.  
> **Bilgisayarında çalıştırılan (terminal tabanlı) bir AI prototipidir.**

---

## 🚀 Ne yapar?

- 📺 YouTube’dan **konuya ve seviyeye uygun** eğitim videosu bulur  
- ⏱️ Kısa ve net (≤10 dk) videoları tercih eder  
- 🧠 Video izlenirken **öğrenme odağı verir**
- ❓ Video sonrası **düşündürten soru** sorar

---

## ❌ Ne yapmaz? (şimdilik)

- Web arayüzü yok  
- Buton / tıklanabilir sayfa yok  
- Videoyu otomatik durdurmaz  
- Gerçek AI modeli içermez (mantık prototipidir)

---

## 🧩 Proje Yapısı

```text
EduVideoAI/
│
├── main.py              # Ana giriş noktası
├── video_finder.py      # YouTube video bulma
├── learner_profile.py   # Kullanıcı profili
├── explainer.py         # Video + açıklama
├── requirements.txt
└── README.md

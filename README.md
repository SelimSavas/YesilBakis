# 🌱 Yeşil Bakış  
**Akıllı Tarım ve Bitki Bakım Asistanı (LLM + RAG Destekli)**  

Yeşil Bakış, tarım ve bitki bakımı konularında **çiftçilere**, **bahçıvanlara** ve **hobi yetiştiricilerine** akıllı öneriler sunan bir bilgi sistemi.  
Sistem; PDF, Word, web makaleleri veya görsellerden (OCR ile) elde edilen tarımsal içerikleri işler, anlamlı şekilde indeksler ve kullanıcının **doğal dilde sorduğu sorulara doğru, kaynak gösteren cevaplar** üretir.

---

## 🚜 Sorun ve Çözüm

### Sorun  
Günümüzde çiftçiler ve yetiştiriciler, **doğru bakım bilgisine** ulaşmakta zorlanıyor.  
- İnternetteki bilgi **dağınıklığı**  
- Teknik dokümanların **karmaşıklığı**  
- Zaman kaybı ve **güvenilir bilgiye ulaşamama**  

### Çözüm  
Yeşil Bakış:  
- **Güvenilir tarım rehberleri**, akademik makaleler ve resmi kaynaklardan veri toplar.  
- **LLM + FAISS destekli RAG pipeline** ile hızlı ve doğru cevaplar üretir.  
- **Kaynak gösterir**, böylece şeffaf ve doğrulanabilir bilgiler sunar.  
- Opsiyonel olarak **görselden bitki hastalık teşhisi** yapar.  

---

## ✨ Özellikler
- 🔍 **Hızlı Arama ve Sorgulama** (LLM + FAISS destekli RAG)
- 🦠 **Bitki Hastalık Teşhisi** (Opsiyonel CV + OCR entegrasyonu)
- 📅 **Bakım Takvimi Önerisi**
- 📚 **Kaynak Gösterme** ile şeffaf cevaplar
- 📥 **Çoklu Veri Kaynağı Desteği** (PDF, Word, Web makaleleri, Görseller)

---

## 🛠️ Teknik Yığın
| Katman | Teknoloji |
|--------|-----------|
| **LLM** | GPT-4 / LLaMA 3 / Mistral |
| **Embedding** | SentenceTransformers (Türkçe + İngilizce) |
| **Veritabanı** | FAISS veya Milvus |
| **OCR** | Tesseract / PaddleOCR |
| **Backend** | FastAPI |
| **Frontend** | Streamlit |
| **Deployment** | Docker + Hugging Face Spaces / Railway |

---

## 📌 Kullanım Alanları
- 🌾 **Sera Yönetimi**
- 🥦 **Meyve / Sebze Yetiştiriciliği**
- 🩺 **Bitki Hastalık ve Zararlı Kontrolü**
- 🌱 **Organik Tarım Uygulamaları**

---

## 🚀 Kurulum

### 1️⃣ Depoyu Klonla
```bash
git clone https://github.com/kullanici/yesil-bakis.git
cd yesil-bakis

<div align="center">

 
 
  ### Bilgiye Giden Kestirme Yol.
  
  <p><strong>Saatlerce süren içerikleri saniyelere sığdırın. Vaktiniz size kalsın.</strong></p>

  <p>
    <a href="https://github.com/electrichunter/KisaKes.ai/blob/main/LICENSE"><img src="https://img.shields.io/github/license/electrichunter/KisaKes.ai?style=for-the-badge&color=5865F2" alt="Lisans"></a>
    <a href="#"><img src="https://img.shields.io/badge/durum-geliştirme-orange?style=for-the-badge" alt="Proje Durumu"></a>
    <a href="#"><img src="https://img.shields.io/github/stars/electrichunter/KisaKes.ai?style=for-the-badge&color=gold" alt="GitHub Yıldızları"></a>
    <a href="#"><img src="https://img.shields.io/github/last-commit/electrichunter/KisaKes.ai?style=for-the-badge&color=green" alt="Son Commit"></a>
  </p>
  
  <br>

  <p>
    <a href="#-problem-ne"><strong>Problem Ne?</strong></a> ·
    <a href="#-çözüm-nedir"><strong>Çözüm Nedir?</strong></a> ·
    <a href="#-teknoloji-yığını"><strong>Teknolojiler</strong></a> ·
    <a href="#-nasıl-çalışır"><strong>Nasıl Çalışır?</strong></a> ·
    <a href="#-kurulum"><strong>Kurulum</strong></a>
  </p>
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/electrichunter/KisaKes.ai/main/assets/kisakes_demo.gif" alt="KısaKes.ai Uygulama Demosu" width="85%">
</p>

---

## <a name="-problem-ne"></a> 🤯 Problem Ne?

Günümüz dijital dünyasında **bilgiye ulaşmak kolay, onu sindirmek zor.** Saatlerce süren podcast'ler, YouTube videoları ve upuzun makaleler... Hepsinin içindeki değerli bilgiye ihtiyacımız var ama en değerli kaynağımız olan **zamanımız** kısıtlı.

## <a name="-çözüm-nedir"></a> ✨ Çözüm Nedir?

**KısaKes.ai**, bu bilgi yorgunluğuna modern bir çözüm sunar. Tek yapmanız gereken, özetlemek istediğiniz YouTube videosunun veya makalenin linkini yapıştırmak. Yapay zeka destekli altyapımız saniyeler içinde içeriğin özünü çıkarır ve size en önemli noktaları hap gibi sunar.

* **🚀 Hız Kazanın:** Saatlik içerikleri dakikalara indirin.
* **🎯 Odaklanın:** Sadece en önemli bilgilere ulaşın, gürültüyü atlayın.
* **🧠 Daha Fazla Öğrenin:** Kısıtlı zamanda daha fazla konuya hakim olun.

---

## <a name="-teknoloji-yığını"></a> 🛠️ Teknoloji Yığını

Bu proje, modern ve ölçeklenebilir teknolojiler kullanılarak tutkuyla geliştirilmiştir.

<table>
  <tr>
    <td align="center"><strong>Frontend</strong></td>
    <td align="center"><strong>Backend</strong></td>
    <td align="center"><strong>Yapay Zeka</strong></td>
    <td align="center"><strong>DevOps</strong></td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://reactjs.org/" target="_blank"><img src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=for-the-badge" alt="React"></a><br>
      <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white&style=for-the-badge" alt="TailwindCSS"></a>
    </td>
    <td align="center">
      <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge" alt="FastAPI"></a><br>
      <a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge" alt="Python"></a>
    </td>
    <td align="center">
      <a href="https://openai.com/" target="_blank"><img src="https://img.shields.io/badge/-OpenAI-412991?logo=openai&logoColor=white&style=for-the-badge" alt="OpenAI"></a><br>
      <a href="https://ollama.ai/" target="_blank"><img src="https://img.shields.io/badge/-Ollama-lightgrey?style=for-the-badge" alt="Ollama"></a>
    </td>
    <td align="center">
      <a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" alt="Docker"></a><br>
      <a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge" alt="PostgreSQL"></a>
    </td>
  </tr>
</table>

---

## <a name="-nasıl-çalışır"></a> ⚙️ Nasıl Çalışır?

<details>
  <summary><strong>Arka planda neler olduğunu merak ediyorsan tıkla!</strong></summary>

  1.  **URL Analizi:** Kullanıcı bir link yapıştırdığında, backend önce bunun bir YouTube linki mi yoksa standart bir web sayfası mı olduğunu anlar.
  2.  **Veri Çekme:**
      * **YouTube için:** `youtube_transcript_api` kütüphanesi ile videonun tüm altyazı metni çekilir.
      * **Makale için:** `BeautifulSoup4` ile sayfanın HTML'i analiz edilir ve sadece ana metin içeriği temizlenir.
  3.  **Yapay Zeka Büyüsü:** Elde edilen uzun metin, güçlü bir dil modeline (örn: GPT-4) özel bir komutla (`prompt`) gönderilir: "Bu metni en önemli 5 noktayı vurgulayan, anlaşılır bir özet haline getir."
  4.  **Sunum:** AI'dan gelen özet, temiz ve okunaklı bir formatta kullanıcı arayüzüne gönderilir.
</details>

---

## <a isim="-kurulum"></a> 🚀 Yerel Makinede Çalıştırma

Projeyi kendini makinenizde denemek için:

''bash
# 1. Projeyi klonlayın
git klonu [https://github.com/electrichunter/KisaKes.ai.git](https://github.com/electrichunter/KisaKes.ai.git)
cd KisaKes.ai

# 2. Backend'i kurun ve çalıştırın (Terminal 1)
cd arka ücü
python - m venv venv
# Sanal ortamı aktif edin (Windows: venv\Scripts\Activate | Mac/Linux: source venv/bin/activate)
pip yükselmek - r requirements.txt
python - m uvicorn app.main: uygulama - - yeniden yükselme

# 3. Frontend'i çalıştırın (Terminal 2)
cd ../ön uç
npm yükseleyin
npm çalıştır dev
'`'
Uygulama şimdi `http://localhost:3000` adresinde seni bekliyor!

---

## <a isim="-yol-haritası"></a> ?? ️ Yol Haritası

- [x] **MVP Konsepti:** Temel YouTube ve makale özetleme.
- [ ] **Kullanıcı Hesapları:** Özet geçmişini kaydetme ve kullanım limitleri.
- [ ] **Freemium Modeli:** Aylık ucretsiz kullanım hakkı ve premium abonelik.
- [ ] **Podcast Özetleme:** Ses dosyalarından metin çıkmazma (Konuşmadan Metne).
- [ ] **Tarayıcı Eklentisi:** Tek tıkla özetleme için Chrome/Firefox eklentisi.
- [ ] **Ollama Entegrasyonu:** Maliyetleri düşürmek için kendine barındırılan (kendi kendine barındırılan) AI modelleri.

---

<div hizalamak="merkez">
  <i̇k>
  <p>Bu proje MIT Lisansı altında dağıtılmaktadır.</p>
  <br>
  <p><güçlü>Ömer Faruk Uysal</güçlü></p>
  <p>
    <a href="https://github.com/electrichunter"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=beyaz" alt="GitHub"></a>
    <a href="[https://www.linkedin.com/in/omerfarukuysal](https://www.linkedin.com/in/omer-farukuysal/)"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=beyaz" alt="Bağlantılı"></a>
  </p>
  <br>
  <p><küçük>KısaKes.ai © 2025</küçük></p>
</div>

[ ?? ️ Başa Dön](#)

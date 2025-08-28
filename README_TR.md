# TSD-WebUI (Turkish Stable Diffusion WebUI)
🇹🇷 **Türkçe Stable Diffusion Web Arayüzü - Google Colab İçin Optimize Edilmiş**

[![GitHub](https://img.shields.io/badge/GitHub-TSD--WebUI-blue)](https://github.com/projeman/TSD-WebUI) 
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/projeman/TSD-WebUI/blob/main/TSD_ComfyUI_Flux_v1.ipynb)
[![Türkçe](https://img.shields.io/badge/Dil-Türkçe-red)](https://github.com/projeman/TSD-WebUI)

## 🎯 Özellikler

- 🇹🇷 **Tam Türkçe Destek**: Arayüz ve prompts Türkçe
- ⚡ **Google Colab Optimizasyonu**: Tesla T4/V100 GPU desteği
- 🎨 **ComfyUI Entegrasyonu**: Modern node-based arayüz
- 🔥 **Flux Model Desteği**: En son AI modelleri
- 🌐 **Cloudflared Tunnel**: Kolay paylaşım
- 📱 **Türk Kültürü Prompts**: Hazır Türkçe şablonlar

## 🚀 Hızlı Başlangıç

### Google Colab'da Çalıştır
1. [![Colab'da Aç](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/projeman/TSD-WebUI/blob/main/TSD_ComfyUI_Flux_v1.ipynb)
2. `Runtime` > `Change runtime type` > `GPU` seç
3. İlk hücreyi çalıştır ve seçenekleri ayarla
4. İkinci hücreyi çalıştır ve başlat

### Yerel Kurulum
```bash
git clone https://github.com/projeman/TSD-WebUI.git
cd TSD-WebUI
# Kurulum talimatları yakında...
```

## 🎨 Türkçe Prompt Örnekleri

### Portre
```
güzel türk kadın, geleneksel kıyafet, istanbul arka plan, 4K, ultra detailed
yakışıklı türk erkek, modern stil, boğaz manzarası, profesyonel fotoğraf
```

### Manzara  
```
kapadokya balonları, gün doğumu, renkli gökyüzü, cinematic lighting
istanbul boğazı, köprü, gün batımı, epic vista, masterpiece
```

### Kültürel
```
osmanlı sarayı, altın süslemeler, tarihsel, baroque architecture
türk kahvesi, geleneksel fincan, çini desenler, still life
```

## ⚙️ Desteklenen Modeller

- 🔥 **Flux Dev v1** (Önerin)
- ⚡ **Flux Schnell** (Hızlı)  
- 🎯 **SDXL Lightning**
- 🖼️ **SD 1.5 Optimized**
- 🇹🇷 **Turkish LoRA** (Geliştiriliyor)

## 📋 Sistem Gereksinimleri

### Google Colab (Önerilen)
- ✅ **GPU**: Tesla T4 (15GB VRAM)
- ✅ **RAM**: 12-13GB 
- ✅ **Disk**: 100GB+ (Drive bağlantılı)
- ✅ **Internet**: Stabil bağlantı

### Yerel Sistem
- 🔧 **GPU**: 8GB+ VRAM (RTX 3070+)
- 🔧 **RAM**: 16GB+ 
- 🔧 **Disk**: 50GB+ boş alan
- 🔧 **Python**: 3.9+

## 🛠️ Kurulum Modları

| Mod | Özellikler | Disk Kullanımı | Süre |
|-----|-----------|----------------|------|
| ☕ **Temel** | ComfyUI + Flux | ~8GB | 5dk |
| 🍺 **Gelişmiş** | +ControlNet +LoRA | ~15GB | 10dk |
| 📸 **Fotoğraf** | +Upscaling +Face | ~20GB | 15dk |
| 🎥 **Video** | +AnimateDiff +SVD | ~25GB | 20dk |
| 👨‍💻 **Geliştirici** | Tam paket | ~30GB+ | 25dk+ |

## 🌟 Türkçe Özellikler

### Otomatik Çeviri
- Türkçe prompt'lar otomatik İngilizce'ye çevrilir
- Türk kültürü kelime sözlüğü entegre
- Context-aware çeviri sistemi

### Kültürel İçerik
- Osmanli dönem prompts
- Modern Türkiye şablonları  
- Yerel mimari ve manzara prompts
- Türk yemek kültürü prompts

### Türkçe Arayüz
- Tüm menüler Türkçe
- Türkçe tooltip'ler
- Türkçe hata mesajları

## 🎯 Kullanım Örnekleri

### 1. Temel Kullanım
```python
# Türkçe prompt gir
prompt = "güzel türk kadın, modern kıyafet"

# Otomatik çevirir ve üretir
generated_image = tsd.generate(prompt)
```

### 2. Gelişmiş Ayarlar
```python
# Detaylı ayarlar
settings = {
    "model": "Flux_dev_v1-fp8",
    "steps": 30,
    "cfg_scale": 7.5,
    "width": 1024,
    "height": 1024,
    "turkish_enhancement": True
}
```

## 🤝 Katkıda Bulunma

1. Repository'yi fork edin
2. Feature branch oluşturun (`git checkout -b yeni-özellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin yeni-özellik`)
5. Pull Request oluşturun

## 📞 İletişim & Destek

- 🐙 **GitHub**: [Issues](https://github.com/projeman/TSD-WebUI/issues)
- 💬 **Discord**: Turkish AI Community (yakında)
- 📧 **Email**: tsd-webui@turkish-ai.org
- 🌐 **Website**: https://turkish-ai.github.io

## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

## 🙏 Teşekkürler

- [SDVN Team](https://github.com/StableDiffusionVN) - Orijinal proje için
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Harika arayüz için
- [Black Forest Labs](https://blackforestlabs.ai/) - Flux modeller için
- Türk AI topluluğu - Geri bildirimler için

---

**🇹🇷 Türk Yapımı AI Aracı - Made with ❤️ in Turkey**
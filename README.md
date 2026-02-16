# ÖZ UFUK ASANSÖR Yönetim Sistemi

![ÖZ UFUK ASANSÖR](assets/oz-ufuk-logo.png)

## Proje Hakkında

ÖZ UFUK ASANSÖR için asansör bakım ve kontrol yönetim sistemi. Bu sistem, asansör bakım formlarını, kontrol listelerini ve raporlama araçlarını içerir.

## Özellikler

- ✅ Asansör kontrol formları
- ✅ Otomatik doldurma şablonları
- ✅ Excel ve Markdown formatları
- ✅ Dijital imza alanları
- ✅ Müşteri ve asansör bilgi yönetimi
- ✅ Periyodik bakım takibi

## Şablonlar

### 1. Markdown Formatı
📄 `templates/ASANSOR_KONTROL_FORMU.md`
- Web ve mobil uygulamalar için uygun
- Kolay okunabilir format
- Versiyon kontrolü kolay

### 2. Excel/CSV Formatı
📊 `templates/ASANSOR_KONTROL_FORMU_EXCEL.csv`
- Excel'de açılabilir
- Veri analizi için uygun
- Toplu işlem yapılabilir

## Kullanım

### Form Doldurma

Şablonlardaki `{{PLACEHOLDER}}` değerlerini sisteminize göre doldurun:

```javascript
// Örnek kullanım
const formData = {
  FIRMA_ADRES: "Merkez Mah. Devran Sokak No:43 Kağıthane İstanbul",
  FIRMA_TEL: "+90 212 294 0585",
  FIRMA_EMAIL: "info@ozufukasansor.com",
  MUSTERI_ADI: "ABC Plaza",
  SICIL_NO: "12345",
  ASANSOR_TIPI: "İnsan Asansörü",
  DURAK_SAYISI: "8",
  KAPASITE: "630",
  // ... diğer alanlar
};
```

### Otomatik İmza Ekleme

İmza alanları için:

```javascript
// İmza alanları
MUSTERI_IMZA_ALANI: "[Base64 imza görseli]",
TEKNISYEN_IMZA_ALANI: "[Base64 imza görseli]"
```

## Form Bölümleri

### A) Kuyu Odası Kontrolleri
- Genel durum
- Su izleri
- Hidrofor
- Aydınlatma
- Regülatör
- Taban ve duvar kontağı

### B) Kabin Kontrolleri
- Kat kontrolleri
- Seviye ayarları
- Kapı sistemleri
- Güvenlik ekipmanları
- Aydınlatma ve alarm

### C) Kabin Üstü Kontrolleri
- Tavan kontrolü
- Paraşüt sistemi
- Ray kontrolü
- Kablo ve bağlantılar
- Fren sistemleri

### D) Ek Kontroller
- Bakım dosyası
- Bağlantı arşivleri
- Güvenlik tertibatı

## Katkıda Bulunma

Bu projeye katkıda bulunmak için:

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/YeniOzellik`)
5. Pull Request açın

## Lisans

© 2026 ÖZ UFUK ASANSÖR - Tüm hakları saklıdır.

## İletişim

**ÖZ UFUK ASANSÖR**
- 📍 Adres: [Firma Adresi]
- 📞 Tel: [Firma Telefonu]
- 📧 E-posta: [Firma E-postası]
- 🌐 Web: [Firma Web Sitesi]

---

## Versiyon Geçmişi

### v1.0.0 (2026-02-16)
- ✨ İlk versiyon
- 📝 Markdown form şablonu
- 📊 Excel/CSV form şablonu
- 📖 README dokümantasyonu

---

**Not:** Bu sistem ÖZ UFUK ASANSÖR'ün iç kullanımı için tasarlanmıştır.
# Değişiklik günlüğü

## 2.0.0-rc.1 — 24 Ekim 2026 (Ön sürüm)

### Değişti

- Kaynak kod Git altında düzenlendi; sürümden üretilen tekrarlanabilir ZIP dağıtımı eklendi.
- Türkçe kurulum, güvenlik, katkı ve test belgeleri güncellendi.
- Otomatik doğrulama, davranış testleri ve bağımlılık güncelleme yapılandırması eklendi.

### Güvenlik ve uyumluluk

- Güvenli varsayılanlar ve açık entegrasyon sınırları tanımlandı.
- 1.x kurulumlarından otomatik geçiş desteklenmez; README geçiş adımlarını izleyin.

- Sabit gecikmeli paket butonu yerine doğrulanmış Promise sonucuna bağlı adapter sözleşmesi getirildi (kırıcı değişiklik).
- Eksik entegrasyon/ürün ID'sinde hediye devre dışı; normal tema sepet akışı korunuyor.
- Çift tıklama ve kısmi başarıda tekrar ana ürün ekleme engelleniyor.
- Yerleşik özelleştirme alanlarına toplu müdahale kaldırıldı; değerler işlem bağlamında iletiliyor.
- Yeni ürün ID'leri sıfır, teslimat/not özellikleri varsayılan kapalı.

## 1.0.1 — 14 Eylül 2026

- Önceki sürüm teslim tarihi/not alanlarını ana ürünün yerleşik özelleştirme alanlarına senkronize etti.
- Paket eklenirken yerleşik alanları geçici kapatma davranışı eklendi; bu yaklaşım 2.0'da kaldırıldı.

## 1.0.0

- İlk hediye paketi, teslim tarihi ve kart notu modülü.

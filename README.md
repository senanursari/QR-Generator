# 📦 QR Kod Uygulamaları

Bu repo QR kod üretme ve kişilere mail aracılığı ile gönderme ve etkinliklerde qr kontrolü sağlama scriptlerini içerir. Etkinlik girişlerinde hızlı ve güvenli katılım kontrolü sağlamak amacıyla kullanılmaktadır.

---

## 🛠️ İçerik

- `qr_generator.py` → Katılımcı bilgilerine özel QR kod üretir
- `qr_check.html` → Kamera veya görsel üzerinden QR kodu okur ve doğrular
- `send_qr_emails.py/` → Oluşturulan QR kodları mail ile sahiplerine gönderilir. (örnek klasör)
- `README.md` → Açıklama dosyası

---

## 📦 Gereksinimler

Python 3 yüklü olmalıdır. Aşağıdaki kütüphaneleri yüklemeniz gerekir:

```bash
pip install qrcode opencv-python pyzbar

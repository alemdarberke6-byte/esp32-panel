# ESP Kontrol paneli

ESP32 cihazlarını MQTT (WSS) üzerinden kontrol eden tek dosyalık web paneli.

- Broker bilgileri ve şifre bu depoda **yok**; panel açılınca girilir ve sadece o tarayıcının `localStorage`'ında saklanır.
- iPhone: Safari'de aç → Paylaş → **Ana Ekrana Ekle**.
- Cihaz tarafı: `IotLink` kütüphanesi, topic şeması `<base>/<name>/set` → cihaz, `<base>/<name>/state` ← cihaz, `<base>/status` online/offline.

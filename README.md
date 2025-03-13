# Django E-Ticaret Platformu

![E-Ticaret Logo](https://via.placeholder.com/800x400)

Bu proje, Django framework'ü kullanılarak geliştirilmiş kapsamlı bir e-ticaret platformudur. Kullanıcı dostu arayüzü ve çeşitli özellikleriyle modern bir alışveriş deneyimi sunmayı amaçlamaktadır.

## 🚀 Özellikler

- **Kullanıcı Yönetimi**: Kayıt olma, giriş yapma, şifre sıfırlama, profil güncelleme
- **Ürün Kataloğu**: Kategorilere göre ürün listeleme, filtreleme ve arama
- **Alışveriş Sepeti**: Ürün ekleme, çıkarma, miktar güncelleme
- **Ödeme İşlemleri**: Güvenli ödeme entegrasyonu
- **Sipariş Takibi**: Sipariş durumu ve geçmişi görüntüleme
- **Admin Paneli**: Ürün, kategori, sipariş ve kullanıcı yönetimi
- **Responsive Tasarım**: Tüm cihazlarda optimum görüntüleme

## 📋 Gereksinimler

- Python 3.8+
- Django 4.0+
- PostgreSQL veya SQLite
- Diğer bağımlılıklar için `requirements.txt` dosyasına bakınız

## 🔧 Kurulum

1. Repoyu klonlayın:
```bash
git clone https://github.com/Seyfullah-KIZILKAYAA/Django-E-Ticaret-Platformu.git
cd Django-E-Ticaret-Platformu
```

2. Sanal ortam oluşturun ve aktifleştirin:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Bağımlılıkları yükleyin:
```bash
pip install -r requirements.txt
```

4. Veritabanı migrasyonlarını uygulayın:
```bash
python manage.py migrate
```

5. Superuser oluşturun:
```bash
python manage.py createsuperuser
```

6. Uygulamayı çalıştırın:
```bash
python manage.py runserver
```

7. Tarayıcınızda `http://127.0.0.1:8000` adresine giderek uygulamayı görüntüleyin.

## 📸 Ekran Görüntüleri

![Ana Sayfa](https://via.placeholder.com/600x300)
*Ana Sayfa*

![Ürün Sayfası](https://via.placeholder.com/600x300)
*Ürün Detay Sayfası*

![Sepet](https://via.placeholder.com/600x300)
*Alışveriş Sepeti*

## 🛠️ Proje Yapısı

```
Django-E-Ticaret-Platformu/
├── accounts/            # Kullanıcı yönetimi
├── products/            # Ürün ve kategori yönetimi
├── carts/               # Sepet işlemleri
├── orders/              # Sipariş işlemleri
├── payments/            # Ödeme entegrasyonu
├── static/              # Statik dosyalar (CSS, JS, Resimler)
├── templates/           # HTML şablonları
├── media/               # Kullanıcı yüklenen medya dosyaları
├── ecommerce/           # Ana proje dizini ve ayarlar
├── manage.py
├── requirements.txt
└── README.md
```

## 📝 Kullanım

1. Ana sayfadan ürünleri görüntüleyin veya kategoriler arasında gezinin
2. İstediğiniz ürünleri sepetinize ekleyin
3. Sepeti görüntüleyin ve ürün miktarlarını güncelleyin
4. Ödeme sayfasına ilerleyin ve teslimat bilgilerinizi girin
5. Ödeme yöntemini seçin ve siparişi tamamlayın
6. Profil sayfanızdan sipariş durumunu takip edin

## 🔄 API Endpointleri

| Endpoint | Metod | Açıklama |
|----------|-------|----------|
| `/api/products/` | GET | Tüm ürünleri listeler |
| `/api/products/:id/` | GET | Belirli bir ürünün detaylarını gösterir |
| `/api/categories/` | GET | Tüm kategorileri listeler |
| `/api/cart/` | GET | Kullanıcının sepetini gösterir |
| `/api/cart/add/` | POST | Sepete ürün ekler |
| `/api/orders/` | GET | Kullanıcının siparişlerini listeler |
| `/api/orders/:id/` | GET | Belirli bir siparişin detaylarını gösterir |


## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakınız.

## 📞 İletişim

Seyfullah KIZILKAYA - [GitHub](https://github.com/Seyfullah-KIZILKAYAA)

Proje Linki: [https://github.com/Seyfullah-KIZILKAYAA/Django-E-Ticaret-Platformu](https://github.com/Seyfullah-KIZILKAYAA/Django-E-Ticaret-Platformu)

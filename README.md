# StockAPP API Projesi

Bu proje, Stock App uygulaması için gerekli olan API'yi oluşturmayı amaçlamaktadır. Django ve Django REST Framework kullanarak, React uygulamamızın ihtiyaç duyduğu backend API'yi sağlamaktadır.

## Proje İçeriği

- **Backend:** Django & Django REST Framework
- **Frontend:** React (Proje frontend tarafını da içermemektedir, sadece API sağlanmaktadır)

## Özellikler

- Kullanıcı kimlik doğrulama ve yetkilendirme
- CRUD işlemleri (Create, Read, Update, Delete) için API uç noktaları
- JWT veya Token tabanlı kimlik doğrulama
- Veritabanı yönetimi

## Başlarken

### Gereksinimler

- Python 3.x
- Django
- Django REST Framework
- Node.js ve npm (veya Yarn, eğer frontend kütüphanesi kullanılıyorsa)

### Kurulum

#### Backend (Django)

1. **Depoyu Klonlayın:**

   ```bash
   git clone <repo-url>
   cd <repo-directory>

   python -m venv env
   source env/bin/activate # Unix/Mac
   .\env\Scripts\activate # Windows
   ```

```bash
pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

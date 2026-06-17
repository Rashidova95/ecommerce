# E-Commerce API
 
Django REST Framework asosida qurilgan e-commerce backend. mahsulot katalogi, buyurtmalar, flash sale va Stripe orqali to'lov funksiyalarini o'z ichiga oladi.
 
## Texnologiyalar
 
- Python 3 / Django
- Django REST Framework
- Simple JWT (autentifikatsiya)
- Stripe (to'lovlar)
- drf-yasg (Swagger API hujjatlari)
- SQLite (development)
## Ilovalar tuzilishi
 
| Ilova | Vazifasi |
|---|---|
| `custom_auth` | Telefon raqam + SMS kod orqali ro'yxatdan o'tish/kirish, JWT token |
| `products` | Category, Product, Order, Review, FlashSale, ProductViewHistory |
| `billing` | Stripe orqali to'lov qabul qilish (`Payment` modeli) |

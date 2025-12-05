

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الحلويات الفاخر</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* styles.css داخلياً للبساطة، مع ألوان وردية */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fce4ec; /* وردي فاتح */
            color: #333;
        }
        .hero {
            background: linear-gradient(135deg, #ff80ab, #f8bbd9); /* gradient وردي */
            min-height: 50vh;
        }
        .product-card {
            border: none;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
        .btn-primary {
            background-color: #e91e63; /* وردي داكن */
            border-color: #e91e63;
        }
        .btn-primary:hover {
            background-color: #c2185b; /* وردي أغمق */
            border-color: #c2185b;
        }
        .navbar-brand {
            font-weight: bold;
            color: #ff80ab !important; /* وردي فاتح */
        }
        .navbar-dark {
            background-color: #c2185b !important; /* وردي داكن للتنقل */
        }
    </style>
</head>
<body>
    <!-- شريط التنقل -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">متجر الحلويات الفاخر</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">الرئيسية</a></li>
                    <li class="nav-item"><a class="nav-link" href="cakes.html">الكيك</a></li>
                    <li class="nav-item"><a class="nav-link" href="biscuits.html">البسكويت</a></li>
                    <li class="nav-item"><a class="nav-link" href="chocolates.html">الشوكولاتة</a></li>
                    <li class="nav-item"><a class="nav-link" href="eastern.html">الحلويات الشرقية</a></li>
                    <li class="nav-item"><a class="nav-link" href="western.html">الحلويات الغربية</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">اتصل بنا</a></li>
                    <li class="nav-item"><a class="nav-link" href="delivery.html">طلبات التوصيل</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- الصفحة الرئيسية -->
    <section id="home" class="hero bg-gradient text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">مرحباً بكم في متجر الحلويات الفاخر</h1>
            <p class="lead">استمتعوا بأفضل الحلويات الطازجة والمصنوعة يدوياً</p>
            <a href="#products" class="btn btn-light btn-lg">استكشف الأصناف</a>
        </div>
    </section>

    <!-- أقسام الأصناف الرئيسية -->
    <section id="products" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">أصنافنا</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?cake" class="card-img-top" alt="كيك">
                        <div class="card-body">
                            <h5 class="card-title">الكيك</h5>
                            <p class="card-text">كيكات طازجة بأشكال متنوعة.</p>
                            <a href="cakes.html" class="btn btn-primary">عرض التفاصيل</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?biscuit" class="card-img-top" alt="بسكويت">
                        <div class="card-body">
                            <h5 class="card-title">البسكويت</h5>
                            <p class="card-text">بسكويت لذيذ بمختلف النكهات.</p>
                            <a href="biscuits.html" class="btn btn-primary">عرض التفاصيل</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?chocolate" class="card-img-top" alt="شوكولاتة">
                        <div class="card-body">
                            <h5 class="card-title">الشوكولاتة</h5>
                            <p class="card-text">شوكولاتة فاخرة بأنواع متنوعة.</p>
                            <a href="chocolates.html" class="btn btn-primary">عرض التفاصيل</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?baklava" class="card-img-top" alt="حلويات شرقية">
                        <div class="card-body">
                            <h5 class="card-title">الحلويات الشرقية</h5>
                            <p class="card-text">حلويات تقليدية مثل البقلاوة والكنافة.</p>
                            <a href="eastern.html" class="btn btn-primary">عرض التفاصيل</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?donut" class="card-img-top" alt="حلويات غربية">
                        <div class="card-body">
                            <h5 class="card-title">الحلويات الغربية</h5>
                            <p class="card-text">دوناتس وكوكيز وغيرها.</p>
                            <a href="western.html" class="btn btn-primary">عرض التفاصيل</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // script.js داخلياً للبساطة
        document.querySelectorAll('.btn').forEach(btn => {
            btn.addEventListener('click', () => {
                alert('شكراً لزيارتك!');
            });
        });
    </script>
</body>
</html>

<!-- ملف cakes.html (صفحة الكيك) -->
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الكيك - متجر الحلويات الفاخر</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* نفس styles.css مع الألوان الوردية */
        body { font-family: 'Arial', sans-serif; background-color: #fce4ec; color: #333; }
        .product-card { border: none; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .product-card:hover { transform: translateY(-5px); }
        .card-img-top { height: 200px; object-fit: cover; }
        .btn-primary { background-color: #e91e63; border-color: #e91e63; }
        .btn-primary:hover { background-color: #c2185b; border-color: #c2185b; }
        .navbar-dark { background-color: #c2185b !important; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">متجر الحلويات الفاخر</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">الرئيسية</a></li>
                    <li class="nav-item"><a class="nav-link" href="cakes.html">الكيك</a></li>
                    <li class="nav-item"><a class="nav-link" href="biscuits.html">البسكويت</a></li>
                    <li class="nav-item"><a class="nav-link" href="chocolates.html">الشوكولاتة</a></li>
                    <li class="nav-item"><a class="nav-link" href="eastern.html">الحلويات الشرقية</a></li>
                    <li class="nav-item"><a class="nav-link" href="western.html">الحلويات الغربية</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">اتصل بنا</a></li>
                    <li class="nav-item"><a class="nav-link" href="delivery.html">طلبات التوصيل</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">الكيك</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?chocolate-cake" class="card-img-top" alt="كيك الشوكولاتة">
                        <div class="card-body">
                            <h5 class="card-title">كيك الشوكولاتة</h5>
                            <p class="card-text">كيك غني بالشوكولاتة الداكنة.</p>
                            <p class="price">السعر: 50 ريال</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?vanilla-cake" class="card-img-top" alt="كيك الفانيليا">
                        <div class="card-body">
                            <h5 class="card-title">كيك الفانيليا</h5>
                            <p class="card-text">كيك خفيف بنكهة الفانيليا.</p>
                            <p class="price">السعر: 45 ريال</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://source.unsplash.com/400x300/?strawberry-cake" class="card-img-top" alt="كيك الفراولة">
                        <div class="card-body">
                            <h5 class="card-title">كيك الفراولة</h5>
                            <p class="card-text">كيك طازج بالفراولة الطبيعية.</p>
                            <p class="price">السعر: 55 ريال</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!-- ملف biscuits.html (صفحة البسكويت) -->
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>البسكويت - متجر الحلويات الفاخر</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* نفس styles.css مع الألوان الوردية */
        body { font-family: 'Arial', sans-serif; background-color: #fce4ec; color: #333; }
        .product-card { border: none; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .product-card:hover { transform: translateY(-5px); }
        .card-img-top { height: 200px; object-fit: cover; }
        .btn-primary { background-color: #e91e63; border-color: #e91e63; }
        .btn-primary:hover { background-color: #c2185b; border-color: #c2185b; }
        .navbar-dark { background-color: #c2185b !important; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">متجر الحلويات الفاخر</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">الرئيسية</a></li>
                    <li class="nav-item"><a class="nav-link" href="cakes.html">الكيك</a></li>
                    <li class="nav-item"><a class="nav-link" href="biscuits.html">البسكويت</a></li>
                    <li class="nav-item"><a class="nav-link" href="chocolates.html">الشوكولاتة</a></li>
                    <li class="nav-item"><a class="nav-link" href="eastern.html">الحلويات الشرقية</a></li>
                    <li class="nav-item"><a class="nav-link" href="western.html">الحلويات الغربية</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">اتصل بنا</a></li>
                    <li class="nav-item"><a class="nav-link" href="delivery.html">طلبات التوصيل</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zombozo Web Sitesi</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
          rel="stylesheet" 
          xintegrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
          crossorigin="anonymous">
          
    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&display=swap" rel="stylesheet">
</head>

<body class="custom-bg text-white"> 
    
    <header>
        <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top shadow">
            <div class="container">
                
                <a class="navbar-brand fw-bold fs-3 text-danger" href="#">
                    <span class="logo-underline">ZOMBOZO</span>
                </a>
                
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Ana Sayfa</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#oynanis">Oynanış</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#hakkinda">Hakkında</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#iletisim">İletişim</a>
                        </li>
                        <li class="nav-item ms-lg-3">
                            <a class="btn btn-danger btn-sm" href="#">HEMEN İNDİR</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <section class="text-center py-5 hero-section"> 
        <div class="container my-5">
            
            <h1 class="zombozo-title fw-bold text-danger mb-4">ZOMBOZO</h1>
            
            <p class="lead text-white-50 mb-5">
                Karanlık Sana Geliyor Kaçıcak Mısın? Yoksa Savaşıcakmısın?
            </p>
            
            <div class="d-inline-block"> 
                <a href="#" class="btn btn-danger btn-lg px-5 py-3">
                    ŞİMDİ İNDİR
                </a>
            </div>

        </div>
    </section>

    <section class="container py-5">
        <div class="row text-center g-4">
            
            <div class="col-md-4">
                <div class="p-4 rounded bg-secondary h-100 shadow">
                    <i class="fs-1 mb-3">💀</i>
                    <h3 class="fw-bold text-danger">KORKU</h3>
                    <p class="text-white-50">
                        Kanasusamış zombiler ile korkuyu iliklerinize kadar hissedin 💀
                    </p>
                </div>
            </div>

            <div class="col-md-4">
                <div class="p-4 rounded bg-secondary h-100 shadow">
                    <i class="fs-1 mb-3">🌃</i>
                    <h3 class="fw-bold text-danger">HAYATTA KALMA</h3>
                    <p class="text-white-50">
                        Zombilerin hükmettiği bu şehirde hayatta kalabilecek misin ❓
                    </p>
                </div>
            </div>

            <div class="col-md-4">
                <div class="p-4 rounded bg-secondary h-100 shadow">
                    <i class="fs-1 mb-3">🖌️</i>
                    <h3 class="fw-bold text-danger">TASARIM</h3>
                    <p class="text-white-50">
                        Gerçekçi oynanış, modeller ve ortam tasarımı ile oyun deneyiminizi en üst düzeye çıkarın.
                    </p>
                </div>
            </div>
        </div>
    </section><section class="py-5" id="oynanis">
    <div class="container">
        <h2 class="display-4 fw-bold text-center text-danger mb-5">Oynanış Detayları</h2>
        <div class="row align-items-center">
            <div class="col-lg-6 mb-4">
                <p class="lead text-white-50">
                    Zombozo'da hayatta kalabilmek için sadece nişan alma yeteneğiniz değil, aynı zamanda zekanız da önemlidir, Oyun, sürekli karanlık ve karlı sisli bir ortamda geçmektedir, Bu durum tehlikenin her köşede gizlendiği anlamına gelir, Ana görevimiz şehri kurtaracak olan panzehiri bulmak ve salgını kalıcı olarak durdurmaktır.

Oyun Karlı hafif sisli bir ortamda geçiyor amacımız şehire yayılan zombi salgınını engelleyebilecek güçte olan panzehiri bulmak ve tabi siz bunu yapmaya çalışırken zombilerin eli armut toplamayacak Oyun sürekli gece olduğu için görüş açısı düşüktür, kaynak yönetimi zorlaşır, Taktik, keşif ve korku bu amansız hayatta kalma mücadelesinin temel taşlarıdır.
                </p>
            </div>
            <div class="col-lg-6 mb-4">
                <p class="lead text-white-50">
                    Zombozo Evreni: Hikaye, isimsiz bir şehirde, kimyasal bir deneyin felaketle sonuçlanmasının ardından başlar. İlk başta sadece bir salgın olarak görülen olay, kısa sürede geri dönüşü olmayan bir kıyamete dönüşür. Şehir, kalın bir sis tabakası ve sürekli yağan kar altında, donmuş bir cehenneme ev sahipliği yapmaktadır.

Oyuncu, salgının ilk günlerinde hayatta kalmayı başarmış az sayıdaki kişiden biridir. Radyo yayınları, panzehirin şehrin merkezindeki eski bir laboratuvarda olabileceğini işaret ediyor. Amacınız basittir: Oraya ulaşmak, panzehiri bulmak ve insanlığa son bir umut ışığı sunmaktır. Ancak her adımda, hayatta kalma içgüdülerini kaybetmiş zombilerin karanlık ordusu ile karşı karşıyasınız.
            </div>
        </div>
    </div>
</section>
    <section class="py-5 bg-black" id="hakkinda">
    <div class="container">
        <h2 class="display-4 fw-bold text-center text-danger mb-5">Hakkında</h2>
        <div class="row">
            <div class="col-lg-6 mb-4">
                <p class="lead text-white-50">
                    Zombozo, hayatta kalma türünü karanlık 
                    bir şehirde yeniden tanımlıyor. Oyun, kaosu, 
                    korkuyu ve sınırlı kaynaklarla verilen umutsuz 
                    mücadeleyi merkeze alıyor. Geliştirici ekibimiz,
                    en derin korkularınızı tetiklemek için gerçekçi 
                    grafikler ve atmosferik ses tasarımı kullandı.
                </p>
            </div>
            <div class="col-lg-6">
                <p class="lead text-white-50">
                    Amacımız basit: Zombilere yem olmadan ne
                    kadar hayatta kalabileceğini görmek. Her köşe, 
                    her terk edilmiş bina, hayatta kalmak için bir 
                    fırsat ya da ölümcül bir tuzak olabilir. Zombozo 
                    evrenine adım atmaya cesaretin var mı?
                </p>
            </div>
        </div>
    </div>
</section>
<section class="py-5" id="iletisim">
    <div class="container">
        <h2 class="display-4 fw-bold text-center text-danger mb-5">İletişim</h2>
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <form class="p-5 rounded bg-secondary shadow">
                    <div class="mb-3">
                        <label for="inputAdSoyad" class="form-label text-white">Adınız Soyadınız</label>
                        <input type="text" class="form-control bg-dark text-white border-danger" id="inputAdSoyad">
                    </div>
                    <div class="mb-3">
                        <label for="inputEmail" class="form-label text-white">E-Posta Adresiniz</label>
                        <input type="email" class="form-control bg-dark text-white border-danger" id="inputEmail">
                    </div>
                    <div class="mb-3">
                        <label for="inputMesaj" class="form-label text-white">Mesajınız</label>
                        <textarea class="form-control bg-dark text-white border-danger" id="inputMesaj" rows="4"></textarea>
                    </div>
                    <div class="d-grid">
                        <button type="submit" class="btn btn-danger btn-lg">Gönder</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
            xintegrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
            crossorigin="anonymous">
    </script>
</body>
</html>


<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jede Tu | AI Programmer Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@10.0.2.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css">
    <style>
        :root {
            --nintendo-red: #e60012;
            --dark-bg: #1a1a1a;
            --card-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            scroll-behavior: smooth;
        }

        /* Navbar */
        .navbar {
            background-color: var(--dark-bg);
            border-bottom: 3px solid var(--nintendo-red);
        }
        .navbar-brand, .nav-link {
            color: white !important;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--dark-bg) 0%, #333 100%);
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        .hero h1 {
            font-size: 3.5rem;
            font-weight: 800;
        }
        .hero .highlight {
            color: var(--nintendo-red);
        }

        /* Section Styling */
        section {
            padding: 80px 0;
        }
        .section-title {
            margin-bottom: 50px;
            position: relative;
            font-weight: 700;
        }
        .section-title::after {
            content: '';
            width: 60px;
            height: 4px;
            background: var(--nintendo-red);
            position: absolute;
            bottom: -10px;
            left: 0;
        }

        /* Project Cards */
        .project-card {
            background: white;
            border: none;
            border-radius: 15px;
            box-shadow: var(--card-shadow);
            transition: transform 0.3s ease;
            height: 100%;
        }
        .project-card:hover {
            transform: translateY(-10px);
        }
        .badge-tech {
            background-color: #e9ecef;
            color: var(--dark-bg);
            margin-right: 5px;
            font-size: 0.8rem;
        }

        /* Footer */
        footer {
            background-color: var(--dark-bg);
            color: white;
            padding: 40px 0;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#"><i class="bi bi-cpu-fill me-2"></i>Jede Tu</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">關於我</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">核心技術</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">精選專案</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">聯繫方式</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero">
        <div class="container">
            <h1 class="mb-3">我是 <span class="highlight">Jede Tu</span></h1>
            <p class="lead mb-4">AI Programmer | 全端開發工程師 | .NET 專家</p>
            <p class="mb-5">「程式碼是邏輯的體現，而 AI 是加速創意的燃料。」</p>
            <a href="#projects" class="btn btn-outline-light btn-lg">查看我的作品</a>
        </div>
    </header>

    <section id="about" class="container">
        <div class="row align-items-center">
            <div class="col-lg-6">
                <h2 class="section-title">關於我</h2>
                <p>我是一位專注於全端開發與自動化整合的工程師，擅長利用 <strong>.NET 8.0</strong> 核心技術建構穩定的後端架構。</p>
                <p>我熱衷於將複雜的業務場景（如二手車商經營管理）轉化為精確的技術規格，並透過 RESTful API 將數據無縫延伸至 Android 移動端與社群平台。</p>
            </div>
            <div class="col-lg-6">
                <div class="p-4 bg-white rounded shadow-sm">
                    <h5>核心理念</h5>
                    <ul class="list-unstyled">
                        <li><i class="bi bi-check2-circle text-danger me-2"></i> 高效的資料自動化 (ETL)</li>
                        <li><i class="bi bi-check2-circle text-danger me-2"></i> 跨平台系統整合 (Web + Android)</li>
                        <li><i class="bi bi-check2-circle text-danger me-2"></i> 現代化 C# 12 開發實踐</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="bg-light">
        <div class="container">
            <h2 class="section-title">技術軍火庫</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card h-100 p-3 border-0 shadow-sm">
                        <i class="bi bi-code-slash fs-1 text-danger"></i>
                        <h4 class="mt-3">後端開發</h4>
                        <p>ASP.NET Core 8.0, C# 12, Entity Framework Core</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-3 border-0 shadow-sm">
                        <i class="bi bi-database fs-1 text-danger"></i>
                        <h4 class="mt-3">資料工程</h4>
                        <p>SQL Server, SQLite, 資料清洗與 ETL 自動化匯入</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-3 border-0 shadow-sm">
                        <i class="bi bi-phone fs-1 text-danger"></i>
                        <h4 class="mt-3">行動端整合</h4>
                        <p>Android (Java/XML), RESTful API 介接與連線優化</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="container">
        <h2 class="section-title">精選專案</h2>
        <div class="row g-4">
            <div class="col-md-6 col-lg-4">
                <div class="card project-card">
                    <div class="card-body">
                        <h5 class="card-title">Nintendo Switch 遊戲管理平台</h5>
                        <p class="card-text text-muted">整合官方數據與社群互動，支援收藏追蹤與五星評論系統。</p>
                        <div class="mt-3">
                            <span class="badge badge-tech">.NET 8.0</span>
                            <span class="badge badge-tech">MVC</span>
                            <span class="badge badge-tech">Web API</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="card project-card">
                    <div class="card-body">
                        <h5 class="card-title">空氣品質 Open Data API</h5>
                        <p class="card-text text-muted">使用 ASP.NET Core 介接開放數據來源，轉換為標準化 REST 服務。</p>
                        <div class="mt-3">
                            <span class="badge badge-tech">C#</span>
                            <span class="badge badge-tech">JSON Parsing</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="card project-card">
                    <div class="card-body">
                        <h5 class="card-title">二手車商管理系統分析</h5>
                        <p class="card-text text-muted">從業務場景定義功能需求與外部實體，將商業邏輯轉化為技術架構。</p>
                        <div class="mt-3">
                            <span class="badge badge-tech">System Analysis</span>
                            <span class="badge badge-tech">SQL Design</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="bg-dark text-white">
        <div class="container text-center">
            <h2 class="mb-4">準備好啟動下一個專案了嗎？</h2>
            <div class="d-flex justify-content-center gap-4 fs-2">
                <a href="https://www.facebook.com/jede.tu" class="text-white"><i class="bi bi-facebook"></i></a>
                <a href="#" class="text-white"><i class="bi bi-github"></i></a>
                <a href="mailto:example@email.com" class="text-white"><i class="bi bi-envelope-at"></i></a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <small>&copy; 2026 Jede Tu. Built with ❤️ using .NET 8.0 Logic.</small>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    
    <script>
        // 簡單的互動：控制台彩蛋
        console.log("%cJede Tu Portfolio", "color: #e60012; font-size: 20px; font-weight: bold;");
        console.log("「好的系統不僅要能跑，更要具備擴展性。」");

        // 平滑捲動補充（針對舊版瀏覽器）
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>아이랑맵 - 우리 아이와 함께하는 동네 놀이 보물찾기</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        /* 헤더 섹션 */
        .header {
            background: linear-gradient(135deg, #FF6B6B 0%, #4ECDC4 100%);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }
        .logo {
            font-size: 2rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .nav-menu {
            display: flex;
            gap: 2rem;
            list-style: none;
        }
        .nav-menu a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: opacity 0.3s;
        }
        .nav-menu a:hover {
            opacity: 0.8;
        }
        .cta-button {
            background: rgba(255,255,255,0.2);
            padding: 0.75rem 1.5rem;
            border-radius: 25px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: background 0.3s;
        }
        .cta-button:hover {
            background: rgba(255,255,255,0.3);
        }
        /* 히어로 섹션 */
        .hero {
            background: linear-gradient(135deg, #FFE5B4 0%, #FFCCCB 30%, #E6E6FA 70%, #B0E0E6 100%);
            padding: 120px 0 80px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.4)"/><circle cx="80" cy="40" r="1.5" fill="rgba(255,255,255,0.5)"/><circle cx="40" cy="80" r="1" fill="rgba(255,255,255,0.6)"/></svg>') repeat;
            animation: float 20s infinite linear;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            100% { transform: translateY(-100px); }
        }
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 2rem;
            position: relative;
            z-index: 1;
        }
        .hero-title {
            font-size: 3.5rem;
            font-weight: bold;
            color: #2C3E50;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        .hero-subtitle {
            font-size: 1.5rem;
            color: #34495E;
            margin-bottom: 2rem;
        }
        .hero-description {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 3rem;
            line-height: 1.8;
        }
        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }
        .primary-button {
            background: linear-gradient(45deg, #FF6B6B, #4ECDC4);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: transform 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .primary-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }
        .secondary-button {
            background: transparent;
            color: #2C3E50;
            border: 2px solid #2C3E50;
            padding: 1rem 2rem;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s;
        }
        .secondary-button:hover {
            background: #2C3E50;
            color: white;
        }
        /* 문제 섹션 */
        .problem-section {
            padding: 80px 0;
            background: #f8f9fa;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }
        .section-title {
            font-size: 2.5rem;
            text-align: center;
            color: #2C3E50;
            margin-bottom: 3rem;
            font-weight: bold;
        }
        .problem-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }
        .problem-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }
        .problem-card:hover {
            transform: translateY(-5px);
        }
        .problem-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .problem-title {
            font-size: 1.3rem;
            color: #E74C3C;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .problem-text {
            color: #666;
            line-height: 1.6;
        }
        /* 솔루션 섹션 */
        .solution-section {
            padding: 80px 0;
            background: white;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        .feature-card {
            background: linear-gradient(145deg, #f0f8ff, #e6f3ff);
            padding: 2rem;
            border-radius: 20px;
            text-align: center;
            transition: all 0.3s;
            border: 1px solid #e0e0e0;
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .feature-icon {
            font-size: 3.5rem;
            margin-bottom: 1rem;
        }
        .feature-title {
            font-size: 1.4rem;
            color: #2C3E50;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .feature-description {
            color: #666;
            line-height: 1.6;
            margin-bottom: 1rem;
        }
        .feature-list {
            list-style: none;
            text-align: left;
        }
        .feature-list li {
            color: #555;
            margin-bottom: 0.5rem;
            padding-left: 1.5rem;
            position: relative;
        }
        .feature-list li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: #4ECDC4;
            font-weight: bold;
        }
        /* 타겟 섹션 */
        .target-section {
            padding: 80px 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }
        .target-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        .target-card {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
        }
        .target-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .target-title {
            font-size: 1.3rem;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .target-description {
            line-height: 1.6;
            opacity: 0.9;
        }
        /* CTA 섹션 */
        .cta-section {
            padding: 80px 0;
            background: linear-gradient(135deg, #FF6B6B 0%, #4ECDC4 100%);
            color: white;
            text-align: center;
        }
        .cta-content {
            max-width: 600px;
            margin: 0 auto;
        }
        .cta-title {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        .cta-description {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }
        .cta-primary {
            background: white;
            color: #FF6B6B;
            padding: 1rem 2rem;
            border: none;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: transform 0.3s;
        }
        .cta-primary:hover {
            transform: translateY(-2px);
        }
        /* 푸터 */
        .footer {
            background: #2C3E50;
            color: white;
            padding: 3rem 0 1rem;
        }
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }
        .footer-section h3 {
            margin-bottom: 1rem;
            color: #4ECDC4;
        }
        .footer-section ul {
            list-style: none;
        }
        .footer-section ul li {
            margin-bottom: 0.5rem;
        }
        .footer-section ul li a {
            color: #bbb;
            text-decoration: none;
            transition: color 0.3s;
        }
        .footer-section ul li a:hover {
            color: #4ECDC4;
        }
        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid #444;
            color: #999;
        }
        /* 반응형 디자인 */
        @media (max-width: 768px) {
            .nav-menu {
                display: none;
            }
            .hero-title {
                font-size: 2.5rem;
            }
            .hero-subtitle {
                font-size: 1.2rem;
            }
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            .section-title {
                font-size: 2rem;
            }
            .problem-grid,
            .features-grid,
            .target-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- 헤더 -->
    <header class="header">
        <nav class="nav-container">
            <div class="logo">
                 아이랑맘
            </div>
            <ul class="nav-menu">
                <li><a href="#features">서비스 소개</a></li>
                <li><a href="#programs">프로그램</a></li>
                <li><a href="#target">대상</a></li>
                <li><a href="#contact">문의</a></li>
            </ul>
            <a href="#cta" class="cta-button">무료 체험하기</a>
        </nav>
    </header>
    <!-- 히어로 섹션 -->
    <section class="hero">
        <div class="hero-content">
            <h1 class="hero-title">아이랑맘</h1>
            <p class="hero-subtitle">우리 아이와 함께 떠나는 동네 놀이 보물찾기</p>
            <p class="hero-description">
                평범한 공간도 특별한 놀이 장소가 됩니다.<br>
                숨겨진 동네 놀이터부터 전문가 프로그램까지,<br>
                아이의 창의력과 사회성을 키우는 놀이 경험을 선물하세요.
            </p>
            <div class="hero-buttons">
                <a href="#" class="primary-button">🚀 지금 시작하기</a>
                <a href="#features" class="secondary-button">📱 서비스 둘러보기</a>
            </div>
        </div>
    </section>
    <!-- 문제 섹션 -->
    <section class="problem-section">
        <div class="container">
            <h2 class="section-title">이런 고민 있으셨나요?</h2>
            <div class="problem-grid">
                <div class="problem-card">
                    <div class="problem-icon">😟</div>
                    <h3 class="problem-title">"아이와 어디서 뭘 하고 놀아야 할까?"</h3>
                    <p class="problem-text">매일 반복되는 놀이 고민, 새로운 놀이 아이디어가 필요해요</p>
                </div>
                <div class="problem-card">
                    <div class="problem-icon">🔄</div>
                    <h3 class="problem-title">"매번 같은 키즈카페만 가는 것 같아..."</h3>
                    <p class="problem-text">상업시설 외에도 다양한 놀이 공간이 있을 텐데 찾기 어려워요</p>
                </div>
                <div class="problem-card">
                    <div class="problem-icon">🕵️</div>
                    <h3 class="problem-title">"우리 동네 숨겨진 놀이터가 있을 텐데..."</h3>
                    <p class="problem-text">안전하고 교육적인 지역 놀이 자원 정보가 부족해요</p>
                </div>
                <div class="problem-card">
                    <div class="problem-icon">🎯</div>
                    <h3 class="problem-title">"아이 연령에 맞는 놀이를 찾고 싶어!"</h3>
                    <p class="problem-text">우리 아이에게 적합한 맞춤형 놀이 가이드가 필요해요</p>
                </div>
            </div>
        </div>
    </section>
    <!-- 솔루션 섹션 -->
    <section class="solution-section" id="features">
        <div class="container">
            <h2 class="section-title">아이랑맘이 해결해드립니다! ✨</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🔍</div>
                    <h3 class="feature-title">숨겨진 놀이 보물 발견</h3>
                    <p class="feature-description">우리 동네 곳곳에 숨어있는 안전하고 유익한 놀이 공간을 발견하세요</p>
                    <ul class="feature-list">
                        <li>작은 공원부터 도서관 놀이방까지</li>
                        <li>폐교 활용 시설 정보 제공</li>
                        <li>실시간 운영 상태 확인</li>
                        <li>안전도 및 시설 정보</li>
                    </ul>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🎯</div>
                    <h3 class="feature-title">맞춤형 놀이 가이드</h3>
                    <p class="feature-description">각 장소별로 아이 연령에 맞는 창의적인 놀이 방법을 제안해드려요</p>
                    <ul class="feature-list">
                        <li>연령대별 놀이 아이디어</li>
                        <li>계절별 특화 놀이법</li>
                        <li>교육적 놀이 콘텐츠</li>
                        <li>안전 놀이 가이드</li>
                    </ul>
                </div>                
                <div class="feature-card">
                    <div class="feature-icon">🎪</div>
                    <h3 class="feature-title">전문가 놀이 프로그램</h3>
                    <p class="feature-description">놀이 전문가가 기획한 특별한 프로그램에 참여하세요</p>
                    <ul class="feature-list">
                        <li>숲 탐험 오감 놀이 클래스</li>
                        <li>창의력 증진 미술 체험</li>
                        <li>계절별 테마 놀이 투어</li>
                        <li>전통 놀이 체험 프로그램</li>
                    </ul>
                </div>                
                <div class="feature-card">
                    <div class="feature-icon">🏘️</div>
                    <h3 class="feature-title">지역 연계 체험</h3>
                    <p class="feature-description">동네 소상공인과 함께하는 다양한 체험 활동을 만나보세요</p>
                    <ul class="feature-list">
                        <li>동네 베이커리 빵 만들기</li>
                        <li>작은 공방 도예 체험</li>
                        <li>농가 농촌 체험 활동</li>
                        <li>맞춤형 놀이 키트 제공</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <!-- 타겟 섹션 -->
    <section class="target-section" id="target">
        <div class="container">
            <h2 class="section-title">이런 분들께 추천합니다</h2>
            <div class="target-grid">
                <div class="target-card">
                    <div class="target-icon">👶</div>
                    <h3 class="target-title">0-7세 자녀를 둔 부모님</h3>
                    <p class="target-description">영유아 자녀와 함께하는 질 높은 놀이 시간을 원하시는 분</p>
                </div>
                <div class="target-card">
                    <div class="target-icon">🎨</div>
                    <h3 class="target-title">적극적인 놀이 활동 선호</h3>
                    <p class="target-description">아이와의 창의적이고 교육적인 놀이에 관심이 많은 분</p>
                </div>
                <div class="target-card">
                    <div class="target-icon">🛡️</div>
                    <h3 class="target-title">안전한 놀이 공간 추구</h3>
                    <p class="target-description">안전하고 검증된 놀이 환경을 찾으시는 분</p>
                </div>
                <div class="target-card">
                    <div class="target-icon">🏘️</div>
                    <h3 class="target-title">지역 커뮤니티 참여 희망</h3>
                    <p class="target-description">동네 기반 육아 커뮤니티 활동에 참여하고 싶은 분</p>
                </div>
            </div>
        </div>
    </section>
    <!-- CTA 섹션 -->
    <section class="cta-section" id="cta">
        <div class="container">
            <div class="cta-content">
                <h2 class="cta-title">지금 바로 시작해보세요!</h2>
                <p class="cta-description">
                    "평범한 공간도 특별한 놀이 장소가 됩니다"<br>
                    우리 아이의 놀이 세상을 넓혀보세요
                </p>
                <div class="cta-buttons">
                    <a href="https://irangmam.wordpress.com" class="cta-primary">🚀 무료 체험 신청</a>
                    <a href="https://www.instagram.com/@irangmam" class="cta-primary">📱 앱 다운로드</a>
                </div>
            </div>
        </div>
    </section>
    <!-- 푸터 -->
    <footer class="footer" id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>아이랑맘</h3>
                    <ul>
                        <li><a href="#">서비스 소개</a></li>
                        <li><a href="#">놀이 프로그램</a></li>
                        <li><a href="#">지역별 놀이터</a></li>
                        <li><a href="#">커뮤니티</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>고객지원</h3>
                    <ul>
                        <li><a href="#">자주 묻는 질문</a></li>
                        <li><a href="#">이용약관</a></li>
                        <li><a href="#">개인정보처리방침</a></li>
                        <li><a href="#">문의하기</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>연락처</h3>
                    <ul>
                        <li>📧 https://www.instagram.com/@irangmam</li>
                        <li>📱 카카오톡: @아이랑맘</li>
                        <li>🌐 https://irangmam.wordpress.com</li>
                        <li>📍 서울특별시 강남구</li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>소셜미디어</h3>
                    <ul>
                        <li><a href="#">📘 페이스북</a></li>
                        <li><a href="https://www.instagram.com/@irangmam">📷 인스타그램</a></li>
                        <li><a href="#">🐦 트위터</a></li>
                        <li><a href="#">📺 유튜브</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 아이랑맘(I-Rang Mam). All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>

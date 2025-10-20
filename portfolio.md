<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>홍길동의 UX 포트폴리오 | UX Design Portfolio</title>
    <style>
        /* 기본적인 가독성을 위한 인라인 CSS입니다. 실제 포트폴리오에서는 별도 파일로 분리하는 것이 좋습니다. */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 0;
            max-width: 1000px;
            margin-left: auto;
            margin-right: auto;
        }
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid #ccc;
        }
        h1 {
            color: #333;
            margin-bottom: 5px;
        }
        h2 {
            color: #555;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
            margin-top: 40px;
        }
        section {
            padding: 20px 0;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        .project-item {
            margin-bottom: 30px;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <header>
        <h1>홍길동 (Gildong Hong)</h1>
        <p>UX 디자인 및 연구 포트폴리오</p>
        <p><strong>UX/HCI 대학원생</strong> | 사용자 중심 디자인, 리서치, 프로토타이핑</p>
    </header>

    <main>
        <section id="introduction">
            <h2>저를 소개합니다. 🎓</h2>
            <p>
                저는 **OOO 대학 UX/HCI 석사 과정**에 재학 중인 홍길동입니다. 사용자 경험(UX) 연구와 디자인에 깊은 관심을 가지고 있으며, 특히 **데이터 기반 의사결정**과 **포용적 디자인(Inclusive Design)** 방법론을 통해 사용자에게 가치를 제공하는 솔루션을 설계하는 데 중점을 두고 있습니다.
            </p>
            <p>
                본 포트폴리오에서는 지난 연구 프로젝트, 실무 인턴십 경험, 그리고 개인 프로젝트를 통해 제가 습득한 **사용자 리서치, 와이어프레이밍, 프로토타이핑, 사용성 평가** 역량을 보여드리고자 합니다. 새로운 도전을 통해 지속적으로 성장하고자 합니다.
            </p>
        </section>

        <section id="projects">
            <h2>주요 프로젝트 및 연구 목록 💡</h2>
            
            <div class="project-item">
                <h3>1. AI 기반 개인 맞춤형 교육 서비스 UX 디자인 연구</h3>
                <p><strong>역할:</strong> 주 연구원, UX 디자이너 | <strong>기간:</strong> 2024.03 - 2024.08</p>
                <p>
                    인공지능 추천 시스템을 활용한 교육 플랫폼의 학습 경험을 개선하기 위한 연구입니다. 정성적(심층 인터뷰) 및 정량적(설문조사) 리서치를 수행하여 페르소나를 도출하고, 사용자 여정 지도(User Journey Map)를 기반으로 핵심 기능을 재설계했습니다.
                </p>
                <ul>
                    <li><strong>핵심 성과:</strong> 재설계된 프로토타입의 A/B 테스트에서 사용자 만족도 $15\%$ 향상 달성.</li>
                    <li><strong>사용 기술:</strong> Figma, Sketch, Miro, SPSS (통계 분석).</li>
                    <li><a href="project1-detail.html">자세히 보기</a> (별도 상세 페이지 링크)</li>
                </ul>
            </div>

            <div class="project-item">
                <h3>2. 모바일 금융 앱 사용성 평가 및 개선</h3>
                <p><strong>역할:</strong> UX 인턴 | <strong>기간:</strong> 2023.09 - 2024.02</p>
                <p>
                    실제 서비스 중인 모바일 뱅킹 앱의 복잡한 송금 프로세스에 대한 사용성 평가를 진행했습니다. 휴리스틱 평가 및 현장 조사를 통해 문제점을 식별하고, 개선된 인터랙션 디자인 및 와이어프레이밍을 제안했습니다.
                </p>
                <ul>
                    <li><strong>핵심 성과:</strong> 발견된 12가지 주요 사용성 문제 중 8가지에 대한 해결책 제안 및 개발팀에 전달.</li>
                    <li><strong>사용 기술:</strong> Adobe XD, Usability Testing (Think-aloud protocol), Trello.</li>
                    <li><a href="project2-detail.html">자세히 보기</a></li>
                </ul>
            </div>
            
            </section>

        <section id="skills">
            <h2>핵심 역량 및 도구 🛠️</h2>
            <ul>
                <li><strong>UX 리서치:</strong> 심층 인터뷰, 설문조사 설계/분석, 사용성 평가, A/B 테스트, 경쟁사 분석</li>
                <li><strong>UX 디자인:</strong> 와이어프레이밍, 프로토타이핑, 정보 구조(IA) 설계, 사용자 여정 지도, 페르소나 개발</li>
                <li><strong>디자인 도구:</strong> Figma (숙련), Sketch, Adobe XD, Miro, Photoshop, Illustrator</li>
                <li><strong>분석 도구:</strong> SPSS, R (기초 통계), Google Analytics, Hotjar</li>
            </ul>
        </section>

    </main>

    <footer>
        <p style="text-align: center; margin-top: 50px; padding-top: 20px; border-top: 1px solid #eee;">
            연락처: example@email.com | LinkedIn: /in/gildonghong | GitHub: /gildongdev
        </p>
    </footer>

</body>
</html>

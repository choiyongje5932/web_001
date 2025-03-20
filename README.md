# web_001
REPO를 이용한 간단한 홈페이지 만들기

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자기소개</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            color: #4CAF50;
        }
        .about, .skills, .contact {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .skills ul {
            list-style-type: none;
            padding: 0;
        }
        .skills ul li {
            background-color: #f1f1f1;
            margin: 5px 0;
            padding: 8px;
            border-radius: 4px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>안녕하세요, 저는 [이름]입니다!</h1>
        <p>웹 개발자이자 기술 열정가입니다.</p>
    </header>

    <nav>
        <a href="#about">소개</a>
        <a href="#skills">기술</a>
        <a href="#contact">연락처</a>
    </nav>

    <div class="container">
        <section id="about" class="section about">
            <h2>자기소개</h2>
            <p>안녕하세요! 저는 웹 개발에 열정을 가진 [이름]입니다. 다양한 웹 기술을 배우고 활용하는 것을 좋아합니다. 사용자 경험을 중요하게 생각하며, 창의적인 문제 해결을 통해 더 나은 웹을 만들기 위해 노력하고 있습니다.</p>
            <p>저는 [이전 경험/학력]을 바탕으로 웹 개발 분야에서 [경력/학습한 기간] 동안 경험을 쌓았습니다. 앞으로도 꾸준히 성장하며 더 나은 개발자가 되기 위해 힘쓰겠습니다.</p>
        </section>

        <section id="skills" class="section skills">
            <h2>기술</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Vue.js</li>
                <li>Node.js, Express</li>
                <li>Python, Django</li>
                <li>Git, GitHub</li>
            </ul>
        </section>

        <section id="contact" class="section contact">
            <h2>연락처</h2>
            <p>저와 연락하고 싶다면 아래 방법으로 연락해주세요:</p>
            <ul>
                <li>이메일: [이메일 주소]</li>
                <li>전화: [전화번호]</li>
                <li>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 [이름]. 모든 권리 보유.</p>
    </footer>

</body>
</html>

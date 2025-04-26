<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ゴリラ社会主義共和国</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>ゴリラ社会主義共和国</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">共和国について</a></li>
                <li><a href="#government">政府の構成</a></li>
                <li><a href="#economy">経済と社会</a></li>
                <li><a href="#culture">文化と芸術</a></li>
                <li><a href="#news">ニュース</a></li>
                <li><a href="#contact">お問い合わせ</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>共和国について</h2>
            <p>ゴリラ社会主義共和国は、平等と労働を重視する社会主義国家です。設立の目的は全ての国民が平等に生活できる社会を作ることです。</p>
        </section>

        <section id="government">
            <h2>政府の構成</h2>
            <p>当国は社会主義的な理念に基づき、全ての市民が積極的に国家運営に参加します。革命家、労働者、教育者などのロールが重要な役割を果たします。</p>
        </section>

        <section id="economy">
            <h2>経済と社会</h2>
            <p>ゴリラ社会主義共和国では、労働を重んじ、資本主義に代わる平等な経済システムを築いています。</p>
        </section>

        <section id="culture">
            <h2>文化と芸術</h2>
            <p>文化活動は社会の発展に不可欠です。音楽、芸術、文学を通じて国民が自己表現を行い、共に成長します。</p>
        </section>

        <section id="news">
            <h2>最新ニュース</h2>
            <p>最新のニュースや政府発表はこのセクションに掲載されます。</p>
        </section>

        <section id="contact">
            <h2>お問い合わせ</h2>
            <p>お問い合わせは公式メールまたはSNSをご利用ください。</p>
        </section>
    </main>

    <footer>
        <p>© 2025 ゴリラ社会主義共和国. All rights reserved.</p>
    </footer>
</body>
</html>
/* 基本設定 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

header .logo h1 {
    margin: 0;
    font-size: 2rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

h2 {
    font-size: 1.8rem;
    margin-bottom: 0.5rem;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}

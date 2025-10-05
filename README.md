- 👋 Hi, I’m Muharrem Emin Yurt I am 17 years old 3nd year high school student
- 👀 I am interested in object oriented programming and web development
- 🌱 I’m currently learning C++ in Qt Framework, Html Css Javascript in Visual Studio Code and i am interested in Sql
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hi!</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /*
 * GitHub README için Şık ve Modern CSS
 */

        :root {
            /* Renk Paleti */
            --primary-color: #2c3e50;
            /* Koyu Mavi/Gri - Ana metin ve başlıklar */
            --secondary-color: #3498db;
            /* Parlak Mavi - Vurgu, ikonlar ve hover efektleri */
            --background-color: #ffffff;
            /* Beyaz - Arkaplan */
            --section-bg-color: #f8f8f8;
            /* Açık Gri - Bölüm arkaplanları */
            --text-color: #555555;
            /* Orta Gri - Paragraf metni */
            --border-color: #e0e0e0;
            /* Sınır çizgisi */
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--background-color);
            color: var(--primary-color);
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            /* Kenarlarda boşluk bırakır */
            max-width: 900px;
            /* İçeriği ortalar ve okunabilirliği artırır */
            margin: 0 auto;
        }

        /* --- Başlıklar --- */
        h1 {
            font-size: 2.8em;
            color: var(--primary-color);
            margin-bottom: 0.1em;
            border-bottom: 3px solid var(--secondary-color);
            /* Vurgu çizgisi */
            display: inline-block;
            /* Çizginin sadece metin kadar olmasını sağlar */
            padding-bottom: 5px;
        }

        h2 {
            font-size: 1.8em;
            color: var(--secondary-color);
            border-left: 5px solid var(--secondary-color);
            padding-left: 10px;
            margin-top: 30px;
            margin-bottom: 15px;
        }

        h3 {
            font-size: 1.2em;
            color: var(--primary-color);
            margin-top: 10px;
        }

        /* --- Genel Paragraf ve Bölüm Stilleri --- */
        p {
            color: var(--text-color);
            margin-bottom: 15px;
        }

        div {
            margin-bottom: 30px;
            padding: 15px;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            /* Yumuşak köşeler */
            background-color: var(--section-bg-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            /* Hafif gölge */
        }

        .intro {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            padding: 15px;
            background-color: var(--primary-color);
            border: none;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
        }

        .intro p {
            background-color: var(--secondary-color);
            color: var(--background-color);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: flex;
            align-items: center;
            transition: transform 0.2s, background-color 0.2s;
            margin: 0;
        }

        .intro p:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
        }

        .intro i {
            margin-right: 8px;
            font-size: 1.2em;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-top: 10px;
            object-fit: cover;
        }

        .section img {
            width: calc(50% - 10px);
            height: 200px;
            display: inline-block;
            margin-right: 10px;
            border: 3px solid var(--secondary-color);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
        }

        .section img:last-child {
            margin-right: 0;
        }

        div>section>h2 {
            font-size: 1.4em;
            color: var(--primary-color);
            border-left: none;
            padding-left: 0;
            margin-top: 20px;
            margin-bottom: 5px;
            font-weight: 600;
        }
    </style>
</head>

<body>
    <div class="intro">
        <p><i class="fa-brands fa-html5"></i>HTML5</p>
        <p><i class="fa-brands fa-css3-alt"></i>CSS3</p>
        <p><i class="fa-brands fa-js"></i>JavaScript</p>
        <p>C++</p>
        <p>QT</p>
        <p><i class="fa-brands fa-node"></i>Node.js</p>
        <p><i class="fa-brands fa-github"></i>GitHub</p>
        <p><i class="fa-brands fa-linux"></i>Linux</p>
    </div>

    <div>
        <h1>Muharrem Emin</h1>
        <h3>High School 4th Grade</h3>
        <p style="font-size: 18px;">I am a student working on improving my software skills from Türkiye.</p>
    </div>
    <div>
        <h2>What I Wish</h2>
        <p style="font-size: 18px;">I want to progress in C++ using Qt and develop applications for Linux and Windows, and perhaps later for
            mobile devices.</p>
    </div>

    <div>
        <h2>My Personal Space</h2>
        <section>
            <h2>I enjoy watching UFC and e-sports like CS:GO and League of Legends.</h2>
            <section>
                <h3>My Favorite Fighter and Player</h3>
                <img src="Israel Adesanya.JPEG" alt=""><img src="100t-closer-min-scaled.jpg" alt="">
            </section>
            <h2>-I like playing chess and solving puzzles.</h2>
            <h2>-I enjoy listening to music, especially rock and metal genres.</h2>
        </section>
    </div>

</body>

</html>

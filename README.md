# My-site..html<!DOCTYPE html>
<html lang="tl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sino ang Nakikinig? | Blog</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(
                135deg,
                #fff4dc,
                #ffe4d6,
                #e8e1ff,
                #fff7c2
            );
            color: #2b2b2b;
            line-height: 1.8;
        }

        /* HEADER */

        header {
            background: linear-gradient(
                135deg,
                #172b46,
                #435c78,
                #d9796c,
                #f2b84b
            );
            color: white;
            text-align: center;
            padding: 70px 20px;
        }

        header h1 {
            font-size: 3.5rem;
            letter-spacing: 2px;
            margin-bottom: 15px;
        }

        header p {
            font-size: 1.3rem;
        }

        /* NAVIGATION */

        nav {
            background-color: #24364b;
            text-align: center;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 20px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: #f2b84b;
            color: #24364b;
        }

        /* MAIN CONTAINER */

        .container {
            max-width: 950px;
            margin: 40px auto;
            padding: 20px;
        }

        article {
            background-color: rgba(255, 255, 255, 0.95);
            padding: 45px;
            border-radius: 25px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
        }

        /* BLOG IMAGE */

        .hero-image {
            width: 100%;
            max-height: 850px;
            object-fit: cover;
            border-radius: 20px;
            margin-bottom: 35px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            border: 8px solid #fff4dc;
        }

        /* TITLE */

        .blog-title {
            font-size: 2.8rem;
            color: #172b46;
            text-align: center;
            margin-bottom: 10px;
        }

        .subtitle {
            text-align: center;
            color: #b95d54;
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 35px;
        }

        /* TEXT */

        p {
            margin-bottom: 20px;
            font-size: 1.05rem;
        }

        /* SECTION TITLES */

        h2 {
            color: #172b46;
            margin-top: 45px;
            margin-bottom: 20px;
            padding: 15px 20px;
            border-radius: 12px;
            background: linear-gradient(
                90deg,
                #ffe08a,
                #ffd1c7
            );
        }

        /* EXAMPLES */

        .example {
            background-color: #f5edff;
            border-left: 6px solid #8e72b5;
            padding: 25px;
            margin: 25px 0;
            border-radius: 15px;
        }

        /* TIPS */

        .tip {
            background: linear-gradient(
                135deg,
                #e2f4e8,
                #d8f0ff
            );
            border-left: 6px solid #3e8b6b;
            padding: 20px;
            margin: 25px 0;
            border-radius: 15px;
        }

        /* QUESTIONS */

        .questions {
            background: linear-gradient(
                135deg,
                #172b46,
                #3c506b
            );
            color: white;
            padding: 30px;
            border-radius: 20px;
            margin: 30px 0;
        }

        .questions ul {
            padding-left: 25px;
        }

        .questions li {
            margin: 12px 0;
            font-size: 1.1rem;
        }

        /* QUOTE */

        .quote {
            background: linear-gradient(
                135deg,
                #ffe08a,
                #f7b5a8
            );
            padding: 40px;
            border-radius: 25px;
            text-align: center;
            margin: 40px 0;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }

        .quote p {
            font-size: 1.8rem;
            font-weight: bold;
            color: #172b46;
        }

        /* REMEMBER BOX */

        .remember {
            background-color: #e8e1ff;
            border: 3px dashed #8e72b5;
            padding: 30px;
            text-align: center;
            border-radius: 20px;
            margin-top: 30px;
        }

        .remember h3 {
            color: #6c4d92;
            font-size: 1.8rem;
            margin-bottom: 15px;
        }

        /* FOOTER */

        footer {
            background-color: #172b46;
            color: white;
            text-align: center;
            padding: 35px 20px;
            margin-top: 50px;
        }

        footer p {
            margin: 5px;
        }

        /* MOBILE */

        @media (max-width: 600px) {

            header {
                padding: 50px 20px;
            }

            header h1 {
                font-size: 2.3rem;
            }

            .blog-title {
                font-size: 2rem;
            }

            article {
                padding: 25px;
            }

            nav a {
                display: inline-block;
                margin: 5px;
            }

            .quote p {
                font-size: 1.4rem;
            }
        }

    </style>
</head>


<body>

    <!-- HEADER -->

    <header>
        <h1>Sino ang Nakikinig?</h1>
        <p>
            5 Tips Para Mas Maging Mapanuri at Epektibo
            sa Pakikipagkomunikasyon
        </p>
    </header>


    <!-- NAVIGATION -->

    <nav>
        <a href="#home">Home</a>
        <a href="#tips">5 Tips</a>
        <a href="#conclusion">Konklusyon</a>
    </nav>


    <!-- MAIN CONTENT -->

    <main class="container" id="home">

        <article>

            <!-- YOUR UPLOADED IMAGE -->

            <img
                src="received_1396818959182961.jpeg"
                alt="Sino ang Nakikinig communication infographic"
                class="hero-image"
            >


            <h1 class="blog-title">
                Sino ang Nakikinig?
            </h1>

            <p class="subtitle">
                5 Tips Para Mas Maging Mapanuri at Epektibo
                sa Pakikipagkomunikasyon
            </p>


            <p>
                Bago ka magsalita, huminto ka muna sandali,
                tanungin mo ang sarili mo kung:
                <strong>Sino ang kausap mo?</strong>
                <strong>Ano ang gusto mong iparating?</strong>
                At higit sa lahat,
                <strong>paano mo ito sasabihin?</strong>
            </p>


            <p>
                Araw-araw tayong nakikipagkomunikasyon.
                Nakikipag-usap tayo sa kaibigan, pamilya,
                kaklase, guro, at pati na rin sa mga taong
                hindi natin personal na kilala sa social media.
            </p>


            <p>
                Pero kahit araw-araw natin itong ginagawa,
                hindi ibig sabihin na lagi natin itong
                nagagawa nang tama.
            </p>


            <p>
                Minsan, tama naman ang gusto nating sabihin
                pero mali ang paraan ng pagkakasabi.
                Minsan naman, nagbibiro lang tayo pero may
                taong nasasaktan na pala.
            </p>


            <p>
                Kaya mahalagang itanong:
                <strong>“Sino ang nakikinig?”</strong>
            </p>


            <!-- TIPS SECTION -->

            <section id="tips">

                <h2>1. Kilalanin Muna ang Iyong Kausap</h2>

                <p>
                    Bago magsalita, isipin muna kung sino
                    ang iyong kausap. Hindi pare-pareho ang
                    edad, karanasan, kaalaman, at pananaw
                    ng bawat tao.
                </p>


                <div class="example">

                    <strong>
                        Kung kaibigan mo ang kausap:
                    </strong>

                    <p>
                        “Uy, may sasabihin ako sa'yo.”
                    </p>

                    <strong>
                        Kung guro naman ang kausap:
                    </strong>

                    <p>
                        “Ma'am/Sir, maaari po ba akong magtanong?”
                    </p>

                </div>


                <div class="tip">

                    <strong>💡 Tip:</strong>

                    <p>
                        Bago magsalita, tanungin ang sarili:
                        “Sino ang makikinig sa akin?”
                    </p>

                </div>



                <h2>2. Think Before You Speak or Send</h2>

                <p>
                    Mabilis magsalita. Mabilis ding mag-send.
                    Pero hindi lahat ng nasasabi o naipapadala
                    ay maaari pang mabawi.
                </p>


                <div class="example">

                    <p>
                        Sa halip na sabihin:
                    </p>

                    <strong>
                        “Wala ka talagang kwenta sa group.”
                    </strong>

                    <br><br>

                    <p>
                        Maaari mong sabihin:
                    </p>

                    <strong>
                        “Kailangan natin matapos yung part mo
                        para maipasa natin on time.
                        Kailan mo kaya ito matatapos?”
                    </strong>

                </div>


                <div class="tip">

                    <strong>🛑 STOP Technique:</strong>

                    <p>
                        Stop. Think. Observe. Proceed.
                    </p>

                </div>



                <h2>3. Piliin ang Tamang Salita at Tono</h2>

                <p>
                    Hindi lamang kung ano ang sinasabi natin
                    ang mahalaga. Pati ang tono at paraan ng
                    pagkakasabi ay maaaring makaapekto sa ating
                    kausap.
                </p>


                <div class="example">

                    <p>
                        Sa halip na:
                    </p>

                    <strong>
                        “Ang pangit naman ng ginawa mo.”
                    </strong>

                    <br><br>

                    <p>
                        Maaari mong sabihin:
                    </p>

                    <strong>
                        “Baka puwede nating ayusin ito
                        para mas maging okay.”
                    </strong>

                </div>


                <div class="tip">

                    <strong>💬 Tip:</strong>

                    <p>
                        Piliin ang mga salitang nagpapakita
                        ng respeto.
                    </p>

                </div>



                <h2>4. Makinig Bago Sumagot</h2>

                <p>
                    Ang komunikasyon ay hindi lamang tungkol
                    sa pagsasalita. Kasama rin dito ang
                    pakikinig.
                </p>


                <div class="example">

                    <p>
                        Sa halip na agad sabihin:
                    </p>

                    <strong>
                        “Ako nga rin, naranasan ko na 'yan.”
                    </strong>

                    <br><br>

                    <p>
                        Maaari mong sabihin:
                    </p>

                    <strong>
                        “Naiintindihan ko.
                        Gusto mo bang ikuwento pa sa akin?”
                    </strong>

                </div>


                <div class="tip">

                    <strong>👂 Tip:</strong>

                    <p>
                        Makinig, unawain, at magtanong kung may
                        bahagi kang hindi naintindihan.
                    </p>

                </div>



                <h2>5. Suriin Muna ang Impormasyon Bago Ito Ipasa</h2>

                <p>
                    Sa panahon ng social media, napakadaling
                    kumalat ang impormasyon. Pero hindi ibig
                    sabihin na dahil maraming nag-share ay
                    totoo na ito.
                </p>


                <div class="tip">

                    <strong>🔍 Bago Mag-share, Tanungin:</strong>

                    <p>• Saan galing ito?</p>
                    <p>• Totoo ba ito?</p>
                    <p>• Mapagkakatiwalaan ba ang source?</p>

                </div>

            </section>



            <!-- CONCLUSION -->

            <section id="conclusion">

                <h2>Sa Huli</h2>

                <p>
                    Ang mahusay na komunikasyon ay hindi tungkol
                    sa kung sino ang pinakamaraming nasasabi.
                    Ito ay tungkol sa kung paano tayo nakikinig,
                    umiintindi, at nagpapahayag nang may respeto.
                </p>


                <div class="questions">

                    <h3>Bago magsalita, tandaan ang mga tanong na ito:</h3>

                    <ul>
                        <li>Sino ang kausap ko?</li>
                        <li>Ano ang gusto kong sabihin?</li>
                        <li>Paano ko ito sasabihin?</li>
                        <li>Ano ang maaaring maging epekto nito?</li>
                    </ul>

                </div>


                <div class="quote">

                    <p>
                        “Ano ang sasabihin ko?”
                    </p>

                    <br>

                    <p>
                        “Sino ang Nakikinig?”
                    </p>

                </div>


                <div class="remember">

                    <h3>Remember</h3>

                    <p>
                        Ang tunay na mahusay na tagapagsalita
                        ay hindi lamang marunong magsalita.
                    </p>

                    <p>
                        Marunong din siyang makinig, umunawa,
                        at pumili ng tamang paraan upang
                        maiparating ang kanyang mensahe.
                    </p>

                </div>

            </section>

        </article>

    </main>


    <!-- FOOTER -->

    <footer>

        <p>
            © 2026 Sino ang Nakikinig?
        </p>

        <p>
            Makinig • Umunawa • Magsalita nang may respeto
        </p>

    </footer>


</body>
</html>

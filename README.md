

    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serikin Salama Family</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Trebuchet MS", Arial, sans-serif;
            background: #ffffff;
            color: #101c38;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 22px 6%;
            flex-wrap: wrap;
            gap: 20px;
        }

        .logo {
            font-size: 34px;
            font-weight: 900;
            color: #f47700;
            letter-spacing: 2px;
        }

        nav {
            display: flex;
            gap: 25px;
            flex-wrap: wrap;
        }

        nav a {
            color: #101c38;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }

        nav a:hover,
        nav a.active {
            color: #f47700;
        }

        .hero {
            min-height: 65vh;
            padding: 65px 8%;
            display: flex;
            align-items: center;
        }

        .hero-content {
            max-width: 600px;
        }

        .hero h1 {
            font-size: clamp(55px, 12vw, 100px);
            font-weight: 900;
            line-height: 0.95;
            letter-spacing: -4px;
            color: #101c38;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.7;
            margin: 25px 0;
            max-width: 430px;
            font-weight: bold;
        }

        .button {
            display: inline-block;
            background: #f47700;
            color: white;
            padding: 14px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 65px 8%;
        }

        section h2 {
            font-size: 35px;
            margin-bottom: 20px;
            color: #101c38;
        }

        section p {
            line-height: 1.8;
            max-width: 700px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(
                auto-fit, minmax(220px, 1fr)
            );
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            padding: 25px;
            background: #fff7ed;
            border-radius: 15px;
            border: 1px solid #ffe0bd;
        }

        .card h3 {
            margin-bottom: 12px;
            color: #f47700;
        }

        .history {
            background: #f7f8fc;
        }

        .meetings {
            background: #fff7ed;
        }

        footer {
            padding: 30px 8%;
            text-align: center;
            background: #101c38;
            color: white;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
                text-align: center;
            }

            nav {
                justify-content: center;
                gap: 15px;
            }

            .hero {
                padding: 55px 7%;
                min-height: 55vh;
            }

            .hero h1 {
                letter-spacing: -2px;
            }

            section {
                padding: 45px 7%;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">SERIKIN SALAMA.COM</div>

        <nav>
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#history">History</a>
            <a href="#album">Album</a>
            <a href="#blog">Blog</a>
            <a href="#meetings">Meetings</a>
        </nav>
    </header>

    <main>
        <section class="hero" id="home">
            <div class="hero-content">
                <h1>Family</h1>

                <p>
                    One family, one love, one legacy.
                    Celebrating our roots, preserving our
                    history, and building a stronger future
                    together.
                </p>

                <a href="#about" class="button">
                    Get Started
                </a>
            </div>
        </section>

        <section id="about">
            <h2>About Our Family</h2>
            <p>
                Welcome to the Serikin Salama family website.
                This is our digital home for celebrating our
                family, sharing memories, and keeping our
                generations connected through love, unity,
                respect, and togetherness.
            </p>
        </section>

        <section class="history" id="history">
            <h2>Our Family History</h2>
            <p>
                Every family has a story worth preserving.
                This section is dedicated to our origins,
                our elders, our traditions, and the important
                moments that have shaped our family.
            </p>

            <div class="cards">
                <div class="card">
                    <h3>Our Origins</h3>
                    <p>
                        Discover where our family story began.
                        Family members can contribute verified
                        stories and historical information.
                    </p>
                </div>

                <div class="card">
                    <h3>Our Elders</h3>
                    <p>
                        Honour to alhaji ayuba gambari whose
                    wisdom,
                        sacrifices, and guidance helped
                        shape our family.
                    </p>
                </div>

                <div class="card">
                    <h3>Our Legacy</h3>
                    <p>
                        Preserve our values, traditions,
                        and memories for future generations.
                    </p>
                </div>
            </div>
        </section>

        <section id="album">
            <h2>Family Album</h2>
            <!-- FAMILY TREE -->
<section id="family-tree" class="history">

    <h2> Our Family Tree</h2>

    <p>
        Discover our roots, honour our elders,
        and connect every generation of the
        Serekin Salama family.
    </p>

    <div class="family-tree">

        <div class="generation">
<img src="salama.png" width="90px height="50px" alt="serkin salama pic" alt=">

            <div class="person elder">
                <span>👵</span>
                <h3>Grandmother</h3>
                <p>Family Elder</p>
            </div>
        </div>

        <div class="connector">│</div>

        <div class="generation">
            <div class="person parent">
                <span>👨</span>
                <h3>Father</h3>
                <p>Parent</p>
            </div>

            <div class="person parent">
                <span>👩</span>
                <h3>Mother</h3>
                <p>Parent</p>
            </div>
        </div>

        <div class="connector">│</div>

        <div class="generation">
            <div class="person child">
                <span>🧑</span>
                <h3>Children</h3>
                <p>Next Generation</p>
            </div>
        </div>

    </div>

</section>
            <p>
                A home for our family photographs,
                celebrations, reunions, and unforgettable
                moments. Photos can be added as we build
                the website.
            </p>
        </section>

        <section id="blog" class="history">
            <h2>Family News & Blog</h2>
            <p>
                Share family announcements, achievements,
                celebrations, important news, and stories
                that bring us closer together.
            </p>
        </section>

        <section id="meetings" class="meetings">
            <h2>Family Meetings</h2>
            <p>
                Keep everyone informed about family meetings,
                reunions, important discussions, and upcoming
                events.
            </p>

            <div class="cards">
                <div class="card">
                    <h3>Upcoming Meetings</h3>
                    <p>
                        Meeting dates and venues will be
                        announced here when confirmed.
                    </p>
                </div>

                <div class="card">
                    <h3>Meeting Agenda</h3>
                    <p>
                        Important topics and plans can
                        be shared with family members.
                    </p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>
            &copy; <span id="year"></span>
            Serekin Salama Family.
            One Family, One Love, One Legacy.
        </p>
    </footer>

    <script>
        document.getElementById("year").textContent =
            new Date().getFullYear();

        const links = document.querySelectorAll("nav a");

        links.forEach(link => {
            link.addEventListener("click", () => {
                links.forEach(item =>
                    item.classList.remove("active")
                );

                link.classList.add("active");
            });
        });
    </script>

</body>
</html>
</head>
<body>
    
</body>
</html>
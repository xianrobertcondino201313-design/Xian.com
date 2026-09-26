<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Xian Yaz | Socials</title>

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
    font-family:
        Inter,
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        Arial,
        sans-serif;

    background: #090909;
    color: #f5f5f5;
    min-height: 100vh;
}

/* =========================
   NAVIGATION
========================= */

.navbar {
    position: sticky;
    top: 0;
    z-index: 100;

    width: 100%;

    border-bottom: 1px solid #1d1d1d;

    background: rgba(9, 9, 9, 0.88);

    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);
}

.nav-container {
    width: min(1180px, 92%);
    height: 72px;
    margin: auto;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

.brand {
    color: #ffffff;
    text-decoration: none;

    font-size: 21px;
    font-weight: 750;
    letter-spacing: -0.7px;
}

.navigation {
    display: flex;
    gap: 30px;
}

.navigation a {
    color: #8d8d8d;
    text-decoration: none;

    font-size: 14px;
    font-weight: 500;

    transition: color 0.2s ease;
}

.navigation a:hover {
    color: #ffffff;
}

/* =========================
   HERO
========================= */

.hero {
    width: min(1180px, 92%);
    margin: auto;

    min-height: 590px;

    display: flex;
    align-items: center;
    justify-content: center;

    text-align: center;

    position: relative;
}

.hero-content {
    max-width: 800px;
}

.hero-label {
    color: #8c8c8c;

    font-size: 12px;
    font-weight: 600;

    text-transform: uppercase;
    letter-spacing: 2.5px;

    margin-bottom: 22px;
}

.hero h1 {
    font-size: clamp(54px, 9vw, 104px);

    line-height: 0.95;

    letter-spacing: -6px;

    font-weight: 800;
}

.hero-description {
    max-width: 570px;

    margin: 28px auto 0;

    color: #858585;

    font-size: 16px;
    line-height: 1.7;
}

/* =========================
   SOCIAL SECTION
========================= */

.social-section {
    width: min(1180px, 92%);
    margin: 0 auto 120px;
}

.section-header {
    margin-bottom: 30px;
}

.section-header h2 {
    font-size: 30px;
    font-weight: 700;
    letter-spacing: -1px;
}

.section-header p {
    color: #707070;
    margin-top: 8px;
    font-size: 14px;
}

/* =========================
   SOCIAL CARDS
========================= */

.social-grid {
    display: grid;

    grid-template-columns: repeat(2, 1fr);

    gap: 18px;
}

.social-card {
    position: relative;

    min-height: 220px;

    padding: 30px;

    display: flex;
    flex-direction: column;

    justify-content: space-between;

    text-decoration: none;

    color: #ffffff;

    background: #101010;

    border: 1px solid #222222;

    border-radius: 18px;

    overflow: hidden;

    transition:
        transform 0.25s ease,
        border-color 0.25s ease,
        background 0.25s ease;
}

.social-card:hover {
    transform: translateY(-5px);

    background: #141414;

    border-color: #383838;
}

.social-card-top {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

.platform-icon {
    width: 42px;
    height: 42px;

    display: block;
}

.platform-icon svg {
    width: 100%;
    height: 100%;

    fill: #ffffff;
}

.external-icon {
    width: 18px;
    height: 18px;

    opacity: 0.4;

    transition: opacity 0.2s ease;
}

.social-card:hover .external-icon {
    opacity: 0.8;
}

.external-icon svg {
    width: 100%;
    height: 100%;

    fill: none;
    stroke: #ffffff;

    stroke-width: 1.8;
}

.social-info h3 {
    font-size: 22px;
    font-weight: 650;

    letter-spacing: -0.4px;

    margin-bottom: 7px;
}

.social-handle {
    color: #777777;

    font-size: 14px;
}

.social-action {
    margin-top: 20px;

    color: #c5c5c5;

    font-size: 13px;
    font-weight: 600;
}

/* =========================
   ABOUT
========================= */

.about-section {
    width: min(1180px, 92%);

    margin: 0 auto 120px;

    padding-top: 70px;

    border-top: 1px solid #1c1c1c;
}

.about-section h2 {
    font-size: 30px;
    letter-spacing: -1px;
}

.about-section p {
    max-width: 700px;

    margin-top: 15px;

    color: #777777;

    font-size: 15px;
    line-height: 1.8;
}

/* =========================
   FOOTER
========================= */

footer {
    border-top: 1px solid #1c1c1c;

    padding: 28px 20px;

    text-align: center;

    color: #555555;

    font-size: 12px;
}

/* =========================
   MOBILE
========================= */

@media (max-width: 720px) {

    .navigation {
        display: none;
    }

    .nav-container {
        height: 64px;
    }

    .hero {
        min-height: 500px;
    }

    .hero h1 {
        letter-spacing: -4px;
    }

    .social-grid {
        grid-template-columns: 1fr;
    }

    .social-card {
        min-height: 200px;
    }
}
</style>
</head>


<body>

<!-- =========================
     NAVIGATION
========================= -->

<header class="navbar">

    <div class="nav-container">

        <a href="#" class="brand">
            Xian Yaz
        </a>

        <nav class="navigation">

            <a href="#home">
                Home
            </a>

            <a href="#socials">
                Socials
            </a>

            <a href="#about">
                About
            </a>

        </nav>

    </div>

</header>


<main>

<!-- =========================
     HERO
========================= -->

<section class="hero" id="home">

    <div class="hero-content">

        <div class="hero-label">
            Official Social Hub
        </div>

        <h1>
            Xian Yaz
        </h1>

        <p class="hero-description">
            Find the official social platforms for Xian Yaz.
            Select a platform below to visit the corresponding account.
        </p>

    </div>

</section>


<!-- =========================
     SOCIALS
========================= -->

<section class="social-section" id="socials">

    <div class="section-header">

        <h2>
            Social platforms
        </h2>

        <p>
            Official account links
        </p>

    </div>


    <div class="social-grid">


        <!-- X -->

        <a
            class="social-card"
            href="https://x.com/xy_xianyaz"
            target="_blank"
            rel="noopener noreferrer"
        >

            <div class="social-card-top">

                <div class="platform-icon">

                    <!-- Official X-style SVG mark -->

                    <svg
                        viewBox="0 0 24 24"
                        aria-hidden="true"
                    >

                        <path d="
                        M18.244 2.25h3.308l-7.227 8.26
                        8.502 11.24h-6.657l-5.214-6.817
                        -5.964 6.817H1.684l7.73-8.835
                        L1.254 2.25H8.08l4.713 6.231
                        L18.244 2.25Zm-1.161 17.52h1.833
                        L7.084 4.126H5.117L17.083 19.77Z">
                        </path>

                    </svg>

                </div>


                <div class="external-icon">

                    <svg viewBox="0 0 24 24">

                        <path d="
                        M14 5h5v5
                        M19 5l-9 9
                        M19 13v5a1 1 0 0 1-1 1H6
                        a1 1 0 0 1-1-1V6
                        a1 1 0 0 1 1-1h5
                        " />

                    </svg>

                </div>

            </div>


            <div class="social-info">

                <h3>
                    X
                </h3>

                <div class="social-handle">
                    @xy_xianyaz
                </div>

                <div class="social-action">
                    Visit profile
                </div>

            </div>

        </a>


        <!-- TIKTOK -->

        <a
            class="social-card"
            href="https://www.tiktok.com/@xy_xianyaz"
            target="_blank"
            rel="noopener noreferrer"
        >

            <div class="social-card-top">

                <div class="platform-icon">

                    <!-- TikTok-style musical mark -->

                    <svg
                        viewBox="0 0 24 24"
                        aria-hidden="true"
                    >

                        <path d="
                        M16.6 5.82A4.17 4.17 0 0 1
                        14.32 3.2h-3.3v11.18a2.53
                        2.53 0 1 1-1.74-2.4V8.64
                        a5.9 5.9 0 1 0 5.04 5.74V8.7
                        a7.48 7.48 0 0 0 4.1 1.22V6.64
                        a4.12 4.12 0 0 1-1.82-.82Z">
                        </path>

                    </svg>

                </div>


                <div class="external-icon">

                    <svg viewBox="0 0 24 24">

                        <path d="
                        M14 5h5v5
                        M19 5l-9 9
                        M19 13v5a1 1 0 0 1-1 1H6
                        a1 1 0 0 1-1-1V6
                        a1 1 0 0 1 1-1h5
                        " />

                    </svg>

                </div>

            </div>


            <div class="social-info">

                <h3>
                    TikTok
                </h3>

                <div class="social-handle">
                    @xy_xianyaz
                </div>

                <div class="social-action">
                    Visit profile
                </div>

            </div>

        </a>


        <!-- FACEBOOK -->

        <a
            class="social-card"
            href="https://www.facebook.com/XianCondino"
            target="_blank"
            rel="noopener noreferrer"
        >

            <div class="social-card-top">

                <div class="platform-icon">

                    <!-- Facebook-style SVG -->

                    <svg
                        viewBox="0 0 24 24"
                        aria-hidden="true"
                    >

                        <path d="
                        M13.5 21v-8h2.7l.4-3h-3.1V8.1
                        c0-.87.24-1.46 1.5-1.46h1.7V4
                        c-.3-.04-1.33-.13-2.53-.13
                        -2.5 0-4.2 1.53-4.2 4.34V10H7.2v3h2.8v8h3.5Z">
                        </path>

                    </svg>

                </div>


                <div class="external-icon">

                    <svg viewBox="0 0 24 24">

                        <path d="
                        M14 5h5v5
                        M19 5l-9 9
                        M19 13v5a1 1 0 0 1-1 1H6
                        a1 1 0 0 1-1-1V6
                        a1 1 0 0 1 1-1h5
                        " />

                    </svg>

                </div>

            </div>


            <div class="social-info">

                <h3>
                    Facebook
                </h3>

                <div class="social-handle">
                    Xian Condino
                </div>

                <div class="social-action">
                    Visit profile
                </div>

            </div>

        </a>


        <!-- DISCORD -->

        <a
            class="social-card"
            href="https://discord.com/users/xy_xianyaz"
            target="_blank"
            rel="noopener noreferrer"
        >

            <div class="social-card-top">

                <div class="platform-icon">

                    <!-- Discord-style SVG -->

                    <svg
                        viewBox="0 0 24 24"
                        aria-hidden="true"
                    >

                        <path d="
                        M19.54 5.24A16.9 16.9 0 0 0
                        15.38 4l-.52 1.06a15.1 15.1 0 0 0
                        -5.72 0L8.62 4a16.9 16.9 0 0 0
                        -4.16 1.24C1.82 9.12 1.1 12.92
                        1.46 16.67a16.8 16.8 0 0 0
                        5.12 2.6l1.24-1.68c-.68-.25
                        -1.33-.56-1.95-.93l.48-.36
                        c3.77 1.77 8.1 1.77 11.83 0l.48.36
                        c-.62.37-1.27.68-1.95.93l1.24 1.68
                        a16.8 16.8 0 0 0 5.12-2.6
                        c.42-4.35-.72-8.11-3.53-11.43ZM8.32
                        14.83c-1.16 0-2.1-1.06-2.1-2.37
                        0-1.31.93-2.37 2.1-2.37
                        1.18 0 2.11 1.06 2.1 2.37
                        0 1.31-.93 2.37-2.1 2.37Zm7.36
                        0c-1.16 0-2.1-1.06-2.1-2.37
                        0-1.31.93-2.37 2.1-2.37
                        1.18 0 2.11 1.06 2.1 2.37
                        0 1.31-.93 2.37-2.1 2.37Z">
                        </path>

                    </svg>

                </div>


                <div class="external-icon">

                    <svg viewBox="0 0 24 24">

                        <path d="
                        M14 5h5v5
                        M19 5l-9 9
                        M19 13v5a1 1 0 0 1-1 1H6
                        a1 1 0 0 1-1-1V6
                        a1 1 0 0 1 1-1h5
                        " />

                    </svg>

                </div>

            </div>


            <div class="social-info">

                <h3>
                    Discord
                </h3>

                <div class="social-handle">
                    xy_xianyaz
                </div>

                <div class="social-action">
                    Open Discord
                </div>

            </div>

        </a>

    </div>

</section>


<!-- =========================
     ABOUT
========================= -->

<section class="about-section" id="about">

    <h2>
        About
    </h2>

    <p>
        Official social links for Xian Yaz.
        This page only provides direct links to the
        social accounts listed above.
    </p>

</section>

</main>


<!-- =========================
     FOOTER
========================= -->

<footer>

    © 2026 Xian Yaz

</footer>


</body>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corsair Game Jams</title>
    <style>
       

        html {
            scroll-behavior: smooth;
        }


        body {
            background-color: #0b0338;
            color: white;
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            
            margin: 0;
            font-size: 20px;
            line-height: 2;
        }

        a {
            color: white;
        }

        a:hover,
        a:focus-visible {
            text-decoration: underline;
            text-underline-offset: 3px;
        }


        img {
            display: block;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .wrap {
            max-width: 1180px;
            margin: 0 auto;
            padding: 15px;
        }

        .topbar{
            position: sticky;
            top: 0;
            right: 0;
            left: 0;
            z-index: 100;
            display: flex;
            justify-content: flex-end;   /* pushes contents to the right */
            align-items: center;
            background: rgba(7, 2, 38, .85);
            border-bottom: 1px solid white;
            color: white;
            font-weight: 500;
            height: 56px;
            padding: 0 24px;
            gap: 14px;
            
        }
        
        .topbar img{
            
            width: 5%;
            height: auto;
            
        }

        /* ---------- Title ---------- */
        .hero {
            text-align: center;
            padding-bottom: 15px;
            margin-bottom: 15px;
            /*border: 2px solid white;*/
            color: white;
            background-image: url("https://i.imgur.com/MGvVr8V.gif");
            background-size: cover;
            
        }


        .hero p{
            margin-top: -64px;
            
        }



        /* ---------- Image rows ---------- */

        .rowitem {
            transition: transform .2s;

        }

        .rowitem:hover {
            transform: scale(1.5);

        }

        .row {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: (12px, 2vw, 24px);
            padding: (32px, 5vw, 56px) 0;
        }

        .row figure {
            margin: 20px;
            background: transparent;
            aspect-ratio: 4/3;
            
            /*overflow: auto;*/
        }


        /* Second row uses a wider crop so the two rows don't feel like a repeat */
        .row.wide figure {
           
        }

        .row.wide {
            overflow: hidden;
            padding: 50px;
        }
        /* ---------- Separator ---------- */
        .rule {
            border: 0;
            height: 2px;
            background: white;
            margin: 0;
        }

        /* ---------- Text + photo ---------- */
        .about {
           
            padding: 50px;
            margin: 20px;
            
            
            display: grid;
            grid-template-columns: 1.1fr 1fr;
            gap: clamp(32px, 6vw, 96px);
            align-items: center;
            padding: clamp(56px, 8vw, 112px) 0;
            border-top: 2px solid white;
           /* border-bottom: 2px solid white;*/
            
        }

        

        .about figure {
            margin: 0;
            aspect-ratio: auto;
            overflow: hidden;
        }

        /* ---------- Footer links ---------- */
        footer {
            
            padding: 40px 0 56px;
            display: flex;
            color: white;
            background: rgba(7, 2, 38, .85);
        }

        footer .wrap { 
         display: flex;
          justify-content: space-between;
           align-items: baseline;
           gap: 24px;
         flex-wrap: wrap; 
            
            
        }

        footer nav {
            display: flex;
            gap: 28px;
        }

        footer nav a {
            font-weight: 500;
            font-size: 1.05rem;
        }


        /* ---------- Phones ---------- */
        @media (max-width: 720px) {
            .row {
                grid-template-columns: 1fr;
            }

            .about {
                grid-template-columns: 1fr;
            }

            .about figure {
                order: -1;
                aspect-ratio: 4 / 3;
            }
        }
    </style>
</head>

<body>



        <header class="topbar">
            <span>MSB 301, Thursdays 4-5pm</span>
            <img src="https://i.imgur.com/ZrYVBvN.png" alt="Corsair Council photo">
        </header>

    <div class="wrap">

        <header class="hero">
            <img src="https://i.imgur.com/ZrYVBvN.png" style="width: 40%; height: auto; display: block; margin: 0 auto;" alt="Corsair Council photo">
            <p>Game Development Club <br /> Room MSB 301, thursday 4-5pm </p>
        </header>


  <hr class = "rule">

    <h1>Our game jam winners</h1>

        <hr class = "rule">
        
        
        <section class="row">
            <figure>
                <a href="https://itch.io/jam/corsair-game-jam-spring-2025/rate/3579185" target="_blank" rel="noopener">
                    <img class="rowitem" src="https://i.imgur.com/T80a0Wg.png" alt="Holey Moley" style="width:100%" title="Holey Moley. spring 2025 winner"></a>
                   
                
            </figure>
            <figure>

                <a href="https://itch.io/jam/corsair-game-jam-fall-2025/rate/4081788" target="_blank" rel="noopener">
                    <img class="rowitem" src="https://img.itch.zone/aW1nLzI0MzM5MTkyLnBuZw==/315x250%23c/dxAOLc.png" alt="Menace The Dennis" style="width:100%" title="Menace The Dennis. fall 2025 winner"></a>
                
            </figure>
            <figure>

                <a href="https://itch.io/jam/corsair-game-jam-spring-2026/rate/4537357" target="_blank" rel="noopener">
                    <img class="rowitem" src="https://img.itch.zone/aW1nLzI3MzU5MzM2LnBuZw==/315x250%23c/lGCxr7.png" alt="Pedal To The Metal" style="width:100%" title="Pedal To The Metal. spring 2026 winner"> </a>
               
            </figure>
        </section>

        <hr class="rule">
        <h1> Check out all our previous game jams submissions</h1>
        <hr class="rule">
        <!-- Row 2 -->
        <section class="row wide">
            <figure>
               <a href = "https://itch.io/jam/corsair-game-jam-spring-2025" target="_blank">
            <img class="rowitem" src = "https://i.imgur.com/drA9RBB.png" style="width: 60%; height: auto;" title = "Spring 2025 submissions">
             <figcaption>Spring 2025 submissions</figcaption></a>
            </figure>
            <figure>
                <a href = "https://itch.io/jam/corsair-game-jam-fall-2025" target="_blank">
                <img class="rowitem" src = "https://i.imgur.com/drA9RBB.png" style="width: 60%; height: auto;" title = "Fall 2025 submissions">
                <figcaption>Fall 2025 submissions</figcaption></a>
            </figure>
            <figure>
                
                <a href = "https://itch.io/jam/corsair-game-jam-spring-2026" target="_blank">
                <img class="rowitem" src = "https://i.imgur.com/drA9RBB.png" style="width: 60%; height: auto;" title = "Spring 2026 submissions">
                <figcaption>Spring 2026 submissions</figcaption></a>
            </figure>
        </section>

        <!-- Writing on the left, photo on the right -->
        <section class="about">
            <div>
                <h2>About us:</h2>
                <p>Promoting Game Development, creating opportunities for students to explore game engines and develop skills in game design, programming, storytelling, art, and sound design. We also host game jams where students form teams and build original games within a limited time, along with community events, hands-on workshops, and talks from students and industry professionals.</p>
                <h3>No experience needed! Let's all learn together.</h3>
            </div>
            <figure>
                <img src="https://media.licdn.com/dms/image/v2/D5622AQEtG5eJ12arOA/feedshare-image-high-res/B56aD._sMdJMAU-/0/1790984504911?e=1792627200&v=beta&t=AJ9Evy0fnPI5CtnXHGOPi0h55cMYNWi8Gx2nZwCyBaE" width="80%" alt="Corsair Council photo">
            </figure>
        </section>

<hr class="rule">
    <h2>Feel free to follow us on our socials!</h2>
        
        <hr class="rule">
        
        </div>
        <footer>
            <section class="wrap">
            <nav>
                <a href="https://www.instagram.com/corsairgamejams.smc/" target="_blank" rel="noopener"><h2>Instagram</h2></a>
                <a href="https://www.linkedin.com/company/corsair-game-jams" target="_blank" rel="noopener"><h2>Linkedin</h2></a>
                <a href="https://discord.gg/YEZVeW7Cw" target="_blank" rel="noopener"><h2>Discord</h2></a>
            </nav>
            <small>&copy; 2026 Corsair Game Jams</small>
        </section>
        </footer>
        


</body>

</html>





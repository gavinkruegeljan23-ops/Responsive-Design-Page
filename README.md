<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urban City Living - Responsive Design</title>
    <style>
        /* Base Styles (Desktop and Larger Screens) */
        body {
            font-family: Constantia, Georgia, serif;
            max-width: 1024px;
            width: 100%;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
            box-sizing: border-box;
            font-size: 16px;
            line-height: 1.6;
            color: #333333;
        }
        /* Neon Glow Heading */
        h1 {
            text-align: center;
            font-size: 42pt;
            margin-bottom: 20px;
            color: #2c3e50;
            text-shadow:
                0 0 6px #E033FF,
                0 0 12px #E033FF,
                0 0 24px #E033FF;
        }
        h2 {
            color: #1a252f;
            margin-top: 30px;
        }
        /* Page Container and Area Layout with max-width */
        .page-container {
            max-width: 100%;
            margin: 0 auto;
            background: #ffffff;
            padding: 40px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            box-sizing: border-box;
        }
        .content-area {
            max-width: 800px;
            margin: 0 auto;
        }
        /* Responsive Images */
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 25px auto;
            border-radius: 6px;
        }
        p {
            margin-bottom: 20px;
        }
        /* Smartphone Media Query (<= 750px) */
        @media screen and (max-width: 750px) {
            body {
                font-size: 18px; /* Larger text for mobile readability */
                line-height: 1.8; /* Increased line leading */
                padding: 10px;
            }
            h1 {
                font-size: 28pt; /* Scales down title so it doesn't break on small screens */
            }
            .page-container {
                padding: 20px 15px;
                box-shadow: none;
            }
            img {
                width: 100%; /* Full-width images on smartphones */
            }
        }
    </style>
</head>
<body>
    <div class="page-container">
        <div class="content-area">
            <h1>Urban City Living</h1>
            <p>Urban city living is a dynamic dance of relentless energy, architectural grandeur, and cultural convergence. From the dizzying heights of glass-and-steel skyscrapers to the quiet, hidden courtyards tucked behind historic brownstones, the metropolis pulses with a life of its own.</p>
            <img src="IMG_6247.jpeg" alt="Urban Skyline and City Architecture">
            <h2>The Vertical Rhythm</h2>
            <p>Life in the modern metropolis forces a shift in perspective. Space becomes a premium, teaching residents the art of minimalist efficiency. Vertical architecture transforms how we move, work, and interact, stacking coffee shops, loft apartments, and rooftop gardens into a compact, interconnected vertical grid.</p>
            <h2>Pavement and Paradox</h2>
            <p>Walking the city streets reveals constant paradoxes: the roar of subway grates beneath feet sharing space with the quiet rustle of pocket parks; the blur of high-speed commuters passing slow-moving street musicians. It is an environment that tests our adaptability—and rewards it with endless discovery.</p>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TruConnect - Elevating Education in Metro Cities</title>
</head>
<body>
    <header>
        <h1>Welcome to TruConnect</h1>
        <p>Elevating Education in Northeast Metro Cities</p>
    </header>

    <!-- Insert your SVG here with custom CSS animations -->
    <section>
        <svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
            <foreignObject width="100%" height="100%">
                <div xmlns="http://www.w3.org/1999/xhtml">
                    <style>
                        @keyframes hi {
                            0% { transform: rotate(0.0deg); }
                            10% { transform: rotate(14.0deg); }
                            20% { transform: rotate(-8.0deg); }
                            30% { transform: rotate(14.0deg); }
                            40% { transform: rotate(-4.0deg); }
                            50% { transform: rotate(10.0deg); }
                            60% { transform: rotate(0.0deg); }
                            100% { transform: rotate(0.0deg); }
                        }

                        @keyframes gradient {
                            0% { background-position: 0% 50%; }
                            50% { background-position: 100% 50%; }
                            100% { background-position: 0% 50%; }
                        }

                        .container {
                            --color-main: #ee7752;
                            --color-primary: #e73c7e;
                            --color-secondary: #23a6d5;
                            --color-tertiary: #23d5ab;

                            background: linear-gradient(-45deg, var(--color-main), var(--color-primary), var(--color-secondary), var(--color-tertiary));
                            background-size: 400% 400%;
                            animation: gradient 15s ease infinite;

                            width: 100%;
                            height: 300px;

                            display: flex;
                            justify-content: center;
                            align-items: center;
                            color: white;

                            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
                        }

                        .hi {
                            animation: hi 1.5s linear -0.5s infinite;
                            display: inline-block;
                            transform-origin: 70% 70%;
                        }

                        @media (prefers-color-scheme: light) {
                            .container {
                                --color-main: #F15BB5;
                                --color-primary: #24b0ef;
                                --color-secondary: #4526f6;
                                --color-tertiary: #f6f645;
                            }
                        }

                        @media (prefers-reduced-motion) {
                            .container {
                                animation: none;
                            }

                            .hi {
                                animation: none;
                            }
                        }
                    </style>

                    <div class="container">
                        <h1>Welcome to TruConnect! <div class="hi">👋</div></h1>
                    </div>
                </div>
            </foreignObject>
        </svg>
    </section>

    <section>
        <h2>For Students:</h2>
        <ul>
            <li><strong>Personalized Dashboard:</strong> Students can easily track their courses, assignments, and explore available clubs in one convenient location.</li>
            <li><strong>AI Career & Academic Guidance:</strong> The “Ask AI” feature provides personalized academic and career recommendations based on student interests and goals.</li>
            <li><strong>Clubs & Extracurriculars:</strong> Students can view, join, and track clubs and events, reducing the struggle of finding relevant activities.</li>
        </ul>
    </section>

    <section>
        <h2>For Parents:</h2>
        <ul>
            <li><strong>Engagement & Support:</strong> Parents can view their child's performance, upcoming events, and key announcements, helping them stay informed and actively support their child’s success.</li>
        </ul>
    </section>

    <section>
        <h2>For Teachers:</h2>
        <ul>
            <li><strong>Class Management:</strong> Teachers can monitor class progress, track student stats, and manage courses, all in one integrated dashboard.</li>
        </ul>
    </section>

    <footer>
        <p>© 2024 TruConnect. All rights reserved.</p>
    </footer>
</body>
</html>

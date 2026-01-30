<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Sphere Commerce Company | Official Portal</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-dark: #0a192f;
            --bg-card: #112240;
            --accent: #64ffda;
            --text-light: #ccd6f6;
            --text-dim: #8892b0;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            margin: 0;
            padding: 0;
            line-height: 1.8;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        header { margin-bottom: 60px; }
        h1 { font-family: 'Montserrat', sans-serif; font-size: 2.8rem; color: var(--accent); margin: 0; text-transform: uppercase; }
        .mentor-subtitle { font-family: 'Montserrat', sans-serif; font-size: 1.5rem; color: var(--text-dim); font-weight: 700; letter-spacing: 6px; margin-top: 10px; }

        /* Mission & Vision Section */
        .mv-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; margin-bottom: 70px; }
        .mv-card { border: 1px solid var(--accent); padding: 40px; border-radius: 15px; background: rgba(100, 255, 218, 0.05); }
        .mv-card h2 { font-family: 'Montserrat', sans-serif; color: #fff; text-transform: uppercase; font-size: 1.6rem; margin-bottom: 20px; }

        /* Service Grid Section */
        .section-title { font-family: 'Montserrat', sans-serif; font-size: 2rem; color: #fff; margin-bottom: 40px; border-bottom: 2px solid var(--accent); display: inline-block; padding-bottom: 10px; }
        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 80px;
        }

        .service-card {
            background: var(--bg-card);
            padding: 35px;
            border-radius: 16px;
            border: 1px solid rgba(100, 255, 218, 0.1);
            transition: 0.4s ease;
        }

        .service-card:hover { transform: translateY(-10px); border-color: var(--accent); box-shadow: 0 20px 40px rgba(2, 12, 27, 0.8); }
        .service-card b { font-family: 'Montserrat', sans-serif; display: block; margin-bottom: 12px; font-size: 1.3rem; }

        /* Distinct Colors for Each Service */
        .c1 { color: #ff6b6b; } .c2 { color: #4facfe; } .c3 { color: #ffd93d; } .c4 { color: #6bffbc; }
        .c5 { color: #ff9ff3; } .c6 { color: #a29bfe; } .c7 { color: #fab1a0; } .c8 { color: #00d2ff; }
        .c9 { color: #ff9f43; } .c10 { color: #54a0ff; } .c11 { color: #5f27cd; } .c12 { color: #ff6b6b; }
        .c13 { color: #1dd1a1; } .c14 { color: #feca57; }

        /* Activation Box */
        .activation-box {
            background: linear-gradient(145deg, #112240, #0a192f);
            border: 2px solid var(--accent);
            padding: 60px 40px;
            border-radius: 24px;
            max-width: 850px;
            margin: 0 auto;
        }

        .price { font-size: 3.5rem; font-weight: 800; color: #fff; margin: 20px 0; }
        .phone { font-size: 2.5rem; color: var(--accent); font-weight: 700; letter-spacing: 2px; display: block; margin: 25px 0; background

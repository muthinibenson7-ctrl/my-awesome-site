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
            --accent-teal: #64ffda;
            --text-light: #ccd6f6;
            --text-gray: #8892b0;
            --white: #ffffff;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            margin: 0;
            padding: 0;
            line-height: 1.8;
        }

        .wrapper {
            max-width: 1100px;
            margin: 0 auto;
            padding: 80px 24px;
            text-align: center;
        }

        /* Header Section */
        header { margin-bottom: 70px; }
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3rem;
            color: var(--accent-teal);
            margin: 0;
            text-transform: uppercase;
        }
        .mentor-subtitle {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.6rem;
            color: var(--text-gray);
            font-weight: 700;
            letter-spacing: 6px;
            margin-top: 10px;
        }

        /* Mission & Vision Section */
        .mv-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 80px;
        }
        .mv-card {
            background: rgba(100, 255, 218, 0.05);
            border: 1px solid var(--accent-teal);
            padding: 40px;
            border-radius: 15px;
        }
        .mv-card h2 {
            font-family: 'Montserrat', sans-serif;
            color: var(--white);
            margin-top: 0;
            text-transform: uppercase;
            font-size: 1.5rem;
        }

        /* Business Modules Section */
        .section-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 2rem;
            margin-bottom: 50px;
            color: var(--white);
            position: relative;
            display: inline-block;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background: var(--accent-teal);
            margin: 15px auto 0;
        }

        .business-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            margin-bottom: 80px;
        }
        .biz-card {
            background: var(--bg-card);
            padding: 40px;
            border-radius: 16px;
            transition: all 0.3s ease;
            border: 1px solid rgba(100, 255, 218, 0.1);
        }
        .biz-card:hover {
            transform: translateY(-10px);
            border-color: var(--accent-teal);
            box-shadow: 0 20px 40px rgba(2, 12, 27, 0.8);
        }
        .biz-card h3 {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.4rem;
            margin-bottom: 15px;
            font-weight: 700;
        }

        /* Business Colors */
        .academic { color: #ff6b6b; }
        .ecommerce { color: #4facfe; }
        .marketing { color: #ffd93d; }
        .tutoring { color: #6bffbc; }
        .content { color: #ff9ff3; }
        .virtual { color: #a29bfe; }
        .webdev { color: #fab1a0; }

        /* Activation Portal */
        .activation-portal {
            background: linear-gradient(145deg, #112240, #0a192f);
            padding: 60px 40px;
            border-radius: 24px;
            border: 1px solid var(--accent-teal);
            max-width: 800px;
            margin: 0 auto;
        }
        .price-display {
            font-size: 3rem;
            font-weight: 800;
            color: var(--white);
            margin: 20px 0;
            display: block;
        }
        .phone-number {
            font-size: 2.2rem;
            font-weight: 700;
            color: var(--accent-teal);
            background: rgba(100, 255, 218, 0.1);
            padding: 10px 20px;
            border-radius: 8px;
            display: inline-block;
            margin-bottom: 25px;
            letter-spacing: 2px;
        }
        .cta-button {
            background-color: var(--accent-teal);
            color: var(--bg-dark);
            border: none;
            padding: 20px 50px;
            font-size: 1.1rem;
            font-weight: 700;
            border-radius: 50px;
            cursor: pointer;
            transition: 0.4s;
            text-transform: uppercase;
        }
        .cta-button:hover { transform: scale(1.05); }

        footer { margin-top: 100px; color: var(--text-gray); font-size: 0.9rem; }
    </style>
</head>
<body>

<div class="wrapper">
    <header>
        <h1>Online Sphere Commerce Company</h1>
        <div class="mentor-subtitle">MENTOR BENSON</div>
    </header>

    <div class="mv-section">
        <div class="mv-card">
            <h2>Our Mission</h2>
            <p>To empower the digital generation in Kenya by providing high-performance e-commerce tools, professional academic support, and innovative learning systems that simplify wealth creation in the digital economy.</p>
        </div>
        <div class="mv-card">
            <h2>Our Vision</h2>
            <p>To be the leading multi-service digital ecosystem in East Africa, recognized for bridging the gap between digital skills and financial independence through automated, user-centric technology.</p>
        </div>
    </div>

    <h2 class="section-title">Professional Business Modules</h2>

    <div class="business-grid">
        <div class="biz-card">
            <h3 class="academic">1. Academic Writing Services</h3>
            <p>We offer professional research assistance and academic consulting. Our experts help students and professionals manage complex projects with quality, plagiarism-free results that meet global standards.</p>
        </div>

        <div class="biz-card">
            <h3 class="ecommerce">2. E-Commerce Retail Hub</h3>
            <p>A full-scale digital marketplace module. Sell physical products or digital downloads globally, with M-Pesa, PayPal, and card payments fully integrated for seamless local and international transactions.</p>
        </div>

        <div class="biz-card">
            <h3 class="marketing">3. Digital Marketing Agency</h3>
            <p>We help businesses dominate the digital space. Our services include SEO, high-conversion Social Media management, and professional ad campaigns designed to maximize reach and revenue.</p>
        </div>

        <div class="biz-card">
            <h3 class="tutoring">4. Online Tutoring & LMS</h3>
            <p>A specialized Learning Management System for educators. Host your own video courses, manage students, and track progress with our automated certification and enrollment platform.</p>
        </div>

        <div class="biz-card">
            <h3 class="content">5. Content Creation Hub</h3>
            <p>We manage professional Blogs, Vlogs, and Podcasts. This module focuses on content monetization through brand partnerships and affiliate marketing tailored for the African audience.</p>
        </div>

        <div class="biz-card">
            <h3 class="virtual">6. Virtual Assistance Services</h3>
            <p>Remote administrative and technical support for global executives. We provide trained virtual assistants to handle scheduling, data management, and customer support for international firms.</p>
        </div>

        <div class="biz-card">
            <h3 class="webdev">7. Web Design & Hosting</h3>
            <p>Establishing your digital identity with world-class websites. We build mobile-responsive, SEO-optimized sites and provide high-speed cloud hosting to ensure your business is always online.</p>
        </div>
    </div>

    <div class="activation-portal">
        <h2>Instant System Activation</h2>
        <p>To access your personal dashboard and begin managing your business, a one-time activation fee is required to verify your profile.</p>
        
        <span class="price-display">KSh 500</span>

        <p style="margin-bottom: 25px;"><b>✓ AUTOMATION NOTICE:</b> Our system is fully integrated. Once your payment of <b>KSh 500</b> is confirmed via M-Pesa, the website will <b>automatically unlock</b> your account. You will receive instant access to all professional modules.</p>

        <p>Send payment to official number:</p>
        <div class="phone-number">0741723223</div>
        <br>
        <button class="cta-button" onclick="copyAndDirect()">Copy Number & Activate</button>

        <p style="margin-top: 25px; font-size: 0.85rem; color: var(--text-gray);">
            🔒 SSL Encrypted | ⚡ Instant Setup | ✅ Verified Portal
        </p>
    </div>

    <footer>
        &copy; 2026 Online Sphere Commerce Company. <br>
        Partnered with Qaribuhub Solutions Ltd.
    </footer>
</div>

<script>
    function copyAndDirect() {
        const number = "0741723223";
        navigator.clipboard.writeText(number).then(() => {
            alert("M-Pesa Number " + number + " copied to clipboard! \n\nPlease pay KSh 500. Your account will open automatically upon transaction confirmation.");
        });
    }
</script>

</body>
</html>v

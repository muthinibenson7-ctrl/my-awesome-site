<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Sphere Commerce Company</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0a192f; /* Professional Dark Blue Background */
            color: #e6f1ff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
            text-align: center; /* Centers all content */
        }
        h1 {
            color: #64ffda; /* Teal accent color */
            font-size: 2.5rem;
            margin-bottom: 5px;
            text-transform: uppercase;
        }
        .subtitle {
            font-size: 1.2rem;
            color: #8892b0;
            margin-bottom: 40px;
            letter-spacing: 2px;
        }
        .section {
            background: #112240;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px -15px rgba(2,12,27,0.7);
        }
        h2 {
            color: #ccd6f6;
            border-bottom: 2px solid #64ffda;
            display: inline-block;
            padding-bottom: 5px;
            margin-bottom: 20px;
        }
        .payment-box {
            background: #1d3557;
            border: 1px dashed #64ffda;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
        }
        .phone-number {
            font-size: 1.5rem;
            color: #64ffda;
            font-weight: bold;
            display: block;
            margin: 10px 0;
            cursor: pointer;
            text-decoration: underline;
        }
        .btn-copy {
            background: #64ffda;
            color: #0a192f;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn-copy:hover {
            background: #45c7a9;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Online Sphere Commerce Company</h1>
        <div class="subtitle">MENTOR BENSON</div>
    </header>

    <div class="section">
        <h2>Our Digital Services</h2>
        [span_1](start_span)<p>Providing comprehensive solutions in E-commerce, Online Courses (LMS), and Professional Consulting[span_1](end_span).</p>
        <ul style="list-style: none; padding: 0;">
            [span_2](start_span)<li>✓ E-Commerce Module[span_2](end_span)</li>
            [span_3](start_span)<li>✓ Learning Management System[span_3](end_span)</li>
            [span_4](start_span)<li>✓ Consulting & Booking[span_4](end_span)</li>
            [span_5](start_span)<li>✓ Membership & Subscriptions[span_5](end_span)</li>
        </ul>
    </div>

    <div class="section">
        <h2>Secure Payment Method</h2>
        [span_6](start_span)<p>Please use the official M-Pesa line below for all service transactions and booking fees[span_6](end_span).</p>
        
        <div class="payment-box">
            <p>Official Payment Number:</p>
            <span class="phone-number" id="phone">0741723223</span>
            <button class="btn-copy" onclick="copyNumber()">Click to Copy Number</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Online Sphere Commerce Company. All Rights Reserved.</p>
    </footer>
</div>

<script>
    function copyNumber() {
        const num = "0741723223";
        navigator.clipboard.writeText(num);
        alert("Phone number copied: " + num);
    }
</script>

</body>
</html>

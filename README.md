
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>soul coffee</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for social media icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5; /* Light gray background */
        }
        .social-button {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 1rem 1.5rem;
            margin-bottom: 1rem;
            border-radius: 0.75rem; /* Rounded corners */
            font-weight: 600;
            color: white;
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .social-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
        .social-button i {
            margin-right: 0.75rem;
            font-size: 1.5rem;
        }
        .facebook { background-color: #3b5998; }
        .instagram {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
        }
        .telegram { background-color: #0088cc; }
        .whatsapp { background-color: #25d366; }
        .linkedin { background-color: #0a66c2; }
        .tiktok { background-color: #000000; }
        .website { background-color: #1a202c; } /* Dark gray for general website/contact */

        /* Responsive adjustments */
        @media (min-width: 640px) { /* Small screens and up */
            .max-w-md {
                max-width: 28rem; /* Equivalent to md:max-w-md */
            }
        }
        @media (min-width: 768px) { /* Medium screens and up */
            .md\:p-8 {
                padding: 2rem;
            }
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4">
    <div class="bg-white p-6 md:p-8 rounded-xl shadow-lg w-full max-w-sm sm:max-w-md text-center">
        <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1750760962/440939712_464354966118104_4873437149574594081_n_tfqmxb.jpg" alt="Company Logo" class="mx-auto w-32 h-32 rounded-full shadow-md">
        <h1 class="text-3xl font-bold text-gray-800 mb-2">soul coffee</h1>
        <p class="text-gray-600 mb-8">Find all our platforms in one place.</p>

        <a href="https://www.facebook.com/SoulCoffeeCambodia" target="_blank" class="social-button facebook">
            <i class="fab fa-facebook-f"></i> Follow on Facebook
        </a>
        <a href="https://www.instagram.com/soulcoffeecambodia/" target="_blank" class="social-button instagram">
            <i class="fab fa-instagram"></i> Follow on Instagram
        </a>
        <a href="https://t.me/YOUR_TELEGRAM_CHANNEL_OR_GROUP" target="_blank" class="social-button telegram">
            <i class="fab fa-telegram-plane"></i> Join our Telegram
        </a>
    
        <a href="https://www.tiktok.com/@soulcoffeecambodia" target="_blank" class="social-button tiktok">
            <i class="fab fa-tiktok"></i> Follow on TikTok
        </a>
       

        <p class="text-sm text-gray-500 mt-8">Thank you for connecting!</p>
    </div>
</body>

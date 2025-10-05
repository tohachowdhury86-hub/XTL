<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toha Ahammad | Cyber Security Expert</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Roboto', sans-serif; }
        body { background: #f4f4f4; color: #333; line-height:1.6; }
        a { text-decoration: none; color: inherit; }
        header { position:fixed; width:100%; background:#0b3d91; color:#fff; padding:15px 0; z-index:1000; }
        header h1 { text-align:center; font-size:2em; }
        nav { text-align:center; margin-top:10px; }
        nav a { margin:0 15px; color:#fff; font-weight:bold; transition:0.3s; }
        nav a:hover { color:#ffd700; }
        section { padding:100px 20px 60px 20px; max-width:1000px; margin:auto; }
        .hero { background:url('https://images.unsplash.com/photo-1581092333867-89a2b57b4b08?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover; height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center; color:#fff; text-align:center; }
        .hero h2 { font-size:3em; margin-bottom:20px; text-shadow: 2px 2px 8px rgba(0,0,0,0.7); }
        .hero p { font-size:1.3em; margin-bottom:30px; text-shadow: 1px 1px 6px rgba(0,0,0,0.7); }
        .hero button { padding:15px 30px; font-size:1em; border:none; border-radius:5px; background:#ffd700; color:#0b3d91; cursor:pointer; transition:0.3s; }
        .hero button:hover { background:#e6c200; }
        .about, .services, .contact { background:#fff; margin-bottom:20px; border-radius:10px; padding:40px; box-shadow:0 0 15px rgba(0,0,0,0.1); }
        h2 { color:#0b3d91; margin-bottom:20px; text-align:center; }
        ul { list-style:disc inside; }
        .contact form { display:flex; flex-direction:column; }
        .contact input, .contact textarea { margin-bottom:15px; padding:10px; border:1px solid #ccc; border-radius:5px; }
        .contact button { padding:12px; border:none; background:#0b3d91; color:#fff; border-radius:5px; cursor:pointer; transition:0.3s; }
        .contact button:hover { background:#063170; }
        footer { text-align:center; padding:20px; background:#222; color:#fff; }
        .socials { text-align:center; margin-top:15px; }
        .socials a { margin:0 10px; font-size:1.5em; color:#0b3d91; transition:0.3s; }
        .socials a:hover { color:#ffd700; }
        @media(max-width:768px){ nav a { display:block; margin:10px 0; } .hero h2 { font-size:2em; } .hero p { font-size:1em; } }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Toha Ahammad</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Protecting Your Digital World</h2>
        <p>আমি Toha Ahammad, একজন সাইবার নিরাপত্তা বিশেষজ্ঞ</p>
        <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Contact Me</button>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Me | আমার পরিচয়</h2>
        <p>আমি <strong>Toha Ahammad</strong>, একজন সাইবার নিরাপত্তা বিশেষজ্ঞ। আমি ডিজিটাল দুনিয়ায় মানুষের তথ্য, ডিভাইস এবং অনলাইন পরিচয়কে সুরক্ষিত রাখতে কাজ করি।</p>
        <p>আমার লক্ষ্য হলো — ব্যক্তি ও প্রতিষ্ঠানকে অনলাইন হুমকি, হ্যাকিং, ফিশিং, ম্যালওয়্যার এবং ডেটা লিক থেকে রক্ষা করা।</p>
        <p>আমি নিয়মিত সাইবার সিকিউরিটি অডিট, পেনেট্রেশন টেস্টিং, এবং ডিজিটাল সচেতনতা প্রশিক্ষণ পরিচালনা করি। বিশ্বাস করি, <em>“নিরাপদ ডিজিটাল জীবনই আধুনিক স্বাধীনতা”</em>।</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Services | সার্ভিসসমূহ</h2>
        <ul>
            <li>Cyber Security Audit | সাইবার নিরাপত্তা অডিট</li>
            <li>Penetration Testing | পেনেট্রেশন টেস্টিং</li>
            <li>Digital Awareness Training | ডিজিটাল সচেতনতা প্রশিক্ষণ</li>
            <li>Data Protection & Privacy Solutions | ডেটা সুরক্ষা ও প্রাইভেসি সমাধান</li>
            <li>Threat Monitoring & Incident Response | হুমকি পর্যবেক্ষণ ও প্রতিক্রিয়া ব্যবস্থা</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me | যোগাযোগ করুন</h2>
        <form>
            <input type="text" placeholder="Your Name | আপনার নাম" required>
            <input type="email" placeholder="Your Email | আপনার ইমেইল" required>
            <textarea placeholder="Your Message | আপনার বার্তা" rows="5" required></textarea>
            <button type="submit">Send Message | বার্তা পাঠান</button>
        </form>
        <div class="socials">
            <a href="https://facebook.com/" target="_blank">Facebook</a>
            <a href="https://linkedin.com/" target="_blank">LinkedIn</a>
            <a href="https://instagram.com/" target="_blank">Instagram</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Toha Ahammad | All Rights Reserved</p>
    </footer>

    <!-- Smooth Scroll JS -->
    <script>
        const links = document.querySelectorAll('nav a');
        for (const link of links) {
            link.addEventListener('click', function(e){
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({behavior:'smooth'});
            });
        }
    </script>

</body>
</html>

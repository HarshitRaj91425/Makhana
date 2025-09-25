<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Sita Makhana - Premium Foxnut from Bihar</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght=400;500;700&family=Poppins:wght=400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', 'Noto Sans', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f5f0;
            overflow-x: hidden;
        }

        .watermark {
            position: fixed;
            bottom: 20px;
            right: 20px;
            color: rgba(255,255,255,0.3);
            font-size: 12px;
            z-index: 1000;
            transform: rotate(-45deg);
            pointer-events: none;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, #228B22 0%, #32CD32 100%);
            color: white;
            padding: 1rem 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            display: flex;
            align-items: center;
        }

        .logo i {
            margin-right: 10px;
            color: #00ffae;
        }

        .contact-info {
            text-align: right;
            font-size: 0.9rem;
        }

        .contact-banner {
            background: linear-gradient(135deg, #FF6347 0%, #FF4500 100%);
            color: white;
            text-align: center;
            padding: 15px 0;
            font-weight: bold;
        }

        .contact-banner a {
            color: white;
            text-decoration: none;
        }

        .contact-banner i {
            margin-right: 8px;
        }

        nav {
            background: rgba(0,0,0,0.1);
            padding: 1rem 0;
        }

        .nav-links {
            display: flex;
            justify-content: center;
            list-style: none;
            flex-wrap: wrap;
        }

        .nav-links li {
            margin: 0 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
            border-radius: 25px;
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-links a:hover {
            background: rgba(255,255,255,0.2);
            transform: translateY(-2px);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 0;
            height: 2px;
            background: #FFD700;
            transition: all 0.3s ease;
            transform: translateX(-50%);
        }

        .nav-links a:hover::after {
            width: 80%;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1607902281477-3ecd8f9b5a8b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 0;
            position: relative;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg"><path d="M50,15 L65,40 L90,40 L70,60 L80,85 L50,70 L20,85 L30,60 L10,40 L35,40 Z" fill="none" stroke="rgba(255,215,0,0.1)" stroke-width="1"/></svg>');
            background-size: 100px 100px;
            opacity: 0.3;
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.7);
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
        }

        .cultural-highlight {
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 100%);
            padding: 20px;
            border-radius: 15px;
            color: #8B4513;
            text-align: center;
            margin: 20px 0;
            border: 2px solid #D2691E;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: #FF6347;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        .btn:hover {
            background: #FF4500;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
        }

        .section {
            padding: 80px 0;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border: 2px solid #D2691E;
            position: relative;
            overflow: hidden;
        }

        .section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, #FFD700, #FF6347);
        }

        .section-about {
            background: linear-gradient(135deg, #FFF8DC 0%, #FFEBCD 100%);
        }

        .section-benefits {
            background: linear-gradient(135deg, #E6F7FF 0%, #BAE7FF 100%);
        }

        .section-farming {
            background: linear-gradient(135deg, #F6FFED 0%, #D9F7BE 100%);
        }

        .section-extraction {
            background: linear-gradient(135deg, #FFF2E8 0%, #FFE7BA 100%);
        }

        .section-company {
            background: linear-gradient(135deg, #F9F0FF 0%, #EFDBFF 100%);
        }

        .section-feedback {
            background: linear-gradient(135deg, #FFF0F6 0%, #FFD6E7 100%);
        }

        .section-demand {
            background: linear-gradient(135deg, #F0F5FF 0%, #D6E4FF 100%);
        }

        .section-production {
            background: linear-gradient(135deg, #F6FFED 0%, #D9F7BE 100%);
        }

        .section-roasting {
            background: linear-gradient(135deg, #FFF7E6 0%, #FFE7BA 100%);
        }

        .section-offer {
            background: linear-gradient(135deg, #FFF1F0 0%, #FFCCC7 100%);
        }

        .section-owner {
            background: linear-gradient(135deg, #F9F0FF 0%, #EFDBFF 100%);
        }

        .section h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #228B22;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            position: inline-block;
            width: 100%;
        }

        .section h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, #FFD700, #FF6347);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }

        .about-text {
            font-size: 1.1rem;
            line-height: 1.8;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .feature-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border: 1px solid #E0E0E0;
            transition: all 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.15);
        }

        .feature-icon {
            font-size: 2.5rem;
            color: #228B22;
            margin-bottom: 20px;
        }

        .feature-card h3 {
            color: #228B22;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }

        .feature-card p {
            color: #555;
            line-height: 1.7;
        }

        .indian-pattern {
            height: 30px;
            background-image: url('data:image/svg+xml,<svg width="100" height="30" viewBox="0 0 100 30" xmlns="http://www.w3.org/2000/svg"><path d="M0,15 Q25,0 50,15 T100,15" stroke="%23FFD700" stroke-width="2" fill="none"/></svg>');
            background-size: 100px 30px;
            margin: 20px 0;
        }

        .process-steps {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }

        .step {
            flex-basis: 23%;
            text-align: center;
            margin-bottom: 30px;
            position: relative;
        }

        .step-number {
            width: 50px;
            height: 50px;
            background: #228B22;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: bold;
            margin: 0 auto 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .step h3 {
            color: #228B22;
            margin-bottom: 10px;
            font-size: 1.2rem;
        }

        .step p {
            color: #555;
            line-height: 1.6;
        }

        .flowchart {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 40px 0;
        }

        .flowchart-step {
            background: white;
            border-radius: 15px;
            padding: 25px;
            width: 30%;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border: 2px solid #228B22;
            position: relative;
            z-index: 1;
        }

        .flowchart-icon {
            font-size: 3rem;
            color: #228B22;
            margin-bottom: 15px;
        }

        .flowchart-arrow {
            font-size: 2rem;
            color: #228B22;
            margin: 0 10px;
        }

        .taste-description {
            margin-top: 30px;
        }

        .taste-description h3 {
            color: #228B22;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }

        .taste-description p {
            margin-bottom: 15px;
            line-height: 1.7;
        }

        .taste-description ul {
            margin-left: 20px;
            margin-top: 10px;
        }

        .taste-description li {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .demand-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        .demand-box {
            background: white;
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .demand-box h3 {
            color: #228B22;
            margin-bottom: 10px;
            font-size: 1.3rem;
        }

        .demand-box p {
            color: #555;
            line-height: 1.6;
        }

        .production-map {
            display: flex;
            justify-content: center;
            margin: 30px 0;
        }

        .production-map img {
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .roasting-steps ol {
            padding-left: 20px;
            margin-top: 15px;
        }

        .roasting-steps li {
            margin-bottom: 15px;
            line-height: 1.6;
        }

        .offer-container {
            background: white;
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .offer-box {
            background: linear-gradient(135deg, #FF6347 0%, #FF4500 100%);
            color: white;
            border-radius: 15px;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            border: 3px solid #FFD700;
        }

        .offer-box h3 {
            font-size: 2rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .offer-box p {
            font-size: 1.2rem;
            margin-bottom: 15px;
        }

        .offer-box .phone {
            font-size: 1.8rem;
            font-weight: bold;
            margin-top: 20px;
            display: block;
        }

        .offer-box .highlight {
            background: rgba(255,255,255,0.2);
            padding: 5px 15px;
            border-radius: 30px;
            display: inline-block;
            margin-top: 15px;
            font-weight: bold;
        }

        .owner-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            margin-top: 40px;
        }

        .owner-profile {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border: 1px solid #E0E0E0;
        }

        .owner-image {
            text-align: center;
            margin-bottom: 20px;
        }

        .owner-name {
            font-size: 1.8rem;
            color: #228B22;
            margin-bottom: 10px;
            text-align: center;
        }

        .owner-title {
            font-size: 1.2rem;
            color: #FF6347;
            margin-bottom: 20px;
            text-align: center;
        }

        .owner-story {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border: 1px solid #E0E0E0;
        }

        .owner-story h3 {
            color: #228B22;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }

        .owner-story p {
            margin-bottom: 15px;
            line-height: 1.7;
        }

        .vision-box {
            background: linear-gradient(135deg, #228B22 0%, #32CD32 100%);
            color: white;
            border-radius: 15px;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .vision-box h4 {
            margin-bottom: 10px;
            font-size: 1.3rem;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 40px 0;
            margin-top: 50px;
            border-top: 5px solid #FFD700;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 30px;
        }

        .footer-section h3 {
            color: #FFD700;
            margin-bottom: 15px;
        }

        .footer-section p {
            color: #ccc;
            line-height: 1.6;
        }

        .success-message {
            background: #d4edda;
            color: #155724;
            padding: 15px;
            border-radius: 8px;
            margin: 20px 0;
            display: none;
        }
    </style>
</head>
<body>
    <div class="watermark">Sonali</div>
    
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-leaf"></i>
                    सीता मखाना
                </div>
                <div class="contact-info">
                    <div>📧 harshitraj90060@gmail.com</div>
                    <div>📞 +91 9955596013</div>
                    <div>📍 Near Mohit Raj Plot, Charkhi, Katihar-854108, Bihar</div>
                </div>
            </div>
            <nav>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#benefits">Benefits</a></li>
                    <li><a href="#farming">Farming</a></li>
                    <li><a href="#extraction">Extraction</a></li>
                    <li><a href="#company">Our Company</a></li>
                    <li><a href="#owner">Our Owner</a></li>
                    <li><a href="#demand">Global Demand</a></li>
                    <li><a href="#production">Production</a></li>
                    <li><a href="#roasting">Roasting</a></li>
                    <li><a href="#offer">Special Offers</a></li>
                    <li><a href="#feedback">Feedback</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="contact-banner">
        <div class="container">
            <p>For Bulk Orders and Wholesale Inquiries: <a href="tel:+9142500656"><i class="fas fa-phone"></i> +91 9142500656</a></p>
        </div>
    </div>

    <section id="home" class="hero">
        <div class="container hero-content">
            <h1>Premium Makhana from Bihar</h1>
            <p>Authentic Foxnut harvested from the pristine waters of Charkhi, Korha</p>
            <div class="cultural-highlight">
                "मखाने की मिठास, बिहार की पहचान" - The sweetnessof Makhana, Bihar's identity
            </div>
            <a href="#contact" class="btn">Order Now</a>
        </div>
    </section>

    <section id="about" class="section section-about">
        <div class="container">
            <h2>Our Story</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>From the Heart of Bihar</h3>
                    <p>Sita Makhana brings you the finest quality foxnut directly from the traditional farming communities of Charkhi, Korha in Katihar district, Bihar. Our makhana is harvested by skilled farmers who have been practicing this ancient art for generations.</p>
                    
                    <p>Under the proprietorship of <strong>Mr. Ganesh Prasad Chaurasiya</strong>, we are committed to preserving the cultural heritage of Bihar while providing premium quality makhana to customers across India.</p>
                    
                    <div class="cultural-highlight">
                        <p><strong>Cultural Heritage:</strong> Makhana cultivation in Bihar dates back centuries. The lotus seeds are hand-picked from pods during early morning hours when they are at their freshest.</p>
                    </div>
                    
                    <p>Located near Mohit Raj Plot, Charkhi, our processing facility maintains the highest quality standards while preserving the authentic taste and nutritional value of this superfood.</p>
                </div>
                
                <div>
                    <!-- Image removed as per request -->
                </div>
            </div>
            
            <div class="indian-pattern"></div>
            
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Farmer Empowerment</h3>
                    <p>We provide training and resources to our farmers, helping them improve their yield and income while preserving traditional farming knowledge.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-seedling"></i>
                    </div>
                    <h3>Sustainable Farming</h3>
                    <p>Our farming practices are environmentally sustainable, focusing on water conservation and maintaining the ecological balance of the region.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h3>Fair Trade Practices</h3>
                    <p>We ensure fair compensation for our farmers' hard work, eliminating middlemen and creating a direct link between producers and consumers.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="benefits" class="section section-benefits">
        <div class="container">
            <h2>Health Benefits of Makhana</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-heart"></i>
                    </div>
                    <h3>Rich in Antioxidants</h3>
                    <p>Makhana contains powerful antioxidants that help combat oxidative stress and reduce inflammation in the body, promoting overall health.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-weight"></i>
                    </div>
                    <h3>Weight Management</h3>
                    <p>Low in calories and high in fiber, makhana is an excellent snack for weight management as it keeps you full for longer periods.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Brain Health</h3>
                    <p>Rich in thiamine, which helps in maintaining nerve function and cognitive health, making it beneficial for brain development.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-bone"></i>
                    </div>
                    <h3>Bone Health</h3>
                    <p>Contains calcium in good amounts, which is essential for maintaining strong bones and preventing conditions like osteoporosis.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-heartbeat"></i>
                    </div>
                    <h3>Heart Health</h3>
                    <p>Low in sodium and high in magnesium, makhana helps in regulating blood pressure and maintaining a healthy cardiovascular system.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-diabetes"></i>
                    </div>
                    <h3>Diabetes Management</h3>
                    <p>With a low glycemic index and high fiber content, makhana helps in controlling blood sugar levels, making it ideal for diabetics.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-virus"></i>
                    </div>
                    <h3>Anti-inflammatory Properties</h3>
                    <p>The flavonoids in makhana help reduce inflammation and may alleviate symptoms of inflammatory conditions.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-moon"></i>
                    </div>
                    <h3>Promotes Better Sleep</h3>
                    <p>Makhana contains natural sedative properties that can help improve sleep quality and combat insomnia.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-female"></i>
                    </div>
                    <h3>Women's Health</h3>
                    <p>Rich in calcium and other minerals, makhana is beneficial for women's health, especially during pregnancy and menopause.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="farming" class="section section-farming">
        <div class="container">
            <h2>Makhana Farming & Our Farmers</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Traditional Farming Practices</h3>
                    <p>Makhana farming in Bihar is a labor-intensive process that requires skill and patience. Our farmers follow traditional methods that have been passed down through generations, ensuring the highest quality product.</p>
                    
                    <p>The cultivation begins with the preparation of ponds, which are carefully maintained to create the perfect environment for lotus plants to thrive. Our farmers use organic farming practices, avoiding harmful pesticides and chemicals.</p>
                    
                    <div class="cultural-highlight">
                        <p><strong>Supporting Local Farmers:</strong> We work directly with over 200 farming families, providing them with training and resources to transition to organic farming practices. This not only improves the quality of the product but also ensures better health for both farmers and consumers.</p>
                    </div>
                    
                    <p>Our farmers are the backbone of our business, and we are committed to their welfare. We provide them with modern equipment while respecting traditional knowledge, creating a perfect blend of old and new.</p>
                </div>
                
                <div>
                    <!-- Image removed as per request -->
                </div>
            </div>
            
            <div class="indian-pattern"></div>
            
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Farmer Empowerment</h3>
                    <p>We provide training and resources to our farmers, helping them improve their yield and income while preserving traditional farming knowledge.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-seedling"></i>
                    </div>
                    <h3>Sustainable Farming</h3>
                    <p>Our farming practices are environmentally sustainable, focusing on water conservation and maintaining the ecological balance of the region.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h3>Fair Trade Practices</h3>
                    <p>We ensure fair compensation for our farmers' hard work, eliminating middlemen and creating a direct link between producers and consumers.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="extraction" class="section section-extraction">
        <div class="container">
            <h2>Makhana Extraction Process</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">The journey from lotus seed to premium makhana involves several meticulous steps</p>
            
            <div class="process-steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Harvesting</h3>
                    <p>Lotus seeds are hand-picked from the pods during early morning hours when they are at their freshest.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Cleaning</h3>
                    <p>The seeds are thoroughly cleaned to remove any impurities, mud, or organic matter attached to them.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Roasting</h3>
                    <p>The cleaned seeds are roasted at controlled temperatures to achieve the perfect crunch and flavor.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Popping</h3>
                    <p>The roasted seeds are popped to expand them, giving makhana its characteristic light and airy texture.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">5</div>
                    <h3>Sorting</h3>
                    <p>The popped makhana is carefully sorted by size and quality, ensuring only the best reaches our customers.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">6</div>
                    <h3>Packaging</h3>
                    <p>The final product is hygienically packaged to preserve freshness and nutritional value.</p>
                </div>
            </div>
            
            <div class="cultural-highlight">
                <p><strong>Traditional Wisdom:</strong> Our extraction process combines age-old techniques with modern quality control to bring you makhana that is authentic, pure, and of the highest quality.</p>
            </div>
        </div>
    </section>

    <section id="company" class="section section-company">
        <div class="container">
            <h2>About Sita Makhana</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Our Commitment to Quality</h3>
                    <p>At Sita Makhana, we are committed to providing the highest quality makhana while maintaining strict hygiene standards throughout our production process. Our facility is equipped with modern equipment that ensures the product remains pure and uncontaminated.</p>
                    
                    <p>We follow a comprehensive quality control process that begins at the farming stage and continues until the product reaches our customers. Each batch of makhana is tested for purity, size, and taste before being approved for packaging.</p>
                    
                    <div class="cultural-highlight">
                        <p><strong>Our Mission:</strong> We provide direct employment to 30-50 people and indirectly support more than 500 farmers. Our main motto is to eliminate middlemen and maximize benefits for farmers, ensuring they receive fair compensation for their hard work.</p>
                    </div>
                    
                    <p>Under the leadership of Mr. Ganesh Prasad Chaurasiya, we have grown from a local supplier to a recognized name in the makhana industry, while staying true to our roots and commitment to quality.</p>
                </div>
                
                <div>
                    <!-- Image removed as per request -->
                </div>
            </div>
            
            <h3 style="text-align: center; margin-top: 40px; color: #228B22;">Our Journey: From Farm to Customer</h3>
            
            <div class="flowchart">
                <div class="flowchart-step">
                    <div class="flowchart-icon">
                        <i class="fas fa-seedling"></i>
                    </div>
                    <h3>Farm</h3>
                    <p>Lotus seeds harvested by our network of farmers</p>
                </div>
                
                <div class="flowchart-arrow">
                    <i class="fas fa-arrow-right"></i>
                </div>
                
                <div class="flowchart-step">
                    <div class="flowchart-icon">
                        <i class="fas fa-industry"></i>
                    </div>
                    <h3>Factory</h3>
                    <p>Processing, roasting, and quality packaging</p>
                </div>
                
                <div class="flowchart-arrow">
                    <i class="fas fa-arrow-right"></i>
                </div>
                
                <div class="flowchart-step">
                    <div class="flowchart-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Customers</h3>
                    <p>B2B and B2C delivery across India and globally</p>
                </div>
            </div>
            
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-award"></i>
                    </div>
                    <h3>Premium Quality</h3>
                    <p>We offer only Grade A makhana, carefully selected for size, color, and taste, ensuring our customers receive the best product available.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Hygiene Assurance</h3>
                    <p>Our processing facility maintains the highest standards of hygiene, with regular quality checks and food safety certifications.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-truck"></i>
                    </div>
                    <h3>Pan India & Global Delivery</h3>
                    <p>We deliver our premium makhana to customers across India within 5-9 days. For international orders, delivery time depends on distance and courier services.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="demand" class="section section-demand">
        <div class="container">
            <h2>Global Demand for Foxnut</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">Makhana is gaining popularity worldwide as a healthy snack and superfood</p>
            
            <div class="demand-grid">
                <div class="demand-box">
                    <h3>India</h3>
                    <p>Highest consumer and producer with growing demand in urban areas</p>
                </div>
                
                <div class="demand-box">
                    <h3>USA</h3>
                    <p>Rapidly growing market as health-conscious consumers seek nutritious snacks</p>
                </div>
                
                <div class="demand-box">
                    <h3>Canada</h3>
                    <p>Increasing popularity among South Asian diaspora and health enthusiasts</p>
                </div>
                
                <div class="demand-box">
                    <h3>UK</h3>
                    <p>Emerging market with demand rising in specialty food stores</p>
                </div>
                
                <div class="demand-box">
                    <h3>Australia</h3>
                    <p>Growing demand in health food sector and Asian grocery stores</p>
                </div>
                
                <div class="demand-box">
                    <h3>UAE</h3>
                    <p>Strong demand from large Indian expatriate population</p>
                </div>
                
                <div class="demand-box">
                    <h3>Japan</h3>
                    <p>Niche market with interest in unique health foods</p>
                </div>
                
                <div class="demand-box">
                    <h3>Germany</h3>
                    <p>Increasing demand in organic and health food stores</p>
                </div>
            </div>
        </div>
    </section>

    <section id="production" class="section section-production">
        <div class="container">
            <h2>Makhana Production Hub</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">Discover the heartland of makhana cultivation in India</p>
            
            <div class="production-content">
                <div class="about-text">
                    <h3>Leading Makhana Producing Regions</h3>
                    <p>Bihar is the undisputed leader in makhana production, contributing over 90% of India's total output. The fertile plains and abundant water bodies in the state create ideal conditions for lotus cultivation.</p>
                    
                    <p>The major makhana producing districts in Bihar include:</p>
                    <ul style="padding-left: 20px; margin-top: 15px;">
                        <li><strong>Madhubani</strong> - Known as the "Makhana Capital of India"</li>
                        <li><strong>Darbhanga</strong> - Second largest producer with high-quality yield</li>
                        <li><strong>Purnea</strong> - Emerging hub with modern cultivation techniques</li>
                        <li><strong>Katihar</strong> - Our home district with traditional farming practices</li>
                        <li><strong>Saharsa</strong> - Significant contributor to state's makhana production</li>
                    </ul>
                    
                    <p style="margin-top: 20px;">Other states like West Bengal, Assam, and Odisha also produce makhana but in much smaller quantities compared to Bihar.</p>
                </div>
                
                <div class="production-map">
                    <!-- Image removed as per request -->
                </div>
            </div>
        </div>
    </section>

    <section id="roasting" class="section section-roasting">
        <div class="container">
            <h2>Roasting Makhana at Home</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">Learn how to prepare delicious roasted makhana in your kitchen</p>
            
            <div class="roasting-content">
                <div class="roasting-steps">
                    <ol>
                        <li>Take 1 cup of raw makhana seeds .</li>
                        <li>Heat a heavy-bottomed pan or kadai on medium flame for 2-3 minutes.</li>
                        <li>Add 1 teaspoon of ghee to the pan and let it heat slightly.</li>
                        <li>Add the raw makhana seeds to the pan and stir continuously. Roast for 8-10 minutes until they become crispy.</li>
                        <li>Take a few makhana seeds and let them cool. They should be crispy and crunchy when ready.</li>
                        <li>Seasoning: Add salt, pepper, chaat masala, or any other seasoning of your choice. Mix well.</li>
                    </ol>
                </div>
                
                <div class="taste-description">
                    <h3>The Taste of Makhana</h3>
                    <p>Makhana has a unique and delightful taste profile that sets it apart from other snacks. When raw, it has a mild, starchy flavor similar to raw nuts. However, once roasted, it transforms into a light, crispy snack with a subtle nutty taste.</p>
                    
                    <p>The texture is one of makhana's most appealing characteristics - it's light and airy with a satisfying crunch that melts in your mouth. This unique texture makes it an excellent alternative to popcorn or chips.</p>
                    
                    <p>When seasoned, makhana readily absorbs flavors, making it incredibly versatile. You can enjoy it as:</p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Savory snack with salt and spices</li>
                        <li>Sweet treat with jaggery or honey</li>
                        <li>Crispy topping for curries and desserts</li>
                        <li>Healthy ingredient in trail mixes</li>
                    </ul>
                    
                    <p style="margin-top: 15px;">The mild flavor of makhana makes it perfect for both sweet and savory preparations, allowing you to experiment with different seasonings according to your taste preferences.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="offer" class="section section-offer">
        <div class="container">
            <h2>Special Offers</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">Exclusive deals for our valued customers</p>
            
            <div class="offer-container">
                <div class="offer-box">
                    <h3><i class="fas fa-percentage"></i> First Order Discount</h3>
                    <p>Get FLAT 5% OFF on your first order when you call us directly</p>
                    <p>Offer valid on orders of 4kg or more</p>
                    <div class="highlight">Limited Time Offer</div>
                    <a href="tel:+919142500656" class="phone"><i class="fas fa-phone"></i> +91 9142500656</a>
                </div>
                
                <div class="cultural-highlight">
                    <p><strong>Bulk Order Benefits:</strong> For bulk orders, we offer special pricing and benefits that will be discussed personally over the phone. Contact us to know more about our exclusive bulk deals and discounts.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="owner" class="section section-owner">
        <div class="container">
            <h2>Meet Our Owner</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">The visionary behind Sita Makhana's success</p>
            
            <div class="owner-content">
                <div class="owner-profile">
                    <div class="owner-image">
                    </div>
                    <h3 class="owner-name">Mr. Ganesh Prasad Chaurasiya</h3>
                    <p class="owner-title">Proprietor, Sita Makhana</p>
                    
                    <div class="cultural-highlight">
                        <p>"Born and raised in the heartland of makhana farming, I've witnessed the entire journey of this superfood from seed to table."</p>
                    </div>
                
                <div class="owner-story">
                    <h3>A Legacy Rooted in Tradition</h3>
                    <p>Mr. Ganesh Prasad Chaurasiya hails from the Katihar district of Bihar, a region renowned for its makhana cultivation. Having grown up watching his family and community engage in traditional farming, he developed a deep connection with this superfood from an early age.</p>
                    
                    <h3>Vision for Organic Farming</h3>
                    <p>Recognizing the growing global demand for organic products, Mr. Chaurasiya has been a strong advocate for organic makhana farming. He actively promotes and educates farmers about sustainable and organic cultivation methods, ensuring that the makhana produced is free from harmful chemicals and pesticides.</p>
                    
                    <h3>Employment and Social Impact</h3>
                    <p>Currently providing direct employment to more than 40 people and indirectly supporting more than 500 farmers, Mr. Chaurasiya dreams of expanding this number to create opportunities for many more needy individuals in the region. His vision extends beyond business success to creating a sustainable ecosystem where farmers thrive, employees grow, and customers receive the highest quality product.</p>
                    
                    <div class="vision-box">
                        <h4>Employment and Social Impact</h4>
                        <p>Currently providing direct employment to more than 40 people and indirectly supporting more than 500 farmers. Our main motto is to eliminate middlemen and maximize benefits for farmers, ensuring they receive fair compensation for their hard work.</p>
                    </div>
                    
                    <p style="margin-top: 15px;">Under the leadership of Mr. Ganesh Prasad Chaurasiya, we have grown from a local supplier to a recognized name in the makhana industry, while staying true to our roots and commitment to quality.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="feedback" class="section section-feedback">
        <div class="container">
            <h2>Customer Feedback</h2>
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.2rem;">We value your opinion and look forward to hearing from you</p>
            
            <div class="feedback-container">
                <div class="feedback-form">
                    <h3>Share Your Experience</h3>
                    <form id="feedback-form">
                        <div class="form-group">
                            <label for="feedback-name">Name *</label>
                            <input type="text" id="feedback-name" required>
                        </div>
                        <div class="form-group">
                            <label for="feedback-email">Email *</label>
                            <input type="email" id="feedback-email" required>
                        </div>
                        <div class="form-group">
                            <label for="feedback-message">Your Feedback *</label>
                            <textarea id="feedback-message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn">Submit Feedback</button>
                    </form>
                    
                    <div id="feedback-success" class="success-message">
                        <strong>Thank you!</strong> Your feedback has been submitted successfully. We'll get back to you soon.
                    </div>
                </div>
                
                <div class="feedback-list">
                    <h3>Recent Feedback</h3>
                    
                    <div class="feedback-item">
                        <div class="feedback-content">
                            <h4>Rajesh Kumar</h4>
                            <p>The quality of makhana is excellent. I've been a regular customer for the past year and have never been disappointed. The packaging is also very good.</p>
                        </div>
                        <div class="feedback-reply">
                            <h4>Reply from Sita Makhana</h4>
                            <p>Thank you for your feedback, Rajesh! We're glad you enjoy our product. We look forward to serving you for many more years.</p>
                        </div>
                    </div>
                    
                    <div class="feedback-item">
                        <div class="feedback-content">
                            <h4>Priya Sharma</h4>
                            <p>I love the roasted makhana from Sita Makhana. It's crispy and tasty. My kids love it too as a healthy snack option.</p>
                        </div>
                        <div class="feedback-reply">
                            <h4>Reply from Sita Makhana</h4>
                            <p>Thank you, Priya! It's wonderful to know that our makhana is enjoyed by your entire family. We appreciate your support.</p>
                        </div>
                    </div>
                    
                    <div class="feedback-item">
                        <div class="feedback-content">
                            <h4>Amit Patel</h4>
                            <p>The delivery was prompt and the product was fresh. I appreciate the effort to remove middlemen and support farmers directly.</p>
                        </div>
                        <div class="feedback-reply">
                            <h4>Reply from Sita Makhana</h4>
                            <p>Thank you for recognizing our efforts, Amit. Supporting farmers is at the core of our business, and it resonates with our customers.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Us</h2>
            
            <div class="contact-banner">
                <div class="container">
                    <p>For Bulk Orders and Wholesale Inquiries: <a href="tel:+9142500656"><i class="fas fa-phone"></i> +91 9142500656</a></p>
                </div>
            </div>
            
            <div class="form-container">
                <div class="form-tabs">
                    <button class="tab-button active" onclick="switchTab('dealership')">Dealership Inquiry</button>
                    <button class="tab-button" onclick="switchTab('self-use')">Purchase Order</button>
                </div>

                <div id="dealership-tab" class="tab-content active">
                    <h3>Become Our Dealer</h3>
                    <form id="dealership-form">
                        <div class="form-group">
                            <label for="dealer-name">Full Name *</label>
                            <input type="text" id="dealer-name" required>
                        </div>
                        <div class="form-group">
                            <label for="dealer-mobile">Mobile Number *</label>
                            <input type="tel" id="dealer-mobile" required>
                        </div>
                        <div class="form-group">
                            <label for="dealer-email">Email Address *</label>
                            <input type="email" id="dealer-email" required>
                        </div>
                        <div class="form-group">
                            <label for="dealer-location">Location *</label>
                            <textarea id="dealer-location" rows="3" required></textarea>
                        </div>
                        <div class="cultural-highlight">
                            <strong>Space Requirement:</strong> Minimum 500-600 square feet required
                        </div>
                        <button type="submit" class="btn">Submit Dealership Application</button>
                    </form>
                </div>

                <div id="purchase-tab" class="tab-content">
                    <h3>Place Your Order</h3>
                    <form id="purchase-form">
                        <div class="form-group">
                            <label for="customer-name">Full Name *</label>
                            <input type="text" id="customer-name" required>
                        </div>
                        <div class="form-group">
                            <label for="customer-email">Email Address *</label>
                            <input type="email" id="customer-email" required>
                        </div>
                        <div class="form-group">
                            <label for="customer-mobile">Mobile Number *</label>
                            <input type="tel" id="customer-mobile" required>
                        </div>
                        <div class="form-group">
                            <label for="customer-location">Delivery Location *</label>
                            <textarea id="customer-location" rows="3" required></textarea>
                        </div>
                        <div class="form-group">
                            <label>Payment Preference *</label>
                            <div class="payment-options">
                                <div class="payment-option" onclick="selectPayment(this, 'upi')">UPI</div>
                                <div class="payment-option" onclick="selectPayment(this, 'phonepe')">PhonePe</div>
                                <div class="payment-option" onclick="selectPayment(this, 'paytm')">Paytm</div>
                                <div class="payment-option" onclick="selectPayment(this, 'googlepay')">Google Pay</div>
                                <div class="payment-option" onclick="selectPayment(this, 'cod')">Cash on Delivery</div>
                            </div>
                            <input type="hidden" id="payment-method" required>
                        </div>
                        <button type="submit" class="btn">Place Order</button>
                    </form>
                </div>

                <div id="success-message" class="success-message">
                    Thank you! Our company call executive will respond to you soon within 24 hours.
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Sita Makhana</h3>
                    <p>Premium foxnut from the heart of Bihar</p>
                    <p><strong>Proprietor:</strong> Mr. Ganesh Prasad Chaurasiya</p>
                </div>
                <div class="footer-section">
                    <h3>Contact Information</h3>
                    <p>📧 harshitraj90060@gmail.com</p>
                    <p>📞 +91 9955596013</p>
                    <p>📞 +91 9142500656 (Bulk Orders)</p>
                    <p>📍 Near Mohit Raj Plot, Charkhi, Katihar-854108, Bihar</p>
                </div>
                <div class="footer-section">
                    <h3>Our Mission</h3>
                    <p>We provide direct employment to 30-50 people and indirectly support more than 500 farmers. Our main motto is to eliminate middlemen and maximize benefits for farmers, ensuring they receive fair compensation for their hard work.</p>
                </div>
            </div>
            <p>&copy; 2025 Sita Makhana. All rights reserved. | Watermarked by Sonali</p>
        </div>
    </footer>
</body>
</html>

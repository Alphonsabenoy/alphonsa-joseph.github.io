# alphonsa-joseph.github.io
Marketing strategist with 8+ years driving growth across India, Canada &amp; EMEA. Generated $1.1M revenue retention + $2M growth opportunities through data-driven campaigns. Expert in analytics, international marketing &amp; brand strategy. Let's connect!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alphonsa Joseph - Marketing Strategy & Analytics Professional</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #667eea;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease;
        }

        .hero-content .subtitle {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            opacity: 0.9;
            animation: fadeInUp 1s ease 0.1s both;
        }

        .hero-content p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            animation: fadeInUp 1s ease 0.2s both;
        }

        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            background: #ff6b6b;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeInUp 1s ease 0.4s both;
            margin: 0 10px;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(255, 107, 107, 0.4);
        }

        .cta-button.secondary {
            background: transparent;
            border: 2px solid white;
        }

        .cta-button.secondary:hover {
            background: white;
            color: #667eea;
        }

        /* Sections */
        .section {
            padding: 80px 0;
            background: white;
        }

        .section:nth-child(even) {
            background: #f8f9fa;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #333;
        }

        /* About Section */
        .about-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 3rem;
            align-items: center;
        }

        .profile-img {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            background: linear-gradient(135deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.2rem;
            text-align: center;
        }

        .about-text p {
            font-size: 1.1rem;
            margin-bottom: 1.5rem;
            color: #666;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
            margin-top: 2rem;
        }

        .stat-item {
            text-align: center;
            padding: 1.5rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            color: #667eea;
            display: block;
        }

        /* Experience Section */
        .experience-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .experience-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            border-left: 4px solid #667eea;
        }

        .experience-card:hover {
            transform: translateY(-5px);
        }

        .experience-card h3 {
            color: #333;
            margin-bottom: 0.5rem;
        }

        .experience-card .company {
            color: #667eea;
            font-weight: bold;
            margin-bottom: 1rem;
        }

        .experience-card .period {
            color: #888;
            font-size: 0.9rem;
            margin-bottom: 1rem;
        }

        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-img {
            height: 200px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 3rem;
        }

        .project-content {
            padding: 1.5rem;
        }

        .project-content h3 {
            margin-bottom: 1rem;
            color: #333;
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            background: #667eea;
            color: white;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.8rem;
        }

        /* Skills Section */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .skill-category {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .skill-category h3 {
            color: #667eea;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .skill-list {
            list-style: none;
        }

        .skill-list li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }

        .skill-list li:last-child {
            border-bottom: none;
        }

        /* Contact Section */
        .contact-content {
            max-width: 600px;
            margin: 0 auto;
            text-align: center;
        }

        .contact-form {
            display: grid;
            gap: 1rem;
            margin-top: 2rem;
        }

        .contact-form input,
        .contact-form textarea {
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            font-family: inherit;
        }

        .contact-form button {
            padding: 1rem;
            background: #667eea;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .contact-form button:hover {
            background: #5a6fd8;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 2rem;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: #667eea;
            color: white;
            border-radius: 50%;
            text-decoration: none;
            transition: transform 0.3s ease;
        }

        .social-links a:hover {
            transform: scale(1.1);
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2.5rem;
            }

            .hero-content .subtitle {
                font-size: 1.2rem;
            }

            .hero-content p {
                font-size: 1.1rem;
            }

            .about-content {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .stats {
                grid-template-columns: repeat(2, 1fr);
            }

            .nav-links {
                display: none;
            }

            .cta-button {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="container">
            <div class="logo">Alphonsa Joseph</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Alphonsa Joseph</h1>
            <div class="subtitle">Marketing Strategy & Analytics Professional</div>
            <p>Transforming data into actionable marketing insights across global markets</p>
            <a href="#contact" class="cta-button">Let's Connect</a>
            <a href="#projects" class="cta-button secondary">View Projects</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="profile-img">Professional<br>Photo</div>
                <div class="about-text">
                    <p>Results-driven Marketing Professional with 8+ years of experience in market analysis, consumer insights, and campaign optimization. Proven expertise in data-driven marketing strategies, competitive intelligence, and cross-functional collaboration across retail, lighting, and educational sectors.</p>
                    
                    <p>My international experience spans Canada, USA, India, and EMEA markets, with a strong background in predictive analytics, customer segmentation, and strategic marketing planning. I'm passionate about bridging the gap between data and actionable business strategies.</p>
                    
                    <div class="stats">
                        <div class="stat-item">
                            <span class="stat-number">8+</span>
                            <span>Years Experience</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">4</span>
                            <span>Global Markets</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">150+</span>
                            <span>Students Mentored</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">25%</span>
                            <span>Placement Improvement</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="section">
        <div class="container">
            <h2 class="section-title">Professional Experience</h2>
            <div class="experience-grid">
                <div class="experience-card">
                    <h3>Freelance Market Consultant</h3>
                    <div class="company">Kycho Cloud Kitchen</div>
                    <div class="period">July 2025 – Present</div>
                    <p>Conducting comprehensive market analysis for cloud kitchen expansion, analyzing competitor positioning, and developing customer acquisition strategies with sustainable pricing models.</p>
                </div>
                
                <div class="experience-card">
                    <h3>Assistant Professor</h3>
                    <div class="company">IZee Business School</div>
                    <div class="period">February 2024 – June 2025</div>
                    <p>Designed and delivered marketing and strategy courses using real-world case studies. Launched "15 Days 15 Founders" initiative, engaging 150+ students with industry leaders and improving project performance by 30%.</p>
                </div>
                
                <div class="experience-card">
                    <h3>Market Intelligence Coordinator</h3>
                    <div class="company">Amico Lights</div>
                    <div class="period">August 2021 – May 2023</div>
                    <p>Led market analysis across Canada, USA, India, and EMEA markets. Developed customer churn prediction models using CleverTap and conducted competitive analysis identifying significant growth opportunities.</p>
                </div>

                <div class="experience-card">
                    <h3>Merchandise Lead – Health, Beauty and Fashion</h3>
                    <div class="company">Walmart Canada</div>
                    <div class="period">October 2018 – July 2021</div>
                    <p>Managed marketing performance for Health, Beauty & Fashion Categories with focus on consumer behavior analysis. Reduced inventory shrinkage through data-driven SKU optimization and supplier collaboration.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2 class="section-title">Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-img"><i class="fas fa-chart-line"></i></div>
                    <div class="project-content">
                        <h3>Customer Churn Prediction Model</h3>
                        <p>Developed machine learning model using CleverTap data to predict customer churn with high accuracy. Implemented early warning system for at-risk customers across multiple markets.</p>
                        <div class="project-tags">
                            <span class="tag">Python</span>
                            <span class="tag">CleverTap</span>
                            <span class="tag">Predictive Analytics</span>
                            <span class="tag">Customer Retention</span>
                        </div>
                    </div>
                </div>
                
                <div class="project-card">
                    <div class="project-img"><i class="fas fa-beer"></i></div>
                    <div class="project-content">
                        <h3>AB InBev Craft Beer Market Entry</h3>
                        <p>Independent research project analyzing market entry opportunities for craft beer segment in India. Comprehensive consumer analysis and competitive positioning study.</p>
                        <div class="project-tags">
                            <span class="tag">Market Research</span>
                            <span class="tag">Consumer Analysis</span>
                            <span class="tag">Entry Strategy</span>
                            <span class="tag">Competitive Intelligence</span>
                        </div>
                    </div>
                </div>
                
                <div class="project-card">
                    <div class="project-img"><i class="fas fa-coffee"></i></div>
                    <div class="project-content">
                        <h3>Starbucks Australia Turnaround Strategy</h3>
                        <p>Self-initiated marketing-focused strategy emphasizing brand localization. Designed customer re-engagement tactics and performance improvement recommendations.</p>
                        <div class="project-tags">
                            <span class="tag">Brand Strategy</span>
                            <span class="tag">Localization</span>
                            <span class="tag">Customer Engagement</span>
                            <span class="tag">Turnaround Strategy</span>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-img"><i class="fas fa-utensils"></i></div>
                    <div class="project-content">
                        <h3>Cloud Kitchen Market Analysis</h3>
                        <p>Comprehensive market analysis for cloud kitchen expansion targeting optimal delivery radius. Competitor positioning analysis and pricing model recommendations.</p>
                        <div class="project-tags">
                            <span class="tag">Market Analysis</span>
                            <span class="tag">Delivery Optimization</span>
                            <span class="tag">Pricing Strategy</span>
                            <span class="tag">Growth Strategy</span>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-img"><i class="fas fa-users"></i></div>
                    <div class="project-content">
                        <h3>15 Days 15 Founders Initiative</h3>
                        <p>Created innovative curriculum connecting 150+ students with industry leaders and entrepreneurs. Improved student project performance through practical frameworks.</p>
                        <div class="project-tags">
                            <span class="tag">Education</span>
                            <span class="tag">Industry Partnerships</span>
                            <span class="tag">Mentorship</span>
                            <span class="tag">Curriculum Development</span>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-img"><i class="fas fa-award"></i></div>
                    <div class="project-content">
                        <h3>Green Banking Research</h3>
                        <p>Award-winning research on Green Banking and Sustainable Finance. Presented at Indus Sammelan 2024 and received Best Paper Award for innovative approach.</p>
                        <div class="project-tags">
                            <span class="tag">Research</span>
                            <span class="tag">Sustainable Finance</span>
                            <span class="tag">Banking</span>
                            <span class="tag">Award Winner</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section">
        <div class="container">
            <h2 class="section-title">Core Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3><i class="fas fa-chart-bar"></i> Analytics & Research</h3>
                    <ul class="skill-list">
                        <li>Market Research & Consumer Behavior Analysis</li>
                        <li>Competitive Intelligence</li>
                        <li>Predictive Analytics & Statistical Analysis</li>
                        <li>Data Visualization</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-tools"></i> Marketing Tools</h3>
                    <ul class="skill-list">
                        <li>CleverTap & SAS Analytics</li>
                        <li>HubSpot & Google Analytics</li>
                        <li>Advanced Excel & Tableau</li>
                        <li>JIRA & Project Management Tools</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-bullseye"></i> Marketing Expertise</h3>
                    <ul class="skill-list">
                        <li>Campaign Optimization & A/B Testing</li>
                        <li>Customer Segmentation & Churn Analysis</li>
                        <li>Performance Marketing</li>
                        <li>International Marketing Strategy</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-users-cog"></i> Leadership</h3>
                    <ul class="skill-list">
                        <li>Project Management & Strategic Planning</li>
                        <li>Stakeholder Communication</li>
                        <li>Team Leadership & Mentoring</li>
                        <li>Cross-functional Collaboration</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <p>Ready to leverage data-driven marketing strategies for your business? Let's discuss how my expertise in analytics and global market intelligence can drive your growth.</p>
                
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <input type="text" placeholder="Subject">
                    <textarea rows="5" placeholder="Your Message" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
                
                <div class="social-links">
                    <a href="mailto:alphonsabenoy27@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
                    <a href="https://linkedin.com/in/alphonsajoseph" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
                    <a href="#" title="Portfolio"><i class="fas fa-briefcase"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Alphonsa Joseph. All rights reserved. | Bengaluru, India</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                const headerHeight = document.querySelector('header').offsetHeight;
                const targetPosition = target.offsetTop - headerHeight;
                
                window.scrollTo({
                    top: targetPosition,
                    behavior: 'smooth'
                });
            });
        });

        // Contact form handling
        document.querySelector('.contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! I will get back to you soon.');
            this.reset();
        });

        // Add scroll effect to header
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(255, 255, 255, 0.98)';
            } else {
                header.style.background = 'rgba(255, 255, 255, 0.95)';
            }
        });

        // Add typing effect to hero subtitle
        const subtitle = document.querySelector('.subtitle');
        const text = subtitle.textContent;
        subtitle.textContent = '';
        
        setTimeout(() => {
            let i = 0;
            const typeWriter = setInterval(() => {
                if (i < text.length) {
                    subtitle.textContent += text.charAt(i);
                    i++;
                } else {
                    clearInterval(typeWriter);
                }
            }, 100);
        }, 1000);
    </script>
</body>
</html>

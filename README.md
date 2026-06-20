<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdul Haseeb Khalil - Portfolio</title>
    <meta name="description" content="Portfolio of Abdul Haseeb Khalil - Data Analyst, Data Scientist, AI & Machine Learning Enthusiast">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0f172a;
            --surface-color: #1e293b;
            --primary-color: #3b82f6;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --accent: #60a5fa;
            --border-color: #334155;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Header */
        header {
            text-align: center;
            padding: 60px 0;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 40px;
            animation: fadeIn 1s ease-in-out;
        }

        h1 {
            font-size: 3rem;
            font-weight: 800;
            margin-bottom: 15px;
            background: linear-gradient(90deg, #60a5fa, #c084fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        h2, h3 {
            color: var(--text-main);
            margin-bottom: 20px;
        }

        h3.subtitle {
            font-weight: 400;
            color: var(--text-muted);
            font-size: 1.25rem;
            margin-bottom: 30px;
        }

        .badges {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .badges img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .badges img:hover {
            transform: translateY(-3px);
        }

        /* Sections */
        section {
            background-color: var(--surface-color);
            border-radius: 16px;
            padding: 40px;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px -10px rgba(0,0,0,0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px -10px rgba(0,0,0,0.6);
        }

        .section-title {
            font-size: 2rem;
            margin-bottom: 30px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Grid Layouts */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: rgba(255, 255, 255, 0.03);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 25px;
            transition: background-color 0.3s;
        }

        .card:hover {
            background-color: rgba(255, 255, 255, 0.05);
            border-color: var(--primary-color);
        }

        .card h3 {
            font-size: 1.3rem;
            color: var(--accent);
            margin-bottom: 10px;
        }

        ul {
            list-style-type: none;
        }

        ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
            color: var(--text-muted);
        }

        ul li::before {
            content: '▹';
            position: absolute;
            left: 0;
            color: var(--primary-color);
        }

        /* Social Links */
        .social-links {
            display: flex;
            gap: 20px;
            margin-top: 20px;
        }

        .social-links a {
            display: inline-block;
            transition: transform 0.3s;
        }

        .social-links a:hover {
            transform: scale(1.1);
        }

        .contact-info {
            margin-top: 20px;
            color: var(--text-muted);
        }

        .contact-info strong {
            color: var(--text-main);
        }

        /* Images */
        .stats-img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .quote {
            text-align: center;
            font-style: italic;
            color: var(--text-muted);
            font-size: 1.2rem;
            padding: 20px;
            border-left: 4px solid var(--primary-color);
            background: rgba(59, 130, 246, 0.1);
            border-radius: 0 8px 8px 0;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        a {
            color: var(--primary-color);
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Hi 👋, I'm Abdul Haseeb Khalil</h1>
        <h3 class="subtitle">Data Analyst • Data Scientist • AI & Machine Learning Enthusiast</h3>
        
        <div class="badges">
            <img src="https://komarev.com/ghpvc/?username=abdulhaseeebkhalil&label=Profile%20Views&color=blue&style=for-the-badge" alt="Profile Views" />
            <a href="https://github.com/abdulhaseeebkhalil" target="_blank">
                <img src="https://github-profile-trophy.vercel.app/?username=abdulhaseeebkhalil&theme=tokyonight&no-frame=true&row=1&column=7" alt="GitHub Trophies" />
            </a>
        </div>
    </header>

    <section>
        <h2 class="section-title">🚀 About Me</h2>
        <div class="card">
            <p>🎓 <strong>BS Computer Science Graduate</strong></p>
            <p>📊 Passionate about <strong>Data Analytics, Data Science, Machine Learning, NLP, and Generative AI</strong></p>
            <p>💼 Former Intern at <strong>PMRU (Punjab Municipal Regulatory Unit)</strong></p>
            <br>
            <p>🤖 <strong>Currently building AI-powered solutions including:</strong></p>
            <ul>
                <li>Government Knowledge Management & AI Assistant</li>
                <li>AI Resume Analysis & Job Matching System</li>
                <li>Abstractive Text Summarization System</li>
                <li>Bitcoin Price Prediction Models</li>
            </ul>
            <br>
            <p>🌱 <strong>Currently Learning:</strong> Advanced Data Science, Power BI & BI, Generative AI Applications, AI Agents & Multi-Agent Systems, RAG.</p>
            <br>
            <p>🎯 <strong>Goal:</strong> Become a Data Scientist & AI Engineer building impactful AI products</p>
        </div>
    </section>

    <section>
        <h2 class="section-title">🛠️ Tech Stack</h2>
        <div class="grid">
            <div class="card">
                <h3>👨‍💻 Programming Languages</h3>
                <p style="margin-bottom: 15px;">
                    <img src="https://skillicons.dev/icons?i=python,javascript,html,css,mysql" alt="Programming Languages" />
                </p>
            </div>
            
            <div class="card">
                <h3>📊 Data Science & ML</h3>
                <p style="margin-bottom: 15px;">
                    <img src="https://skillicons.dev/icons?i=tensorflow" alt="TensorFlow" />
                </p>
                <ul>
                    <li>Pandas, NumPy, Scikit-Learn</li>
                    <li>Machine Learning & Deep Learning</li>
                    <li>Data Analysis & Predictive Modeling</li>
                </ul>
            </div>

            <div class="card">
                <h3>🤖 AI & NLP</h3>
                <ul>
                    <li>Generative AI & LLM Applications</li>
                    <li>LangChain, RAG Systems, ChromaDB</li>
                    <li>Text Summarization & AI Agents</li>
                </ul>
            </div>

            <div class="card">
                <h3>📈 Data Visualization</h3>
                <ul>
                    <li>Power BI</li>
                    <li>Looker Studio</li>
                    <li>Matplotlib</li>
                    <li>Dashboard Design</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2 class="section-title">📌 Featured Projects</h2>
        <div class="grid">
            <div class="card">
                <h3>🏛️ Government Knowledge Management & AI Assistant</h3>
                <p>AI-powered document intelligence system for retrieving and analyzing government documents using RAG and LLMs.</p>
            </div>
            <div class="card">
                <h3>📄 AI Resume Analyzer</h3>
                <p>Automated resume screening and job matching system using NLP and Generative AI.</p>
            </div>
            <div class="card">
                <h3>📝 Abstractive Text Summarization</h3>
                <p>Deep learning-based NLP system that generates concise summaries from long articles using the CNN News Dataset.</p>
            </div>
            <div class="card">
                <h3>🎯 College Admission Prediction</h3>
                <p>Machine Learning model to predict graduate admission chances based on academic performance and application profile.</p>
            </div>
            <div class="card">
                <h3>₿ Bitcoin Price Prediction</h3>
                <p>Real-time cryptocurrency prediction system using Binance API and Machine Learning.</p>
            </div>
        </div>
    </section>

    <section>
        <h2 class="section-title">📜 Certifications</h2>
        <div class="card">
            <ul>
                <li>🏆 Machine Learning Specialization — Andrew Ng (Coursera)</li>
                <li>🏆 Data Science & Machine Learning Training</li>
                <li>🏆 Artificial Intelligence & NLP Projects</li>
            </ul>
        </div>
    </section>

    <section>
        <h2 class="section-title">📊 GitHub Analytics</h2>
        <div style="text-align: center;">
            <img class="stats-img" src="https://github-readme-stats.vercel.app/api?username=abdulhaseeebkhalil&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
            <br>
            <img class="stats-img" src="https://github-readme-streak-stats.herokuapp.com/?user=abdulhaseeebkhalil&theme=tokyonight" alt="GitHub Streak" />
            <br>
            <img class="stats-img" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdulhaseeebkhalil&layout=compact&theme=tokyonight" alt="Top Languages" />
        </div>
    </section>

    <section>
        <h2 class="section-title">🌐 Connect With Me</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/abdulhaseebkhankhalil/" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="40" width="50" />
            </a>
            <a href="https://facebook.com/abdulhaseebkhankhalil" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="facebook" height="40" width="50" />
            </a>
            <a href="https://instagram.com/abdulhaseebkk1" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="instagram" height="40" width="50" />
            </a>
        </div>
        <div class="contact-info">
            <p>📧 <strong>Email:</strong> <a href="mailto:abdulhaseeb13095@gmail.com">abdulhaseeb13095@gmail.com</a></p>
            <p>🐙 <strong>GitHub:</strong> <a href="https://github.com/abdulhaseeebkhalil" target="_blank">github.com/abdulhaseeebkhalil</a></p>
        </div>
    </section>

    <div class="quote">
        "Transforming Data into Insights and Ideas into Intelligent Solutions."
        <br><br>
        <span style="font-size: 0.9rem;">⭐ If you like my projects, don't forget to star the repositories.</span>
    </div>
</div>

</body>
</html>

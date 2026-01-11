# ⚔️ KARTAVYA JOSHI | Cybersecurity Elite

```
██╗  ██╗ █████╗ ██████╗ ████████╗ █████╗ ██╗   ██╗██╗   ██╗ █████╗ 
██║ ██╔╝██╔══██╗██╔══██╗╚══██╔══╝██╔══██╗██║   ██║██║   ██║██╔══██╗
█████╔╝ ███████║██████╔╝   ██║   ███████║██║   ██║██║   ██║███████║
██╔═██╗ ██╔══██║██╔══██╗   ██║   ██╔══██║╚██╗ ██╔╝██║   ██║██╔══██║
██║  ██╗██║  ██║██║  ██║   ██║   ██║  ██║ ╚████╔╝ ╚██████╔╝██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝  ╚═══╝   ╚═════╝ ╚═╝  ╚═╝
```


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kartavya Joshi - Cybersecurity</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(-45deg, #1a1a2e, #16213e, #0f3460, #533483);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: #e0e0e0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            min-height: 100vh;
            padding: 40px 20px;
            position: relative;
            overflow-x: hidden;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Animated background particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .particle {
            position: absolute;
            width: 2px;
            height: 2px;
            background: #00d4ff;
            border-radius: 50%;
            opacity: 0.5;
            box-shadow: 0 0 10px #00d4ff;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            position: relative;
            z-index: 10;
        }

        /* Main card */
        .main-card {
            background: rgba(15, 52, 96, 0.3);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(0, 212, 255, 0.2);
            border-radius: 20px;
            padding: 60px;
            text-align: center;
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            animation: slideInDown 0.8s ease;
        }

        @keyframes slideInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .main-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 212, 255, 0.1), transparent);
            animation: shimmer 3s infinite;
        }

        @keyframes shimmer {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .name {
            font-size: 3.5em;
            font-weight: 900;
            background: linear-gradient(135deg, #00d4ff, #7b2cbf);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 15px;
            animation: fadeInUp 1s ease;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .tagline {
            font-size: 1.3em;
            color: #00d4ff;
            margin-bottom: 30px;
            animation: fadeInUp 1.2s ease;
        }

        .description {
            color: #b0b0b0;
            font-size: 1.05em;
            line-height: 1.8;
            margin-bottom: 25px;
            animation: fadeInUp 1.4s ease;
        }

        /* Badges container */
        .badges-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
            margin-top: 30px;
        }

        .badge {
            background: rgba(0, 212, 255, 0.1);
            border: 1px solid rgba(0, 212, 255, 0.5);
            padding: 12px;
            border-radius: 10px;
            font-size: 0.9em;
            cursor: pointer;
            transition: all 0.3s ease;
            animation: fadeInUp 1.5s ease;
            animation-fill-mode: both;
        }

        .badge:nth-child(1) { animation-delay: 0.1s; }
        .badge:nth-child(2) { animation-delay: 0.2s; }
        .badge:nth-child(3) { animation-delay: 0.3s; }
        .badge:nth-child(4) { animation-delay: 0.4s; }
        .badge:nth-child(5) { animation-delay: 0.5s; }
        .badge:nth-child(6) { animation-delay: 0.6s; }

        .badge:hover {
            background: rgba(0, 212, 255, 0.2);
            border-color: rgba(123, 44, 191, 0.8);
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 212, 255, 0.3);
        }

        /* Section */
        .section {
            background: rgba(15, 52, 96, 0.2);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(0, 212, 255, 0.15);
            border-radius: 15px;
            padding: 40px;
            margin-bottom: 30px;
            animation: slideInUp 0.8s ease;
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .section-title {
            font-size: 1.8em;
            color: #00d4ff;
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .section-title::before {
            content: '';
            width: 4px;
            height: 30px;
            background: linear-gradient(180deg, #00d4ff, #7b2cbf);
            border-radius: 2px;
        }

        .stat-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .stat {
            background: rgba(0, 212, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid rgba(0, 212, 255, 0.3);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .stat:hover {
            transform: translateY(-5px);
            background: rgba(0, 212, 255, 0.15);
            border-color: rgba(123, 44, 191, 0.6);
            box-shadow: 0 8px 20px rgba(0, 212, 255, 0.2);
        }

        .stat-number {
            font-size: 2.2em;
            font-weight: bold;
            color: #00d4ff;
            display: block;
        }

        .stat-label {
            color: #b0b0b0;
            font-size: 0.9em;
            margin-top: 8px;
        }

        /* Skills */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .skill-item {
            background: rgba(123, 44, 191, 0.1);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid rgba(123, 44, 191, 0.3);
            transition: all 0.3s ease;
        }

        .skill-item:hover {
            transform: translateY(-5px);
            background: rgba(123, 44, 191, 0.15);
            border-color: rgba(0, 212, 255, 0.5);
            box-shadow: 0 8px 20px rgba(123, 44, 191, 0.2);
        }

        .skill-name {
            color: #7b2cbf;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .skill-bar {
            width: 100%;
            height: 6px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 3px;
            overflow: hidden;
            border: 1px solid rgba(0, 212, 255, 0.2);
        }

        .skill-bar-fill {
            height: 100%;
            background: linear-gradient(90deg, #00d4ff, #7b2cbf);
            border-radius: 3px;
            animation: fillBar 2s ease-in-out forwards;
        }

        @keyframes fillBar {
            from { width: 0%; }
            to { width: var(--percentage); }
        }

        /* Timeline */
        .timeline {
            position: relative;
            padding-left: 30px;
            margin-top: 20px;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 2px;
            background: linear-gradient(180deg, #00d4ff, #7b2cbf, transparent);
        }

        .timeline-item {
            margin-bottom: 25px;
            padding-bottom: 20px;
            position: relative;
            animation: slideInLeft 0.8s ease both;
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-20px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .timeline-item:nth-child(1) { animation-delay: 0.1s; }
        .timeline-item:nth-child(2) { animation-delay: 0.2s; }
        .timeline-item:nth-child(3) { animation-delay: 0.3s; }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: -36px;
            top: 2px;
            width: 12px;
            height: 12px;
            background: #00d4ff;
            border-radius: 50%;
            box-shadow: 0 0 15px #00d4ff;
        }

        .timeline-title {
            color: #00d4ff;
            font-weight: bold;
            font-size: 1.05em;
            margin-bottom: 5px;
        }

        .timeline-subtitle {
            color: #7b2cbf;
            font-size: 0.95em;
            margin-bottom: 8px;
        }

        .timeline-text {
            color: #b0b0b0;
            font-size: 0.9em;
            line-height: 1.6;
        }

        /* Contact buttons */
        .contact-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .btn {
            padding: 12px 30px;
            background: linear-gradient(135deg, #00d4ff, #7b2cbf);
            color: #000;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            text-decoration: none;
            font-size: 0.95em;
            box-shadow: 0 4px 15px rgba(0, 212, 255, 0.3);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 212, 255, 0.5);
        }

        .btn:active {
            transform: translateY(-1px);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .main-card {
                padding: 40px 25px;
            }

            .name {
                font-size: 2.5em;
            }

            .tagline {
                font-size: 1.1em;
            }

            .section {
                padding: 25px;
            }

            .section-title {
                font-size: 1.5em;
            }

            .badges-container {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>
    <div class="particles" id="particles"></div>

    <div class="container">
        <!-- Main Card -->
        <div class="main-card">
            <h1 class="name">KARTAVYA JOSHI</h1>
            <p class="tagline">🛡️ Cybersecurity Engineer | SOC Analyst | VAPT Expert</p>
            <p class="description">
                M.Tech Cybersecurity Student specializing in defensive security, threat detection, and cyber resilience. 
                Building secure systems across IT, OT, and emerging technologies.
            </p>

            <div class="badges-container">
                <div class="badge">🛡️ SOC Analyst</div>
                <div class="badge">🧪 VAPT (Web)</div>
                <div class="badge">🏭 OT/ICS</div>
                <div class="badge">🔐 ISC² Certified</div>
                <div class="badge">✅ GATE Qualified</div>
                <div class="badge">🚀 Blue Team</div>
            </div>
        </div>

        <!-- Stats Section -->
        <div class="section">
            <div class="section-title">📊 Achievements</div>
            <div class="stat-grid">
                <div class="stat">
                    <span class="stat-number">9.61</span>
                    <span class="stat-label">B.Tech CPI</span>
                </div>
                <div class="stat">
                    <span class="stat-number">10/10</span>
                    <span class="stat-label">Perfect SPI</span>
                </div>
                <div class="stat">
                    <span class="stat-number">4+</span>
                    <span class="stat-label">Internships</span>
                </div>
                <div class="stat">
                    <span class="stat-number">∞</span>
                    <span class="stat-label">Passion</span>
                </div>
            </div>
        </div>

        <!-- Skills Section -->
        <div class="section">
            <div class="section-title">💪 Core Skills</div>
            <div class="skills-grid">
                <div class="skill-item">
                    <div class="skill-name">Log Monitoring</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 85%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">OWASP Top 10</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 88%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">Threat Analysis</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 82%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">ICS/SCADA</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 75%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">Python</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 90%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <div class="skill-name">Linux/Windows</div>
                    <div class="skill-bar">
                        <div class="skill-bar-fill" style="--percentage: 85%"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Education Section -->
        <div class="section">
            <div class="section-title">🎓 Education</div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-title">M.Tech Cybersecurity</div>
                    <div class="timeline-subtitle">National Forensic Sciences University (NFSU)</div>
                    <div class="timeline-text">Ongoing • SOC operations, threat modeling, cyber resilience frameworks</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-title">B.Tech Computer Science</div>
                    <div class="timeline-subtitle">New LJ Institute of Engineering and Technology</div>
                    <div class="timeline-text">CPI: 9.61 | SPI: 10/10 | GATE Qualified</div>
                </div>
            </div>
        </div>

        <!-- Experience Section -->
        <div class="section">
            <div class="section-title">💼 Experience</div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-title">Cyber Resilience Intern</div>
                    <div class="timeline-subtitle">Bitsware (Current)</div>
                    <div class="timeline-text">SOC workflows, monitoring, threat response & incident handling</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-title">AI-ML-IoT-SAP Intern</div>
                    <div class="timeline-subtitle">Edunet Foundation</div>
                    <div class="timeline-text">Machine learning, IoT architectures, enterprise systems</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-title">Blockchain Intern</div>
                    <div class="timeline-subtitle">Web4next</div>
                    <div class="timeline-text">Solidity smart contracts, Ethereum deployment</div>
                </div>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="section" style="text-align: center;">
            <div class="section-title" style="justify-content: center;">🤝 Connect</div>
            <p style="color: #b0b0b0; margin-bottom: 20px;">Let's collaborate on cybersecurity projects & research</p>
            <div class="contact-buttons">
                <a href="mailto:joshi.kartavyaa@gmail.com" class="btn">📧 Email</a>
                <a href="https://linkedin.com/in/kartavyajoshi" class="btn" target="_blank">💼 LinkedIn</a>
                <a href="https://github.com/Kartavyajoshi" class="btn" target="_blank">🧑‍💻 GitHub</a>
            </div>
        </div>
    </div>

    <script>
        // Generate floating particles
        const container = document.getElementById('particles');
        for (let i = 0; i < 50; i++) {
            const particle = document.createElement('div');
            particle.className = 'particle';
            particle.style.left = Math.random() * window.innerWidth + 'px';
            particle.style.top = Math.random() * window.innerHeight + 'px';
            particle.style.animationDuration = (Math.random() * 20 + 10) + 's';
            particle.style.animationDelay = Math.random() * 5 + 's';
            particle.style.animation = `float ${Math.random() * 20 + 10}s infinite linear`;
            container.appendChild(particle);
        }

        // Float animation
        const style = document.createElement('style');
        style.innerHTML = `
            @keyframes float {
                0% { transform: translateY(0) translateX(0) scale(1); opacity: 0; }
                10% { opacity: 1; }
                90% { opacity: 1; }
                100% { transform: translateY(-100vh) translateX(100px) scale(0); opacity: 0; }
            }
        `;
        document.head.appendChild(style);
    </script>
</body>
</html>

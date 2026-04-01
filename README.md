# palestine
about Palestine
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Palestine: History and the World</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }
        header {
            background: linear-gradient(135deg, #8B0000, #DC143C);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        nav {
            background: rgba(255,255,255,0.95);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav li {
            margin: 0 1.5rem;
        }
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 25px;
            transition: all 0.3s ease;
        }
        nav a:hover {
            background: #DC143C;
            color: white;
            transform: translateY(-2px);
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        section {
            background: white;
            margin: 2rem 0;
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        h2 {
            color: #8B0000;
            font-size: 2rem;
            margin-bottom: 1rem;
            border-bottom: 3px solid #DC143C;
            padding-bottom: 0.5rem;
        }
        .timeline {
            position: relative;
            padding-left: 2rem;
        }
        .timeline-item {
            margin: 2rem 0;
            position: relative;
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -2rem;
            top: 0;
            width: 12px;
            height: 12px;
            background: #DC143C;
            border-radius: 50%;
        }
        .timeline-item:not(:last-child)::after {
            content: '';
            position: absolute;
            left: -1.8rem;
            top: 12px;
            bottom: -2rem;
            width: 2px;
            background: #DC143C;
        }
        .map-container {
            text-align: center;
            margin: 2rem 0;
        }
        .flag {
            width: 100px;
            height: 60px;
            background: linear-gradient(to bottom, #000000 0%, #000000 33.33%, #ffffff 33.33%, #ffffff 66.66%, #008000 66.66%, #008000 100%);
            border: 2px solid #333;
            margin: 1rem auto;
            border-radius: 5px;
        }
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        .stat-card {
            background: linear-gradient(135deg, #DC143C, #8B0000);
            color: white;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
        }
        .stat-number {
            font-size: 2rem;
            font-weight: bold;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }
        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            nav ul { flex-direction: column; align-items: center; }
            nav li { margin: 0.5rem 0; }
            .container { padding: 1rem; }
            section { padding: 1.5rem; margin: 1rem 0; }
        }
    </style>
</head>
<body>
    <header>
        <h1>🇵🇸 Palestine: Land of History & Resilience</h1>
        <p>Discover the rich history, culture, and global significance of Palestine</p>
    </header>

    <nav>
        <ul>
            <li><a href="#history">History</a></li>
            <li><a href="#geography">Geography</a></li>
            <li><a href="#culture">Culture</a></li>
            <li><a href="#modern">Modern Palestine</a></li>
            <li><a href="#world">Global Impact</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="history">
            <h2>📜 Historical Timeline</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <h3>~3000 BCE - Canaanite Period</h3>
                    <p>Palestine derives its name from the Philistines (Peleset), ancient sea peoples who settled the southern coast around 1200 BCE. The region was known as Canaan.</p>
                </div>
                <div class="timeline-item">
                    <h3>1000 BCE - Kingdom of Israel & Judah</h3>
                    <p>King David establishes Jerusalem as capital. The region becomes a center of Jewish, Christian, and later Islamic history.</p>
                </div>
                <div class="timeline-item">
                    <h3>63 BCE - Roman Rule</h3>
                    <p>Rome conquers the region, renaming it "Syria Palaestina" after the Philistines to diminish Jewish identity after revolts.</p>
                </div>
                <div class="timeline-item">
                    <h3>636 CE - Islamic Conquest</h3>
                    <p>Arab Muslim armies conquer the region from Byzantines. Jerusalem becomes third holiest city in Islam.</p>
                </div>
                <div class="timeline-item">
                    <h3>1516-1917 - Ottoman Empire</h3>
                    <p>Palestine remains under Ottoman rule for 400 years. Arab population grows alongside small Jewish communities.</p>
                </div>
                <div class="timeline-item">
                    <h3>1917 - Balfour Declaration</h3>
                    <p>Britain supports "national home for Jewish people" in Palestine while promising independence to Arabs.</p>
                </div>
                <div class="timeline-item">
                    <h3>1948 - Nakba ("Catastrophe")</h3>
                    <p>Creation of Israel leads to displacement of 750,000 Palestinians. West Bank & Gaza remain under Jordanian/Egyptian control.</p>
                </div>
                <div class="timeline-item">
                    <h3>1967 - Six-Day War</h3>
                    <p>Israel occupies West Bank, Gaza, East Jerusalem, Golan Heights, Sinai. Palestinian Liberation Organization (PLO) gains prominence.</p>
                </div>
                <div class="timeline-item">
                    <h3>1993 - Oslo Accords</h3>
                    <p>PLO recognizes Israel; Israel recognizes PLO. Palestinian Authority established with limited self-rule.</p>
                </div>
            </div>
        </section>

        <section id="geography">
            <h2>🗺️ Geography & Demographics</h2>
            <div class="map-container">
                <div class="flag"></div>
                <h3>Palestinian Flag</h3>
                <p>Black (Arab liberation), White (peace), Green (lands), Red (families who fought)</p>
            </div>
            
            <div class="stats">
                <div class="stat-card">
                    <div class="stat-number">14,000 km²</div>
                    <p>Total claimed territory<br>(West Bank + Gaza + East Jerusalem)</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">5.5M</div>
                    <p>Population (2024)</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">2.3M</div>
                    <p>Gaza Strip</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">3M</div>
                    <p>West Bank</p>
                </div>
            </div>
        </section>

        <section id="culture">
            <h2>🎭 Culture & Heritage</h2>
            <ul style="list-style: none; padding: 0;">
                <li style="margin: 1rem 0; padding: 1rem; background: #f8f9fa; border-radius: 8px;">
                    <strong>🕌 Al-Aqsa Mosque</strong> - Third holiest site in Islam, located in Jerusalem
                </li>
                <li style="margin: 1rem 0; padding: 1rem; background: #f8f9fa; border-radius: 8px;">
                    <strong>✡️ Western Wall</strong> - Holiest site in Judaism, adjacent to Al-Aqsa
                </li>
                <li style="margin: 1rem 0; padding: 1rem; background: #f8f9fa; border-radius: 8px;">
                    <strong>🕊️ Church of the Holy Sepulchre</strong> - Traditional site of Jesus' crucifixion and burial
                </li>
                <li style="margin: 1rem 0; padding: 1rem; background: #f8f9fa; border-radius: 8px;">
                    <strong>🍽️ Cuisine:</strong> Falafel, hummus, maqluba, knafeh, musakhan
                </li>
                <li style="margin: 1rem 0; padding: 1rem; background: #f8f9fa; border-radius: 8px;">
                    <strong>🎶 Music:</strong> Traditional dabke folk dance, oud music
                </li>
            </ul>
        </section>

        <section id="modern">
            <h2>🏛️ Modern Palestinian Territories</h2>
            <p><strong>Palestinian Authority (PA)</strong> governs parts of West Bank. Capital: Ramallah (de facto).</p>
            <p><strong>Hamas</strong> governs Gaza Strip since 2007 elections.</p>
            <p><strong>East Jerusalem</strong> claimed as capital by Palestinians, annexed by Israel.</p>
            <p>Key issues: Settlements, security barrier, right of return, Jerusalem status, borders.</p>
        </section>

        <section id="world">
            <h2>🌍 Palestine in the World</h2>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin-top: 1.5rem;">
                <div style="background: #f8f9fa; padding: 1.5rem; border-radius: 10px;">
                    <h4>🗳️ UN Status</h4>
                    <p>Non-member observer state since 2012. 139/193 UN members recognize Palestine.</p>
                </div>
                <div style="background: #f8f9fa; padding: 1.5rem; border-radius: 10px;">
                    <h4>🏛️ International Bodies</h4>
                    <p>Member of Arab League, OIC, UNESCO. Observer in WTO, IMF.</p>
                </div>
                <div style="background: #f8f9fa; padding: 1.5rem; border-radius: 10px;">
                    <h4>💰 Economy</h4>
                    <p>2023 GDP: ~$19B. Main exports: stone, agriculture. High unemployment (25-45%).</p>
                </div>
                <div style="background: #f8f9fa; padding: 1.5rem; border-radius: 10px;">
                    <h4>📚 Diaspora</h4>
                    <p>6-7 million Palestinians live abroad, mainly in Jordan, Lebanon, Syria, Chile, US.</p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Palestine History Website | Educational Resource | Sources: UN, Britannica, Palestinian Central Bureau of Statistics</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add scroll animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        });

        document.querySelectorAll('section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(30px)';
            section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(section);
        });
    </script>
</body>
</html>
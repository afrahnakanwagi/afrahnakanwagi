<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afrah Nakanwagi's GitHub Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #e0e0e0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            background: rgba(15, 12, 41, 0.9);
            border-radius: 15px;
            padding: 20px;
            width: 100%;
            max-width: 900px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            position: relative;
            overflow: hidden;
        }
        .header {
            text-align: center;
            padding: 20px 0;
            border-bottom: 2px solid #5D5CDE;
        }
        .header h1 {
            margin: 0;
            font-size: 2em;
            color: #5D5CDE;
            animation: fadeIn 2s ease-in-out;
        }
        .profile {
            display: flex;
            align-items: center;
            padding: 20px;
            position: relative;
        }
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #5D5CDE;
            margin-right: 20px;
            animation: float 3s infinite ease-in-out;
        }
        .profile-info h2 {
            margin: 0;
            font-size: 1.5em;
            color: #fff;
        }
        .profile-info p {
            margin: 5px 0;
            color: #b0b0b0;
            font-size: 0.9em;
        }
        .stats {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }
        .stat-btn {
            background: #5D5CDE;
            color: #fff;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.8em;
            cursor: default;
        }
        .section {
            margin: 20px 0;
            padding: 15px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .section:hover {
            transform: translateY(-5px);
        }
        .section h3 {
            color: #5D5CDE;
            margin-top: 0;
            border-bottom: 1px solid #5D5CDE;
            padding-bottom: 5px;
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .tech-item {
            background: #5D5CDE;
            color: #fff;
            padding: 5px 10px;
            border-radius: 20px;
            animation: pulse 2s infinite;
        }
        .project {
            margin: 10px 0;
            padding: 10px;
            background: rgba(93, 92, 222, 0.1);
            border-left: 4px solid #5D5CDE;
            transition: all 0.3s ease;
        }
        .project:hover {
            background: rgba(93, 92, 222, 0.2);
        }
        .animated-character {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 80px;
            height: 80px;
            background: url('https://i.imgur.com/placeholder-character.png') no-repeat;
            animation: move 5s infinite linear;
            opacity: 0.7;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        @keyframes move {
            0% { transform: translateX(0); }
            50% { transform: translateX(50px) rotate(10deg); }
            100% { transform: translateX(0); }
        }
        @media (max-width: 600px) {
            .profile {
                flex-direction: column;
                text-align: center;
            }
            .profile-img {
                margin-bottom: 10px;
            }
            .profile-info {
                margin-left: 0;
            }
            .animated-character {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>👋 Hi, I'm Afrah Nakanwagi</h1>
        </div>
        <div class="profile">
            <img src="https://via.placeholder.com/120" alt="Afrah Nakanwagi" class="profile-img">
            <div class="profile-info">
                <h2>Afrah Nakanwagi</h2>
                <p>Software Developer & UI/UX Designer | Kampala, Uganda</p>
                <p>She/Her | Followers: 150 | Following: 50</p>
                <div class="stats">
                    <span class="stat-btn">👥 150</span>
                    <span class="stat-btn">⭐ 50</span>
                    <span class="stat-btn">📊 10</span>
                </div>
            </div>
        </div>
        <div class="section">
            <h3>🚀 About Me</h3>
            <p>I'm a passionate Software Developer and UI/UX Designer based in Kampala, Uganda. With over a year of experience, I craft user-centric, responsive, and innovative digital solutions that blend technical expertise with creative design. My mission is to build seamless, impactful applications that solve real-world problems.</p>
            <p><strong>Fun Fact:</strong> I once designed an entire Agro-Tourism website in Figma in just 48 hours to meet a tight deadline, and it was a hit with the client! When I'm not coding or designing, you can find me exploring Kampala's vibrant food scene or sketching new UI ideas.</p>
        </div>
        <div class="section">
            <h3>🔭 What I'm Working On</h3>
            <ul>
                <li>Developing web applications with Django, Python, and React.js to streamline business operations.</li>
                <li>Designing intuitive UI/UX interfaces using Figma to enhance user experiences.</li>
                <li>Leading team projects to create dynamic platforms like Xtreative Market, connecting local creatives with customers.</li>
                <li>Exploring advanced backend development techniques with RESTful APIs and PostgreSQL.</li>
            </ul>
        </div>
        <div class="section">
            <h3>🌱 What I'm Learning</h3>
            <ul>
                <li>Deepening my expertise in React.js for scalable frontend development.</li>
                <li>Enhancing my skills in CI/CD pipelines to improve deployment workflows.</li>
                <li>Experimenting with advanced Python frameworks to build robust backend systems.</li>
                <li>Staying updated with the latest UI/UX trends to create modern, user-friendly designs.</li>
            </ul>
        </div>
        <div class="section">
            <h3>🛠️ My Tech Stack</h3>
            <div class="tech-stack">
                <span class="tech-item">HTML5</span>
                <span class="tech-item">CSS</span>
                <span class="tech-item">React.js</span>
                <span class="tech-item">WordPress</span>
                <span class="tech-item">Python</span>
                <span class="tech-item">Django</span>
                <span class="tech-item">RESTful APIs</span>
                <span class="tech-item">PostgreSQL</span>
                <span class="tech-item">Figma</span>
                <span class="tech-item">Git</span>
                <span class="tech-item">CI/CD</span>
            </div>
        </div>
        <div class="section">
            <h3>🏆 Achievements</h3>
            <ul>
                <li>3+ Projects Completed: Including a grocery inventory system and e-commerce platforms.</li>
                <li>4 Certifications Earned: Including CSE Python (Refactory Academy) and UI/UX Design Basics (Simplilearn).</li>
                <li>Led 2 Team Projects: Successfully guided a team of 7 to develop Xtreative Market.</li>
            </ul>
        </div>
        <div class="section">
            <h3>📫 How to Reach Me</h3>
            <p><a href="mailto:afrahnakanwagi@gmail.com" style="color: #5D5CDE;">afrahnakanwagi@gmail.com</a> | <a href="tel:+256768917360" style="color: #5D5CDE;">+256 768917360</a></p>
            <p><a href="https://www.linkedin.com/in/afrah-nakanwagi-b829a5314/" style="color: #5D5CDE;">LinkedIn</a> | <a href="https://x.com/naiyosh28792" style="color: #5D5CDE;">X: @naiyosh28792</a> | <a href="https://github.com/afrahnakanwagi" style="color: #5D5CDE;">GitHub</a></p>
        </div>
        <div class="section">
            <h3>🚀 Let's Connect</h3>
            <p>Let's build something amazing together! Feel free to explore my repositories or reach out to discuss your next project.</p>
        </div>
    </div>
    <div class="animated-character"></div>
</body>
</html>

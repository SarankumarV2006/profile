# profile
A simple and responsive Personal Profile Card created using HTML and CSS. This project is designed to practice basic HTML elements and CSS styling concepts.
# PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Personal Profile Card</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: radial-gradient(circle at top left, #0f172a 0%, #142a55 40%, #060b1e 100%);
            color: #e2e8f0;
            min-height: 100vh;

            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Profile Card */
        .profile-card {
            width: 350px;
            background: rgba(255, 255, 255, 0.09);
            padding: 32px;
            text-align: center;
            border-radius: 28px;
            border: 1px solid rgba(255, 255, 255, 0.18);
            box-shadow: 0 24px 70px rgba(6, 11, 30, 0.45);
            backdrop-filter: blur(18px);
            -webkit-backdrop-filter: blur(18px);

            transition: 0.3s ease;
        }

        /* Hover Animation */
        .profile-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
        }

        /* Profile Image */
        .profile-card img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #4285f4;
            margin-bottom: 15px;
        }

        /* Name */
        .profile-card h1 {
            font-size: 26px;
            color: #eff6ff;
            margin-bottom: 5px;
        }

        /* Introduction */
        .intro {
            color: #cbd5e1;
            font-size: 15px;
            margin-bottom: 20px;
        }

        /* About */
        .profile-card h2 {
            font-size: 18px;
            color: #dbeafe;
            margin-bottom: 8px;
        }

        .about {
            color: #cbd5e1;
            font-size: 14px;
            margin-bottom: 20px;
        }

        /* Hobbies */
        .hobbies {
            text-align: left;
            margin: 0 auto 20px;
            width: 180px;
            color: #f9f5f5;
        }

        .hobbies li {
            margin-bottom: 6px;
        }

        /* Contact Button */
        .contact-btn {
            border: none;
            background: linear-gradient(135deg, rgba(96, 165, 250, 0.96), rgba(59, 130, 246, 0.96));
            color: #f8fafc;
            padding: 12px 25px;
            border-radius: 25px;
            font-size: 15px;
            font-family: inherit;
            cursor: pointer;
            box-shadow: 0 12px 24px rgba(59, 130, 246, 0.24);
            transition: 0.3s ease;
        }

        .contact-btn:hover {
            background: linear-gradient(135deg, rgba(59, 130, 246, 0.96), rgba(37, 99, 235, 0.96));
            transform: scale(1.05);
        }

        /* Responsive Design */
        @media (max-width: 480px) {
            .profile-card {
                width: 90%;
                padding: 25px;
            }
        }
    </style>
</head>

<body>

    <div class="profile-card">

        <!-- Profile Image -->
        <img src="profile.jpg" alt="Profile Image">

        <!-- Name -->
        <h1>Sarankumar V</h1>

        <!-- Introduction -->
        <p class="intro">Student | Web Developer | UIUX Designer</p>

        <!-- About Me -->
        <h2>About Me</h2>

        <p class="about">
            I enjoy learning HTML, CSS and creating beautiful websites.
        </p>

        <!-- Hobbies -->
        <h2>Hobbies</h2>

        <ul class="hobbies">
            <li>Reading</li>
            <li>Music</li>
            <li>Coding</li>
            <li>Design</li>
        </ul>

        <!-- Contact Button -->
        <button class="contact-btn">Contact Me</button>

    </div>

</body>
</html>
```
OUTPUT
![alt text](<Screenshot 2026-08-03 124838.png>)
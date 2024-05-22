<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My PortOfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <img src="profile-photo.jpg" alt="Profile Photo" class="profile-photo">
            <h1>Nama Anda</h1>
            <p>About Me: Singkat tentang diri Anda.</p>
        </header>
        <section>
            <h2>Experience</h2>
            <ul>
                <li><strong>Job Title</strong> - Company Name (Year - Year)</li>
                <li><strong>Job Title</strong> - Company Name (Year - Year)</li>
                <!-- Tambahkan pengalaman lain di sini -->
            </ul>
        </section>
        <section>
            <h2>Education</h2>
            <ul>
                <li><strong>Degree</strong> - Institution Name (Year - Year)</li>
                <li><strong>Degree</strong> - Institution Name (Year - Year)</li>
                <!-- Tambahkan pendidikan lain di sini -->
            </ul>
        </section>
        <section>
            <h2>Social Media</h2>
            <ul class="social-media">
                <li><a href="https://twitter.com/username">Twitter</a></li>
                <li><a href="https://linkedin.com/in/username">LinkedIn</a></li>
                <!-- Tambahkan link media sosial lain di sini -->
            </ul>
        </section>
        <section>
            <h2>Organizations & Volunteering Experiences</h2>
            <ul>
                <li><strong>Role</strong> - Organization Name (Year - Year)</li>
                <li><strong>Role</strong> - Organization Name (Year - Year)</li>
                <!-- Tambahkan pengalaman organisasi lain di sini -->
            </ul>
        </section>
        <footer>
            <h2>Skills</h2>
            <ul>
                <li>Skill 1</li>
                <li>Skill 2</li>
                <!-- Tambahkan keterampilan lain di sini -->
            </ul>
        </footer>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #77ab59 3px solid;
}

header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    display: block;
    margin: 0 auto;
}

header h1 {
    text-align: center;
    margin: 0;
    padding: 10px 0;
}

header p {
    text-align: center;
    margin: 10px 0;
    font-size: 1.2em;
}

section {
    margin: 20px 0;
    padding: 20px;
    background: #fff;
    border: 1px solid #ccc;
}

h2 {
    text-align: center;
    color: #77ab59;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    padding: 10px 0;
    border-bottom: 1px #ccc dotted;
}

ul li:last-child {
    border-bottom: none;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
}

footer ul {
    list-style: none;
    padding: 0;
}

footer ul li {
    display: inline;
    margin: 0 10px;
}

footer ul li a {
    color: #fff;
    text-decoration: none;
}

footer ul li a:hover {
    text-decoration: underline;
}


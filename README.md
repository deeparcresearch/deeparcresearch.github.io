<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeepARC Research Group</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white; /* Fondo blanco */
            color: black; /* Texto negro */
        }
        header {
            background-color: white; /* Fondo blanco */
            color: black; /* Texto negro */
            padding: 20px 0;
            text-align: center;
            position: relative;
        }
        header img {
            position: absolute;
            left: 20px;
            top: 20px;
            width: 60px;
            height: 60px;
        }
        footer {
            background-color: white; /* Fondo blanco */
            color: black; /* Texto negro */
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .container {
            margin-top: 20px;
        }
        h1, h2, h3, h4, h5 {
            color: black; /* Títulos en negro */
        }
        .member-photo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }
        .funding {
            font-size: 0.9em;
            color: gray;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="DeepARC Logo">
        <h1>DeepARC Research Group</h1>
        <p>This research group is partially funded by Yachay Tech University, and Universidad Internacional del Ecuador (UIDE).</p>
    </header>
    <div class="container">
        <div class="funding">
            <p>Innovating the Future with Artificial Intelligence</p>
        </div>
        <section id="publications">
            <h2>Publications</h2>
            <p>Explore our latest research articles:</p>
            <h3>Journals</h3>
            <ul>
                <li>
                    <h4><a href="https://doi.org/example1" target="_blank">Title of Journal Publication 1</a></h4>
                    <p>Description of the publication. <a href="https://github.com/DeepARC/CodeExample1" target="_blank">Code Repository</a></p>
                </li>
                <li>
                    <h4><a href="https://doi.org/example2" target="_blank">Title of Journal Publication 2</a></h4>
                    <p>Description of the publication. <a href="https://github.com/DeepARC/CodeExample2" target="_blank">Code Repository</a></p>
                </li>
            </ul>
            <h3>Conferences</h3>
            <ul>
                <li>
                    <h4><a href="https://doi.org/conference1" target="_blank">Title of Conference Presentation 1</a></h4>
                    <p>Description of the conference. <a href="slides/conference1-slides.pdf" target="_blank">Download Slides</a></p>
                </li>
                <li>
                    <h4><a href="https://doi.org/conference2" target="_blank">Title of Conference Presentation 2</a></h4>
                    <p>Description of the conference. <a href="slides/conference2-slides.pdf" target="_blank">Download Slides</a></p>
                </li>
            </ul>
        </section>
        <hr>
        <section id="members">
            <h2>Team Members</h2>
            <p>Meet the researchers behind DeepARC.</p>
            <div class="row">
                <div class="col-md-4 text-center">
                    <img src="member1.jpg" alt="Member 1" class="member-photo">
                    <h5>Eugenio Morocho</h5>
                    <p>Coordinator of DeepARC Research Group.</p>
                </div>
                <div class="col-md-4 text-center">
                    <img src="member2.jpg" alt="Member 2" class="member-photo">
                    <h5>Member Name</h5>
                    <p>Researcher in AI and Wireless Networks.</p>
                </div>
                <div class="col-md-4 text-center">
                    <img src="member3.jpg" alt="Member 3" class="member-photo">
                    <h5>Member Name</h5>
                    <p>Specialist in Computer Vision.</p>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 DeepARC Research Group</p>
    </footer>
</body>
</html>

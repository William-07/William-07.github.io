# William-07.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Preview Blocks</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f7f7f7;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .project-card {
            width: 300px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            margin: 15px;
            text-decoration: none; /* Remove underline */
            color: inherit; /* Inherit text color */
            transition: transform 0.3s;
        }
        .project-card:hover {
            transform: translateY(-10px);
        }
        .project-image {
            width: 100%;
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        .project-content {
            padding: 15px;
        }
        .project-title {
            font-size: 20px;
            font-weight: bold;
            margin: 0 0 10px;
        }
        .project-subtitle {
            color: #555;
            margin: 0 0 10px;
            font-size: 14px;
        }
        .project-description {
            font-size: 14px;
            color: #333;
        }
    </style>
</head>
<body>
    <!-- Project 1 -->
    <a href="project1.html" class="project-card">
        <div class="project-image" style="background-image: url('project1.jpg');"></div>
        <div class="project-content">
            <div class="project-title">Project 1 Title</div>
            <div class="project-subtitle">Subtitle or Pricing Info</div>
            <div class="project-description">
                Brief description or abstract of the project goes here.
            </div>
        </div>
    </a>

    <!-- Project 2 -->
    <a href="project2.html" class="project-card">
        <div class="project-image" style="background-image: url('project2.jpg');"></div>
        <div class="project-content">
            <div class="project-title">Project 2 Title</div>
            <div class="project-subtitle">Subtitle or Pricing Info</div>
            <div class="project-description">
                Brief description or abstract of the project goes here.
            </div>
        </div>
    </a>

    <!-- Project 3 -->
    <a href="project3.html" class="project-card">
        <div class="project-image" style="background-image: url('project3.jpg');"></div>
        <div class="project-content">
            <div class="project-title">Project 3 Title</div>
            <div class="project-subtitle">Subtitle or Pricing Info</div>
            <div class="project-description">
                Brief description or abstract of the project goes here.
            </div>
        </div>
    </a>
</body>
</html>

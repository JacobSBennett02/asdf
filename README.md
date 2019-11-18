<!DOCTYPE HTML>
<html>
    <head>
        <title>Jacob's Website</title>
        <style>
            body {
                background: rgb(120, 200, 255);
                color: rgb(45, 45, 45);
                padding: 10px;
                font-family: arial;
            }
            header {
                font-size: 1.5em;
                font-weight: bold;
            }
            #all-contents {
                max-width: 800px;
                margin: auto;
            }

            /* navigation menu */
            nav {
                background: rgb(50, 50, 50);
                margin: 0 auto;
                margin-bottom: 20px;
                display: flex;
                padding: 10px;
            }
            nav header {
                display: flex;
                align-items: center;
                color: rgb(255, 255, 255);
                flex: 1;
            }
            nav ul {
                list-style-image: none;
            }
            nav li {
                display: inline-block;
                padding: 0 10px;
            }
            nav a {
                text-decoration: none;
                color: #fff;
            }

            /* main container area beneath menu */
            main {
                background: rgb(150, 150, 255);
                display: flex;
            }
            .sidebar {
                margin-right: 25px;
                padding: 10px;
            }
            .sidebar img {
                width: 200px;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
            .interests header {
                font-size: 1.25em;
            }
        </style>
    </head>  
    
    <body>
        <div id="all-contents">
            <nav>
                <header>Jacob's Website</header>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="portfolio.html">Portfolio</a></li>
                </ul>
            </nav>
            <main>
                <div class="sidebar">
                    <img src="data:image/jpeg;base64,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">
                </div> 
                <div class="content">
                    <h1>
                        Jacob Bennett
                    </h1>
                    <p>
                        Professor in the study of Baljeet
                    </p>
                    <section class="facts">
                        <header>Interests</header>
                        <ul>
                            <li>Soccer.</li>
                            <li>The bus Rosa Parks wouldn't sit on.</li>
                            <li>The Axis powers.</li>
                        </ul>
                    </section>
                
                </div>
            </main>
        </div>    
    </body>
</html>
<!DOCTYPE HTML>
<html>   
    <head>
        <title>Jacob's Website</title>
        <style type="text/css">
            body {
                background: rgb(125, 198, 205);
                color: rgb(45, 45, 45);
                padding: 10px;
                font-family: arial;
            }
            header {
                font-size: 1.5em;
                font-weight: bold;
            }
            h1 {
                margin: 10px;
            }
            #all-contents {
                max-width: 800px;
                margin: auto;
            }

            /* navigation menu */
            nav {
                background: rgb(239, 80, 41);
                margin: 0 auto;
                display: flex;
                padding: 10px;
            }
            nav header {
                display: flex;
                align-items: center;
                color: rgb(255, 255, 255);
                flex: 1;
            }
            nav ul {
                list-style-image: none;
            }
            nav li {
                display: inline-block;
                padding: 0 10px;
            }
            nav a {
                text-decoration: none;
                color: #fff;
            }

            /* main container area beneath menu */
            main {
                background: rgb(245, 238, 219);
                display: flex;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
            /* portfolio styles */
            #portfolio {
                list-style-type: none;
                padding-left: 0;
            }

            #portfolio li {
                background: #fff;
                padding: 10px;
                border-radius: 10px;
                margin-bottom: 10px;
            }

            #portfolio li:hover {
                background: #eee;
            } 

            #portfolio a {
                text-decoration: none;
                color: #454545;
            }
        </style>
    </head>
    
    <body>
        <div id="all content">
            <nav>
                <header>Daschund shrine</header>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="portfolio.html">Portfolio</a></li>
                </ul>
            </nav>
            <main>
                <div class="content">
                    <h1>Portfolio</h1>
                    <ul id="portfolio"></ul>
                </div>
            </main>
        </div>
    </body>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
 <script id="portfolioScript">$(document).ready(function() {$.getJSON('projects/projects.json').then(function(data) { data.projects.forEach(function(project){ $('#portfolio').append('<li><a href="projects/' + project.name + '/">' + project.title + ' : ' + project.description + '</a></li>'); }); }); });</script>


</html>    

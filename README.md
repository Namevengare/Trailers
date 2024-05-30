<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trailer Movies - README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
            line-height: 1.5;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3, h4, h5, h6 {
            font-weight: bold;
        }
        code {
            background-color: #f3f3f3;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background-color: #f3f3f3;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>Trailer Movies</h1>
    <p>This is a React web application that allows you to search and watch movie trailers using The Movie Database (TMDb) API.</p>

    <h2>Requirements</h2>
    <ul>
        <li>Node.js (version 12 or higher)</li>
        <li>npm (usually installed with Node.js)</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone this repository to your local machine:
            <pre><code>git clone https://github.com/your-username/trailer-movies.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd trailer-movies</code></pre>
        </li>
        <li>Install project dependencies:
            <pre><code>npm install</code></pre>
        </li>
    </ol>

    <h2>Running the Application</h2>
    <p>To run the application in development mode, use the following command:</p>
    <pre><code>npm start</code></pre>
    <p>This will start the application in development mode and automatically open your default web browser at <a href="http://localhost:3000">http://localhost:3000</a>.</p>

    <h2>Usage</h2>
    <ol>
        <li>On the main page, you'll see a list of popular movies.</li>
        <li>You can search for specific movies using the search bar at the top.</li>
        <li>Click on a movie to see more details and its official trailer (if available).</li>
        <li>If a trailer is available, you can play it by clicking the "Play Trailer" button.</li>
        <li>To close the trailer, click the "Close" button.</li>
    </ol>

    <h2>Credits</h2>
    <ul>
        <li>This application uses the <a href="https://www.themoviedb.org/">The Movie Database (TMDb)</a> API to fetch movie and trailer information.</li>
        <li>The video player used is <a href="https://github.com/tjallingt/react-youtube">react-youtube</a>.</li>
        <li>The design and CSS styles were created by the application author.</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
</body>
</html>

# style.css
/* Reset default margin and padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Global Styles */
body {
    font-family: 'Poppins', sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 20px; /* Adding padding to the body to prevent sticking at the top */
    display: flex;
    justify-content: center;
    align-items: flex-start; /* Aligns content towards the top */
    min-height: 100vh;
}

/* Main Container */
section {
    background-color: white;
    padding: 2rem;
    width: 90%;
    max-width: 800px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    text-align: center;
    margin-top: 30px; /* Adding margin to ensure there's space from the top */
}

/* Header */
header {
    background-color: #4CAF50;
    color: white;
    padding: 2rem;
    border-radius: 8px;
    margin-bottom: 1.5rem;
}

header h1 {
    font-size: 2rem;
    margin: 0;
}

header p {
    margin: 1rem 0 0;
}

/* Section Titles */
h2 {
    color: #4CAF50;
    margin-bottom: 1rem;
}

/* List Items */
ul {
    list-style: none;
    padding: 0;
}

ul li {
    background-color: #e7f7e7;
    margin-bottom: 0.5rem;
    padding: 0.75rem;
    border-radius: 5px;
}

/* Links */
a {
    color: #4CAF50;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}

/* Definition List */
dl dt {
    font-weight: bold;
    color: #333;
    margin-top: 1rem;
}

dl dd {
    margin-left: 1.5rem;
    color: #666;
}

/* Blockquote */
blockquote {
    font-style: italic;
    color: #555;
    border-left: 4px solid #4CAF50;
    padding-left: 1rem;
    margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 600px) {
    section {
        padding: 1.5rem;
    }

    header {
        padding: 1.5rem;
    }
}

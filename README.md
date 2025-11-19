# Rhulani123
WEB FINAL PART 3
IN MY part 3 i changes any mistakes from part 2 i make sure that my devices works on devices but my first page has issues then after that I create the js codes and it changes my website
i did the js for each and every page and run it

example of part 2
/* General Styles */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    background-color: skyblue;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background: #0077b6;
    color: white;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    font-size: 3rem;
    margin: 0;
}

header p {
    font-size: 1.2rem;
    margin-top: 5px;
}

/* Header Image */
header img {
    display: block;
    margin: 20px auto;
    max-width: 100%;
    height: auto;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.3);
}

/* Navigation */
nav {
    margin-top: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #ffd700;
}

/* About Section */
main#about {
    background: rgba(255,255,255,0.9);
    margin: 30px auto;
    padding: 30px;
    max-width: 900px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

main#about h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 15px;
    color: #0077b6;
}

main#about p {
    font-size: 1.1rem;
    margin-bottom: 15px;
    text-align: justify;
}

main#about ul {
    padding-left: 20px;
    margin: 15px 0;
}

main#about ul li {
    margin-bottom: 8px;
    font-weight: bold;
    color: #0077b6;
}

/* Footer */
footer {
    text-align: center;
    background: #0077b6;
    color: white;
    padding: 15px 0;
    margin-top: 40px;
    border-top: 2px solid #023e8a;
}

/* Responsive Styles */
@media (max-width: 768px) {
    header h1 { font-size: 2.3rem; }
    nav a { font-size: 1rem; }
    main#about { padding: 20px; }
    main#about p { font-size: 1rem; }
}

@media (max-width: 480px) {
    header h1 { font-size: 1.8rem; }
    header p { font-size: 1rem; }
    nav { flex-direction: column; gap: 10px; }
    nav a { display: block; font-size: 1rem; }
    main#about h2 { font-size: 1.6rem; }
    main#about p { font-size: 0.95rem; }
}

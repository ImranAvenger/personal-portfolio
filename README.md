# Personal Portfolio — Frontend Practice

This repository contains a small personal-portfolio site built with plain HTML and CSS. It's a learning / showcase project focused on creating a clean, responsive layout without JavaScript.

Purpose
 - Practice semantic HTML structure and CSS layout (flexbox, responsiveness).
 - Create a simple portfolio page that lists projects, education, work experience and reviews.

What you'll find
 - `index.html` — home page / portfolio layout
 - `projects.html`, `articles.html`, `contact.html` — other pages (basic HTML)
 - `style.css` — site styles, responsive rules and color-scheme handling

Development notes
 - No build step required — open `index.html` in a browser to view.
 - The CSS uses a small mobile-first media query at `@media (max-width: 600px)` to stack columns vertically.

Challenge / reference
 - This project was built following the roadmap.sh challenge: https://roadmap.sh/projects/portfolio-website

How to view locally
1. Clone the repository (if not already):

	git clone https://github.com/ImranAvenger/personal-portfolio.git

2. Open `index.html` in your browser, or serve the folder with a static server:

	# using Python 3
	python3 -m http.server 8000

Then visit `http://localhost:8000`.

Contributing
 - This is a simple portfolio template — feel free to open issues or PRs to improve accessibility, add tests, or convert styles to a CSS preprocessor.

License
 - See the `LICENSE` file in the repository.

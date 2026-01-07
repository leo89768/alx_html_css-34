🌐 alx_html_css
This repository contains a beginner friendly front end portfolio project. It demonstrates semantic HTML, responsive CSS, and Git workflows. The project includes a homepage and a tweets page, styled with a combination of base.css (global resets and typography) and styles.css (visual design and layout).
________________________________________
📂 Project Structure
project-root/
│
├── index.html      # Homepage with portfolio intro and feature cards
├── tweets.html     # Tweets page with updates from coding journey
├── base.css        # Global reset, fonts, colors, responsive rules
├── styles.css      # Visual design, layout, cards, branding
________________________________________
🖥️ File Overview
1. index.html
•	Purpose: Homepage introducing the portfolio.
•	Features: 
o	Semantic structure (<header>, <main>, <article>, <aside>, <footer>).
o	Navigation menu linking to tweets.html.
o	Feature cards highlighting accessibility, incremental learning, and connected pages.
o	Partner logo figure with caption.
o	Footer with author attribution and GitHub link.
________________________________________
2. tweets.html
•	Purpose: Secondary page showing updates and progress.
•	Features: 
o	Simple navigation back to index.html.
o	Article section with heading and list of daily updates.
o	Aside placeholder for future comment thread.
o	Footer with author attribution.
________________________________________
3. base.css
•	Purpose: Foundation stylesheet applied across all pages.
•	Features: 
o	CSS reset for consistent cross browser rendering.
o	Global font imports (Josefin Sans, Yeseva One).
o	Typography rules for headings, paragraphs, and links.
o	Header, footer, and aside base styling.
o	Responsive rules (@media max-width: 800px) and smartphone overrides via body.works_on_smartphone.
________________________________________
4. styles.css
•	Purpose: Visual design and layout enhancements.
•	Features: 
o	Body typography and background color.
o	Link colors and hover/focus states.
o	Header gradient background and styled navigation links.
o	Logo styling with Unicode icon and box shadow.
o	Article card styling with borders, rounded corners, and shadows.
o	Feature cards grid layout.
o	Brand figure centering and caption styling.
o	Aside visuals with border and background.
o	Fluid image handling.
o	Smartphone spacing adjustments via .works_on_smartphone.
________________________________________
🚀 How to Run
1.	Clone the repository: 
2.	git clone https://github.com/yourusername/my-first-portfolio.git
3.	Open index.html in your browser to view the homepage.
4.	Navigate to tweets.html via the header menu to see updates.
________________________________________
📱 Responsive Design
•	Automatic: Media queries in base.css and styles.css adapt layout for screens ≤ 700px and ≤ 800px.
•	Manual: Add class="works_on_smartphone" to <body> to force smartphone layout even on larger screens.
________________________________________
🧑💻 Git Bash Workflow (Learning Guide)
Stage files
git add index.html tweets.html base.css styles.css
Commit changes
git commit -m "Updated homepage and tweets page with new styles"
Push to GitHub
git push origin master
Unstage files (if needed)
git restore --staged index.html
git restore --staged base.css
👉 This workflow shows how to stage, commit, push, and unstage files safely while keeping originals preserved in Git history.
________________________________________
✨ Learning Goals Demonstrated
•	Semantic HTML5 structure for accessibility.
•	Separation of concerns: base styles vs. visual design.
•	Responsive design with media queries and flexbox/grid.
•	Git workflow practice: staging, committing, branching, and pushing changes

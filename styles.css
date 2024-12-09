:root {
    --primary-color: #ffffff;
    --background-color: #000000;
    --accent-color: #6b46c1;
    --text-color: #ffffff;
    --secondary-bg: #1a1a1a;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Inter', sans-serif;
    background-color: var(--background-color);
    color: var(--text-color);
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header Styles */
.header {
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
    transition: background-color 0.3s ease;
    padding: 1rem 0;
}

.header.scrolled {
    background-color: rgba(0, 0, 0, 0.8);
    backdrop-filter: blur(8px);
}

.header nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    gap: 2rem;
}

.header nav a {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

.header nav a:hover {
    color: var(--accent-color);
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(to bottom right, var(--accent-color), var(--background-color));
    text-align: center;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.5rem;
    margin-bottom: 2rem;
}

/* Sections */
section {
    padding: 5rem 0;
}

.section-title {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 2rem;
}

.section-text {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
    font-size: 1.2rem;
}

/* Projects Grid */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
}

.project-card {
    background-color: var(--secondary-bg);
    padding: 2rem;
    border-radius: 8px;
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
}

/* Contact Form */
.contact-form {
    max-width: 600px;
    margin: 0 auto;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 0.75rem;
    border: none;
    background-color: var(--secondary-bg);
    color: var(--text-color);
    border-radius: 4px;
}

/* Buttons */
.cta-button,
.submit-button {
    background-color: var(--primary-color);
    color: var(--background-color);
    border: none;
    padding: 0.75rem 2rem;
    font-size: 1.1rem;
    border-radius: 9999px;
    cursor: pointer;
    transition: transform 0.3s ease, background-color 0.3s ease;
}

.cta-button:hover,
.submit-button:hover {
    transform: scale(1.05);
    background-color: #f0f0f0;
}

/* Animations */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease, transform 0.6s ease;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}

/* Responsive Design */
@media (max-width: 768px) {
    .hero-content h1 {
        font-size: 2.5rem;
    }

    .hero-content p {
        font-size: 1.2rem;
    }

    .section-title {
        font-size: 2rem;
    }

    .projects-grid {
        grid-template-columns: 1fr;
    }
}


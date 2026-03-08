
:root {
    --bg: #ffffff;
    --fg: #000000;
    --blue: #0070f3;
    --gray: #eaeaea;
    --text-muted: #666;
}

body {
    font-family: 'Inter', sans-serif;
    background: var(--bg);
    color: var(--fg);
    margin: 0;
    line-height: 1.5;
}

.container { max-width: 1000px; margin: 0 auto; padding: 0 2rem; }

.hero { padding: 100px 0 60px; text-align: center; }

.badge {
    background: #f0f7ff;
    color: var(--blue);
    padding: 6px 16px;
    border-radius: 100px;
    font-size: 0.8rem;
    font-weight: 600;
}

h1 { font-size: 4rem; letter-spacing: -2px; margin: 20px 0; }
.text-blue { color: var(--blue); }

.subtitle { font-size: 1.2rem; color: var(--text-muted); max-width: 600px; margin: 0 auto 30px; }

.btn {
    padding: 12px 24px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 500;
    transition: 0.2s;
}

.btn-primary { background: var(--fg); color: white; }
.btn-primary:hover { opacity: 0.8; }

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    padding-bottom: 80px;
}

.card {
    border: 1px solid var(--gray);
    padding: 30px;
    border-radius: 12px;
    transition: 0.3s;
}

.card:hover { border-color: var(--blue); box-shadow: 0 10px 30px rgba(0,0,0,0.05); }

.card i { color: var(--blue); margin-bottom: 15px; }

.card h3 { margin: 10px 0; font-size: 1.3rem; }

.card p { color: var(--text-muted); font-size: 0.95rem; }

@media (max-width: 768px) { h1 { font-size: 2.5rem; } }

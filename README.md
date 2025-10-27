# algiraldo92.github.io

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio | Alan Giraldo</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #1e293b;
      --text: #e2e8f0;
      --accent: #38bdf8;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 60px 20px 40px;
      background: linear-gradient(180deg, #0f172a, #1e293b);
    }

    header h1 {
      color: var(--accent);
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      opacity: 0.9;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .about {
      text-align: center;
    }

    .about p {
      max-width: 700px;
      margin: 20px auto;
      font-size: 1.1rem;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
      margin-top: 20px;
    }

    .skill {
      background: var(--card);
      padding: 10px 18px;
      border-radius: 20px;
      font-weight: 500;
      border: 1px solid #334155;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .project-card {
      background: var(--card);
      padding: 25px;
      border-radius: 16px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      border: 1px solid #334155;
    }

    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    .project-card h3 {
      color: var(--accent);
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      border-top: 1px solid #1e293b;
      background-color: #0f172a;
    }

    footer a {
      color: var(--accent);
      text-decoration: none;
      margin: 0 10px;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Alan Giraldo</h1>
    <p>Data Analyst | Python • SQL • Power BI • Tableau</p>
  </header>

  <section class="about">
    <h2>Sobre mí</h2>
    <p>
      Soy un analista de datos apasionado por transformar información en conocimiento.
      Combino herramientas como Python, SQL y Power BI para descubrir patrones

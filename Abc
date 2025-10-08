<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My Site — Landing / Login</title>
  <meta name="description" content="Simple landing page with a link and login form." />
  <style>
    /* Simple, modern, responsive styling (no frameworks) */
    :root{
      --bg:#0f1724;
      --card:#111827;
      --muted:#94a3b8;
      --accent:#06b6d4;
      --glass: rgba(255,255,255,0.03);
      --radius:14px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:
        radial-gradient(800px 400px at 10% 10%, rgba(6,182,212,0.06), transparent 8%),
        radial-gradient(700px 350px at 90% 90%, rgba(99,102,241,0.04), transparent 8%),
        var(--bg);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
      gap:24px;
    }

    .container{
      width:100%;
      max-width:980px;
      display:grid;
      grid-template-columns: 1fr 420px;
      gap:28px;
      align-items:center;
    }

    /* Responsive: single column on small screens */
    @media (max-width:880px){
      .container{grid-template-columns:1fr; padding:8px}
    }

    .hero{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      padding:28px;
      border-radius:var(--radius);
      box-shadow: 0 8px 30px rgba(2,6,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }
    .brand{
      display:flex;
      gap:12px;
      align-items:center;
      margin-bottom:16px;
    }
    .logo{
      width:56px;
      height:56px;
      border-radius:12px;
      background:linear-gradient(135deg,var(--accent),#6366f1);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      color:#022;
      box-shadow: 0 6px 20px rgba(6,182,212,0.08);
      font-size:20px;
    }
    h1{margin:0 0 6px 0; font-size:26px}
    p.lead{margin:0; color:var(--muted)}

    .links{
      margin-top:20px;
      display:flex;
      gap:12px;
      flex-wrap:wrap;
    }
    .btn{
      display:inline-flex;
      align-items:center;
      gap:10px;
      padding:10px 16px;
      border-radius:12px;
      text-decoration:none;
      font-weight:600;
      cursor:pointer;
      border:1px solid rgba(255,255,255,0.04);
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      transition: transform .12s ease, box-shadow .12s ease;
      color:inherit;
      backdrop-filter: blur(6px);
    }
    .btn:active{ transform: translateY(1px) }
    .btn.primary{
      background: linear-gradient(90deg, rgba(6,182,212,0.12), rgba(99,102,241,0.06));
      box-shadow: 0 8px 30px rgba(6,182,212,0.06);
      border: 1px solid rgba(6,182,212,0.16);
      color:#dffafe;
    }
    .small{
      color:var

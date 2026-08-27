# MaritimePathway
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Maritime Credential Pathways — Quick Reference</title>
<style>
  :root{
    --navy:#0f1e33;
    --steel:#3a5673;
    --brass:#c9a24b;
    --paper:#f2ede1;
    --ink:#1b2430;
    --line:#9fb4c4;
  }
  *{box-sizing:border-box;}
  html,body{height:100%;}
  body{
    margin:0;
    background:var(--paper);
    font-family:Georgia,"Times New Roman",serif;
    color:var(--ink);
    padding:22px 26px;
  }
  .page{max-width:1200px;margin:0 auto;}
  header{
    text-align:center;
    border-bottom:2px solid var(--navy);
    padding-bottom:10px;
    margin-bottom:18px;
  }
  h1{margin:0;font-size:1.6rem;color:var(--navy);font-variant:small-caps;letter-spacing:0.5px;}
  .sub{font-family:"Courier New",monospace;font-size:0.72rem;color:var(--steel);text-transform:uppercase;letter-spacing:1.5px;margin-top:4px;}

  .cols{display:grid;grid-template-columns:1fr 1fr;gap:30px;}
  .col-title{
    text-align:center;
    font-variant:small-caps;
    font-size:1.05rem;
    color:#fff;
    background:var(--navy);
    padding:6px 10px;
    border-radius:3px;
    margin-bottom:14px;
  }
  .col-title.b{background:var(--steel);}

  .box{
    background:#fff;
    border:1px solid var(--steel);
    border-left:4px solid var(--navy);
    border-radius:2px;
    padding:8px 12px;
    font-size:0.82rem;
    line-height:1.35;
    box-shadow:1px 1px 0 rgba(15,30,51,0.08);
  }
  .box.b{border-left-color:var(--brass);}
  .box strong{color:var(--navy);display:block;font-size:0.88rem;margin-bottom:1px;}
  .box .tag{
    font-family:"Courier New",monospace;
    font-size:0.6rem;
    color:var(--steel);
    letter-spacing:0.5px;
  }
  .arrow{
    text-align:center;
    color:var(--line);
    font-size:1.1rem;
    line-height:1;
    margin:2px 0;
  }
  .fork-row{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
  .fork-note{
    grid-column:1/-1;
    text-align:center;
    font-size:0.68rem;
    font-style:italic;
    color:var(--steel);
  }

  .links{
    margin-top:22px;
    border-top:1px solid var(--steel);
    padding-top:14px;
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:24px;
  }
  .links h2{
    font-size:0.85rem;
    font-variant:small-caps;
    color:var(--navy);
    margin:0 0 8px;
    border-bottom:1px solid var(--brass);
    display:inline-block;
    padding-bottom:2px;
  }
  .links ul{margin:0;padding-left:18px;font-size:0.78rem;line-height:1.75;}
  .links a{color:var(--navy);text-decoration:none;border-bottom:1px dotted var(--steel);}
  .links a:hover{color:var(--brass);}
  .links .note{display:block;color:var(--steel);font-size:0.68rem;font-style:italic;}

  footer{
    margin-top:16px;
    text-align:center;
    font-family:"Courier New",monospace;
    font-size:0.65rem;
    color:var(--steel);
  }

  @media (max-width:820px){
    .cols{grid-template-columns:1fr;}
    .links{grid-template-columns:1fr;}
    .fork-row{grid-template-columns:1fr;}
  }
</style>
</head>
<body>
<div class="page">
  <header>
    <h1>Merchant Mariner Credential Pathways</h1>
    <div class="sub">Unlicensed &amp; Licensed Tracks — Quick Reference</div>
  </header>

  <div class="cols">
    <!-- UNLICENSED -->
    <div class="col">
      <div class="col-title">Unlicensed Track</div>

      <div class="box"><span class="tag">STEP 1</span><strong>TWIC + Entry MMC</strong>Physical exam, drug test, TSA background check.</div>
      <div class="arrow">↓</div>
      <div class="box b"><span class="tag">STCW VI/1</span><strong>Basic Training</strong>Fire fighting · first aid · survival techniques · personal safety.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">STEP 2</span><strong>Entry Rating</strong>Ordinary Seaman / Wiper / Steward's Dept. — begin sea service.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">STEP 3 · ~180–540 days</span><strong>Sea Service Accrual</strong>Union hiring hall (SIU) or direct commercial hire.</div>
      <div class="arrow">↓</div>
      <div class="box b"><span class="tag">MILESTONE</span><strong>Able Seafarer (AB) / QMED</strong>Sea service + exam or approved course + STCW II/5 or III/4.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">STEP 4</span><strong>Advanced Endorsements</strong>Lifeboatman · Tankerman-PIC · Radar Observer.</div>
      <div class="arrow">↓</div>
      <div class="box" style="border-left-color:#5c8a6e;"><span class="tag" style="color:#5c8a6e;">CROSSOVER</span><strong>Hawsepipe into Licensed Track →</strong>~360+ days sea service + license-prep coursework qualifies for 3rd mate / 3rd engineer exam.</div>
    </div>

    <!-- LICENSED -->
    <div class="col">
      <div class="col-title b">Licensed Track</div>

      <div class="fork-row">
        <div class="box b"><span class="tag">ROUTE A</span><strong>Academy</strong>4-yr degree (USMMA / state academy) → license on graduation.</div>
        <div class="box b"><span class="tag">ROUTE B</span><strong>Hawsepipe / Union Apprentice</strong>Sea service + MITAGS/Piney Point/private school + USCG exam.</div>
        <div class="fork-note">both routes converge on the same first license</div>
      </div>
      <div class="arrow">↓</div>
      <div class="box b"><span class="tag">STCW II/1 · III/1</span><strong>3rd Mate / 3rd Engineer</strong>Officer in Charge of Watch (OICNW / OICEW) — entry officer license.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">~360 days + exam modules</span><strong>2nd Mate / 2nd Engineer</strong>Expanding tonnage / kW scope.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">~360 days + exam modules</span><strong>Chief Mate / 1st Engineer</strong>Final operational rank before management-level courses.</div>
      <div class="arrow">↓</div>
      <div class="box b"><span class="tag">STCW II/2 · III/2</span><strong>Master / Chief Engineer</strong>Management level — ERM/BRM + Leadership &amp; Managerial Skills + final exam.</div>
      <div class="arrow">↓</div>
      <div class="box"><span class="tag">GOAL</span><strong>Unlimited Tonnage / Horsepower</strong>Same license, maximum scope — reached via sea service on larger vessels.</div>
    </div>
  </div>

  <div class="links">
    <div>
      <h2>MMC Application</h2>
      <ul>
        <li><a href="https://www.dco.uscg.mil/nmc/" target="_blank">National Maritime Center (NMC) — home</a></li>
        <li><a href="https://www.dco.uscg.mil/Our-Organization/NMC/Applications-Forms/" target="_blank">MMC application forms &amp; checklists</a></li>
        <li><a href="https://www.dco.uscg.mil/nmc/merchant_mariner_medical_certification/" target="_blank">CG-719K medical certificate (physical exam form)</a></li>
        <li><a href="https://www.dco.uscg.mil/nmc/merchant_mariner_credential/" target="_blank">MMC overview — ratings, endorsements, renewals</a></li>
        <li><a href="https://www.tsa.gov/for-industry/twic" target="_blank">TWIC (Transportation Worker ID Credential) — TSA</a></li>
        <li class="note">All license/rating exams and sea-service policy are administered through NMC — start here for current requirements.</li>
      </ul>
    </div>
    <div>
      <h2>Maritime Education Resources</h2>
      <ul>
        <li><a href="https://www.usmma.edu" target="_blank">USMMA (Kings Point)</a> — federal academy, unlimited license on graduation</li>
        <li><a href="https://www.maritime.edu" target="_blank">Massachusetts Maritime Academy</a></li>
        <li><a href="https://www.sunymaritime.edu" target="_blank">SUNY Maritime College</a></li>
        <li><a href="https://www.csum.edu" target="_blank">Cal Maritime</a></li>
        <li><a href="https://www.mainemaritime.edu" target="_blank">Maine Maritime Academy</a></li>
        <li><a href="https://www.tamug.edu" target="_blank">Texas A&amp;M Maritime Academy</a></li>
        <li><a href="https://www.nmc.edu/maritime" target="_blank">Great Lakes Maritime Academy</a></li>
        <li><a href="https://www.mitags.org" target="_blank">MITAGS</a> / <a href="https://www.mitags-pmi.org" target="_blank">MITAGS-PMI</a> — union license-prep &amp; STCW courses</li>
        <li><a href="https://www.seafarers.org/psu/" target="_blank">Paul Hall Center (SIU — Piney Point)</a> — unlicensed apprentice program</li>
        <li><a href="https://www.mptusa.com" target="_blank">Maritime Professional Training (MPT)</a> — private STCW school</li>
      </ul>
    </div>
  </div>

  <footer>
    Sea-service day counts, course requirements, and tonnage/HP thresholds are set by NMC policy and change periodically — confirm current figures at dco.uscg.mil/nmc.
  </footer>
</div>
</body>
</html>
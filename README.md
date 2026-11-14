<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TaRL Coaching &amp; Mentoring — Complete Course</title>
<style>
:root{--p:#0d6e6e;--pd:#095454;--pl:#e6f4f4;--acc:#f4a261;--accd:#e76f51;--succ:#2a9d8f;--dan:#e63946;--warn:#e9c46a;--dark:#1d3557;--gray:#6c757d;--lt:#f8f9fa;--sh:0 4px 20px rgba(0,0,0,.08)}
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Segoe UI',Tahoma,sans-serif;background:var(--lt);color:var(--dark);line-height:1.65}
.container{max-width:1000px;margin:0 auto;padding:20px}
h1,h2,h3,h4{color:var(--pd);line-height:1.3;margin-bottom:.6rem}
h1{font-size:2rem}h2{font-size:1.6rem;margin:1.5rem 0 .8rem}h3{font-size:1.25rem;margin:1.2rem 0 .5rem}h4{font-size:1.05rem;color:var(--p);margin:1rem 0 .4rem}
p{margin-bottom:.9rem}ul,ol{margin:.5rem 0 1rem 1.5rem}li{margin-bottom:.4rem}
a{color:var(--p)}
.card{background:#fff;border-radius:12px;box-shadow:var(--sh);padding:1.5rem;margin-bottom:1.2rem}
.callout{background:var(--pl);border-left:5px solid var(--p);padding:1rem 1.3rem;border-radius:0 8px 8px 0;margin:1rem 0}
.callout.warn{background:#fdf6e3;border-color:var(--warn)}
.callout.dan{background:#fde8ea;border-color:var(--dan)}
.callout.succ{background:#e6f7f3;border-color:var(--succ)}
.btn{display:inline-block;padding:.7rem 1.6rem;border:none;border-radius:8px;font-size:1rem;font-weight:600;cursor:pointer;text-decoration:none;text-align:center;transition:.2s;font-family:inherit}
.btn:hover{transform:translateY(-2px)}
.btn-p{background:var(--acc);color:var(--dark)}
.btn-s{background:var(--p);color:#fff}
.btn-succ{background:var(--succ);color:#fff}
.btn-dan{background:var(--dan);color:#fff}
.btn-o{background:transparent;border:2px solid var(--p);color:var(--p)}
.btn-sm{padding:.35rem .9rem;font-size:.85rem}
.btn-blk{display:block;width:100%}
.form-group{margin-bottom:1rem}
label{display:block;font-weight:600;margin-bottom:.3rem;font-size:.92rem}
input,select,textarea{width:100%;padding:.65rem .9rem;border:2px solid #dde4e4;border-radius:8px;font-size:1rem;font-family:inherit}
input:focus,select:focus,textarea:focus{outline:none;border-color:var(--p)}
.alert{padding:1rem 1.2rem;border-radius:8px;margin-bottom:1rem;border-left:5px solid}
.alert-i{background:var(--pl);border-color:var(--p);color:var(--pd)}
.alert-s{background:#e6f7f3;border-color:var(--succ);color:#1a6b5e}
.alert-d{background:#fde8ea;border-color:var(--dan);color:#a4161a}
.alert-w{background:#fdf6e3;border-color:var(--warn);color:#8a6d1a}
.navbar{background:var(--pd);color:#fff;padding:.9rem 0;margin-bottom:1.5rem;position:sticky;top:0;z-index:100;box-shadow:0 2px 10px rgba(0,0,0,.15)}
.navbar .container{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:.5rem;padding-top:0;padding-bottom:0}
.navbar-brand{font-weight:bold;font-size:1.1rem;color:#fff}
.navbar-brand .badge{background:var(--acc);color:var(--dark);padding:2px 8px;border-radius:12px;font-size:.65rem;margin-left:6px}
.navbar-links{display:flex;gap:1rem;list-style:none;flex-wrap:wrap;margin:0}
.navbar-links a{color:#cde3e3;text-decoration:none;font-size:.88rem;cursor:pointer}
.navbar-links a:hover{color:#fff}
.hidden{display:none!important}
.grid{display:grid;gap:1rem}
.grid-2{grid-template-columns:repeat(auto-fit,minmax(240px,1fr))}
.stat{background:var(--pl);border-radius:8px;padding:1rem;text-align:center}
.stat .v{font-size:1.6rem;font-weight:bold;color:var(--p)}
.stat .l{font-size:.72rem;color:var(--gray);text-transform:uppercase;letter-spacing:.5px}
.prog-wrap{background:#e2e8e8;border-radius:20px;height:12px;overflow:hidden;margin:.4rem 0}
.prog-bar{height:100%;background:linear-gradient(90deg,var(--succ),var(--p));transition:width .5s;width:0}
.mod-item{display:flex;align-items:center;gap:1rem;background:#fff;border-radius:10px;box-shadow:var(--sh);padding:1rem 1.2rem;margin-bottom:.7rem;flex-wrap:wrap}
.mod-num{width:44px;height:44px;border-radius:50%;background:var(--p);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:bold;flex-shrink:0}
.mod-item.done .mod-num{background:var(--succ)}
.mod-info{flex:1;min-width:180px}
.mod-info h4{margin:0;font-size:.98rem}
.mod-meta{font-size:.8rem;color:var(--gray)}
.q-card{background:#fff;border-radius:12px;box-shadow:var(--sh);padding:1.4rem;margin-bottom:1rem}
.q-num{display:inline-block;background:var(--p);color:#fff;width:28px;height:28px;border-radius:50%;text-align:center;line-height:28px;font-weight:bold;font-size:.85rem;margin-right:.5rem}
.q-text{font-weight:600}
.option{display:flex;gap:.6rem;padding:.55rem .8rem;border-radius:6px;cursor:pointer;margin-bottom:.2rem}
.option:hover{background:var(--pl)}
.option input{width:auto;margin-top:.35rem}
table{width:100%;border-collapse:collapse;font-size:.88rem;background:#fff;border-radius:8px;overflow:hidden;margin:.8rem 0}
th,td{padding:.65rem .8rem;border-bottom:1px solid #eef2f2;text-align:left;vertical-align:top}
th{background:var(--pd);color:#fff;font-size:.78rem;text-transform:uppercase;letter-spacing:.5px}
tr:hover td{background:var(--pl)}
.table-wrap{overflow-x:auto}
code{background:#eef2f2;padding:2px 6px;border-radius:4px;font-size:.85rem}
.video-embed{position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:8px;margin:1rem 0;background:#000}
.video-embed iframe{position:absolute;inset:0;width:100%;height:100%;border:none}
.res-list{list-style:none;margin:0}
.res-list li{padding:.8rem 1rem;background:#fff;border:1px solid #eef2f2;border-radius:8px;margin-bottom:.5rem;display:flex;gap:.8rem;align-items:flex-start}
.res-list .icon{font-size:1.3rem;flex-shrink:0}
.res-title{font-weight:600;color:var(--p)}
.res-desc{font-size:.85rem;color:var(--gray)}
.unit-title{border-bottom:3px solid var(--acc);padding-bottom:.3rem;margin-top:2rem}
.cert{background:#fff;border:10px double var(--p);padding:2.5rem;text-align:center;max-width:800px;margin:1rem auto;position:relative}
.cert::before{content:'';position:absolute;inset:12px;border:2px solid var(--acc);pointer-events:none}
.cert-org{font-size:.85rem;letter-spacing:3px;color:var(--p);text-transform:uppercase;font-weight:600}
.cert-title{font-family:Georgia,serif;font-size:2.3rem;color:var(--pd);margin:.8rem 0}
.cert-name{font-family:Georgia,serif;font-size:2rem;color:var(--dark);border-bottom:2px solid var(--acc);display:inline-block;padding:0 2rem .2rem;margin:.6rem 0}
.cert-footer{display:flex;justify-content:space-around;flex-wrap:wrap;gap:1.5rem;margin-top:2rem;padding-top:1rem}
.sign-line{width:200px;border-top:2px solid var(--dark);margin-bottom:.3rem}
.sign-name{font-weight:700;color:var(--pd)}
.sign-role{font-size:.78rem;color:var(--gray)}
.cert-id{font-size:.72rem;color:var(--gray);margin-top:1.5rem;letter-spacing:.5px}
.flex-btw{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:.8rem}
.mod-nav{display:flex;justify-content:space-between;gap:1rem;margin:1.5rem 0;flex-wrap:wrap}
@media(max-width:768px){h1{font-size:1.5rem}h2{font-size:1.25rem}.cert{padding:1.5rem}.cert-title{font-size:1.6rem}.cert-name{font-size:1.4rem}}
@media print{.no-print,.navbar{display:none!important}body{background:#fff}}
</style>
</head>
<body>

<nav class="navbar no-print">
  <div class="container">
    <div class="navbar-brand">🎓 TaRL Course <span class="badge">FULL</span></div>
    <ul class="navbar-links">
      <li><a onclick="show('view-landing')">Home</a></li>
      <li><a onclick="show('view-dashboard')">Dashboard</a></li>
      <li><a onclick="show('view-login')">Login</a></li>
      <li><a onclick="show('view-admin-login')">Admin</a></li>
    </ul>
  </div>
</nav>

<div class="container">

<!-- LANDING -->
<div id="view-landing">
  <div class="card" style="background:linear-gradient(135deg,#095454,#0d6e6e);color:#fff;text-align:center;padding:2.5rem 1.5rem">
    <h1 style="color:#fff;font-size:1.8rem">Coaching, Mentoring &amp; Data-Driven Monitoring in TaRL</h1>
    <p style="opacity:.92;margin:.8rem 0 1rem">Complete 5-module professional development curriculum · Certificate on completion</p>
    <p style="opacity:.85;font-size:.9rem">Based on the 300-Page Comprehensive TaRL Curriculum (Parts 1–5)</p>
    <button class="btn btn-p mt-1" onclick="show('view-register')">Register Now</button>
    <button class="btn btn-o" style="border-color:#fff;color:#fff;margin-left:.5rem" onclick="show('view-admin-login')">Admin Login</button>
  </div>

  <div class="card">
    <h2>📋 Course Overview &amp; Front Matter</h2>
    <div id="frontMatterRender"></div>
  </div>

  <div class="card" style="background:var(--dark);color:#fff;text-align:center">
    <h3 style="color:var(--acc)">Course Administrator</h3>
    <p style="font-size:1.15rem;font-weight:700;margin:.5rem 0">Mohammed Sultan</p>
    <p style="font-size:.92rem;opacity:.9">Program Manager, Primary Education</p>
    <p style="font-size:.92rem;opacity:.9">Imagine 1Day International Organization</p>
    <p style="font-size:.92rem;opacity:.9">📧 mohammedscho2023@gmail.com</p>
    <p style="font-size:.85rem;color:var(--acc);margin-top:.5rem">Admin Code: <code style="background:#fff3;color:#fff">54025402</code></p>
  </div>
</div>

<!-- REGISTER -->
<div id="view-register" class="hidden">
  <div class="card" style="max-width:700px;margin:0 auto">
    <h2>📝 Learner Registration</h2>
    <p style="color:var(--gray);font-size:.9rem">Registration is reviewed by the administrator. Upon approval you will receive an approval code to log in.</p>
    <div id="regAlert"></div>
    <div class="grid grid-2">
      <div class="form-group"><label>Full Name *</label><input id="regName"></div>
      <div class="form-group"><label>Email *</label><input id="regEmail" type="email"></div>
      <div class="form-group"><label>Phone *</label><input id="regPhone"></div>
      <div class="form-group"><label>Country *</label><input id="regCountry"></div>
    </div>
    <div class="grid grid-2">
      <div class="form-group"><label>Role</label>
        <select id="regRole">
          <option>School-Based Mentor</option><option>Senior Teacher</option><option>School Director</option>
          <option>Cluster/Zonal Supervisor</option><option>Woreda/District Education Officer</option>
          <option>NGO Program Advisor</option><option>Teacher</option><option>Other</option>
        </select>
      </div>
      <div class="form-group"><label>Organization</label><input id="regOrg"></div>
    </div>
    <div class="form-group"><label>Motivation (optional)</label><textarea id="regMotivation" rows="2"></textarea></div>
    <button class="btn btn-p btn-blk" onclick="doRegister()">Submit Registration</button>
    <div id="regEmailBox" class="hidden" style="margin-top:1rem">
      <a id="regMailBtn" class="btn btn-succ btn-blk" href="#">📧 Send Registration Email to Administrator</a>
    </div>
  </div>
</div>

<!-- LOGIN -->
<div id="view-login" class="hidden">
  <div class="card" style="max-width:480px;margin:0 auto">
    <h2>🔐 Learner Login</h2>
    <div id="loginAlert"></div>
    <div class="form-group"><label>Email</label><input id="loginEmail" type="email"></div>
    <div class="form-group"><label>Approval Code</label><input id="loginCode" placeholder="TaRL-XXXXXX"></div>
    <button class="btn btn-p btn-blk" onclick="doLogin()">Login</button>
    <p style="text-align:center;font-size:.85rem;margin-top:1rem;color:var(--gray)">No account? <a href="#" onclick="show('view-register');return false">Register</a></p>
  </div>
</div>

<!-- ADMIN LOGIN -->
<div id="view-admin-login" class="hidden">
  <div class="card" style="max-width:480px;margin:0 auto;border:2px solid var(--dark)">
    <h2>👨‍💼 Administrator Login</h2>
    <p style="color:var(--gray);font-size:.9rem">Admin Code: <code>54025402</code></p>
    <div id="adminLoginAlert"></div>
    <div class="form-group"><label>Administrator Code</label><input id="adminCodeIn" type="password"></div>
    <button class="btn btn-s btn-blk" onclick="doAdminLogin()">Admin Login</button>
  </div>
</div>

<!-- ADMIN -->
<div id="view-admin" class="hidden">
  <div class="card" style="background:var(--dark);color:#fff">
    <div class="flex-btw">
      <div><h2 style="color:#fff">👨‍💼 Admin Panel</h2><p style="opacity:.85;font-size:.85rem">Mohammed Sultan · Code 54025402 · Imagine 1Day</p></div>
      <button class="btn btn-dan btn-sm" onclick="sessionStorage.removeItem('admin');show('view-landing')">Logout</button>
    </div>
  </div>
  <div class="card"><h3>⏳ Pending Registrations</h3><div id="pendingList"></div></div>
  <div class="card"><h3>✅ Approved Users</h3><div id="usersList"></div></div>
  <div class="card"><h3>🏆 Issued Certificates</h3><div id="certsList"></div></div>
</div>

<!-- DASHBOARD -->
<div id="view-dashboard" class="hidden">
  <div class="card">
    <div class="flex-btw">
      <div><h1>Welcome, <span id="dashName">Learner</span> 👋</h1><p style="color:var(--gray)">TaRL Coaching &amp; Mentoring · 5 Modules + Final Exam</p></div>
      <button class="btn btn-o btn-sm" onclick="doLogout()">Logout</button>
    </div>
    <div class="grid grid-2" style="margin-top:1rem">
      <div class="stat"><div class="v" id="statDone">0</div><div class="l">Modules Passed</div></div>
      <div class="stat"><div class="v" id="statTotal">5</div><div class="l">Total Modules</div></div>
      <div class="stat"><div class="v" id="statPct">0%</div><div class="l">Progress</div></div>
      <div class="stat"><div class="v" id="statFinal">—</div><div class="l">Final Exam</div></div>
    </div>
    <div style="margin-top:1rem">
      <div class="flex-btw" style="font-size:.85rem;color:var(--gray)"><span>Overall Progress</span><span id="pctLabel">0%</span></div>
      <div class="prog-wrap"><div class="prog-bar" id="progressBar"></div></div>
    </div>
  </div>
  <h2>📚 Course Modules</h2>
  <div id="moduleList"></div>
  <div id="finalBox" style="margin-top:1.5rem"></div>
</div>

<!-- MODULE VIEWER -->
<div id="view-module" class="hidden">
  <div class="card no-print" style="background:linear-gradient(135deg,#095454,#0d6e6e);color:#fff">
    <div class="flex-btw">
      <div>
        <div style="font-size:.8rem;letter-spacing:2px;opacity:.9;text-transform:uppercase" id="modLabel">MODULE</div>
        <h1 style="color:#fff;font-size:1.6rem" id="modTitle"></h1>
        <div style="font-size:.85rem;opacity:.85;margin-top:.3rem" id="modMeta"></div>
      </div>
      <button class="btn btn-p btn-sm" onclick="show('view-dashboard')">← Dashboard</button>
    </div>
  </div>
  <div id="moduleContent"></div>
  <div class="mod-nav no-print">
    <button class="btn btn-o" onclick="prevModule()">← Previous</button>
    <button class="btn btn-s" onclick="openExamForCurrent()">📝 Take Module Exam</button>
    <button class="btn btn-o" onclick="nextModule()">Next →</button>
  </div>
</div>

<!-- EXAM -->
<div id="view-exam" class="hidden">
  <div class="card" style="background:linear-gradient(135deg,#1d3557,#2a4a6b);color:#fff">
    <h2 style="color:#fff" id="examTitle">Exam</h2>
    <p style="opacity:.85">Pass mark: <span id="examPass"></span>% · <span id="examSections"></span></p>
  </div>
  <div id="examContainer"></div>
</div>

<!-- CERTIFICATE -->
<div id="view-cert" class="hidden">
  <div class="no-print" style="text-align:center;margin-bottom:1rem">
    <button class="btn btn-p" onclick="window.print()">🖨️ Print / Save PDF</button>
    <button class="btn btn-o" onclick="show('view-dashboard')">Back to Dashboard</button>
  </div>
  <div id="certBox"></div>
</div>

</div><!-- /container -->

<script>
/* ============================================================
   CONFIG
============================================================ */
const CFG = {
  adminName: "Mohammed Sultan",
  adminTitle: "Program Manager, Primary Education",
  adminOrg: "Imagine 1Day International Organization",
  adminCode: "54025402",
  adminEmail: "mohammedscho2023@gmail.com",
  courseName: "Coaching, Mentoring, and Data-Driven Monitoring in Teaching at the Right Level (TaRL)",
  courseShort: "TaRL Coaching & Mentoring",
  finalPass: 70,
  modPass: 60,
  totalModules: 5
};

/* ============================================================
   STORAGE
============================================================ */
const DB = {
  get: k => JSON.parse(localStorage.getItem("tarl_" + k) || "[]"),
  set: (k, v) => localStorage.setItem("tarl_" + k, JSON.stringify(v)),
  prog: email => JSON.parse(localStorage.getItem("tarl_prog_" + email) || "{}"),
  saveProg: (email, p) => localStorage.setItem("tarl_prog_" + email, JSON.stringify(p))
};
let currentUser = JSON.parse(sessionStorage.getItem("tarl_user") || "null");
let currentMod = 1;
let currentExam = null;

function val(id){const e=document.getElementById(id);return e?e.value:"";}
function show(id){document.querySelectorAll('[id^="view-"]').forEach(v=>v.classList.add('hidden'));document.getElementById(id).classList.remove('hidden');window.scrollTo(0,0);if(id==='view-dashboard')renderDashboard();if(id==='view-admin')renderAdmin();}
function alertBox(id,type,msg){const e=document.getElementById(id);if(e)e.innerHTML=`<div class="alert alert-${type}">${msg}</div>`;}

/* ============================================================
   FRONT MATTER RENDERER
============================================================ */
function renderFrontMatter() {
  document.getElementById("frontMatterRender").innerHTML = `
    <h3>Series Architecture Overview (300-Page Comprehensive Curriculum)</h3>
    <ul>
      <li><strong>Part 1 (Current Volume):</strong> Front Matter, Master 5-Day Training Blueprint, Mentor Self-Audit &amp; Module 1 (Foundations of Mentoring, Coaching &amp; Adult Learning in TaRL).</li>
      <li><strong>Part 2:</strong> Module 2 — Mastering TaRL Classroom Pedagogy, Assessment Integrity &amp; Level-Specific Observation Rubrics.</li>
      <li><strong>Part 3:</strong> Module 3 — Coaching Conversations, Active Listening, GROW/RESULTS Scripts &amp; Conflict Resolution.</li>
      <li><strong>Part 4:</strong> Module 4 — Data-Driven Monitoring, Learner Progression Analytics &amp; Multi-School Triage Protocols.</li>
      <li><strong>Part 5:</strong> Module 5 &amp; Appendices — Multi-Tiered Governance, Communities of Practice, Printable Field Toolkits &amp; Global Resource Compendium.</li>
    </ul>
    <h3>Manual Metadata</h3>
    <div class="table-wrap"><table>
      <tr><th>Target Audience</th><td>School-Based Mentors (Senior Teachers, School Directors), Cluster/Zonal Supervisors, Woreda/District Education Officers, and NGO Program Advisors</td></tr>
      <tr><th>Training Delivery Model</th><td>5-Day Intensive Workshop + 15-20 Days of Mentor Practice Classes + Ongoing Data-Driven Field Coaching Cycles</td></tr>
      <tr><th>Core Pedagogical Frameworks</th><td>Pratham / TaRL Africa CAMaL Methodology, OpenLearn Mentoring Continuum, Daloz Support/Challenge Matrix, Lofthouse Practice Development Model, GROW &amp; RESULTS Coaching Frameworks</td></tr>
      <tr><th>Geographic &amp; System Context</th><td>Adaptable across Sub-Saharan African and South Asian primary education systems, including government-led scale-ups (Zambia, Kenya, Ethiopia, Uganda) and humanitarian/refugee education settings</td></tr>
    </table></div>
    <h3>1. Rationale: Why Mentoring is the Decisive Lever in TaRL</h3>
    <p>Across primary education systems globally, millions of children sit in Grades 3, 4, 5, and beyond without having mastered basic foundational literacy and numeracy. Traditional age-grade curricula march forward on a fixed calendar regardless of whether learners can recognize letters, decode simple words, or perform two-digit subtraction. Teaching at the Right Level (TaRL) disrupts this cycle by grouping children according to their actual learning competence rather than age or grade, assessing every child one-on-one, and engaging learners in joyful, multi-sensory Combined Activities for Maximized Learning (CAMaL).</p>
    <p>However, empirical evaluations of TaRL programs across India and Africa reveal a critical operational reality: <strong>initial teacher training workshops are necessary, but they are never sufficient on their own.</strong> When teachers return from a 5- or 10-day training workshop to overcrowded classrooms, rigid school timetables, and administrative pressures, they routinely default to familiar lecture-style, whole-class instruction. Without sustained, empathetic, and data-informed mentoring on the ground, classroom execution drifts away from program design.</p>
    <p>Mentoring and coaching serve as the operational bridge between workshop theory and daily classroom fidelity. An effective mentor does not arrive at a school as a punitive inspector wielding a fault-finding checklist. Instead, the mentor acts as a trusted teacher-educator, co-inquirer, and pedagogical problem-solver who observes full lessons, models difficult activities live, facilitates reflective dialogue, and uses learner progression data to direct support where children need it most.</p>
    <div class="callout"><strong>CORE PRINCIPLE OF TaRL MENTORING:</strong> Planning = Execution only when teachers receive continuous, non-judgmental, school-based support. Mentoring transforms isolated teachers into confident facilitators and turns static baseline data into rapid, measurable gains in children's reading and mathematics.</div>
    <h3>2. Comprehensive Competency Framework for TaRL Mentors &amp; Coaches</h3>
    <div class="table-wrap"><table>
      <tr><th>Domain</th><th>Code</th><th>Competency</th><th>Observable Field Indicator</th></tr>
      <tr><td rowspan="3">Domain 1: Pedagogical Mastery &amp; Modeling</td><td>C1.1</td><td>TaRL Methodology &amp; CAMaL Fluency</td><td>Accurately demonstrates all literacy and numeracy activities across Beginner, Word/Paragraph, and Story levels.</td></tr>
      <tr><td>C1.2</td><td>One-on-One Assessment Integrity</td><td>Administers ASER/TaRL placement tools calmly and accurately; verifies teacher grouping accuracy.</td></tr>
      <tr><td>C1.3</td><td>Contextual &amp; Multilingual Adaptation</td><td>Guides teachers in adapting activities for over-age learners, large PTR, and local mother tongues.</td></tr>
      <tr><td rowspan="3">Domain 2: Relational Trust &amp; Mentoring Stance</td><td>C2.1</td><td>Psychological Safety &amp; Acculturation</td><td>Builds non-threatening rapport; eliminates punitive 'judge mentoring'; fosters teacher willingness to experiment.</td></tr>
      <tr><td>C2.2</td><td>Calibrated Support &amp; Challenge</td><td>Applies Daloz's matrix to balance emotional/practical affirmation with stretch challenges based on teacher readiness.</td></tr>
      <tr><td>C2.3</td><td>Continuum Navigation</td><td>Transitions fluidly from directive apprenticeship (modeling) to non-directive coaching (facilitating reflection).</td></tr>
      <tr><td rowspan="3">Domain 3: Coaching Dialogue &amp; Observation</td><td>C3.1</td><td>Collegial Full-Lesson Observation</td><td>Observes full 45-60 minute sessions, tracking student time-on-task and material usage rather than superficial compliance.</td></tr>
      <tr><td>C3.2</td><td>Committed Active Listening</td><td>Listens with empathy, tolerates silence, and avoids interrupting or imposing premature top-down fixes.</td></tr>
      <tr><td>C3.3</td><td>Structured Coaching Questioning</td><td>Uses GROW and RESULTS frameworks to ask open questions that empower teachers to diagnose and solve issues.</td></tr>
      <tr><td rowspan="3">Domain 4: Data Triage &amp; System Governance</td><td>C4.1</td><td>Learner Progression Analytics</td><td>Interprets baseline, midline, and endline group movement tables to spot stagnation early.</td></tr>
      <tr><td>C4.2</td><td>Data-Driven School Prioritization</td><td>Allocates scarce visit days dynamically to schools with lowest learning levels or slowest growth rates.</td></tr>
      <tr><td>C4.3</td><td>Multi-Tiered Review &amp; Peer Networks</td><td>Leads school/cluster review meetings and moderates WhatsApp/Telegram peer learning communities.</td></tr>
    </table></div>
    <h3>3. Pre-Course Diagnostic: Mentor Self-Audit Instrument</h3>
    <p>Facilitators should administer this diagnostic tool on Day 1 Morning (30 minutes) and revisit it on Day 5 Afternoon and after 60 days of field practice. Participants rate their current proficiency from 1 (Foundational / Needs Intensive Practice) to 5 (Exemplary / Ready to Coach Peers) and record concrete evidence.</p>
    <div class="table-wrap"><table>
      <tr><th>#</th><th>Mentor Self-Audit Statement</th><th>Rating (1-5)</th></tr>
      <tr><td>1</td><td>I can act as a positive, enthusiastic pedagogical role model during live classroom demonstrations.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>2</td><td>I understand how local school context, language of instruction, and class size affect TaRL delivery.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>3</td><td>I establish psychological safety before offering critique, avoiding 'judge mentoring' behaviors.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>4</td><td>I can conduct a full-lesson collegial observation without disrupting the teacher or learners.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>5</td><td>I ask open, non-leading coaching questions (GROW) rather than simply telling teachers what to fix.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>6</td><td>I practice committed listening—allowing silence and encouraging teachers to analyze their own lessons.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>7</td><td>I co-construct 1-2 achievable SMART targets with teachers rather than overwhelming them with long lists.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>8</td><td>I accurately verify one-on-one learner assessments and spot misgrouped students quickly.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>9</td><td>I analyze baseline-to-midline progression tables to prioritize which schools I visit first.</td><td>[ 1 2 3 4 5 ]</td></tr>
      <tr><td>10</td><td>I facilitate peer learning across schools and collaborate with school leaders to solve structural barriers.</td><td>[ 1 2 3 4 5 ]</td></tr>
    </table></div>
    <h3>4. Master 5-Day Intensive Workshop &amp; Practice Rollout Blueprint</h3>
    <div class="table-wrap"><table>
      <tr><th>Day</th><th>Morning (08:30-12:30)</th><th>Afternoon (13:30-17:00)</th><th>Deliverable</th></tr>
      <tr><td>Day 1: Mentor Mindset &amp; Foundations</td><td>1.1 Learning Crisis &amp; TaRL Philosophy<br>1.2 Mentor vs. Inspector — Eliminating Judge Mentoring<br>1.3 Mentor Self-Audit</td><td>1.4 The Mentoring Continuum (Familiarisation to Autonomy)<br>1.5 Daloz Support/Challenge Matrix &amp; Lofthouse Model</td><td>Completed Self-Audit &amp; Personal Growth Charter</td></tr>
      <tr><td>Day 2: Assessment Integrity &amp; Grouping</td><td>2.1 One-on-One Assessment Protocol<br>2.2 Live Simulation &amp; Inter-Rater Reliability</td><td>2.3 Interpreting Assessment Data &amp; Forming Groups<br>2.4 Managing High PTR &amp; Over-Age Learners</td><td>Calibrated Assessment Scoring Sheet &amp; Grouping Plan</td></tr>
      <tr><td>Day 3: TaRL Lesson Architecture</td><td>3.1 CAMaL Principles<br>3.2 Whole-Class Warm-Ups</td><td>3.3 Level-Wise Literacy Activities<br>3.4 Level-Wise Numeracy Activities</td><td>Annotated 60-Min Lesson Observation Rubric</td></tr>
      <tr><td>Day 4: Live Micro-Teaching &amp; Modeling</td><td>4.1 Mentor Micro-Teaching Round 1<br>4.2 Peer Critique Using Collegial Observation</td><td>4.3 Mentor Micro-Teaching Round 2<br>4.4 Co-Teaching &amp; Respectful In-Lesson Demonstration</td><td>Peer-Validated Micro-Teaching Feedback Log</td></tr>
      <tr><td>Day 5: Coaching Dialogue &amp; Data Triage</td><td>5.1 Committed Listening &amp; Open Question Rewrites<br>5.2 Role-Playing GROW &amp; RESULTS</td><td>5.3 Data-Driven School Triage Simulation<br>5.4 Multi-Tiered Governance &amp; 30-Day Field Action Plan</td><td>30-Day Prioritized School Visit &amp; Coaching Action Plan</td></tr>
    </table></div>
    <div class="callout warn"><strong>MANDATORY FIELD IMMERSION: THE 15-20 DAY PRACTICE CLASS RULE</strong><br>Following the 5-day workshop, all newly trained mentors (including zonal supervisors and NGO officers) must run a daily 1-hour TaRL practice class for 15-20 consecutive school days before mentoring teachers. Why? First, practicing the full cycle—testing, grouping, teaching, and re-testing—deepens tacit craft knowledge. Second, witnessing children progress under their own instruction builds authentic conviction and moral authority when coaching teachers.</div>
  `;
}

/* ============================================================
   ALL MODULE CONTENT & EXAMS
============================================================ */
const MODULES = {
  1: {
    title: "Module 1: Theoretical Foundations of Mentoring, Coaching & Adult Learning in TaRL",
    meta: "Estimated Duration: 6 Hours · Core Focus: Shift professional identity from administrative inspectors to developmental teacher-educators",
    videos: [
      { title: "Introduction to Teaching at the Right Level (TaRL)", url: "https://www.youtube.com/embed/rX04c4Q7uSk", desc: "Overview of TaRL methodology and why targeted instruction matters" },
      { title: "Mentoring vs Coaching — Key Differences", url: "https://www.youtube.com/embed/3n6pN_q8kZE", desc: "Understanding the mentoring continuum and supportive stances" },
      { title: "Daloz Support/Challenge Matrix Explained", url: "https://www.youtube.com/embed/1k2jK0Qr8xY", desc: "Balancing support and challenge in adult professional learning" }
    ],
    resources: [
      { title: "TaRL Africa Official Website", url: "https://teachingatherightlevel.org/", desc: "Measurement toolkits, implementation guides, country case studies" },
      { title: "OpenLearn Mentoring in Education", url: "https://www.open.edu/openlearn/education-development/mentoring-in-education", desc: "Free open-access mentoring courses and modules" },
      { title: "J-PAL / Pratham Research", url: "https://www.povertyactionlab.org/", desc: "Randomized controlled trials on targeted instruction and foundational learning" },
      { title: "Imagine 1Day Program Portfolios", url: "https://imagine1day.org/", desc: "Country-level foundational learning implementations in Ethiopia" }
    ],
    html: `
      <div class="card">
        <h3>📖 Module 1 Core Concepts</h3>
        <p>Mentoring in TaRL requires a deliberate shift from hierarchical inspection to collaborative professional inquiry. Mentors act as co-investigators who model joyful, active learning and support teachers through non-judgmental dialogue.</p>
        <p><strong>Key Theories Explored:</strong></p>
        <ul>
          <li><strong>Daloz Support/Challenge Matrix:</strong> Balancing high emotional and practical support with appropriate professional challenge so teachers neither stagnate nor experience burnout.</li>
          <li><strong>OpenLearn Mentoring Continuum:</strong> Moving teachers from initial familiarization and guided practice toward autonomous reflective mastery.</li>
          <li><strong>Lofthouse Practice Development Model:</strong> Combining collegial observation, co-planning, and reflective debriefs to ensure sustainable pedagogical change.</li>
        </ul>
        <div class="callout"><strong>Key Takeaway:</strong> An effective mentor builds psychological safety first. When teachers feel safe to admit instructional challenges, real pedagogical transformation begins.</div>
      </div>
    `,
    exam: [
      {
        q: "What is the primary role of a TaRL mentor compared to a traditional school inspector?",
        options: [
          "To fault-find and penalize teachers for non-compliance with administrative paperwork.",
          "To act as a trusted teacher-educator, co-inquirer, and pedagogical problem-solver.",
          "To take over the classroom and teach all lessons while the teacher observes.",
          "To focus exclusively on school infrastructure and attendance records."
        ],
        ans: 1
      },
      {
        q: "According to Daloz's Support/Challenge Matrix, what happens when a mentor provides high challenge but low support?",
        options: [
          "The teacher feels affirmed and stagnates without growing.",
          "The teacher experiences anxiety, defensiveness, or withdrawal.",
          "The teacher achieves optimal autonomous mastery.",
          "The teacher ignores the feedback entirely without stress."
        ],
        ans: 1
      },
      {
        q: "Why is the 15-20 day mentor practice class mandatory following initial training?",
        options: [
          "To fulfill administrative audit requirements for the education bureau.",
          "To test children for promotion to secondary school.",
          "To build tacit craft knowledge and moral authority through firsthand teaching experience.",
          "To replace regular school teachers during teacher strikes."
        ],
        ans: 2
      }
    ]
  },
  2: {
    title: "Module 2: Mastering TaRL Classroom Pedagogy, Assessment Integrity & Observation Rubrics",
    meta: "Estimated Duration: 6 Hours · Core Focus: ASER placement testing, grouping mechanics, and level-specific CAMaL activities",
    videos: [
      { title: "Administering the ASER / TaRL Assessment", url: "https://www.youtube.com/embed/rX04c4Q7uSk", desc: "Step-by-step one-on-one literacy and numeracy assessment" },
      { title: "Level-Wise Grouping & Classroom Management", url: "https://www.youtube.com/embed/3n6pN_q8kZE", desc: "Managing multi-level groups in overcrowded classrooms" }
    ],
    resources: [
      { title: "TaRL Assessment Toolkits", url: "https://teachingatherightlevel.org/resources/", desc: "Standardized testing cards and scoring sheets in multiple languages" },
      { title: "CAMaL Activity Repository", url: "https://www.povertyactionlab.org/", desc: "Interactive games and exercises for literacy and numeracy" }
    ],
    html: `
      <div class="card">
        <h3>📖 Module 2 Core Concepts</h3>
        <p>Assessment integrity is the bedrock of TaRL. If children are misassessed or misgrouped, targeted instruction fails. Mentors must master the one-on-one ASER testing protocol and train teachers to assess without bias.</p>
        <p><strong>The Four Literacy Levels:</strong> Beginner → Letter → Word → Paragraph → Story.</p>
        <p><strong>The Four Numeracy Levels:</strong> Beginner → 1-Digit Number Recognition (1-9) → 2-Digit Number Recognition (10-99) → Subtraction (with borrowing) → Division (3-digit by 1-digit).</p>
        <div class="callout succ"><strong>Tip for Mentors:</strong> Always observe whether teachers use concrete local objects (stones, sticks, bottle caps) during numeracy sessions before moving to abstract symbols.</div>
      </div>
    `,
    exam: [
      {
        q: "At what level does a child enter the TaRL literacy grouping if they can recognize letters and simple words but cannot fluently read a short paragraph?",
        options: ["Beginner level", "Letter level", "Word level", "Story level"],
        ans: 2
      },
      {
        q: "What is the primary purpose of the one-on-one assessment in TaRL?",
        options: [
          "To rank students for class valedictorian awards.",
          "To determine each child's actual learning level so they can be grouped appropriately.",
          "To punish students who have fallen behind in grade-level curriculum.",
          "To grade teachers on their previous semester performance."
        ],
        ans: 1
      },
      {
        q: "Which numeracy assessment task distinguishes a student at the Subtraction level from one at the 2-Digit Number Recognition level?",
        options: [
          "Identifying numbers from 10 to 99.",
          "Performing a two-digit subtraction problem with borrowing.",
          "Counting fingers up to 10.",
          "Reciting the multiplication table up to 10."
        ],
        ans: 1
      }
    ]
  },
  3: {
    title: "Module 3: Coaching Conversations, Active Listening, GROW/RESULTS Scripts & Conflict Resolution",
    meta: "Estimated Duration: 6 Hours · Core Focus: Post-observation feedback, GROW/RESULTS coaching frameworks, and emotional intelligence",
    videos: [
      { title: "GROW Coaching Model in Practice", url: "https://www.youtube.com/embed/1k2jK0Qr8xY", desc: "Goal, Reality, Options, Will — structured coaching dialogue" },
      { title: "Handling Resistance in Teacher Coaching", url: "https://www.youtube.com/embed/3n6pN_q8kZE", desc: "De-escalating defensive reactions and building trust" }
    ],
    resources: [
      { title: "GROW Model Coaching Toolkit", url: "https://www.open.edu/openlearn/", desc: "Question prompts and role-play scenario guides" },
      { title: "RESULTS Coaching Framework", url: "https://teachingatherightlevel.org/", desc: "Action-oriented feedback protocols for school leaders" }
    ],
    html: `
      <div class="card">
        <h3>📖 Module 3 Core Concepts</h3>
        <p>Coaching is not telling; it is unlocking a teacher's potential to maximize their own instructional performance. Mentors utilize structured frameworks such as <strong>GROW</strong> (Goal, Reality, Options, Will) and <strong>RESULTS</strong> to guide reflective debriefs.</p>
        <p><strong>Active Listening Skills:</strong></p>
        <ul>
          <li><strong>Tolerating Silence:</strong> Giving teachers 5–10 seconds to process questions before jumping in.</li>
          <li><strong>Paraphrasing &amp; Reflecting:</strong> Confirming understanding without imposing personal biases.</li>
          <li><strong>Open Questioning:</strong> Asking "What led you to choose that group activity?" rather than "Why didn't you manage time better?"</li>
        </ul>
        <div class="callout"><strong>Rule of Thumb:</strong> In a 30-minute post-observation debrief, the teacher should be speaking for at least 70% of the time.</div>
      </div>
    `,
    exam: [
      {
        q: "In the GROW coaching model, what does the 'R' stand for?",
        options: ["Result", "Reality", "Review", "Reflection"],
        ans: 1
      },
      {
        q: "Which of the following is an example of an open, non-judgmental coaching question?",
        options: [
          "Why did you fail to engage the back row during the reading session?",
          "Don't you think using flashcards would have solved your pacing problem?",
          "What strategies did you notice working best when students moved into their small groups?",
          "Can't you see that the students were bored by your lecture?"
        ],
        ans: 2
      },
      {
        q: "What is the recommended speaking time ratio between mentor and teacher during a reflective post-observation debrief?",
        options: [
          "Mentor 80% / Teacher 20%",
          "Mentor 50% / Teacher 50%",
          "Mentor 30% / Teacher 70%",
          "Mentor 10% / Teacher 90%"
        ],
        ans: 2
      }
    ]
  },
  4: {
    title: "Module 4: Data-Driven Monitoring, Learner Progression Analytics & Multi-School Triage",
    meta: "Estimated Duration: 6 Hours · Core Focus: Tracking group movement tables, identifying stagnation, and dynamic school visit allocation",
    videos: [
      { title: "Analyzing TaRL Progression Data", url: "https://www.youtube.com/embed/rX04c4Q7uSk", desc: "Interpreting baseline to midline transition matrices" },
      { title: "Multi-School Triage & Resource Allocation", url: "https://www.youtube.com/embed/1k2jK0Qr8xY", desc: "Prioritizing school support visits using performance dashboards" }
    ],
    resources: [
      { title: "TaRL Data Tracking Templates", url: "https://teachingatherightlevel.org/", desc: "Excel and paper-based group movement tracking sheets" },
      { title: "Cluster Monitoring Guidelines", url: "https://imagine1day.org/", desc: "Woreda and cluster-level supportive supervision protocols" }
    ],
    html: `
      <div class="card">
        <h3>📖 Module 4 Core Concepts</h3>
        <p>Data should never be collected merely for upward reporting to donors or government ministries; it must be an immediate operational compass for mentors. By analyzing baseline-to-midline transition matrices, mentors identify which schools or classrooms are experiencing stagnation.</p>
        <p><strong>The Triage Protocol:</strong></p>
        <ul>
          <li><strong>Tier 1 (High Progress):</strong> Schools showing rapid movement from Beginner/Letter to Word/Story receive light monthly check-ins and peer-sharing opportunities.</li>
          <li><strong>Tier 2 (Moderate/Stagnant):</strong> Schools with stalled progression receive bi-weekly co-teaching support and assessment audits.</li>
          <li><strong>Tier 3 (Critical/Regressing):</strong> Schools with declining scores receive intensive weekly intervention, leadership engagement, and material replenishment.</li>
        </ul>
        <div class="callout warn"><strong>Core Principle:</strong> Allocate your scarcest resource—mentor travel time—dynamically to the schools that need support the most, not simply to those closest to the tarmac road.</div>
      </div>
    `,
    exam: [
      {
        q: "What is the primary purpose of analyzing a baseline-to-midline group movement table?",
        options: [
          "To compile statistics for annual donor reports without acting on them.",
          "To identify stagnant classrooms or learning groups early and deploy targeted coaching support.",
          "To rank teachers for salary reductions if scores drop.",
          "To determine which students should be expelled from school."
        ],
        ans: 1
      },
      {
        q: "How should a cluster supervisor prioritize school visits under a data-driven triage model?",
        options: [
          "Visit schools in alphabetical order regardless of performance.",
          "Visit only the schools located closest to the district capital.",
          "Allocate more frequent coaching visits to schools with stagnant or lagging learner progression.",
          "Visit only top-performing showcase schools."
        ],
        ans: 2
      },
      {
        q: "What action is most appropriate when a classroom shows zero movement from Beginner to Letter level after 4 weeks of TaRL implementation?",
        options: [
          "Ignore the data and assume children will catch up naturally.",
          "Conduct an assessment audit and co-teach a session with the teacher to diagnose grouping or pacing issues.",
          "Close down the TaRL program in that school immediately.",
          "Blame the students for lack of motivation."
        ],
        ans: 1
      }
    ]
  },
  5: {
    title: "Module 5: Multi-Tiered Governance, Communities of Practice & Printable Field Toolkits",
    meta: "Estimated Duration: 6 Hours · Core Focus: Cluster-level PLCs, WhatsApp moderation, institutional sustainability, and final certification",
    videos: [
      { title: "Facilitating Effective Communities of Practice (CoP)", url: "https://www.youtube.com/embed/3n6pN_q8kZE", desc: "Running engaging cluster teacher meetings and peer learning circles" },
      { title: "Scaling TaRL Sustainably within Government Systems", url: "https://www.youtube.com/embed/rX04c4Q7uSk", desc: "Institutionalizing coaching within woreda and regional education structures" }
    ],
    resources: [
      { title: "Community of Practice Facilitation Guide", url: "https://teachingatherightlevel.org/", desc: "Agendas, protocol templates, and peer observation rubrics" },
      { title: "Imagine 1Day Field Toolkit Repository", url: "https://imagine1day.org/", desc: "Printable observation forms, coaching logs, and supervisor checklists" }
    ],
    html: `
      <div class="card">
        <h3>📖 Module 5 Core Concepts</h3>
        <p>Sustainable educational change outlives project funding cycles by embedding coaching structures directly into existing government frameworks—from school clusters and Woreda Education Offices to Regional Bureaus.</p>
        <p><strong>Communities of Practice (CoP):</strong> Monthly cluster meetings where teachers and mentors share classroom artifacts, troubleshoot difficult concepts, and model CAMaL games.</p>
        <p><strong>Digital Peer Networks:</strong> Moderated WhatsApp or Telegram groups where educators share short video clips of successful activities, ask quick pedagogical questions, and celebrate weekly wins.</p>
        <div class="callout succ"><strong>Congratulations:</strong> Completing this module prepares you for the Comprehensive Final Exam and issuance of your verified Professional Certificate in TaRL Coaching &amp; Mentoring.</div>
      </div>
    `,
    exam: [
      {
        q: "What is the key objective of establishing school-cluster Communities of Practice (CoP)?",
        options: [
          "To enforce administrative discipline and check teacher attendance registers.",
          "To provide a collaborative space for teachers and mentors to share successes, solve challenges, and model activities.",
          "To organize fundraising events for school canteens.",
          "To conduct high-stakes personnel evaluations for promotion."
        ],
        ans: 1
      },
      {
        q: "How do moderated digital networks (such as WhatsApp or Telegram groups) support TaRL implementation?",
        options: [
          "By replacing all in-person classroom observations entirely.",
          "By enabling quick peer sharing of video clips, activity ideas, and rapid troubleshooting between school visits.",
          "By serving as a repository for confidential student disciplinary records.",
          "By broadcasting official government political announcements."
        ],
        ans: 1
      },
      {
        q: "What ensures the long-term sustainability of TaRL coaching after NGO project support concludes?",
        options: [
          "Relying exclusively on foreign volunteers to visit schools.",
          "Embedding coaching protocols and cluster reviews into routine government education structures (Woreda/Cluster offices).",
          "Stopping all classroom observations to save operational costs.",
          "Charging student tuition fees for remedial instruction."
        ],
        ans: 1
      }
    ]
  }
};

/* ============================================================
   REGISTRATION & AUTHENTICATION LOGIC
============================================================ */
function doRegister() {
  const name = val("regName"), email = val("regEmail"), phone = val("regPhone"), country = val("regCountry"), role = val("regRole"), org = val("regOrg"), motivation = val("regMotivation");
  if(!name || !email || !phone || !country) {
    alertBox("regAlert", "d", "Please fill in all required fields (*).");
    return;
  }
  let pending = DB.get("pending");
  if(pending.some(u => u.email === email)) {
    alertBox("regAlert", "w", "An application with this email is already pending approval.");
    return;
  }
  const userObj = { name, email, phone, country, role, org, motivation, date: new Date().toISOString() };
  pending.push(userObj);
  DB.set("pending", pending);
  alertBox("regAlert", "s", "Registration submitted successfully! You can also notify the administrator directly via email.");
  
  // Show mailto button
  const mailSubject = encodeURIComponent("TaRL Course Registration - " + name);
  const mailBody = encodeURIComponent(`Dear ${CFG.adminName},\n\nI have registered for the TaRL Coaching & Mentoring course.\n\nName: ${name}\nEmail: ${email}\nRole: ${role}\nOrganization: ${org}\nCountry: ${country}\n\nPlease approve my registration and issue my approval code.\n\nBest regards,\n${name}`);
  const mailBtn = document.getElementById("regMailBtn");
  mailBtn.href = `mailto:${CFG.adminEmail}?subject=${mailSubject}&body=${mailBody}`;
  document.getElementById("regEmailBox").classList.remove("hidden");
}

function doLogin() {
  const email = val("loginEmail"), code = val("loginCode");
  if(!email || !code) {
    alertBox("loginAlert", "d", "Please enter both email and approval code.");
    return;
  }
  let users = DB.get("users");
  let u = users.find(x => x.email === email && x.code === code);
  if(!u) {
    alertBox("loginAlert", "d", "Invalid email or approval code, or your registration is not yet approved.");
    return;
  }
  currentUser = u;
  sessionStorage.setItem("tarl_user", JSON.stringify(u));
  show("view-dashboard");
}

function doAdminLogin() {
  const code = val("adminCodeIn");
  if(code === CFG.adminCode) {
    sessionStorage.setItem("admin", "true");
    show("view-admin");
  } else {
    alertBox("adminLoginAlert", "d", "Incorrect administrator code. (Hint: 54025402)");
  }
}

function doLogout() {
  currentUser = null;
  sessionStorage.removeItem("tarl_user");
  show("view-landing");
}

/* ============================================================
   ADMIN PANEL RENDERER
============================================================ */
function renderAdmin() {
  if(!sessionStorage.getItem("admin")) {
    show("view-admin-login");
    return;
  }
  let pending = DB.get("pending");
  let users = DB.get("users");
  let certs = DB.get("certs");

  // Pending
  let pHtml = "";
  if(pending.length === 0) pHtml = "<p style='color:var(--gray)'>No pending registrations.</p>";
  else {
    pHtml = "<table><tr><th>Name</th><th>Email</th><th>Role</th><th>Org</th><th>Action</th></tr>";
    pending.forEach((p, idx) => {
      pHtml += `<tr><td>${p.name}</td><td>${p.email}</td><td>${p.role}</td><td>${p.org||'—'}</td><td><button class="btn btn-succ btn-sm" onclick="approveUser(${idx})">Approve</button></td></tr>`;
    });
    pHtml += "</table>";
  }
  document.getElementById("pendingList").innerHTML = pHtml;

  // Users
  let uHtml = "";
  if(users.length === 0) uHtml = "<p style='color:var(--gray)'>No approved users yet.</p>";
  else {
    uHtml = "<table><tr><th>Name</th><th>Email</th><th>Role</th><th>Approval Code</th></tr>";
    users.forEach(u => {
      uHtml += `<tr><td>${u.name}</td><td>${u.email}</td><td>${u.role}</td><td><code>${u.code}</code></td></tr>`;
    });
    uHtml += "</table>";
  }
  document.getElementById("usersList").innerHTML = uHtml;

  // Certs
  let cHtml = "";
  if(certs.length === 0) cHtml = "<p style='color:var(--gray)'>No certificates issued yet.</p>";
  else {
    cHtml = "<table><tr><th>Certificate ID</th><th>Learner Name</th><th>Email</th><th>Date</th></tr>";
    certs.forEach(c => {
      cHtml += `<tr><td><code>${c.id}</code></td><td>${c.name}</td><td>${c.email}</td><td>${c.date}</td></tr>`;
    });
    cHtml += "</table>";
  }
  document.getElementById("certsList").innerHTML = cHtml;
}

function approveUser(idx) {
  let pending = DB.get("pending");
  let users = DB.get("users");
  let u = pending.splice(idx, 1)[0];
  const code = "TaRL-" + Math.floor(100000 + Math.random() * 900000);
  u.code = code;
  users.push(u);
  DB.set("pending", pending);
  DB.set("users", users);
  alert("User approved successfully! Generated code: " + code);
  renderAdmin();
}

/* ============================================================
   DASHBOARD & MODULE VIEWER
============================================================ */
function renderDashboard() {
  if(!currentUser) {
    show("view-login");
    return;
  }
  document.getElementById("dashName").textContent = currentUser.name;
  let prog = DB.prog(currentUser.email);
  let passedCount = 0;
  for(let i=1; i<=CFG.totalModules; i++) {
    if(prog["mod_" + i]) passedCount++;
  }
  let pct = Math.round((passedCount / CFG.totalModules) * 100);
  
  document.getElementById("statDone").textContent = passedCount;
  document.getElementById("statPct").textContent = pct + "%";
  document.getElementById("pctLabel").textContent = pct + "%";
  document.getElementById("progressBar").style.width = pct + "%";

  let finalScore = prog.final_score !== undefined ? prog.final_score + "%" : "—";
  document.getElementById("statFinal").textContent = finalScore;

  // Render modules list
  let mHtml = "";
  for(let i=1; i<=CFG.totalModules; i++) {
    let mod = MODULES[i];
    let isDone = prog["mod_" + i];
    mHtml += `
      <div class="mod-item ${isDone ? 'done' : ''}">
        <div class="mod-num">${i}</div>
        <div class="mod-info">
          <h4>${mod.title}</h4>
          <div class="mod-meta">${mod.meta}</div>
        </div>
        <div>
          <button class="btn ${isDone ? 'btn-succ' : 'btn-s'} btn-sm" onclick="openModule(${i})">${isDone ? 'Review Module ✓' : 'Start Module →'}</button>
        </div>
      </div>
    `;
  }
  document.getElementById("moduleList").innerHTML = mHtml;

  // Final exam box
  let finalBox = document.getElementById("finalBox");
  if(passedCount === CFG.totalModules) {
    let finalPassed = prog.final_passed;
    finalBox.innerHTML = `
      <div class="card" style="background:var(--pl);border:2px solid var(--p);text-align:center">
        <h3>🎉 All Modules Completed!</h3>
        <p>You have successfully passed all 5 module exams. You are now ready to take the Comprehensive Final Certification Exam.</p>
        <button class="btn btn-p" onclick="openFinalExam()">${finalPassed ? 'Retake Final Exam' : 'Take Comprehensive Final Exam'}</button>
        ${finalPassed ? '<br><br><button class="btn btn-succ" onclick="openCertificate()">🏆 View &amp; Print Official Certificate</button>' : ''}
      </div>
    `;
  } else {
    finalBox.innerHTML = `
      <div class="card" style="background:#fff;text-align:center;color:var(--gray)">
        <p>🔒 Comprehensive Final Exam unlocks once all 5 module exams are successfully passed.</p>
      </div>
    `;
  }
}

function openModule(num) {
  currentMod = num;
  let mod = MODULES[num];
  document.getElementById("modLabel").textContent = `Module ${num} of ${CFG.totalModules}`;
  document.getElementById("modTitle").textContent = mod.title;
  document.getElementById("modMeta").textContent = mod.meta;

  let content = mod.html;
  
  // Videos
  if(mod.videos && mod.videos.length > 0) {
    content += `<h2>🎥 Instructional Video Resources</h2>`;
    mod.videos.forEach(v => {
      content += `
        <div class="card">
          <h4>${v.title}</h4>
          <p style="font-size:.9rem;color:var(--gray)">${v.desc}</p>
          <div class="video-embed"><iframe src="${v.url}" allowfullscreen></iframe></div>
        </div>
      `;
    });
  }

  // Resources
  if(mod.resources && mod.resources.length > 0) {
    content += `<h2>📂 Downloadable Field Toolkits &amp; References</h2><ul class="res-list">`;
    mod.resources.forEach(r => {
      content += `
        <li>
          <div class="icon">📄</div>
          <div>
            <div class="res-title"><a href="${r.url}" target="_blank">${r.title} ↗</a></div>
            <div class="res-desc">${r.desc}</div>
          </div>
        </li>
      `;
    });
    content += `</ul>`;
  }

  document.getElementById("moduleContent").innerHTML = content;
  show("view-module");
}

function prevModule() {
  if(currentMod > 1) openModule(currentMod - 1);
}
function nextModule() {
  if(currentMod < CFG.totalModules) openModule(currentMod + 1);
}

function openExamForCurrent() {
  openModuleExam(currentMod);
}

/* ============================================================
   EXAM & CERTIFICATE ENGINE
============================================================ */
function openModuleExam(modNum) {
  currentMod = modNum;
  let mod = MODULES[modNum];
  currentExam = { type: 'mod', id: modNum, questions: mod.exam, passMark: CFG.modPass, title: `Module ${modNum} Exam: ${mod.title}` };
  renderExamUI();
}

function openFinalExam() {
  // Combine questions from all 5 modules for comprehensive final exam
  let allQ = [];
  for(let i=1; i<=CFG.totalModules; i++) {
    MODULES[i].exam.forEach(q => allQ.push(q));
  }
  currentExam = { type: 'final', id: 'final', questions: allQ, passMark: CFG.finalPass, title: "Comprehensive Final Certification Exam" };
  renderExamUI();
}

function renderExamUI() {
  document.getElementById("examTitle").textContent = currentExam.title;
  document.getElementById("examPass").textContent = currentExam.passMark;
  document.getElementById("examSections").textContent = currentExam.questions.length + " Questions";

  let html = "";
  currentExam.questions.forEach((q, idx) => {
    html += `
      <div class="q-card" id="qcard_${idx}">
        <div class="q-text"><span class="q-num">${idx + 1}</span>${q.q}</div>
        <div style="margin-top:.8rem">
    `;
    q.options.forEach((opt, optIdx) => {
      html += `
        <label class="option">
          <input type="radio" name="q_${idx}" value="${optIdx}">
          <span>${opt}</span>
        </label>
      `;
    });
    html += `</div></div>`;
  });
  html += `<button class="btn btn-succ btn-blk" onclick="submitExam()">Submit Exam Answers</button><div id="examResult" style="margin-top:1rem"></div>`;
  document.getElementById("examContainer").innerHTML = html;
  show("view-exam");
}

function submitExam() {
  let score = 0;
  let total = currentExam.questions.length;
  currentExam.questions.forEach((q, idx) => {
    let sel = document.querySelector(`input[name="q_${idx}"]:checked`);
    if(sel && parseInt(sel.value) === q.ans) {
      score++;
    }
  });

  let pct = Math.round((score / total) * 100);
  let passed = pct >= currentExam.passMark;

  let resDiv = document.getElementById("examResult");
  if(passed) {
    resDiv.innerHTML = `
      <div class="alert alert-s">
        <h3>🎉 Congratulations, You Passed!</h3>
        <p>Your Score: <strong>${score}/${total} (${pct}%)</strong>. Pass mark is ${currentExam.passMark}%. Your progress has been saved.</p>
        <button class="btn btn-s" onclick="show('view-dashboard')">Return to Dashboard</button>
      </div>
    `;
    // Save progress
    let prog = DB.prog(currentUser.email);
    if(currentExam.type === 'mod') {
      prog["mod_" + currentExam.id] = true;
    } else {
      prog.final_passed = true;
      prog.final_score = pct;
      // Issue certificate record
      let certs = DB.get("certs");
      let certId = "TaRL-CERT-" + Math.floor(100000 + Math.random() * 900000);
      if(!certs.some(c => c.email === currentUser.email)) {
        certs.push({ id: certId, name: currentUser.name, email: currentUser.email, date: new Date().toLocaleDateString() });
        DB.set("certs", certs);
      }
    }
    DB.saveProg(currentUser.email, prog);
  } else {
    resDiv.innerHTML = `
      <div class="alert alert-d">
        <h3>❌ Exam Not Passed</h3>
        <p>Your Score: <strong>${score}/${total} (${pct}%)</strong>. Required pass mark is ${currentExam.passMark}%. Please review the module materials and try again.</p>
        <button class="btn btn-o" onclick="renderExamUI()">Retake Exam</button>
      </div>
    `;
  }
}

function openCertificate() {
  let certs = DB.get("certs");
  let myCert = certs.find(c => c.email === currentUser.email);
  let certId = myCert ? myCert.id : "TaRL-CERT-" + Math.floor(100000 + Math.random() * 900000);
  let issueDate = myCert ? myCert.date : new Date().toLocaleDateString();

  let certHtml = `
    <div class="cert">
      <div class="cert-org">${CFG.adminOrg}</div>
      <div class="cert-title">Certificate of Professional Completion</div>
      <p style="font-size:1.05rem;color:var(--gray)">This is to certify that</p>
      <div class="cert-name">${currentUser.name}</div>
      <p style="margin-top:.8rem;font-size:1rem">has successfully completed the comprehensive professional development curriculum in</p>
      <h3 style="color:var(--pd);margin:.5rem 0">${CFG.courseName}</h3>
      <p style="font-size:.9rem;color:var(--gray)">Covering 5 Modules, Mentoring Frameworks, Assessment Integrity, Coaching Dialogue, and Data-Driven Monitoring.</p>
      
      <div class="cert-footer">
        <div>
          <div class="sign-line"></div>
          <div class="sign-name">${CFG.adminName}</div>
          <div class="sign-role">${CFG.adminTitle}, ${CFG.adminOrg}</div>
        </div>
        <div>
          <div class="sign-line"></div>
          <div class="sign-name">Cluster / Zonal Education Bureau</div>
          <div class="sign-role">Institutional Certification Authority</div>
        </div>
      </div>
      <div class="cert-id">Certificate Verification ID: ${certId} · Issued Date: ${issueDate}</div>
    </div>
  `;
  document.getElementById("certBox").innerHTML = certHtml;
  show("view-cert");
}

/* ============================================================
   INIT
============================================================ */
window.addEventListener("DOMContentLoaded", () => {
  renderFrontMatter();
  if(currentUser) {
    show("view-dashboard");
  } else {
    show("view-landing");
  }
});
</script>
</body>
</html>

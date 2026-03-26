
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Control Room</title>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root {
  --bg:#0e0f11;--bg2:#16181c;--bg3:#1e2126;--bg4:#252930;
  --border:#2e3138;--border2:#3a3f4a;
  --text:#e8eaf0;--text2:#9199a8;--text3:#5a6070;
  --green:#2ecc8a;--green-dim:#1a3d2e;
  --amber:#f0a500;--amber-dim:#3a2800;
  --red:#e85555;--red-dim:#3a1515;
  --blue:#4d9eff;--blue-dim:#0d2240;
  --purple:#9b7fff;--purple-dim:#221a40;
  --font:'IBM Plex Sans',sans-serif;--mono:'IBM Plex Mono',monospace;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{background:var(--bg);color:var(--text);font-family:var(--font);font-size:14px;min-height:100vh;}
::-webkit-scrollbar{width:4px;height:4px;} ::-webkit-scrollbar-track{background:transparent;} ::-webkit-scrollbar-thumb{background:var(--border2);border-radius:2px;}

/* NAV */
.nav{display:flex;align-items:center;gap:2px;padding:8px 12px;background:var(--bg2);border-bottom:1px solid var(--border);flex-wrap:wrap;gap:4px;}
.nav-brand{font-family:var(--mono);font-size:12px;color:var(--green);margin-right:8px;letter-spacing:.05em;white-space:nowrap;}
.nav-tab{padding:5px 12px;border-radius:5px;font-size:13px;color:var(--text2);cursor:pointer;border:none;background:transparent;font-family:var(--font);transition:all .15s;white-space:nowrap;}
.nav-tab:hover{background:var(--bg3);color:var(--text);}
.nav-tab.active{background:var(--bg3);color:var(--text);border:1px solid var(--border2);}
.nav-spacer{flex:1;}
.nav-time{font-family:var(--mono);font-size:11px;color:var(--text3);}

/* VIEWS */
.view{display:none;padding:14px;}
.view.active{display:block;}

/* TIMER STRIP */
.timer-strip{display:flex;align-items:center;gap:10px;background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:10px 14px;margin-bottom:12px;flex-wrap:wrap;}
.timer-big{font-family:var(--mono);font-size:26px;font-weight:500;color:var(--green);min-width:65px;}
.timer-big.urgent{color:var(--red);animation:pulse 1s infinite;}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.6}}
.timer-bar-wrap{flex:1;min-width:80px;height:5px;background:var(--bg4);border-radius:3px;overflow:hidden;}
.timer-bar-fill{height:100%;background:var(--green);border-radius:3px;transition:width 1s linear;}
.timer-bar-fill.urgent{background:var(--red);}
.cycles-badge{font-family:var(--mono);font-size:11px;color:var(--text3);white-space:nowrap;}

/* COLS */
.cols3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px;}
@media(max-width:800px){.cols3{grid-template-columns:1fr 1fr;}}
@media(max-width:500px){.cols3{grid-template-columns:1fr;}}

/* CARD */
.card{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:12px;}
.card-title{font-size:11px;font-weight:500;color:var(--text3);letter-spacing:.08em;text-transform:uppercase;margin-bottom:8px;}

/* BUTTONS */
.tbtn{padding:5px 12px;border-radius:5px;border:1px solid var(--border2);background:var(--bg3);color:var(--text);font-size:12px;cursor:pointer;font-family:var(--font);}
.tbtn:hover{border-color:var(--green);color:var(--green);}
.tbtn.active-btn{border-color:var(--green);color:var(--green);}
.btn-primary{padding:6px 16px;background:var(--green-dim);border:1px solid var(--green);border-radius:5px;color:var(--green);font-size:13px;cursor:pointer;font-family:var(--font);}
.btn-primary:hover{background:var(--green);color:#000;}
.btn-cancel{padding:6px 16px;background:transparent;border:1px solid var(--border2);border-radius:5px;color:var(--text2);font-size:13px;cursor:pointer;font-family:var(--font);}
.btn-cancel:hover{border-color:var(--text2);color:var(--text);}
.btn-danger{padding:6px 14px;background:transparent;border:1px solid var(--red-dim);border-radius:5px;color:var(--red);font-size:12px;cursor:pointer;font-family:var(--font);}
.btn-danger:hover{background:var(--red-dim);}

/* TASK ITEMS */
.task-item{display:flex;align-items:center;gap:8px;padding:6px 8px;border-radius:5px;background:var(--bg3);margin-bottom:4px;}
.task-cb{width:14px;height:14px;accent-color:var(--green);cursor:pointer;flex-shrink:0;}
.task-label{flex:1;font-size:13px;color:var(--text);}
.task-item.done .task-label{text-decoration:line-through;color:var(--text3);}
.task-del{background:none;border:none;color:var(--text3);cursor:pointer;font-size:13px;padding:0 2px;line-height:1;}
.task-del:hover{color:var(--red);}
.rec-badge{font-size:10px;padding:2px 6px;border-radius:10px;font-weight:500;background:var(--green-dim);color:var(--green);white-space:nowrap;}
.rec-badge.done{background:var(--bg4);color:var(--text3);}

/* ADD ROW */
.add-row{display:flex;gap:5px;margin-top:7px;}
.add-row input,.add-inp{flex:1;background:var(--bg3);border:1px solid var(--border2);border-radius:5px;padding:6px 9px;color:var(--text);font-family:var(--font);font-size:13px;}
.add-row input:focus,.add-inp:focus{outline:none;border-color:var(--green);}
.add-row button{padding:5px 11px;background:var(--bg3);border:1px solid var(--border2);border-radius:5px;color:var(--green);font-size:13px;cursor:pointer;font-family:var(--font);}
.add-row button:hover{border-color:var(--green);background:var(--green-dim);}

/* CL TABS */
.cl-tabs{display:flex;gap:4px;flex-wrap:wrap;margin-bottom:7px;}
.cl-tab{font-size:11px;padding:2px 9px;border-radius:10px;border:1px solid var(--border);background:var(--bg3);color:var(--text2);cursor:pointer;}
.cl-tab.active{border-color:var(--blue);color:var(--blue);background:var(--blue-dim);}
.prog-row{display:flex;align-items:center;gap:7px;margin-bottom:7px;}
.prog-bar{flex:1;height:4px;background:var(--bg4);border-radius:2px;overflow:hidden;}
.prog-fill{height:100%;background:var(--green);border-radius:2px;transition:width .3s;}
.prog-txt{font-size:11px;color:var(--text3);font-family:var(--mono);min-width:28px;text-align:right;}

/* NOTES */
.notes-layout{display:grid;grid-template-columns:200px 1fr;gap:10px;min-height:480px;}
@media(max-width:600px){.notes-layout{grid-template-columns:1fr;}}
.notes-sidebar{display:flex;flex-direction:column;gap:7px;}
.notes-list{display:flex;flex-direction:column;gap:3px;flex:1;max-height:400px;overflow-y:auto;}
.note-entry{padding:7px 9px;border-radius:5px;border:1px solid transparent;cursor:pointer;background:var(--bg3);}
.note-entry:hover{border-color:var(--border2);}
.note-entry.active{border-color:var(--blue);background:var(--blue-dim);}
.note-entry-time{font-size:10px;color:var(--text3);font-family:var(--mono);margin-bottom:1px;}
.note-entry-title{font-size:12px;color:var(--text);font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.note-editor{display:flex;flex-direction:column;gap:7px;}
.note-editor textarea{flex:1;min-height:280px;background:var(--bg2);border:1px solid var(--border);border-radius:7px;padding:11px;color:var(--text);font-family:var(--mono);font-size:13px;resize:vertical;line-height:1.7;}
.note-editor textarea:focus{outline:none;border-color:var(--blue);}
.note-title-input{background:var(--bg3);border:1px solid var(--border);border-radius:5px;padding:6px 11px;color:var(--text);font-family:var(--font);font-size:14px;font-weight:500;width:100%;}
.note-title-input:focus{outline:none;border-color:var(--blue);}

/* TEMPLATES */
.tpl-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:7px;margin-bottom:12px;}
.tpl-btn{padding:8px 10px;border-radius:6px;border:1px solid var(--border2);background:var(--bg3);color:var(--text2);font-size:12px;cursor:pointer;font-family:var(--font);text-align:left;transition:all .15s;}
.tpl-btn:hover{border-color:var(--amber);color:var(--amber);background:var(--amber-dim);}
.tpl-icon{font-size:15px;display:block;margin-bottom:3px;}
.tpl-name{font-weight:500;display:block;}
.tpl-desc{font-size:11px;color:var(--text3);margin-top:1px;display:block;}

/* TAGS */
.tag{display:inline-block;font-size:10px;padding:2px 6px;border-radius:10px;font-weight:500;margin-right:3px;}
.tag-incident{background:var(--red-dim);color:var(--red);}
.tag-response{background:var(--purple-dim);color:var(--purple);}
.tag-obs{background:var(--bg4);color:var(--text2);}
.tag-task{background:var(--green-dim);color:var(--green);}

/* LOG */
.log-entry{display:flex;gap:9px;padding:7px 9px;border-radius:5px;background:var(--bg3);margin-bottom:4px;border-left:3px solid var(--border2);}
.log-entry.incident{border-left-color:var(--red);}
.log-entry.response{border-left-color:var(--purple);}
.log-entry.task{border-left-color:var(--green);}
.log-entry.note{border-left-color:var(--blue);}
.log-entry.scan{border-left-color:var(--amber);}
.log-time{font-family:var(--mono);font-size:11px;color:var(--text3);min-width:48px;padding-top:1px;}
.log-body{flex:1;}
.log-title{font-size:13px;color:var(--text);font-weight:500;}
.log-detail{font-size:12px;color:var(--text2);margin-top:2px;line-height:1.5;}

/* SCAN SITES */
.sites-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:8px;margin-top:10px;}
.site-card{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:11px;}
.site-card.ok{border-left:3px solid var(--green);}
.site-card.due{border-left:3px solid var(--amber);}
.site-card.overdue{border-left:3px solid var(--red);}
.site-card.never{border-left:3px solid var(--text3);}
.site-header{display:flex;align-items:center;gap:6px;margin-bottom:7px;}
.site-name{font-size:13px;font-weight:500;color:var(--text);flex:1;}
.site-badge{font-size:10px;padding:2px 6px;border-radius:10px;font-weight:500;}
.badge-nerc{background:#1a2a3a;color:#4d9eff;}
.badge-ok{background:var(--green-dim);color:var(--green);}
.badge-due{background:var(--amber-dim);color:var(--amber);}
.badge-overdue{background:var(--red-dim);color:var(--red);}
.badge-never{background:var(--bg4);color:var(--text3);}
.site-meta{font-size:11px;color:var(--text3);margin-bottom:5px;font-family:var(--mono);}
.site-actions{display:flex;gap:5px;flex-wrap:wrap;}
.scan-btn{padding:4px 10px;border-radius:4px;border:1px solid var(--green);background:var(--green-dim);color:var(--green);font-size:11px;cursor:pointer;font-family:var(--font);}
.scan-btn:hover{background:var(--green);color:#000;}
.site-note-preview{font-size:11px;color:var(--text3);margin-top:5px;font-style:italic;border-top:1px solid var(--border);padding-top:5px;}
.filter-row{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:10px;align-items:center;}
.filter-btn{padding:4px 11px;border-radius:10px;border:1px solid var(--border);background:var(--bg3);color:var(--text2);font-size:12px;cursor:pointer;font-family:var(--font);}
.filter-btn.active{border-color:var(--blue);color:var(--blue);background:var(--blue-dim);}
.stat-row{display:flex;gap:7px;flex-wrap:wrap;margin-bottom:10px;}
.stat-chip{background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:5px 11px;}
.stat-chip .s-val{font-family:var(--mono);font-size:17px;font-weight:500;color:var(--text);display:block;}
.stat-chip .s-lbl{font-size:11px;color:var(--text3);}

/* MODAL */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.75);display:flex;align-items:center;justify-content:center;z-index:100;padding:12px;}
.modal-overlay.hidden{display:none;}
.modal{background:var(--bg2);border:1px solid var(--border2);border-radius:10px;padding:18px;width:440px;max-width:100%;max-height:90vh;overflow-y:auto;}
.modal-title{font-size:15px;font-weight:500;margin-bottom:12px;color:var(--text);}
.modal label{font-size:12px;color:var(--text2);display:block;margin-bottom:3px;margin-top:9px;}
.modal input,.modal select,.modal textarea{width:100%;background:var(--bg3);border:1px solid var(--border2);border-radius:5px;padding:6px 9px;color:var(--text);font-family:var(--font);font-size:13px;}
.modal input:focus,.modal select:focus,.modal textarea:focus{outline:none;border-color:var(--blue);}
.modal textarea{min-height:70px;resize:vertical;font-family:var(--mono);}
.modal select option{background:var(--bg3);}
.modal-actions{display:flex;gap:7px;margin-top:14px;justify-content:flex-end;}

/* HANDOFF */
.handoff-box{background:var(--bg3);border:1px solid var(--border2);border-radius:8px;padding:14px;font-family:var(--mono);font-size:12px;line-height:1.8;color:var(--text2);white-space:pre-wrap;max-height:420px;overflow-y:auto;}
.handoff-section{color:var(--amber);font-weight:500;}
.handoff-ok{color:var(--green);}
.handoff-warn{color:var(--red);}

/* TOAST */
.toast{position:fixed;bottom:18px;right:18px;background:var(--red);color:#fff;padding:9px 16px;border-radius:6px;font-size:13px;font-weight:500;opacity:0;transition:opacity .3s;pointer-events:none;z-index:200;font-family:var(--mono);}
.toast.show{opacity:1;}
.empty{font-size:12px;color:var(--text3);text-align:center;padding:14px 0;}
select{background:var(--bg3);border:1px solid var(--border2);border-radius:5px;padding:5px 8px;color:var(--text);font-family:var(--font);font-size:13px;}
select option{background:var(--bg3);}
</style>
</head>
<body>

<div class="nav">
  <div class="nav-brand">◈ CTRL ROOM</div>
  <button class="nav-tab active" onclick="switchView('ops',this)">Ops</button>
  <button class="nav-tab" onclick="switchView('scans',this)">Scans</button>
  <button class="nav-tab" onclick="switchView('notes',this)">Notes</button>
  <button class="nav-tab" onclick="switchView('log',this)">Log</button>
  <div class="nav-spacer"></div>
  <div class="nav-time" id="nav-clock"></div>
</div>

<!-- OPS VIEW -->
<div class="view active" id="view-ops">
  <div class="timer-strip">
    <div class="timer-big" id="timer-disp">30:00</div>
    <div class="timer-bar-wrap"><div class="timer-bar-fill" id="timer-fill" style="width:100%"></div></div>
    <span class="cycles-badge" id="cycles-badge">0 cycles</span>
    <button class="tbtn" id="timer-btn" onclick="toggleTimer()">Start</button>
    <button class="tbtn" onclick="resetTimer()">Reset</button>
  </div>
  <div class="cols3">
    <div class="card">
      <div class="card-title">Recurring tasks</div>
      <div id="rec-list"></div>
      <div class="add-row">
        <input id="rec-inp" placeholder="Add recurring task..." onkeydown="if(event.key==='Enter')addRec()">
        <button onclick="addRec()">+</button>
      </div>
    </div>
    <div class="card">
      <div class="card-title">Ad hoc tasks</div>
      <div id="adhoc-list" style="max-height:250px;overflow-y:auto;"></div>
      <div class="add-row">
        <input id="adhoc-inp" placeholder="Quick capture..." onkeydown="if(event.key==='Enter')addAdhoc()">
        <button onclick="addAdhoc()">+</button>
      </div>
    </div>
    <div class="card">
      <div class="card-title">Checklists</div>
      <div class="cl-tabs" id="cl-tabs"></div>
      <div class="prog-row" id="cl-prog-row" style="display:none">
        <div class="prog-bar"><div class="prog-fill" id="cl-prog-fill" style="width:0%"></div></div>
        <div class="prog-txt" id="cl-prog-txt">0/0</div>
      </div>
      <div id="cl-items" style="max-height:190px;overflow-y:auto;"></div>
      <div class="add-row" style="margin-top:7px;flex-wrap:wrap;gap:4px;">
        <input id="cl-list-inp" placeholder="New list..." onkeydown="if(event.key==='Enter')addClList()" style="max-width:105px;flex:none;">
        <button onclick="addClList()" style="font-size:11px;">+ List</button>
        <input id="cl-item-inp" placeholder="Add item..." onkeydown="if(event.key==='Enter')addClItem()" style="flex:1;display:none;">
        <button id="cl-item-btn" onclick="addClItem()" style="display:none;font-size:11px;">+</button>
      </div>
    </div>
  </div>
</div>

<!-- SCANS VIEW -->
<div class="view" id="view-scans">
  <div style="display:flex;gap:8px;align-items:center;margin-bottom:10px;flex-wrap:wrap;">
    <button class="btn-primary" onclick="openModal('modal-add-site')">+ Add site</button>
    <button class="tbtn" onclick="scanAll()">Scan all NERC</button>
    <div class="nav-spacer"></div>
    <span id="scan-next-due" style="font-family:var(--mono);font-size:11px;color:var(--text3);"></span>
  </div>
  <div class="stat-row" id="scan-stats"></div>
  <div class="filter-row">
    <button class="filter-btn active" onclick="setSiteFilter('all',this)">All</button>
    <button class="filter-btn" onclick="setSiteFilter('overdue',this)">Overdue</button>
    <button class="filter-btn" onclick="setSiteFilter('due',this)">Due soon</button>
    <button class="filter-btn" onclick="setSiteFilter('ok',this)">OK</button>
    <button class="filter-btn" onclick="setSiteFilter('nerc',this)">NERC only</button>
  </div>
  <div class="sites-grid" id="sites-grid"></div>
</div>

<!-- NOTES VIEW -->
<div class="view" id="view-notes">
  <div class="tpl-grid" id="tpl-grid"></div>
  <div class="notes-layout">
    <div class="notes-sidebar">
      <div class="card-title" style="padding:0 2px;">Notes log</div>
      <button class="tbtn" style="text-align:center;width:100%;" onclick="newBlankNote()">+ New note</button>
      <div class="notes-list" id="notes-list"></div>
    </div>
    <div class="card note-editor">
      <div id="note-no-sel" style="color:var(--text3);font-size:13px;padding:20px;text-align:center;">Select a note or use a template above</div>
      <div id="note-form" style="display:none;flex-direction:column;gap:7px;height:100%;">
        <div style="display:flex;gap:6px;align-items:center;flex-wrap:wrap;">
          <input class="note-title-input" id="note-title" placeholder="Note title..." style="flex:1;min-width:120px;">
          <select id="note-tag">
            <option value="obs">Observation</option>
            <option value="incident">Incident</option>
            <option value="response">Response</option>
            <option value="task">Task note</option>
          </select>
          <button class="btn-primary" onclick="saveNote()">Save</button>
          <button class="btn-cancel" onclick="deleteNote()">Del</button>
        </div>
        <textarea id="note-body" placeholder="Start typing..."></textarea>
        <div style="font-size:11px;color:var(--text3);" id="note-meta"></div>
      </div>
    </div>
  </div>
</div>

<!-- LOG VIEW -->
<div class="view" id="view-log">
  <div class="stat-row" id="log-stats"></div>
  <div style="display:flex;gap:7px;margin-bottom:10px;align-items:center;flex-wrap:wrap;">
    <select id="log-filter" onchange="renderLog()">
      <option value="all">All entries</option>
      <option value="incident">Incidents</option>
      <option value="response">Responses</option>
      <option value="task">Tasks</option>
      <option value="note">Notes</option>
      <option value="scan">Scans</option>
    </select>
    <button class="tbtn" onclick="openHandoff()">🔄 Shift handoff</button>
    <button class="btn-danger" onclick="clearLog()">Clear log</button>
  </div>
  <div id="log-list" style="max-height:500px;overflow-y:auto;"></div>
</div>

<!-- HANDOFF MODAL -->
<div class="modal-overlay hidden" id="modal-handoff">
  <div class="modal" style="width:520px;">
    <div class="modal-title">🔄 Shift handoff summary</div>
    <div class="handoff-box" id="handoff-content"></div>
    <div class="modal-actions">
      <button class="tbtn" onclick="copyHandoff()">Copy text</button>
      <button class="btn-cancel" onclick="closeModal('modal-handoff')">Close</button>
    </div>
  </div>
</div>

<!-- ADD SITE MODAL -->
<div class="modal-overlay hidden" id="modal-add-site">
  <div class="modal">
    <div class="modal-title" id="site-modal-title">Add site</div>
    <input type="hidden" id="site-edit-id">
    <label>Site name</label>
    <input id="site-name" placeholder="e.g. Station Alpha, Gate B...">
    <label>NERC site?</label>
    <select id="site-nerc"><option value="0">No</option><option value="1">Yes</option></select>
    <label>Scan interval (minutes)</label>
    <input id="site-interval" type="number" value="30" min="1">
    <label>Due-soon threshold (minutes before overdue)</label>
    <input id="site-threshold" type="number" value="5" min="1">
    <label>Reference notes</label>
    <textarea id="site-notes" placeholder="Baseline values, what to check, key contacts..."></textarea>
    <div class="modal-actions">
      <button class="btn-cancel" onclick="closeModal('modal-add-site')">Cancel</button>
      <button class="btn-primary" onclick="saveSite()">Save site</button>
    </div>
  </div>
</div>

<!-- SCAN NOTE MODAL -->
<div class="modal-overlay hidden" id="modal-scan-note">
  <div class="modal">
    <div class="modal-title" id="scan-note-title">Log scan</div>
    <input type="hidden" id="scan-note-site-id">
    <label>Scan notes (optional)</label>
    <textarea id="scan-note-body" placeholder="All clear, or note any anomalies..."></textarea>
    <div class="modal-actions">
      <button class="btn-cancel" onclick="closeModal('modal-scan-note')">Cancel</button>
      <button class="btn-primary" onclick="confirmScan()">Log scan</button>
    </div>
  </div>
</div>

<!-- INCIDENT MODAL -->
<div class="modal-overlay hidden" id="modal-incident">
  <div class="modal">
    <div class="modal-title">🚨 Incident report</div>
    <label>Location / zone</label>
    <input id="inc-location" placeholder="Zone, gate, site name...">
    <label>Severity</label>
    <select id="inc-severity"><option>Low</option><option>Medium</option><option selected>High</option><option>Critical</option></select>
    <label>Reported by</label>
    <input id="inc-reporter" placeholder="Name or radio ID...">
    <label>Description</label>
    <textarea id="inc-desc" placeholder="What happened?"></textarea>
    <label>Action taken</label>
    <textarea id="inc-action" placeholder="What did you do?"></textarea>
    <label>Follow-up required?</label>
    <select id="inc-followup"><option value="no">No</option><option value="yes">Yes — open item</option></select>
    <div class="modal-actions">
      <button class="btn-cancel" onclick="closeModal('modal-incident')">Cancel</button>
      <button class="btn-primary" onclick="saveIncident()">Log incident</button>
    </div>
  </div>
</div>

<!-- RESPONSE MODAL -->
<div class="modal-overlay hidden" id="modal-response">
  <div class="modal">
    <div class="modal-title">✅ Correct response log</div>
    <label>Situation / trigger</label>
    <input id="res-situation" placeholder="What prompted this?">
    <label>Who was notified</label>
    <input id="res-notified" placeholder="Names, teams, channels...">
    <label>Procedure followed</label>
    <textarea id="res-procedure" placeholder="Steps taken..."></textarea>
    <label>Resolution / outcome</label>
    <textarea id="res-outcome" placeholder="What was the result?"></textarea>
    <label>Escalation</label>
    <select id="res-escalation"><option>No escalation</option><option>Yes — escalated</option><option>Yes — pending</option></select>
    <div class="modal-actions">
      <button class="btn-cancel" onclick="closeModal('modal-response')">Cancel</button>
      <button class="btn-primary" onclick="saveResponse()">Log response</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
const SK = 'ctrlroom_v4';
let S = {
  recTasks:[], adhocTasks:[], checklists:{}, activeList:null,
  notes:[], activeNote:null,
  logEntries:[],
  sites:[], siteFilter:'all',
  timerRunning:false, timerElapsed:0, timerCycles:0,
  shiftStart: Date.now()
};

function save() {
  try { localStorage.setItem(SK, JSON.stringify(S)); } catch(e) {}
  try { window.storage && window.storage.set(SK, JSON.stringify(S)); } catch(e) {}
}
async function load() {
  let raw = null;
  try { raw = localStorage.getItem(SK); } catch(e) {}
  if (!raw) { try { const r = await window.storage.get(SK); if(r) raw=r.value; } catch(e) {} }
  if (raw) {
    try {
      const p = JSON.parse(raw);
      S = {...S,...p};
      if(!S.checklists) S.checklists={};
      if(!S.notes) S.notes=[];
      if(!S.logEntries) S.logEntries=[];
      if(!S.sites) S.sites=[];
      if(!S.timerCycles) S.timerCycles=0;
      if(!S.shiftStart) S.shiftStart=Date.now();
    } catch(e) {}
  }
  renderAll();
  if (S.timerRunning) startTimerInterval();
  setInterval(refreshScanStatuses, 30000);
  refreshScanStatuses();
}

// CLOCK
function updateClock() {
  document.getElementById('nav-clock').textContent = new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit',second:'2-digit'});
}
setInterval(updateClock,1000); updateClock();

// VIEW SWITCH
function switchView(v, el) {
  document.querySelectorAll('.view').forEach(x=>x.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(x=>x.classList.remove('active'));
  document.getElementById('view-'+v).classList.add('active');
  if(el) el.classList.add('active');
  if(v==='log') renderLog();
  if(v==='scans') { refreshScanStatuses(); renderSites(); }
}

// TIMER
let timerInt=null;
const TOTAL=30*60;
function toggleTimer() {
  if(S.timerRunning){stopTimer();}
  else{S.timerRunning=true;save();startTimerInterval();}
}
function startTimerInterval() {
  document.getElementById('timer-btn').textContent='Stop';
  document.getElementById('timer-btn').classList.add('active-btn');
  timerInt=setInterval(()=>{
    S.timerElapsed++;
    if(S.timerElapsed>=TOTAL){
      S.timerElapsed=0;S.timerCycles++;
      addLog({type:'task',title:'30-min cycle #'+S.timerCycles+' completed',detail:''});
      fireAlert('Cycle #'+S.timerCycles+' complete — time to scan!');
    }
    save();updateTimerUI();
  },1000);
}
function stopTimer(){S.timerRunning=false;clearInterval(timerInt);timerInt=null;document.getElementById('timer-btn').textContent='Start';document.getElementById('timer-btn').classList.remove('active-btn');save();}
function resetTimer(){stopTimer();S.timerElapsed=0;save();updateTimerUI();}
function updateTimerUI(){
  const rem=TOTAL-S.timerElapsed;
  const disp=document.getElementById('timer-disp');
  disp.textContent=String(Math.floor(rem/60)).padStart(2,'0')+':'+String(rem%60).padStart(2,'0');
  const urgent=rem<=120;
  disp.classList.toggle('urgent',urgent);
  const fill=document.getElementById('timer-fill');
  fill.style.width=((rem/TOTAL)*100).toFixed(1)+'%';
  fill.classList.toggle('urgent',urgent);
  document.getElementById('cycles-badge').textContent=S.timerCycles+' cycle'+(S.timerCycles!==1?'s':'');
}

// RECURRING
function addRec(){const v=document.getElementById('rec-inp').value.trim();if(!v)return;S.recTasks.push({id:Date.now(),name:v,done:false});document.getElementById('rec-inp').value='';save();renderRec();}
function toggleRec(id){const t=S.recTasks.find(x=>x.id===id);if(t)t.done=!t.done;save();renderRec();}
function delRec(id){S.recTasks=S.recTasks.filter(x=>x.id!==id);save();renderRec();}
function renderRec(){
  const el=document.getElementById('rec-list');
  if(!S.recTasks.length){el.innerHTML='<div class="empty">No recurring tasks</div>';return;}
  el.innerHTML=S.recTasks.map(t=>`<div class="task-item${t.done?' done':''}">
    <input type="checkbox" class="task-cb" ${t.done?'checked':''} onchange="toggleRec(${t.id})">
    <span class="task-label">${esc(t.name)}</span>
    <span class="rec-badge${t.done?' done':''}">${t.done?'done':'due'}</span>
    <button class="task-del" onclick="delRec(${t.id})">✕</button>
  </div>`).join('');
}

// ADHOC
function addAdhoc(){
  const v=document.getElementById('adhoc-inp').value.trim();if(!v)return;
  S.adhocTasks.push({id:Date.now(),name:v,done:false});
  document.getElementById('adhoc-inp').value='';
  addLog({type:'task',title:'Task added: '+v,detail:''});
  save();renderAdhoc();
}
function toggleAdhoc(id){
  const t=S.adhocTasks.find(x=>x.id===id);if(t){t.done=!t.done;if(t.done)addLog({type:'task',title:'Task done: '+t.name,detail:''});}
  save();renderAdhoc();
}
function delAdhoc(id){S.adhocTasks=S.adhocTasks.filter(x=>x.id!==id);save();renderAdhoc();}
function renderAdhoc(){
  const el=document.getElementById('adhoc-list');
  if(!S.adhocTasks.length){el.innerHTML='<div class="empty">No tasks yet</div>';return;}
  el.innerHTML=S.adhocTasks.map(t=>`<div class="task-item${t.done?' done':''}">
    <input type="checkbox" class="task-cb" ${t.done?'checked':''} onchange="toggleAdhoc(${t.id})">
    <span class="task-label">${esc(t.name)}</span>
    <button class="task-del" onclick="delAdhoc(${t.id})">✕</button>
  </div>`).join('');
}

// CHECKLISTS
function addClList(){const v=document.getElementById('cl-list-inp').value.trim();if(!v)return;if(!S.checklists[v])S.checklists[v]=[];S.activeList=v;document.getElementById('cl-list-inp').value='';save();renderCl();}
function switchCl(name){S.activeList=name;renderCl();}
function delClList(name){delete S.checklists[name];if(S.activeList===name)S.activeList=Object.keys(S.checklists)[0]||null;save();renderCl();}
function addClItem(){if(!S.activeList)return;const v=document.getElementById('cl-item-inp').value.trim();if(!v)return;S.checklists[S.activeList].push({id:Date.now(),name:v,done:false});document.getElementById('cl-item-inp').value='';save();renderCl();}
function toggleCl(id){if(!S.activeList)return;const t=S.checklists[S.activeList].find(x=>x.id===id);if(t)t.done=!t.done;save();renderCl();}
function delCl(id){if(!S.activeList)return;S.checklists[S.activeList]=S.checklists[S.activeList].filter(x=>x.id!==id);save();renderCl();}
function renderCl(){
  const keys=Object.keys(S.checklists);
  document.getElementById('cl-tabs').innerHTML=keys.map(k=>`<span class="cl-tab${S.activeList===k?' active':''}" onclick="switchCl('${esc(k)}')">${esc(k)} <span onclick="event.stopPropagation();delClList('${esc(k)}')" style="opacity:.5;cursor:pointer;">✕</span></span>`).join('');
  const hasActive=S.activeList&&S.checklists[S.activeList];
  document.getElementById('cl-item-inp').style.display=hasActive?'block':'none';
  document.getElementById('cl-item-btn').style.display=hasActive?'inline-block':'none';
  const progRow=document.getElementById('cl-prog-row');
  const el=document.getElementById('cl-items');
  if(!hasActive){el.innerHTML='<div class="empty">Create or select a list</div>';progRow.style.display='none';return;}
  const list=S.checklists[S.activeList];
  const done=list.filter(x=>x.done).length,total=list.length;
  if(total>0){progRow.style.display='flex';document.getElementById('cl-prog-fill').style.width=Math.round(done/total*100)+'%';document.getElementById('cl-prog-txt').textContent=done+'/'+total;}
  else progRow.style.display='none';
  el.innerHTML=!list.length?'<div class="empty">No items yet</div>':list.map(t=>`<div class="task-item${t.done?' done':''}">
    <input type="checkbox" class="task-cb" ${t.done?'checked':''} onchange="toggleCl(${t.id})">
    <span class="task-label">${esc(t.name)}</span>
    <button class="task-del" onclick="delCl(${t.id})">✕</button>
  </div>`).join('');
}

// SITES
function siteStatus(site) {
  if(!site.lastScan) return 'never';
  const elapsedMin=(Date.now()-site.lastScan)/60000;
  const interval=site.interval||30;
  const threshold=site.threshold||5;
  if(elapsedMin>interval) return 'overdue';
  if(elapsedMin>interval-threshold) return 'due';
  return 'ok';
}
function siteStatusLabel(s){return{ok:'OK',due:'Due soon',overdue:'OVERDUE',never:'Never scanned'}[s]||s;}
function siteStatusBadgeClass(s){return{ok:'badge-ok',due:'badge-due',overdue:'badge-overdue',never:'badge-never'}[s]||'badge-never';}
function refreshScanStatuses(){renderSites();renderScanStats();}

function setSiteFilter(f,el){
  S.siteFilter=f;
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  if(el)el.classList.add('active');
  renderSites();
}
function renderScanStats(){
  const total=S.sites.length;
  const ok=S.sites.filter(s=>siteStatus(s)==='ok').length;
  const due=S.sites.filter(s=>siteStatus(s)==='due').length;
  const overdue=S.sites.filter(s=>siteStatus(s)==='overdue').length;
  const never=S.sites.filter(s=>siteStatus(s)==='never').length;
  document.getElementById('scan-stats').innerHTML=`
    <div class="stat-chip"><span class="s-val">${total}</span><span class="s-lbl">Sites</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--green)">${ok}</span><span class="s-lbl">OK</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--amber)">${due}</span><span class="s-lbl">Due soon</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--red)">${overdue}</span><span class="s-lbl">Overdue</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--text3)">${never}</span><span class="s-lbl">Never scanned</span></div>`;
  // next due
  const pending=S.sites.filter(s=>s.lastScan&&siteStatus(s)==='ok').sort((a,b)=>{
    const aRem=(a.interval||30)-((Date.now()-a.lastScan)/60000);
    const bRem=(b.interval||30)-((Date.now()-b.lastScan)/60000);
    return aRem-bRem;
  });
  if(pending.length){
    const next=pending[0];
    const remMin=Math.max(0,((next.interval||30)-((Date.now()-next.lastScan)/60000)));
    document.getElementById('scan-next-due').textContent='Next: '+esc(next.name)+' in ~'+Math.ceil(remMin)+'min';
  } else {
    document.getElementById('scan-next-due').textContent='';
  }
}
function renderSites(){
  renderScanStats();
  let sites=[...S.sites];
  const f=S.siteFilter;
  if(f==='nerc') sites=sites.filter(s=>s.nerc);
  else if(f!=='all') sites=sites.filter(s=>siteStatus(s)===f);
  // sort: overdue first, then due, then never, then ok
  const order={overdue:0,due:1,never:2,ok:3};
  sites.sort((a,b)=>(order[siteStatus(a)]||0)-(order[siteStatus(b)]||0));
  const el=document.getElementById('sites-grid');
  if(!sites.length){el.innerHTML='<div class="empty" style="grid-column:1/-1;">No sites'+(f!=='all'?' matching filter':' added yet')+'</div>';return;}
  el.innerHTML=sites.map(site=>{
    const status=siteStatus(site);
    const lastStr=site.lastScan?timeSince(site.lastScan):'—';
    const intervalStr=(site.interval||30)+'min interval';
    return `<div class="site-card ${status}">
      <div class="site-header">
        <span class="site-name">${esc(site.name)}</span>
        ${site.nerc?'<span class="site-badge badge-nerc">NERC</span>':''}
        <span class="site-badge ${siteStatusBadgeClass(status)}">${siteStatusLabel(status)}</span>
      </div>
      <div class="site-meta">Last: ${lastStr} · ${intervalStr}</div>
      <div class="site-actions">
        <button class="scan-btn" onclick="openScanNote(${site.id})">Log scan</button>
        <button class="tbtn" style="font-size:11px;padding:3px 9px;" onclick="editSite(${site.id})">Edit</button>
        <button class="tbtn" style="font-size:11px;padding:3px 9px;color:var(--red);border-color:var(--red-dim);" onclick="deleteSite(${site.id})">Del</button>
      </div>
      ${site.notes?`<div class="site-note-preview">${esc(site.notes.substring(0,80))}${site.notes.length>80?'…':''}</div>`:''}
    </div>`;
  }).join('');
}
function timeSince(ts){
  const m=Math.floor((Date.now()-ts)/60000);
  if(m<1)return'just now';
  if(m<60)return m+'min ago';
  return Math.floor(m/60)+'h '+m%60+'m ago';
}
function openScanNote(id){
  const site=S.sites.find(s=>s.id===id);if(!site)return;
  document.getElementById('scan-note-title').textContent='Log scan — '+site.name;
  document.getElementById('scan-note-site-id').value=id;
  document.getElementById('scan-note-body').value='';
  openModal('modal-scan-note');
}
function confirmScan(){
  const id=parseInt(document.getElementById('scan-note-site-id').value);
  const site=S.sites.find(s=>s.id===id);if(!site)return;
  const note=document.getElementById('scan-note-body').value.trim();
  site.lastScan=Date.now();
  addLog({type:'scan',title:'Scan: '+site.name,detail:note||'All clear'});
  closeModal('modal-scan-note');
  save();renderSites();showToast('Scan logged','#f0a500');
}
function scanAll(){
  const nerc=S.sites.filter(s=>s.nerc);
  if(!nerc.length){showToast('No NERC sites added','#9199a8');return;}
  const now=Date.now();
  nerc.forEach(s=>s.lastScan=now);
  addLog({type:'scan',title:'Scan all NERC ('+nerc.length+' sites)',detail:nerc.map(s=>s.name).join(', ')});
  save();renderSites();showToast('All NERC sites scanned','#f0a500');
}
function saveSite(){
  const name=document.getElementById('site-name').value.trim();if(!name)return;
  const editId=document.getElementById('site-edit-id').value;
  const siteData={
    name,
    nerc:document.getElementById('site-nerc').value==='1',
    interval:parseInt(document.getElementById('site-interval').value)||30,
    threshold:parseInt(document.getElementById('site-threshold').value)||5,
    notes:document.getElementById('site-notes').value.trim()
  };
  if(editId){
    const site=S.sites.find(s=>s.id===parseInt(editId));
    if(site) Object.assign(site,siteData);
  } else {
    S.sites.push({id:Date.now(),lastScan:null,...siteData});
  }
  closeModal('modal-add-site');
  save();renderSites();showToast('Site saved','#2ecc8a');
}
function editSite(id){
  const site=S.sites.find(s=>s.id===id);if(!site)return;
  document.getElementById('site-modal-title').textContent='Edit site';
  document.getElementById('site-edit-id').value=id;
  document.getElementById('site-name').value=site.name;
  document.getElementById('site-nerc').value=site.nerc?'1':'0';
  document.getElementById('site-interval').value=site.interval||30;
  document.getElementById('site-threshold').value=site.threshold||5;
  document.getElementById('site-notes').value=site.notes||'';
  openModal('modal-add-site');
}
function deleteSite(id){if(confirm('Delete this site?')){S.sites=S.sites.filter(s=>s.id!==id);save();renderSites();}}

// TEMPLATES
const TEMPLATES=[
  {id:'incident',icon:'🚨',name:'Incident report',desc:'Location, severity, action',tag:'incident'},
  {id:'response',icon:'✅',name:'Correct response',desc:'Procedure, notify, outcome',tag:'response'},
  {id:'obs',icon:'📋',name:'Observation',desc:'Quick freeform note',tag:'obs',quick:'Time: {time}\nLocation: \nObservation: \nAction taken: '},
  {id:'callback',icon:'📞',name:'Callback / follow-up',desc:'Who to call back',tag:'task',quick:'Time: {time}\nContact: \nReason: \nFollow up by: '},
  {id:'handoff',icon:'🔄',name:'Shift handoff',desc:'Auto-summary of your shift',tag:'obs'},
];
function renderTemplates(){
  document.getElementById('tpl-grid').innerHTML=TEMPLATES.map(t=>`<button class="tpl-btn" onclick="useTemplate('${t.id}')"><span class="tpl-icon">${t.icon}</span><span class="tpl-name">${t.name}</span><span class="tpl-desc">${t.desc}</span></button>`).join('');
}
function useTemplate(id){
  if(id==='incident'){openModal('modal-incident');return;}
  if(id==='response'){openModal('modal-response');return;}
  if(id==='handoff'){openHandoffAsNote();return;}
  const tpl=TEMPLATES.find(t=>t.id===id);if(!tpl)return;
  const now=new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  newNote(tpl.name+' — '+now, tpl.quick.replace('{time}',now), tpl.tag);
}

// NOTES
function newBlankNote(){newNote('New note','','obs');}
function newNote(title,body,tag){
  const note={id:Date.now(),title:title||'New note',body:body||'',tag:tag||'obs',ts:Date.now()};
  S.notes.unshift(note);S.activeNote=note.id;
  save();renderNotes();loadNoteForm(note);
}
function selectNote(id){S.activeNote=id;const note=S.notes.find(n=>n.id===id);renderNotes();loadNoteForm(note);}
function loadNoteForm(note){
  document.getElementById('note-no-sel').style.display='none';
  const f=document.getElementById('note-form');f.style.display='flex';
  document.getElementById('note-title').value=note.title;
  document.getElementById('note-body').value=note.body;
  document.getElementById('note-tag').value=note.tag;
  document.getElementById('note-meta').textContent='Saved '+new Date(note.ts).toLocaleString();
}
function saveNote(){
  if(!S.activeNote)return;
  const note=S.notes.find(n=>n.id===S.activeNote);if(!note)return;
  note.title=document.getElementById('note-title').value||'Untitled';
  note.body=document.getElementById('note-body').value;
  note.tag=document.getElementById('note-tag').value;
  note.ts=Date.now();
  document.getElementById('note-meta').textContent='Saved '+new Date(note.ts).toLocaleString();
  addLog({type:note.tag==='incident'?'incident':note.tag==='response'?'response':'note',title:note.title,detail:note.body.substring(0,100)});
  save();renderNotes();showToast('Saved','#2ecc8a');
}
function deleteNote(){
  if(!S.activeNote)return;
  S.notes=S.notes.filter(n=>n.id!==S.activeNote);
  S.activeNote=S.notes[0]?.id||null;
  save();renderNotes();
  if(S.activeNote)loadNoteForm(S.notes.find(n=>n.id===S.activeNote));
  else{document.getElementById('note-form').style.display='none';document.getElementById('note-no-sel').style.display='block';}
}
const TAG_LABELS={obs:'Observation',incident:'Incident',response:'Response',task:'Task note'};
const TAG_CLS={obs:'tag-obs',incident:'tag-incident',response:'tag-response',task:'tag-task'};
function renderNotes(){
  const el=document.getElementById('notes-list');
  if(!S.notes.length){el.innerHTML='<div class="empty">No notes yet</div>';return;}
  el.innerHTML=S.notes.map(n=>`<div class="note-entry${S.activeNote===n.id?' active':''}" onclick="selectNote(${n.id})">
    <div class="note-entry-time">${new Date(n.ts).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'})}</div>
    <div class="note-entry-title">${esc(n.title)}</div>
    <div style="margin-top:2px;"><span class="tag ${TAG_CLS[n.tag]||'tag-obs'}">${TAG_LABELS[n.tag]||n.tag}</span></div>
  </div>`).join('');
}

// INCIDENT / RESPONSE
function saveIncident(){
  const loc=document.getElementById('inc-location').value;
  const sev=document.getElementById('inc-severity').value;
  const rep=document.getElementById('inc-reporter').value;
  const desc=document.getElementById('inc-desc').value;
  const action=document.getElementById('inc-action').value;
  const followup=document.getElementById('inc-followup').value;
  const now=new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  const title='['+sev+'] Incident — '+(loc||'unknown location');
  const body='Time: '+now+'\nLocation: '+loc+'\nSeverity: '+sev+'\nReported by: '+rep+'\nDescription: '+desc+'\nAction taken: '+action+'\nFollow-up required: '+followup;
  newNote(title,body,'incident');
  addLog({type:'incident',title,detail:sev+' at '+(loc||'?')+'. '+(desc||'').substring(0,80),followup:followup==='yes'});
  closeModal('modal-incident');
  ['inc-location','inc-reporter','inc-desc','inc-action'].forEach(id=>{document.getElementById(id).value='';});
  showToast('Incident logged','#e85555');
  switchView('notes', document.querySelectorAll('.nav-tab')[2]);
}
function saveResponse(){
  const sit=document.getElementById('res-situation').value;
  const notif=document.getElementById('res-notified').value;
  const proc=document.getElementById('res-procedure').value;
  const out=document.getElementById('res-outcome').value;
  const esc2=document.getElementById('res-escalation').value;
  const now=new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  const title='Response — '+(sit||'situation')+' at '+now;
  const body='Time: '+now+'\nSituation: '+sit+'\nNotified: '+notif+'\nProcedure: '+proc+'\nOutcome: '+out+'\nEscalation: '+esc2;
  newNote(title,body,'response');
  addLog({type:'response',title,detail:'Notified: '+notif+'. '+(out||'').substring(0,80)});
  closeModal('modal-response');
  ['res-situation','res-notified','res-procedure','res-outcome'].forEach(id=>{document.getElementById(id).value='';});
  showToast('Response logged','#9b7fff');
  switchView('notes', document.querySelectorAll('.nav-tab')[2]);
}

// HANDOFF SUMMARY
function buildHandoffText(){
  const now=new Date();
  const shiftStartStr=new Date(S.shiftStart).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  const shiftEndStr=now.toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});

  // Todays entries since shiftStart
  const todayEntries=S.logEntries.filter(e=>e.ts>=S.shiftStart);
  const incidents=todayEntries.filter(e=>e.type==='incident');
  const responses=todayEntries.filter(e=>e.type==='response');
  const tasks=todayEntries.filter(e=>e.type==='task'&&e.title.startsWith('Task done:'));
  const cycles=S.timerCycles;
  const scans=todayEntries.filter(e=>e.type==='scan');

  // Open items
  const openIncidents=incidents.filter(e=>e.followup);
  const openTasks=S.adhocTasks.filter(t=>!t.done);

  // Overdue sites
  const overdueSites=S.sites.filter(s=>siteStatus(s)==='overdue');
  const dueSites=S.sites.filter(s=>siteStatus(s)==='due');

  // Checklist status
  const clKeys=Object.keys(S.checklists);
  const clStatus=clKeys.map(k=>{
    const list=S.checklists[k];
    const done=list.filter(x=>x.done).length;
    return k+': '+done+'/'+list.length;
  });

  let lines=[];
  lines.push('SHIFT HANDOFF SUMMARY');
  lines.push('─────────────────────');
  lines.push('Shift: '+shiftStartStr+' → '+shiftEndStr);
  lines.push('Cycles completed: '+cycles);
  lines.push('');

  // Open items — most important
  const hasOpen=openIncidents.length||openTasks.length||overdueSites.length||dueSites.length;
  lines.push('⚠ OPEN ITEMS'+(hasOpen?'':' — none'));
  if(openIncidents.length){lines.push('');lines.push('  Incidents requiring follow-up:');openIncidents.forEach(e=>lines.push('  • '+e.title+(e.detail?' — '+e.detail.substring(0,60):'')));}
  if(openTasks.length){lines.push('');lines.push('  Incomplete tasks:');openTasks.forEach(t=>lines.push('  • '+t.name));}
  if(overdueSites.length){lines.push('');lines.push('  Overdue scans:');overdueSites.forEach(s=>lines.push('  • '+s.name+(s.nerc?' [NERC]':'')+' — last '+timeSince(s.lastScan||0)));}
  if(dueSites.length){lines.push('');lines.push('  Due soon:');dueSites.forEach(s=>lines.push('  • '+s.name+(s.nerc?' [NERC]':'')));}

  lines.push('');
  lines.push('✓ ACTIVITY THIS SHIFT');
  lines.push('  Incidents logged: '+incidents.length);
  lines.push('  Responses logged: '+responses.length);
  lines.push('  Tasks completed:  '+tasks.length);
  lines.push('  Scans logged:     '+scans.length);

  if(clStatus.length){lines.push('');lines.push('  Checklists:');clStatus.forEach(s=>lines.push('  • '+s));}

  if(incidents.length){
    lines.push('');
    lines.push('  Incident log:');
    incidents.forEach(e=>{
      const t=new Date(e.ts).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
      lines.push('  ['+t+'] '+e.title);
      if(e.detail)lines.push('          '+e.detail.substring(0,80));
    });
  }

  lines.push('');
  lines.push('──────────────────────');
  lines.push('Generated '+now.toLocaleString());
  return lines.join('\n');
}

function openHandoffAsNote(){
  const text=buildHandoffText();
  const now=new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  newNote('Shift handoff — '+now, text, 'obs');
  switchView('notes', document.querySelectorAll('.nav-tab')[2]);
}
function openHandoff(){
  const text=buildHandoffText();
  document.getElementById('handoff-content').textContent=text;
  openModal('modal-handoff');
}
function copyHandoff(){
  const text=document.getElementById('handoff-content').textContent;
  try{navigator.clipboard.writeText(text);showToast('Copied!','#2ecc8a');}catch(e){showToast('Select and copy manually','#9199a8');}
}

// LOG
function addLog(entry){
  S.logEntries.unshift({...entry,ts:Date.now(),id:Date.now()});
  if(S.logEntries.length>500)S.logEntries=S.logEntries.slice(0,500);
  save();
}
function renderLog(){
  const filter=document.getElementById('log-filter').value;
  const entries=filter==='all'?S.logEntries:S.logEntries.filter(e=>e.type===filter);
  const el=document.getElementById('log-list');
  el.innerHTML=!entries.length?'<div class="empty">No entries yet</div>':entries.map(e=>`<div class="log-entry ${e.type||'note'}">
    <div class="log-time">${new Date(e.ts).toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'})}</div>
    <div class="log-body">
      <div class="log-title">${esc(e.title||'')}</div>
      ${e.detail?`<div class="log-detail">${esc(e.detail)}</div>`:''}
    </div>
  </div>`).join('');
  const total=S.logEntries.length;
  const inc=S.logEntries.filter(e=>e.type==='incident').length;
  const res=S.logEntries.filter(e=>e.type==='response').length;
  const tsk=S.logEntries.filter(e=>e.type==='task').length;
  const scn=S.logEntries.filter(e=>e.type==='scan').length;
  document.getElementById('log-stats').innerHTML=`
    <div class="stat-chip"><span class="s-val">${total}</span><span class="s-lbl">Total</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--red)">${inc}</span><span class="s-lbl">Incidents</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--purple)">${res}</span><span class="s-lbl">Responses</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--green)">${tsk}</span><span class="s-lbl">Tasks</span></div>
    <div class="stat-chip"><span class="s-val" style="color:var(--amber)">${scn}</span><span class="s-lbl">Scans</span></div>`;
}
function clearLog(){if(confirm('Clear all log entries?')){S.logEntries=[];save();renderLog();}}

// MODAL
function openModal(id){document.getElementById(id).classList.remove('hidden');}
function closeModal(id){document.getElementById(id).classList.add('hidden');}

// UTILS
function fireAlert(msg){
  showToast(msg,'#e85555');
  try{const ctx=new AudioContext();[880,660].forEach((f,i)=>{const o=ctx.createOscillator(),g=ctx.createGain();o.connect(g);g.connect(ctx.destination);o.frequency.value=f;g.gain.setValueAtTime(.25,ctx.currentTime+i*.15);g.gain.exponentialRampToValueAtTime(.001,ctx.currentTime+i*.15+.4);o.start(ctx.currentTime+i*.15);o.stop(ctx.currentTime+i*.15+.4);});}catch(e){}
}
function showToast(msg,color){
  const t=document.getElementById('toast');t.textContent=msg;t.style.background=color||'var(--red)';
  t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2500);
}
function esc(s){return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;').replace(/'/g,'&#39;');}
function renderAll(){renderRec();renderAdhoc();renderCl();renderNotes();renderTemplates();updateTimerUI();renderSites();}

load();
</script>
</body>
</html>

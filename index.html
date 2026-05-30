<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dashboard Khuyến Mãi</title>
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@300;400;500;600;700;800&family=Sora:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d0f14;
    --surface: #13161e;
    --card: #1a1e2a;
    --border: #252a38;
    --accent: #f97316;
    --accent2: #3b82f6;
    --accent3: #22c55e;
    --accent4: #a855f7;
    --text: #e8eaf0;
    --muted: #8891aa;
    --danger: #ef4444;
    --warning: #eab308;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { font-family: 'Be Vietnam Pro', sans-serif; background: var(--bg); color: var(--text); min-height: 100vh; }

  /* SIDEBAR */
  .sidebar { position: fixed; left: 0; top: 0; bottom: 0; width: 220px; background: var(--surface); border-right: 1px solid var(--border); display: flex; flex-direction: column; z-index: 100; }
  .logo { padding: 24px 20px 20px; font-family: 'Sora', sans-serif; font-weight: 700; font-size: 17px; border-bottom: 1px solid var(--border); display: flex; align-items: center; gap: 10px; }
  .logo-icon { width: 32px; height: 32px; border-radius: 8px; background: linear-gradient(135deg, var(--accent), #f59e0b); display: flex; align-items: center; justify-content: center; font-size: 16px; }
  .nav { padding: 16px 12px; flex: 1; }
  .nav-label { font-size: 10px; font-weight: 700; color: var(--muted); letter-spacing: 1.2px; text-transform: uppercase; padding: 0 8px; margin: 16px 0 8px; }
  .nav-item { display: flex; align-items: center; gap: 10px; padding: 10px 12px; border-radius: 8px; font-size: 13.5px; font-weight: 500; cursor: pointer; transition: all .2s; color: var(--muted); margin-bottom: 2px; }
  .nav-item:hover, .nav-item.active { background: var(--card); color: var(--text); }
  .nav-item.active { color: var(--accent); }
  .nav-item .icon { font-size: 16px; width: 20px; text-align: center; }

  /* MAIN */
  .main { margin-left: 220px; padding: 28px 32px; transition: margin-right .3s ease; }
  .main.drawer-open { margin-right: 380px; }

  /* HEADER */
  .header { display: flex; align-items: center; justify-content: space-between; margin-bottom: 28px; }
  .header-left h1 { font-family: 'Sora', sans-serif; font-size: 22px; font-weight: 700; }
  .header-left p { font-size: 13px; color: var(--muted); margin-top: 3px; }
  .header-right { display: flex; gap: 10px; align-items: center; }
  .btn { padding: 9px 18px; border-radius: 8px; font-size: 13px; font-family: 'Be Vietnam Pro', sans-serif; font-weight: 600; border: none; cursor: pointer; transition: all .2s; }
  .btn-primary { background: var(--accent); color: #fff; }
  .btn-primary:hover { background: #ea6c0a; transform: translateY(-1px); }
  .btn-ghost { background: var(--card); color: var(--text); border: 1px solid var(--border); }
  .btn-ghost:hover { background: var(--border); }

  /* STATS */
  .stats { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; margin-bottom: 24px; }
  .stat-card { background: var(--card); border: 1px solid var(--border); border-radius: 12px; padding: 20px; position: relative; overflow: hidden; transition: transform .2s; }
  .stat-card:hover { transform: translateY(-2px); }
  .stat-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 3px; }
  .stat-card.orange::before { background: var(--accent); }
  .stat-card.blue::before { background: var(--accent2); }
  .stat-card.green::before { background: var(--accent3); }
  .stat-card.purple::before { background: var(--accent4); }
  .stat-label { font-size: 12px; color: var(--muted); font-weight: 500; margin-bottom: 8px; }
  .stat-value { font-size: 28px; font-weight: 800; font-family: 'Sora', sans-serif; }
  .stat-sub { font-size: 12px; color: var(--muted); margin-top: 6px; }
  .stat-badge { display: inline-flex; align-items: center; gap: 4px; font-size: 11px; font-weight: 600; padding: 2px 8px; border-radius: 99px; margin-top: 6px; }
  .stat-badge.up { background: rgba(34,197,94,.15); color: var(--accent3); }

  .info-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 24px; }
  /* GRID */
  .grid2 { display: grid; grid-template-columns: 1fr; gap: 20px; margin-bottom: 24px; }

  /* CARD */
  .card { background: var(--card); border: 1px solid var(--border); border-radius: 14px; overflow: hidden; }
  .card-header { padding: 18px 22px; border-bottom: 1px solid var(--border); display: flex; align-items: center; justify-content: space-between; }
  .card-title { font-size: 14px; font-weight: 700; display: flex; align-items: center; gap: 8px; }
  .card-title .dot { width: 8px; height: 8px; border-radius: 50%; }

  /* TABLE */
  table { width: 100%; border-collapse: collapse; }
  th { text-align: left; font-size: 11px; font-weight: 700; color: var(--muted); text-transform: uppercase; letter-spacing: .8px; padding: 12px 22px; border-bottom: 1px solid var(--border); background: rgba(255,255,255,.02); }
  td { padding: 13px 22px; font-size: 13px; border-bottom: 1px solid rgba(255,255,255,.04); }
  tr:last-child td { border-bottom: none; }
  tbody tr { cursor: pointer; transition: background .15s; }
  tbody tr:hover td { background: rgba(249,115,22,.04); }
  tbody tr.active-row td { background: rgba(249,115,22,.08); }

  .promo-name { font-weight: 600; }
  .promo-channel { font-size: 11px; font-weight: 500; padding: 3px 9px; border-radius: 99px; display: inline-block; }
  .ch-fanpage  { background: rgba(168,85,247,.15);  color: #c084fc; }   /* tím */
  .ch-hotline  { background: rgba(239,68,68,.15);   color: #f87171; }   /* đỏ  */
  .ch-zalo     { background: rgba(59,130,246,.15);  color: #60a5fa; }   /* xanh dương */
  .ch-cuahang  { background: rgba(234,179,8,.15);   color: #fbbf24; }   /* vàng */
  .ch-all      { background: rgba(249,115,22,.15);  color: #fb923c; }   /* cam */

  .status-badge { font-size: 11px; font-weight: 600; padding: 4px 10px; border-radius: 99px; display: inline-flex; align-items: center; gap: 5px; }
  .s-live { background: rgba(34,197,94,.15); color: var(--accent3); }
  .s-live::before { content: ''; width: 6px; height: 6px; border-radius: 50%; background: var(--accent3); animation: pulse 1.5s infinite; }
  .s-upcoming { background: rgba(234,179,8,.15); color: var(--warning); }
  .s-ended { background: rgba(139,148,164,.1); color: var(--muted); }
  @keyframes pulse { 0%,100%{opacity:1}50%{opacity:.4} }

  .priority { width: 8px; height: 8px; border-radius: 2px; display: inline-block; }
  .p-high { background: var(--danger); }
  .p-med { background: var(--warning); }
  .p-low { background: var(--accent3); }

  .progress-wrap { display: flex; align-items: center; gap: 8px; }
  .progress-bar { flex: 1; height: 5px; background: var(--border); border-radius: 99px; overflow: hidden; }
  .progress-fill { height: 100%; border-radius: 99px; }
  .progress-pct { font-size: 11px; font-weight: 600; color: var(--muted); width: 32px; text-align: right; }

  /* RIGHT PANEL */
  .right-panel { display: flex; flex-direction: column; gap: 16px; }

  /* ALERT */
  .alert-list { padding: 8px 0; }
  .alert-item { display: flex; gap: 12px; padding: 12px 20px; border-bottom: 1px solid rgba(255,255,255,.04); align-items: flex-start; transition: background .15s; }
  .alert-item:hover { background: rgba(255,255,255,.02); }
  .alert-item:last-child { border-bottom: none; }
  .alert-icon { width: 32px; height: 32px; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 15px; flex-shrink: 0; }
  .ai-warn { background: rgba(234,179,8,.15); }
  .ai-ok { background: rgba(34,197,94,.15); }
  .ai-err { background: rgba(239,68,68,.15); }
  .ai-info { background: rgba(59,130,246,.15); }
  .alert-content { flex: 1; }
  .alert-title { font-size: 13px; font-weight: 600; line-height: 1.4; }
  .alert-time { font-size: 11px; color: var(--muted); margin-top: 2px; }

  /* CALENDAR */
  .calendar-mini { padding: 18px 20px; }
  .cal-header { display: flex; align-items: center; justify-content: space-between; margin-bottom: 14px; }
  .cal-month { font-size: 13px; font-weight: 700; }
  .cal-nav { display: flex; gap: 4px; }
  .cal-nav button { width: 26px; height: 26px; border-radius: 6px; background: var(--border); border: none; color: var(--muted); cursor: pointer; font-size: 13px; transition: all .2s; }
  .cal-nav button:hover { background: var(--accent); color: #fff; }
  .cal-grid { display: grid; grid-template-columns: repeat(7,1fr); gap: 2px; }
  .cal-day-name { text-align: center; font-size: 10px; font-weight: 700; color: var(--muted); padding: 4px 0; text-transform: uppercase; }
  .cal-day { text-align: center; padding: 5px 2px; font-size: 12px; border-radius: 6px; cursor: pointer; transition: all .15s; position: relative; }
  .cal-day:hover { background: var(--border); }
  .cal-day.today { background: var(--accent); color: #fff; font-weight: 700; }
  .cal-day.has-event::after { content: ''; position: absolute; bottom: 2px; left: 50%; transform: translateX(-50%); width: 4px; height: 4px; border-radius: 50%; background: var(--accent2); }
  .cal-day.today.has-event::after { background: #fff; }
  .cal-day.other-month { color: var(--border); }

  /* CHECKLIST */
  .checklist { padding: 8px 20px 16px; }
  .check-item { display: flex; align-items: center; gap: 10px; padding: 9px 0; border-bottom: 1px solid rgba(255,255,255,.04); cursor: pointer; }
  .check-item:last-child { border-bottom: none; }
  .check-box { width: 18px; height: 18px; border-radius: 5px; border: 2px solid var(--border); flex-shrink: 0; display: flex; align-items: center; justify-content: center; transition: all .2s; font-size: 11px; }
  .check-item.done .check-box { background: var(--accent3); border-color: var(--accent3); }
  .check-item.done .check-box::after { content: '✓'; color: #fff; font-weight: 700; }
  .check-item.done .check-label { text-decoration: line-through; color: var(--muted); }
  .check-label { font-size: 13px; flex: 1; }
  .check-who { font-size: 10px; font-weight: 600; padding: 2px 7px; border-radius: 99px; background: var(--border); color: var(--muted); }

  /* FILTER */
  .filter-chips { display: flex; gap: 8px; padding: 12px 22px; }
  .chip { padding: 5px 12px; border-radius: 99px; font-size: 12px; font-weight: 600; cursor: pointer; border: 1px solid var(--border); color: var(--muted); background: none; font-family: 'Be Vietnam Pro', sans-serif; transition: all .2s; }
  .chip.active { background: var(--accent); border-color: var(--accent); color: #fff; }
  .chip:hover:not(.active) { border-color: var(--text); color: var(--text); }

  /* SEARCH */
  .search-bar { display: flex; align-items: center; gap: 8px; background: var(--card); border: 1px solid var(--border); border-radius: 8px; padding: 8px 14px; width: 220px; }
  .search-bar input { background: none; border: none; outline: none; font-family: 'Be Vietnam Pro', sans-serif; font-size: 13px; color: var(--text); flex: 1; }
  .search-bar input::placeholder { color: var(--muted); }

  .table-scroll { overflow-x: auto; }
  .owner-tag { font-size: 11px; font-weight: 600; padding: 3px 8px; border-radius: 6px; background: var(--border); color: var(--text); }

  .notice-bar { background: linear-gradient(90deg, rgba(249,115,22,.12), rgba(249,115,22,.04)); border: 1px solid rgba(249,115,22,.2); border-radius: 10px; padding: 12px 20px; display: flex; align-items: center; gap: 12px; margin-bottom: 24px; font-size: 13px; }
  .notice-bar strong { color: var(--accent); }

  @keyframes fadeUp { from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)} }
  .stats .stat-card { animation: fadeUp .4s ease both; }
  .stats .stat-card:nth-child(1){animation-delay:.05s}
  .stats .stat-card:nth-child(2){animation-delay:.1s}
  .stats .stat-card:nth-child(3){animation-delay:.15s}
  .stats .stat-card:nth-child(4){animation-delay:.2s}


  /* ACTION BUTTONS */
  .action-btns { display: flex; gap: 5px; opacity: 0; transition: opacity .15s; }
  tbody tr:hover .action-btns { opacity: 1; }
  .act-btn {
    width: 28px; height: 28px; border-radius: 7px; border: 1px solid var(--border);
    background: var(--surface); cursor: pointer; font-size: 13px;
    display: flex; align-items: center; justify-content: center;
    transition: all .15s; color: var(--muted);
  }
  .act-btn.edit:hover { background: rgba(59,130,246,.15); border-color: var(--accent2); color: var(--accent2); }
  .act-btn.del:hover  { background: rgba(239,68,68,.15);  border-color: var(--danger);  color: var(--danger); }

  /* MODAL TITLE (edit mode) */
  .modal-mode-badge {
    font-size: 11px; font-weight: 700; padding: 3px 10px; border-radius: 99px;
    margin-left: 10px; vertical-align: middle;
  }
  .modal-mode-badge.add  { background: rgba(249,115,22,.15); color: var(--accent); }
  .modal-mode-badge.edit { background: rgba(59,130,246,.15);  color: var(--accent2); }

  /* CONFIRM DELETE DIALOG */
  .confirm-overlay {
    position: fixed; inset: 0; background: rgba(0,0,0,.65); backdrop-filter: blur(4px);
    z-index: 400; display: flex; align-items: center; justify-content: center;
    opacity: 0; pointer-events: none; transition: opacity .2s;
  }
  .confirm-overlay.open { opacity: 1; pointer-events: all; }
  .confirm-box {
    background: var(--surface); border: 1px solid var(--border); border-radius: 14px;
    padding: 28px 32px; width: 380px; text-align: center;
    box-shadow: 0 20px 50px rgba(0,0,0,.5);
    transform: scale(.95); transition: transform .2s;
  }
  .confirm-overlay.open .confirm-box { transform: scale(1); }
  .confirm-icon { font-size: 36px; margin-bottom: 12px; }
  .confirm-title { font-family: 'Sora', sans-serif; font-size: 16px; font-weight: 700; margin-bottom: 8px; }
  .confirm-sub { font-size: 13px; color: var(--muted); margin-bottom: 22px; line-height: 1.5; }
  .confirm-actions { display: flex; gap: 10px; justify-content: center; }
  ::-webkit-scrollbar{width:5px;height:5px}
  ::-webkit-scrollbar-track{background:transparent}
  ::-webkit-scrollbar-thumb{background:var(--border);border-radius:99px}

  /* ========== DRAWER ========== */
  .drawer {
    position: fixed; top: 0; right: -400px; bottom: 0; width: 380px;
    background: var(--surface); border-left: 1px solid var(--border);
    z-index: 200; display: flex; flex-direction: column;
    transition: right .3s cubic-bezier(.4,0,.2,1);
    overflow: hidden;
  }
  .drawer.open { right: 0; }

  .drawer-header {
    padding: 20px 22px 16px; border-bottom: 1px solid var(--border);
    display: flex; align-items: flex-start; justify-content: space-between; flex-shrink: 0;
  }
  .drawer-title { font-family: 'Sora', sans-serif; font-size: 16px; font-weight: 700; line-height: 1.4; max-width: 280px; }
  .drawer-code { font-size: 11px; color: var(--muted); margin-top: 4px; }
  .drawer-close {
    width: 30px; height: 30px; border-radius: 8px; background: var(--card);
    border: 1px solid var(--border); color: var(--muted); cursor: pointer;
    font-size: 16px; display: flex; align-items: center; justify-content: center;
    transition: all .2s; flex-shrink: 0; margin-left: 10px;
  }
  .drawer-close:hover { background: var(--danger); color: #fff; border-color: var(--danger); }

  .drawer-body { flex: 1; overflow-y: auto; padding: 20px 22px; }

  .drawer-section { margin-bottom: 22px; }
  .drawer-section-title {
    font-size: 10px; font-weight: 700; color: var(--muted);
    text-transform: uppercase; letter-spacing: 1px; margin-bottom: 12px;
    display: flex; align-items: center; gap: 6px;
  }
  .drawer-section-title::after { content:''; flex:1; height:1px; background:var(--border); }

  .info-row { display: flex; justify-content: space-between; align-items: center; padding: 8px 0; border-bottom: 1px solid rgba(255,255,255,.04); }
  .info-row:last-child { border-bottom: none; }
  .info-label { font-size: 12px; color: var(--muted); }
  .info-value { font-size: 13px; font-weight: 600; text-align: right; }

  /* STORE LIST */
  .store-list { display: flex; flex-direction: column; gap: 8px; }
  .store-item {
    display: flex; align-items: center; gap: 10px;
    background: var(--card); border: 1px solid var(--border);
    border-radius: 10px; padding: 10px 14px;
    transition: border-color .15s;
  }
  .store-item:hover { border-color: var(--accent); }
  .store-icon { width: 34px; height: 34px; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 16px; flex-shrink: 0; }
  .store-info { flex: 1; }
  .store-name { font-size: 13px; font-weight: 600; }
  .store-addr { font-size: 11px; color: var(--muted); margin-top: 2px; }
  .store-badge { font-size: 10px; font-weight: 700; padding: 2px 8px; border-radius: 99px; }
  .sb-yes { background: rgba(34,197,94,.15); color: var(--accent3); }
  .sb-no { background: rgba(139,148,164,.1); color: var(--muted); }


  /* STORE SEARCH */
  .store-search {
    display: flex; align-items: center; gap: 8px;
    background: var(--bg); border: 1px solid var(--border);
    border-radius: 8px; padding: 8px 12px; margin-bottom: 10px;
  }
  .store-search input {
    background: none; border: none; outline: none;
    font-family: 'Be Vietnam Pro', sans-serif; font-size: 12.5px;
    color: var(--text); flex: 1;
  }
  .store-search input::placeholder { color: var(--muted); }
  .store-search span { color: var(--muted); font-size: 13px; }
  .store-empty { text-align:center; color:var(--muted); font-size:12px; padding:16px 0; }
  /* NOTE BOX */
  .note-box {
    background: rgba(249,115,22,.06); border: 1px solid rgba(249,115,22,.2);
    border-radius: 10px; padding: 12px 14px; font-size: 13px; line-height: 1.6;
    color: var(--text);
  }

  /* PROGRESS BIG */
  .progress-big { margin: 8px 0; }
  .progress-big .bar { height: 8px; background: var(--border); border-radius: 99px; overflow: hidden; margin-bottom: 6px; }
  .progress-big .fill { height: 100%; border-radius: 99px; transition: width .5s; }
  .progress-big .label { display: flex; justify-content: space-between; font-size: 12px; color: var(--muted); }

  /* ===== MODAL ===== */
  .modal-overlay {
    position: fixed; inset: 0; background: rgba(0,0,0,.6);
    backdrop-filter: blur(4px); z-index: 300;
    display: flex; align-items: center; justify-content: center;
    opacity: 0; pointer-events: none; transition: opacity .25s;
  }
  .modal-overlay.open { opacity: 1; pointer-events: all; }

  .modal {
    background: var(--surface); border: 1px solid var(--border);
    border-radius: 16px; width: 560px; max-width: 95vw;
    max-height: 90vh; overflow-y: auto;
    transform: translateY(20px) scale(.97);
    transition: transform .25s cubic-bezier(.4,0,.2,1);
    box-shadow: 0 24px 60px rgba(0,0,0,.5);
  }
  .modal-overlay.open .modal { transform: translateY(0) scale(1); }

  .modal-header {
    padding: 22px 24px 18px; border-bottom: 1px solid var(--border);
    display: flex; align-items: center; justify-content: space-between;
    position: sticky; top: 0; background: var(--surface); z-index: 1;
  }
  .modal-header h2 { font-family: 'Sora', sans-serif; font-size: 17px; font-weight: 700; }
  .modal-close {
    width: 30px; height: 30px; border-radius: 8px; background: var(--card);
    border: 1px solid var(--border); color: var(--muted); cursor: pointer;
    font-size: 16px; display: flex; align-items: center; justify-content: center;
    transition: all .2s;
  }
  .modal-close:hover { background: var(--danger); color: #fff; border-color: var(--danger); }

  .modal-body { padding: 20px 24px 24px; display: block; }
  .modal-body > * { margin-bottom: 16px; }
  .modal-body > *:last-child { margin-bottom: 0; }

  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
  .form-group { display: flex; flex-direction: column; gap: 6px; }
  .form-group.full { grid-column: 1 / -1; }
  .form-label { font-size: 12px; font-weight: 700; color: var(--muted); text-transform: uppercase; letter-spacing: .7px; }
  .form-input, .form-select, .form-textarea {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 9px; padding: 10px 14px;
    font-family: 'Be Vietnam Pro', sans-serif; font-size: 13.5px;
    color: var(--text); outline: none; transition: border-color .2s;
    width: 100%; color-scheme: dark;
  }
  input[type="date"]::-webkit-calendar-picker-indicator { filter: invert(1); opacity: .6; cursor: pointer; }
  .form-input:focus, .form-select:focus, .form-textarea:focus {
    border-color: var(--accent);
    box-shadow: 0 0 0 3px rgba(249,115,22,.12);
  }
  .form-input::placeholder, .form-textarea::placeholder { color: var(--muted); }
  .form-textarea { resize: vertical; min-height: 80px; line-height: 1.6; }
  .form-select option { background: var(--card); }

  /* Priority pills */
  .priority-group { display: flex; gap: 8px; }
  .priority-pill {
    flex: 1; padding: 9px; border-radius: 9px; border: 2px solid var(--border);
    background: none; font-family: 'Be Vietnam Pro', sans-serif;
    font-size: 12px; font-weight: 700; cursor: pointer; text-align: center;
    transition: all .18s; color: var(--muted);
  }
  .priority-pill:hover { border-color: currentColor; }
  .priority-pill.high { color: var(--danger); }
  .priority-pill.high.sel { background: rgba(239,68,68,.15); border-color: var(--danger); }
  .priority-pill.med { color: var(--warning); }
  .priority-pill.med.sel { background: rgba(234,179,8,.15); border-color: var(--warning); }
  .priority-pill.low { color: var(--accent3); }
  .priority-pill.low.sel { background: rgba(34,197,94,.15); border-color: var(--accent3); }

  /* Store checkboxes */
  .store-check-list { display: flex; flex-direction: column; gap: 6px; max-height: 180px; overflow-y: auto; }
  .store-check-item {
    display: flex; align-items: center; gap: 10px;
    padding: 8px 12px; border-radius: 9px; border: 1px solid var(--border);
    cursor: pointer; transition: all .15s; background: var(--card);
    user-select: none;
  }
  .store-check-item:hover { border-color: var(--accent); }
  .store-check-item.checked { background: rgba(34,197,94,.07); border-color: var(--accent3); }
  .store-check-item .sck-box {
    width: 18px; height: 18px; border-radius: 5px;
    border: 2px solid var(--border); flex-shrink: 0;
    display: flex; align-items: center; justify-content: center;
    font-size: 11px; transition: all .2s;
  }
  .store-check-item.checked .sck-box { background: var(--accent3); border-color: var(--accent3); color: #fff; }
  .store-check-item .sck-label { font-size: 13px; font-weight: 500; flex: 1; }
  .store-check-item .sck-addr { font-size: 11px; color: var(--muted); }

  .modal-footer {
    padding: 16px 24px; border-top: 1px solid var(--border);
    display: flex; gap: 10px; justify-content: flex-end;
    position: sticky; bottom: 0; background: var(--surface);
  }

  /* Toast */
  .toast {
    position: fixed; bottom: 30px; left: 50%; transform: translateX(-50%) translateY(20px);
    background: var(--accent3); color: #fff; font-size: 13px; font-weight: 600;
    padding: 12px 22px; border-radius: 10px; z-index: 400;
    opacity: 0; transition: all .3s; pointer-events: none; white-space: nowrap;
    box-shadow: 0 8px 24px rgba(34,197,94,.3);
  }
  .toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }
</style>
</head>
<body>

<!-- SIDEBAR -->
<div class="sidebar">
  <div class="logo">
    <div class="logo-icon">🎯</div>
    KM Manager
  </div>
  <nav class="nav">
    <div class="nav-label">Tổng quan</div>
    <div class="nav-item active" onclick="setNav(this)"><span class="icon">📋</span> CTKM</div>
    <div class="nav-label">Chương trình</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">🎁</span> Đang chạy</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">📅</span> Sắp triển khai</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">📂</span> Lưu trữ</div>
    <div class="nav-label">Công việc</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">✅</span> Checklist</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">📁</span> File tài liệu</div>
    <div class="nav-item" onclick="setNav(this)"><span class="icon">👥</span> Nhân sự</div>
  </nav>
</div>

<!-- DRAWER -->
<div class="drawer" id="drawer">
  <div class="drawer-header">
    <div>
      <div class="drawer-title" id="d-title">—</div>
      <div class="drawer-code" id="d-code">—</div>
    </div>
    <button class="drawer-close" onclick="closeDrawer()">✕</button>
  </div>
  <div class="drawer-body" id="drawer-body">
  </div>
</div>

<!-- MAIN -->
<div class="main" id="main">

  <!-- HEADER -->
  <div class="header">
    <div class="header-left">
      <h1>Dashboard Khuyến Mãi 🎯</h1>
      <p>Cập nhật lần cuối: hôm nay 09:15 — Tháng 5/2026</p>
    </div>
    <div class="header-right">
      <div class="search-bar">
        <span>🔍</span>
        <input type="text" placeholder="Tìm chương trình...">
      </div>
      <button class="btn btn-ghost">📤 Xuất báo cáo</button>
      <button class="btn btn-primary" onclick="openModal()">＋ Thêm KM</button>
    </div>
  </div>

  <!-- NOTICE -->
  <div class="notice-bar">
    <span style="font-size:18px">⚡</span>
    <span><strong>3 chương trình</strong> sắp hết hạn trong 48h tới — <strong>Flash Sale cuối tuần</strong> cần cập nhật thông tin trước 17:00 hôm nay</span>
    <button class="btn btn-primary" style="margin-left:auto;padding:6px 14px;font-size:12px;white-space:nowrap">Xem ngay →</button>
  </div>

  <!-- STATS -->
  <div class="stats">
    <div class="stat-card orange">
      <div class="stat-label">Đang chạy</div>
      <div class="stat-value" style="color:var(--accent)">8</div>
      <div class="stat-sub">chương trình active</div>
      <div class="stat-badge up">▲ +3 so tuần trước</div>
    </div>
    <div class="stat-card blue">
      <div class="stat-label">Sắp triển khai</div>
      <div class="stat-value" style="color:var(--accent2)">6</div>
      <div class="stat-sub">trong 7 ngày tới</div>
      <div class="stat-badge up">📅 Gần nhất: 01/6</div>
    </div>
    <div class="stat-card green">
      <div class="stat-label">Hoàn thành checklist</div>
      <div class="stat-value" style="color:var(--accent3)">68%</div>
      <div class="stat-sub">17/25 đầu việc xong</div>
      <div class="stat-badge up">▲ +12% hôm nay</div>
    </div>
    <div class="stat-card purple">
      <div class="stat-label">Miss thông tin</div>
      <div class="stat-value" style="color:var(--accent4)">0</div>
      <div class="stat-sub">tuần này</div>
      <div class="stat-badge up">✅ Tốt!</div>
    </div>
  </div>

  <!-- MAIN GRID -->
  <div class="grid2">

    <!-- TABLE -->
    <div class="card">
      <div class="card-header">
        <div class="card-title">
          <div class="dot" style="background:var(--accent)"></div>
          Danh sách chương trình khuyến mãi
          <span style="font-size:11px;color:var(--muted);font-weight:400">— click để xem chi tiết</span>
        </div>
        <select style="background:var(--surface);border:1px solid var(--border);color:var(--muted);border-radius:7px;padding:6px 10px;font-size:12px;font-family:'Be Vietnam Pro',sans-serif;">
          <option>Tất cả kênh</option><option>Fanpage</option><option>Hotline</option><option>Zalo Phòng</option><option>Cửa hàng</option>
        </select>
      </div>
      <div class="filter-chips">
        <button class="chip active" onclick="filterChip(this)">Tất cả</button>
        <button class="chip" onclick="filterChip(this)">🟢 Đang chạy</button>
        <button class="chip" onclick="filterChip(this)">🟡 Sắp tới</button>
        <button class="chip" onclick="filterChip(this)">⚫ Đã kết thúc</button>
        <button class="chip" onclick="filterChip(this)">🔴 Khẩn cấp</button>
      </div>
      <div class="table-scroll">
        <table>
          <thead>
            <tr>
              <th>ƯU TIÊN</th>
              <th>TÊN CHƯƠNG TRÌNH</th>
              <th>KÊNH</th>
              <th>THỜI GIAN</th>
              <th>TIẾN ĐỘ</th>
              <th>TRẠNG THÁI</th>
              <th>PHỤ TRÁCH</th>
              <th style="width:90px"></th>
            </tr>
          </thead>
          <tbody id="promo-table">
          </tbody>
        </table>
      </div>
    </div>

  </div>

  <!-- INFO GRID: Cảnh báo + Lịch triển khai -->
  <div class="info-grid">

    <!-- ALERTS -->
    <div class="card">
      <div class="card-header">
        <div class="card-title"><div class="dot" style="background:var(--danger)"></div>Cảnh báo & nhắc việc</div>
        <span style="font-size:11px;color:var(--muted)">Hôm nay</span>
      </div>
      <div class="alert-list">
        <div class="alert-item">
          <div class="alert-icon ai-err">🚨</div>
          <div class="alert-content">
            <div class="alert-title">Flash Sale cần cập nhật thông tin</div>
            <div class="alert-time">Deadline 17:00 hôm nay · Ngọc phụ trách</div>
          </div>
        </div>
        <div class="alert-item">
          <div class="alert-icon ai-warn">⏰</div>
          <div class="alert-content">
            <div class="alert-title">KM VIP hết hạn sau 3 ngày</div>
            <div class="alert-time">Cần gửi tổng kết về nhóm · Tài</div>
          </div>
        </div>
        <div class="alert-item">
          <div class="alert-icon ai-warn">📝</div>
          <div class="alert-content">
            <div class="alert-title">Combo Mùa Hè chưa có banner</div>
            <div class="alert-time">Cần hoàn thiện trước 30/5 · Trinh</div>
          </div>
        </div>
        <div class="alert-item">
          <div class="alert-icon ai-ok">✅</div>
          <div class="alert-content">
            <div class="alert-title">KM sinh nhật đã gửi 1,200 SMS</div>
            <div class="alert-time">Hoàn thành lúc 08:30 · Lan Anh</div>
          </div>
        </div>
        <div class="alert-item">
          <div class="alert-icon ai-info">📊</div>
          <div class="alert-content">
            <div class="alert-title">Báo cáo tuần đã sẵn sàng</div>
            <div class="alert-time">Lưu file vào Drive · 09:00 hôm nay</div>
          </div>
        </div>
      </div>
    </div>

    <!-- CALENDAR -->
    <div class="card">
      <div class="card-header">
        <div class="card-title"><div class="dot" style="background:var(--accent2)"></div>Lịch triển khai</div>
      </div>
      <div class="calendar-mini">
        <div class="cal-header">
          <span class="cal-month">Tháng 5 – 2026</span>
          <div class="cal-nav"><button>‹</button><button>›</button></div>
        </div>
        <div class="cal-grid">
          <div class="cal-day-name">CN</div><div class="cal-day-name">T2</div><div class="cal-day-name">T3</div><div class="cal-day-name">T4</div><div class="cal-day-name">T5</div><div class="cal-day-name">T6</div><div class="cal-day-name">T7</div>
          <div class="cal-day other-month">28</div><div class="cal-day other-month">29</div><div class="cal-day other-month">30</div><div class="cal-day">1</div><div class="cal-day has-event">2</div><div class="cal-day">3</div><div class="cal-day has-event">4</div>
          <div class="cal-day">5</div><div class="cal-day has-event">6</div><div class="cal-day">7</div><div class="cal-day">8</div><div class="cal-day has-event">9</div><div class="cal-day">10</div><div class="cal-day">11</div>
          <div class="cal-day">12</div><div class="cal-day">13</div><div class="cal-day">14</div><div class="cal-day has-event">15</div><div class="cal-day">16</div><div class="cal-day">17</div><div class="cal-day has-event">18</div>
          <div class="cal-day has-event">19</div><div class="cal-day">20</div><div class="cal-day">21</div><div class="cal-day">22</div><div class="cal-day has-event">23</div><div class="cal-day">24</div><div class="cal-day has-event">25</div>
          <div class="cal-day today has-event">27</div><div class="cal-day">28</div><div class="cal-day has-event">29</div><div class="cal-day">30</div><div class="cal-day has-event">31</div><div class="cal-day other-month">1</div><div class="cal-day other-month">2</div>
        </div>
      </div>
    </div>

  </div>

  <!-- CHECKLIST -->
  <div class="card">
    <div class="card-header">
      <div class="card-title"><div class="dot" style="background:var(--accent3)"></div>Checklist công việc hôm nay</div>
      <div style="font-size:12px;color:var(--muted)">17/25 hoàn thành</div>
    </div>
    <div style="display:grid;grid-template-columns:repeat(3,1fr);">
      <div class="checklist">
        <div style="font-size:11px;font-weight:700;color:var(--accent);text-transform:uppercase;letter-spacing:.8px;padding:8px 0 4px;">🎯 Triển khai KM</div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Tạo mã khuyến mãi trên hệ thống</div><span class="check-who">Ngọc</span></div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Upload banner lên Zalo OA</div><span class="check-who">Tài</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Duyệt nội dung Facebook post</div><span class="check-who">Trinh</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Test link ưu đãi trên web</div><span class="check-who">Lan Anh</span></div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Gửi brief cho team CSKH</div><span class="check-who">Ngọc</span></div>
      </div>
      <div class="checklist" style="border-left:1px solid var(--border)">
        <div style="font-size:11px;font-weight:700;color:var(--accent2);text-transform:uppercase;letter-spacing:.8px;padding:8px 0 4px;">📢 Truyền thông</div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Schedule post Facebook 8h sáng</div><span class="check-who">Trinh</span></div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Gửi Zalo broadcast đợt 1</div><span class="check-who">Tài</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">SMS blast khách VIP (3,500 số)</div><span class="check-who">Lan Anh</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Gửi email newsletter</div><span class="check-who">Trinh</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Check hiển thị pop-up web</div><span class="check-who">Ngọc</span></div>
      </div>
      <div class="checklist" style="border-left:1px solid var(--border)">
        <div style="font-size:11px;font-weight:700;color:var(--accent4);text-transform:uppercase;letter-spacing:.8px;padding:8px 0 4px;">📊 Theo dõi & báo cáo</div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Chụp số liệu đầu ngày</div><span class="check-who">Tài</span></div>
        <div class="check-item done" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Update sheet theo dõi đơn hàng</div><span class="check-who">Lan Anh</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Báo cáo kết quả buổi trưa</div><span class="check-who">Ngọc</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Tổng kết cuối ngày gửi nhóm</div><span class="check-who">Trinh</span></div>
        <div class="check-item" onclick="toggleCheck(this)"><div class="check-box"></div><div class="check-label">Lưu file báo cáo vào Drive</div><span class="check-who">Lan Anh</span></div>
      </div>
    </div>
  </div>

</div>

<!-- TOAST -->
<div class="toast" id="toast">✅ Đã thêm chương trình thành công!</div>

<!-- MODAL THÊM KM -->
<div class="modal-overlay" id="modal-overlay" onclick="handleOverlayClick(event)">
  <div class="modal" id="modal">
    <div class="modal-header">
      <h2 id="modal-title">＋ Thêm chương trình khuyến mãi</h2>
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div class="modal-body">

      <!-- Tên + Mã -->
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Tên chương trình *</label>
          <input class="form-input" id="f-name" type="text" placeholder="VD: Flash Sale Cuối Tuần">
        </div>
        <div class="form-group">
          <label class="form-label">Mã chương trình</label>
          <input class="form-input" id="f-code" type="text" placeholder="VD: KM-060101" readonly style="color:var(--muted)">
        </div>
      </div>

      <!-- Kênh + Phụ trách -->
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Kênh triển khai *</label>
          <select class="form-select" id="f-channel">
            <option value="">-- Chọn kênh --</option>
            <option value="">-- Chọn kênh --</option>
            <option value="ch-fanpage">Fanpage</option>
            <option value="ch-hotline">Hotline</option>
            <option value="ch-zalo">Zalo Phòng</option>
            <option value="ch-cuahang">Cửa hàng</option>
            <option value="ch-all">Tất cả kênh</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Người phụ trách *</label>
          <select class="form-select" id="f-owner">
            <option value="">-- Chọn nhân sự --</option>
            <option>Ngọc</option>
            <option>Tài</option>
            <option>Trinh</option>
            <option>Lan Anh</option>
          </select>
        </div>
      </div>

      <!-- Ngày bắt đầu + kết thúc -->
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">Ngày bắt đầu *</label>
          <input class="form-input" id="f-start" type="date">
        </div>
        <div class="form-group">
          <label class="form-label">Ngày kết thúc *</label>
          <input class="form-input" id="f-end" type="date">
        </div>
      </div>

      <!-- Ưu tiên -->
      <div class="form-group full">
        <label class="form-label">Mức độ ưu tiên *</label>
        <div class="priority-group">
          <button class="priority-pill high" onclick="selectPriority(this,'p-high')">🔴 Cao</button>
          <button class="priority-pill med"  onclick="selectPriority(this,'p-med')">🟡 Trung bình</button>
          <button class="priority-pill low"  onclick="selectPriority(this,'p-low')">🟢 Thấp</button>
        </div>
      </div>

      <!-- Mô tả -->
      <div class="form-group full">
        <label class="form-label">Mô tả chương trình</label>
        <textarea class="form-textarea" id="f-desc" placeholder="Nội dung, ưu đãi, mức giảm..."></textarea>
      </div>

      <!-- Điều kiện -->
      <div class="form-group full">
        <label class="form-label">Điều kiện áp dụng</label>
        <textarea class="form-textarea" id="f-cond" placeholder="Điều kiện, giới hạn sử dụng..."></textarea>
      </div>

      <!-- Cửa hàng tham gia -->
      <div class="form-group full">
        <label class="form-label" style="display:flex;align-items:center;justify-content:space-between;">
          Cửa hàng tham gia
          <button type="button" onclick="addCustomStore()" style="font-size:11px;font-weight:700;padding:4px 10px;border-radius:7px;background:rgba(249,115,22,.15);color:var(--accent);border:1px solid rgba(249,115,22,.3);cursor:pointer;font-family:inherit;">＋ Thêm cửa hàng</button>
        </label>
        <div style="margin-bottom:8px;">
          <div class="store-search" style="margin-bottom:0;">
            <span>🔍</span>
            <input type="text" id="form-store-search" placeholder="Tìm cửa hàng trong form..." oninput="filterFormStores(this.value)">
          </div>
        </div>
        <div class="store-check-list" id="store-check-list"></div>
      </div>

    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" onclick="closeModal()">Huỷ</button>
      <button class="btn btn-primary" id="modal-submit-btn" onclick="submitForm()">＋ Thêm chương trình</button>
    </div>
  </div>
</div>

<!-- CONFIRM DELETE -->
<div class="confirm-overlay" id="confirm-overlay">
  <div class="confirm-box">
    <div class="confirm-icon">🗑️</div>
    <div class="confirm-title">Xoá chương trình này?</div>
    <div class="confirm-sub" id="confirm-sub">Thao tác này không thể hoàn tác.</div>
    <div class="confirm-actions">
      <button class="btn btn-ghost" onclick="closeConfirm()">Huỷ bỏ</button>
      <button class="btn btn-primary" style="background:var(--danger)" onclick="doDelete()">🗑️ Xoá ngay</button>
    </div>
  </div>
</div>

<script>
// ===== DATA =====
const promos = [
  {
    id:'KM-052601', name:'Flash Sale Cuối Tuần', channel:'ch-all', channelLabel:'Tất cả kênh',
    dateRange:'25/5 – 26/5', dateNote:'⏰ Còn 1 ngày!', dateColor:'var(--danger)',
    progress:85, progressColor:'var(--accent3)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Ngọc', priority:'p-high',
    description:'Chương trình giảm giá cuối tuần dành cho tất cả khách hàng. Áp dụng toàn bộ sản phẩm, giảm tối đa 50%.',
    condition:'Không giới hạn số lần dùng. Áp dụng đơn từ 150.000đ trở lên.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:false},
    ]
  },
  {
    id:'KM-052602', name:'Ưu đãi thành viên VIP', channel:'ch-zalo', channelLabel:'Zalo Phòng',
    dateRange:'20/5 – 30/5', dateNote:'⏰ Còn 3 ngày', dateColor:'var(--warning)',
    progress:60, progressColor:'var(--accent2)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Tài', priority:'p-high',
    description:'Chương trình dành riêng cho thành viên VIP. Giảm 30% cho tất cả đơn hàng, tặng thêm quà sinh nhật.',
    condition:'Chỉ áp dụng cho thành viên có hạng VIP trở lên. Mỗi thành viên dùng 1 lần/tháng.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:false},
    ]
  },
  {
    id:'KM-052603', name:'Combo Mùa Hè 2026', channel:'ch-fanpage', channelLabel:'Fanpage',
    dateRange:'01/6 – 15/6', dateNote:'Còn 5 ngày', dateColor:'var(--muted)',
    progress:30, progressColor:'var(--warning)', status:'s-upcoming', statusLabel:'Sắp tới',
    owner:'Trinh', priority:'p-med',
    description:'Combo sản phẩm mùa hè với giá đặc biệt. Mua combo tiết kiệm hơn 25% so với mua lẻ từng sản phẩm.',
    condition:'Áp dụng khi mua combo đúng bộ. Không kết hợp với các KM khác.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:true},
    ]
  },
  {
    id:'KM-052604', name:'Tặng quà sinh nhật KH', channel:'ch-hotline', channelLabel:'Hotline',
    dateRange:'01/5 – 31/5', dateNote:'Chạy cả tháng', dateColor:'var(--muted)',
    progress:75, progressColor:'var(--accent4)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Lan Anh', priority:'p-med',
    description:'Gửi SMS chúc mừng sinh nhật kèm voucher giảm giá 20% cho khách hàng trong tháng sinh nhật.',
    condition:'Tự động gửi vào ngày sinh nhật của khách. Voucher có hiệu lực 7 ngày.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
    ]
  },
  {
    id:'KM-052605', name:'Freeship đơn từ 200k', channel:'ch-all', channelLabel:'Tất cả kênh',
    dateRange:'29/5 – 02/6', dateNote:'Còn 2 ngày', dateColor:'var(--muted)',
    progress:10, progressColor:'var(--accent)', status:'s-upcoming', statusLabel:'Sắp tới',
    owner:'Ngọc', priority:'p-low',
    description:'Miễn phí giao hàng cho đơn hàng từ 200.000đ. Áp dụng toàn quốc, tất cả đơn online.',
    condition:'Áp dụng cho đơn đặt qua app và website. Không áp dụng tại quầy.',
    stores:[
      {icon:'🏪', name:'Online – App', addr:'Toàn quốc', join:true},
      {icon:'🏬', name:'Online – Website', addr:'Toàn quốc', join:true},
    ]
  },
  {
    id:'KM-052500', name:'Ưu đãi ngày lẻ tháng 5', channel:'ch-zalo', channelLabel:'Zalo Phòng',
    dateRange:'15/5 – 20/5', dateNote:'—', dateColor:'var(--muted)',
    progress:100, progressColor:'var(--muted)', status:'s-ended', statusLabel:'Kết thúc',
    owner:'Tài', priority:'p-low',
    description:'Chương trình khuyến mãi các ngày lẻ trong tháng 5. Giảm 15% cho tất cả sản phẩm.',
    condition:'Áp dụng các ngày 15, 17, 19 tháng 5. Mỗi ngày chỉ áp dụng 1 lần/khách.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
    ]
  },
  {
    id:'KM-060101', name:'Siêu Sale 1/6 Thiếu Nhi', channel:'ch-all', channelLabel:'Tất cả kênh',
    dateRange:'01/6 – 01/6', dateNote:'⏰ Còn 3 ngày', dateColor:'var(--warning)',
    progress:45, progressColor:'var(--warning)', status:'s-upcoming', statusLabel:'Sắp tới',
    owner:'Trinh', priority:'p-high',
    description:'Siêu sale nhân ngày Quốc tế Thiếu Nhi 1/6. Giảm đến 40% nhóm sản phẩm dành cho trẻ em và gia đình.',
    condition:'Chỉ áp dụng ngày 1/6. Số lượng có hạn, áp dụng đến khi hết hàng.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:true},
      {icon:'🏪', name:'Online – App', addr:'Toàn quốc', join:true},
    ]
  },
  {
    id:'KM-052606', name:'Giảm 20% cho khách mới', channel:'ch-fanpage', channelLabel:'Fanpage',
    dateRange:'27/5 – 10/6', dateNote:'Còn 12 ngày', dateColor:'var(--muted)',
    progress:20, progressColor:'var(--accent2)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Lan Anh', priority:'p-med',
    description:'Chào mừng khách hàng mới với voucher giảm 20% cho lần mua đầu tiên. Quảng bá qua Facebook Ads.',
    condition:'Chỉ áp dụng cho tài khoản mới đăng ký. Dùng 1 lần duy nhất.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏪', name:'Online – App', addr:'Toàn quốc', join:true},
      {icon:'🏬', name:'Online – Website', addr:'Toàn quốc', join:true},
    ]
  },
  {
    id:'KM-060201', name:'Tích điểm đổi quà tháng 6', channel:'ch-zalo', channelLabel:'Zalo Phòng',
    dateRange:'05/6 – 30/6', dateNote:'Còn 7 ngày', dateColor:'var(--muted)',
    progress:15, progressColor:'var(--accent4)', status:'s-upcoming', statusLabel:'Sắp tới',
    owner:'Ngọc', priority:'p-high',
    description:'Chương trình tích điểm tháng 6 — đổi điểm lấy quà hấp dẫn. Điểm x2 cho mọi giao dịch trong tháng.',
    condition:'Áp dụng cho thành viên đã đăng ký chương trình tích điểm. Quà có hạn số lượng.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:false},
    ]
  },
  {
    id:'KM-052607', name:'Mua 2 tặng 1 – Sản phẩm mới', channel:'ch-hotline', channelLabel:'Hotline',
    dateRange:'28/5 – 05/6', dateNote:'Còn 7 ngày', dateColor:'var(--muted)',
    progress:55, progressColor:'var(--accent3)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Tài', priority:'p-low',
    description:'Mua 2 sản phẩm mới ra mắt tháng 5, tặng 1 sản phẩm cùng loại. Áp dụng cho 5 dòng sản phẩm mới.',
    condition:'Chỉ áp dụng cho 5 SKU mới ra mắt. Số lượng quà tặng có giới hạn theo cửa hàng.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:false},
    ]
  },
  {
    id:'KM-052608', name:'Hoàn tiền 15% ví điện tử', channel:'ch-all', channelLabel:'Tất cả kênh',
    dateRange:'01/5 – 25/5', dateNote:'—', dateColor:'var(--muted)',
    progress:100, progressColor:'var(--muted)', status:'s-ended', statusLabel:'Kết thúc',
    owner:'Trinh', priority:'p-med',
    description:'Hoàn 15% vào ví điện tử khi thanh toán qua MoMo, ZaloPay, VNPay trong tháng 5.',
    condition:'Hoàn tối đa 50.000đ/giao dịch. Áp dụng tối đa 3 lần/khách hàng.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:true},
    ]
  },
  {
    id:'KM-052609', name:'Ưu đãi cuối tháng – Thanh lý', channel:'ch-fanpage', channelLabel:'Fanpage',
    dateRange:'29/5 – 31/5', dateNote:'⏰ Còn 2 ngày!', dateColor:'var(--danger)',
    progress:70, progressColor:'var(--accent)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Lan Anh', priority:'p-low',
    description:'Thanh lý hàng tồn kho cuối tháng, giảm từ 30–60% các sản phẩm theo danh sách đính kèm.',
    condition:'Áp dụng danh sách SKU riêng. Không hoàn đổi sau khi mua.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:false},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
    ]
  },
  {
    id:'KM-052610', name:'Giờ vàng 12h – 13h hằng ngày', channel:'ch-zalo', channelLabel:'Zalo Phòng',
    dateRange:'25/5 – 31/5', dateNote:'⏰ Còn 2 ngày', dateColor:'var(--warning)',
    progress:90, progressColor:'var(--accent3)', status:'s-live', statusLabel:'Đang chạy',
    owner:'Ngọc', priority:'p-high',
    description:'Giảm 25% tất cả đơn hàng trong khung giờ 12:00 – 13:00 hằng ngày. Push thông báo qua Zalo.',
    condition:'Áp dụng đúng khung giờ 12h–13h. Đơn đặt ngoài giờ không được tính.',
    stores:[
      {icon:'🏪', name:'Chi nhánh Ninh Kiều', addr:'123 Nguyễn Trãi, Q. Ninh Kiều', join:true},
      {icon:'🏬', name:'Chi nhánh Bình Thủy', addr:'45 Lê Lợi, Q. Bình Thủy', join:true},
      {icon:'🏪', name:'Chi nhánh Cái Răng', addr:'78 CMT8, Q. Cái Răng', join:true},
      {icon:'🏬', name:'Chi nhánh Ô Môn', addr:'12 Trần Phú, Q. Ô Môn', join:true},
      {icon:'🏪', name:'Online – App', addr:'Toàn quốc', join:true},
    ]
  },
];

// ── EDIT ──
function openEditModal(idx) {
  const p = promos[idx];
  editingIdx = idx;
  document.getElementById('modal-title').textContent = '✏️ Chỉnh sửa chương trình';
  document.getElementById('modal-submit-btn').textContent = '💾 Lưu thay đổi';

  // Fill fields
  document.getElementById('f-code').value = p.id;
  document.getElementById('f-code').readOnly = true;
  document.getElementById('f-name').value = p.name;
  document.getElementById('f-channel').value = p.channel;
  document.getElementById('f-owner').value = p.owner;
  document.getElementById('f-desc').value = p.description || '';
  document.getElementById('f-cond').value = p.condition || '';

  // Priority
  selectedPriority = p.priority;
  document.querySelectorAll('.priority-pill').forEach(pill => {
    pill.classList.remove('sel');
    if ((p.priority === 'p-high' && pill.classList.contains('high')) ||
        (p.priority === 'p-med'  && pill.classList.contains('med'))  ||
        (p.priority === 'p-low'  && pill.classList.contains('low')))
      pill.classList.add('sel');
  });

  // Parse dateRange "dd/mm – dd/mm" back to input[date] value
  try {
    const parts = p.dateRange.split('–').map(s => s.trim()); // ["25/5", "26/5"]
    const toISO = str => {
      const [d, m] = str.split('/');
      return `2026-${String(m).padStart(2,'0')}-${String(d).padStart(2,'0')}`;
    };
    document.getElementById('f-start').value = toISO(parts[0]);
    document.getElementById('f-end').value   = toISO(parts[1]);
  } catch(e) {}

  // Render stores, pre-check ones that joined
  renderFormStores('');
  const joinedNames = (p.stores || []).filter(s => s.join).map(s => s.name);
  document.querySelectorAll('#store-check-list .store-check-item').forEach(el => {
    if (joinedNames.includes(el.getAttribute('data-store'))) {
      el.classList.add('checked');
      el.querySelector('.sck-box').textContent = '✓';
    }
  });

  document.getElementById('modal-overlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}

// ── DELETE ──
let deleteIdx = -1;
function confirmDelete(idx) {
  deleteIdx = idx;
  document.getElementById('confirm-sub').textContent =
    `"${promos[idx].name}" sẽ bị xoá vĩnh viễn. Thao tác này không thể hoàn tác.`;
  document.getElementById('confirm-overlay').classList.add('open');
}
function closeConfirm() {
  document.getElementById('confirm-overlay').classList.remove('open');
  deleteIdx = -1;
}
function doDelete() {
  if (deleteIdx < 0) return;
  // close drawer if showing same item
  if (document.getElementById('drawer').classList.contains('open')) closeDrawer();
  promos.splice(deleteIdx, 1);
  renderTable();
  closeConfirm();
  // update stats
  document.querySelector('.stat-card.orange .stat-value').textContent = promos.filter(p=>p.status==='s-live').length;
  document.querySelector('.stat-card.blue .stat-value').textContent   = promos.filter(p=>p.status==='s-upcoming').length;
  showToast('🗑️ Đã xoá chương trình thành công!', 'var(--danger)');
}


// ===== RENDER TABLE =====
function renderTable() {
  const tbody = document.getElementById('promo-table');
  tbody.innerHTML = promos.map((p,i) => `
    <tr onclick="openDrawer(${i})" data-idx="${i}">
      <td><span class="priority ${p.priority}"></span></td>
      <td><div class="promo-name">${p.name}</div><div style="font-size:11px;color:var(--muted)">Mã: ${p.id}</div></td>
      <td><span class="promo-channel ${p.channel}">${p.channelLabel}</span></td>
      <td><div style="font-size:12px;">${p.dateRange}</div><div style="font-size:11px;color:${p.dateColor};font-weight:600">${p.dateNote}</div></td>
      <td><div class="progress-wrap"><div class="progress-bar"><div class="progress-fill" style="width:${p.progress}%;background:${p.progressColor}"></div></div><span class="progress-pct">${p.progress}%</span></div></td>
      <td><span class="status-badge ${p.status}">${p.statusLabel}</span></td>
      <td><span class="owner-tag">${p.owner}</span></td>
      <td onclick="event.stopPropagation()">
        <div class="action-btns">
          <button class="act-btn edit" title="Chỉnh sửa" onclick="openEditModal(${i})">✏️</button>
          <button class="act-btn del"  title="Xóa" onclick="confirmDelete(${i})">🗑️</button>
        </div>
      </td>
    </tr>
  `).join('');
}

// ===== DRAWER =====
function openDrawer(idx) {
  const p = promos[idx];
  // highlight row
  document.querySelectorAll('tbody tr').forEach(r => r.classList.remove('active-row'));
  document.querySelector(`tr[data-idx="${idx}"]`).classList.add('active-row');

  document.getElementById('d-title').textContent = p.name;
  document.getElementById('d-code').textContent = 'Mã: ' + p.id + '  ·  Phụ trách: ' + p.owner;

  const joinCount = p.stores.filter(s=>s.join).length;

  document.getElementById('drawer-body').innerHTML = `
    <div class="drawer-section">
      <div class="drawer-section-title">Thông tin chung</div>
      <div class="info-row"><span class="info-label">Kênh triển khai</span><span class="info-value"><span class="promo-channel ${p.channel}" style="display:inline-block">${p.channelLabel}</span></span></div>
      <div class="info-row"><span class="info-label">Thời gian</span><span class="info-value">${p.dateRange}</span></div>
      <div class="info-row"><span class="info-label">Trạng thái</span><span class="info-value"><span class="status-badge ${p.status}">${p.statusLabel}</span></span></div>
      <div class="info-row"><span class="info-label">Phụ trách</span><span class="info-value"><span class="owner-tag">${p.owner}</span></span></div>
    </div>

    <div class="drawer-section">
      <div class="drawer-section-title">Tiến độ chuẩn bị</div>
      <div class="progress-big">
        <div class="bar"><div class="fill" style="width:${p.progress}%;background:${p.progressColor}"></div></div>
        <div class="label"><span>Hoàn thành ${p.progress}%</span><span style="color:${p.progressColor};font-weight:700">${p.progress >= 80 ? '✅ Tốt' : p.progress >= 40 ? '⚡ Đang làm' : '⚠️ Cần đẩy nhanh'}</span></div>
      </div>
    </div>

    <div class="drawer-section">
      <div class="drawer-section-title">Mô tả chương trình</div>
      <div class="note-box">${p.description}</div>
    </div>

    <div class="drawer-section">
      <div class="drawer-section-title">Điều kiện áp dụng</div>
      <div class="note-box" style="background:rgba(59,130,246,.06);border-color:rgba(59,130,246,.2)">${p.condition}</div>
    </div>

    <div class="drawer-section">
      <div class="drawer-section-title">Cửa hàng tham gia (${joinCount}/${p.stores.length})</div>
      <div class="store-search">
        <span>🔍</span>
        <input type="text" id="store-search-input" placeholder="Tìm tên cửa hàng..." oninput="filterStores(this.value, ${idx})">
      </div>
      <div class="store-list" id="store-list-container">
        ${p.stores.map(s => `
          <div class="store-item" data-store-name="${s.name.toLowerCase()}">
            <div class="store-icon" style="background:${s.join ? 'rgba(34,197,94,.1)' : 'rgba(139,148,164,.1)'}">${s.icon}</div>
            <div class="store-info">
              <div class="store-name">${s.name}</div>
              <div class="store-addr">${s.addr || s.dia_chi || ''}</div>
              ${s.lien_he ? `<div class="store-addr" style="color:var(--accent2)">📞 ${s.lien_he}</div>` : ''}
              ${s.mien ? `<div class="store-addr">📍 ${s.mien}</div>` : ''}
            </div>
            <span class="store-badge ${s.join ? 'sb-yes' : 'sb-no'}">${s.join ? 'Tham gia' : 'Không tham gia'}</span>
          </div>
        `).join('')}
      </div>
    </div>
  `;

  document.getElementById('drawer').classList.add('open');
  document.getElementById('main').classList.add('drawer-open');
}

function closeDrawer() {
  document.getElementById('drawer').classList.remove('open');
  document.getElementById('main').classList.remove('drawer-open');
  document.querySelectorAll('tbody tr').forEach(r => r.classList.remove('active-row'));
}


// ===== MODAL =====
let selectedPriority = '';
let editingIdx = -1; // -1 = add mode, >=0 = edit mode
const MASTER_STORES = [{"ma": "PHUCTEA004", "ten": "THÍCH QUẢNG ĐỨC LONG KHÁNH", "dia_chi": "02 Thích Quảng Đức, phường Xuân An, TP. Long Khánh, Đồng Nai", "lien_he": "0941835373", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA006", "ten": "PHAN RANG", "dia_chi": "(Gần Lẩu bò Sáu Hít) 117 Trần Quang Diệu, phường Thanh Sơn, Phan Rang-Tháp Chàm, Ninh Thuận", "lien_he": "0933800585", "mien": "Miền Trung", "icon": "🏬"}, {"ma": "PHUCTEA007", "ten": "TÔN ĐỨC THẮNG LONG THÀNH", "dia_chi": "(Đối diện Bánh kem Ngọc Trai, kế Tiệm Lẩu Nhà Nì) Tôn Đức Thắng, thị trấn Long Thành, huyện Long Thành, Đồng Nai", "lien_he": "090 8983390", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA023", "ten": "TRẢNG DÀI", "dia_chi": "(Đối diện trường Đại Học Công Nghệ Đồng Nai) đường Nguyễn Khuyến, tổ 2, khu phố 5, phường Trảng Dài, TP. Biên Hòa, Đồng Nai", "lien_he": "", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA034", "ten": "NGUYỄN AN NINH DĨ AN", "dia_chi": "(Gần Ga Dĩ An) Số 352 đường Nguyễn An Ninh, thị xã Dĩ An, huyện Dĩ An, Bình Dương", "lien_he": "0969122221", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA044", "ten": "AN NHƠN", "dia_chi": "177 Đường Nguyễn Sinh Sắc nối dài, G1 Khu đô thị mới Bắc Tân An, phường Bình Định, thị xã An Nhơn, Bình Định", "lien_he": "0964621777", "mien": "Miền Trung", "icon": "🏬"}, {"ma": "PHUCTEA045", "ten": "PHÚ TÀI", "dia_chi": "(Đối diện công viên Phú Tài) Số 1736 đường Hùng Vương, phường Trần Quang Diệu, TP. Quy Nhơn, Bình Định", "lien_he": "0974733554", "mien": "Miền Trung", "icon": "🏬"}, {"ma": "PHUCTEA056", "ten": "BÌNH TÂN VĨNH LONG", "dia_chi": "(Đối diện cây xăng Tân Quới) ấp Tân Thuận, xã Tân Quới, huyện Bình Tân, Vĩnh Long", "lien_he": "0973998905 / 0377330738", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA059", "ten": "MỸ PHƯỚC BẾN CÁT", "dia_chi": "265 đường 30/4, khu phố 2, phường Mỹ Phước, thị xã Bến Cát, Bình Dương", "lien_he": "0365611053", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA062", "ten": "BẾN LỨC", "dia_chi": "(gần cổng chào Bến Lức) 62 Nguyễn Hữu Thọ, thị trấn Bến Lức, huyện Bến Lức, Long An", "lien_he": "0397938240", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA068", "ten": "HÀ LAM", "dia_chi": "79, Lý Tự Trọng, Thị Trấn Hà Lam, Huyện Thăng Bình, Quảng Nam", "lien_he": "0934783830 / 0932440150", "mien": "Miền Trung", "icon": "🏬"}, {"ma": "PHUCTEA076", "ten": "TRỊ AN", "dia_chi": "(Sát Mỳ cay Seoul, đầu khu công nghiệp Sông Mây) 329 đường Tây Lạc (đường 767), ấp Bùi Chu, xã Bắc Sơn, huyện Trảng Bom, Đồng Nai", "lien_he": "0343980445", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA091", "ten": "BÌNH CHÂU", "dia_chi": "Ấp Thanh Bình 3, xã Bình Châu, huyện Xuyên Mộc, Bà Rịa - Vũng Tàu", "lien_he": "0363678579", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA094", "ten": "NINH PHƯỚC", "dia_chi": "(Gần Cầu Phú Quý & Chợ Phú Quý) 206 Quốc lộ 1, thị trấn Phước Dân, huyện Ninh Phước, Ninh Thuận", "lien_he": "0919636285", "mien": "Miền Trung", "icon": "🏬"}, {"ma": "PHUCTEA099", "ten": "BÌNH MINH", "dia_chi": "(Đối diện Công An phường Cái Vồn) Số 144 Nguyễn Văn Thảnh, khóm 5, phường Cái Vồn, thị xã Bình Minh, Vĩnh Long", "lien_he": "0702526831", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA101", "ten": "VĨNH AN", "dia_chi": "Số 169 đường Quang Trung, KP3, thị trấn Vĩnh An, huyện Vĩnh Cửu, Đồng Nai", "lien_he": "0985886307", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA107", "ten": "MỸ PHƯỚC 2 BẾN CÁT", "dia_chi": "68 đường XC2, khu phố 3, phường Mỹ Phước, thị xã Bến Cát, Bình Dương", "lien_he": "0762974730", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA108", "ten": "Ô MÔN", "dia_chi": "1251 đường Nguyễn Trãi, phường Châu Văn Liêm, quận Ô Môn, TP. Cần Thơ, Cần Thơ", "lien_he": "0949977902", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA111", "ten": "BÀU BÀNG", "dia_chi": "Số A6, Căn 47, Phố Thương Mại Bàu Bàng, Đ. NC, xã Lai Uyên, huyện Bàu Bàng, Bình Dương", "lien_he": "0823931292", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA114", "ten": "MỸ PHƯỚC 3 BẾN CÁT", "dia_chi": "Lô J55, đường NE8, Mỹ Phước 3, phường Thới Hòa, thị xã Bến Cát, Bình Dương", "lien_he": "0762974730", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA116", "ten": "AN TÂY", "dia_chi": "83A đường DT744, ấp An Thành, xã An Tây, thị xã Bến Cát, Bình Dương", "lien_he": "0767739749", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA120", "ten": "CHƠN THÀNH", "dia_chi": "(Đối diện trung tâm thương mại và Plaza Chơn Thành) Tổ 1, khu phố 1, phường Hưng Long, thị xã Chơn Thành, Bình Phước", "lien_he": "0862119087", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA128", "ten": "GÒ CÔNG TÂY", "dia_chi": "(Gần Trường THPT Vĩnh Bình) ấp Bình Hoà Đông, xã Bình Nhì, huyện Gò Công Tây, Tiền Giang", "lien_he": "0847422578  / 0947422578", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA130", "ten": "THỦ ĐỨC", "dia_chi": "33 Chương Dương, phường Linh Chiểu, quận Thủ Đức, TP. Thủ Đức, Hồ Chí Minh", "lien_he": "0386266590", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA135", "ten": "VÕ NGUYÊN GIÁP TRÀ VINH", "dia_chi": "TNR Amaluna Trà Vinh -TNR Holding, C2-16, Võ Nguyên Giáp, phường 7, TP. Trà Vinh, Trà Vinh (Gần siêu thị GO)", "lien_he": "0932720388", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA137", "ten": "VĨNH TÂN", "dia_chi": "Số nhà D-32.37 KDC Sun Casa Central, phường Vĩnh Tân, TP. Tân Uyên, Bình Dương", "lien_he": "", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA138", "ten": "TRẦN HOÀNG NA CẦN THƠ", "dia_chi": "151/47, khu vực 2, đường Trần Hoàng Na, phường Hưng Lợi, quận Ninh Kiều, TP. Cần Thơ, Cần Thơ", "lien_he": "", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA139", "ten": "HÒA LẠC HÀ NỘI", "dia_chi": "Số 360, thôn 3, xã Thạch Hòa, huyện Thạch Thất, Hà Nội", "lien_he": "0964472197 / 0984379693", "mien": "Miền Bắc", "icon": "🏪"}, {"ma": "PHUCTEA140", "ten": "NGUYỄN VĂN KHỐI GÒ VẤP", "dia_chi": "253, Nguyễn Văn Khối, phường 9, quận Gò Vấp, HCM", "lien_he": "0901233964", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA143", "ten": "THỚI HÒA BẾN CÁT", "dia_chi": "198 đường D10, khu phố 6, phường Thới Hòa, thị xã Bến Cát, Bình Dương", "lien_he": "084 2022698", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA147", "ten": "PHÚ LỢI THỦ DẦU MỘT", "dia_chi": "Số 275, DT743, Phường Phú Lợi, Thành Phố Thủ Dầu Một, Tỉnh Bình Dương", "lien_he": "0978544598", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA148", "ten": "LÊ LỢI LAI VUNG", "dia_chi": "(Dưới chân cầu Hòa Long) 423, Lê Lợi, Khóm 1, Thị trấn Lai Vung, Huyện Lai Vung, Đồng Tháp", "lien_he": "0774005312", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA149", "ten": "HÙNG VƯƠNG ĐỒNG XOÀI", "dia_chi": "74, Hùng Vương, Phường Tân Bình, Thành Phố Đồng Xoài, Bình Phước", "lien_he": "096 7704734", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA150", "ten": "CHỬ ĐỒNG TỬ TÂN BÌNH", "dia_chi": "43, Chử Đồng Tử, phường 7, quận Tân Bình, TP. HCM", "lien_he": "0901777839", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA151", "ten": "BÌNH SƠN LONG THÀNH", "dia_chi": "(Kế bên quán cà phê Phố) 411, DT769, ấp 1, xã Bình Sơn, huyện Long Thành, Đồng Nai", "lien_he": "0913614999", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA152", "ten": "VÕ OANH BÌNH THẠNH", "dia_chi": "42, Võ Oanh, phường 25, quận Bình Thạnh, TP. HCM", "lien_he": "0702526508", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA153", "ten": "HỒ THỊ THƯỞNG THỚI LAI", "dia_chi": "(Đối diện Công an Thị trấn Thới Lai) Ấp Thới Thuận A, thị trấn Thới Lai, huyện Thới Lai, TP. Cần Thơ", "lien_he": "0939070723", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA095", "ten": "CÁI TẮC", "dia_chi": "(Kế bên Điện máy xanh) 37 QL61, Ấp Tân Phú A, Thị trấn Cái Tắc, Châu Thành A, Hậu Giang", "lien_he": "0767992374", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA155", "ten": "PHÚ CHÁNH", "dia_chi": "742, đường Huỳnh Văn Lũy, phường Phú Chánh, Thành phố Tân Uyên, Bình Dương", "lien_he": "0968145915", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA156", "ten": "ĐINH ĐỨC THIỆN BÌNH CHÁNH", "dia_chi": "D12/56A, Huỳnh Văn Trí, Ấp 8, xã Bình Chánh, huyện Bình Chánh, TP. Hồ Chí Minh", "lien_he": "0987886818 / 0931513283", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA157", "ten": "ĐOÀN THỊ ĐIỂM XUÂN LỘC", "dia_chi": "18 Đoàn Thị Điểm, Thị trấn Gia Ray, Huyện Xuân Lộc, Đồng Nai Từ photocopy Cảnh vào 50m (chỗ hẻm đối diện shop Tuấn Tài)", "lien_he": "0878888860", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA158", "ten": "ĐỨC HÒA TÂY NINH", "dia_chi": "523, TL 825, Ấp Bình Tiền 2, Xã Đức Hoà Hạ, Huyện Đức Hoà, Tỉnh Long An", "lien_he": "0839747839", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA159", "ten": "TÂN PHƯỚC KHÁNH", "dia_chi": "78, Lý Tự Trọng, Tổ 3, Khu Phố Khánh Hội, Tân Phước Khánh, Thành phố Tân Uyên, Tỉnh Bình Dương", "lien_he": "0968976338", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA160", "ten": "CẦU TRÀM", "dia_chi": "(Đối diện Cầu Tràm Quán) 254, Ấp Cầu Tràm, Xã Long Trạch, Huyện Cần Đước, Tỉnh Long An", "lien_he": "0766849968", "mien": "Miền Tây", "icon": "🏪"}, {"ma": "PHUCTEA161", "ten": "ĐỖ XUÂN HỢP", "dia_chi": "575A, Đỗ Xuân Hợp, Phường Phước Long, TP. Hồ Chí Minh", "lien_he": "0329515505", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA162", "ten": "THẠNH PHÚ VĨNH CỬU", "dia_chi": "(Cách BIDV Thạnh Phú 2 căn) ĐT768, Tổ 8, Ấp 5, Xã Thạnh Phú, Huyện Vĩnh Cửu, Tỉnh Đồng Nai", "lien_he": "", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA163", "ten": "TÂN NINH TÂY NINH", "dia_chi": "1178, Cách Mạng Tháng 8, Phường 4, Thành Phố Tây Ninh, Tỉnh Tây Ninh (ngay đèn đỏ cách Con Cưng 02 căn)", "lien_he": "", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA164", "ten": "NGUYỄN VĂN LINH BÀ RỊA", "dia_chi": "219 Nguyễn Văn Linh, Phường Phước Nguyên, Thành Phố Bà Rịa, Tỉnh Bà Rịa - Vũng Tàu", "lien_he": "", "mien": "Miền Nam", "icon": "🏪"}, {"ma": "PHUCTEA165", "ten": "SÓC TRĂNG", "dia_chi": "72 Lê Lợi, Khu Phố 4, Phường 6, Thị Xã Sóc Trăng, Sóc Trăng", "lien_he": "", "mien": "Miền Tây", "icon": "🏪"}];

let autoCodeCounter = 100;

function openModal() {
  editingIdx = -1;
  document.getElementById('modal-title').textContent = '＋ Thêm chương trình khuyến mãi';
  document.getElementById('modal-submit-btn').textContent = '＋ Thêm chương trình';
  document.getElementById('f-code').readOnly = false;
  // Auto-generate code
  const now = new Date();
  const mm = String(now.getMonth()+1).padStart(2,'0');
  const dd = String(now.getDate()).padStart(2,'0');
  autoCodeCounter++;
  document.getElementById('f-code').value = `KM-${String(now.getFullYear()).slice(2)}${mm}${dd}${autoCodeCounter}`;

  // Reset form
  ['f-name','f-desc','f-cond','f-start','f-end'].forEach(id => document.getElementById(id).value = '');
  document.getElementById('f-channel').value = '';
  document.getElementById('f-owner').value = '';
  document.querySelectorAll('.priority-pill').forEach(p => p.classList.remove('sel'));
  renderFormStores(''); // rebuild from master list
  selectedPriority = '';

  document.getElementById('modal-overlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}

function closeModal() {
  document.getElementById('modal-overlay').classList.remove('open');
  document.body.style.overflow = '';
}

function handleOverlayClick(e) {
  if (e.target === document.getElementById('modal-overlay')) closeModal();
}

function selectPriority(el, val) {
  document.querySelectorAll('.priority-pill').forEach(p => p.classList.remove('sel'));
  el.classList.add('sel');
  selectedPriority = val;
}

function toggleStoreCheck(el) {
  el.classList.toggle('checked');
  el.querySelector('.sck-box').textContent = el.classList.contains('checked') ? '✓' : '';
}

function submitForm() {
  const name = document.getElementById('f-name').value.trim();
  const channel = document.getElementById('f-channel').value;
  const owner = document.getElementById('f-owner').value;
  const start = document.getElementById('f-start').value;
  const end = document.getElementById('f-end').value;

  // Validation
  if (!name) { highlight('f-name'); return; }
  if (!channel) { highlight('f-channel'); return; }
  if (!owner) { highlight('f-owner'); return; }
  if (!start) { highlight('f-start'); return; }
  if (!end) { highlight('f-end'); return; }
  if (!selectedPriority) { document.querySelector('.priority-group').style.outline = '2px solid var(--danger)'; return; }

  const channelMap = { 'ch-fanpage':'Fanpage', 'ch-hotline':'Hotline', 'ch-zalo':'Zalo Phòng', 'ch-cuahang':'Cửa hàng', 'ch-all':'Tất cả kênh' };

  // Format date dd/mm
  const fmt = d => { const [y,m,day] = d.split('-'); return `${day}/${m}`; };
  const dateRange = `${fmt(start)} – ${fmt(end)}`;

  // Collect stores
  const stores = [];
  document.querySelectorAll('#store-check-list .store-check-item').forEach(el => {
    stores.push({
      icon: el.getAttribute('data-icon') || '🏪',
      name: el.getAttribute('data-store'),
      addr: el.getAttribute('data-addr'),
      lien_he: el.getAttribute('data-lien_he') || '',
      mien: el.getAttribute('data-mien') || '',
      join: el.classList.contains('checked')
    });
  });

  const newPromo = {
    id: document.getElementById('f-code').value,
    name,
    channel,
    channelLabel: channelMap[channel],
    dateRange,
    dateNote: 'Mới thêm',
    dateColor: 'var(--accent2)',
    progress: 0,
    progressColor: 'var(--accent)',
    status: 's-upcoming',
    statusLabel: 'Sắp tới',
    owner,
    priority: selectedPriority,
    description: document.getElementById('f-desc').value.trim() || 'Chưa có mô tả.',
    condition: document.getElementById('f-cond').value.trim() || 'Chưa có điều kiện.',
    stores
  };

  if (editingIdx >= 0) {
    // EDIT MODE: preserve status/progress/colors from existing
    const existing = promos[editingIdx];
    newPromo.status        = existing.status;
    newPromo.statusLabel   = existing.statusLabel;
    newPromo.progress      = existing.progress;
    newPromo.progressColor = existing.progressColor;
    newPromo.dateNote      = existing.dateNote;
    newPromo.dateColor     = existing.dateColor;
    promos[editingIdx] = newPromo;
    showToast('✅ Đã lưu thay đổi thành công!', 'var(--accent2)');
  } else {
    promos.unshift(newPromo);
    showToast('✅ Đã thêm chương trình thành công!', 'var(--accent3)');
  }

  renderTable();
  closeModal();
  document.querySelector('.stat-card.orange .stat-value').textContent = promos.filter(p=>p.status==='s-live').length;
  document.querySelector('.stat-card.blue .stat-value').textContent   = promos.filter(p=>p.status==='s-upcoming').length;
}

function highlight(id) {
  const el = document.getElementById(id);
  el.style.borderColor = 'var(--danger)';
  el.style.boxShadow = '0 0 0 3px rgba(239,68,68,.15)';
  el.focus();
  setTimeout(() => { el.style.borderColor = ''; el.style.boxShadow = ''; }, 2000);
}

function showToast(msg, color) {
  const t = document.getElementById('toast');
  if (msg) t.textContent = msg;
  if (color) t.style.background = color;
  t.classList.add('show');
  setTimeout(() => { t.classList.remove('show'); t.textContent = '✅ Đã thêm chương trình thành công!'; t.style.background = ''; }, 3000);
}

// ===== MISC =====
function setNav(el) {
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  el.classList.add('active');
}
function filterChip(el) {
  document.querySelectorAll('.chip').forEach(c => c.classList.remove('active'));
  el.classList.add('active');
}
function toggleCheck(el) {
  el.classList.toggle('done');
  const done = document.querySelectorAll('.check-item.done').length;
  const total = document.querySelectorAll('.check-item').length;
  const pct = Math.round(done/total*100);
  document.querySelector('.stat-card.green .stat-value').textContent = pct + '%';
  document.querySelector('.stat-card.green .stat-sub').textContent = done + '/' + total + ' đầu việc xong';
}

function filterStores(query, idx) {
  const items = document.querySelectorAll('#store-list-container .store-item');
  const q = query.toLowerCase().trim();
  let found = 0;
  items.forEach(item => {
    const name = item.getAttribute('data-store-name') || '';
    if (!q || name.includes(q)) {
      item.style.display = '';
      found++;
    } else {
      item.style.display = 'none';
    }
  });
  let empty = document.getElementById('store-no-result');
  if (!found && q) {
    if (!empty) {
      empty = document.createElement('div');
      empty.id = 'store-no-result';
      empty.className = 'store-empty';
      empty.textContent = 'Không tìm thấy cửa hàng "' + query + '"';
      document.getElementById('store-list-container').after(empty);
    }
  } else if (empty) {
    empty.remove();
  }
}

// ===== STORE HELPERS =====
function renderFormStores(filter) {
  const list = document.getElementById('store-check-list');
  if (!list) return;
  const q = (filter || '').toLowerCase();
  const filtered = MASTER_STORES.filter(s =>
    s.ten.toLowerCase().includes(q) || s.ma.toLowerCase().includes(q) || s.mien.toLowerCase().includes(q)
  );
  list.innerHTML = filtered.map(s => `
    <div class="store-check-item" onclick="toggleStoreCheck(this)"
      data-store="${s.ten}" data-addr="${s.dia_chi}"
      data-lien_he="${s.lien_he}" data-mien="${s.mien}" data-icon="${s.icon}">
      <div class="sck-box"></div>
      <div style="flex:1;min-width:0;">
        <div class="sck-label">${s.icon} ${s.ten}</div>
        <div class="sck-addr">${s.ma} · ${s.mien}</div>
      </div>
    </div>
  `).join('') || '<div style="text-align:center;color:var(--muted);font-size:12px;padding:12px">Không tìm thấy cửa hàng</div>';
}

function filterFormStores(q) { renderFormStores(q); }

function addCustomStore() {
  const name = prompt('Tên cửa hàng mới:');
  if (!name || !name.trim()) return;
  const addr = prompt('Địa chỉ:') || '';
  const ma = 'CUSTOM-' + Date.now().toString().slice(-4);
  MASTER_STORES.push({ ma, ten: name.trim(), dia_chi: addr, lien_he: '', mien: 'Khác', icon: '🏪' });
  renderFormStores(document.getElementById('form-store-search')?.value || '');
}


renderTable();
</script>
</body>
</html>

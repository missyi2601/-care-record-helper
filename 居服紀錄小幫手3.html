<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
<title>居服紀錄小幫手</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700;900&display=swap" rel="stylesheet">
<style>
:root{
  --pink:#C9938A; --soft-pink:#E8C4BC; --light-pink:#F5E6E3;
  --blue:#7A9BAD; --soft-blue:#B8CFDA; --light-blue:#E3EDF3;
  --sage:#9AAE9B; --light-sage:#E8F0E8;
  --cream:#FAF3EE; --bg:#FAFAF8; --dark:#37352F; --medium:#5A5248; --gray:#9B9A97;
  --danger:#C97A6D; --radius:14px; --radius-sm:10px;
  --shadow:0 2px 10px rgba(55,53,47,0.06); --shadow-md:0 6px 20px rgba(55,53,47,0.10);
}
*{box-sizing:border-box; margin:0; padding:0;}
html,body{height:100%;}
body{
  font-family:'Noto Sans TC', sans-serif;
  background:var(--bg);
  color:var(--dark);
  -webkit-font-smoothing:antialiased;
  padding-bottom:72px;
}
button, input, select, textarea{ font-family:inherit; font-size:15px; }
button{ cursor:pointer; }
::selection{ background:var(--soft-pink); }

/* ---------- layout ---------- */
.app-header{
  position:sticky; top:0; z-index:30;
  background:var(--cream);
  border-bottom:1px solid var(--light-pink);
  padding:14px 20px;
}
.header-row{
  display:flex; align-items:center; justify-content:space-between;
  max-width:1100px; margin:0 auto; gap:12px; flex-wrap:wrap;
}
.brand{ display:flex; align-items:center; gap:10px; }
.brand-logo{
  width:38px; height:38px; border-radius:10px;
  background:linear-gradient(135deg, var(--pink), var(--blue));
  display:flex; align-items:center; justify-content:center;
  color:#fff; font-weight:900; font-size:16px; flex-shrink:0;
}
.brand-text h1{ font-size:17px; font-weight:700; color:var(--dark); }
.brand-text p{ font-size:12px; color:var(--gray); margin-top:1px; }

.header-actions{ display:flex; gap:8px; align-items:center; flex-wrap:wrap; }

.tabs{
  display:flex; gap:6px; background:var(--light-pink); padding:4px; border-radius:12px;
}
.tab-btn{
  border:none; background:transparent; padding:8px 16px; border-radius:9px;
  font-weight:700; color:var(--medium); font-size:14px; transition:.15s;
}
.tab-btn.active{ background:#fff; color:var(--pink); box-shadow:var(--shadow); }

.btn{
  border:none; border-radius:10px; padding:9px 16px; font-weight:700; font-size:14px;
  display:inline-flex; align-items:center; gap:6px; transition:.15s; white-space:nowrap;
}
.btn-primary{ background:var(--pink); color:#fff; }
.btn-primary:hover{ background:#b97e73; }
.btn-secondary{ background:#fff; color:var(--medium); border:1px solid var(--soft-pink); }
.btn-secondary:hover{ background:var(--light-pink); }
.btn-ghost{ background:transparent; color:var(--medium); }
.btn-ghost:hover{ background:var(--light-pink); }
.btn-danger{ background:transparent; color:var(--danger); border:1px solid var(--soft-pink); }
.btn-danger:hover{ background:var(--light-pink); }
.btn-sm{ padding:6px 12px; font-size:13px; border-radius:8px; }
.btn:disabled{ opacity:.5; cursor:not-allowed; }

.main{ max-width:1100px; margin:0 auto; padding:22px 20px 40px; }
.view{ display:none; }
.view.active{ display:block; animation:fadeIn .2s ease; }
@keyframes fadeIn{ from{opacity:0; transform:translateY(4px);} to{opacity:1; transform:translateY(0);} }

.section-title{ font-size:15px; font-weight:700; color:var(--dark); margin:26px 0 12px; }
.section-title:first-child{ margin-top:0; }

/* ---------- dashboard cards ---------- */
.cards-grid{
  display:grid; grid-template-columns:repeat(auto-fit, minmax(200px,1fr)); gap:14px;
}
.card{
  background:#fff; border-radius:var(--radius); padding:18px; box-shadow:var(--shadow);
  border:1px solid var(--light-pink);
}
.card-icon{
  width:34px; height:34px; border-radius:9px; display:flex; align-items:center; justify-content:center;
  font-size:16px; margin-bottom:10px;
}
.card-label{ font-size:12.5px; color:var(--gray); font-weight:500; margin-bottom:4px; }
.card-value{ font-size:26px; font-weight:900; color:var(--dark); line-height:1.2; }
.card-sub{ font-size:12px; color:var(--gray); margin-top:4px; }
.card.pink .card-icon{ background:var(--light-pink); color:var(--pink); }
.card.blue .card-icon{ background:var(--light-blue); color:var(--blue); }
.card.sage .card-icon{ background:var(--light-sage); color:var(--sage); }
.card.warn .card-icon{ background:var(--light-pink); color:var(--danger); }
.card-clickable{ cursor:pointer; transition:.15s; }
.card-clickable:hover{ box-shadow:var(--shadow-md); transform:translateY(-1px); }

.panel{
  background:#fff; border-radius:var(--radius); padding:18px 20px; box-shadow:var(--shadow);
  border:1px solid var(--light-pink);
}
.mini-list{ display:flex; flex-direction:column; gap:2px; }
.mini-row{
  display:flex; align-items:center; justify-content:space-between; padding:11px 4px;
  border-bottom:1px solid var(--light-pink); gap:10px;
}
.mini-row:last-child{ border-bottom:none; }
.mini-row-left{ display:flex; flex-direction:column; gap:2px; min-width:0; }
.mini-row-code{ font-weight:700; font-size:14px; }
.mini-row-meta{ font-size:12px; color:var(--gray); }
.empty-hint{ color:var(--gray); font-size:13.5px; padding:20px 4px; text-align:center; }

/* ---------- chips / tags ---------- */
.tag{
  display:inline-flex; align-items:center; gap:4px; font-size:12px; font-weight:700;
  padding:3px 9px; border-radius:99px; white-space:nowrap;
}
.tag-blue{ background:var(--light-blue); color:var(--blue); }
.tag-sage{ background:var(--light-sage); color:var(--sage); }
.tag-pink{ background:var(--light-pink); color:var(--pink); }
.tag-gray{ background:#F1F0EE; color:var(--medium); }
.tag-wrap{ display:flex; flex-wrap:wrap; gap:5px; }

/* ---------- list / filters ---------- */
.toolbar{
  display:flex; gap:10px; flex-wrap:wrap; align-items:center; margin-bottom:16px;
}
.search-box{
  flex:1 1 220px; position:relative;
}
.search-box input{
  width:100%; padding:10px 14px 10px 36px; border-radius:10px; border:1px solid var(--soft-pink);
  background:#fff; outline:none;
}
.search-box input:focus{ border-color:var(--pink); }
.search-box::before{
  content:"⌕"; position:absolute; left:12px; top:50%; transform:translateY(-50%);
  color:var(--gray); font-size:16px; font-weight:700;
}
.filter-select{
  padding:10px 12px; border-radius:10px; border:1px solid var(--soft-pink); background:#fff; color:var(--medium);
}

.case-table{ width:100%; border-collapse:collapse; }
.case-table thead th{
  text-align:left; font-size:12.5px; color:var(--gray); font-weight:700; padding:0 12px 10px;
  border-bottom:1px solid var(--light-pink);
}
.case-table tbody td{ padding:14px 12px; border-bottom:1px solid var(--light-pink); vertical-align:top; }
.case-table tbody tr:last-child td{ border-bottom:none; }
.case-table tbody tr:hover{ background:var(--light-pink); }
.code-cell{ font-weight:700; font-size:14.5px; }
.date-cell{ font-size:12.5px; color:var(--gray); white-space:nowrap; }
.actions-cell{ display:flex; gap:6px; flex-wrap:wrap; }

.desktop-only{ display:table; }
.mobile-cards{ display:none; flex-direction:column; gap:12px; }
.case-card{
  background:#fff; border:1px solid var(--light-pink); border-radius:var(--radius-sm);
  padding:14px; box-shadow:var(--shadow);
}
.case-card-top{ display:flex; justify-content:space-between; align-items:flex-start; gap:8px; margin-bottom:8px; }
.case-card-actions{ display:flex; gap:6px; margin-top:10px; flex-wrap:wrap; }

/* ---------- form overlay ---------- */
.overlay{
  position:fixed; inset:0; background:rgba(55,53,47,0.35); z-index:100;
  display:none; align-items:flex-start; justify-content:center; padding:26px 16px; overflow-y:auto;
}
.overlay.active{ display:flex; }
.form-panel{
  background:#fff; border-radius:18px; width:100%; max-width:640px; box-shadow:var(--shadow-md);
  display:flex; flex-direction:column; max-height:calc(100vh - 52px);
}
.form-panel.wide{ max-width:760px; }
.form-header{
  display:flex; align-items:center; justify-content:space-between; padding:18px 22px;
  border-bottom:1px solid var(--light-pink); flex-shrink:0;
}
.form-header h2{ font-size:16.5px; font-weight:700; }
.form-header .sub{ font-size:12px; color:var(--gray); font-weight:500; margin-top:2px; }
.close-x{
  width:30px; height:30px; border-radius:9px; border:none; background:var(--light-pink);
  color:var(--medium); font-size:15px; font-weight:700; flex-shrink:0;
}
.form-body{ padding:20px 22px; overflow-y:auto; flex:1; }
.form-footer{
  padding:14px 22px; border-top:1px solid var(--light-pink); display:flex; justify-content:space-between; align-items:center; gap:10px; flex-shrink:0; flex-wrap:wrap;
}
.form-footer-right{ display:flex; gap:10px; }

.field{ margin-bottom:18px; }
.field label{ display:block; font-size:13px; font-weight:700; color:var(--medium); margin-bottom:7px; }
.field .hint{ font-size:12px; color:var(--gray); font-weight:400; margin-top:5px; }
.field input[type=text], .field input[type=date], .field textarea{
  width:100%; padding:10px 13px; border-radius:10px; border:1px solid var(--soft-pink);
  background:#FDFBFA; outline:none; color:var(--dark);
}
.field input:focus, .field textarea:focus{ border-color:var(--pink); background:#fff; }
.field textarea{ resize:vertical; line-height:1.6; }
.error-text{ color:var(--danger); font-size:12px; margin-top:5px; font-weight:700; display:none; }
.field.error input{ border-color:var(--danger); }
.field.error .error-text{ display:block; }

.chip-picker{ display:flex; flex-wrap:wrap; gap:8px; }
.chip-option{
  padding:7px 14px; border-radius:99px; border:1px solid var(--soft-pink); background:#fff;
  font-size:13px; font-weight:700; color:var(--medium); transition:.15s;
}
.chip-option.selected{ background:var(--pink); border-color:var(--pink); color:#fff; }
.chip-add-row{ display:flex; gap:8px; margin-top:10px; }
.chip-add-row input{ flex:1; padding:8px 12px; border-radius:9px; border:1px solid var(--soft-pink); }

.service-list{ display:flex; flex-direction:column; gap:8px; max-height:280px; overflow-y:auto; padding:2px; border:1px solid var(--light-pink); border-radius:12px; }
.service-item{ padding:11px 12px; border-radius:10px; transition:.15s; }
.service-item:hover{ background:var(--light-pink); }
.service-item.checked{ background:var(--light-blue); }
.service-item-head{ display:flex; align-items:flex-start; gap:10px; cursor:pointer; }
.service-item-head input{ margin-top:3px; accent-color:var(--pink); width:16px; height:16px; flex-shrink:0; }
.service-item-name{ font-weight:700; font-size:13.5px; }
.service-item-code{ color:var(--blue); font-weight:900; }
.service-item-desc{ font-size:12px; color:var(--gray); margin-top:2px; line-height:1.5; }
.service-item-pay{ font-size:12px; color:var(--sage); font-weight:700; margin-top:3px; }
.service-item-count{
  display:flex; align-items:center; gap:6px; margin-top:6px;
}
.service-item-count label{ font-size:12px; color:var(--medium); font-weight:700; margin:0; }
.service-item-count input{
  width:60px; padding:5px 8px; border-radius:8px; border:1px solid var(--soft-pink); background:#fff; text-align:center;
}
.pay-pill{ display:inline-flex; align-items:center; gap:4px; font-size:12px; font-weight:700; padding:3px 9px; border-radius:99px; background:var(--light-sage); color:var(--sage); white-space:nowrap; }

.note-toolbar{ display:flex; justify-content:space-between; align-items:center; margin-bottom:7px; gap:8px; }
.note-toolbar label{ margin-bottom:0; }

/* ---------- section box (六大段落) ---------- */
.record-section{
  border:1px solid var(--light-pink); border-radius:12px; padding:14px 16px; margin-bottom:14px; background:#FDFBFA;
}
.record-section-title{ font-weight:700; font-size:13.5px; color:var(--pink); margin-bottom:10px; display:flex; align-items:center; gap:6px; }
.record-section-num{
  width:20px; height:20px; border-radius:50%; background:var(--soft-pink); color:#fff; font-size:11px;
  display:flex; align-items:center; justify-content:center; flex-shrink:0;
}
.mini-field{ margin-bottom:10px; }
.mini-field:last-child{ margin-bottom:0; }
.mini-field label{ display:block; font-size:12px; font-weight:700; color:var(--medium); margin-bottom:5px; }
.mini-field input[type=text], .mini-field textarea{
  width:100%; padding:8px 11px; border-radius:9px; border:1px solid var(--soft-pink); background:#fff; outline:none;
}
.mini-field textarea{ resize:vertical; line-height:1.6; }
.event-toggle{ display:flex; align-items:center; gap:8px; margin-bottom:10px; }
.event-toggle input{ width:16px; height:16px; accent-color:var(--pink); }
.event-toggle label{ font-size:13px; font-weight:700; color:var(--medium); margin:0; }

.preview-box{
  background:var(--light-blue); border-radius:12px; padding:16px; font-size:13px; line-height:1.9;
  white-space:pre-wrap; color:var(--dark); max-height:320px; overflow-y:auto; border:1px solid var(--soft-blue);
}

/* ---------- records timeline ---------- */
.record-card{
  background:#fff; border:1px solid var(--light-pink); border-radius:12px; padding:14px 16px; margin-bottom:12px; box-shadow:var(--shadow);
}
.record-card-head{ display:flex; justify-content:space-between; align-items:center; gap:8px; margin-bottom:8px; flex-wrap:wrap; }
.record-card-date{ font-weight:700; font-size:14px; }
.record-card-body{ font-size:13px; color:var(--medium); white-space:pre-wrap; line-height:1.8; max-height:0; overflow:hidden; transition:max-height .25s ease; }
.record-card-body.expanded{ max-height:2000px; margin-top:8px; padding-top:10px; border-top:1px dashed var(--light-pink); }
.record-card-actions{ display:flex; gap:6px; flex-wrap:wrap; }

/* ---------- month income detail ---------- */
.month-case-block{
  background:#fff; border:1px solid var(--light-pink); border-radius:12px; padding:14px 16px; margin-bottom:12px; box-shadow:var(--shadow);
}
.month-case-head{ display:flex; justify-content:space-between; align-items:center; margin-bottom:10px; flex-wrap:wrap; gap:8px; }
.month-case-code{ font-weight:700; font-size:15px; }
.month-item-row{
  display:flex; justify-content:space-between; align-items:center; padding:8px 0; border-bottom:1px solid var(--light-pink); gap:10px; font-size:13px;
}
.month-item-row:last-of-type{ border-bottom:none; }
.month-item-name{ color:var(--dark); font-weight:500; }
.month-item-meta{ color:var(--gray); font-size:12px; margin-top:2px; }
.month-item-subtotal{ font-weight:700; color:var(--sage); white-space:nowrap; }
.month-case-total{
  display:flex; justify-content:space-between; margin-top:10px; padding-top:10px; border-top:1px dashed var(--soft-pink);
  font-weight:700; font-size:13.5px;
}

/* ---------- top services ranking ---------- */
.top-rank-row{
  display:flex; align-items:center; gap:12px; padding:14px 4px; border-bottom:1px solid var(--light-pink);
}
.top-rank-row:last-child{ border-bottom:none; }
.top-rank-badge{
  width:34px; height:34px; border-radius:50%; display:flex; align-items:center; justify-content:center;
  font-weight:900; font-size:15px; flex-shrink:0; color:#fff;
}
.top-rank-badge.rank1{ background:linear-gradient(135deg,#E8B84B,#D9A22E); }
.top-rank-badge.rank2{ background:linear-gradient(135deg,#B8C1CC,#9AA5B1); }
.top-rank-badge.rank3{ background:linear-gradient(135deg,#CD8D5C,#B87342); }
.top-rank-info{ flex:1; min-width:0; }
.top-rank-name{ font-weight:700; font-size:14.5px; color:var(--dark); }
.top-rank-meta{ font-size:12px; color:var(--gray); margin-top:2px; }
.top-rank-count{ font-weight:900; font-size:18px; color:var(--blue); white-space:nowrap; }

/* ---------- import/export menu ---------- */
.menu-wrap{ position:relative; }
.menu-dropdown{
  position:absolute; right:0; top:calc(100% + 6px); background:#fff; border:1px solid var(--light-pink);
  border-radius:12px; box-shadow:var(--shadow-md); width:200px; padding:6px; display:none; z-index:40;
}
.menu-dropdown.active{ display:block; }
.menu-item{
  width:100%; text-align:left; padding:9px 12px; border-radius:8px; background:transparent; border:none;
  font-size:13.5px; color:var(--medium); font-weight:500;
}
.menu-item:hover{ background:var(--light-pink); }
input[type=file]{ display:none; }

.toast{
  position:fixed; bottom:24px; left:50%; transform:translateX(-50%) translateY(20px);
  background:var(--dark); color:#fff; padding:11px 20px; border-radius:99px; font-size:13.5px; font-weight:700;
  box-shadow:var(--shadow-md); z-index:200; opacity:0; pointer-events:none; transition:.25s;
}
.toast.show{ opacity:1; transform:translateX(-50%) translateY(0); }

/* ---------- initial load overlay ---------- */
.app-loading{
  position:fixed; inset:0; background:var(--bg); z-index:500;
  display:flex; align-items:center; justify-content:center; flex-direction:column; gap:12px;
}
.app-loading.hidden{ display:none; }
.app-loading-spinner{
  width:34px; height:34px; border-radius:50%; border:3px solid var(--light-pink); border-top-color:var(--pink);
  animation:appLoadingSpin .8s linear infinite;
}
@keyframes appLoadingSpin{ to{ transform:rotate(360deg); } }
.app-loading-text{ font-size:13.5px; color:var(--gray); font-weight:700; }

.fab{
  position:fixed; bottom:22px; right:22px; width:54px; height:54px; border-radius:50%;
  background:var(--pink); color:#fff; font-size:26px; font-weight:700; border:none;
  box-shadow:var(--shadow-md); z-index:20; display:none; align-items:center; justify-content:center;
}

.confirm-overlay{
  position:fixed; inset:0; background:rgba(55,53,47,0.4); z-index:150; display:none;
  align-items:center; justify-content:center; padding:20px;
}
.confirm-overlay.active{ display:flex; }
.confirm-box{ background:#fff; border-radius:16px; padding:22px; width:100%; max-width:340px; box-shadow:var(--shadow-md); text-align:center; }
.confirm-box p{ font-size:14.5px; color:var(--dark); margin:6px 0 18px; line-height:1.6; }
.confirm-box .confirm-title{ font-weight:700; font-size:16px; }
.confirm-actions{ display:flex; gap:10px; }
.confirm-actions .btn{ flex:1; justify-content:center; }

/* ---------- responsive ---------- */
@media (max-width:860px){
  .cards-grid{ grid-template-columns:repeat(2,1fr); }
}
@media (max-width:720px){
  .desktop-only{ display:none; }
  .mobile-cards{ display:flex; }
  .fab{ display:flex; }
  .header-actions .btn-primary{ display:none; }
  .brand-text p{ display:none; }
}
@media (max-width:480px){
  .cards-grid{ grid-template-columns:1fr 1fr; gap:10px; }
  .card{ padding:14px; }
  .card-value{ font-size:22px; }
  .main{ padding:16px 14px 40px; }
}
</style>
</head>
<body>

<div class="app-loading" id="appLoading">
  <div class="app-loading-spinner"></div>
  <div class="app-loading-text">載入中，請稍候…</div>
</div>

<header class="app-header">
  <div class="header-row">
    <div class="brand">
      <div class="brand-logo">居</div>
      <div class="brand-text">
        <h1>居服紀錄小幫手</h1>
        <p>個案管理與每週紀錄自動帶入</p>
      </div>
    </div>
    <div class="header-actions">
      <div class="tabs">
        <button class="tab-btn active" data-tab="dashboard">儀表板</button>
        <button class="tab-btn" data-tab="list">個案清單</button>
      </div>
      <button class="btn btn-primary" id="btnAddTop">＋ 新增案件</button>
      <div class="menu-wrap">
        <button class="btn btn-secondary" id="btnMenu">⋯ 更多</button>
        <div class="menu-dropdown" id="menuDropdown">
          <button class="menu-item" id="btnExport">⬇ 匯出備份 (JSON)</button>
          <button class="menu-item" id="btnImportTrigger">⬆ 匯入備份</button>
          <input type="file" id="fileImport" accept="application/json">
        </div>
      </div>
    </div>
  </div>
</header>

<main class="main">

  <!-- ================= DASHBOARD ================= -->
  <section class="view active" id="view-dashboard">
    <div class="section-title">總覽</div>
    <div class="cards-grid">
      <div class="card pink">
        <div class="card-icon">👥</div>
        <div class="card-label">總案件數</div>
        <div class="card-value" id="statTotal">0</div>
        <div class="card-sub">目前建檔中的個案</div>
      </div>
      <div class="card sage">
        <div class="card-icon">✓</div>
        <div class="card-label">本週已寫紀錄</div>
        <div class="card-value" id="statWeek">0</div>
        <div class="card-sub">本週（週日起）已新增紀錄</div>
      </div>
      <div class="card warn">
        <div class="card-icon">⏰</div>
        <div class="card-label">逾期未寫紀錄</div>
        <div class="card-value" id="statOverdue">0</div>
        <div class="card-sub">本週（週日起）尚未新增紀錄</div>
      </div>
      <div class="card blue card-clickable" id="cardTopService">
        <div class="card-icon">★</div>
        <div class="card-label">最常用服務項目</div>
        <div class="card-value" id="statTopService" style="font-size:19px;">—</div>
        <div class="card-sub" id="statTopServiceSub">尚無資料</div>
      </div>
      <div class="card sage card-clickable" id="cardMonthPay">
        <div class="card-icon">💰</div>
        <div class="card-label">本月預估收入</div>
        <div class="card-value" id="statMonthPay">NT$0</div>
        <div class="card-sub">依本月紀錄・給付×55% 估算・點我看明細 →</div>
      </div>
    </div>

    <div class="section-title">待更新提醒</div>
    <div class="panel">
      <div class="mini-list" id="overdueList">
        <div class="empty-hint">目前沒有逾期未更新的案件 🌿</div>
      </div>
    </div>

    <div class="section-title">最近紀錄</div>
    <div class="panel">
      <div class="mini-list" id="recentList">
        <div class="empty-hint">尚未建立任何案件，點右上角「新增案件」開始使用</div>
      </div>
    </div>
  </section>

  <!-- ================= LIST ================= -->
  <section class="view" id="view-list">
    <div class="toolbar">
      <div class="search-box">
        <input type="text" id="searchInput" placeholder="搜尋個案代號…">
      </div>
      <select class="filter-select" id="filterDisease"><option value="">全部慢性病</option></select>
      <select class="filter-select" id="filterService"><option value="">全部服務項目</option></select>
      <select class="filter-select" id="filterStatus">
        <option value="">全部狀態</option>
        <option value="ok">本週已寫紀錄</option>
        <option value="overdue">逾期未寫紀錄</option>
      </select>
    </div>

    <table class="case-table desktop-only" id="caseTable">
      <thead>
        <tr>
          <th>個案代號</th>
          <th>慢性病</th>
          <th>常用服務預估收入</th>
          <th>紀錄筆數</th>
          <th>最後紀錄</th>
          <th>操作</th>
        </tr>
      </thead>
      <tbody id="caseTableBody"></tbody>
    </table>

    <div class="mobile-cards" id="caseCards"></div>
    <div class="empty-hint" id="listEmptyHint" style="display:none;">找不到符合條件的案件</div>
  </section>

</main>

<button class="fab" id="btnAddFab">＋</button>

<!-- ================= CASE PROFILE FORM ================= -->
<div class="overlay" id="formOverlay">
  <div class="form-panel">
    <div class="form-header">
      <div><h2 id="formTitle">新增案件</h2><div class="sub">個案基本資料，不常變動的部分</div></div>
      <button class="close-x" id="btnCloseForm">✕</button>
    </div>
    <div class="form-body">
      <div class="field" id="fieldCode">
        <label>個案代號 *</label>
        <input type="text" id="inputCode" placeholder="例如：A102 或 王OO">
        <div class="error-text">請輸入個案代號，且不可與現有案件重複</div>
      </div>

      <div class="field">
        <label>慢性病</label>
        <div class="chip-picker" id="diseasePicker"></div>
        <div class="chip-add-row">
          <input type="text" id="diseaseCustomInput" placeholder="自訂新增慢性病，按 Enter 加入">
        </div>
      </div>

      <div class="field">
        <label>注意事項</label>
        <div class="chip-picker" id="attentionPicker"></div>
        <div class="chip-add-row">
          <input type="text" id="attentionCustomInput" placeholder="自訂新增注意事項，按 Enter 加入">
        </div>
      </div>

      <div class="field">
        <label>服務項目（本案件配合的服務項目，寫每週紀錄時會依此自動帶入內容，不用每次重選）</label>
        <div class="service-list" id="serviceList"></div>
        <div class="hint" id="serviceListPayTotal" style="margin-top:8px; font-weight:700; color:var(--sage);"></div>
      </div>

      <div class="field">
        <label>備註（選填）</label>
        <textarea id="inputRemark" rows="2" placeholder="其他想補充的事項"></textarea>
      </div>
    </div>
    <div class="form-footer">
      <div></div>
      <div class="form-footer-right">
        <button class="btn btn-secondary" id="btnCancelForm">取消</button>
        <button class="btn btn-primary" id="btnSaveForm">儲存案件</button>
      </div>
    </div>
  </div>
</div>

<!-- ================= RECORDS (歷史紀錄) OVERLAY ================= -->
<div class="overlay" id="recordsOverlay">
  <div class="form-panel wide">
    <div class="form-header">
      <div><h2 id="recordsCaseTitle">個案紀錄</h2><div class="sub" id="recordsCaseSub"></div></div>
      <button class="close-x" id="btnCloseRecords">✕</button>
    </div>
    <div class="form-body">
      <button class="btn btn-primary" id="btnAddRecord" style="margin-bottom:16px;">＋ 新增本週紀錄</button>
      <div id="recordsTimeline"></div>
    </div>
    <div class="form-footer">
      <div></div>
      <div class="form-footer-right">
        <button class="btn btn-secondary" id="btnCloseRecords2">關閉</button>
      </div>
    </div>
  </div>
</div>

<!-- ================= WEEKLY RECORD FORM (六大段落) ================= -->
<div class="overlay" id="recordFormOverlay">
  <div class="form-panel wide">
    <div class="form-header">
      <div><h2 id="recordFormTitle">新增本週紀錄</h2><div class="sub" id="recordFormSub"></div></div>
      <button class="close-x" id="btnCloseRecordForm">✕</button>
    </div>
    <div class="form-body">

      <div class="field">
        <label>紀錄日期</label>
        <input type="date" id="inputRecordDate">
        <div class="hint" id="recordWeekLabel" style="font-weight:700; color:var(--sage);"></div>
      </div>

      <div class="field">
        <label>本週服務項目與次數（依實際服務調整，會自動帶入「五、服務過程與溝通紀錄」並計算薪資）</label>
        <div class="service-list" id="recServiceList"></div>
        <div class="hint" id="recServicePayTotal" style="margin-top:8px; font-weight:700; color:var(--sage);"></div>
        <button type="button" class="btn btn-ghost btn-sm" id="btnEditCaseServices" style="margin-top:8px;">✎ 編輯本案件常用服務項目（新紀錄的預設值）</button>
      </div>

      <div class="section-title" style="margin-top:22px;">紀錄內容（已自動帶入草稿，請依實際狀況調整文字）</div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">1</span>認知功能與身體狀況變化</div>
        <div class="mini-field"><label>狀況</label><input type="text" id="s1_label"></div>
        <div class="mini-field"><label>說明</label><textarea id="s1_desc" rows="2"></textarea></div>
      </div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">2</span>精神情緒及互動情形</div>
        <div class="mini-field"><label>狀況</label><input type="text" id="s2_label"></div>
        <div class="mini-field"><label>說明</label><textarea id="s2_desc" rows="2"></textarea></div>
      </div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">3</span>生活作息與基本生理狀況</div>
        <div class="mini-field"><label>狀況</label><input type="text" id="s3_label"></div>
        <div class="mini-field"><label>說明</label><textarea id="s3_desc" rows="2"></textarea></div>
      </div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">4</span>特殊事件及異常狀況</div>
        <div class="event-toggle">
          <input type="checkbox" id="s4_hasEvent">
          <label for="s4_hasEvent">本次有特殊事件或異常狀況</label>
        </div>
        <div class="mini-field"><label>事件內容</label><textarea id="s4_event" rows="2"></textarea></div>
        <div class="mini-field"><label>處理情形</label><textarea id="s4_handling" rows="2"></textarea></div>
      </div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">5</span>服務過程與溝通紀錄</div>
        <div class="note-toolbar"><span></span><button class="btn btn-ghost btn-sm" id="btnRegenS5">↻ 依服務項目重新帶入</button></div>
        <div class="mini-field"><textarea id="s5_desc" rows="4"></textarea></div>
      </div>

      <div class="record-section">
        <div class="record-section-title"><span class="record-section-num">6</span>整體評估與後續建議</div>
        <div class="mini-field"><textarea id="s6_desc" rows="3"></textarea></div>
      </div>

      <div class="field">
        <label>小提醒（依需要自行勾選，會附加在紀錄最後）</label>
        <div class="chip-picker" id="reminderPicker"></div>
        <div class="chip-add-row">
          <input type="text" id="reminderCustomInput" placeholder="自訂新增小提醒，按 Enter 加入">
        </div>
      </div>

      <div class="field">
        <div class="note-toolbar"><label>預覽（將依此格式複製）</label><button class="btn btn-ghost btn-sm" id="btnResetDefaults">↻ 全部重設為預設文字</button></div>
        <div class="preview-box" id="recordPreview"></div>
      </div>

    </div>
    <div class="form-footer">
      <div></div>
      <div class="form-footer-right">
        <button class="btn btn-secondary" id="btnCancelRecordForm">取消</button>
        <button class="btn btn-primary" id="btnSaveRecordForm">儲存紀錄</button>
      </div>
    </div>
  </div>
</div>

<!-- ================= MONTH INCOME DETAIL OVERLAY ================= -->
<div class="overlay" id="monthDetailOverlay">
  <div class="form-panel wide">
    <div class="form-header">
      <div><h2 id="monthDetailTitle">本月預估收入明細</h2><div class="sub" id="monthDetailSub"></div></div>
      <button class="close-x" id="btnCloseMonthDetail">✕</button>
    </div>
    <div class="form-body">
      <div class="panel" style="margin-bottom:16px; display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:8px;">
        <span style="font-weight:700; color:var(--dark);">本月總計</span>
        <span class="pay-pill" id="monthDetailGrandTotal" style="font-size:15px; padding:6px 14px;">NT$0</span>
      </div>
      <div id="monthDetailList"></div>
    </div>
    <div class="form-footer">
      <div></div>
      <div class="form-footer-right">
        <button class="btn btn-secondary" id="btnCloseMonthDetail2">關閉</button>
      </div>
    </div>
  </div>
</div>

<!-- ================= TOP SERVICES DETAIL OVERLAY ================= -->
<div class="overlay" id="topServicesOverlay">
  <div class="form-panel">
    <div class="form-header">
      <div><h2>最常用服務項目 TOP 3</h2><div class="sub">依所有紀錄的實際執行次數統計</div></div>
      <button class="close-x" id="btnCloseTopServices">✕</button>
    </div>
    <div class="form-body">
      <div id="topServicesList"></div>
    </div>
    <div class="form-footer">
      <div></div>
      <div class="form-footer-right">
        <button class="btn btn-secondary" id="btnCloseTopServices2">關閉</button>
      </div>
    </div>
  </div>
</div>

<!-- ================= CONFIRM DIALOG ================= -->
<div class="confirm-overlay" id="confirmOverlay">
  <div class="confirm-box">
    <div class="confirm-title" id="confirmTitle">確定要刪除嗎？</div>
    <p id="confirmMsg">此動作無法復原。</p>
    <div class="confirm-actions">
      <button class="btn btn-secondary" id="confirmCancel">取消</button>
      <button class="btn btn-danger" id="confirmOk" style="background:var(--pink); color:#fff; border:none;">確定</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ========================================================
   1. 資料常數：BA 服務項目範本 / 慢性病預設 / 注意事項預設 / 小提醒預設
   ======================================================== */
var BA_ITEMS = [
  {code:"BA01", name:"基本身體清潔", desc:"梳頭修面、穿脫衣服、床上擦澡（視需要含床上洗頭、排泄物清理）", text:"協助個案完成基本身體清潔，包括梳頭修面、穿脫衣服、床上擦澡。", price:260},
  {code:"BA02", name:"基本日常照顧", desc:"翻身、移位、上下床、刷牙洗臉、如廁、更換尿片、整理床鋪等", text:"協助個案基本日常生活照顧，包括翻身、移位、上下床、刷牙洗臉、穿脫衣服、如廁、更換尿片、整理床鋪等。", price:195},
  {code:"BA03", name:"測量生命徵象", desc:"測量血壓、體溫、脈搏、呼吸並記錄，異常時轉知家屬及照管中心", text:"測量個案血壓、體溫、脈搏及呼吸並記錄數值，如有異常已轉知家屬及照顧管理師。", price:35},
  {code:"BA04", name:"協助進食或管灌餵食", desc:"進食環境準備、加熱飯菜、協助餵食或管灌、觀察進食量及反應", text:"協助準備進食環境並加熱飯菜，協助個案進食（或管灌餵食），觀察進食量及反應。", price:130},
  {code:"BA05", name:"餐食照顧", desc:"在案家備餐（含管灌飲食）及善後清潔", text:"為個案準備當日餐食（或管灌飲食），並完成備餐後之用具、餐具清潔善後。", price:310},
  {code:"BA07", name:"協助沐浴及洗頭", desc:"引導至浴間、穿脫衣服、全身淋浴或盆浴、洗頭、浴間事前準備及事後清理", text:"協助個案至浴間沐浴及洗頭，包含穿脫衣服、全身淋浴、排泄物清理，並完成浴間事前準備與事後清理。", price:325},
  {code:"BA08", name:"足部照護", desc:"評估趾甲及足部皮膚、修剪趾甲、處理繭處、足部按摩保養", text:"評估個案趾甲及足部皮膚狀況，修剪趾（指）甲、處理足部繭處，並進行足部按摩保養。", price:500},
  {code:"BA09", name:"到宅沐浴車服務-第1型", desc:"專用車輛攜行動浴槽到宅，全身式沐浴", text:"使用到宅沐浴車為個案進行全身式沐浴，包含架設沐浴裝置、身體清潔、穿換衣服及移位。", price:2200},
  {code:"BA09a", name:"到宅沐浴車服務-第2型", desc:"適用留置管路/呼吸器/傷口個案，含護理人員評估護理", text:"使用到宅沐浴車為個案進行全身式沐浴，並由護理人員完成沐浴前後生命徵象、身體及傷口評估與護理指導。", price:2500},
  {code:"BA10", name:"翻身拍背", desc:"扣背、震顫、翻身及相關照顧指導", text:"協助個案翻身拍背，執行扣背及震顫，並依指引提供照顧指導。", price:155},
  {code:"BA11", name:"肢體關節活動", desc:"上肢下肢被動運動，或督促主動運動、站立練習", text:"協助個案進行上肢、下肢關節被動運動，或督促個案進行主動運動及站立練習。", price:195},
  {code:"BA12", name:"協助上(下)樓梯", desc:"協助上下樓梯或輪椅搬運上下樓梯", text:"協助個案上下樓梯（含輪椅搬運），並注意移位安全。", price:130},
  {code:"BA13", name:"陪同外出", desc:"外出工具安排、陪同外出並注意安全（30分鐘/組）", text:"陪同個案外出（如購物、社交活動、辦理事務、散步等），並注意外出安全。", price:195},
  {code:"BA14", name:"陪同就醫", desc:"協助掛號、陪同就診、聽取及轉知醫囑（1.5小時/組）", text:"協助個案掛號（含預約），陪同就診，並聽取及轉知醫囑與注意事項。", price:685},
  {code:"BA15-1", name:"家務協助(自用)", desc:"居家生活空間清理、衣物洗滌晾曬、簡單縫補（30分鐘/組）", text:"協助個案居家生活空間清理或洗滌、衣物洗滌晾曬及簡單縫補等家事服務。", price:195},
  {code:"BA15-2", name:"家務協助(共用)", desc:"與家人共用區域之清理、衣物洗滌等（30分鐘/組）", text:"協助個案與家人共用生活空間之清理或洗滌、衣物洗滌晾曬等家事服務。", price:195},
  {code:"BA16-1", name:"代購代領代送(自用)", desc:"代購生活用品、代領補助品、代送物品等", text:"協助個案代購生活用品、代領補助品或代送物品，並完成清點歸位及記帳。", price:130},
  {code:"BA16-2", name:"代購代領代送(共用)", desc:"代購餐食、食材、藥品等物品", text:"協助個案代購餐食、食材或藥品等物品，並完成清點歸位及記帳。", price:130},
  {code:"BA17a", name:"人工氣道管內分泌物抽吸", desc:"協助個案清除人工氣道（氣切）內分泌物", text:"協助個案清除人工氣道（氣切）內分泌物抽吸。", price:75},
  {code:"BA17b", name:"口鼻抽吸", desc:"協助個案口腔或鼻腔分泌物抽吸", text:"協助個案口腔或鼻腔分泌物抽吸。", price:65},
  {code:"BA17c", name:"管路清潔", desc:"尿管、鼻胃管等管路清潔", text:"協助個案尿管、鼻胃管等管路清潔。", price:50},
  {code:"BA17d", name:"甘油球通便、血糖機驗血糖", desc:"甘油球通便，或使用血糖機驗血糖", text:"協助個案甘油球通便，或使用血糖機為個案驗血糖。", price:50},
  {code:"BA17e", name:"依指示置入藥盒", desc:"依藥袋指示為個案分裝藥盒", text:"依藥袋指示為個案分裝藥盒。", price:50},
  {code:"BA18", name:"安全看視", desc:"陪伴、支持、看視安全，限心智障礙者使用（30分鐘/組）", text:"至個案住所陪伴看視，注意安全及異常狀況，並協助日常生活參與。", price:200},
  {code:"BA20", name:"陪伴服務", desc:"陪伴看視、日常生活參與、讀報或書信（30分鐘/組）", text:"陪伴個案看視及日常生活參與，並協助閱讀書信或新聞。", price:175},
  {code:"BA22", name:"巡視服務", desc:"上午6點至下午6點至案家探視，簡易協助，至少3次", text:"於當日多次至個案住所巡視，並進行簡易協助，注意個案安全狀況。", price:130},
  {code:"BA23", name:"協助洗頭", desc:"引導至浴間、洗頭、身體部位清潔、環境整理", text:"協助個案移位至浴間，完成洗頭及弄濕弄髒部位之清潔，並整理環境。", price:200},
  {code:"BA24", name:"協助排泄", desc:"協助大小便、尿袋更換、造廔袋清理、排泄物觀察處理", text:"協助個案如廁排泄，包括尿袋更換、造廔袋清理及排泄物觀察處理。", price:220},
  {code:"GA09", name:"居家喘息服務", desc:"受過訓練之照服員到宅提供身體照顧服務，如有陪同就醫需求可加計BA14；以2小時為1給付單位，單日上限10小時", text:"依居家喘息服務組合，協助個案如廁、沐浴、穿換衣服、口腔清潔、進食、服藥、翻身、拍背、簡單被動式肢體關節活動、上下床、陪同運動及使用日常生活輔助器具等服務。", price:770},
  {code:"AA09", name:"例假日服務", desc:"於週六、週日或國定假日提供照顧及專業服務時加計，1日為1給付單位，不扣個人額度（同日不得與AA08晚間服務同時申請）", text:"因本次服務於例假日（週六、週日或國定假日）提供，依規定加計例假日服務。", price:770}
];

var PAY_RATE = 0.55;
/* 金額一律只保留到小數點後兩位（避免浮點數誤差），顯示時再用 formatMoney 整理 */
function payOf(price){ return Math.round((price||0) * PAY_RATE * 100) / 100; }
function formatMoney(n){
  var rounded = Math.round((n||0) * 100) / 100;
  if(Math.abs(rounded - Math.round(rounded)) < 1e-9) return String(Math.round(rounded));
  return rounded.toFixed(2);
}

var DEFAULT_DISEASES = ["高血壓","糖尿病","心臟病","中風","失智症","巴金森氏症","慢性腎臟病","慢性阻塞性肺病(COPD)","關節炎","骨質疏鬆","憂鬱症"];
var DEFAULT_ATTENTIONS = ["活動自如","坐輪椅","清淡飲食","多喝水"];
var DEFAULT_REMINDERS = ["低油低鹽、定時定量","少量多餐並補充水分","依醫囑","多喝水","預防跌倒","有寫安全（防滑、水溫）","有寫皮膚觀察","有寫是否全程或部分協助","有寫更換衣物"];

var DEFAULT_SECTION_TEXT = {
  s1_label: "無明顯改變",
  s1_desc: "個案意識清楚，可正常應答，活動狀況與平日相同。",
  s2_label: "情緒穩定",
  s2_desc: "服務過程互動良好，情緒平穩。",
  s3_label: "生活作息正常",
  s3_desc: "今日生活作息與平日相同，未見明顯異常。",
  s4_event_no: "無特殊不適主訴。",
  s4_handling_no: "無需特殊處理。",
  s6_desc: "個案整體狀況穩定，建議持續現有照顧模式，如有異常將立即回報家屬及照顧管理師。"
};

var STORAGE_KEY = "cgRecordTool_cases_v2";
var TAGS_KEY = "cgRecordTool_customTags_v2";

/* ========================================================
   2. 狀態管理
   ======================================================== */
var state = {
  cases: [],
  customDiseases: [],
  customAttentions: [],
  customReminders: [],
  currentTab: "dashboard",
  editingId: null,
  selectedDiseases: [],
  selectedAttentions: [],
  selectedServices: [],
  filters: { search:"", disease:"", service:"", status:"" },
  pendingConfirmAction: null,
  reopenRecordsCaseId: null,

  viewingCaseId: null,

  recordEditingId: null,
  recordServiceCounts: {},
  recordSelectedReminders: [],
  s5LastAuto: ""
};

function uid(){ return "c" + Date.now().toString(36) + Math.random().toString(36).slice(2,7); }

/* 資料存在 Claude 提供的跨裝置持久化儲存（個人資料，shared=false），
   在 Claude App／claude.ai 裡開啟這個檔案都能讀到同一份資料 */
async function loadData(){
  try{
    var res = await window.storage.get(STORAGE_KEY, false);
    state.cases = (res && res.value) ? JSON.parse(res.value) : [];
  }catch(e){
    state.cases = [];
  }

  try{
    var resTags = await window.storage.get(TAGS_KEY, false);
    if(resTags && resTags.value){
      var tags = JSON.parse(resTags.value);
      state.customDiseases = tags.diseases || [];
      state.customAttentions = tags.attentions || [];
      state.customReminders = tags.reminders || [];
    }
  }catch(e){}

  var patched = false;
  state.cases.forEach(function(c){
    if(!c.records) c.records = [];
    if(!c.services){
      var latest = c.records.length ? c.records.slice().sort(function(a,b){
        return (dateStrToTs(b.date)||b.updatedAt||0) - (dateStrToTs(a.date)||a.updatedAt||0);
      })[0] : null;
      c.services = latest ? (latest.services || []).slice() : [];
      patched = true;
    }
  });

  /* 清除舊版已停用/合併的服務代碼（例如合併前的 BA05-1、BA05-2、舊版單一 BA17），
     避免案件或紀錄裡殘留無法辨識的代碼標籤 */
  var validCodes = {};
  BA_ITEMS.forEach(function(it){ validCodes[it.code] = true; });
  var cleaned = false;
  state.cases.forEach(function(c){
    if(c.services && c.services.length){
      var filteredServices = c.services.filter(function(code){ return validCodes[code]; });
      if(filteredServices.length !== c.services.length){ c.services = filteredServices; cleaned = true; }
    }
    (c.records||[]).forEach(function(r){
      if(r.services && r.services.length){
        var filteredR = r.services.filter(function(code){ return validCodes[code]; });
        if(filteredR.length !== r.services.length){ r.services = filteredR; cleaned = true; }
      }
      if(r.serviceCounts){
        var newCounts = {};
        var countsChanged = false;
        Object.keys(r.serviceCounts).forEach(function(code){
          if(validCodes[code]) newCounts[code] = r.serviceCounts[code];
          else countsChanged = true;
        });
        if(countsChanged){ r.serviceCounts = newCounts; cleaned = true; }
      }
    });
  });

  if(cleaned){ await saveData(); showToastQueued("已自動清除舊版無效的服務項目代碼"); }
  else if(patched){ await saveData(); }
}

var _toastQueue = "";
function showToastQueued(msg){ _toastQueue = msg; }

async function saveData(){
  try{
    await window.storage.set(STORAGE_KEY, JSON.stringify(state.cases), false);
  }catch(e){
    console.error("儲存案件資料失敗", e);
    showToast("儲存失敗，請稍後再試一次");
  }
  try{
    await window.storage.set(TAGS_KEY, JSON.stringify({diseases:state.customDiseases, attentions:state.customAttentions, reminders:state.customReminders}), false);
  }catch(e){
    console.error("儲存標籤資料失敗", e);
  }
}

/* ========================================================
   3. 工具函式
   ======================================================== */
function formatDate(ts){
  var d = new Date(ts);
  var y=d.getFullYear(), m=("0"+(d.getMonth()+1)).slice(-2), day=("0"+d.getDate()).slice(-2);
  return y+"/"+m+"/"+day;
}
function todayStr(){
  var d = new Date();
  return d.getFullYear()+"-"+("0"+(d.getMonth()+1)).slice(-2)+"-"+("0"+d.getDate()).slice(-2);
}
function dateStrToTs(str){
  if(!str) return null;
  var p = str.split("-");
  return new Date(parseInt(p[0],10), parseInt(p[1],10)-1, parseInt(p[2],10)).getTime();
}
function daysSince(ts){
  return Math.floor((Date.now()-ts) / 86400000);
}
/* 週期以週日為起始：回傳指定時間所屬「本週週日 00:00」的時間戳 */
function startOfWeek(ts){
  var d = new Date(ts);
  d.setHours(0,0,0,0);
  d.setDate(d.getDate() - d.getDay());
  return d.getTime();
}
function currentWeekRange(){
  var start = startOfWeek(Date.now());
  return { start: start, end: start + 7*86400000 };
}
function isInCurrentWeek(ts){
  if(ts===null || ts===undefined) return false;
  var range = currentWeekRange();
  return ts >= range.start && ts < range.end;
}
/* 當月範圍：當月1日 00:00 ～ 下月1日 00:00（不含） */
function currentMonthRange(){
  var now = new Date();
  var start = new Date(now.getFullYear(), now.getMonth(), 1).getTime();
  var end = new Date(now.getFullYear(), now.getMonth()+1, 1).getTime();
  return { start: start, end: end };
}
function isInCurrentMonth(ts){
  if(ts===null || ts===undefined) return false;
  var range = currentMonthRange();
  return ts >= range.start && ts < range.end;
}
function isoDateFromTs(ts){
  var d = new Date(ts);
  return d.getFullYear()+"-"+("0"+(d.getMonth()+1)).slice(-2)+"-"+("0"+d.getDate()).slice(-2);
}
function formatDateSlash(ts){
  var d = new Date(ts);
  return d.getFullYear()+"/"+(d.getMonth()+1)+"/"+d.getDate();
}
/* 一筆紀錄的週別顯示，例如 2026/8/2-2026/8/9（週日起算的7日區間） */
/* 週範圍顯示為週日～週六（例如 2026/8/2-2026/8/8），共7天 */
function weekLabelFromTs(ts){
  var start = startOfWeek(ts);
  var end = start + 6*86400000;
  return formatDateSlash(start) + "-" + formatDateSlash(end);
}
function weekLabelFromDateStr(dateStr){
  var ts = dateStrToTs(dateStr);
  if(ts===null) return "";
  return weekLabelFromTs(ts);
}
function esc(s){
  return String(s==null?"":s).replace(/[&<>"']/g, function(ch){
    return {"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[ch];
  });
}
function showToast(msg){
  var t = document.getElementById("toast");
  t.textContent = msg;
  t.classList.add("show");
  clearTimeout(showToast._timer);
  showToast._timer = setTimeout(function(){ t.classList.remove("show"); }, 2200);
}
function showAppLoading(show){
  var el = document.getElementById("appLoading");
  if(!el) return;
  el.classList.toggle("hidden", !show);
}
function baItemByCode(code){
  for(var i=0;i<BA_ITEMS.length;i++){ if(BA_ITEMS[i].code===code) return BA_ITEMS[i]; }
  return null;
}
function allDiseaseOptions(){ return DEFAULT_DISEASES.concat(state.customDiseases); }
function allAttentionOptions(){ return DEFAULT_ATTENTIONS.concat(state.customAttentions); }
function allReminderOptions(){ return DEFAULT_REMINDERS.concat(state.customReminders); }

function caseLastRecord(c){
  if(!c.records || c.records.length===0) return null;
  var sorted = c.records.slice().sort(function(a,b){
    return (dateStrToTs(b.date)||b.updatedAt) - (dateStrToTs(a.date)||a.updatedAt);
  });
  return sorted[0];
}
function caseLastTs(c){
  var r = caseLastRecord(c);
  if(!r) return null;
  return dateStrToTs(r.date) || r.updatedAt;
}
function caseHasRecordThisWeek(c){
  return (c.records||[]).some(function(r){
    var ts = dateStrToTs(r.date) || r.updatedAt;
    return isInCurrentWeek(ts);
  });
}
function caseIsOverdue(c){
  return !caseHasRecordThisWeek(c);
}

/* ========================================================
   4. 紀錄自動組成
   ======================================================== */
function buildAutoS5(codes){
  if(!codes || codes.length===0) return "";
  var sentences = codes.map(function(code){
    var item = baItemByCode(code);
    return item ? item.text : "";
  }).filter(Boolean);
  return sentences.join("");
}

/* 依「服務項目→本週次數」物件產生第五段文字，次數大於1時附註執行次數 */
function buildAutoS5FromCounts(counts){
  var codes = Object.keys(counts||{}).filter(function(code){ return (counts[code]||0) > 0; });
  if(!codes.length) return "";
  var sentences = codes.map(function(code){
    var item = baItemByCode(code);
    if(!item) return "";
    var cnt = counts[code];
    var suffix = cnt > 1 ? ("（本週執行" + cnt + "次）") : "";
    return item.text + suffix;
  }).filter(Boolean);
  return sentences.join("");
}

/* 依「服務項目→本週次數」物件計算薪資（單價×次數加總後再乘上收入比例，只捨入一次） */
function payFromCounts(counts){
  var raw = 0;
  Object.keys(counts||{}).forEach(function(code){
    var item = baItemByCode(code);
    if(item) raw += item.price * (counts[code]||0);
  });
  return Math.round(raw * PAY_RATE * 100) / 100;
}

/* 相容舊資料：優先使用 serviceCounts，若無則退回以 services 陣列(每項視為1次)計算 */
function payForRecord(r){
  if(r && r.serviceCounts && Object.keys(r.serviceCounts).length){
    return payFromCounts(r.serviceCounts);
  }
  return servicesPayTotal(r ? r.services : []);
}

function buildFullRecordText(caseCode, r){
  var lines = [];
  if(r.date){
    lines.push("服務週別：" + weekLabelFromDateStr(r.date));
    lines.push("");
  }
  lines.push("一、認知功能與身體狀況變化");
  lines.push("☑ " + (r.s1_label || "").trim());
  lines.push("說明：" + (r.s1_desc || "").trim());
  lines.push("");
  lines.push("二、精神情緒及互動情形");
  lines.push("☑ " + (r.s2_label || "").trim());
  lines.push("說明：" + (r.s2_desc || "").trim());
  lines.push("");
  lines.push("三、生活作息與基本生理狀況");
  lines.push("☑ " + (r.s3_label || "").trim());
  lines.push("說明：" + (r.s3_desc || "").trim());
  lines.push("");
  lines.push("四、特殊事件及異常狀況");
  lines.push("☑ " + (r.s4_hasEvent ? "有" : "無"));
  lines.push("事件內容：" + (r.s4_event || "").trim());
  lines.push("處理情形：" + (r.s4_handling || "").trim());
  lines.push("");
  lines.push("五、服務過程與溝通紀錄");
  lines.push((r.s5_desc || "").trim());
  lines.push("");
  lines.push("六、整體評估與後續建議");
  lines.push((r.s6_desc || "").trim());
  if(r.reminders && r.reminders.length){
    lines.push("");
    lines.push("小提醒");
    r.reminders.forEach(function(rm){ lines.push("✓ " + rm); });
  }
  return lines.join("\n");
}

/* ========================================================
   5. 導覽切換
   ======================================================== */
function switchTab(tab){
  state.currentTab = tab;
  document.querySelectorAll(".tab-btn").forEach(function(b){
    b.classList.toggle("active", b.dataset.tab===tab);
  });
  document.getElementById("view-dashboard").classList.toggle("active", tab==="dashboard");
  document.getElementById("view-list").classList.toggle("active", tab==="list");
  if(tab==="dashboard") renderDashboard();
  if(tab==="list") renderList();
}

/* ========================================================
   6. 儀表板渲染
   ======================================================== */
function renderDashboard(){
  var cases = state.cases;
  document.getElementById("statTotal").textContent = cases.length;

  var overdue = cases.filter(caseIsOverdue);
  var weekCount = cases.length - overdue.length;
  document.getElementById("statWeek").textContent = weekCount;
  document.getElementById("statOverdue").textContent = overdue.length;

  var topList = computeTopServices(3);
  if(topList.length){
    var top1 = topList[0];
    document.getElementById("statTopService").textContent = top1.code + " " + top1.name;
    document.getElementById("statTopServiceSub").textContent = "共執行 " + top1.count + " 次・點我看前3名 →";
  }else{
    document.getElementById("statTopService").textContent = "—";
    document.getElementById("statTopServiceSub").textContent = "尚無資料";
  }

  var monthPay = 0;
  cases.forEach(function(c){
    (c.records||[]).forEach(function(r){
      var ts = dateStrToTs(r.date) || r.updatedAt;
      if(isInCurrentMonth(ts)){
        monthPay += payForRecord(r);
      }
    });
  });
  document.getElementById("statMonthPay").textContent = "NT$" + formatMoney(monthPay);

  var overdueListEl = document.getElementById("overdueList");
  if(overdue.length===0){
    overdueListEl.innerHTML = '<div class="empty-hint">目前沒有逾期未更新的案件 🌿</div>';
  }else{
    overdue.sort(function(a,b){
      var ta = caseLastTs(a), tb = caseLastTs(b);
      return (ta===null?-1:ta) - (tb===null?-1:tb);
    });
    overdueListEl.innerHTML = overdue.map(function(c){
      var ts = caseLastTs(c);
      var meta = ts===null ? "尚未有任何紀錄" : ("本週尚未新增紀錄（最後一筆 "+weekLabelFromTs(ts)+"）");
      return '<div class="mini-row">'+
        '<div class="mini-row-left"><div class="mini-row-code">'+esc(c.code)+'</div>'+
        '<div class="mini-row-meta">'+meta+'</div></div>'+
        '<button class="btn btn-sm btn-secondary" data-view-records="'+c.id+'">前往新增紀錄</button>'+
      '</div>';
    }).join("");
  }

  var recentListEl = document.getElementById("recentList");
  var allRecords = [];
  cases.forEach(function(c){
    (c.records||[]).forEach(function(r){
      allRecords.push({caseId:c.id, caseCode:c.code, ts: dateStrToTs(r.date)||r.updatedAt, serviceCount:(r.services||[]).length});
    });
  });
  if(allRecords.length===0){
    recentListEl.innerHTML = '<div class="empty-hint">尚未建立任何紀錄，點右上角「新增案件」開始使用</div>';
  }else{
    allRecords.sort(function(a,b){ return b.ts - a.ts; });
    recentListEl.innerHTML = allRecords.slice(0,5).map(function(r){
      return '<div class="mini-row">'+
        '<div class="mini-row-left"><div class="mini-row-code">'+esc(r.caseCode)+'</div>'+
        '<div class="mini-row-meta">'+ r.serviceCount +' 項服務・'+weekLabelFromTs(r.ts)+'</div></div>'+
        '<button class="btn btn-sm btn-ghost" data-view-records="'+r.caseId+'">查看</button>'+
      '</div>';
    }).join("");
  }

  bindRowActions();
}

/* ========================================================
   6a. 最常用服務項目排行
   ======================================================== */
function computeTopServices(limit){
  var freq = {};
  state.cases.forEach(function(c){
    (c.records||[]).forEach(function(r){
      var counts = (r.serviceCounts && Object.keys(r.serviceCounts).length) ? r.serviceCounts : countsFromRecord(r);
      Object.keys(counts).forEach(function(code){
        freq[code] = (freq[code]||0) + (counts[code]||0);
      });
    });
  });
  var list = Object.keys(freq).map(function(code){
    var item = baItemByCode(code);
    return { code: code, name: item ? item.name : code, count: freq[code] };
  }).sort(function(a,b){ return b.count - a.count; });
  return limit ? list.slice(0, limit) : list;
}

function renderTopServicesDetail(){
  var top3 = computeTopServices(3);
  var listEl = document.getElementById("topServicesList");
  if(top3.length===0){
    listEl.innerHTML = '<div class="empty-hint">尚無任何服務執行紀錄</div>';
    return;
  }
  var medals = ["🥇","🥈","🥉"];
  listEl.innerHTML = top3.map(function(it, idx){
    return '<div class="top-rank-row">'+
      '<div class="top-rank-badge rank'+(idx+1)+'">'+(idx+1)+'</div>'+
      '<div class="top-rank-info">'+
        '<div class="top-rank-name">'+medals[idx]+' '+it.code+' '+esc(it.name)+'</div>'+
        '<div class="top-rank-meta">累計執行次數</div>'+
      '</div>'+
      '<div class="top-rank-count">'+it.count+' 次</div>'+
    '</div>';
  }).join("");
}

function openTopServices(){
  renderTopServicesDetail();
  document.getElementById("topServicesOverlay").classList.add("active");
  document.body.style.overflow = "hidden";
}
function closeTopServices(){
  document.getElementById("topServicesOverlay").classList.remove("active");
  document.body.style.overflow = "";
}

/* ========================================================
   6b. 本月預估收入明細
   ======================================================== */
function computeMonthDetail(){
  var range = currentMonthRange();
  var caseBlocks = [];
  var grandTotal = 0;

  state.cases.forEach(function(c){
    var itemCounts = {};
    (c.records||[]).forEach(function(r){
      var ts = dateStrToTs(r.date) || r.updatedAt;
      if(ts===null || ts < range.start || ts >= range.end) return;
      var counts = (r.serviceCounts && Object.keys(r.serviceCounts).length) ? r.serviceCounts : countsFromRecord(r);
      Object.keys(counts).forEach(function(code){
        itemCounts[code] = (itemCounts[code]||0) + (counts[code]||0);
      });
    });

    var codes = Object.keys(itemCounts);
    if(codes.length===0) return;

    var items = codes.map(function(code){
      var item = baItemByCode(code);
      var count = itemCounts[code];
      var unitPrice = item ? item.price : 0;
      var subtotal = Math.round(unitPrice * count * PAY_RATE * 100) / 100;
      return { code: code, name: item ? item.name : code, count: count, unitPrice: unitPrice, subtotal: subtotal };
    }).sort(function(a,b){ return b.subtotal - a.subtotal; });

    var caseTotal = Math.round(items.reduce(function(s,it){ return s+it.subtotal; }, 0) * 100) / 100;
    grandTotal += caseTotal;
    caseBlocks.push({ caseCode: c.code, items: items, caseTotal: caseTotal });
  });

  caseBlocks.sort(function(a,b){ return b.caseTotal - a.caseTotal; });
  grandTotal = Math.round(grandTotal * 100) / 100;

  return { caseBlocks: caseBlocks, grandTotal: grandTotal };
}

function renderMonthDetail(){
  var now = new Date();
  document.getElementById("monthDetailSub").textContent = now.getFullYear() + "年" + (now.getMonth()+1) + "月";

  var detail = computeMonthDetail();
  document.getElementById("monthDetailGrandTotal").textContent = "NT$" + formatMoney(detail.grandTotal);

  var listEl = document.getElementById("monthDetailList");
  if(detail.caseBlocks.length===0){
    listEl.innerHTML = '<div class="empty-hint">本月尚無任何紀錄</div>';
    return;
  }

  listEl.innerHTML = detail.caseBlocks.map(function(block){
    var itemsHtml = block.items.map(function(it){
      return '<div class="month-item-row">'+
        '<div><div class="month-item-name">'+it.code+' '+esc(it.name)+'</div>'+
        '<div class="month-item-meta">單價 NT$'+it.unitPrice+' × '+it.count+' 次</div></div>'+
        '<div class="month-item-subtotal">NT$'+formatMoney(it.subtotal)+'</div>'+
      '</div>';
    }).join("");
    return '<div class="month-case-block">'+
      '<div class="month-case-head"><span class="month-case-code">'+esc(block.caseCode)+'</span></div>'+
      itemsHtml+
      '<div class="month-case-total"><span>小計</span><span>NT$'+formatMoney(block.caseTotal)+'</span></div>'+
    '</div>';
  }).join("");
}

function openMonthDetail(){
  renderMonthDetail();
  document.getElementById("monthDetailOverlay").classList.add("active");
  document.body.style.overflow = "hidden";
}
function closeMonthDetail(){
  document.getElementById("monthDetailOverlay").classList.remove("active");
  document.body.style.overflow = "";
}

function bindRowActions(){
  document.querySelectorAll("[data-edit]").forEach(function(btn){
    btn.onclick = function(){ openForm(btn.dataset.edit); };
  });
  document.querySelectorAll("[data-delete]").forEach(function(btn){
    btn.onclick = function(){ askDeleteCase(btn.dataset.delete); };
  });
  document.querySelectorAll("[data-view-records]").forEach(function(btn){
    btn.onclick = function(){ openRecordsOverlay(btn.dataset.viewRecords); };
  });
  document.querySelectorAll("[data-copy-latest]").forEach(function(btn){
    btn.onclick = function(){ copyLatestRecord(btn.dataset.copyLatest); };
  });
}

/* ========================================================
   7. 清單頁渲染
   ======================================================== */
function populateFilterOptions(){
  var diseaseSel = document.getElementById("filterDisease");
  var current = diseaseSel.value;
  var diseaseSet = {};
  state.cases.forEach(function(c){ (c.diseases||[]).forEach(function(d){ diseaseSet[d]=true; }); });
  var diseaseList = Object.keys(diseaseSet).sort();
  diseaseSel.innerHTML = '<option value="">全部慢性病</option>' + diseaseList.map(function(d){
    return '<option value="'+esc(d)+'">'+esc(d)+'</option>';
  }).join("");
  diseaseSel.value = diseaseList.indexOf(current)>=0 ? current : "";

  var serviceSel = document.getElementById("filterService");
  var currentS = serviceSel.value;
  serviceSel.innerHTML = '<option value="">全部服務項目</option>' + BA_ITEMS.map(function(it){
    return '<option value="'+it.code+'">'+it.code+' '+esc(it.name)+'</option>';
  }).join("");
  serviceSel.value = currentS;
}

function caseHasService(c, code){
  return (c.services||[]).indexOf(code)>=0;
}

function getFilteredCases(){
  var f = state.filters;
  return state.cases.filter(function(c){
    if(f.search && c.code.toLowerCase().indexOf(f.search.toLowerCase())===-1) return false;
    if(f.disease && (c.diseases||[]).indexOf(f.disease)===-1) return false;
    if(f.service && !caseHasService(c, f.service)) return false;
    if(f.status==="ok" && caseIsOverdue(c)) return false;
    if(f.status==="overdue" && !caseIsOverdue(c)) return false;
    return true;
  }).sort(function(a,b){
    var ta = caseLastTs(a), tb = caseLastTs(b);
    return (tb===null?-1:tb) - (ta===null?-1:ta);
  });
}

function tagListHtml(list, cls){
  if(!list || list.length===0) return '<span class="tag tag-gray">未設定</span>';
  return '<div class="tag-wrap">' + list.map(function(v){
    return '<span class="tag '+cls+'">'+esc(v)+'</span>';
  }).join("") + '</div>';
}

function renderList(){
  populateFilterOptions();
  var list = getFilteredCases();
  var tbody = document.getElementById("caseTableBody");
  var cardsWrap = document.getElementById("caseCards");
  var emptyHint = document.getElementById("listEmptyHint");

  if(list.length===0){
    tbody.innerHTML = "";
    cardsWrap.innerHTML = "";
    emptyHint.style.display = "block";
    return;
  }
  emptyHint.style.display = "none";

  tbody.innerHTML = list.map(function(c){
    var ts = caseLastTs(c);
    var statusTag = caseIsOverdue(c) ? '<span class="tag tag-pink">逾期</span>' : '<span class="tag tag-sage">已更新</span>';
    var lastDateText = ts===null ? "尚無紀錄" : weekLabelFromTs(ts);
    var pay = servicesPayTotal(c.services);
    return '<tr>'+
      '<td class="code-cell">'+esc(c.code)+'</td>'+
      '<td>'+tagListHtml(c.diseases, "tag-gray")+'</td>'+
      '<td><span class="pay-pill">NT$'+formatMoney(pay)+'</span></td>'+
      '<td>'+(c.records||[]).length+' 筆</td>'+
      '<td class="date-cell">'+lastDateText+'<br>'+statusTag+'</td>'+
      '<td class="actions-cell">'+
        '<button class="btn btn-sm btn-primary" data-view-records="'+c.id+'">紀錄</button>'+
        '<button class="btn btn-sm btn-ghost" data-edit="'+c.id+'">編輯資料</button>'+
        '<button class="btn btn-sm btn-danger" data-delete="'+c.id+'">刪除</button>'+
      '</td>'+
    '</tr>';
  }).join("");

  cardsWrap.innerHTML = list.map(function(c){
    var ts = caseLastTs(c);
    var statusTag = caseIsOverdue(c) ? '<span class="tag tag-pink">逾期未寫紀錄</span>' : '<span class="tag tag-sage">本週已寫紀錄</span>';
    var lastDateText = ts===null ? "尚無紀錄" : weekLabelFromTs(ts);
    var pay = servicesPayTotal(c.services);
    return '<div class="case-card">'+
      '<div class="case-card-top"><div class="code-cell">'+esc(c.code)+'</div>'+statusTag+'</div>'+
      '<div style="margin-bottom:8px;">'+tagListHtml(c.diseases,"tag-gray")+'</div>'+
      '<div style="margin-bottom:8px;"><span class="pay-pill">常用服務預估收入 NT$'+formatMoney(pay)+'</span></div>'+
      '<div class="date-cell">紀錄 '+(c.records||[]).length+' 筆・最後 '+lastDateText+'</div>'+
      '<div class="case-card-actions">'+
        '<button class="btn btn-sm btn-primary" data-view-records="'+c.id+'">紀錄</button>'+
        '<button class="btn btn-sm btn-ghost" data-edit="'+c.id+'">編輯資料</button>'+
        '<button class="btn btn-sm btn-danger" data-delete="'+c.id+'">刪除</button>'+
      '</div>'+
    '</div>';
  }).join("");

  bindRowActions();
}

function copyText(text){
  var doCopy = function(){ showToast("已複製紀錄內容"); };
  if(navigator.clipboard && navigator.clipboard.writeText){
    navigator.clipboard.writeText(text).then(doCopy).catch(function(){ fallbackCopy(text, doCopy); });
  }else{
    fallbackCopy(text, doCopy);
  }
}
function fallbackCopy(text, cb){
  var ta = document.createElement("textarea");
  ta.value = text; ta.style.position="fixed"; ta.style.opacity="0";
  document.body.appendChild(ta); ta.select();
  try{ document.execCommand("copy"); }catch(e){}
  document.body.removeChild(ta);
  if(cb) cb();
}
function copyLatestRecord(caseId){
  var c = state.cases.find(function(x){ return x.id===caseId; });
  if(!c) return;
  var r = caseLastRecord(c);
  if(!r){ showToast("此案件尚無紀錄"); return; }
  copyText("個案代號：" + c.code + "\n" + buildFullRecordText(c.code, r));
}

/* ========================================================
   8. 案件基本資料表單
   ======================================================== */
function renderDiseasePicker(){
  var wrap = document.getElementById("diseasePicker");
  wrap.innerHTML = allDiseaseOptions().map(function(d){
    var sel = state.selectedDiseases.indexOf(d)>=0;
    return '<button type="button" class="chip-option'+(sel?' selected':'')+'" data-disease="'+esc(d)+'">'+esc(d)+'</button>';
  }).join("");
  wrap.querySelectorAll("[data-disease]").forEach(function(btn){
    btn.onclick = function(){
      var d = btn.dataset.disease;
      var idx = state.selectedDiseases.indexOf(d);
      if(idx>=0) state.selectedDiseases.splice(idx,1); else state.selectedDiseases.push(d);
      renderDiseasePicker();
    };
  });
}

function renderAttentionPicker(){
  var wrap = document.getElementById("attentionPicker");
  wrap.innerHTML = allAttentionOptions().map(function(a){
    var sel = state.selectedAttentions.indexOf(a)>=0;
    return '<button type="button" class="chip-option'+(sel?' selected':'')+'" data-attn="'+esc(a)+'">'+esc(a)+'</button>';
  }).join("");
  wrap.querySelectorAll("[data-attn]").forEach(function(btn){
    btn.onclick = function(){
      var a = btn.dataset.attn;
      var idx = state.selectedAttentions.indexOf(a);
      if(idx>=0) state.selectedAttentions.splice(idx,1); else state.selectedAttentions.push(a);
      renderAttentionPicker();
    };
  });
}

function servicesPayTotal(codes){
  var sum = (codes||[]).reduce(function(acc, code){
    var item = baItemByCode(code);
    return acc + (item ? payOf(item.price) : 0);
  }, 0);
  return Math.round(sum * 100) / 100;
}

function renderServiceListPayTotal(){
  var el = document.getElementById("serviceListPayTotal");
  if(!el) return;
  var total = servicesPayTotal(state.selectedServices);
  el.textContent = state.selectedServices.length
    ? ("每次服務完成，這個案件預估可得 NT$" + formatMoney(total))
    : "";
}

function renderServiceList(){
  var wrap = document.getElementById("serviceList");
  wrap.innerHTML = BA_ITEMS.map(function(item){
    var checked = state.selectedServices.indexOf(item.code)>=0;
    return '<div class="service-item'+(checked?' checked':'')+'" data-code="'+item.code+'">'+
      '<label class="service-item-head">'+
        '<input type="checkbox" '+(checked?'checked':'')+' data-service-checkbox="'+item.code+'">'+
        '<span><span class="service-item-name"><span class="service-item-code">'+item.code+'</span> '+esc(item.name)+'</span>'+
        '<div class="service-item-desc">'+esc(item.desc)+'</div>'+
        '<div class="service-item-pay">給付 NT$'+item.price+'・預估收入 NT$'+formatMoney(payOf(item.price))+'</div></span>'+
      '</label>'+
    '</div>';
  }).join("");
  renderServiceListPayTotal();
  wrap.querySelectorAll("[data-service-checkbox]").forEach(function(cb){
    cb.onchange = function(){
      var code = cb.dataset.serviceCheckbox;
      var idx = state.selectedServices.indexOf(code);
      if(idx>=0) state.selectedServices.splice(idx,1); else state.selectedServices.push(code);
      renderServiceList();
    };
  });
}

function resetFormState(){
  state.editingId = null;
  state.selectedDiseases = [];
  state.selectedAttentions = [];
  state.selectedServices = [];
  document.getElementById("inputCode").value = "";
  document.getElementById("inputRemark").value = "";
  document.getElementById("fieldCode").classList.remove("error");
  document.getElementById("inputCode").disabled = false;
}

function openForm(id){
  resetFormState();
  var title = document.getElementById("formTitle");
  if(id){
    var c = state.cases.find(function(x){ return x.id===id; });
    if(!c) return;
    state.editingId = id;
    title.textContent = "編輯案件";
    document.getElementById("inputCode").value = c.code;
    state.selectedDiseases = (c.diseases||[]).slice();
    state.selectedAttentions = (c.attentions||[]).slice();
    state.selectedServices = (c.services||[]).slice();
    document.getElementById("inputRemark").value = c.remark || "";
  }else{
    title.textContent = "新增案件";
  }
  renderDiseasePicker();
  renderAttentionPicker();
  renderServiceList();
  document.getElementById("formOverlay").classList.add("active");
  document.body.style.overflow = "hidden";
  setTimeout(function(){ document.getElementById("inputCode").focus(); }, 50);
}

function closeForm(){
  document.getElementById("formOverlay").classList.remove("active");
  document.body.style.overflow = "";
  if(state.reopenRecordsCaseId){
    var idToReopen = state.reopenRecordsCaseId;
    state.reopenRecordsCaseId = null;
    openRecordsOverlay(idToReopen);
  }
}

function saveCase(){
  var codeInput = document.getElementById("inputCode");
  var code = codeInput.value.trim();
  var fieldCode = document.getElementById("fieldCode");

  if(!code){
    fieldCode.classList.add("error");
    codeInput.focus();
    return;
  }
  var dup = state.cases.find(function(c){ return c.code===code && c.id!==state.editingId; });
  if(dup){
    fieldCode.classList.add("error");
    codeInput.focus();
    return;
  }
  fieldCode.classList.remove("error");

  var now = Date.now();
  var remark = document.getElementById("inputRemark").value.trim();

  if(state.editingId){
    var c = state.cases.find(function(x){ return x.id===state.editingId; });
    c.code = code;
    c.diseases = state.selectedDiseases.slice();
    c.attentions = state.selectedAttentions.slice();
    c.services = state.selectedServices.slice();
    c.remark = remark;
    c.updatedAt = now;
    showToast("已更新案件「"+code+"」");
  }else{
    state.cases.push({
      id: uid(),
      code: code,
      diseases: state.selectedDiseases.slice(),
      attentions: state.selectedAttentions.slice(),
      services: state.selectedServices.slice(),
      remark: remark,
      createdAt: now,
      updatedAt: now,
      records: []
    });
    showToast("已新增案件「"+code+"」");
  }
  saveData();
  closeForm();
  if(state.currentTab==="dashboard") renderDashboard(); else renderList();
}

/* ========================================================
   9. 歷史紀錄總覽 (records overlay)
   ======================================================== */
function openRecordsOverlay(caseId){
  var c = state.cases.find(function(x){ return x.id===caseId; });
  if(!c) return;
  state.viewingCaseId = caseId;
  document.getElementById("recordsCaseTitle").textContent = c.code + " 的紀錄";
  document.getElementById("recordsCaseSub").textContent = (c.diseases&&c.diseases.length) ? ("慢性病："+c.diseases.join("、")) : "尚未設定慢性病";
  renderRecordsTimeline();
  document.getElementById("recordsOverlay").classList.add("active");
  document.body.style.overflow = "hidden";
}
function closeRecordsOverlay(){
  document.getElementById("recordsOverlay").classList.remove("active");
  document.body.style.overflow = "";
  state.viewingCaseId = null;
  renderList();
  renderDashboard();
}

function renderRecordsTimeline(){
  var c = state.cases.find(function(x){ return x.id===state.viewingCaseId; });
  var wrap = document.getElementById("recordsTimeline");
  if(!c || !c.records || c.records.length===0){
    wrap.innerHTML = '<div class="empty-hint">這個案件還沒有任何紀錄，點上方「新增本週紀錄」開始寫第一筆</div>';
    return;
  }
  var sorted = c.records.slice().sort(function(a,b){
    return (dateStrToTs(b.date)||b.updatedAt) - (dateStrToTs(a.date)||a.updatedAt);
  });
  var grandTotal = sorted.reduce(function(sum, r){ return sum + payForRecord(r); }, 0);
  var totalBar = '<div class="hint" style="margin-bottom:10px; font-weight:700; color:var(--sage);">累計 '+sorted.length+' 筆紀錄，預估總收入 NT$'+formatMoney(grandTotal)+'</div>';
  wrap.innerHTML = totalBar + sorted.map(function(r, idx){
    var fullText = buildFullRecordText(c.code, r);
    var recPay = payForRecord(r);
    var weekLabel = r.date ? weekLabelFromDateStr(r.date) : "（未設定週別）";
    return '<div class="record-card">'+
      '<div class="record-card-head">'+
        '<div class="record-card-date">📅 '+esc(weekLabel)+' <span class="pay-pill" style="margin-left:6px;">NT$'+formatMoney(recPay)+'</span></div>'+
        '<div class="record-card-actions">'+
          '<button class="btn btn-sm btn-secondary" data-toggle-idx="'+idx+'">展開內容</button>'+
          '<button class="btn btn-sm btn-secondary" data-copy-rec="'+r.id+'">複製</button>'+
          '<button class="btn btn-sm btn-ghost" data-edit-rec="'+r.id+'">編輯</button>'+
          '<button class="btn btn-sm btn-danger" data-del-rec="'+r.id+'">刪除</button>'+
        '</div>'+
      '</div>'+
      '<div class="record-card-body" id="recBody'+idx+'">'+esc(fullText)+'</div>'+
    '</div>';
  }).join("");

  wrap.querySelectorAll("[data-toggle-idx]").forEach(function(btn){
    btn.onclick = function(){
      var el = document.getElementById("recBody"+btn.dataset.toggleIdx);
      var expanded = el.classList.toggle("expanded");
      btn.textContent = expanded ? "收合內容" : "展開內容";
    };
  });
  wrap.querySelectorAll("[data-copy-rec]").forEach(function(btn){
    btn.onclick = function(){
      var rec = c.records.find(function(x){ return x.id===btn.dataset.copyRec; });
      if(rec) copyText("個案代號：" + c.code + "\n" + buildFullRecordText(c.code, rec));
    };
  });
  wrap.querySelectorAll("[data-edit-rec]").forEach(function(btn){
    btn.onclick = function(){ openRecordForm(c.id, btn.dataset.editRec); };
  });
  wrap.querySelectorAll("[data-del-rec]").forEach(function(btn){
    btn.onclick = function(){ askDeleteRecord(c.id, btn.dataset.delRec); };
  });
}

/* ========================================================
   10. 每週紀錄表單 (六大段落)
   ======================================================== */
function currentCaseServices(){
  var c = state.cases.find(function(x){ return x.id===state.viewingCaseId; });
  return c ? (c.services||[]) : [];
}

function renderRecServiceList(){
  var wrap = document.getElementById("recServiceList");
  wrap.innerHTML = BA_ITEMS.map(function(item){
    var checked = Object.prototype.hasOwnProperty.call(state.recordServiceCounts, item.code);
    var count = checked ? (state.recordServiceCounts[item.code] || 1) : 1;
    return '<div class="service-item'+(checked?' checked':'')+'" data-code="'+item.code+'">'+
      '<label class="service-item-head">'+
        '<input type="checkbox" '+(checked?'checked':'')+' data-rec-service-checkbox="'+item.code+'">'+
        '<span><span class="service-item-name"><span class="service-item-code">'+item.code+'</span> '+esc(item.name)+'</span>'+
        '<div class="service-item-desc">'+esc(item.desc)+'</div>'+
        '<div class="service-item-pay">給付 NT$'+item.price+'・單次預估收入 NT$'+formatMoney(payOf(item.price))+'</div>'+
        (checked ? ('<div class="service-item-count"><label>本週次數</label><input type="number" min="1" step="1" value="'+count+'" data-rec-service-count="'+item.code+'"></div>') : '') +
        '</span>'+
      '</label>'+
    '</div>';
  }).join("");
  renderRecServicePayTotal();
  wrap.querySelectorAll("[data-rec-service-checkbox]").forEach(function(cb){
    cb.onchange = function(){ toggleRecServiceCode(cb.dataset.recServiceCheckbox); };
  });
  wrap.querySelectorAll("[data-rec-service-count]").forEach(function(inp){
    inp.onclick = function(e){ e.preventDefault(); e.stopPropagation(); };
    inp.oninput = function(){
      var n = parseInt(inp.value, 10);
      if(!n || n < 1) n = 1;
      changeRecServiceCount(inp.dataset.recServiceCount, n);
    };
  });
}

function toggleRecServiceCode(code){
  var s5 = document.getElementById("s5_desc");
  var wasAuto = (s5.value.trim() === state.s5LastAuto.trim());

  if(Object.prototype.hasOwnProperty.call(state.recordServiceCounts, code)){
    delete state.recordServiceCounts[code];
  }else{
    state.recordServiceCounts[code] = 1;
  }
  renderRecServiceList();

  if(wasAuto || s5.value.trim()===""){
    var newAuto = buildAutoS5FromCounts(state.recordServiceCounts);
    s5.value = newAuto;
    state.s5LastAuto = newAuto;
  }
  updatePreview();
}

function changeRecServiceCount(code, count){
  var s5 = document.getElementById("s5_desc");
  var wasAuto = (s5.value.trim() === state.s5LastAuto.trim());

  state.recordServiceCounts[code] = count;
  renderRecServicePayTotal();

  if(wasAuto || s5.value.trim()===""){
    var newAuto = buildAutoS5FromCounts(state.recordServiceCounts);
    s5.value = newAuto;
    state.s5LastAuto = newAuto;
  }
  updatePreview();
}

function renderRecServicePayTotal(){
  var el = document.getElementById("recServicePayTotal");
  var codes = Object.keys(state.recordServiceCounts);
  if(!codes.length){
    el.textContent = "尚未勾選任何服務項目";
    return;
  }
  el.textContent = "這筆紀錄預估收入 NT$" + formatMoney(payFromCounts(state.recordServiceCounts));
}

function renderReminderPicker(){
  var wrap = document.getElementById("reminderPicker");
  wrap.innerHTML = allReminderOptions().map(function(r){
    var sel = state.recordSelectedReminders.indexOf(r)>=0;
    return '<button type="button" class="chip-option'+(sel?' selected':'')+'" data-reminder="'+esc(r)+'">'+esc(r)+'</button>';
  }).join("");
  wrap.querySelectorAll("[data-reminder]").forEach(function(btn){
    btn.onclick = function(){
      var r = btn.dataset.reminder;
      var idx = state.recordSelectedReminders.indexOf(r);
      if(idx>=0) state.recordSelectedReminders.splice(idx,1); else state.recordSelectedReminders.push(r);
      renderReminderPicker();
      updatePreview();
    };
  });
}

function currentRecordFormData(){
  var counts = {};
  Object.keys(state.recordServiceCounts).forEach(function(code){
    if(state.recordServiceCounts[code] > 0) counts[code] = state.recordServiceCounts[code];
  });
  return {
    date: document.getElementById("inputRecordDate").value,
    services: Object.keys(counts),
    serviceCounts: counts,
    s1_label: document.getElementById("s1_label").value,
    s1_desc: document.getElementById("s1_desc").value,
    s2_label: document.getElementById("s2_label").value,
    s2_desc: document.getElementById("s2_desc").value,
    s3_label: document.getElementById("s3_label").value,
    s3_desc: document.getElementById("s3_desc").value,
    s4_hasEvent: document.getElementById("s4_hasEvent").checked,
    s4_event: document.getElementById("s4_event").value,
    s4_handling: document.getElementById("s4_handling").value,
    s5_desc: document.getElementById("s5_desc").value,
    s6_desc: document.getElementById("s6_desc").value,
    reminders: state.recordSelectedReminders.slice()
  };
}

function updatePreview(){
  var data = currentRecordFormData();
  var caseObj = state.cases.find(function(x){ return x.id===state.viewingCaseId; });
  var text = buildFullRecordText(caseObj?caseObj.code:"", data);
  document.getElementById("recordPreview").textContent = text;
}

function applyDefaultsToForm(keepEvent){
  document.getElementById("s1_label").value = DEFAULT_SECTION_TEXT.s1_label;
  document.getElementById("s1_desc").value = DEFAULT_SECTION_TEXT.s1_desc;
  document.getElementById("s2_label").value = DEFAULT_SECTION_TEXT.s2_label;
  document.getElementById("s2_desc").value = DEFAULT_SECTION_TEXT.s2_desc;
  document.getElementById("s3_label").value = DEFAULT_SECTION_TEXT.s3_label;
  document.getElementById("s3_desc").value = DEFAULT_SECTION_TEXT.s3_desc;
  if(!keepEvent){
    document.getElementById("s4_hasEvent").checked = false;
    document.getElementById("s4_event").value = DEFAULT_SECTION_TEXT.s4_event_no;
    document.getElementById("s4_handling").value = DEFAULT_SECTION_TEXT.s4_handling_no;
  }
  var s5auto = buildAutoS5FromCounts(state.recordServiceCounts);
  document.getElementById("s5_desc").value = s5auto;
  state.s5LastAuto = s5auto;
  document.getElementById("s6_desc").value = DEFAULT_SECTION_TEXT.s6_desc;
  updatePreview();
}

function onEventToggleChange(){
  var checked = document.getElementById("s4_hasEvent").checked;
  var eventEl = document.getElementById("s4_event");
  var handlingEl = document.getElementById("s4_handling");
  if(checked){
    if(eventEl.value.trim()===DEFAULT_SECTION_TEXT.s4_event_no) eventEl.value = "";
    if(handlingEl.value.trim()===DEFAULT_SECTION_TEXT.s4_handling_no) handlingEl.value = "";
    eventEl.placeholder = "請描述本次發生的事件";
    handlingEl.placeholder = "請描述如何處理及後續追蹤";
  }else{
    eventEl.value = DEFAULT_SECTION_TEXT.s4_event_no;
    handlingEl.value = DEFAULT_SECTION_TEXT.s4_handling_no;
  }
  updatePreview();
}

function countsFromRecord(r){
  if(r.serviceCounts && Object.keys(r.serviceCounts).length){
    var copy = {};
    Object.keys(r.serviceCounts).forEach(function(code){ copy[code] = r.serviceCounts[code]; });
    return copy;
  }
  var counts = {};
  (r.services||[]).forEach(function(code){ counts[code] = 1; });
  return counts;
}

function countsFromCaseDefaults(c){
  var counts = {};
  (c && c.services ? c.services : []).forEach(function(code){ counts[code] = 1; });
  return counts;
}

function updateRecordWeekLabel(){
  var val = document.getElementById("inputRecordDate").value;
  var el = document.getElementById("recordWeekLabel");
  el.textContent = val ? ("所屬週別：" + weekLabelFromDateStr(val)) : "";
}

function openRecordForm(caseId, recordId){
  state.viewingCaseId = caseId;
  state.recordEditingId = recordId || null;
  state.recordSelectedReminders = [];

  var c = state.cases.find(function(x){ return x.id===caseId; });
  var titleEl = document.getElementById("recordFormTitle");
  var subEl = document.getElementById("recordFormSub");
  subEl.textContent = c ? ("個案代號："+c.code) : "";

  if(recordId){
    var r = c.records.find(function(x){ return x.id===recordId; });
    titleEl.textContent = "編輯紀錄";
    document.getElementById("inputRecordDate").value = r.date || todayStr();
    updateRecordWeekLabel();
    state.recordServiceCounts = countsFromRecord(r);
    renderRecServiceList();
    document.getElementById("s1_label").value = r.s1_label||"";
    document.getElementById("s1_desc").value = r.s1_desc||"";
    document.getElementById("s2_label").value = r.s2_label||"";
    document.getElementById("s2_desc").value = r.s2_desc||"";
    document.getElementById("s3_label").value = r.s3_label||"";
    document.getElementById("s3_desc").value = r.s3_desc||"";
    document.getElementById("s4_hasEvent").checked = !!r.s4_hasEvent;
    document.getElementById("s4_event").value = r.s4_event||"";
    document.getElementById("s4_handling").value = r.s4_handling||"";
    document.getElementById("s5_desc").value = r.s5_desc||"";
    state.s5LastAuto = buildAutoS5FromCounts(state.recordServiceCounts);
    document.getElementById("s6_desc").value = r.s6_desc||"";
    state.recordSelectedReminders = (r.reminders||[]).slice();
    renderReminderPicker();
    updatePreview();
  }else{
    titleEl.textContent = "新增本週紀錄";
    document.getElementById("inputRecordDate").value = todayStr();
    updateRecordWeekLabel();
    state.recordServiceCounts = countsFromCaseDefaults(c);
    renderRecServiceList();
    renderReminderPicker();
    applyDefaultsToForm(false);
  }

  document.getElementById("recordFormOverlay").classList.add("active");
  document.body.style.overflow = "hidden";
}

function closeRecordForm(){
  document.getElementById("recordFormOverlay").classList.remove("active");
  document.body.style.overflow = "";
}

function saveRecordForm(){
  var c = state.cases.find(function(x){ return x.id===state.viewingCaseId; });
  if(!c) return;
  var data = currentRecordFormData();
  if(!data.date){ showToast("請選擇紀錄週別"); return; }

  var now = Date.now();
  if(state.recordEditingId){
    var r = c.records.find(function(x){ return x.id===state.recordEditingId; });
    Object.assign(r, data);
    r.updatedAt = now;
    showToast("已更新這筆紀錄");
  }else{
    c.records.push(Object.assign({id:uid(), createdAt:now, updatedAt:now}, data));
    showToast("已新增本週紀錄");
  }
  c.updatedAt = now;
  saveData();
  closeRecordForm();
  renderRecordsTimeline();
}

function askDeleteRecord(caseId, recordId){
  var c = state.cases.find(function(x){ return x.id===caseId; });
  if(!c) return;
  document.getElementById("confirmTitle").textContent = "刪除紀錄";
  document.getElementById("confirmMsg").textContent = "確定要刪除這筆紀錄嗎？此動作無法復原。";
  state.pendingConfirmAction = function(){
    c.records = c.records.filter(function(x){ return x.id!==recordId; });
    c.updatedAt = Date.now();
    saveData();
    showToast("已刪除紀錄");
    renderRecordsTimeline();
  };
  document.getElementById("confirmOverlay").classList.add("active");
}

/* ========================================================
   11. 刪除案件確認
   ======================================================== */
function askDeleteCase(id){
  var c = state.cases.find(function(x){ return x.id===id; });
  if(!c) return;
  document.getElementById("confirmTitle").textContent = "刪除案件";
  document.getElementById("confirmMsg").textContent = "確定要刪除「"+c.code+"」的案件資料嗎？其所有歷史紀錄也會一併刪除，此動作無法復原。";
  state.pendingConfirmAction = function(){
    state.cases = state.cases.filter(function(x){ return x.id!==id; });
    saveData();
    showToast("已刪除案件「"+c.code+"」");
    if(state.currentTab==="dashboard") renderDashboard(); else renderList();
  };
  document.getElementById("confirmOverlay").classList.add("active");
}

/* ========================================================
   12. 匯出／匯入
   ======================================================== */
function exportBackup(){
  var payload = {
    version: 2,
    exportedAt: new Date().toISOString(),
    cases: state.cases,
    customDiseases: state.customDiseases,
    customAttentions: state.customAttentions,
    customReminders: state.customReminders
  };
  var blob = new Blob([JSON.stringify(payload, null, 2)], {type:"application/json"});
  var url = URL.createObjectURL(blob);
  var a = document.createElement("a");
  var d = new Date();
  var stamp = d.getFullYear()+("0"+(d.getMonth()+1)).slice(-2)+("0"+d.getDate()).slice(-2);
  a.href = url;
  a.download = "居服紀錄備份_"+stamp+".json";
  document.body.appendChild(a);
  a.click();
  document.body.removeChild(a);
  URL.revokeObjectURL(url);
  showToast("已匯出備份檔");
}

function importBackup(file){
  var reader = new FileReader();
  reader.onload = function(e){
    try{
      var data = JSON.parse(e.target.result);
      var incomingCases = Array.isArray(data.cases) ? data.cases : (Array.isArray(data) ? data : null);
      if(!incomingCases) throw new Error("格式不正確");

      document.getElementById("confirmTitle").textContent = "匯入備份";
      document.getElementById("confirmMsg").textContent = "將匯入 "+incomingCases.length+" 筆案件資料，並與現有資料合併（相同代號將被匯入檔覆蓋）。是否繼續？";
      state.pendingConfirmAction = function(){
        var map = {};
        state.cases.forEach(function(c){ map[c.code]=c; });
        incomingCases.forEach(function(c){
          if(!c.id) c.id = uid();
          if(!c.records) c.records = [];
          if(!c.createdAt) c.createdAt = Date.now();
          if(!c.updatedAt) c.updatedAt = Date.now();
          map[c.code] = c;
        });
        state.cases = Object.keys(map).map(function(k){ return map[k]; });
        if(Array.isArray(data.customDiseases)){
          state.customDiseases = Array.from(new Set(state.customDiseases.concat(data.customDiseases)));
        }
        if(Array.isArray(data.customAttentions)){
          state.customAttentions = Array.from(new Set(state.customAttentions.concat(data.customAttentions)));
        }
        if(Array.isArray(data.customReminders)){
          state.customReminders = Array.from(new Set(state.customReminders.concat(data.customReminders)));
        }
        saveData();
        showToast("匯入完成，共 "+state.cases.length+" 筆案件");
        if(state.currentTab==="dashboard") renderDashboard(); else renderList();
      };
      document.getElementById("confirmOverlay").classList.add("active");
    }catch(err){
      showToast("匯入失敗：檔案格式不正確");
    }
  };
  reader.readAsText(file, "utf-8");
}

/* ========================================================
   13. 事件綁定
   ======================================================== */
function bindEvents(){
  document.querySelectorAll(".tab-btn").forEach(function(b){
    b.onclick = function(){ switchTab(b.dataset.tab); };
  });

  document.getElementById("btnAddTop").onclick = function(){ openForm(null); };
  document.getElementById("btnAddFab").onclick = function(){ openForm(null); };
  document.getElementById("btnCloseForm").onclick = closeForm;
  document.getElementById("btnCancelForm").onclick = closeForm;
  document.getElementById("btnSaveForm").onclick = saveCase;
  document.getElementById("formOverlay").addEventListener("click", function(e){
    if(e.target.id === "formOverlay") closeForm();
  });

  document.getElementById("inputCode").addEventListener("input", function(){
    document.getElementById("fieldCode").classList.remove("error");
  });

  document.getElementById("diseaseCustomInput").addEventListener("keydown", function(e){
    if(e.key==="Enter"){
      e.preventDefault();
      var v = e.target.value.trim();
      if(v){
        if(allDiseaseOptions().indexOf(v)===-1) state.customDiseases.push(v);
        if(state.selectedDiseases.indexOf(v)===-1) state.selectedDiseases.push(v);
        e.target.value = "";
        renderDiseasePicker();
      }
    }
  });
  document.getElementById("attentionCustomInput").addEventListener("keydown", function(e){
    if(e.key==="Enter"){
      e.preventDefault();
      var v = e.target.value.trim();
      if(v){
        if(allAttentionOptions().indexOf(v)===-1) state.customAttentions.push(v);
        if(state.selectedAttentions.indexOf(v)===-1) state.selectedAttentions.push(v);
        e.target.value = "";
        renderAttentionPicker();
      }
    }
  });

  // records overlay
  document.getElementById("btnCloseRecords").onclick = closeRecordsOverlay;
  document.getElementById("btnCloseRecords2").onclick = closeRecordsOverlay;
  document.getElementById("recordsOverlay").addEventListener("click", function(e){
    if(e.target.id === "recordsOverlay") closeRecordsOverlay();
  });
  document.getElementById("btnAddRecord").onclick = function(){ openRecordForm(state.viewingCaseId, null); };

  document.getElementById("cardMonthPay").onclick = openMonthDetail;
  document.getElementById("btnCloseMonthDetail").onclick = closeMonthDetail;
  document.getElementById("btnCloseMonthDetail2").onclick = closeMonthDetail;
  document.getElementById("monthDetailOverlay").addEventListener("click", function(e){
    if(e.target.id === "monthDetailOverlay") closeMonthDetail();
  });

  document.getElementById("cardTopService").onclick = openTopServices;
  document.getElementById("btnCloseTopServices").onclick = closeTopServices;
  document.getElementById("btnCloseTopServices2").onclick = closeTopServices;
  document.getElementById("topServicesOverlay").addEventListener("click", function(e){
    if(e.target.id === "topServicesOverlay") closeTopServices();
  });

  // record form
  document.getElementById("btnCloseRecordForm").onclick = closeRecordForm;
  document.getElementById("btnCancelRecordForm").onclick = closeRecordForm;
  document.getElementById("btnSaveRecordForm").onclick = saveRecordForm;
  document.getElementById("recordFormOverlay").addEventListener("click", function(e){
    if(e.target.id === "recordFormOverlay") closeRecordForm();
  });
  document.getElementById("btnRegenS5").onclick = function(){
    var s5auto = buildAutoS5FromCounts(state.recordServiceCounts);
    document.getElementById("s5_desc").value = s5auto;
    state.s5LastAuto = s5auto;
    updatePreview();
    showToast("已依服務項目重新帶入");
  };
  document.getElementById("btnEditCaseServices").onclick = function(){
    var caseId = state.viewingCaseId;
    closeRecordForm();
    document.getElementById("recordsOverlay").classList.remove("active");
    state.reopenRecordsCaseId = caseId;
    openForm(caseId);
  };
  document.getElementById("btnResetDefaults").onclick = function(){
    applyDefaultsToForm(true);
    showToast("已重設為預設文字");
  };
  document.getElementById("s4_hasEvent").addEventListener("change", onEventToggleChange);

  ["s1_label","s1_desc","s2_label","s2_desc","s3_label","s3_desc","s4_event","s4_handling","s5_desc","s6_desc"].forEach(function(id){
    document.getElementById(id).addEventListener("input", updatePreview);
  });
  document.getElementById("inputRecordDate").addEventListener("input", function(){
    updateRecordWeekLabel();
    updatePreview();
  });

  document.getElementById("reminderCustomInput").addEventListener("keydown", function(e){
    if(e.key==="Enter"){
      e.preventDefault();
      var v = e.target.value.trim();
      if(v){
        if(allReminderOptions().indexOf(v)===-1) state.customReminders.push(v);
        if(state.recordSelectedReminders.indexOf(v)===-1) state.recordSelectedReminders.push(v);
        e.target.value = "";
        renderReminderPicker();
        updatePreview();
      }
    }
  });

  document.getElementById("searchInput").addEventListener("input", function(e){
    state.filters.search = e.target.value;
    renderList();
  });
  document.getElementById("filterDisease").addEventListener("change", function(e){
    state.filters.disease = e.target.value; renderList();
  });
  document.getElementById("filterService").addEventListener("change", function(e){
    state.filters.service = e.target.value; renderList();
  });
  document.getElementById("filterStatus").addEventListener("change", function(e){
    state.filters.status = e.target.value; renderList();
  });

  document.getElementById("btnMenu").onclick = function(e){
    e.stopPropagation();
    document.getElementById("menuDropdown").classList.toggle("active");
  };
  document.addEventListener("click", function(){
    document.getElementById("menuDropdown").classList.remove("active");
  });
  document.getElementById("btnExport").onclick = function(){
    exportBackup();
    document.getElementById("menuDropdown").classList.remove("active");
  };
  document.getElementById("btnImportTrigger").onclick = function(){
    document.getElementById("fileImport").click();
    document.getElementById("menuDropdown").classList.remove("active");
  };
  document.getElementById("fileImport").addEventListener("change", function(e){
    var file = e.target.files[0];
    if(file) importBackup(file);
    e.target.value = "";
  });

  document.getElementById("confirmCancel").onclick = function(){
    document.getElementById("confirmOverlay").classList.remove("active");
    state.pendingConfirmAction = null;
  };
  document.getElementById("confirmOk").onclick = function(){
    if(state.pendingConfirmAction) state.pendingConfirmAction();
    document.getElementById("confirmOverlay").classList.remove("active");
    state.pendingConfirmAction = null;
  };
}

/* ========================================================
   14. 初始化
   ======================================================== */
function init(){
  showAppLoading(true);
  loadData().then(function(){
    showAppLoading(false);
    bindEvents();
    renderDashboard();
    renderList();
    if(_toastQueue){ showToast(_toastQueue); _toastQueue = ""; }
  }).catch(function(err){
    console.error("初始化資料失敗", err);
    showAppLoading(false);
    bindEvents();
    renderDashboard();
    renderList();
  });
}

if(document.readyState === "loading"){
  document.addEventListener("DOMContentLoaded", init);
}else{
  init();
}
})();
</script>
</body>
</html>

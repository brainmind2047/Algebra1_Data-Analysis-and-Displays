<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Data Analysis and Displays</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}


  .rep-top{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;margin-top:8px;}
  .rep-legend{flex:1;min-width:220px;display:flex;flex-direction:column;gap:8px;}
  .rep-cap{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);text-transform:uppercase;letter-spacing:.05em;}
  .rep-li{display:flex;align-items:center;gap:6px;font-size:15px;}
  .rep-n{margin-left:auto;white-space:nowrap;padding-left:8px;font-family:'IBM Plex Mono',monospace;font-weight:600;}
  .sw{display:inline-block;width:12px;height:12px;border-radius:3px;flex:none;}
  .rep-grid{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .rep-grid{grid-template-columns:1fr 1fr;} }
  .rep-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:14px;display:flex;flex-direction:column;gap:10px;}
  .rep-h{display:flex;align-items:center;gap:8px;font:700 16px 'Source Sans 3',sans-serif;}
  .crit{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;color:var(--card);font:700 15px Fraunces,serif;flex:none;}
  .rep-row{display:flex;gap:14px;align-items:center;}
  .rep-stats{display:flex;flex-direction:column;gap:5px;font-size:14.5px;}
  .rep-stats div{display:flex;align-items:center;gap:6px;}
  .rep-lvl{margin-top:4px;color:var(--accent-text);} .rep-lvl span{color:var(--ink-soft);font-size:13px;}
  .rep-note{font-size:13px;color:var(--ink-soft);}


  .skip-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;}
  .skip-chips .chip{min-width:48px;min-height:40px;cursor:pointer;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--retry-text);border-radius:10px;font:600 14px 'IBM Plex Mono',monospace;}
  .skip-btns{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:12px;}


  .kb-toggle{border:none;background:transparent;font-size:15px;cursor:pointer;padding:0 2px;vertical-align:middle;opacity:.7;}
  .vkb{position:fixed;left:0;right:0;bottom:0;z-index:80;background:var(--paper-2);border-top:1px solid var(--rule);box-shadow:0 -6px 20px rgba(0,0,0,.12);padding:6px 6px 8px;display:none;}
  .vkb.show{display:block;}
  .vkb-top{display:flex;justify-content:space-between;align-items:center;max-width:640px;margin:0 auto 4px;font:600 12px 'Source Sans 3',sans-serif;color:var(--ink-soft);}
  .vkb-link{border:none;background:none;color:var(--accent-text);font:600 12px 'Source Sans 3',sans-serif;cursor:pointer;text-decoration:underline;}
  .vkb-row{display:flex;gap:5px;max-width:640px;margin:0 auto 5px;}
  .vkb-k{flex:1;min-height:42px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 17px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .vkb-k.fn{font:600 13px 'Source Sans 3',sans-serif;background:var(--gold-soft);}
  .vkb-k.done{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .vkb-k:active{transform:scale(.96);}
  body.kb-open .wrap{padding-bottom:360px;}
  body.kb-open .fab{display:none;}
  .tool-bar{display:flex;gap:8px;flex-wrap:wrap;margin:-4px 0 10px;}
  .tool-btn{min-height:36px;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--ink);border-radius:18px;padding:4px 12px;font:600 13.5px 'Source Sans 3',sans-serif;cursor:pointer;}
  .tool-panel{position:fixed;z-index:85;background:var(--card);border:1px solid var(--rule);border-radius:14px;box-shadow:0 10px 30px rgba(0,0,0,.25);display:none;}
  .tool-panel.show{display:block;}
  .tp-head{display:flex;align-items:center;gap:8px;padding:8px 10px;border-bottom:1px solid var(--rule);font:600 14px 'Source Sans 3',sans-serif;}
  .tp-note{font-size:12px;color:var(--ink-soft);font-weight:500;}
  .tp-x{margin-left:auto;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:8px;min-height:32px;padding:2px 10px;cursor:pointer;font:600 13px 'Source Sans 3',sans-serif;}
  .tp-x + .tp-x{margin-left:0;}
  .calc{right:12px;bottom:84px;width:min(330px,calc(100vw - 24px));}
  body.calc-open .wrap{padding-bottom:440px;}
  body.calc-open .fab{display:none;}
  @media (max-width:640px){ .calc{left:6px;right:6px;width:auto;} .calc-keys button{min-height:36px;} }
  .calc-disp{padding:8px 12px;text-align:right;background:var(--paper-2);}
  .calc-expr{font:500 13px 'IBM Plex Mono',monospace;color:var(--ink-soft);min-height:18px;word-break:break-all;}
  .calc-res{font:600 24px 'IBM Plex Mono',monospace;color:var(--ink);word-break:break-all;}
  .calc-keys{display:grid;grid-template-columns:repeat(6,1fr);gap:5px;padding:8px;}
  .calc-keys button{min-height:40px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 14px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .calc-keys button.fn{background:var(--gold-soft);font-family:'Source Sans 3',sans-serif;font-size:13px;}
  .calc-keys button.eq{grid-column:span 2;background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .desmos{left:50%;top:50%;transform:translate(-50%,-50%);width:min(760px,calc(100vw - 16px));height:min(560px,calc(100vh - 90px));flex-direction:column;}
  .desmos.show{display:flex;}
  #desmosBox{flex:1;min-height:0;border-radius:0 0 14px 14px;overflow:hidden;}
  .desmos-msg{padding:24px;text-align:center;color:var(--ink-soft);}
  .chip[data-status="skipped"]{cursor:pointer;}
  .chip[data-status="answered"]{border-color:var(--accent-text);color:var(--accent-text);}


  button.crest-home{border:none;padding:0;position:relative;cursor:pointer;transition:transform .15s ease;}
  button.crest-home:hover,button.crest-home:focus-visible{transform:scale(1.06);outline:2px solid var(--gold);outline-offset:2px;}
  .crest-h{position:absolute;right:-7px;bottom:-7px;width:18px;height:18px;border-radius:50%;background:#F4EFDF;color:var(--navy);font:700 12px/18px 'Source Sans 3',sans-serif;text-align:center;box-shadow:0 1px 3px rgba(0,0,0,.3);}
  .brand .brand-row{position:relative;}
  .bmasw{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);display:flex;flex-shrink:0;white-space:nowrap;align-items:center;gap:6px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.25);border-radius:99px;padding:5px 14px;color:#F4EFDF;}
  .bmasw-ic{font-size:16px;} .bmasw-t{font:600 20px 'IBM Plex Mono',monospace;letter-spacing:.02em;min-width:62px;text-align:center;}
  .bmasw-b{border:none;background:rgba(255,255,255,.18);color:#F4EFDF;border-radius:50%;width:30px;height:30px;cursor:pointer;font-size:13px;}
  .bmasw.off{display:none;}
  @media (max-width:560px){ .bmasw{position:static;transform:none;margin-left:auto;padding:4px 5px 4px 8px;gap:4px;} .bmasw-ic{display:none;} .bmasw-t{font-size:16px;min-width:48px;} .bmasw-b{width:26px;height:26px;} .brand .series-name{font-size:15px;} .brand .brand-name{font-size:10.5px;} .brand .brand-row>div:not(.bmasw){min-width:0;} }
  .bmasw-done{font:600 15px 'IBM Plex Mono',monospace;color:var(--accent-text);margin:4px 0 8px;}
  .sp-fab{position:fixed;left:14px;bottom:84px;z-index:60;border:1.5px solid var(--navy-2);background:var(--card);color:var(--ink);border-radius:99px;padding:9px 14px;font:700 14px 'Source Sans 3',sans-serif;box-shadow:0 4px 14px rgba(0,0,0,.15);cursor:pointer;}
  .sp-fab.on{background:var(--navy);color:#F4EFDF;}
  body.kb-open .sp-fab{display:none;}
  .sp-canvas{position:absolute;z-index:55;display:none;touch-action:none;cursor:crosshair;}
  .sp-canvas.passive{pointer-events:none;cursor:default;}
  .sp-bar{position:fixed;top:8px;left:8px;right:8px;margin:0 auto;width:max-content;z-index:90;display:none;align-items:center;gap:6px;background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:6px 8px;box-shadow:0 6px 20px rgba(0,0,0,.2);max-width:calc(100vw - 16px);flex-wrap:wrap;justify-content:center;}
  .sp-lbl{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);margin-right:2px;}
  .sp-pen,.sp-tool{width:38px;height:38px;border-radius:10px;border:1.5px solid var(--rule);background:var(--paper);cursor:pointer;display:inline-flex;align-items:center;justify-content:center;font-size:17px;padding:0;color:var(--ink);}
  .sp-pen i{width:20px;height:20px;border-radius:50%;display:block;}
  .sp-pen.on,.sp-tool.on{border-color:var(--navy-2);box-shadow:0 0 0 3px var(--gold-soft);}
  @media (max-width:560px){ .sp-lbl{display:none;} .sp-pen,.sp-tool{width:34px;height:34px;} .sp-fab span{display:none;} }

  /* larger reading sizes */
  .chapter-eyebrow{font-size:13.5px;}
  .chapter-title{font-size:36px;line-height:1.15;}
  .chapter-sub{font-size:16.5px;}
  .tab-btn{font-size:15.5px;}
  .sec-sub{font-size:15px;}
  .qtext{font-size:19px;line-height:1.55;}
  .qnum{width:36px;height:36px;font-size:16px;}
  .opt{font-size:17.5px;padding:12px 14px;}
  .step-line{font-size:17.5px;line-height:2;}
  .blank-input{font-size:16px;}
  .sol-line{font-size:16.5px;}
  .feedback{font-size:15px;}
  .note h2{font-size:28px;}
  .note h4{font-size:19px;}
  .note p,.note li{font-size:17.5px;line-height:1.65;}
  .note .lt{font-size:15.5px;}
  .ex .exh{font-size:18px;} .ex .exl{font-size:16.5px;}
  .keybox{font-size:16.5px;}
  .ttab{font-size:15.5px;}
  .hub-card h3{font-size:21px;} .hub-card p{font-size:15.5px;} .hub-btn{font-size:15px;}
  @media (max-width:480px){ .chapter-title{font-size:30px;} .qtext{font-size:18px;} .opt,.step-line{font-size:16.5px;} .note h2{font-size:24px;} .note p,.note li{font-size:16.5px;} }

  /* v4 celebration */
  .v4conf{position:fixed;inset:0;width:100vw;height:100vh;pointer-events:none;z-index:9999;}
  .v4ban{background:linear-gradient(135deg,var(--gold-soft),var(--card));border:2px solid var(--gold);border-radius:18px;padding:18px 14px 16px;margin:-4px 0 18px;text-align:center;animation:v4pop .55s cubic-bezier(.2,1.6,.4,1);}
  @keyframes v4pop{0%{transform:scale(.6);opacity:0}100%{transform:scale(1);opacity:1}}
  .v4trophy{font-size:54px;line-height:1;animation:v4bob 1.4s ease-in-out infinite;}
  @keyframes v4bob{0%,100%{transform:translateY(0) rotate(-6deg)}50%{transform:translateY(-6px) rotate(6deg)}}
  .v4h{font-size:28px;font-weight:800;color:var(--accent-text);margin-top:6px;}
  .v4m{font-size:19px;color:var(--ink);margin-top:4px;}
  .v4pills{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:12px;}
  .v4p{font-size:16px;font-weight:700;border-radius:999px;padding:6px 12px;}
  .v4p.g{background:var(--success-soft);color:var(--success);} .v4p.o{background:var(--gold-soft);color:var(--retry-text);}
  .v4p.r{background:var(--danger-soft);color:var(--danger);} .v4p.s{background:var(--rule);color:var(--ink);}
  .v4next{margin-top:14px;} .v4go{font-size:18px !important;padding:13px 20px !important;}
  .v4rec td.v4g{color:var(--success);font-weight:700;} .v4rec td.v4o{color:var(--retry-text);font-weight:700;} .v4rec td.v4r{color:var(--danger);font-weight:700;}
  .v4rec tr.v4tot td{font-weight:800;border-top:2px solid var(--rule);}
  .v4rec th{font-size:12.5px;padding:6px 3px !important;white-space:nowrap;} .v4rec td{font-size:15px;padding:7px 3px !important;text-align:center;}
  .v4rec td:first-child,.v4rec th:first-child{text-align:left;white-space:normal;min-width:92px;max-width:150px;font-size:14.5px;}
  @media(max-width:460px){ .v4left{display:none;} }
  .v4leg{font-size:14.5px;color:var(--ink-soft);margin:2px 0 8px;line-height:1.5;}
  body.v4done .fab-q,body.v4done #qFab{display:none;}
  .v4sum{font-size:16px;margin-top:10px;}
  /* v4 larger reading sizes */
  body{font-size:18px;}
  .chapter-title{font-size:38px !important;line-height:1.15;}
  .chapter-sub{font-size:17px !important;}
  .tab-btn{font-size:16.5px !important;}
  .sec-sub{font-size:16.5px !important;}
  .qtext{font-size:21px !important;line-height:1.6 !important;}
  .qnum{width:38px !important;height:38px !important;font-size:17px !important;}
  .opt{font-size:19.5px !important;padding:13px 15px !important;}
  .step-line{font-size:19.5px !important;line-height:2.1 !important;}
  .blank-input{font-size:18px !important;min-height:40px;}
  .sol-line{font-size:18px !important;line-height:1.6;}
  .feedback{font-size:16.5px !important;}
  .note h2{font-size:29px !important;}
  .note h3{font-size:22px !important;}
  .note h4{font-size:20px !important;}
  .note p,.note li,.note td,.note th{font-size:18.5px !important;line-height:1.7 !important;}
  .ex .exh{font-size:19px !important;} .ex .exl{font-size:18px !important;}
  .keybox{font-size:18px !important;}
  .hub-card p{font-size:17.5px !important;} .hub-btn{font-size:16.5px !important;}
  .review-q,.review-ans{font-size:17.5px !important;}
  .rec-table td{font-size:16px;}
  .vkb-k{font-size:19px !important;}
  .fq{font-size:0.95em;}
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Algebra 1 · Chapter 11</div>
  <div class="chapter-title">Data Analysis and Displays</div>
  <div class="chapter-sub">Theory Notes · Practice by Section · Learning Assessment</div><div class="chapter-credit">Follows the sections of Big Ideas Math Algebra 1, Chapter 11</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · Algebra 1 · Chapter 11<br>Lessons follow the chapter and section structure of <i>Big Ideas Math Algebra 1</i> (2015), Chapter 11. Theory notes, questions, learning assessments and worked solutions are written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^[a-z]=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(-?)(\d+)(?: |\+)(\d+)\/(\d+)$/))){ if(+m[4]===0) return null; var sg=m[1]?-1:1; return {v:sg*(+m[2]+m[3]/m[4]),form:'mixed',w:sg*m[2],n:+m[3],d:+m[4]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).replace(/[−–—]/g,'-').match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Explained notes for every section of the chapter, with rules in boxes, data displays, common mistakes and worked examples.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n111\">11.1 notes</button><button class=\"hub-btn\" data-jump=\"n112\">11.2 notes</button><button class=\"hub-btn\" data-jump=\"n113\">11.3 notes</button><button class=\"hub-btn\" data-jump=\"n114\">11.4 notes</button><button class=\"hub-btn\" data-jump=\"n115\">11.5 notes</button></div></div><div class=\"hub-card\"><h3>🎯 Practice by section</h3><p>One practice sheet for each section, easy to hard, mixing multiple-choice and fill-in-the-blank questions, with real-life problems and error-analysis items.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">11.1 · Measures of Center and Variation</button><button class=\"hub-btn\" data-go=\"s2\">11.2 · Box-and-Whisker Plots</button><button class=\"hub-btn\" data-go=\"s3\">11.3 · Shapes of Distributions</button><button class=\"hub-btn\" data-go=\"s4\">11.4 · Two-Way Tables</button><button class=\"hub-btn\" data-go=\"s5\">11.5 · Choosing a Data Display</button></div></div><div class=\"hub-card\"><h3>📝 Learning assessment</h3><p>Four short assessments mixing all five sections, one per skill area. Take them in Quiz mode and open the report to see your results as pie charts.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s6\">A · Knowing and understanding</button><button class=\"hub-btn\" data-go=\"s7\">B · Investigating patterns</button><button class=\"hub-btn\" data-go=\"s8\">C · Communicating</button><button class=\"hub-btn\" data-go=\"s9\">D · Applying mathematics in real-life contexts</button><button class=\"hub-btn primary\" data-go=\"report\">📊 View my report</button></div></div></div><section class=\"note\" id=\"nintro\"><h2>About this chapter</h2><p><b>Statistics</b> is the science of collecting, organising and interpreting data. In this chapter you summarise a data set by its <b>center</b> (mean, median, mode) and its <b>spread</b> (range, interquartile range, standard deviation), draw and read <b>box-and-whisker plots</b>, describe the <b>shape</b> of a distribution, organise two categorical variables in a <b>two-way table</b>, and choose a suitable <b>data display</b>, including spotting displays that mislead.</p><h4>Maintaining mathematical proficiency</h4><p>These skills from earlier grades are used on every page. Check that each example makes sense before you start 11.1.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Skill</th><th>Key idea</th><th>Example</th></tr><tr><td>Ordering data</td><td>Write the values from least to greatest before finding a median or quartile.</td><td class=\"mono\">9, 4, 7, 4, 12 → 4, 4, 7, 9, 12</td></tr><tr><td>Mean, median, mode</td><td>Mean = sum ÷ count; median = middle value; mode = most frequent value.</td><td class=\"mono\">4, 4, 7, 9, 12: mean 7.2, median 7, mode 4</td></tr><tr><td>Square roots</td><td>√a is the non-negative number whose square is a; round as asked.</td><td class=\"mono\">√20 ≈ 4.47 ≈ 4.5</td></tr><tr><td>Fractions, decimals, percents</td><td>Part ÷ whole gives a decimal; × 100 gives a percent.</td><td class=\"mono\">18 out of 40 = 0.45 = 45%</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Warm-up example · Mean and median of 15, 8, 11, 20, 6</div><div class=\"exl\">Order: 6, 8, 11, 15, 20. The median is the middle (3rd) value: <b>11</b>.<br>Mean = (6 + 8 + 11 + 15 + 20) ÷ 5 = 60 ÷ 5 = <b>12</b>.</div></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Sheet</th><th>Section</th><th>Learning target</th></tr><tr><td>11.1</td><td>Measures of Center and Variation</td><td>I can find the mean, median, mode, range and standard deviation of a data set and describe how outliers and data transformations change them.</td></tr><tr><td>11.2</td><td>Box-and-Whisker Plots</td><td>I can find a five-number summary and interquartile range, and read, interpret and compare box-and-whisker plots.</td></tr><tr><td>11.3</td><td>Shapes of Distributions</td><td>I can describe a distribution as symmetric, skewed left or skewed right, and choose the measures of center and spread that suit its shape.</td></tr><tr><td>11.4</td><td>Two-Way Tables</td><td>I can complete two-way tables and find and interpret joint, marginal and conditional relative frequencies to look for an association.</td></tr><tr><td>11.5</td><td>Choosing a Data Display</td><td>I can classify data as qualitative or quantitative, choose a suitable display, and explain why a display is misleading.</td></tr></table></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Assessment</th><th>Skill area</th><th>What it checks</th></tr><tr><td>A</td><td>Knowing and understanding</td><td>Computing measures, quartiles and relative frequencies correctly.</td></tr><tr><td>B</td><td>Investigating patterns</td><td>How measures change when the data change, and patterns in tables.</td></tr><tr><td>C</td><td>Communicating</td><td>Vocabulary, reading displays, explaining and spotting errors.</td></tr><tr><td>D</td><td>Applying mathematics in real-life contexts</td><td>Salaries, weather, surveys, deliveries and one “is this reasonable?” judgement.</td></tr></table></div><p><b>Conventions in this chapter.</b> Standard deviation is the population standard deviation (divide by n). Quartiles are the medians of the lower and upper halves of the ordered data; when n is odd, the median itself is left out of both halves.</p><p><b>Tools:</b> ⏱ at the top times each tab (pause or reset it). ✏️ opens a scratchpad for rough work. Some questions have a 🧮 calculator button. Tap the BM badge to go back to the home page.</p><p><b>Typing answers:</b> type numbers like <span class=\"mono\">6.5</span> or <span class=\"mono\">0.75</span>, rounded as the question says. Type a percent without the % sign, e.g. <span class=\"mono\">63.2</span>.</p></section><section class=\"note\" id=\"n111\"><h2>11.1 Measures of Center and Variation</h2><p class=\"lt\"><b>Learning target:</b> I can find the mean, median, mode, range and standard deviation of a data set and describe how outliers and data transformations change them.</p><h4>Measures of center</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Measure</th><th>How to find it</th><th>Best used when…</th></tr><tr><td><b>Mean</b> x̄</td><td>Add the values and divide by how many there are.</td><td>the data have no outliers</td></tr><tr><td><b>Median</b></td><td>Order the values; take the middle one (or the mean of the two middle ones).</td><td>the data have outliers</td></tr><tr><td><b>Mode</b></td><td>The value(s) that occur most often. There can be no mode or several.</td><td>the data are repeated values or categories</td></tr></table></div><p>An <b>outlier</b> is a value much greater or much less than the other values. An outlier pulls the mean towards it but hardly moves the median.</p><div class=\"ex\"><div class=\"exh\">Worked example 1 · Effect of an outlier</div><div class=\"exl\">Ages of six cousins: 8, 9, 10, 10, 12, 41.<br>Mean = 90 ÷ 6 = 15; median = (10 + 10) ÷ 2 = 10; mode = 10.<br>The outlier 41 lifts the mean to 15, older than five of the six cousins, so the <b>median, 10</b>, describes the group better.</div></div><h4>Measures of variation</h4><p>The <b>range</b> is greatest value − least value. The <b>standard deviation</b> σ measures how much the values typically differ from the mean:</p><div class=\"keybox\"><b>Standard deviation</b> σ = √( [ (x<sub>1</sub> − x̄)<sup>2</sup> + (x<sub>2</sub> − x̄)<sup>2</sup> + … + (x<sub>n</sub> − x̄)<sup>2</sup> ] ÷ n )<br>1. Find the mean x̄. 2. Find each deviation x − x̄ and square it. 3. Find the mean of the squares. 4. Take the square root.</div><svg class=\"figsvg\" viewBox=\"0 0 330 86\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Dot plot of 2, 4, 4, 6, 9 (mean 5)</text><line x1=\"14.0\" y1=\"62.0\" x2=\"316.0\" y2=\"62.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"22.0\" y1=\"58.0\" x2=\"22.0\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"22.0\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"50.6\" y1=\"58.0\" x2=\"50.6\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"50.6\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">1</text><line x1=\"79.2\" y1=\"58.0\" x2=\"79.2\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"79.2\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"107.8\" y1=\"58.0\" x2=\"107.8\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"107.8\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">3</text><line x1=\"136.4\" y1=\"58.0\" x2=\"136.4\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"136.4\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"165.0\" y1=\"58.0\" x2=\"165.0\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"165.0\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">5</text><line x1=\"193.6\" y1=\"58.0\" x2=\"193.6\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"193.6\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"222.2\" y1=\"58.0\" x2=\"222.2\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"222.2\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">7</text><line x1=\"250.8\" y1=\"58.0\" x2=\"250.8\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"250.8\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"279.4\" y1=\"58.0\" x2=\"279.4\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"279.4\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">9</text><line x1=\"308.0\" y1=\"58.0\" x2=\"308.0\" y2=\"66.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"308.0\" y=\"75.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><circle cx=\"79.2\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"136.4\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"136.4\" cy=\"41.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"193.6\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"279.4\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/></svg><div class=\"ex\"><div class=\"exh\">Worked example 2 · Standard deviation of 2, 4, 4, 6, 9</div><div class=\"exl\">Mean x̄ = (2 + 4 + 4 + 6 + 9) ÷ 5 = 25 ÷ 5 = 5.<br>Deviations: −3, −1, −1, 1, 4; squares: 9, 1, 1, 1, 16; sum = 28.<br>σ = √(28 ÷ 5) = √5.6 ≈ <b>2.4</b>. A small σ means the values are close to the mean; a large σ means they are spread out.</div></div><h4>Data transformations</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Change to every value</th><th>Mean, median, mode</th><th>Range, standard deviation</th></tr><tr><td>add a number k</td><td>increase by k</td><td>do not change</td></tr><tr><td>multiply by k (k &gt; 0)</td><td>are multiplied by k</td><td>are multiplied by k</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Transforming data</div><div class=\"exl\">Quiz scores have mean 14, median 15, range 8 and σ = 2. Every score gets 3 bonus points.<br>New mean 17, new median 18; range stays <b>8</b> and σ stays <b>2</b> (every value moves the same amount).<br>If instead every score is doubled: mean 28, median 30, range 16, σ = 4.</div></div><div class=\"keybox\"><b>Common mistake.</b> Always <b>order</b> the data before finding the median. Also, the standard deviation uses the <b>squared</b> deviations: adding the plain deviations always gives 0.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise 11.1 →</button></div></section><section class=\"note\" id=\"n112\"><h2>11.2 Box-and-Whisker Plots</h2><p class=\"lt\"><b>Learning target:</b> I can find a five-number summary and interquartile range, and read, interpret and compare box-and-whisker plots.</p><p>A <b>box-and-whisker plot</b> shows a data set along a number line using five numbers, the <b>five-number summary</b>: minimum, first quartile Q1, median, third quartile Q3 and maximum.</p><svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">A box-and-whisker plot</text><line x1=\"20.0\" y1=\"42.0\" x2=\"20.0\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"56.8\" y1=\"42.0\" x2=\"56.8\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"93.5\" y1=\"42.0\" x2=\"93.5\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"130.2\" y1=\"42.0\" x2=\"130.2\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"167.0\" y1=\"42.0\" x2=\"167.0\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"203.8\" y1=\"42.0\" x2=\"203.8\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"240.5\" y1=\"42.0\" x2=\"240.5\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"277.2\" y1=\"42.0\" x2=\"277.2\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"42.0\" x2=\"314.0\" y2=\"88.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"42.0\" y1=\"65.0\" x2=\"86.2\" y2=\"65.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"203.8\" y1=\"65.0\" x2=\"306.6\" y2=\"65.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"42.0\" y1=\"57.0\" x2=\"42.0\" y2=\"73.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"306.6\" y1=\"57.0\" x2=\"306.6\" y2=\"73.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"86.2\" y=\"52.0\" width=\"117.6\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"144.9\" y1=\"52.0\" x2=\"144.9\" y2=\"78.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><text x=\"42.0\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">min</text><text x=\"86.2\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Q1</text><text x=\"144.9\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">median</text><text x=\"203.8\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Q3</text><text x=\"306.6\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">max</text><line x1=\"20.0\" y1=\"94.0\" x2=\"314.0\" y2=\"94.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"89.0\" x2=\"20.0\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">5</text><line x1=\"27.4\" y1=\"91.0\" x2=\"27.4\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"34.7\" y1=\"91.0\" x2=\"34.7\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"42.0\" y1=\"91.0\" x2=\"42.0\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"49.4\" y1=\"91.0\" x2=\"49.4\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"56.8\" y1=\"89.0\" x2=\"56.8\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"56.8\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"64.1\" y1=\"91.0\" x2=\"64.1\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"71.4\" y1=\"91.0\" x2=\"71.4\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"78.8\" y1=\"91.0\" x2=\"78.8\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"86.2\" y1=\"91.0\" x2=\"86.2\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"93.5\" y1=\"89.0\" x2=\"93.5\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"93.5\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">15</text><line x1=\"100.9\" y1=\"91.0\" x2=\"100.9\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"108.2\" y1=\"91.0\" x2=\"108.2\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"115.5\" y1=\"91.0\" x2=\"115.5\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"122.9\" y1=\"91.0\" x2=\"122.9\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"130.2\" y1=\"89.0\" x2=\"130.2\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"130.2\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><line x1=\"137.6\" y1=\"91.0\" x2=\"137.6\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"144.9\" y1=\"91.0\" x2=\"144.9\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"152.3\" y1=\"91.0\" x2=\"152.3\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"159.7\" y1=\"91.0\" x2=\"159.7\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"167.0\" y1=\"89.0\" x2=\"167.0\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"167.0\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">25</text><line x1=\"174.3\" y1=\"91.0\" x2=\"174.3\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"181.7\" y1=\"91.0\" x2=\"181.7\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"189.0\" y1=\"91.0\" x2=\"189.0\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"91.0\" x2=\"196.4\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"203.8\" y1=\"89.0\" x2=\"203.8\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"203.8\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"211.1\" y1=\"91.0\" x2=\"211.1\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"218.5\" y1=\"91.0\" x2=\"218.5\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"225.8\" y1=\"91.0\" x2=\"225.8\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"233.2\" y1=\"91.0\" x2=\"233.2\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"240.5\" y1=\"89.0\" x2=\"240.5\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"240.5\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">35</text><line x1=\"247.8\" y1=\"91.0\" x2=\"247.8\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"91.0\" x2=\"255.2\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"262.5\" y1=\"91.0\" x2=\"262.5\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"269.9\" y1=\"91.0\" x2=\"269.9\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"277.2\" y1=\"89.0\" x2=\"277.2\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"277.2\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><line x1=\"284.6\" y1=\"91.0\" x2=\"284.6\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"291.9\" y1=\"91.0\" x2=\"291.9\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"299.3\" y1=\"91.0\" x2=\"299.3\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"306.6\" y1=\"91.0\" x2=\"306.6\" y2=\"97.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"89.0\" x2=\"314.0\" y2=\"99.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"108.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">45</text></svg><div class=\"keybox\"><b>Finding the five-number summary</b><br>1. Order the data. 2. Find the median. 3. Q1 = median of the lower half; Q3 = median of the upper half (leave the median out when n is odd). 4. Note the least and greatest values.<br><b>Interquartile range</b> IQR = Q3 − Q1: the spread of the middle 50% of the data.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Odd number of values</div><div class=\"exl\">Data: 15, 4, 9, 22, 11, 7, 18 → ordered 4, 7, 9, 11, 15, 18, 22.<br>Median = 11. Lower half 4, 7, 9 → Q1 = 7. Upper half 15, 18, 22 → Q3 = 18.<br>Five-number summary: 4, 7, 11, 18, 22; <b>IQR = 18 − 7 = 11</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Even number of values</div><div class=\"exl\">Data: 3, 5, 6, 8, 10, 13, 14, 20.<br>Median = (8 + 10) ÷ 2 = 9. Lower half 3, 5, 6, 8 → Q1 = 5.5. Upper half 10, 13, 14, 20 → Q3 = 13.5.<br><b>IQR = 13.5 − 5.5 = 8</b>.</div></div><h4>Reading a box-and-whisker plot</h4><p>The four parts (left whisker, left part of the box, right part of the box, right whisker) each contain about <b>25%</b> of the data. A long part means those values are <b>spread out</b>, not that it holds more values.</p><div class=\"ex\"><div class=\"exh\">Worked example 3 · Comparing two plots</div><div class=\"exl\">Plot P: 10, 20, 26, 32, 40. Plot R: 12, 18, 30, 34, 38.<br>Median: R (30) is greater than P (26), so R values are typically greater.<br>IQR: P = 12, R = 16, so the middle half of R is more spread out.</div></div><div class=\"keybox\"><b>Common mistake.</b> The IQR is Q3 − Q1, not the range (max − min). And a longer whisker does <b>not</b> contain more data: every whisker holds about a quarter of the values.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise 11.2 →</button></div></section><section class=\"note\" id=\"n113\"><h2>11.3 Shapes of Distributions</h2><p class=\"lt\"><b>Learning target:</b> I can describe a distribution as symmetric, skewed left or skewed right, and choose the measures of center and spread that suit its shape.</p><p>A <b>histogram</b> or dot plot shows the <b>shape</b> of a distribution. The side with the long <b>tail</b> names the skew.</p><svg class=\"figsvg\" viewBox=\"0 0 330 140\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"55.0\" y=\"12.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Skewed left</text><rect x=\"10.0\" y=\"114.0\" width=\"15.0\" height=\"12.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><rect x=\"25.0\" y=\"102.0\" width=\"15.0\" height=\"24.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><rect x=\"40.0\" y=\"90.0\" width=\"15.0\" height=\"36.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><rect x=\"55.0\" y=\"66.0\" width=\"15.0\" height=\"60.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><rect x=\"70.0\" y=\"30.0\" width=\"15.0\" height=\"96.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><rect x=\"85.0\" y=\"54.0\" width=\"15.0\" height=\"72.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1\"/><line x1=\"7.0\" y1=\"126.0\" x2=\"103.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"165.0\" y=\"12.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Symmetric</text><rect x=\"120.0\" y=\"110.0\" width=\"15.0\" height=\"16.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><rect x=\"135.0\" y=\"78.0\" width=\"15.0\" height=\"48.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><rect x=\"150.0\" y=\"30.0\" width=\"15.0\" height=\"96.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><rect x=\"165.0\" y=\"30.0\" width=\"15.0\" height=\"96.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><rect x=\"180.0\" y=\"78.0\" width=\"15.0\" height=\"48.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><rect x=\"195.0\" y=\"110.0\" width=\"15.0\" height=\"16.0\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1\"/><line x1=\"117.0\" y1=\"126.0\" x2=\"213.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"275.0\" y=\"12.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Skewed right</text><rect x=\"230.0\" y=\"54.0\" width=\"15.0\" height=\"72.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><rect x=\"245.0\" y=\"30.0\" width=\"15.0\" height=\"96.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><rect x=\"260.0\" y=\"66.0\" width=\"15.0\" height=\"60.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><rect x=\"275.0\" y=\"90.0\" width=\"15.0\" height=\"36.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><rect x=\"290.0\" y=\"102.0\" width=\"15.0\" height=\"24.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><rect x=\"305.0\" y=\"114.0\" width=\"15.0\" height=\"12.0\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1\"/><line x1=\"227.0\" y1=\"126.0\" x2=\"323.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Shape</th><th>Looks like</th><th>Mean vs median</th><th>Describe with</th></tr><tr><td><b>Symmetric</b></td><td>left and right halves are mirror images</td><td>about equal</td><td>mean and standard deviation</td></tr><tr><td><b>Skewed left</b></td><td>tail on the left, most data on the right</td><td>mean usually &lt; median</td><td>median and IQR (five-number summary)</td></tr><tr><td><b>Skewed right</b></td><td>tail on the right, most data on the left</td><td>mean usually &gt; median</td><td>median and IQR (five-number summary)</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Choose the measures</div><div class=\"exl\">Waiting times (min): 2, 3, 3, 4, 4, 5, 6, 18.<br>Most values are small and one long tail goes to the right: <b>skewed right</b>.<br>Mean = 45 ÷ 8 ≈ 5.6, median = 4. Use the <b>median and IQR</b>, because the tail pulls the mean up.</div></div><h4>Shape in a box-and-whisker plot</h4><p>If the median is nearer Q1 and the right whisker is long, the data are skewed right. If the median is nearer Q3 and the left whisker is long, they are skewed left. Equal halves suggest a symmetric distribution.</p><div class=\"ex\"><div class=\"exh\">Worked example 2 · Comparing distributions</div><div class=\"exl\">Two symmetric score distributions both have mean 70. Class X has σ = 4 and class Y has σ = 11.<br>Same center; class Y is far more spread out, class X is more consistent.</div></div><div class=\"keybox\"><b>Common mistake.</b> “Skewed right” does not mean most data are on the right. It means the <b>tail</b> points right, so most data are on the <b>left</b>.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise 11.3 →</button></div></section><section class=\"note\" id=\"n114\"><h2>11.4 Two-Way Tables</h2><p class=\"lt\"><b>Learning target:</b> I can complete two-way tables and find and interpret joint, marginal and conditional relative frequencies to look for an association.</p><p>A <b>two-way table</b> shows the frequencies of data in two categories. Each inner entry is a <b>joint frequency</b>; the row and column totals are <b>marginal frequencies</b>.</p><div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Plays a sport</th><th style=\"text-align:center\">No sport</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Grade 9</th><td style=\"text-align:center\">36</td><td style=\"text-align:center\">24</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">Grade 10</th><td style=\"text-align:center\">30</td><td style=\"text-align:center\">30</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">66</td><td style=\"text-align:center;font-weight:700\">54</td><td style=\"text-align:center;font-weight:700\">120</td></tr></table></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Relative frequency</th><th>Divide…</th><th>Example from the table</th></tr><tr><td><b>Joint</b></td><td>a joint frequency by the grand total</td><td class=\"mono\">Grade 9 and sport: 36 ÷ 120 = 0.3</td></tr><tr><td><b>Marginal</b></td><td>a row or column total by the grand total</td><td class=\"mono\">plays a sport: 66 ÷ 120 = 0.55</td></tr><tr><td><b>Conditional</b></td><td>a joint frequency by the total of the <b>given</b> row or column</td><td class=\"mono\">sport, given Grade 9: 36 ÷ 60 = 0.6</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Complete the table</div><div class=\"exl\">Of 80 shoppers, 45 used a bag of their own. 28 of the 50 weekend shoppers used their own bag.<br>Weekday shoppers: 80 − 50 = 30. Weekday with own bag: 45 − 28 = 17.<br>Weekday without own bag: 30 − 17 = <b>13</b>; weekend without: 50 − 28 = <b>22</b>.</div></div><h4>Looking for an association</h4><p>Compare <b>conditional</b> relative frequencies. If they are clearly different, the two variables are associated; if they are about the same, there is no association.</p><div class=\"ex\"><div class=\"exh\">Worked example 2 · Is there an association?</div><div class=\"exl\">From the table: sport given Grade 9 = 36 ÷ 60 = 0.6; sport given Grade 10 = 30 ÷ 60 = 0.5.<br>60% vs 50%: Grade 9 students are somewhat more likely to play a sport, so there is an association between grade and playing a sport.</div></div><div class=\"keybox\"><b>Common mistake.</b> For a conditional relative frequency, divide by the total of the group you are <b>given</b> (“of the Grade 9 students…”), not by the grand total and not by the other total.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise 11.4 →</button></div></section><section class=\"note\" id=\"n115\"><h2>11.5 Choosing a Data Display</h2><p class=\"lt\"><b>Learning target:</b> I can classify data as qualitative or quantitative, choose a suitable display, and explain why a display is misleading.</p><p><b>Qualitative</b> (categorical) data are labels or names, such as favourite fruit or blood type. <b>Quantitative</b> data are numbers that are counted or measured, such as height or number of siblings. Numbers used as labels, like jersey numbers or zip codes, are qualitative.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Display</th><th>Data</th><th>Shows</th></tr><tr><td>Bar graph</td><td>qualitative</td><td>counts in each category</td></tr><tr><td>Circle graph</td><td>qualitative</td><td>parts of a whole (percents add to 100%)</td></tr><tr><td>Dot plot / stem-and-leaf plot</td><td>quantitative, small sets</td><td>every value and the shape</td></tr><tr><td>Histogram</td><td>quantitative</td><td>frequencies in equal intervals</td></tr><tr><td>Box-and-whisker plot</td><td>quantitative</td><td>five-number summary, spread, comparing groups</td></tr><tr><td>Line graph</td><td>quantitative over time</td><td>change over time</td></tr><tr><td>Scatter plot</td><td>two quantitative variables</td><td>the relationship between them</td></tr></table></div><h4>Misleading displays</h4><p>A display can mislead when the vertical axis does not start at 0, the intervals of a scale are unequal, pictures are scaled in two directions, or percents in a circle graph do not add to 100%.</p><svg class=\"figsvg\" viewBox=\"0 0 330 224\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Axis starts at 60, not 0</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"188.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"44.0\" y1=\"158.4\" x2=\"320.0\" y2=\"158.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"158.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">61</text><line x1=\"44.0\" y1=\"128.8\" x2=\"320.0\" y2=\"128.8\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"128.8\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">62</text><line x1=\"44.0\" y1=\"99.2\" x2=\"320.0\" y2=\"99.2\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"99.2\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">63</text><line x1=\"44.0\" y1=\"69.6\" x2=\"320.0\" y2=\"69.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"69.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">64</text><line x1=\"44.0\" y1=\"40.0\" x2=\"320.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">65</text><text x=\"48.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Members</text><rect x=\"74.4\" y=\"158.4\" width=\"77.3\" height=\"29.6\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"113.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Year 1</text><rect x=\"212.4\" y=\"69.6\" width=\"77.3\" height=\"118.4\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"251.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Year 2</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"44.0\" y1=\"188.0\" x2=\"44.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg><div class=\"ex\"><div class=\"exh\">Worked example · Why the graph above misleads</div><div class=\"exl\">The bars stand 1 and 4 units above the axis start, so Year 2 looks 4 times as tall.<br>The real change is 61 → 64 members, an increase of only 3 ÷ 61 ≈ 5%.<br>Start the vertical axis at 0 to show the true comparison.</div></div><div class=\"keybox\"><b>Common mistake.</b> A line graph should only connect values that follow in order, such as times. Do not use a line graph for categories like “favourite sport”; use a bar graph.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s5\">Practise 11.5 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Chapter checklist</h2><ul><li>I can find the mean, median, mode, range and standard deviation of a data set and describe how outliers and data transformations change them.</li><li>I can find a five-number summary and interquartile range, and read, interpret and compare box-and-whisker plots.</li><li>I can describe a distribution as symmetric, skewed left or skewed right, and choose the measures of center and spread that suit its shape.</li><li>I can complete two-way tables and find and interpret joint, marginal and conditional relative frequencies to look for an association.</li><li>I can classify data as qualitative or quantitative, choose a suitable display, and explain why a display is misleading.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn\" data-go=\"s6\">Assessment A</button><button class=\"hub-btn\" data-go=\"s7\">Assessment B</button><button class=\"hub-btn\" data-go=\"s8\">Assessment C</button><button class=\"hub-btn\" data-go=\"s9\">Assessment D</button><button class=\"hub-btn primary\" data-go=\"report\">📊 Report</button></div></section>";
var REPORT = [["s6", "A", "Knowing and understanding"], ["s7", "B", "Investigating patterns"], ["s8", "C", "Communicating"], ["s9", "D", "Applying mathematics in real-life contexts"]];
var SECTIONS = [{"id": "s1", "label": "11.1 Measures of Center and Variation", "sub": "I can find the mean, median, mode, range and standard deviation of a data set and describe how outliers and data transformations change them.", "slides": [{"kind": "mcq", "text": "Find the mean of 12, 15, 9, 18, 16.", "opts": ["17.5", "14", "15", "9"], "correct": 1, "tag": "", "sol": "Sum = 12 + 15 + 9 + 18 + 16 = 70. Mean = 70 ÷ 5 = 14. (15 is the median, 9 is the range, and 17.5 comes from dividing by 4.)"}, {"kind": "blank", "p": "Data: 7, 3, 9, 3, 12, 6, 2, 10.", "tag": "", "marks": "", "flat": [{"t": "Median = __B1__", "a": {"B1": "6.5"}}, {"t": "Mode = __B1__", "a": {"B1": "3"}}, {"t": "Range = __B1__", "a": {"B1": "10"}}], "sol": "Order: 2, 3, 3, 6, 7, 9, 10, 12. The two middle values are 6 and 7: (6 + 7) ÷ 2 = 6.5.\n3 appears twice, more than any other value.\n12 − 2 = 10."}, {"kind": "mcq", "text": "Monthly earnings ($) of six part-time workers: 820, 760, 900, 850, 790, 4,200. Which measure best describes a typical worker's earnings?", "opts": ["The median, $835", "The mean, $1,386.67", "The range, $3,440", "The mean, $835"], "correct": 0, "tag": "", "sol": "4,200 is an outlier that pulls the mean up to 8,320 ÷ 6 ≈ $1,386.67, more than five of the six workers earn. Ordered: 760, 790, 820, 850, 900, 4,200, so the median is (820 + 850) ÷ 2 = $835, which is typical."}, {"kind": "blank", "p": "Test scores: 82, 88, 75, 91, 84, 30.", "tag": "", "marks": "", "flat": [{"t": "Mean of all six scores = __B1__", "a": {"B1": "75"}}, {"t": "Mean without the outlier 30 = __B1__", "a": {"B1": "84"}}, {"t": "The outlier __B1__ the mean (raises / lowers).", "a": {"B1": "lowers"}, "expr": "words", "accept": ["lowered", "decreases", "reduces"]}], "sol": "Sum = 450, so the mean is 450 ÷ 6 = 75.\nWithout 30 the sum is 420, and 420 ÷ 5 = 84.\n75 &lt; 84, so the low outlier lowers the mean by 9 points. (The median only moves from 83 to 84.)"}, {"kind": "mcq", "text": "Data set A is 48, 50, 50, 52 and data set B is 30, 45, 55, 70. Both have mean 50. Which statement is true?", "opts": ["B has the greater standard deviation, because its values are farther from the mean", "A has the greater standard deviation, because its values are closer to the mean", "A has the greater standard deviation, because it has two equal values", "They have the same standard deviation, because they have the same mean"], "correct": 0, "tag": "", "sol": "A's values are within 2 of the mean; B's are 5 to 20 away. Standard deviation measures typical distance from the mean, so B's is greater. (σ for A ≈ 1.4, for B ≈ 14.6.)"}, {"kind": "blank", "p": "Find the standard deviation of 4, 6, 8, 10, 12.", "tag": "", "marks": "", "flat": [{"t": "Mean x̄ = __B1__", "a": {"B1": "8"}}, {"t": "Sum of the squared deviations = __B1__", "a": {"B1": "40"}}, {"t": "Standard deviation σ ≈ __B1__ (nearest tenth)", "a": {"B1": "2.8"}}], "sol": "40 ÷ 5 = 8.\nDeviations −4, −2, 0, 2, 4; squares 16, 4, 0, 4, 16; sum 40.\nσ = √(40 ÷ 5) = √8 ≈ 2.83 ≈ 2.8.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "<b>Error analysis.</b> Kofi says the median of 9, 2, 14, 5, 11 is 14, because 14 is in the middle of the list. Which is correct?", "opts": ["14 is correct: it is the middle value of the list", "Order first: 2, 5, 9, 11, 14, so the median is 11", "Order first: 2, 5, 9, 11, 14, so the median is 9", "The median is the mean, 8.2"], "correct": 2, "tag": "", "sol": "The median is the middle of the <b>ordered</b> data. Ordered: 2, 5, 9, 11, 14; the 3rd value is 9."}, {"kind": "blank", "p": "A data set has mean 20, median 18, range 12 and standard deviation 3. The number 5 is added to every value.", "tag": "", "marks": "", "flat": [{"t": "New mean = __B1__", "a": {"B1": "25"}}, {"t": "New range = __B1__", "a": {"B1": "12"}}, {"t": "New standard deviation = __B1__", "a": {"B1": "3"}}], "sol": "Adding 5 to every value adds 5 to the mean: 25.\nEvery value moves 5, so the greatest and least values keep the same gap: 12.\nThe distances from the mean do not change: σ is still 3."}, {"kind": "mcq", "text": "A data set has mean 20 and standard deviation 3. Every value is multiplied by 2. What are the new mean and standard deviation?", "opts": ["Mean 22, standard deviation 5", "Mean 40, standard deviation 6", "Mean 40, standard deviation 3", "Mean 40, standard deviation 12"], "correct": 1, "tag": "", "sol": "Multiplying every value by 2 doubles the mean (40) and doubles every distance from the mean, so σ also doubles: 6."}, {"kind": "blank", "p": "Noon temperatures (°F) on five days in Austin: 62, 65, 70, 68, 75.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__ °F", "a": {"B1": "68"}}, {"t": "Standard deviation ≈ __B1__ °F (nearest tenth)", "a": {"B1": "4.4"}}], "sol": "340 ÷ 5 = 68.\nDeviations −6, −3, 2, 0, 7; squares 36, 9, 4, 0, 49; sum 98. σ = √(98 ÷ 5) = √19.6 ≈ 4.43 ≈ 4.4 °F.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "The heights of the players on two teams have the same mean. Team A has a standard deviation of 1.2 in. and Team B has 3.5 in. Which statement is true?", "opts": ["Team B's heights are more consistent", "Team A has more players than Team B", "Team A's heights are closer together around the mean", "Team B's players are taller on average"], "correct": 2, "tag": "", "sol": "A smaller standard deviation means values lie closer to the mean, so Team A's heights are more alike. The means are equal, so neither team is taller on average, and σ says nothing about team size."}, {"kind": "blank", "p": "The dot plot shows the ages of the children at a swim class.", "tag": "", "marks": "", "flat": [{"t": "Mean age = __B1__ years", "a": {"B1": "11.8"}}, {"t": "Median age = __B1__ years", "a": {"B1": "12"}}], "sol": "15 children. Sum = 2(10) + 4(11) + 5(12) + 3(13) + 14 = 177; 177 ÷ 15 = 11.8.\nThe 8th value is the median: values 1–2 are 10, 3–6 are 11, 7–11 are 12, so the 8th is 12.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 138\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Ages of children at a swim class</text><line x1=\"14.0\" y1=\"98.0\" x2=\"316.0\" y2=\"98.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"22.0\" y1=\"94.0\" x2=\"22.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"22.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">9</text><line x1=\"69.7\" y1=\"94.0\" x2=\"69.7\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"69.7\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"117.3\" y1=\"94.0\" x2=\"117.3\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"117.3\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">11</text><line x1=\"165.0\" y1=\"94.0\" x2=\"165.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"165.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"212.7\" y1=\"94.0\" x2=\"212.7\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"212.7\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">13</text><line x1=\"260.3\" y1=\"94.0\" x2=\"260.3\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"260.3\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text><line x1=\"308.0\" y1=\"94.0\" x2=\"308.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"308.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">15</text><circle cx=\"69.7\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"41.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"260.3\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><text x=\"165.0\" y=\"130.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Age (years)</text></svg>"}, {"kind": "mcq", "text": "<b>Reasoning.</b> The mean of five numbers is 14. Four of them are 10, 12, 15 and 18. What is the fifth number?", "opts": ["14", "16", "13.75", "15"], "correct": 3, "tag": "", "sol": "Five numbers with mean 14 add to 5 × 14 = 70. 10 + 12 + 15 + 18 = 55, so the fifth is 70 − 55 = 15. (13.75 is the mean of the four.)"}, {"kind": "blank", "p": "Daily sales (number of cakes) at two bakeries over five days. Bakery A: 40, 42, 45, 43, 40. Bakery B: 20, 65, 30, 60, 35.", "tag": "", "marks": "", "flat": [{"t": "Mean of Bakery A = __B1__", "a": {"B1": "42"}}, {"t": "Range of Bakery B = __B1__", "a": {"B1": "45"}}, {"t": "Bakery __B1__ has more consistent sales (A / B).", "a": {"B1": "A"}, "expr": "words", "accept": ["bakery a"]}], "sol": "210 ÷ 5 = 42 (Bakery B's mean is also 42).\n65 − 20 = 45 (Bakery A's range is only 5).\nSame mean, but A's values vary much less, so A is more consistent."}]}, {"id": "s2", "label": "11.2 Box-and-Whisker Plots", "sub": "I can find a five-number summary and interquartile range, and read, interpret and compare box-and-whisker plots.", "slides": [{"kind": "mcq", "text": "In a box-and-whisker plot, what does the line inside the box mark?", "opts": ["The mean", "The mode", "The first quartile", "The median"], "correct": 3, "tag": "", "sol": "The box runs from Q1 to Q3 and the line inside it is the median. The mean and mode are not shown on a box-and-whisker plot."}, {"kind": "blank", "p": "Data: 12, 5, 18, 3, 9, 15, 20, 6, 11, 14, 8.", "tag": "", "marks": "", "flat": [{"t": "Minimum = __B1__, maximum = __B2__", "a": {"B1": "3", "B2": "20"}}, {"t": "Median = __B1__", "a": {"B1": "11"}}, {"t": "Q1 = __B1__", "a": {"B1": "6"}}, {"t": "Q3 = __B1__", "a": {"B1": "15"}}], "sol": "Order: 3, 5, 6, 8, 9, 11, 12, 14, 15, 18, 20. Least 3, greatest 20.\n11 values: the 6th value, 11, is the median.\nLower half 3, 5, 6, 8, 9 → Q1 = 6.\nUpper half 12, 14, 15, 18, 20 → Q3 = 15."}, {"kind": "mcq", "text": "Use the box-and-whisker plot. What is the interquartile range of the reading times?", "opts": ["28 minutes", "25 minutes", "7 minutes", "13 minutes"], "correct": 3, "tag": "", "sol": "Q1 = 18 and Q3 = 31, so IQR = 31 − 18 = 13. (28 is the range 40 − 12; 25 is the median; 7 is median − Q1.)", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Minutes spent reading</text><line x1=\"20.0\" y1=\"28.0\" x2=\"20.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"69.0\" y1=\"28.0\" x2=\"69.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"118.0\" y1=\"28.0\" x2=\"118.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"167.0\" y1=\"28.0\" x2=\"167.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"216.0\" y1=\"28.0\" x2=\"216.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"265.0\" y1=\"28.0\" x2=\"265.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"39.6\" y1=\"51.0\" x2=\"98.4\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"225.8\" y1=\"51.0\" x2=\"314.0\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"39.6\" y1=\"43.0\" x2=\"39.6\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"314.0\" y1=\"43.0\" x2=\"314.0\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"98.4\" y=\"38.0\" width=\"127.4\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"167.0\" y1=\"38.0\" x2=\"167.0\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"80.0\" x2=\"314.0\" y2=\"80.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"75.0\" x2=\"20.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"29.8\" y1=\"77.0\" x2=\"29.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"39.6\" y1=\"77.0\" x2=\"39.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"49.4\" y1=\"77.0\" x2=\"49.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"59.2\" y1=\"77.0\" x2=\"59.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"69.0\" y1=\"75.0\" x2=\"69.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"69.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">15</text><line x1=\"78.8\" y1=\"77.0\" x2=\"78.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"88.6\" y1=\"77.0\" x2=\"88.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"98.4\" y1=\"77.0\" x2=\"98.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"108.2\" y1=\"77.0\" x2=\"108.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"118.0\" y1=\"75.0\" x2=\"118.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"118.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><line x1=\"127.8\" y1=\"77.0\" x2=\"127.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"137.6\" y1=\"77.0\" x2=\"137.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"147.4\" y1=\"77.0\" x2=\"147.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"157.2\" y1=\"77.0\" x2=\"157.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"167.0\" y1=\"75.0\" x2=\"167.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"167.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">25</text><line x1=\"176.8\" y1=\"77.0\" x2=\"176.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"186.6\" y1=\"77.0\" x2=\"186.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"77.0\" x2=\"196.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"206.2\" y1=\"77.0\" x2=\"206.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"216.0\" y1=\"75.0\" x2=\"216.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"216.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"225.8\" y1=\"77.0\" x2=\"225.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"235.6\" y1=\"77.0\" x2=\"235.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"245.4\" y1=\"77.0\" x2=\"245.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"77.0\" x2=\"255.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"265.0\" y1=\"75.0\" x2=\"265.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"265.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">35</text><line x1=\"274.8\" y1=\"77.0\" x2=\"274.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"284.6\" y1=\"77.0\" x2=\"284.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"294.4\" y1=\"77.0\" x2=\"294.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"304.2\" y1=\"77.0\" x2=\"304.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"75.0\" x2=\"314.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><text x=\"167.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Minutes</text></svg>"}, {"kind": "blank", "p": "Data: 22, 15, 30, 18, 27, 35, 12, 25, 20, 28.", "tag": "", "marks": "", "flat": [{"t": "Median = __B1__", "a": {"B1": "23.5"}}, {"t": "Q1 = __B1__", "a": {"B1": "18"}}, {"t": "Q3 = __B1__", "a": {"B1": "28"}}, {"t": "IQR = __B1__", "a": {"B1": "10"}}], "sol": "Order: 12, 15, 18, 20, 22, 25, 27, 28, 30, 35. (22 + 25) ÷ 2 = 23.5.\nLower half 12, 15, 18, 20, 22 → Q1 = 18.\nUpper half 25, 27, 28, 30, 35 → Q3 = 28.\n28 − 18 = 10."}, {"kind": "mcq", "text": "About what percent of a data set lies between Q1 and the median?", "opts": ["50%", "33%", "75%", "25%"], "correct": 3, "tag": "", "sol": "The five-number summary splits the data into four parts with about 25% of the values in each, so Q1 to median holds about 25%. (Q1 to Q3 holds 50%.)"}, {"kind": "blank", "p": "Use the box-and-whisker plot of science test scores.", "tag": "", "marks": "", "flat": [{"t": "Range = __B1__", "a": {"B1": "42"}}, {"t": "IQR = __B1__", "a": {"B1": "18"}}, {"t": "Half of the scores are at or above __B1__", "a": {"B1": "74"}}], "sol": "Maximum 96 − minimum 54 = 42.\nQ3 86 − Q1 68 = 18.\nThe median is 74, so 50% of the scores are 74 or higher.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Science test scores</text><line x1=\"20.0\" y1=\"28.0\" x2=\"20.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"78.8\" y1=\"28.0\" x2=\"78.8\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"137.6\" y1=\"28.0\" x2=\"137.6\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"196.4\" y1=\"28.0\" x2=\"196.4\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"255.2\" y1=\"28.0\" x2=\"255.2\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"43.5\" y1=\"51.0\" x2=\"125.8\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"231.7\" y1=\"51.0\" x2=\"290.5\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"43.5\" y1=\"43.0\" x2=\"43.5\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"290.5\" y1=\"43.0\" x2=\"290.5\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"125.8\" y=\"38.0\" width=\"105.8\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"161.1\" y1=\"38.0\" x2=\"161.1\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"80.0\" x2=\"314.0\" y2=\"80.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"75.0\" x2=\"20.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"31.8\" y1=\"77.0\" x2=\"31.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"43.5\" y1=\"77.0\" x2=\"43.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"55.3\" y1=\"77.0\" x2=\"55.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"67.0\" y1=\"77.0\" x2=\"67.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"78.8\" y1=\"75.0\" x2=\"78.8\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"78.8\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"90.6\" y1=\"77.0\" x2=\"90.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"102.3\" y1=\"77.0\" x2=\"102.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"114.1\" y1=\"77.0\" x2=\"114.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"125.8\" y1=\"77.0\" x2=\"125.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"137.6\" y1=\"75.0\" x2=\"137.6\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"137.6\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><line x1=\"149.4\" y1=\"77.0\" x2=\"149.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"161.1\" y1=\"77.0\" x2=\"161.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"172.9\" y1=\"77.0\" x2=\"172.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"184.6\" y1=\"77.0\" x2=\"184.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"75.0\" x2=\"196.4\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"196.4\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">80</text><line x1=\"208.2\" y1=\"77.0\" x2=\"208.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"219.9\" y1=\"77.0\" x2=\"219.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"231.7\" y1=\"77.0\" x2=\"231.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"243.4\" y1=\"77.0\" x2=\"243.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"75.0\" x2=\"255.2\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"255.2\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">90</text><line x1=\"267.0\" y1=\"77.0\" x2=\"267.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"278.7\" y1=\"77.0\" x2=\"278.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"290.5\" y1=\"77.0\" x2=\"290.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"302.2\" y1=\"77.0\" x2=\"302.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"75.0\" x2=\"314.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">100</text><text x=\"167.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text></svg>"}, {"kind": "mcq", "text": "<b>Error analysis.</b> Rosa looks at the plot of science scores and says, “The right whisker is longer than the left part of the box, so more students scored between 86 and 96 than between 68 and 74.” Which reply is correct?", "opts": ["She is right: a longer part always holds more data", "The box always holds 75% of the data, so she is wrong", "Both parts hold about 25% of the scores; the whisker just shows more spread", "She is right, because 96 − 86 is greater than 74 − 68"], "correct": 2, "tag": "", "sol": "Each of the four parts of a box-and-whisker plot contains about one quarter of the data. Length shows spread, not how many values there are.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Science test scores</text><line x1=\"20.0\" y1=\"28.0\" x2=\"20.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"78.8\" y1=\"28.0\" x2=\"78.8\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"137.6\" y1=\"28.0\" x2=\"137.6\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"196.4\" y1=\"28.0\" x2=\"196.4\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"255.2\" y1=\"28.0\" x2=\"255.2\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"43.5\" y1=\"51.0\" x2=\"125.8\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"231.7\" y1=\"51.0\" x2=\"290.5\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"43.5\" y1=\"43.0\" x2=\"43.5\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"290.5\" y1=\"43.0\" x2=\"290.5\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"125.8\" y=\"38.0\" width=\"105.8\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"161.1\" y1=\"38.0\" x2=\"161.1\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"80.0\" x2=\"314.0\" y2=\"80.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"75.0\" x2=\"20.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"31.8\" y1=\"77.0\" x2=\"31.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"43.5\" y1=\"77.0\" x2=\"43.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"55.3\" y1=\"77.0\" x2=\"55.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"67.0\" y1=\"77.0\" x2=\"67.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"78.8\" y1=\"75.0\" x2=\"78.8\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"78.8\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"90.6\" y1=\"77.0\" x2=\"90.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"102.3\" y1=\"77.0\" x2=\"102.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"114.1\" y1=\"77.0\" x2=\"114.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"125.8\" y1=\"77.0\" x2=\"125.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"137.6\" y1=\"75.0\" x2=\"137.6\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"137.6\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><line x1=\"149.4\" y1=\"77.0\" x2=\"149.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"161.1\" y1=\"77.0\" x2=\"161.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"172.9\" y1=\"77.0\" x2=\"172.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"184.6\" y1=\"77.0\" x2=\"184.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"75.0\" x2=\"196.4\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"196.4\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">80</text><line x1=\"208.2\" y1=\"77.0\" x2=\"208.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"219.9\" y1=\"77.0\" x2=\"219.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"231.7\" y1=\"77.0\" x2=\"231.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"243.4\" y1=\"77.0\" x2=\"243.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"75.0\" x2=\"255.2\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"255.2\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">90</text><line x1=\"267.0\" y1=\"77.0\" x2=\"267.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"278.7\" y1=\"77.0\" x2=\"278.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"290.5\" y1=\"77.0\" x2=\"290.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"302.2\" y1=\"77.0\" x2=\"302.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"75.0\" x2=\"314.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">100</text><text x=\"167.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text></svg>"}, {"kind": "blank", "p": "The box-and-whisker plots compare two classes' math scores.", "tag": "", "marks": "", "flat": [{"t": "The median of Class A is greater by __B1__ points", "a": {"B1": "6"}}, {"t": "IQR of Class B = __B1__", "a": {"B1": "22"}}, {"t": "Class __B1__ has the greater IQR (A / B).", "a": {"B1": "B"}, "expr": "words", "accept": ["class b"]}], "sol": "Medians: A 78, B 72; 78 − 72 = 6.\nQ3 − Q1 = 88 − 66 = 22.\nClass A: 84 − 70 = 14 &lt; 22, so the middle half of Class B is more spread out.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 166\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Math test scores</text><line x1=\"70.0\" y1=\"28.0\" x2=\"70.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"118.8\" y1=\"28.0\" x2=\"118.8\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"167.6\" y1=\"28.0\" x2=\"167.6\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"216.4\" y1=\"28.0\" x2=\"216.4\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"265.2\" y1=\"28.0\" x2=\"265.2\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"118.8\" y1=\"51.0\" x2=\"167.6\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"235.9\" y1=\"51.0\" x2=\"284.7\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"118.8\" y1=\"43.0\" x2=\"118.8\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"284.7\" y1=\"43.0\" x2=\"284.7\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"167.6\" y=\"38.0\" width=\"68.3\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"206.6\" y1=\"38.0\" x2=\"206.6\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><text x=\"62.0\" y=\"51.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Class A</text><line x1=\"79.8\" y1=\"97.0\" x2=\"148.1\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"255.4\" y1=\"97.0\" x2=\"304.2\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"79.8\" y1=\"89.0\" x2=\"79.8\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"304.2\" y1=\"89.0\" x2=\"304.2\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><rect x=\"148.1\" y=\"84.0\" width=\"107.4\" height=\"26\" style=\"fill:var(--danger);fill-opacity:.14;stroke:var(--danger);stroke-width:1.8\"/><line x1=\"177.4\" y1=\"84.0\" x2=\"177.4\" y2=\"110.0\" style=\"stroke:var(--danger);stroke-width:2.4\"/><text x=\"62.0\" y=\"97.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Class B</text><line x1=\"70.0\" y1=\"126.0\" x2=\"314.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"70.0\" y1=\"121.0\" x2=\"70.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"70.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"79.8\" y1=\"123.0\" x2=\"79.8\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"89.5\" y1=\"123.0\" x2=\"89.5\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"99.3\" y1=\"123.0\" x2=\"99.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"109.0\" y1=\"123.0\" x2=\"109.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"118.8\" y1=\"121.0\" x2=\"118.8\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"118.8\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"128.6\" y1=\"123.0\" x2=\"128.6\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"138.3\" y1=\"123.0\" x2=\"138.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"148.1\" y1=\"123.0\" x2=\"148.1\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"157.8\" y1=\"123.0\" x2=\"157.8\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"167.6\" y1=\"121.0\" x2=\"167.6\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"167.6\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><line x1=\"177.4\" y1=\"123.0\" x2=\"177.4\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"187.1\" y1=\"123.0\" x2=\"187.1\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.9\" y1=\"123.0\" x2=\"196.9\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"206.6\" y1=\"123.0\" x2=\"206.6\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"216.4\" y1=\"121.0\" x2=\"216.4\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"216.4\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">80</text><line x1=\"226.2\" y1=\"123.0\" x2=\"226.2\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"235.9\" y1=\"123.0\" x2=\"235.9\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"245.7\" y1=\"123.0\" x2=\"245.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.4\" y1=\"123.0\" x2=\"255.4\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"265.2\" y1=\"121.0\" x2=\"265.2\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"265.2\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">90</text><line x1=\"275.0\" y1=\"123.0\" x2=\"275.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"284.7\" y1=\"123.0\" x2=\"284.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"294.5\" y1=\"123.0\" x2=\"294.5\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"304.2\" y1=\"123.0\" x2=\"304.2\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"121.0\" x2=\"314.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">100</text><text x=\"192.0\" y=\"158.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text></svg>"}, {"kind": "mcq", "text": "Which data set is shown by the box-and-whisker plot?", "opts": ["2, 4, 5, 7, 8, 10, 12", "2, 4, 5, 7, 8, 9, 12", "2, 3, 5, 7, 8, 9, 12", "2, 4, 5, 6, 8, 9, 12"], "correct": 1, "tag": "", "sol": "The plot shows min 2, Q1 4, median 7, Q3 9, max 12. For 2, 4, 5, 7, 8, 9, 12: median 7; lower half 2, 4, 5 → Q1 = 4; upper half 8, 9, 12 → Q3 = 9 ✓. The others have Q1 = 3, median 6, or Q3 = 10.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 86\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"20.0\" y1=\"8.0\" x2=\"20.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"62.0\" y1=\"8.0\" x2=\"62.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"104.0\" y1=\"8.0\" x2=\"104.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"146.0\" y1=\"8.0\" x2=\"146.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"188.0\" y1=\"8.0\" x2=\"188.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"230.0\" y1=\"8.0\" x2=\"230.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"272.0\" y1=\"8.0\" x2=\"272.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"8.0\" x2=\"314.0\" y2=\"54.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"62.0\" y1=\"31.0\" x2=\"104.0\" y2=\"31.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"209.0\" y1=\"31.0\" x2=\"272.0\" y2=\"31.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"62.0\" y1=\"23.0\" x2=\"62.0\" y2=\"39.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"272.0\" y1=\"23.0\" x2=\"272.0\" y2=\"39.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"104.0\" y=\"18.0\" width=\"105.0\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"167.0\" y1=\"18.0\" x2=\"167.0\" y2=\"44.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"60.0\" x2=\"314.0\" y2=\"60.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"55.0\" x2=\"20.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"41.0\" y1=\"57.0\" x2=\"41.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"62.0\" y1=\"55.0\" x2=\"62.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"62.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"83.0\" y1=\"57.0\" x2=\"83.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"104.0\" y1=\"55.0\" x2=\"104.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"104.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"125.0\" y1=\"57.0\" x2=\"125.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"146.0\" y1=\"55.0\" x2=\"146.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"146.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"167.0\" y1=\"57.0\" x2=\"167.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"188.0\" y1=\"55.0\" x2=\"188.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"188.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"209.0\" y1=\"57.0\" x2=\"209.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"230.0\" y1=\"55.0\" x2=\"230.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"230.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"251.0\" y1=\"57.0\" x2=\"251.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"272.0\" y1=\"55.0\" x2=\"272.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"272.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"293.0\" y1=\"57.0\" x2=\"293.0\" y2=\"63.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"55.0\" x2=\"314.0\" y2=\"65.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"74.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text></svg>"}, {"kind": "blank", "p": "Commute times (minutes) of 12 office workers: 14, 22, 9, 30, 18, 25, 11, 16, 35, 20, 27, 13.", "tag": "", "marks": "", "flat": [{"t": "Q1 = __B1__", "a": {"B1": "13.5"}}, {"t": "Q3 = __B1__", "a": {"B1": "26"}}, {"t": "IQR = __B1__ minutes", "a": {"B1": "12.5"}}], "sol": "Order: 9, 11, 13, 14, 16, 18, 20, 22, 25, 27, 30, 35. Lower half 9, 11, 13, 14, 16, 18 → Q1 = (13 + 14) ÷ 2 = 13.5.\nUpper half 20, 22, 25, 27, 30, 35 → Q3 = (25 + 27) ÷ 2 = 26.\n26 − 13.5 = 12.5. (The median is (18 + 20) ÷ 2 = 19.)"}, {"kind": "mcq", "text": "A box-and-whisker plot of the heights of 40 students has Q1 = 150 cm and Q3 = 165 cm. About how many students are between 150 cm and 165 cm tall?", "opts": ["20", "15", "10", "30"], "correct": 0, "tag": "", "sol": "Q1 to Q3 contains the middle 50% of the data: 50% of 40 = 20 students."}, {"kind": "blank", "p": "Data: 10, 12, 15, 18, 20, 21, 25. The value 25 is replaced by 50.", "tag": "", "marks": "", "flat": [{"t": "New maximum = __B1__", "a": {"B1": "50"}}, {"t": "New median = __B1__", "a": {"B1": "18"}}, {"t": "New IQR = __B1__", "a": {"B1": "9"}}], "sol": "The greatest value is now 50.\nStill 7 values with the same middle value: 18.\nQ1 = 12 and Q3 = 21 are unchanged, so IQR = 9. The median and IQR resist the change; only the range grows."}, {"kind": "mcq", "text": "The plots compare the battery life of two brands of phone. Which statement is true?", "opts": ["The median of Brand Y is greater than the median of Brand X", "More than half of the Brand Y batteries last less than 9 hours", "Brand X has the greater IQR", "Brand X has the greater range"], "correct": 0, "tag": "", "sol": "Medians: Y 12, X 11 ✓. Ranges: X 7, Y 10. IQRs: X 2, Y 5. Only about 25% of Brand Y batteries last less than Q1 = 9 hours.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 166\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Battery life</text><line x1=\"70.0\" y1=\"28.0\" x2=\"70.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"110.7\" y1=\"28.0\" x2=\"110.7\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"151.3\" y1=\"28.0\" x2=\"151.3\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"192.0\" y1=\"28.0\" x2=\"192.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"232.7\" y1=\"28.0\" x2=\"232.7\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"273.3\" y1=\"28.0\" x2=\"273.3\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"151.3\" y1=\"51.0\" x2=\"192.0\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"232.7\" y1=\"51.0\" x2=\"293.7\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"151.3\" y1=\"43.0\" x2=\"151.3\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"293.7\" y1=\"43.0\" x2=\"293.7\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"192.0\" y=\"38.0\" width=\"40.7\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"212.3\" y1=\"38.0\" x2=\"212.3\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><text x=\"62.0\" y=\"51.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Brand X</text><line x1=\"110.7\" y1=\"97.0\" x2=\"171.7\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"273.3\" y1=\"97.0\" x2=\"314.0\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"110.7\" y1=\"89.0\" x2=\"110.7\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"314.0\" y1=\"89.0\" x2=\"314.0\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><rect x=\"171.7\" y=\"84.0\" width=\"101.7\" height=\"26\" style=\"fill:var(--danger);fill-opacity:.14;stroke:var(--danger);stroke-width:1.8\"/><line x1=\"232.7\" y1=\"84.0\" x2=\"232.7\" y2=\"110.0\" style=\"stroke:var(--danger);stroke-width:2.4\"/><text x=\"62.0\" y=\"97.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Brand Y</text><line x1=\"70.0\" y1=\"126.0\" x2=\"314.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"70.0\" y1=\"121.0\" x2=\"70.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"70.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"90.3\" y1=\"123.0\" x2=\"90.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"110.7\" y1=\"121.0\" x2=\"110.7\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"110.7\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"131.0\" y1=\"123.0\" x2=\"131.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"151.3\" y1=\"121.0\" x2=\"151.3\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"151.3\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"171.7\" y1=\"123.0\" x2=\"171.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"192.0\" y1=\"121.0\" x2=\"192.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"192.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"212.3\" y1=\"123.0\" x2=\"212.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"232.7\" y1=\"121.0\" x2=\"232.7\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"232.7\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"253.0\" y1=\"123.0\" x2=\"253.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"273.3\" y1=\"121.0\" x2=\"273.3\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"273.3\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text><line x1=\"293.7\" y1=\"123.0\" x2=\"293.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"121.0\" x2=\"314.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">16</text><text x=\"192.0\" y=\"158.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Hours</text></svg>"}, {"kind": "blank", "p": "Points scored by a basketball player in nine games: 12, 18, 7, 22, 15, 9, 25, 15, 20.", "tag": "", "marks": "", "flat": [{"t": "Q1 = __B1__", "a": {"B1": "10.5"}}, {"t": "Q3 = __B1__", "a": {"B1": "21"}}, {"t": "IQR = __B1__", "a": {"B1": "10.5"}}], "sol": "Order: 7, 9, 12, 15, 15, 18, 20, 22, 25; median 15 (5th value). Lower half 7, 9, 12, 15 → Q1 = (9 + 12) ÷ 2 = 10.5.\nUpper half 18, 20, 22, 25 → Q3 = (20 + 22) ÷ 2 = 21.\n21 − 10.5 = 10.5."}]}, {"id": "s3", "label": "11.3 Shapes of Distributions", "sub": "I can describe a distribution as symmetric, skewed left or skewed right, and choose the measures of center and spread that suit its shape.", "slides": [{"kind": "mcq", "text": "Describe the shape of the distribution in the histogram.", "opts": ["Skewed left", "Flat (no peak)", "Symmetric", "Skewed right"], "correct": 0, "tag": "", "sol": "The tallest bars are on the right and the tail of short bars stretches to the left, so the distribution is skewed left.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Scores on an easy quiz</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"192.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"170.3\" x2=\"316.0\" y2=\"170.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"170.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"40.0\" y1=\"148.6\" x2=\"316.0\" y2=\"148.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"148.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"40.0\" y1=\"126.9\" x2=\"316.0\" y2=\"126.9\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"126.9\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"40.0\" y1=\"105.1\" x2=\"316.0\" y2=\"105.1\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"105.1\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"40.0\" y1=\"83.4\" x2=\"316.0\" y2=\"83.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"83.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"40.0\" y1=\"61.7\" x2=\"316.0\" y2=\"61.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"61.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"40.0\" y1=\"40.0\" x2=\"316.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text><text x=\"178.0\" y=\"222.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Frequency</text><rect x=\"46.0\" y=\"181.1\" width=\"45.0\" height=\"10.9\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"91.0\" y=\"170.3\" width=\"45.0\" height=\"21.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"136.0\" y=\"148.6\" width=\"45.0\" height=\"43.4\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"181.0\" y=\"116.0\" width=\"45.0\" height=\"76.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"226.0\" y=\"61.7\" width=\"45.0\" height=\"130.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"271.0\" y=\"94.3\" width=\"45.0\" height=\"97.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"46.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><text x=\"91.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><text x=\"136.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><text x=\"181.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><text x=\"226.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><text x=\"271.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><text x=\"316.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"192.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "blank", "p": "Use the histogram of daily exercise.", "tag": "", "marks": "", "flat": [{"t": "Number of adults who exercised at least 30 minutes = __B1__", "a": {"B1": "10"}}, {"t": "Shape: __B1__ (skewed left / skewed right / symmetric)", "a": {"B1": "skewed right"}, "expr": "words", "accept": ["right", "right skewed", "positively skewed"]}], "sol": "30–40, 40–50 and 50–60: 6 + 3 + 1 = 10.\nMost adults are on the left with a tail to the right: skewed right.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Daily exercise of 34 adults</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"192.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"166.7\" x2=\"316.0\" y2=\"166.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"166.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"40.0\" y1=\"141.3\" x2=\"316.0\" y2=\"141.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"141.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"40.0\" y1=\"116.0\" x2=\"316.0\" y2=\"116.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"116.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"40.0\" y1=\"90.7\" x2=\"316.0\" y2=\"90.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"90.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"40.0\" y1=\"65.3\" x2=\"316.0\" y2=\"65.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"65.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"40.0\" y1=\"40.0\" x2=\"316.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><text x=\"178.0\" y=\"222.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Minutes</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Frequency</text><rect x=\"46.0\" y=\"141.3\" width=\"45.0\" height=\"50.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"91.0\" y=\"52.7\" width=\"45.0\" height=\"139.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"136.0\" y=\"78.0\" width=\"45.0\" height=\"114.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"181.0\" y=\"116.0\" width=\"45.0\" height=\"76.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"226.0\" y=\"154.0\" width=\"45.0\" height=\"38.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"271.0\" y=\"179.3\" width=\"45.0\" height=\"12.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"46.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><text x=\"91.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><text x=\"136.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><text x=\"181.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><text x=\"226.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><text x=\"271.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><text x=\"316.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"192.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "mcq", "text": "In a distribution that is skewed left, the mean is usually", "opts": ["greater than the median", "equal to the median", "less than the median", "equal to the mode"], "correct": 2, "tag": "", "sol": "The few small values in the left tail pull the mean down, below the median."}, {"kind": "blank", "p": "Choose measures to suit the shape.", "tag": "", "marks": "", "flat": [{"t": "For a skewed distribution, the best measure of center is the __B1__.", "a": {"B1": "median"}, "expr": "words"}, {"t": "and the best measure of spread is the __B1__.", "a": {"B1": "interquartile range"}, "expr": "words", "accept": ["iqr", "interquartilerange"]}], "sol": "The median is not pulled by the values in the tail.\nThe IQR uses the middle 50% only, so it also resists the tail. (For symmetric data use the mean and standard deviation.)"}, {"kind": "mcq", "text": "Describe the shape of the distribution in the dot plot.", "opts": ["Symmetric", "Skewed left", "Skewed right", "Two separate clusters"], "correct": 0, "tag": "", "sol": "The dots form mirror images on either side of 5 (1, 3, 5, 3, 1), so the distribution is symmetric.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 138\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Goals per match</text><line x1=\"14.0\" y1=\"98.0\" x2=\"316.0\" y2=\"98.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"22.0\" y1=\"94.0\" x2=\"22.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"22.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"69.7\" y1=\"94.0\" x2=\"69.7\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"69.7\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">3</text><line x1=\"117.3\" y1=\"94.0\" x2=\"117.3\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"117.3\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"165.0\" y1=\"94.0\" x2=\"165.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"165.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">5</text><line x1=\"212.7\" y1=\"94.0\" x2=\"212.7\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"212.7\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"260.3\" y1=\"94.0\" x2=\"260.3\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"260.3\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">7</text><line x1=\"308.0\" y1=\"94.0\" x2=\"308.0\" y2=\"102.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"308.0\" y=\"111.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><circle cx=\"69.7\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"41.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"260.3\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><text x=\"165.0\" y=\"130.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Goals</text></svg>"}, {"kind": "blank", "p": "Prices of seven houses on a street (thousands of dollars): 210, 230, 240, 250, 260, 270, 640.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__ thousand dollars", "a": {"B1": "300"}}, {"t": "Median = __B1__ thousand dollars", "a": {"B1": "250"}}, {"t": "The best measure of a typical price is the __B1__ (mean / median).", "a": {"B1": "median"}, "expr": "words"}], "sol": "Sum = 2,100, and 2,100 ÷ 7 = 300.\nThe 4th value is 250.\n640 makes the data skewed right and pulls the mean above six of the seven prices, so use the median."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Mia says, “Most bars of this histogram are on the right, so it is skewed right.” Which is correct?", "opts": ["It is skewed left: the skew is named by the side of the long tail", "She is right: the skew is named by where most data are", "It cannot be described without the mean", "It is symmetric, because it has one peak"], "correct": 0, "tag": "", "sol": "The tail of short bars is on the left, so the distribution is skewed left, even though most data are on the right.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Scores on an easy quiz</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"192.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"170.3\" x2=\"316.0\" y2=\"170.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"170.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"40.0\" y1=\"148.6\" x2=\"316.0\" y2=\"148.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"148.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"40.0\" y1=\"126.9\" x2=\"316.0\" y2=\"126.9\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"126.9\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"40.0\" y1=\"105.1\" x2=\"316.0\" y2=\"105.1\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"105.1\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"40.0\" y1=\"83.4\" x2=\"316.0\" y2=\"83.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"83.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"40.0\" y1=\"61.7\" x2=\"316.0\" y2=\"61.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"61.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"40.0\" y1=\"40.0\" x2=\"316.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text><text x=\"178.0\" y=\"222.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Frequency</text><rect x=\"46.0\" y=\"181.1\" width=\"45.0\" height=\"10.9\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"91.0\" y=\"170.3\" width=\"45.0\" height=\"21.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"136.0\" y=\"148.6\" width=\"45.0\" height=\"43.4\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"181.0\" y=\"116.0\" width=\"45.0\" height=\"76.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"226.0\" y=\"61.7\" width=\"45.0\" height=\"130.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"271.0\" y=\"94.3\" width=\"45.0\" height=\"97.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"46.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><text x=\"91.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><text x=\"136.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><text x=\"181.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><text x=\"226.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><text x=\"271.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><text x=\"316.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"192.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "blank", "p": "Use the box-and-whisker plot of clinic wait times.", "tag": "", "marks": "", "flat": [{"t": "median − Q1 = __B1__ minutes", "a": {"B1": "2"}}, {"t": "Q3 − median = __B1__ minutes", "a": {"B1": "6"}}, {"t": "Shape: __B1__ (skewed left / skewed right / symmetric)", "a": {"B1": "skewed right"}, "expr": "words", "accept": ["right", "right skewed"]}], "sol": "Q1 = 12, median = 14: 14 − 12 = 2.\nQ3 = 20: 20 − 14 = 6.\nThe median is close to Q1 and the right whisker (20 to 34) is long, so the data are skewed right.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Wait times at a clinic</text><line x1=\"20.0\" y1=\"28.0\" x2=\"20.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"78.8\" y1=\"28.0\" x2=\"78.8\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"137.6\" y1=\"28.0\" x2=\"137.6\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"196.4\" y1=\"28.0\" x2=\"196.4\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"255.2\" y1=\"28.0\" x2=\"255.2\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"20.0\" y1=\"51.0\" x2=\"43.5\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"137.6\" y1=\"51.0\" x2=\"302.2\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"20.0\" y1=\"43.0\" x2=\"20.0\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"302.2\" y1=\"43.0\" x2=\"302.2\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"43.5\" y=\"38.0\" width=\"94.1\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"67.0\" y1=\"38.0\" x2=\"67.0\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"80.0\" x2=\"314.0\" y2=\"80.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"75.0\" x2=\"20.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"31.8\" y1=\"77.0\" x2=\"31.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"43.5\" y1=\"77.0\" x2=\"43.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"55.3\" y1=\"77.0\" x2=\"55.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"67.0\" y1=\"77.0\" x2=\"67.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"78.8\" y1=\"75.0\" x2=\"78.8\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"78.8\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">15</text><line x1=\"90.6\" y1=\"77.0\" x2=\"90.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"102.3\" y1=\"77.0\" x2=\"102.3\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"114.1\" y1=\"77.0\" x2=\"114.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"125.8\" y1=\"77.0\" x2=\"125.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"137.6\" y1=\"75.0\" x2=\"137.6\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"137.6\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><line x1=\"149.4\" y1=\"77.0\" x2=\"149.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"161.1\" y1=\"77.0\" x2=\"161.1\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"172.9\" y1=\"77.0\" x2=\"172.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"184.6\" y1=\"77.0\" x2=\"184.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"75.0\" x2=\"196.4\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"196.4\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">25</text><line x1=\"208.2\" y1=\"77.0\" x2=\"208.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"219.9\" y1=\"77.0\" x2=\"219.9\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"231.7\" y1=\"77.0\" x2=\"231.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"243.4\" y1=\"77.0\" x2=\"243.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"75.0\" x2=\"255.2\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"255.2\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"267.0\" y1=\"77.0\" x2=\"267.0\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"278.7\" y1=\"77.0\" x2=\"278.7\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"290.5\" y1=\"77.0\" x2=\"290.5\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"302.2\" y1=\"77.0\" x2=\"302.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"75.0\" x2=\"314.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">35</text><text x=\"167.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Minutes</text></svg>"}, {"kind": "mcq", "text": "Two classes' test scores are both symmetric with mean 72. Class P has a standard deviation of 6 and class Q has a standard deviation of 12. Which is true?", "opts": ["Class Q scored higher on average", "The two distributions are identical", "Class Q's scores are more spread out than class P's", "Class P's scores are more spread out"], "correct": 2, "tag": "", "sol": "Same center (72), but a larger σ means more spread, so class Q's scores vary more."}, {"kind": "blank", "p": "Goals scored by a soccer team in nine matches: 1, 2, 2, 3, 3, 3, 4, 4, 5. The distribution is symmetric, so use the mean and standard deviation.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__", "a": {"B1": "3"}}, {"t": "Standard deviation ≈ __B1__ (nearest tenth)", "a": {"B1": "1.2"}}], "sol": "27 ÷ 9 = 3.\nSquared deviations 4, 1, 1, 0, 0, 0, 1, 1, 4; sum 12. σ = √(12 ÷ 9) ≈ 1.15 ≈ 1.2.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "Which data set is symmetric?", "opts": ["1, 1, 2, 2, 3, 9", "2, 3, 3, 4, 8, 10", "1, 7, 8, 8, 9, 9", "3, 5, 6, 6, 7, 9"], "correct": 3, "tag": "", "sol": "3, 5, 6, 6, 7, 9 is balanced about 6: 3 and 9, 5 and 7, 6 and 6 are the same distance from 6. The second set is skewed right and the third skewed left; the fourth is not balanced."}, {"kind": "blank", "p": "The table shows the hours of sleep reported by 30 students.", "tag": "", "marks": "", "flat": [{"t": "Mean ≈ __B1__ hours (nearest tenth)", "a": {"B1": "7.9"}}, {"t": "Median = __B1__ hours", "a": {"B1": "8"}}], "sol": "Sum = 6(3) + 7(8) + 8(10) + 9(6) + 10(3) = 238; 238 ÷ 30 ≈ 7.93 ≈ 7.9.\nThe median is the mean of the 15th and 16th values. Running totals: 3, 11, 21, so both are 8.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><table class=\"ttab\"><tr><th style=\"text-align:center\">Hours of sleep</th><th style=\"text-align:center\">6</th><th style=\"text-align:center\">7</th><th style=\"text-align:center\">8</th><th style=\"text-align:center\">9</th><th style=\"text-align:center\">10</th></tr><tr><td style=\"text-align:center\">Students</td><td style=\"text-align:center\">3</td><td style=\"text-align:center\">8</td><td style=\"text-align:center\">10</td><td style=\"text-align:center\">6</td><td style=\"text-align:center\">3</td></tr></table></div>", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "Household incomes in a town are strongly skewed right. A newspaper wants to report a “typical” income. What should it report?", "opts": ["The range, because it shows all incomes", "The median, because the few very high incomes do not pull it up", "The mean, because it uses every income", "The mean, because skewed data have no median"], "correct": 1, "tag": "", "sol": "In data skewed right the high incomes pull the mean above what most households earn; the median is the better typical value."}, {"kind": "blank", "p": "Ages of ten people at a family dinner: 2, 4, 5, 35, 38, 40, 41, 42, 44, 45.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__", "a": {"B1": "29.6"}}, {"t": "Median = __B1__", "a": {"B1": "39"}}, {"t": "Shape: __B1__ (skewed left / skewed right / symmetric)", "a": {"B1": "skewed left"}, "expr": "words", "accept": ["left", "left skewed", "negatively skewed"]}], "sol": "Sum = 296, and 296 ÷ 10 = 29.6.\n(38 + 40) ÷ 2 = 39.\nMost ages are high with a tail of small values (the children) to the left: skewed left, so the mean is less than the median."}]}, {"id": "s4", "label": "11.4 Two-Way Tables", "sub": "I can complete two-way tables and find and interpret joint, marginal and conditional relative frequencies to look for an association.", "slides": [{"kind": "mcq", "text": "In a two-way table, what are the totals in the last row and last column called?", "opts": ["Outliers", "Conditional relative frequencies", "Marginal frequencies", "Joint frequencies"], "correct": 2, "tag": "", "sol": "The entries inside the table are joint frequencies; the row and column totals around the edge (margin) are marginal frequencies."}, {"kind": "blank", "p": "Complete the two-way table about students in two grades and whether they own a pet.", "tag": "", "marks": "", "flat": [{"t": "Grade 9, no pet = __B1__", "a": {"B1": "32"}}, {"t": "Total with a pet = __B1__", "a": {"B1": "63"}}, {"t": "Grand total = __B1__", "a": {"B1": "120"}}], "sol": "60 − 28 = 32.\n28 + 35 = 63.\n60 + 60 = 120 (also 63 + 57 = 120 ✓).", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Pet: yes</th><th style=\"text-align:center\">Pet: no</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Grade 9</th><td style=\"text-align:center\">28</td><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">Grade 10</th><td style=\"text-align:center\">35</td><td style=\"text-align:center\">25</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td><td style=\"text-align:center;font-weight:700\">57</td><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td></tr></table></div>"}, {"kind": "mcq", "text": "Use the library card table. What is the joint relative frequency of people who are under 18 and have a card?", "opts": ["0.36", "0.6", "0.18", "0.3"], "correct": 2, "tag": "", "sol": "Joint relative frequency = 36 ÷ 200 = 0.18. (0.6 = 36 ÷ 60 is a conditional relative frequency; 0.3 = 60 ÷ 200 is a marginal one.)", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Library card survey</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Card</th><th style=\"text-align:center\">No card</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Under 18</th><td style=\"text-align:center\">36</td><td style=\"text-align:center\">24</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">18 and over</th><td style=\"text-align:center\">84</td><td style=\"text-align:center\">56</td><td style=\"text-align:center\">140</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">120</td><td style=\"text-align:center;font-weight:700\">80</td><td style=\"text-align:center;font-weight:700\">200</td></tr></table></div>"}, {"kind": "blank", "p": "Use the library card table.", "tag": "", "marks": "", "flat": [{"t": "Marginal relative frequency of people with a card = __B1__", "a": {"B1": "0.6"}}, {"t": "Marginal relative frequency of people 18 and over = __B1__", "a": {"B1": "0.7"}}], "sol": "120 ÷ 200 = 0.6.\n140 ÷ 200 = 0.7.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Library card survey</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Card</th><th style=\"text-align:center\">No card</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Under 18</th><td style=\"text-align:center\">36</td><td style=\"text-align:center\">24</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">18 and over</th><td style=\"text-align:center\">84</td><td style=\"text-align:center\">56</td><td style=\"text-align:center\">140</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">120</td><td style=\"text-align:center;font-weight:700\">80</td><td style=\"text-align:center;font-weight:700\">200</td></tr></table></div>"}, {"kind": "mcq", "text": "Use the library card table. Given that a person is 18 or over, what is the conditional relative frequency that they have a card?", "opts": ["0.84", "0.42", "0.7", "0.6"], "correct": 3, "tag": "", "sol": "Divide by the total of the given group: 84 ÷ 140 = 0.6. (84 ÷ 200 = 0.42 is joint; 84 ÷ 120 = 0.7 is conditioned on having a card.)", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Library card survey</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Card</th><th style=\"text-align:center\">No card</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Under 18</th><td style=\"text-align:center\">36</td><td style=\"text-align:center\">24</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">18 and over</th><td style=\"text-align:center\">84</td><td style=\"text-align:center\">56</td><td style=\"text-align:center\">140</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">120</td><td style=\"text-align:center;font-weight:700\">80</td><td style=\"text-align:center;font-weight:700\">200</td></tr></table></div>"}, {"kind": "blank", "p": "Use the table of homework habits and test results.", "tag": "", "marks": "", "flat": [{"t": "Conditional relative frequency of passing, given homework daily = __B1__", "a": {"B1": "0.9"}}, {"t": "Conditional relative frequency of passing, given not daily = __B1__", "a": {"B1": "0.6"}}, {"t": "Is there an association between homework and passing? __B1__ (yes / no)", "a": {"B1": "yes"}, "expr": "words"}], "sol": "72 ÷ 80 = 0.9.\n42 ÷ 70 = 0.6.\n90% compared with 60% is a clear difference, so yes: students who do homework daily are more likely to pass.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Homework and test results</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Pass</th><th style=\"text-align:center\">Fail</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Homework daily</th><td style=\"text-align:center\">72</td><td style=\"text-align:center\">8</td><td style=\"text-align:center\">80</td></tr><tr><th style=\"text-align:center\">Not daily</th><td style=\"text-align:center\">42</td><td style=\"text-align:center\">28</td><td style=\"text-align:center\">70</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">114</td><td style=\"text-align:center;font-weight:700\">36</td><td style=\"text-align:center;font-weight:700\">150</td></tr></table></div>"}, {"kind": "mcq", "text": "<b>Error analysis.</b> Using the homework table, Ben says the conditional relative frequency of passing, given that a student does homework daily, is 72 ÷ 114 ≈ 0.63. Which is correct?", "opts": ["Divide by the fail total: 72 ÷ 36 = 2", "Divide by the homework-daily total: 72 ÷ 80 = 0.9", "Divide by the grand total: 72 ÷ 150 = 0.48", "His answer is right: 72 ÷ 114 ≈ 0.63"], "correct": 1, "tag": "", "sol": "“Given homework daily” means the group is the 80 homework-daily students. Ben divided by the pass total, which answers a different question (homework daily, given passed).", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Homework and test results</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Pass</th><th style=\"text-align:center\">Fail</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Homework daily</th><td style=\"text-align:center\">72</td><td style=\"text-align:center\">8</td><td style=\"text-align:center\">80</td></tr><tr><th style=\"text-align:center\">Not daily</th><td style=\"text-align:center\">42</td><td style=\"text-align:center\">28</td><td style=\"text-align:center\">70</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">114</td><td style=\"text-align:center;font-weight:700\">36</td><td style=\"text-align:center;font-weight:700\">150</td></tr></table></div>"}, {"kind": "blank", "p": "Of 90 people at a movie, 50 bought popcorn. 30 people bought popcorn and a drink, and 25 bought a drink but no popcorn.", "tag": "", "marks": "", "flat": [{"t": "Popcorn but no drink = __B1__", "a": {"B1": "20"}}, {"t": "Total who bought a drink = __B1__", "a": {"B1": "55"}}, {"t": "Bought neither = __B1__", "a": {"B1": "15"}}], "sol": "50 − 30 = 20.\n30 + 25 = 55.\nNo popcorn: 90 − 50 = 40; of these 25 bought a drink, so 40 − 25 = 15 bought neither."}, {"kind": "mcq", "text": "The table shows relative frequencies for people's workout times. Given that a person works out in the morning, what is the conditional relative frequency that they listen to music?", "opts": ["0.40", "0.55", "0.30", "0.75"], "correct": 3, "tag": "", "sol": "0.30 ÷ 0.40 = 0.75. (0.30 is the joint relative frequency, 0.55 the marginal for music, 0.40 the marginal for morning.)", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Workouts (relative frequencies)</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Music</th><th style=\"text-align:center\">No music</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Morning</th><td style=\"text-align:center\">0.3</td><td style=\"text-align:center\">0.1</td><td style=\"text-align:center\">0.4</td></tr><tr><th style=\"text-align:center\">Evening</th><td style=\"text-align:center\">0.25</td><td style=\"text-align:center\">0.35</td><td style=\"text-align:center\">0.6</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">0.55</td><td style=\"text-align:center;font-weight:700\">0.45</td><td style=\"text-align:center;font-weight:700\">1</td></tr></table></div>"}, {"kind": "blank", "p": "Use the workout table.", "tag": "", "marks": "", "flat": [{"t": "Marginal relative frequency of evening workouts = __B1__", "a": {"B1": "0.6"}}, {"t": "Given no music, the conditional relative frequency of an evening workout ≈ __B1__ (nearest hundredth)", "a": {"B1": "0.78"}}], "sol": "Row total for evening: 0.60.\n0.35 ÷ 0.45 ≈ 0.778 ≈ 0.78.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Workouts (relative frequencies)</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Music</th><th style=\"text-align:center\">No music</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Morning</th><td style=\"text-align:center\">0.3</td><td style=\"text-align:center\">0.1</td><td style=\"text-align:center\">0.4</td></tr><tr><th style=\"text-align:center\">Evening</th><td style=\"text-align:center\">0.25</td><td style=\"text-align:center\">0.35</td><td style=\"text-align:center\">0.6</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">0.55</td><td style=\"text-align:center;font-weight:700\">0.45</td><td style=\"text-align:center;font-weight:700\">1</td></tr></table></div>"}, {"kind": "mcq", "text": "Using the library card table, which statement is true?", "opts": ["Adults are more likely to have a card, because 84 is greater than 36", "There is no association: 60% of each age group has a card", "There is an association, because the totals 60 and 140 are different", "Under-18s are more likely to have a card, because 36 ÷ 120 is less than 84 ÷ 120"], "correct": 1, "tag": "", "sol": "Compare conditional relative frequencies: under 18, 36 ÷ 60 = 0.6; 18 and over, 84 ÷ 140 = 0.6. They are equal, so age and having a card are not associated. Raw counts are misleading because the groups are different sizes.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Library card survey</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Card</th><th style=\"text-align:center\">No card</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Under 18</th><td style=\"text-align:center\">36</td><td style=\"text-align:center\">24</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">18 and over</th><td style=\"text-align:center\">84</td><td style=\"text-align:center\">56</td><td style=\"text-align:center\">140</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">120</td><td style=\"text-align:center;font-weight:700\">80</td><td style=\"text-align:center;font-weight:700\">200</td></tr></table></div>"}, {"kind": "blank", "p": "Use the homework table. Round to the nearest tenth of a percent.", "tag": "", "marks": "", "flat": [{"t": "Of the students who passed, __B1__% did homework daily", "a": {"B1": "63.2"}}, {"t": "__B1__% of all students did not do homework daily and failed", "a": {"B1": "18.7"}}], "sol": "72 ÷ 114 ≈ 0.6316 ≈ 63.2%.\n28 ÷ 150 ≈ 0.1867 ≈ 18.7%.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Homework and test results</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Pass</th><th style=\"text-align:center\">Fail</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Homework daily</th><td style=\"text-align:center\">72</td><td style=\"text-align:center\">8</td><td style=\"text-align:center\">80</td></tr><tr><th style=\"text-align:center\">Not daily</th><td style=\"text-align:center\">42</td><td style=\"text-align:center\">28</td><td style=\"text-align:center\">70</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">114</td><td style=\"text-align:center;font-weight:700\">36</td><td style=\"text-align:center;font-weight:700\">150</td></tr></table></div>", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "In a survey of shoppers, 40% are adults over 60, and 30% of those adults prefer tea. What is the joint relative frequency of shoppers who are adults over 60 and prefer tea?", "opts": ["0.12", "0.10", "0.30", "0.70"], "correct": 0, "tag": "", "sol": "30% of 40% = 0.3 × 0.4 = 0.12 of all shoppers."}, {"kind": "blank", "p": "Complete the table, then answer.", "tag": "", "marks": "", "flat": [{"t": "Students living 2 miles or less who ride the bus = __B1__", "a": {"B1": "8"}}, {"t": "Given a student lives over 2 miles away, the relative frequency of riding the bus = __B1__", "a": {"B1": "0.75"}}, {"t": "Given a student rides the bus, the relative frequency of living over 2 miles away ≈ __B1__ (nearest hundredth)", "a": {"B1": "0.79"}}], "sol": "38 − 30 = 8 (and 8 + 32 = 40 ✓).\n30 ÷ 40 = 0.75.\n30 ÷ 38 ≈ 0.789 ≈ 0.79.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">How 80 students get to school</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Bus</th><th style=\"text-align:center\">No bus</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Over 2 miles</th><td style=\"text-align:center\">30</td><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td><td style=\"text-align:center\">40</td></tr><tr><th style=\"text-align:center\">2 miles or less</th><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td><td style=\"text-align:center\">32</td><td style=\"text-align:center\">40</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">38</td><td style=\"text-align:center;color:var(--danger);font-weight:700\">?</td><td style=\"text-align:center;font-weight:700\">80</td></tr></table></div>"}]}, {"id": "s5", "label": "11.5 Choosing a Data Display", "sub": "I can classify data as qualitative or quantitative, choose a suitable display, and explain why a display is misleading.", "slides": [{"kind": "mcq", "text": "Which of these data are quantitative?", "opts": ["The students' zip codes", "The favourite colours of the students", "The students' eye colours", "The heights of the students in a class"], "correct": 3, "tag": "", "sol": "Heights are measured numbers. Colours are categories, and zip codes are numbers used as labels, so those are qualitative."}, {"kind": "blank", "p": "Classify each data set as qualitative or quantitative.", "tag": "", "marks": "", "flat": [{"t": "a) Types of pets owned: __B1__", "a": {"B1": "qualitative"}, "expr": "words", "accept": ["categorical"]}, {"t": "b) Number of siblings: __B1__", "a": {"B1": "quantitative"}, "expr": "words", "accept": ["numerical"]}, {"t": "c) Jersey numbers of a team: __B1__", "a": {"B1": "qualitative"}, "expr": "words", "accept": ["categorical"]}], "sol": "Pet types are names of categories.\nSiblings are counted, so the data are numbers you can average.\nJersey numbers are labels; averaging them means nothing."}, {"kind": "mcq", "text": "Which display is best for showing how a city's population changed each year from 2015 to 2025?", "opts": ["Circle graph", "Two-way table", "Box-and-whisker plot", "Line graph"], "correct": 3, "tag": "", "sol": "Change over time is shown best by a line graph."}, {"kind": "blank", "p": "Choose a display.", "tag": "", "marks": "", "flat": [{"t": "To show what percent of a family's budget goes to each category: __B1__ (circle graph / line graph)", "a": {"B1": "circle graph"}, "expr": "words", "accept": ["circle", "pie chart", "pie graph", "pie"]}, {"t": "To show whether hours studied and test scores are related: __B1__ (scatter plot / bar graph)", "a": {"B1": "scatter plot"}, "expr": "words", "accept": ["scatter", "scatterplot", "scatter graph"]}], "sol": "Parts of a whole (100%) suit a circle graph.\nTwo quantitative variables measured on the same people suit a scatter plot."}, {"kind": "mcq", "text": "Why is this bar graph misleading?", "opts": ["The bars should be different widths", "It uses quantitative data, so it should be a circle graph", "The bars should touch, as in a histogram", "The vertical axis starts at 50, so the difference looks much bigger than it is"], "correct": 3, "tag": "", "sol": "The axis starts at 50 instead of 0, so Store B's bar looks three times as tall even though sales differ by only $4 thousand.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 224\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Weekly sales</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"188.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"44.0\" y1=\"166.9\" x2=\"320.0\" y2=\"166.9\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"166.9\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">51</text><line x1=\"44.0\" y1=\"145.7\" x2=\"320.0\" y2=\"145.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"145.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">52</text><line x1=\"44.0\" y1=\"124.6\" x2=\"320.0\" y2=\"124.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"124.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">53</text><line x1=\"44.0\" y1=\"103.4\" x2=\"320.0\" y2=\"103.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"103.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">54</text><line x1=\"44.0\" y1=\"82.3\" x2=\"320.0\" y2=\"82.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"82.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">55</text><line x1=\"44.0\" y1=\"61.1\" x2=\"320.0\" y2=\"61.1\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"61.1\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">56</text><line x1=\"44.0\" y1=\"40.0\" x2=\"320.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">57</text><text x=\"48.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">$ thousand</text><rect x=\"74.4\" y=\"145.7\" width=\"77.3\" height=\"42.3\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"113.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Store A</text><rect x=\"212.4\" y=\"61.1\" width=\"77.3\" height=\"126.9\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"251.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Store B</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"44.0\" y1=\"188.0\" x2=\"44.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "blank", "p": "Use the misleading bar graph of weekly sales.", "tag": "", "marks": "", "flat": [{"t": "Store B's sales are greater by $__B1__ thousand", "a": {"B1": "4"}}, {"t": "In the graph, Store B's bar looks __B1__ times as tall as Store A's", "a": {"B1": "3"}}], "sol": "$56 thousand − $52 thousand = $4 thousand (about 8% more).\nAbove the axis start, the bars are 56 − 50 = 6 and 52 − 50 = 2 units tall; 6 ÷ 2 = 3.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 224\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Weekly sales</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"188.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"44.0\" y1=\"166.9\" x2=\"320.0\" y2=\"166.9\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"166.9\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">51</text><line x1=\"44.0\" y1=\"145.7\" x2=\"320.0\" y2=\"145.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"145.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">52</text><line x1=\"44.0\" y1=\"124.6\" x2=\"320.0\" y2=\"124.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"124.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">53</text><line x1=\"44.0\" y1=\"103.4\" x2=\"320.0\" y2=\"103.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"103.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">54</text><line x1=\"44.0\" y1=\"82.3\" x2=\"320.0\" y2=\"82.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"82.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">55</text><line x1=\"44.0\" y1=\"61.1\" x2=\"320.0\" y2=\"61.1\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"61.1\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">56</text><line x1=\"44.0\" y1=\"40.0\" x2=\"320.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"39.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">57</text><text x=\"48.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">$ thousand</text><rect x=\"74.4\" y=\"145.7\" width=\"77.3\" height=\"42.3\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"113.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Store A</text><rect x=\"212.4\" y=\"61.1\" width=\"77.3\" height=\"126.9\" style=\"fill:var(--accent-text);fill-opacity:.45;stroke:var(--accent-text);stroke-width:1.1\"/><text x=\"251.0\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Store B</text><line x1=\"44.0\" y1=\"188.0\" x2=\"320.0\" y2=\"188.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"44.0\" y1=\"188.0\" x2=\"44.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "mcq", "text": "<b>Error analysis.</b> Leo used a line graph to show the favourite sport of each student in his class. What is wrong?", "opts": ["He should have used a box-and-whisker plot", "Sports are categories with no order, so a bar graph is better", "He should have used a scatter plot", "Nothing; line graphs suit any data"], "correct": 1, "tag": "", "sol": "A line graph joins values that follow one another, such as times. Favourite sports are qualitative, so a bar graph (or circle graph) is better. A box-and-whisker plot needs quantitative data."}, {"kind": "blank", "p": "Choose a display.", "tag": "", "marks": "", "flat": [{"t": "To show every value of a small quantitative data set and its shape: __B1__ (dot plot / circle graph)", "a": {"B1": "dot plot"}, "expr": "words", "accept": ["dotplot", "dot"]}, {"t": "To compare the five-number summaries of two large data sets: __B1__ (box-and-whisker plots / circle graphs)", "a": {"B1": "box-and-whisker plots"}, "expr": "words", "accept": ["box-and-whisker plot", "box plots", "box plot", "boxplot", "boxplots", "box and whisker plots", "box and whisker plot"]}], "sol": "A dot plot shows one dot per value.\nBox-and-whisker plots show min, Q1, median, Q3 and max side by side."}, {"kind": "mcq", "text": "Which display is misleading?", "opts": ["A circle graph with sections labelled 45%, 30%, 20% and 15%", "A line graph with the months in order along the horizontal axis", "A bar graph with a vertical axis from 0 to 100 in steps of 10", "A histogram with intervals 0–10, 10–20, 20–30"], "correct": 0, "tag": "", "sol": "45 + 30 + 20 + 15 = 110%, but a circle graph shows parts of one whole, which must add to 100%."}, {"kind": "blank", "p": "The line graph shows the number of bicycles a shop sold each month.", "tag": "", "marks": "", "flat": [{"t": "The greatest increase from one month to the next is __B1__ bicycles", "a": {"B1": "20"}}, {"t": "It happens from March to __B1__.", "a": {"B1": "April"}, "expr": "words", "accept": ["apr"]}, {"t": "Sales fell by __B1__ bicycles from May to June", "a": {"B1": "20"}}], "sol": "Increases: 10, 10, 20, 10; the greatest is 60 − 40 = 20.\nMarch 40 → April 60.\n70 − 50 = 20.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 224\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Bicycles sold</text><line x1=\"40.0\" y1=\"188.0\" x2=\"318.0\" y2=\"188.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"188.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"169.5\" x2=\"318.0\" y2=\"169.5\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"169.5\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"40.0\" y1=\"151.0\" x2=\"318.0\" y2=\"151.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"151.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><line x1=\"40.0\" y1=\"132.5\" x2=\"318.0\" y2=\"132.5\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"132.5\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"40.0\" y1=\"114.0\" x2=\"318.0\" y2=\"114.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"114.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><line x1=\"40.0\" y1=\"95.5\" x2=\"318.0\" y2=\"95.5\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"95.5\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><line x1=\"40.0\" y1=\"77.0\" x2=\"318.0\" y2=\"77.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"77.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><line x1=\"40.0\" y1=\"58.5\" x2=\"318.0\" y2=\"58.5\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"58.5\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><line x1=\"40.0\" y1=\"40.0\" x2=\"318.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">80</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Bicycles</text><polyline points=\"63.2,151.0 109.5,132.5 155.8,114.0 202.2,77.0 248.5,58.5 294.8,95.5\" style=\"fill:none;stroke:var(--accent-text);stroke-width:2\"/><circle cx=\"63.2\" cy=\"151.0\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"63.2\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Jan</text><circle cx=\"109.5\" cy=\"132.5\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"109.5\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Feb</text><circle cx=\"155.8\" cy=\"114.0\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"155.8\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Mar</text><circle cx=\"202.2\" cy=\"77.0\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"202.2\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Apr</text><circle cx=\"248.5\" cy=\"58.5\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"248.5\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">May</text><circle cx=\"294.8\" cy=\"95.5\" r=\"3.6\" style=\"fill:var(--card);stroke:var(--accent-text);stroke-width:1.8\"/><text x=\"294.8\" y=\"200.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Jun</text><line x1=\"40.0\" y1=\"188.0\" x2=\"318.0\" y2=\"188.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"188.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "mcq", "text": "A teacher wants to compare the distributions of test scores for two classes of 30 students. Which display is best?", "opts": ["A circle graph for each class", "Two box-and-whisker plots on the same scale", "A two-way table", "A line graph"], "correct": 1, "tag": "", "sol": "Box-and-whisker plots on one number line let you compare medians, IQRs and ranges directly. Scores are quantitative, so circle graphs and two-way tables do not fit."}, {"kind": "blank", "p": "A company's yearly profit rose from $40 million to $48 million. Its advert shows a bar graph whose vertical axis starts at $38 million.", "tag": "", "marks": "", "flat": [{"t": "Actual percent increase = __B1__%", "a": {"B1": "20"}}, {"t": "In the advert, the second bar looks __B1__ times as tall as the first", "a": {"B1": "5"}}], "sol": "(48 − 40) ÷ 40 = 0.2 = 20%.\nAbove $38 million the bars are 10 and 2 units tall; 10 ÷ 2 = 5, which makes the growth look far bigger."}, {"kind": "mcq", "text": "A coach records the 400 m times (seconds) of 30 runners and wants to show how many runners fall in the intervals 50–55, 55–60, 60–65 and so on. Which display should she use?", "opts": ["Histogram", "Two-way table", "Line graph", "Circle graph"], "correct": 0, "tag": "", "sol": "Frequencies of quantitative data in equal intervals are shown by a histogram."}, {"kind": "blank", "p": "A poster shows money bags for a charity's donations. The 2025 bag is twice as tall and twice as wide as the 2024 bag, because donations doubled.", "tag": "", "marks": "", "flat": [{"t": "The 2025 bag's area is __B1__ times the 2024 bag's area", "a": {"B1": "4"}}, {"t": "but the donations are only __B1__ times as large", "a": {"B1": "2"}}], "sol": "2 × 2 = 4: scaling in both directions multiplies the area by 4.\nDonations doubled, so the picture exaggerates the growth. Only one dimension should be doubled."}]}, {"id": "s6", "label": "Assessment A", "sub": "Knowing and understanding", "slides": [{"kind": "mcq", "text": "Find the median of 14, 9, 21, 17, 9, 12.", "opts": ["9", "13.7", "19", "13"], "correct": 3, "tag": "", "sol": "Order: 9, 9, 12, 14, 17, 21. The two middle values are 12 and 14: (12 + 14) ÷ 2 = 13. (19 averages the middle of the unordered list; 13.7 is the mean.)"}, {"kind": "blank", "p": "Data: 48, 52, 55, 45, 60.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__", "a": {"B1": "52"}}, {"t": "Range = __B1__", "a": {"B1": "15"}}], "sol": "260 ÷ 5 = 52.\n60 − 45 = 15."}, {"kind": "mcq", "text": "Find the interquartile range of 3, 7, 8, 10, 12, 15, 19, 21.", "opts": ["9.5", "12", "18", "11"], "correct": 0, "tag": "", "sol": "Lower half 3, 7, 8, 10 → Q1 = 7.5. Upper half 12, 15, 19, 21 → Q3 = 17. IQR = 17 − 7.5 = 9.5. (18 is the range; 11 is the median.)"}, {"kind": "blank", "p": "Find the standard deviation of 5, 7, 10, 13, 15.", "tag": "", "marks": "", "flat": [{"t": "Mean = __B1__", "a": {"B1": "10"}}, {"t": "σ ≈ __B1__ (nearest tenth)", "a": {"B1": "3.7"}}], "sol": "50 ÷ 5 = 10.\nSquared deviations 25, 9, 0, 9, 25; sum 68. σ = √(68 ÷ 5) = √13.6 ≈ 3.69 ≈ 3.7.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "Describe the shape of the histogram.", "opts": ["Skewed left", "Symmetric", "Flat (no peak)", "Skewed right"], "correct": 0, "tag": "", "sol": "The bars are tallest on the right with a tail to the left: skewed left.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Test scores</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"192.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"166.7\" x2=\"316.0\" y2=\"166.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"166.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"40.0\" y1=\"141.3\" x2=\"316.0\" y2=\"141.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"141.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"40.0\" y1=\"116.0\" x2=\"316.0\" y2=\"116.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"116.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><line x1=\"40.0\" y1=\"90.7\" x2=\"316.0\" y2=\"90.7\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"90.7\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"40.0\" y1=\"65.3\" x2=\"316.0\" y2=\"65.3\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"65.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">10</text><line x1=\"40.0\" y1=\"40.0\" x2=\"316.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><text x=\"178.0\" y=\"222.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Score</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Frequency</text><rect x=\"46.0\" y=\"179.3\" width=\"45.0\" height=\"12.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"91.0\" y=\"154.0\" width=\"45.0\" height=\"38.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"136.0\" y=\"128.7\" width=\"45.0\" height=\"63.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"181.0\" y=\"90.7\" width=\"45.0\" height=\"101.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"226.0\" y=\"52.7\" width=\"45.0\" height=\"139.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"271.0\" y=\"116.0\" width=\"45.0\" height=\"76.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"46.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><text x=\"91.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><text x=\"136.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><text x=\"181.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><text x=\"226.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">80</text><text x=\"271.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">90</text><text x=\"316.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">100</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"192.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "blank", "p": "Use the phone survey table.", "tag": "", "marks": "", "flat": [{"t": "Given a person is a teen, the relative frequency of choosing Brand A = __B1__", "a": {"B1": "0.75"}}, {"t": "Joint relative frequency of adults who chose Brand B = __B1__", "a": {"B1": "0.4"}}], "sol": "45 ÷ 60 = 0.75.\n60 ÷ 150 = 0.4.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Phone survey</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Brand A</th><th style=\"text-align:center\">Brand B</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Teens</th><td style=\"text-align:center\">45</td><td style=\"text-align:center\">15</td><td style=\"text-align:center\">60</td></tr><tr><th style=\"text-align:center\">Adults</th><td style=\"text-align:center\">30</td><td style=\"text-align:center\">60</td><td style=\"text-align:center\">90</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">75</td><td style=\"text-align:center;font-weight:700\">75</td><td style=\"text-align:center;font-weight:700\">150</td></tr></table></div>"}, {"kind": "mcq", "text": "Which display is best for showing the percent of students in each school club?", "opts": ["Circle graph", "Box-and-whisker plot", "Scatter plot", "Line graph"], "correct": 0, "tag": "", "sol": "Percents of a whole by category suit a circle graph."}, {"kind": "blank", "p": "Use the box-and-whisker plot.", "tag": "", "marks": "", "flat": [{"t": "Median = __B1__ hours", "a": {"B1": "32"}}, {"t": "IQR = __B1__ hours", "a": {"B1": "12"}}], "sol": "The line in the box is at 32.\n38 − 26 = 12.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 120\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Weekly hours of practice</text><line x1=\"20.0\" y1=\"28.0\" x2=\"20.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"118.0\" y1=\"28.0\" x2=\"118.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"216.0\" y1=\"28.0\" x2=\"216.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"74.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"20.0\" y1=\"51.0\" x2=\"78.8\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"196.4\" y1=\"51.0\" x2=\"314.0\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"20.0\" y1=\"43.0\" x2=\"20.0\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"314.0\" y1=\"43.0\" x2=\"314.0\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"78.8\" y=\"38.0\" width=\"117.6\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"137.6\" y1=\"38.0\" x2=\"137.6\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><line x1=\"20.0\" y1=\"80.0\" x2=\"314.0\" y2=\"80.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"20.0\" y1=\"75.0\" x2=\"20.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"20.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><line x1=\"39.6\" y1=\"77.0\" x2=\"39.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"59.2\" y1=\"77.0\" x2=\"59.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"78.8\" y1=\"77.0\" x2=\"78.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"98.4\" y1=\"77.0\" x2=\"98.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"118.0\" y1=\"75.0\" x2=\"118.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"118.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"137.6\" y1=\"77.0\" x2=\"137.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"157.2\" y1=\"77.0\" x2=\"157.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"176.8\" y1=\"77.0\" x2=\"176.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"196.4\" y1=\"77.0\" x2=\"196.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"216.0\" y1=\"75.0\" x2=\"216.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"216.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><line x1=\"235.6\" y1=\"77.0\" x2=\"235.6\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"255.2\" y1=\"77.0\" x2=\"255.2\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"274.8\" y1=\"77.0\" x2=\"274.8\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"294.4\" y1=\"77.0\" x2=\"294.4\" y2=\"83.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"75.0\" x2=\"314.0\" y2=\"85.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"94.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><text x=\"167.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Hours</text></svg>"}, {"kind": "mcq", "text": "Which measure is least affected by an outlier?", "opts": ["Standard deviation", "Mean", "Interquartile range", "Range"], "correct": 2, "tag": "", "sol": "The IQR uses only the middle 50% of the data, so one extreme value hardly changes it. The mean, range and standard deviation all use the extreme value."}]}, {"id": "s7", "label": "Assessment B", "sub": "Investigating patterns", "slides": [{"kind": "blank", "p": "Data: 3, 5, 9, 11. Then 10 is added to every value.", "tag": "", "marks": "", "flat": [{"t": "Original mean = __B1__", "a": {"B1": "7"}}, {"t": "New mean = __B1__", "a": {"B1": "17"}}, {"t": "New range = __B1__", "a": {"B1": "8"}}], "sol": "28 ÷ 4 = 7.\nAdding 10 to every value adds 10 to the mean: 17.\nThe range stays 11 − 3 = 8."}, {"kind": "mcq", "text": "A data set has mean 7 and standard deviation 2. Every value is multiplied by 3. What are the new mean and standard deviation?", "opts": ["Mean 21, standard deviation 2", "Mean 21, standard deviation 6", "Mean 10, standard deviation 5", "Mean 10, standard deviation 2"], "correct": 1, "tag": "", "sol": "Multiplying by 3 multiplies both the mean and every distance from the mean by 3."}, {"kind": "blank", "p": "Look at the mean of 1, 2, 3, …, n.", "tag": "", "marks": "", "flat": [{"t": "n = 9: mean = __B1__", "a": {"B1": "5"}}, {"t": "n = 20: mean = __B1__", "a": {"B1": "10.5"}}, {"t": "In general, the mean is __B1__ (in terms of n)", "a": {"B1": "(n+1)/2"}, "expr": true, "accept": ["n/2+1/2", "0.5n+0.5", "0.5(n+1)"]}], "sol": "45 ÷ 9 = 5.\n210 ÷ 20 = 10.5.\nThe values pair up (1 and n, 2 and n − 1, …), each pair averaging (n + 1) ÷ 2."}, {"kind": "mcq", "text": "A value equal to the mean is added to a data set whose values are not all equal. What happens?", "opts": ["The mean stays the same and the standard deviation decreases", "The mean stays the same and the standard deviation increases", "The mean and the standard deviation both stay the same", "The mean increases and the standard deviation stays the same"], "correct": 0, "tag": "", "sol": "The sum rises by exactly the mean, so the mean is unchanged. The new value adds 0 to the sum of squared deviations but n grows, so σ decreases. Example: 4, 6, 8, 10, 12 has σ ≈ 2.83; adding 8 gives σ ≈ 2.58."}, {"kind": "blank", "p": "Six values have a mean of 15.", "tag": "", "marks": "", "flat": [{"t": "Their sum = __B1__", "a": {"B1": "90"}}, {"t": "If 22 is added as a seventh value, the new mean = __B1__", "a": {"B1": "16"}}, {"t": "The seventh value that would make the mean 17 = __B1__", "a": {"B1": "29"}}], "sol": "6 × 15 = 90.\n(90 + 22) ÷ 7 = 112 ÷ 7 = 16.\n7 × 17 = 119, and 119 − 90 = 29."}, {"kind": "mcq", "text": "In a survey, 40% of group P and 40% of group Q answer “yes”. What does this suggest?", "opts": ["There is no association between the group and the answer", "Group P is more likely to answer yes", "Nothing, unless the groups are the same size", "There is a strong association"], "correct": 0, "tag": "", "sol": "Equal conditional relative frequencies mean the answer does not depend on the group, so there is no association."}, {"kind": "blank", "p": "Data: 2, 4, 6, 8, 10, 12, 14, 16, 18, 20.", "tag": "", "marks": "", "flat": [{"t": "Median = __B1__", "a": {"B1": "11"}}, {"t": "Q1 = __B1__", "a": {"B1": "6"}}, {"t": "Q3 = __B1__", "a": {"B1": "16"}}], "sol": "(10 + 12) ÷ 2 = 11.\nLower half 2, 4, 6, 8, 10 → 6.\nUpper half 12, 14, 16, 18, 20 → 16. (IQR = 16 − 6 = 10.)"}, {"kind": "mcq", "text": "In a distribution that is skewed right, which is usually true?", "opts": ["The mean is greater than the median", "The mean equals the median", "The mean is less than the median", "The median is greater than the maximum"], "correct": 0, "tag": "", "sol": "The long right tail pulls the mean up, above the median."}, {"kind": "blank", "p": "Data: 4, 8, 9, 12, 15. Then 15 is replaced by 40.", "tag": "", "marks": "", "flat": [{"t": "New mean = __B1__", "a": {"B1": "14.6"}}, {"t": "The mean increases by __B1__", "a": {"B1": "5"}}, {"t": "The median changes by __B1__", "a": {"B1": "0"}}], "sol": "Sum = 4 + 8 + 9 + 12 + 40 = 73; 73 ÷ 5 = 14.6.\nThe sum rose by 25, so the mean rose by 25 ÷ 5 = 5 (from 9.6).\nThe middle value is still 9, so the median changes by 0."}]}, {"id": "s8", "label": "Assessment C", "sub": "Communicating", "slides": [{"kind": "mcq", "text": "What does the standard deviation of a data set describe?", "opts": ["The value that occurs most often", "The difference between the greatest and least values", "The middle value of the ordered data", "How much the values typically differ from the mean"], "correct": 3, "tag": "", "sol": "σ is a measure of variation from the mean. The others describe the median, the range and the mode."}, {"kind": "blank", "p": "Complete each sentence.", "tag": "", "marks": "", "flat": [{"t": "Data that are counted or measured are __B1__ (qualitative / quantitative).", "a": {"B1": "quantitative"}, "expr": "words", "accept": ["numerical"]}, {"t": "An entry inside a two-way table is a __B1__ frequency (joint / marginal).", "a": {"B1": "joint"}, "expr": "words"}], "sol": "Counts and measurements are numbers: quantitative.\nInside entries count one category of each variable at once: joint frequencies."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Zara found the median of 7, 2, 9, 4, 12, 5 as (9 + 4) ÷ 2 = 6.5, using the two middle numbers as written. Which is correct?", "opts": ["Her answer is correct", "The median is the mean, 6.5", "Order first: the median is 7", "Order first: 2, 4, 5, 7, 9, 12, so the median is 6"], "correct": 3, "tag": "", "sol": "Ordered: 2, 4, 5, 7, 9, 12. The two middle values are 5 and 7: (5 + 7) ÷ 2 = 6. (The mean is 39 ÷ 6 = 6.5, which only matches by coincidence.)"}, {"kind": "blank", "p": "Explain what a box-and-whisker plot shows.", "tag": "", "marks": "", "flat": [{"t": "The box shows the middle __B1__ percent of the data", "a": {"B1": "50"}}, {"t": "Each whisker shows about __B1__ percent of the data", "a": {"B1": "25"}}], "sol": "From Q1 to Q3: 50%.\nMin to Q1 and Q3 to max each hold about 25%."}, {"kind": "mcq", "text": "Which statement about histograms and bar graphs is correct?", "opts": ["A histogram and a bar graph are the same display", "A histogram shows categories and its bars have gaps", "A histogram shows quantitative data in intervals and its bars touch", "A bar graph is used only for data over time"], "correct": 2, "tag": "", "sol": "Histograms group numbers into equal intervals with no gaps; bar graphs show separate categories."}, {"kind": "blank", "p": "<b>Error analysis.</b> Using the homework table, Omar found the conditional relative frequency of failing, given not doing homework daily, as 28 ÷ 36.", "tag": "", "marks": "", "flat": [{"t": "The correct denominator is __B1__", "a": {"B1": "70"}}, {"t": "The correct value is __B1__", "a": {"B1": "0.4"}}], "sol": "The given group is the 70 students who do not do homework daily.\n28 ÷ 70 = 0.4. (28 ÷ 36 is the relative frequency of not doing homework, given failing.)", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">Homework and test results</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Pass</th><th style=\"text-align:center\">Fail</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Homework daily</th><td style=\"text-align:center\">72</td><td style=\"text-align:center\">8</td><td style=\"text-align:center\">80</td></tr><tr><th style=\"text-align:center\">Not daily</th><td style=\"text-align:center\">42</td><td style=\"text-align:center\">28</td><td style=\"text-align:center\">70</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">114</td><td style=\"text-align:center;font-weight:700\">36</td><td style=\"text-align:center;font-weight:700\">150</td></tr></table></div>"}, {"kind": "mcq", "text": "Which statement describes the dot plot correctly?", "opts": ["It is skewed left, so the mean describes the center better", "It is skewed right, so the median describes the center better than the mean", "It is skewed right, so the mean is less than the median", "It is symmetric, so the mean equals the median"], "correct": 1, "tag": "", "sol": "Most households have 0–2 pets with a tail to the right: skewed right. The tail pulls the mean (27 ÷ 18 = 1.5) above the median (1), so the median is the better center.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Pets per household</text><line x1=\"14.0\" y1=\"110.0\" x2=\"316.0\" y2=\"110.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"22.0\" y1=\"106.0\" x2=\"22.0\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"22.0\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"69.7\" y1=\"106.0\" x2=\"69.7\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"69.7\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">1</text><line x1=\"117.3\" y1=\"106.0\" x2=\"117.3\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"117.3\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">2</text><line x1=\"165.0\" y1=\"106.0\" x2=\"165.0\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"165.0\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">3</text><line x1=\"212.7\" y1=\"106.0\" x2=\"212.7\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"212.7\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"260.3\" y1=\"106.0\" x2=\"260.3\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"260.3\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">5</text><line x1=\"308.0\" y1=\"106.0\" x2=\"308.0\" y2=\"114.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"308.0\" y=\"123.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">6</text><circle cx=\"22.0\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"22.0\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"22.0\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"22.0\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"22.0\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"22.0\" cy=\"41.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"65.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"69.7\" cy=\"53.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"117.3\" cy=\"77.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"89.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"212.7\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><circle cx=\"308.0\" cy=\"101.0\" r=\"4.6\" style=\"fill:var(--accent-text);fill-opacity:.75;stroke:var(--accent-text)\"/><text x=\"165.0\" y=\"142.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Pets</text></svg>"}, {"kind": "blank", "p": "Complete each sentence.", "tag": "", "marks": "", "flat": [{"t": "In a distribution that is skewed left, the tail is on the __B1__ (left / right).", "a": {"B1": "left"}, "expr": "words"}, {"t": "and the mean is usually __B1__ the median (less than / greater than).", "a": {"B1": "less than"}, "expr": "words", "accept": ["lessthan", "smaller than", "below"]}], "sol": "The skew is named by the tail.\nThe small values in the tail pull the mean down."}, {"kind": "mcq", "text": "Which change would make a bar graph comparing two values misleading?", "opts": ["Using equal steps on the vertical scale", "Making all bars the same width", "Labelling both axes", "Starting the vertical axis at a large number instead of 0"], "correct": 3, "tag": "", "sol": "Cutting off the bottom of the axis exaggerates differences between the bars. The other choices make a graph clearer."}]}, {"id": "s9", "label": "Assessment D", "sub": "Applying mathematics in real-life contexts", "slides": [{"kind": "mcq", "text": "Salaries (thousands of dollars) at a small firm: 32, 35, 38, 40, 42, 45, 250. Which gives the best “typical” salary?", "opts": ["Range, $218,000", "Median, $40,000", "Mean, $40,000", "Mean, about $68,860"], "correct": 1, "tag": "", "sol": "The owner's $250,000 is an outlier. Mean = 482 ÷ 7 ≈ 68.86 thousand, more than six of the seven salaries. The median (4th value) is $40,000."}, {"kind": "blank", "p": "Monthly rainfall (inches) over five months. City P: 3, 4, 5, 4, 4. City Q: 1, 7, 2, 8, 2. Both means are 4.", "tag": "", "marks": "", "flat": [{"t": "σ for City P ≈ __B1__ (nearest tenth)", "a": {"B1": "0.6"}}, {"t": "σ for City Q ≈ __B1__ (nearest tenth)", "a": {"B1": "2.9"}}, {"t": "City __B1__ has more consistent rainfall (P / Q).", "a": {"B1": "P"}, "expr": "words", "accept": ["city p"]}], "sol": "Squared deviations 1, 0, 1, 0, 0; sum 2. √(2 ÷ 5) = √0.4 ≈ 0.63 ≈ 0.6.\nSquared deviations 9, 9, 4, 16, 4; sum 42. √(42 ÷ 5) = √8.4 ≈ 2.90 ≈ 2.9.\nThe smaller σ belongs to City P.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "Use the table of how shoppers paid. Which shoppers were more likely to pay by card?", "opts": ["Weekend shoppers: 60% paid by card, compared with 40% on weekdays", "Weekday shoppers: about 67% paid by card, compared with 60% at weekends", "Neither: the table cannot show this", "Neither: both groups paid by card 60% of the time"], "correct": 1, "tag": "", "sol": "Conditional relative frequencies: weekday 120 ÷ 180 ≈ 0.67; weekend 72 ÷ 120 = 0.6. Weekday shoppers were more likely to pay by card.", "fig": "<div class=\"tscroll\" style=\"max-width:420px;margin:0 auto\"><div style=\"text-align:center;font-weight:700;margin-bottom:4px\">How 300 shoppers paid</div><table class=\"ttab\"><tr><th style=\"text-align:center\"></th><th style=\"text-align:center\">Card</th><th style=\"text-align:center\">Cash</th><th style=\"text-align:center\">Total</th></tr><tr><th style=\"text-align:center\">Weekday</th><td style=\"text-align:center\">120</td><td style=\"text-align:center\">60</td><td style=\"text-align:center\">180</td></tr><tr><th style=\"text-align:center\">Weekend</th><td style=\"text-align:center\">72</td><td style=\"text-align:center\">48</td><td style=\"text-align:center\">120</td></tr><tr><th style=\"text-align:center\">Total</th><td style=\"text-align:center;font-weight:700\">192</td><td style=\"text-align:center;font-weight:700\">108</td><td style=\"text-align:center;font-weight:700\">300</td></tr></table></div>"}, {"kind": "blank", "p": "The plots compare delivery times for two companies.", "tag": "", "marks": "", "flat": [{"t": "QuickBox's median is greater by __B1__ hours", "a": {"B1": "3"}}, {"t": "IQR for QuickBox = __B1__ hours", "a": {"B1": "14"}}, {"t": "__B1__ has the more consistent middle half of delivery times (FastShip / QuickBox).", "a": {"B1": "FastShip"}, "expr": "words", "accept": ["fast ship"]}], "sol": "28 − 25 = 3.\n34 − 20 = 14.\nFastShip's IQR is 30 − 22 = 8, smaller than 14.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 166\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Delivery times</text><line x1=\"70.0\" y1=\"28.0\" x2=\"70.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"104.9\" y1=\"28.0\" x2=\"104.9\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"139.7\" y1=\"28.0\" x2=\"139.7\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"174.6\" y1=\"28.0\" x2=\"174.6\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"209.4\" y1=\"28.0\" x2=\"209.4\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"244.3\" y1=\"28.0\" x2=\"244.3\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"279.1\" y1=\"28.0\" x2=\"279.1\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"314.0\" y1=\"28.0\" x2=\"314.0\" y2=\"120.0\" style=\"stroke:var(--rule);stroke-width:0.7\"/><line x1=\"104.9\" y1=\"51.0\" x2=\"139.7\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"209.4\" y1=\"51.0\" x2=\"305.3\" y2=\"51.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"104.9\" y1=\"43.0\" x2=\"104.9\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"305.3\" y1=\"43.0\" x2=\"305.3\" y2=\"59.0\" style=\"stroke:var(--accent-text);stroke-width:1.8\"/><rect x=\"139.7\" y=\"38.0\" width=\"69.7\" height=\"26\" style=\"fill:var(--accent-text);fill-opacity:.14;stroke:var(--accent-text);stroke-width:1.8\"/><line x1=\"165.9\" y1=\"38.0\" x2=\"165.9\" y2=\"64.0\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/><text x=\"62.0\" y=\"51.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">FastShip</text><line x1=\"78.7\" y1=\"97.0\" x2=\"122.3\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"244.3\" y1=\"97.0\" x2=\"261.7\" y2=\"97.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"78.7\" y1=\"89.0\" x2=\"78.7\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><line x1=\"261.7\" y1=\"89.0\" x2=\"261.7\" y2=\"105.0\" style=\"stroke:var(--danger);stroke-width:1.8\"/><rect x=\"122.3\" y=\"84.0\" width=\"122.0\" height=\"26\" style=\"fill:var(--danger);fill-opacity:.14;stroke:var(--danger);stroke-width:1.8\"/><line x1=\"192.0\" y1=\"84.0\" x2=\"192.0\" y2=\"110.0\" style=\"stroke:var(--danger);stroke-width:2.4\"/><text x=\"62.0\" y=\"97.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">QuickBox</text><line x1=\"70.0\" y1=\"126.0\" x2=\"314.0\" y2=\"126.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"70.0\" y1=\"121.0\" x2=\"70.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"70.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">14</text><line x1=\"78.7\" y1=\"123.0\" x2=\"78.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"87.4\" y1=\"123.0\" x2=\"87.4\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"96.1\" y1=\"123.0\" x2=\"96.1\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"104.9\" y1=\"121.0\" x2=\"104.9\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"104.9\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">18</text><line x1=\"113.6\" y1=\"123.0\" x2=\"113.6\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"122.3\" y1=\"123.0\" x2=\"122.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"131.0\" y1=\"123.0\" x2=\"131.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"139.7\" y1=\"121.0\" x2=\"139.7\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"139.7\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">22</text><line x1=\"148.4\" y1=\"123.0\" x2=\"148.4\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"157.1\" y1=\"123.0\" x2=\"157.1\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"165.9\" y1=\"123.0\" x2=\"165.9\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"174.6\" y1=\"121.0\" x2=\"174.6\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"174.6\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">26</text><line x1=\"183.3\" y1=\"123.0\" x2=\"183.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"192.0\" y1=\"123.0\" x2=\"192.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"200.7\" y1=\"123.0\" x2=\"200.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"209.4\" y1=\"121.0\" x2=\"209.4\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"209.4\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><line x1=\"218.1\" y1=\"123.0\" x2=\"218.1\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"226.9\" y1=\"123.0\" x2=\"226.9\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"235.6\" y1=\"123.0\" x2=\"235.6\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"244.3\" y1=\"121.0\" x2=\"244.3\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"244.3\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">34</text><line x1=\"253.0\" y1=\"123.0\" x2=\"253.0\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"261.7\" y1=\"123.0\" x2=\"261.7\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"270.4\" y1=\"123.0\" x2=\"270.4\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"279.1\" y1=\"121.0\" x2=\"279.1\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"279.1\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">38</text><line x1=\"287.9\" y1=\"123.0\" x2=\"287.9\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"296.6\" y1=\"123.0\" x2=\"296.6\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"305.3\" y1=\"123.0\" x2=\"305.3\" y2=\"129.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><line x1=\"314.0\" y1=\"121.0\" x2=\"314.0\" y2=\"131.0\" style=\"stroke:var(--ink-soft);stroke-width:1.1\"/><text x=\"314.0\" y=\"140.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10.5px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">42</text><text x=\"192.0\" y=\"158.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Hours</text></svg>"}, {"kind": "mcq", "text": "<b>Is this reasonable?</b> Ana records the number of pets in seven households: 0, 1, 2, 1, 3, 0, 2. She reports that the mean is 9. What should she conclude?", "opts": ["Not reasonable: the mean must be a whole number, so it is 1", "Reasonable, because the data include zeros", "Reasonable: 9 is the total number of pets", "Not reasonable: a mean cannot be greater than the largest value, 3; the mean is about 1.3"], "correct": 3, "tag": "", "sol": "9 is the sum; she forgot to divide by 7. 9 ÷ 7 ≈ 1.3. A mean always lies between the least and greatest values, so 9 is a warning sign."}, {"kind": "blank", "p": "Use the histogram of runners' ages.", "tag": "", "marks": "", "flat": [{"t": "Number of runners = __B1__", "a": {"B1": "60"}}, {"t": "Percent of runners aged 50 or older = __B1__%", "a": {"B1": "25"}}], "sol": "12 + 18 + 15 + 9 + 6 = 60.\n9 + 6 = 15, and 15 ÷ 60 = 0.25 = 25%.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Ages of 10K runners</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"192.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">0</text><line x1=\"40.0\" y1=\"161.6\" x2=\"316.0\" y2=\"161.6\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"161.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">4</text><line x1=\"40.0\" y1=\"131.2\" x2=\"316.0\" y2=\"131.2\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"131.2\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">8</text><line x1=\"40.0\" y1=\"100.8\" x2=\"316.0\" y2=\"100.8\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"100.8\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">12</text><line x1=\"40.0\" y1=\"70.4\" x2=\"316.0\" y2=\"70.4\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"70.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">16</text><line x1=\"40.0\" y1=\"40.0\" x2=\"316.0\" y2=\"40.0\" style=\"stroke:var(--rule);stroke-width:0.8\"/><text x=\"35.0\" y=\"40.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><text x=\"178.0\" y=\"222.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Age (years)</text><text x=\"44.0\" y=\"30.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">Frequency</text><rect x=\"46.0\" y=\"100.8\" width=\"54.0\" height=\"91.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"100.0\" y=\"55.2\" width=\"54.0\" height=\"136.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"154.0\" y=\"78.0\" width=\"54.0\" height=\"114.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"208.0\" y=\"123.6\" width=\"54.0\" height=\"68.4\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><rect x=\"262.0\" y=\"146.4\" width=\"54.0\" height=\"45.6\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"46.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">20</text><text x=\"100.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">30</text><text x=\"154.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">40</text><text x=\"208.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">50</text><text x=\"262.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">60</text><text x=\"316.0\" y=\"203.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px;stroke-linejoin:round\">70</text><line x1=\"40.0\" y1=\"192.0\" x2=\"316.0\" y2=\"192.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"40.0\" y1=\"192.0\" x2=\"40.0\" y2=\"40.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/></svg>"}, {"kind": "mcq", "text": "A school nurse records each student's height and weight to see whether they are related. Which display should she use?", "opts": ["Scatter plot", "Bar graph", "Circle graph", "Histogram"], "correct": 0, "tag": "", "sol": "Two quantitative variables measured on the same students are shown with a scatter plot."}, {"kind": "blank", "p": "A survey of 500 people asked about buying an electric car. 60% were under 40; 45% of those under 40 and 25% of those 40 or over said they were interested.", "tag": "", "marks": "", "flat": [{"t": "Number under 40 who are interested = __B1__", "a": {"B1": "135"}}, {"t": "Total number interested = __B1__", "a": {"B1": "185"}}, {"t": "Given a person is interested, the relative frequency of being under 40 ≈ __B1__ (nearest hundredth)", "a": {"B1": "0.73"}}], "sol": "60% of 500 = 300; 45% of 300 = 135.\n40 or over: 200 people; 25% of 200 = 50. 135 + 50 = 185.\n135 ÷ 185 ≈ 0.730 ≈ 0.73.", "tools": ["calc"], "desmos": []}, {"kind": "mcq", "text": "Daily high temperatures in a city have mean 20 °C and standard deviation 4 °C. They are converted to Fahrenheit using F = 1.8C + 32. What are the new mean and standard deviation?", "opts": ["Mean 68 °F, standard deviation 4 °F", "Mean 68 °F, standard deviation 7.2 °F", "Mean 68 °F, standard deviation 39.2 °F", "Mean 36 °F, standard deviation 7.2 °F"], "correct": 1, "tag": "", "sol": "Mean: 1.8(20) + 32 = 68. Multiplying by 1.8 multiplies σ by 1.8 (7.2); adding 32 does not change σ."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-bim-ch11';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Data Analysis and Displays</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('') + '<button class="tab-btn'+(activeTab==='report'?' active':'')+'" data-tab="report">📊 Report<span class="tab-count">pie</span></button>';
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — you can answer it now and press <b>Check</b>, or come back later from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+((item.status!=='unanswered'&&item.status!=='skipped')?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  if(item.status==='skipped') item.status='unanswered';
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+fr(THEORY)+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};


/* ================= MYP criterion report ================= */
var CRIT_COL={A:'var(--accent-text)',B:'var(--gold)',C:'#8A6FC4',D:'#2F9AA0'};
function critStats(){
  return REPORT.map(function(r){
    var tabId=r[0], slides=SLIDES[tabId], ts=state&&state.tabs[tabId];
    var c=0,w=0,n=0;
    slides.forEach(function(sl,i){
      if(!ts||!ts.items[i]){ n++; return; }
      var it=ts.items[i];
      if(MODE==='learning'){
        if(it.status==='correct') c++; else if(it.status==='revealed') w++; else n++;
      } else {
        if(isSlideCorrect(tabId,i)) c++; else if(isSlideAttempted(tabId,i)) w++; else n++;
      }
    });
    var tot=slides.length, pct=tot?Math.round(c/tot*100):0;
    var lvl=Math.round(c/Math.max(tot,1)*8);
    return {tab:tabId,letter:r[1],name:r[2],c:c,w:w,n:n,tot:tot,pct:pct,lvl:lvl};
  });
}
function arcPath(cx,cy,r,a0,a1){
  if(a1-a0>=Math.PI*2-1e-6){ return 'M'+(cx-r)+','+cy+' a'+r+','+r+' 0 1,0 '+(2*r)+',0 a'+r+','+r+' 0 1,0 '+(-2*r)+',0 Z'; }
  var x0=cx+r*Math.sin(a0), y0=cy-r*Math.cos(a0), x1=cx+r*Math.sin(a1), y1=cy-r*Math.cos(a1);
  return 'M'+cx+','+cy+' L'+x0.toFixed(2)+','+y0.toFixed(2)+' A'+r+','+r+' 0 '+((a1-a0)>Math.PI?1:0)+',1 '+x1.toFixed(2)+','+y1.toFixed(2)+' Z';
}
function pieSVG(parts,size,hole,center,sub){
  var tot=parts.reduce(function(s,p){return s+p.v;},0), cx=size/2, cy=size/2, r=size/2-4, a=0, h='';
  if(!tot){ h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+r+'" style="fill:var(--paper-2);stroke:var(--rule)"/>'; }
  parts.forEach(function(p){ if(!p.v) return; var b=a+p.v/tot*Math.PI*2; h+='<path d="'+arcPath(cx,cy,r,a,b)+'" style="fill:'+p.col+';stroke:var(--card);stroke-width:2"><title>'+esc(p.label)+': '+p.v+'</title></path>'; a=b; });
  if(hole) h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+(r*hole)+'" style="fill:var(--card)"/>';
  if(center) h+='<text x="'+cx+'" y="'+(cy-(sub?4:0))+'" text-anchor="middle" dominant-baseline="middle" style="fill:var(--ink);font:700 '+(size>150?22:15)+'px Fraunces,serif">'+center+'</text>';
  if(sub) h+='<text x="'+cx+'" y="'+(cy+16)+'" text-anchor="middle" style="fill:var(--ink-soft);font:600 11px \'Source Sans 3\',sans-serif">'+sub+'</text>';
  return '<svg viewBox="0 0 '+size+' '+size+'" width="'+size+'" height="'+size+'" role="img">'+h+'</svg>';
}
function band(l){ return l===0?'0':(l<=2?'1–2':(l<=4?'3–4':(l<=6?'5–6':'7–8'))); }
function renderReport(){
  var st=critStats(), totC=0, totQ=0;
  st.forEach(function(s){ totC+=s.c; totQ+=s.tot; });
  var h='<div class="theory">';
  h+='<section class="note"><h2>Chapter test report</h2><p class="lt">'+(MODE==='quiz'?'<b>Quiz mode</b> results: answers are marked when you finish each test tab.':'<b>Learning mode</b> results: a question counts as correct only if you got it without the answer being revealed. Switch to Quiz mode for an exam-style score.')+'</p>';
  h+='<div class="rep-top"><div class="rep-pie">'+pieSVG(st.map(function(s){return {v:s.c,col:CRIT_COL[s.letter],label:'Criterion '+s.letter};}),200,0.55,totC+'/'+totQ,'correct')+'</div>';
  h+='<div class="rep-legend"><div class="rep-cap">Marks earned, by criterion</div>'+st.map(function(s){ return '<div class="rep-li"><span class="sw" style="background:'+CRIT_COL[s.letter]+'"></span><b>'+s.letter+'</b>&nbsp;'+esc(s.name)+'<span class="rep-n">'+s.c+' / '+s.tot+'</span></div>'; }).join('')+'</div></div></section>';
  h+='<div class="rep-grid">'+st.map(function(s){
    return '<div class="rep-card"><div class="rep-h"><span class="crit" style="background:'+CRIT_COL[s.letter]+'">'+s.letter+'</span>'+esc(s.name)+'</div>'+
      '<div class="rep-row">'+pieSVG([{v:s.c,col:'var(--success)',label:'Correct'},{v:s.w,col:'var(--danger)',label:'Incorrect'},{v:s.n,col:'var(--locked)',label:'Not attempted'}],120,0.5,s.pct+'%')+
      '<div class="rep-stats"><div><span class="sw" style="background:var(--success)"></span>Correct <b>'+s.c+'</b></div><div><span class="sw" style="background:var(--danger)"></span>Incorrect <b>'+s.w+'</b></div><div><span class="sw" style="background:var(--locked)"></span>Not attempted <b>'+s.n+'</b></div>'+
      '<div class="rep-lvl">Indicative level <b>'+s.lvl+'</b> / 8 <span>(band '+band(s.lvl)+')</span></div></div></div>'+
      '<button class="hub-btn" data-go="'+s.tab+'">Open Test '+s.letter+' →</button></div>';
  }).join('')+'</div>';
  h+='<p class="rep-note">Indicative level = fraction of questions correct × 8, rounded. It is a practice guide only; your teacher awards the real MYP criterion levels.</p></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Report — chapter test results by MYP criterion';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
}
var _rsReport = renderSlide;
renderSlide = function(){
  if(activeTab==='report'){ renderReport(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  _rsReport();
};


/* ================= skipped-question return ================= */
function firstSkippedIdx(ts){
  for(var i=0;i<ts.items.length;i++){
    var it=ts.items[i];
    if(MODE==='quiz'){ if(!isSlideAttempted(activeTab,i)) return i; }
    else if(it.status==='skipped'||it.status==='unanswered') return i;
  }
  return -1;
}
function skippedList(ts){
  var out=[]; for(var i=0;i<ts.items.length;i++){ var it=ts.items[i];
    if(MODE==='quiz' ? !isSlideAttempted(activeTab,i) : (it.status==='skipped'||it.status==='unanswered')) out.push(i); }
  return out;
}
function renderSkipGate(ts){
  var list=skippedList(ts);
  var h='<div class="qcard done-card"><div class="big">⏭️</div><h2>You skipped '+list.length+' question'+(list.length>1?'s':'')+'</h2>'+
    '<p style="color:var(--ink-soft);font-size:14px;">Answer them now, or submit the tab as it is. Answers are marked only when you submit.</p>'+
    '<div class="skip-chips">'+list.map(function(i){ return '<button class="chip skip-go" data-i="'+i+'">Q'+(i+1)+'</button>'; }).join('')+'</div>'+
    '<div class="skip-btns"><button class="btn btn-primary" id="btnGoSkipped">Answer skipped questions</button><button class="btn" id="btnSubmitAnyway">Submit anyway</button></div></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  var go=function(i){ ts.idx=i; ts.maxReached=Math.max(ts.maxReached,i); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); };
  document.getElementById('btnGoSkipped').addEventListener('click',function(){ go(list[0]); });
  document.querySelectorAll('.skip-go').forEach(function(b){ b.addEventListener('click',function(){ go(parseInt(b.dataset.i,10)); }); });
  document.getElementById('btnSubmitAnyway').addEventListener('click',function(){ ts.submitOK=true; renderFinished(); ts.submitOK=false; });
  saveState();
}
var _rfSkip = renderFinished;
renderFinished = function(){
  var ts=state.tabs[activeTab];
  if(MODE==='quiz' && !ts.submitOK && skippedList(ts).length){ renderSkipGate(ts); return; }
  _rfSkip();
  if(MODE==='learning'){
    var list=skippedList(ts);
    if(list.length){
      var card=document.querySelector('.done-card');
      if(card){ var d=document.createElement('div'); d.className='skip-btns';
        d.innerHTML='<button class="btn btn-primary" id="btnGoSkipped">Attempt skipped questions ('+list.length+')</button>';
        card.appendChild(d);
        document.getElementById('btnGoSkipped').addEventListener('click',function(){ ts.idx=list[0]; ts.recorded=false; renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); }
    }
  }
};


/* ================= approx answers (physics: within 1%) ================= */
var _amTools = answerMatches;
answerMatches = function(input,answer,accept,expr){
  if(expr==='approx'){
    var n1=parseNum(input); if(n1===null) return false;
    return [answer].concat(accept||[]).some(function(a){ var n2=parseNum(a); if(n2===null) return false; return Math.abs(n1-n2) <= Math.max(0.011*Math.abs(n2), 1e-9); });
  }
  return _amTools(input,answer,accept,expr);
};

/* ================= palette: every question already reached can be opened ================= */
statusOf = function(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  var s=ts.items[i].status;
  if(s==='unanswered') return 'skipped';
  return s;
};

/* ================= on-screen keyboard ================= */
var KB={on:true, page:'num', target:null};
try{ var kbp=localStorage.getItem('sopaan-kb-pref'); if(kbp==='off') KB.on=false; }catch(e){}
function kbSave(){ try{ localStorage.setItem('sopaan-kb-pref', KB.on?'on':'off'); }catch(e){} }
var KEYS_NUM=[['7','8','9','(',')'],['4','5','6','−','/'],['1','2','3','.',','],['0',':','%','°','⌫'],['abc','←','→','Clear','Done']];
var KEYS_FRAC=[['7','8','9','/'],['4','5','6','−'],['1','2','3','space'],['0',',','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ALG=[['7','8','9','x','y','n'],['4','5','6','+','−','a'],['1','2','3','×','÷','b'],['0','.','(',')','^','²'],['/','π','|','t','⌫','Clear'],['abc','←','→','Done']];
function kbLayoutFor(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; var m=stp.expr, key=String(stp.a[inp.dataset.bkey]||'');
  if(m==='words'||m==='glist'||m==='angle') return 'abc'; if(m===true||m==='pow'||m==='primes') return 'alg';
  if(['fv','fe','fl','fm','fi','flist'].indexOf(m)>=0) return 'frac'; if(m==='dec'||m==='approx'||m==='dlist'||m==='set'||m==='coord'||m==='list'||m==='time') return 'num';
  if(/^[\-−]?\d+ \d+\/\d+$/.test(key)||/^[\-−]?\d+\/\d+$/.test(key)) return 'frac'; if(/[a-df-z]/i.test(key.replace(/pi/gi,''))) return /\d/.test(key)?'alg':'abc'; return 'num'; }catch(e){ return 'num'; } }
var KEYS_CALC=[['7','8','9','x','(',')'],['4','5','6','+','−','^'],['1','2','3','×','/','²'],['0','.','e','eˣ','√','ln'],['sin','cos','tan','t','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ABC=[['q','w','e','r','t','y','u','i','o','p'],['a','s','d','f','g','h','j','k','l','-'],['z','x','c','v','b','n','m',',',':','/'],['123','space','←','→','⌫','Done']];
function kbBuild(){
  var el=document.getElementById('vkb'); if(!el){ el=document.createElement('div'); el.id='vkb'; el.className='vkb'; document.body.appendChild(el);
    el.addEventListener('pointerdown',function(e){ var b=e.target.closest('button[data-k]'); e.preventDefault(); if(b) kbPress(b.dataset.k); });
    el.addEventListener('mousedown',function(e){ e.preventDefault(); }); }
  var rows={num:KEYS_NUM,frac:KEYS_FRAC,alg:KEYS_ALG,abc:KEYS_ABC,calc:KEYS_CALC}[KB.page]||KEYS_NUM;
  el.innerHTML='<div class="vkb-top"><span>⌨️ Keyboard</span><button data-k="device" class="vkb-link">Use device keyboard</button></div>'+
    rows.map(function(r){ return '<div class="vkb-row">'+r.map(function(k){
      var cls='vkb-k'+(/^(abc|123|Done|Clear|⌫|←|→|space)$/.test(k)?' fn':'')+(k==='Done'?' done':'');
      return '<button type="button" class="'+cls+'" data-k="'+k+'">'+(k==='space'?'space':k)+'</button>'; }).join('')+'</div>'; }).join('');
  return el;
}
function kbShow(inp){ KB.target=inp; KB.home=kbLayoutFor(inp); KB.page=KB.home; if(!KB.on) return; var cp=document.getElementById('calcPanel'); if(cp&&cp.classList.contains('show')) return; var el=kbBuild(); var nb=document.querySelector('.navbar'); el.style.bottom=(nb?nb.getBoundingClientRect().height:0)+'px'; el.classList.add('show'); document.body.classList.add('kb-open'); setTimeout(function(){ var r=inp.getBoundingClientRect(), top=el.getBoundingClientRect().top; if(r.bottom>top-12) window.scrollBy({top:r.bottom-top+60,behavior:'smooth'}); else if(r.top<60) window.scrollBy({top:r.top-80,behavior:'smooth'}); },30); }
function kbHide(){ var el=document.getElementById('vkb'); if(el) el.classList.remove('show'); document.body.classList.remove('kb-open'); }
function kbInsert(s){
  var t=KB.target; if(!t||t.disabled) return;
  var a=t.selectionStart==null?t.value.length:t.selectionStart, b=t.selectionEnd==null?a:t.selectionEnd;
  t.value=t.value.slice(0,a)+s+t.value.slice(b); var p=a+s.length; try{ t.setSelectionRange(p,p); }catch(e){}
  t.dispatchEvent(new Event('input',{bubbles:true}));
}
function kbPress(k){
  var t=KB.target; if(k==='device'){ KB.on=false; kbSave(); kbHide(); document.querySelectorAll('.blank-input').forEach(function(i){ i.removeAttribute('inputmode'); }); if(t){ t.blur(); setTimeout(function(){ t.focus(); },50); } showToast('Device keyboard on. Tap ⌨️ on any blank to bring the on-screen keyboard back.'); return; }
  if(k==='Done'){ kbHide(); if(t) t.blur(); return; }
  if(k==='abc'||k==='123'){ KB.page=(k==='abc')?'abc':(KB.home&&KB.home!=='abc'?KB.home:'num'); kbBuild(); return; }
  if(!t) return;
  if(k==='⌫'){ var a=t.selectionStart, b=t.selectionEnd; if(a===b&&a>0){ t.value=t.value.slice(0,a-1)+t.value.slice(b); try{t.setSelectionRange(a-1,a-1);}catch(e){} } else { t.value=t.value.slice(0,a)+t.value.slice(b); try{t.setSelectionRange(a,a);}catch(e){} } t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='Clear'){ t.value=''; t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='←'||k==='→'){ var p=(t.selectionStart||0)+(k==='←'?-1:1); p=Math.max(0,Math.min(t.value.length,p)); try{t.setSelectionRange(p,p);}catch(e){} return; }
  var map={'−':'-','space':' '}; kbInsert(map[k]!==undefined?map[k]:k);
}
function kbWire(){
  document.querySelectorAll('.blank-input').forEach(function(inp){
    if(inp.dataset.kb) return; inp.dataset.kb='1';
    if(KB.on) inp.setAttribute('inputmode','none');
    inp.addEventListener('focus',function(){ kbShow(inp); });
    var btn=document.createElement('button'); btn.type='button'; btn.className='kb-toggle'; btn.title='On-screen keyboard'; btn.textContent='⌨️'; btn.tabIndex=-1;
    btn.addEventListener('mousedown',function(e){ e.preventDefault(); });
    btn.addEventListener('click',function(){ KB.on=true; kbSave(); document.querySelectorAll('.blank-input').forEach(function(i){ i.setAttribute('inputmode','none'); }); inp.focus(); kbShow(inp); });
    if(!inp.disabled) inp.insertAdjacentElement('afterend',btn);
  });
}
document.addEventListener('focusout',function(e){ setTimeout(function(){ var a=document.activeElement; if(!a||!a.classList||!a.classList.contains('blank-input')){ if(!document.querySelector('#vkb:hover')) kbHide(); } },120); });

/* ================= calculator ================= */
var CALC={expr:'', ans:0};
function calcEval(src){
  var s=String(src).replace(/×/g,'*').replace(/÷/g,'/').replace(/−/g,'-').replace(/π/g,'(PI)').replace(/Ans/g,'('+CALC.ans+')').replace(/\^/g,'**').replace(/√\(/g,'sqrt(').replace(/²/g,'**2').replace(/E/g,'*10**');
  s=s.replace(/(^|[(*\/+\-,])-/g,'$1(-1)*');
  if(/[^0-9+\-*/().,a-z A-Z]/.test(s)) throw 0;
  var ok=s.replace(/sin|cos|tan|asin|acos|atan|sqrt|log|ln|PI|abs/g,''); if(/[a-zA-Z]/.test(ok)) throw 0;
  var f=new Function('sin','cos','tan','asin','acos','atan','sqrt','log','ln','PI','abs','return ('+s+');');
  var d=Math.PI/180;
  var v=f(function(x){return Math.sin(x*d);},function(x){return Math.cos(x*d);},function(x){return Math.tan(x*d);},
    function(x){return Math.asin(x)/d;},function(x){return Math.acos(x)/d;},function(x){return Math.atan(x)/d;},Math.sqrt,Math.log10,Math.log,Math.PI,Math.abs);
  if(typeof v!=='number'||!isFinite(v)) throw 0; return v;
}
function fmtNum(v){ if(Math.abs(v)>=1e10||(Math.abs(v)<1e-6&&v!==0)) return v.toExponential(6).replace(/\.?0+e/,'e'); return String(parseFloat(v.toPrecision(10))); }
var CKEYS=[['sin(','cos(','tan(','√(','^','²'],['asin(','acos(','atan(','(',')','π'],['7','8','9','÷','⌫','AC'],['4','5','6','×','E','Ans'],['1','2','3','−','(−)','Insert'],['0','.','=','+']];
function openCalc(){
  var p=document.getElementById('calcPanel');
  if(!p){ p=document.createElement('div'); p.id='calcPanel'; p.className='tool-panel calc';
    p.innerHTML='<div class="tp-head"><b>🧮 Calculator</b><span class="tp-note">degrees · tap a blank, then Insert</span><button class="tp-x" data-c="close">✕</button></div>'+
      '<div class="calc-disp"><div class="calc-expr" id="calcExpr"></div><div class="calc-res" id="calcRes">0</div></div>'+
      '<div class="calc-keys">'+CKEYS.map(function(r){ return r.map(function(k){ return '<button type="button" data-c="'+k+'" class="'+(k==='='?'eq':(/^(AC|⌫|Insert)$/.test(k)?'fn':''))+'">'+({'sin(':'sin','cos(':'cos','tan(':'tan','asin(':'sin⁻¹','acos(':'cos⁻¹','atan(':'tan⁻¹','√(':'√'}[k]||k)+'</button>'; }).join(''); }).join('')+'</div>';
    document.body.appendChild(p);
    p.addEventListener('mousedown',function(e){ if(e.target.closest('button')) e.preventDefault(); });
    p.addEventListener('click',function(e){ var b=e.target.closest('button[data-c]'); if(!b) return; calcKey(b.dataset.c); });
  }
  kbHide(); var nb=document.querySelector('.navbar'); p.style.bottom=((nb?nb.getBoundingClientRect().height:0)+8)+'px'; p.classList.add('show'); document.body.classList.add('calc-open'); calcShow();
}
function calcShow(res){ document.getElementById('calcExpr').textContent=CALC.expr||' '; if(res!==undefined) document.getElementById('calcRes').textContent=res; }
function calcKey(k){
  if(k==='close'){ document.getElementById('calcPanel').classList.remove('show'); document.body.classList.remove('calc-open'); return; }
  if(k==='AC'){ CALC.expr=''; calcShow('0'); return; }
  if(k==='⌫'){ CALC.expr=CALC.expr.replace(/(asin\(|acos\(|atan\(|sin\(|cos\(|tan\(|√\(|Ans|.)$/,''); calcShow(); return; }
  if(k==='='){ try{ var v=calcEval(CALC.expr); CALC.ans=v; calcShow(fmtNum(v)); }catch(e){ calcShow('Error'); } return; }
  if(k==='(−)'){ CALC.expr+='−'; calcShow(); return; }
  if(k==='Insert'){ var r=document.getElementById('calcRes').textContent; if(KB.target && !KB.target.disabled && r!=='Error'){ KB.target.value=r; KB.target.dispatchEvent(new Event('input',{bubbles:true})); showToast('Inserted '+r+' into the blank.'); } else showToast('Tap a blank first, then press Insert.'); return; }
  CALC.expr+=k; calcShow();
}

/* ================= Desmos ================= */
var DESMOS_KEY='dcb31709b452b1cf9dc26972add0fda6', desmosCalc=null, desmosLoading=false;
function openDesmos(exprs){
  var p=document.getElementById('desmosPanel');
  if(!p){ p=document.createElement('div'); p.id='desmosPanel'; p.className='tool-panel desmos';
    p.innerHTML='<div class="tp-head"><b>📈 Desmos graphing calculator</b><button class="tp-x" id="desmosReset">Reset graph</button><button class="tp-x" id="desmosClose">✕</button></div><div id="desmosBox"><div class="desmos-msg">Loading Desmos…</div></div>';
    document.body.appendChild(p);
    document.getElementById('desmosClose').addEventListener('click',function(){ p.classList.remove('show'); });
    document.getElementById('desmosReset').addEventListener('click',function(){ if(desmosCalc) desmosSet(p._exprs||[]); });
  }
  p._exprs=exprs||[]; p.classList.add('show');
  if(window.Desmos){ desmosInit(); desmosSet(p._exprs); return; }
  if(desmosLoading) return; desmosLoading=true;
  var sc=document.createElement('script'); sc.src='https://www.desmos.com/api/v1.9/calculator.js?apiKey='+DESMOS_KEY;
  sc.onload=function(){ desmosInit(); desmosSet(p._exprs); };
  sc.onerror=function(){ desmosLoading=false; document.getElementById('desmosBox').innerHTML='<div class="desmos-msg">Desmos needs an internet connection. <a href="https://www.desmos.com/calculator" target="_blank" rel="noopener">Open Desmos in a new tab</a>.</div>'; };
  document.head.appendChild(sc);
}
function desmosInit(){ if(desmosCalc) return; var box=document.getElementById('desmosBox'); box.innerHTML=''; desmosCalc=Desmos.GraphingCalculator(box,{expressionsCollapsed:false,settingsMenu:false,border:false,degreeMode:true}); }
function desmosSet(exprs){ if(!desmosCalc) return; desmosCalc.setBlank(); (exprs||[]).forEach(function(e,i){ if(typeof e==='string') desmosCalc.setExpression({id:'e'+i,latex:e}); else desmosCalc.setExpression(Object.assign({id:'e'+i},e)); }); }

/* ================= toolbar on each question ================= */
var _rsTools = renderSlide;
renderSlide = function(){
  _rsTools();
  kbHide();
  if(activeTab==='theory'||activeTab==='report') return;
  var ts=state.tabs[activeTab]; if(!ts) return;
  var slide=SLIDES[activeTab][ts.idx], card=document.querySelector('#wrap .qcard');
  if(card && slide && slide.tools && slide.tools.length && !card.querySelector('.tool-bar')){
    var bar=document.createElement('div'); bar.className='tool-bar';
    bar.innerHTML=(slide.tools.indexOf('calc')>=0?'<button type="button" class="tool-btn" data-t="calc">🧮 Calculator</button>':'')+
                  (slide.tools.indexOf('desmos')>=0?'<button type="button" class="tool-btn" data-t="desmos">📈 Desmos graph</button>':'');
    card.insertBefore(bar, card.firstChild);
    bar.addEventListener('click',function(e){ var b=e.target.closest('[data-t]'); if(!b) return; if(b.dataset.t==='calc') openCalc(); else openDesmos(slide.desmos||[]); });
  }
  kbWire();
};



/* ================= signed fractions in text: {−3/4}, {3/−4}, {−2 1/3}, {p/q} ================= */
fr = function(s){ return String(s).replace(/&lt;(\/?)(b|sup|sub|i)>/g,'<$1$2>')
  .replace(/\{([−-]?\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>')
  .replace(/\{([−-]?[A-Za-z0-9]+)\/([−-]?[A-Za-z0-9]+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); };
/* ================= BMA badge → main page of this sheet (theory hub) ================= */
(function(){
  var c=document.querySelector('.brand .crest'); if(!c) return;
  var a=document.createElement('button'); a.type='button'; a.className='crest crest-home'; a.title='Back to the main page (theory notes)'; a.setAttribute('aria-label','Main page');
  a.innerHTML='BM<span class="crest-h">⌂</span>'; c.parentNode.replaceChild(a,c);
  a.addEventListener('click',function(){
    if(!student||!MODE){ window.scrollTo({top:0,behavior:'smooth'}); return; }
    if(typeof kbHide==='function') kbHide(); if(typeof SP!=='undefined'&&SP.on) spToggle(false);
    var cp=document.getElementById('calcPanel'); if(cp) cp.classList.remove('show'); document.body.classList.remove('calc-open');
    activeTab = (typeof THEORY!=='undefined') ? 'theory' : TAB_DEFS[0].id;
    buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'});
  });
})();

/* ================= session clock: starts at sign-in and keeps running ================= */
var CLK={t0:null};
(function(){
  var row=document.querySelector('.brand .brand-row'); if(!row) return;
  var d=document.createElement('div'); d.className='bmasw off'; d.id='swBox'; d.title='Time since you signed in';
  d.innerHTML='<span class="bmasw-ic">⏱</span><span class="bmasw-t" id="swT">00:00</span>';
  row.appendChild(d); setInterval(swTick,1000);
})();
function swFmt(s){ s=Math.floor(s||0); var h=Math.floor(s/3600), m=Math.floor(s%3600/60), x=s%60; return (h?h+':'+String(m).padStart(2,'0'):String(m).padStart(2,'0'))+':'+String(x).padStart(2,'0'); }
function swTick(){
  var box=document.getElementById('swBox'); if(!box) return;
  if(student && !CLK.t0) CLK.t0=Date.now();
  if(!student) CLK.t0=null;
  box.classList.toggle('off',!CLK.t0);
  document.getElementById('swT').textContent = CLK.t0 ? swFmt((Date.now()-CLK.t0)/1000) : '00:00';
}
function swTab(){ try{ if(!state||!state.tabs||activeTab==='theory'||activeTab==='report') return null; return state.tabs[activeTab]||null; }catch(e){ return null; } }
var _rsSW = renderSlide;
renderSlide = function(){ _rsSW(); swTick(); };
var _rfSW = renderFinished;
renderFinished = function(){ _rfSW(); var done=document.querySelector('#wrap .done-card'); if(CLK.t0 && done && !done.querySelector('.bmasw-done')){ var p=document.createElement('p'); p.className='bmasw-done'; p.textContent='⏱ Time since sign-in: '+swFmt((Date.now()-CLK.t0)/1000); var h2=done.querySelector('h2'); if(h2) h2.insertAdjacentElement('afterend',p); else done.appendChild(p); } };

/* ================= scratchpad (Khan-style, 4 pens) ================= */
var SP={on:false, draw:true, color:'ink', size:3, erase:false, store:{}, key:null, cv:null, ctx:null, down:false, last:null};
var SP_COL={ink:null, blue:'#2563EB', red:'#DC2626', green:'#16A34A'};
function spInk(){ return getComputedStyle(document.documentElement).getPropertyValue('--ink').trim()||'#211E1A'; }
function spKey(){ var ts=swTab(); return ts ? (MODE+'|'+activeTab+'|'+ts.idx) : null; }
function spBuild(){
  if(SP.cv) return;
  var cv=document.createElement('canvas'); cv.id='spCanvas'; cv.className='sp-canvas'; document.body.appendChild(cv);
  var bar=document.createElement('div'); bar.id='spBar'; bar.className='sp-bar';
  bar.innerHTML='<span class="sp-lbl">✏️ Scratchpad</span>'+
    ['ink','blue','red','green'].map(function(c){ return '<button type="button" class="sp-pen" data-c="'+c+'" title="'+(c==='ink'?'black':c)+' pen"><i style="background:'+(c==='ink'?'var(--ink)':SP_COL[c])+'"></i></button>'; }).join('')+
    '<button type="button" class="sp-tool" data-t="erase" title="Eraser">🧽</button><button type="button" class="sp-tool" data-t="size" title="Pen size">●</button><button type="button" class="sp-tool" data-t="scroll" title="Pause drawing to scroll or answer">✋</button>'+
    '<button type="button" class="sp-tool" data-t="clear" title="Clear page">🗑</button><button type="button" class="sp-tool" data-t="close" title="Close scratchpad">✕</button>';
  document.body.appendChild(bar);
  bar.addEventListener('click',function(e){ var b=e.target.closest('button'); if(!b) return;
    if(b.dataset.c){ SP.color=b.dataset.c; SP.erase=false; SP.draw=true; }
    else if(b.dataset.t==='erase'){ SP.erase=true; SP.draw=true; }
    else if(b.dataset.t==='size'){ SP.size = SP.size===3?6:(SP.size===6?1.5:3); b.textContent = SP.size===6?'⬤':(SP.size===1.5?'·':'●'); }
    else if(b.dataset.t==='scroll'){ SP.draw=!SP.draw; }
    else if(b.dataset.t==='clear'){ spClear(); }
    else if(b.dataset.t==='close'){ spToggle(false); return; }
    spUI(); });
  SP.cv=cv; SP.ctx=cv.getContext('2d');
  cv.addEventListener('pointerdown',function(e){ if(!SP.draw) return; e.preventDefault(); cv.setPointerCapture(e.pointerId); SP.down=true; SP.last=spPt(e); spDot(SP.last); });
  cv.addEventListener('pointermove',function(e){ if(!SP.down) return; e.preventDefault(); var p=spPt(e); spLine(SP.last,p); SP.last=p; });
  var up=function(){ if(SP.down){ SP.down=false; spSave(); } };
  cv.addEventListener('pointerup',up); cv.addEventListener('pointercancel',up); cv.addEventListener('pointerleave',up);
  window.addEventListener('resize',function(){ if(SP.on) spFit(true); });
}
function spPt(e){ var r=SP.cv.getBoundingClientRect(); return {x:e.clientX-r.left, y:e.clientY-r.top}; }
function spStyle(){ var c=SP.ctx; c.lineCap='round'; c.lineJoin='round'; c.globalCompositeOperation=SP.erase?'destination-out':'source-over'; c.strokeStyle=c.fillStyle=(SP.color==='ink'?spInk():SP_COL[SP.color]); c.lineWidth=SP.erase?22:SP.size; }
function spDot(p){ spStyle(); var c=SP.ctx; c.beginPath(); c.arc(p.x,p.y,(SP.erase?11:SP.size/2),0,Math.PI*2); c.fill(); }
function spLine(a,b){ spStyle(); var c=SP.ctx; c.beginPath(); c.moveTo(a.x,a.y); c.lineTo(b.x,b.y); c.stroke(); }
function spSave(){ if(SP.key&&SP.cv){ try{ SP.store[SP.key]=SP.cv.toDataURL(); }catch(e){} } }
function spClear(){ if(!SP.ctx) return; SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.clearRect(0,0,SP.cv.width,SP.cv.height); SP.ctx.restore(); if(SP.key) delete SP.store[SP.key]; }
function spFit(keep){
  var wrap=document.getElementById('wrap'); if(!wrap||!SP.cv) return;
  var r=wrap.getBoundingClientRect(), top=r.top+window.scrollY, h=Math.max(wrap.scrollHeight, window.innerHeight-r.top)+40, w=document.documentElement.clientWidth;
  var old=keep&&SP.key?SP.store[SP.key]:null, dpr=window.devicePixelRatio||1;
  SP.cv.style.top=top+'px'; SP.cv.style.left='0px'; SP.cv.style.width=w+'px'; SP.cv.style.height=h+'px';
  SP.cv.width=Math.round(w*dpr); SP.cv.height=Math.round(h*dpr); SP.ctx.setTransform(dpr,0,0,dpr,0,0);
  if(old){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=old; }
}
function spLoad(){ spSave(); SP.key=spKey(); spFit(false); var d=SP.key&&SP.store[SP.key]; if(d){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=d; } }
function spUI(){
  var bar=document.getElementById('spBar'); if(!bar) return;
  bar.querySelectorAll('.sp-pen').forEach(function(b){ b.classList.toggle('on', !SP.erase && SP.draw && b.dataset.c===SP.color); });
  bar.querySelector('[data-t=erase]').classList.toggle('on', SP.erase && SP.draw);
  bar.querySelector('[data-t=scroll]').classList.toggle('on', !SP.draw);
  SP.cv.classList.toggle('passive', !SP.draw);
  var fb=document.getElementById('spFab'); if(fb) fb.classList.toggle('on',SP.on);
}
function spToggle(on){
  spBuild(); SP.on=(on===undefined)?!SP.on:on;
  document.body.classList.toggle('sp-open',SP.on); SP.cv.style.display=SP.on?'block':'none'; document.getElementById('spBar').style.display=SP.on?'flex':'none';
  if(SP.on){ SP.draw=true; SP.erase=false; spLoad(); if(typeof kbHide==='function') kbHide(); } else { spSave(); }
  spUI();
}
(function(){ var f=document.createElement('button'); f.type='button'; f.id='spFab'; f.className='sp-fab'; f.innerHTML='✏️ <span>Scratchpad</span>'; f.title='Open a scratchpad to write your working'; f.addEventListener('click',function(){ spToggle(); }); document.body.appendChild(f); })();
var _rsSP = renderSlide;
renderSlide = function(){ _rsSP(); var fab=document.getElementById('spFab'); var q=!!swTab(); if(fab) fab.style.display=q?'':'none'; if(!q && SP.on) spToggle(false); if(SP.on) setTimeout(spLoad,30); };


/* ================= v4: attempt classification ================= */
function v4Class(item){
  if(!item) return 'un';
  if(item.status==='skipped') return 'sk';
  if(item.status==='unanswered') return 'un';
  if(item.stepStates){ // step question
    if(item.status!=='correct' && item.status!=='revealed') return 'un';
    if(item.status==='revealed' || item.stepStates.some(function(s){return s.status==='revealed';})) return 'w';
    return item.stepStates.some(function(s){return (s.attempts||0)>0;}) ? 'c2' : 'c1';
  }
  if(item.status==='revealed') return 'w';
  if(item.status==='correct') return (item.attempts||0)>0 ? 'c2' : 'c1';
  if(item.status==='wrong'||item.status==='incorrect') return 'w';
  return 'un';
}
function v4Counts(items){ var c={n:items.length,c1:0,c2:0,w:0,sk:0,un:0}; items.forEach(function(it){ c[v4Class(it)]++; }); return c; }

/* ================= v4: My record with attempt columns ================= */
renderRecord = function(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var title=(document.querySelector('.chapter-title')||{}).textContent||'';
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+(title?' · '+esc(title):'')+'</p>';
  var st=appState.learning;
  h+='<h3>📘 Learning Sheet — attempts</h3><p class="v4leg"><b>1st ✓</b> correct on the first attempt · <b>2nd ✓</b> correct on the second attempt · <b>Wrong</b> still wrong after two attempts (answer revealed) · <b>Skip</b> skipped<span class="v4left"> · <b>Left</b> not done yet</span></p>';
  if(!st){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    var T={n:0,c1:0,c2:0,w:0,sk:0,un:0};
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th><th>Skip</th><th class="v4left">Left</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=st.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var c=v4Counts(tt.items);
      ['n','c1','c2','w','sk','un'].forEach(function(k){ T[k]+=c[k]; });
      h+='<tr><td>'+td.label+'</td><td>'+c.n+'</td><td class="v4g">'+c.c1+'</td><td class="v4o">'+c.c2+'</td><td class="v4r">'+c.w+'</td><td>'+c.sk+'</td><td class="v4left">'+c.un+'</td></tr>'; });
    h+='<tr class="v4tot"><td>Total</td><td>'+T.n+'</td><td class="v4g">'+T.c1+'</td><td class="v4o">'+T.c2+'</td><td class="v4r">'+T.w+'</td><td>'+T.sk+'</td><td class="v4left">'+T.un+'</td></tr>';
    h+='</tbody></table></div>';
    var doneN=T.c1+T.c2+T.w; if(doneN){ h+='<p class="v4sum">Of '+doneN+' questions answered: <b>'+Math.round(T.c1/doneN*100)+'%</b> right first time, <b>'+Math.round(T.c2/doneN*100)+'%</b> right on the second try, <b>'+Math.round(T.w/doneN*100)+'%</b> still wrong after two tries.</p>'; }
  }
  var q=appState.quiz;
  h+='<h3>📝 Quiz Mode</h3>';
  if(!q){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>Status</th><th>Correct</th><th>Wrong</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=q.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var n=tt.items.length, cor=0, att=0;
      tt.items.forEach(function(it){ if(it.status!=='unanswered'||it.choice!==undefined) att++; });
      var rec=records.filter(function(r){ return r.mode==='quiz'&&r.tab===td.id; })[0];
      if(rec){ cor=rec.correct; att=Math.max(att,rec.total); }
      h+='<tr><td>'+td.label+'</td><td>'+n+'</td><td>'+(rec?'Finished':att+' / '+n)+'</td><td class="v4g">'+(rec?cor:'—')+'</td><td class="v4r">'+(rec?(rec.total-cor):'—')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><div class="rec-card"><h3>Finished sheets (latest first)</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sheets finished yet. Each time you finish a sheet, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>When</th><th>Mode</th><th>Sheet</th><th>Score</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+'</td><td>'+(r.c1!=null?r.c1:'—')+'</td><td>'+(r.c2!=null?r.c2:'—')+'</td><td>'+(r.w!=null?r.w:(r.mode==='quiz'?r.total-r.correct:'—'))+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){ if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker(); });
  window.scrollTo({top:0});
};
var _v4add = addRecord;
addRecord = function(mode, tabId, correct, revealed, skipped, total){
  _v4add(mode, tabId, correct, revealed, skipped, total);
  try{ if(mode==='learning'&&records[0]){ var c=v4Counts(state.tabs[tabId].items); records[0].c1=c.c1; records[0].c2=c.c2; records[0].w=c.w; saveState(); } }catch(e){}
};

/* ================= v4: celebration ================= */
function v4Cracker(){
  var ctx=ensureAudio(); if(!ctx) return; try{ if(ctx.state==='suspended') ctx.resume(); }catch(e){}
  var now=ctx.currentTime;
  function pop(t, vol, dur, hp){
    var len=Math.floor(ctx.sampleRate*dur), buf=ctx.createBuffer(1,len,ctx.sampleRate), d=buf.getChannelData(0);
    for(var i=0;i<len;i++){ d[i]=(Math.random()*2-1)*Math.pow(1-i/len,3); }
    var src=ctx.createBufferSource(); src.buffer=buf;
    var f=ctx.createBiquadFilter(); f.type='highpass'; f.frequency.value=hp;
    var g=ctx.createGain(); g.gain.setValueAtTime(vol,t); g.gain.exponentialRampToValueAtTime(0.001,t+dur);
    src.connect(f); f.connect(g); g.connect(ctx.destination); src.start(t); src.stop(t+dur+0.02);
  }
  pop(now,0.9,0.35,300);                                   // big bang
  for(var k=0;k<14;k++){ pop(now+0.35+Math.random()*1.3, 0.25+Math.random()*0.35, 0.05+Math.random()*0.08, 1500+Math.random()*2500); } // crackles
  [523.25,659.25,783.99,1046.5].forEach(function(fq,i){ var o=ctx.createOscillator(), g=ctx.createGain(); o.type='triangle'; o.frequency.value=fq;
    var t=now+0.15+i*0.12; g.gain.setValueAtTime(0.0001,t); g.gain.exponentialRampToValueAtTime(0.18,t+0.03); g.gain.exponentialRampToValueAtTime(0.001,t+0.5);
    o.connect(g); g.connect(ctx.destination); o.start(t); o.stop(t+0.55); });
}
function v4Confetti(){
  var cv=document.createElement('canvas'); cv.className='v4conf'; document.body.appendChild(cv);
  var W=cv.width=window.innerWidth*(window.devicePixelRatio||1), H=cv.height=window.innerHeight*(window.devicePixelRatio||1), s=(window.devicePixelRatio||1);
  var ctx=cv.getContext('2d'), cols=['#e8b13a','#d9534f','#2e86de','#27ae60','#9b59b6','#f39c12','#1abc9c','#ff6b9a'], P=[];
  function burst(x,y,n){ for(var i=0;i<n;i++){ var a=Math.random()*Math.PI*2, v=(4+Math.random()*9)*s;
    P.push({x:x,y:y,vx:Math.cos(a)*v,vy:Math.sin(a)*v-6*s,w:(6+Math.random()*7)*s,h:(4+Math.random()*5)*s,r:Math.random()*6,vr:(Math.random()-.5)*.4,c:cols[i%cols.length],life:0,flyer:Math.random()<.25}); } }
  burst(W*0.2,H*0.35,90); burst(W*0.8,H*0.35,90); setTimeout(function(){ burst(W*0.5,H*0.25,120); },380); setTimeout(function(){ burst(W*0.35,H*0.3,70); burst(W*0.65,H*0.3,70); },800);
  var t0=performance.now();
  (function frame(t){
    ctx.clearRect(0,0,W,H);
    P.forEach(function(p){ p.vy+=0.22*s; p.vx*=0.985; p.vy*=0.985; p.x+=p.vx; p.y+=p.vy; p.r+=p.vr; p.life++;
      ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.r); ctx.fillStyle=p.c;
      if(p.flyer){ ctx.fillRect(-p.w*1.4,-1.5*s,p.w*2.8,3*s); } else { ctx.fillRect(-p.w/2,-p.h/2,p.w,p.h*Math.abs(Math.cos(p.life/6))); }
      ctx.restore(); });
    if(t-t0<4200) requestAnimationFrame(frame); else cv.remove();
  })(t0);
}
function v4NextTab(){
  var i=TAB_DEFS.findIndex(function(t){return t.id===activeTab;});
  for(var j=i+1;j<TAB_DEFS.length;j++){ var id=TAB_DEFS[j].id; if(id!=='theory' && SLIDES[id] && SLIDES[id].length) return TAB_DEFS[j]; }
  return null;
}
function v4Celebrate(){
  var done=document.querySelector('#wrap .done-card'); if(!done || done.dataset.v4) return; done.dataset.v4='1';
  var ts=state.tabs[activeTab], c=v4Counts(ts.items), n=ts.items.length;
  var first=(student&&student.name)?String(student.name).split(' ')[0]:'';
  var pct=MODE==='quiz'?null:Math.round((c.c1+c.c2)/Math.max(n,1)*100);
  var msg = pct===null ? 'You finished this sheet!' : (pct>=90?'Outstanding work!':pct>=75?'Excellent effort!':pct>=50?'Well done — keep going!':'Great persistence — every try makes you stronger!');
  var banner=document.createElement('div'); banner.className='v4ban';
  banner.innerHTML='<div class="v4trophy">🏆</div><div class="v4h">Congratulations'+(first?', '+esc(first):'')+'!</div><div class="v4m">'+msg+'</div>'+
    (MODE==='quiz'?'':'<div class="v4pills"><span class="v4p g">✅ '+c.c1+' first attempt</span><span class="v4p o">🔁 '+c.c2+' second attempt</span><span class="v4p r">❌ '+c.w+' finally wrong</span>'+(c.sk?'<span class="v4p s">⏭ '+c.sk+' skipped</span>':'')+'</div>');
  done.insertBefore(banner, done.firstChild);
  var nx=v4NextTab(), wrapB=document.createElement('div'); wrapB.className='v4next';
  if(nx){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">Next sheet: '+nx.label+' →</button>'; }
  else if(SLIDES.report!==undefined || TAB_DEFS.some(function(t){return t.id==='report';})){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">📊 View my report →</button>'; }
  else { wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">⌂ Back to the home page</button>'; }
  banner.appendChild(wrapB);
  document.getElementById('v4Next').addEventListener('click',function(){
    var t=nx?nx.id:(TAB_DEFS.some(function(x){return x.id==='report';})?'report':(TAB_DEFS[0]&&TAB_DEFS[0].id));
    activeTab=t; showChrome(true); buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  setTimeout(function(){ var r=banner.getBoundingClientRect(); window.scrollBy({top:r.top-110,behavior:'smooth'}); },60);
  v4Confetti(); v4Cracker();
}
var _v4rf = renderFinished;
renderFinished = function(){ _v4rf.apply(this,arguments); try{ v4Celebrate(); }catch(e){ console.log('v4',e); } };


/* ================= calculus answer mode ================= */
function calcCompile(src){
  var s=String(src).replace(/\s+/g,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/π/g,'#').replace(/eˣ/g,'e^x');
  if(s.indexOf('=')>=0) s=s.slice(s.lastIndexOf('=')+1);
  var FN=['sqrt','abs','ln','log','exp','sin','cos','tan','sec','csc','cot','pi'];
  var i=0,toks=[];
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length&&/[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(ch==='√'){ toks.push({k:'f',v:'sqrt'}); i++; continue; }
    if(/[a-zA-Z#]/.test(ch)){
      var hit=null; for(var q=0;q<FN.length;q++){ if(s.substr(i,FN[q].length).toLowerCase()===FN[q]){ hit=FN[q]; break; } }
      if(hit==='pi'){ toks.push({k:'v',v:'#'}); i+=2; continue; }
      if(hit){ toks.push({k:'f',v:hit}); i+=hit.length; continue; }
      toks.push({k:'v',v:ch}); i++; continue; }
    if('+-*/^()|'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  // absolute value bars -> abs( )
  var t2=[],open=false; for(var a=0;a<toks.length;a++){ var tk=toks[a]; if(tk.k==='|'){ if(!open){ t2.push({k:'f',v:'abs'}); t2.push({k:'('}); open=true; } else { t2.push({k:')'}); open=false; } } else t2.push(tk); }
  toks=t2;
  var out=[];
  for(var t=0;t<toks.length;t++){ var A=toks[t], B=out[out.length-1];
    if(B&&(B.k==='n'||B.k==='v'||B.k===')')&&(A.k==='n'||A.k==='v'||A.k==='('||A.k==='f')) out.push({k:'&'});
    out.push(A); }
  var p=0; function pk(){ return out[p]; }
  var F={sqrt:Math.sqrt,ln:Math.log,log:function(x){return Math.log(x)/Math.LN10;},exp:Math.exp,sin:Math.sin,cos:Math.cos,tan:Math.tan,
    sec:function(x){return 1/Math.cos(x);},csc:function(x){return 1/Math.sin(x);},cot:function(x){return 1/Math.tan(x);},abs:Math.abs};
  function E(){ var n=T(); while(pk()&&(pk().k==='+'||pk().k==='-')){ var o=out[p++].k,r=T(); n=(function(l,r,o){return function(e){return o==='+'?l(e)+r(e):l(e)-r(e);};})(n,r,o);} return n; }
  function T(){ var n=I(); while(pk()&&(pk().k==='*'||pk().k==='/')){ var o=out[p++].k,r=I(); n=(function(l,r,o){return function(e){return o==='*'?l(e)*r(e):l(e)/r(e);};})(n,r,o);} return n; }
  function I(){ var n=U(); while(pk()&&pk().k==='&'){ p++; var r=P(); n=(function(l,r){return function(e){return l(e)*r(e);};})(n,r);} return n; }
  function U(){ if(pk()&&pk().k==='-'){ p++; var u=U(); return function(e){return -u(e);}; } if(pk()&&pk().k==='+'){ p++; return U(); } return P(); }
  function P(){ var b=Aa(); if(pk()&&pk().k==='^'){ p++; var x=U(); return function(e){return Math.pow(b(e),x(e));}; } return b; }
  function Aa(){ var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){return t.v;};
    if(t.k==='v'){ if(t.v==='#') return function(){return Math.PI;}; if(t.v==='e') return function(){return Math.E;}; return function(e){return e[t.v];}; }
    if(t.k==='('){ var n=E(); if(!pk()||pk().k!==')') throw 0; p++; return n; }
    if(t.k==='f'){ var fn=F[t.v]; var ex=null;
      if(pk()&&pk().k==='^'){ p++; ex=Aa(); if(pk()&&pk().k==='&') p++; }            // sin^2(x)
      var arg; if(pk()&&pk().k==='('){ p++; arg=E(); if(!pk()||pk().k!==')') throw 0; p++; } else arg=P();
      return ex? function(e){ return Math.pow(fn(arg(e)),ex(e)); } : function(e){ return fn(arg(e)); }; }
    throw 0; }
  try{ var f=E(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function calcEqual(input,answer){
  var f=calcCompile(input), g=calcCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<14;trial++){
    var env={}; 'abcdfghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=0.35+Math.random()*2.3; });
    var x=f(env), y=g(env); if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-6*Math.max(1,Math.abs(x),Math.abs(y))) return false; hits++;
  }
  return hits>=4;
}
(function(){
  var _am=answerMatches;
  answerMatches=function(input,answer,accept,expr){
    if(expr==='calc'){ if(input===undefined||input===null||String(input).trim()==='') return false;
      if(calcEqual(input,answer)) return true; return (accept||[]).some(function(a){ return calcEqual(input,a); }); }
    return _am.apply(this,arguments); };
  var _kl=kbLayoutFor;
  kbLayoutFor=function(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; if(stp.expr==='calc') return 'calc'; }catch(e){} return _kl(inp); };
  var _kp=kbPress;
  kbPress=function(k){ var m={'eˣ':'e^(','√':'√(','ln':'ln(','sin':'sin(','cos':'cos(','tan':'tan('}; if(KB.page==='calc'&&m[k]){ kbInsert(m[k]); return; } return _kp(k); };
})();

renderLogin();
})();
</script>
</body>
</html>

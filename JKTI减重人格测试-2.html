<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JKTI · 减重人格测试</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;600&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#FAF8F3;
  --surface:#FFFFFF;
  --border:#E8E3DA;
  --text:#1A1A16;
  --text-muted:#7A7468;
  --text-light:#B0AA9F;
  --green:#4A7C59;
  --green-light:#EAF3E8;
  --coral:#E07B6A;
  --serif:'Noto Serif SC',serif;
  --sans:'DM Sans',sans-serif;
  --r:16px;
  --r-sm:10px;
  --shadow:0 2px 24px rgba(0,0,0,0.07);
}
html{scroll-behavior:smooth}
body{font-family:var(--sans);background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden}

.screen{display:none;min-height:100vh}
.screen.active{display:flex;flex-direction:column}

/* ── HOME ── */
#home{align-items:center;justify-content:center;padding:2rem}
.home-inner{max-width:560px;width:100%;text-align:center}
.logo{display:inline-flex;align-items:center;gap:10px;margin-bottom:3rem}
.logo-mark{width:38px;height:38px;background:var(--green);border-radius:10px;display:flex;align-items:center;justify-content:center}
.logo-mark svg{width:20px;height:20px;fill:white}
.logo-wordmark{font-family:var(--serif);font-size:18px;font-weight:600;letter-spacing:0.12em;color:var(--text)}
.home-eyebrow{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--green);font-weight:500;margin-bottom:1rem}
.home-title{font-family:var(--serif);font-size:clamp(28px,5vw,44px);line-height:1.25;margin-bottom:1.25rem;font-weight:600}
.home-title em{font-style:normal;color:var(--coral)}
.home-sub{font-size:15px;color:var(--text-muted);line-height:1.7;margin-bottom:2.5rem}
.badge-row{display:flex;justify-content:center;gap:8px;margin-bottom:2.5rem;flex-wrap:wrap}
.badge{font-size:11px;padding:5px 12px;border-radius:20px;border:1px solid var(--border);color:var(--text-muted);background:var(--surface)}
.start-btn{display:inline-flex;align-items:center;gap:10px;background:var(--green);color:white;font-family:var(--sans);font-size:15px;font-weight:500;padding:14px 32px;border-radius:40px;border:none;cursor:pointer;transition:all .2s}
.start-btn:hover{background:#3a6347;transform:translateY(-1px)}
.start-btn svg{width:16px;height:16px;fill:white}
.type-preview{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:3rem}
.type-chip{background:var(--surface);border:1px solid var(--border);border-radius:var(--r-sm);padding:14px 16px;text-align:left;filter:blur(3px);opacity:.5;user-select:none}
.type-chip-icon{font-size:20px;margin-bottom:6px}
.type-chip-name{font-size:13px;font-weight:500}
.type-chip-en{font-size:11px;color:var(--text-muted)}
.unlock-hint{font-size:12px;color:var(--text-light);margin-top:10px}

/* ── QUIZ ── */
#quiz{padding:0}
.quiz-topbar{position:sticky;top:0;z-index:10;background:var(--bg);border-bottom:1px solid var(--border);padding:1rem 1.5rem}
.quiz-topbar-inner{max-width:600px;margin:0 auto}
.progress-meta{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.progress-qnum{font-size:13px;font-weight:500;color:var(--text)}
.progress-section{font-size:12px;color:var(--text-muted)}
.progress-track{height:4px;background:var(--border);border-radius:2px;overflow:hidden}
.progress-fill{height:100%;background:var(--green);border-radius:2px;transition:width .4s ease}

.quiz-body{max-width:600px;width:100%;margin:0 auto;padding:1.5rem;flex:1;display:flex;flex-direction:column}

.section-divider{text-align:center;padding:.5rem 0 1.25rem}
.section-divider-inner{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:1.5rem 2rem;display:inline-block}
.section-divider-icon{font-size:28px;margin-bottom:.5rem}
.section-divider-title{font-family:var(--serif);font-size:16px;font-weight:600;margin-bottom:.25rem}
.section-divider-sub{font-size:13px;color:var(--text-muted)}

.question-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:1.75rem;box-shadow:var(--shadow);animation:slideIn .25s ease}
@keyframes slideIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}
.q-num{font-size:12px;color:var(--text-light);margin-bottom:.6rem;letter-spacing:.04em}
.q-text{font-family:var(--serif);font-size:18px;line-height:1.55;font-weight:600;margin-bottom:1.5rem}
.options{display:flex;flex-direction:column;gap:9px}
.option{display:flex;align-items:flex-start;gap:12px;padding:13px 15px;border:1.5px solid var(--border);border-radius:var(--r-sm);cursor:pointer;transition:all .15s;background:var(--bg)}
.option:hover{border-color:var(--green);background:var(--green-light)}
.option.selected{border-color:var(--green);background:var(--green-light)}
.option-dot{width:20px;height:20px;min-width:20px;border-radius:50%;border:1.5px solid var(--border);display:flex;align-items:center;justify-content:center;transition:all .15s;margin-top:1px}
.option.selected .option-dot{background:var(--green);border-color:var(--green)}
.check-icon{width:10px;height:10px;opacity:0;transition:opacity .12s}
.option.selected .check-icon{opacity:1}
.option-text{font-size:14px;line-height:1.55}

/* ── QUIZ NAV ── */
.quiz-nav{display:flex;align-items:center;justify-content:space-between;margin-top:1.25rem;gap:10px}
.back-btn{display:flex;align-items:center;gap:6px;padding:10px 16px;border-radius:30px;border:1.5px solid var(--border);background:var(--surface);cursor:pointer;font-family:var(--sans);font-size:13px;color:var(--text-muted);transition:all .15s;white-space:nowrap}
.back-btn:hover:not(:disabled){border-color:#B0AA9F;color:var(--text);background:var(--bg)}
.back-btn:disabled{opacity:.25;cursor:not-allowed}
.back-btn svg{width:14px;height:14px;fill:currentColor}
.back-btn .back-label{display:inline}
.next-btn{display:flex;align-items:center;gap:8px;padding:11px 24px;border-radius:30px;border:none;background:var(--green);color:white;cursor:pointer;font-family:var(--sans);font-size:14px;font-weight:500;transition:all .15s;white-space:nowrap;margin-left:auto}
.next-btn:hover:not(:disabled){background:#3a6347}
.next-btn:disabled{opacity:.35;cursor:not-allowed}
.next-btn svg{width:14px;height:14px;fill:white}

/* modified indicator */
.modified-tag{font-size:11px;color:var(--green);background:var(--green-light);padding:3px 9px;border-radius:20px;border:1px solid #C5DFC7;display:none}
.modified-tag.show{display:inline-block}

/* ── LOADING ── */
#loading{align-items:center;justify-content:center;text-align:center}
.loading-inner{max-width:340px;padding:2rem}
.loading-orb{width:80px;height:80px;border-radius:50%;background:var(--green);margin:0 auto 2rem;display:flex;align-items:center;justify-content:center;animation:pulse 1.5s ease-in-out infinite}
@keyframes pulse{0%,100%{transform:scale(1);opacity:1}50%{transform:scale(1.08);opacity:.85}}
.loading-orb svg{width:36px;height:36px;fill:white}
.loading-title{font-family:var(--serif);font-size:22px;font-weight:600;margin-bottom:.75rem}
.loading-sub{font-size:14px;color:var(--text-muted);line-height:1.6}
.loading-steps{margin-top:2rem;display:flex;flex-direction:column;gap:10px}
.loading-step{display:flex;align-items:center;gap:10px;padding:10px 14px;border-radius:var(--r-sm);background:var(--surface);border:1px solid var(--border);font-size:13px;color:var(--text-muted);opacity:0;transition:opacity .4s,color .4s}
.loading-step.active{opacity:1;color:var(--green)}
.loading-step.done{opacity:1;color:var(--text)}
.loading-step-dot{width:8px;height:8px;min-width:8px;border-radius:50%;background:var(--border);transition:background .4s}
.loading-step.active .loading-step-dot,.loading-step.done .loading-step-dot{background:var(--green)}

/* ── RESULT ── */
#result{overflow-y:auto;padding:1.5rem}
.result-inner{max-width:600px;width:100%;margin:0 auto}
.result-header{text-align:center;padding:2rem 0 1.5rem;border-bottom:1px solid var(--border);margin-bottom:1.25rem}
.result-type-badge{display:inline-block;font-size:11px;letter-spacing:.1em;text-transform:uppercase;padding:5px 14px;border-radius:20px;font-weight:500;margin-bottom:1rem}
.result-emoji{font-size:52px;margin-bottom:.75rem;display:block}
.result-type-name{font-family:var(--serif);font-size:30px;font-weight:600;margin-bottom:.3rem}
.result-type-en{font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);margin-bottom:1.25rem}
.result-tagline{font-size:14px;line-height:1.7;color:var(--text-muted);max-width:420px;margin:0 auto}

.result-section{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:1.5rem;margin-bottom:1rem}
.result-section-title{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);font-weight:500;margin-bottom:1rem}

.strength-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.strength-card{padding:14px;border-radius:var(--r-sm);border:1px solid var(--border)}
.strength-card-label{font-size:11px;text-transform:uppercase;letter-spacing:.08em;font-weight:500;margin-bottom:.5rem}
.strength-card-text{font-size:13px;line-height:1.55}

.score-bars{display:flex;flex-direction:column;gap:12px}
.score-bar-row{display:flex;align-items:center;gap:12px}
.score-bar-label{font-size:12px;width:90px;min-width:90px;color:var(--text-muted)}
.score-bar-track{flex:1;height:6px;background:var(--border);border-radius:3px;overflow:hidden}
.score-bar-fill{height:100%;border-radius:3px;transition:width 1s ease .3s}
.score-bar-val{font-size:13px;font-weight:500;min-width:24px;text-align:right}

.advice-list{display:flex;flex-direction:column;gap:10px}
.advice-item{display:flex;gap:12px;align-items:flex-start}
.advice-num{width:24px;height:24px;min-width:24px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:500}
.advice-text{font-size:14px;line-height:1.6}

.other-types{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
.other-type-card{padding:12px;border-radius:var(--r-sm);border:1px solid var(--border);text-align:center}
.other-type-emoji{font-size:22px;margin-bottom:4px}
.other-type-name{font-size:11px;font-weight:500;line-height:1.3}
.other-type-score{font-size:11px;color:var(--text-muted);margin-top:2px}

.result-actions{display:flex;gap:10px;margin-top:1.5rem;flex-wrap:wrap}
.action-btn{flex:1;padding:12px 18px;border-radius:30px;font-family:var(--sans);font-size:14px;font-weight:500;cursor:pointer;border:1px solid var(--border);transition:all .15s;background:transparent;min-width:120px}
.action-btn.primary{background:var(--green);color:white;border-color:var(--green)}
.action-btn.primary:hover{background:#3a6347}
.action-btn:hover{border-color:#B0AA9F}
.retake-wrap{text-align:center;margin-top:1rem}
.retake-btn{background:none;border:none;color:var(--text-muted);font-size:13px;cursor:pointer;text-decoration:underline;font-family:var(--sans)}

/* ── MODAL ── */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.5);display:none;align-items:center;justify-content:center;z-index:100;padding:1.5rem}
.modal-overlay.show{display:flex}
.modal{background:var(--surface);border-radius:var(--r);max-width:380px;width:100%;overflow:hidden}
.share-card{padding:2rem;text-align:center;background:var(--bg)}
.share-card-logo{font-family:var(--serif);font-size:13px;font-weight:600;letter-spacing:.1em;color:var(--text-muted);margin-bottom:1.5rem}
.share-card-emoji{font-size:48px;margin-bottom:.75rem}
.share-card-type{font-family:var(--serif);font-size:24px;font-weight:600;margin-bottom:.35rem}
.share-card-en{font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);margin-bottom:1rem}
.share-card-quote{font-size:13px;color:var(--text-muted);line-height:1.6;border-top:1px solid var(--border);padding-top:1rem}
.share-card-cta{font-size:12px;color:var(--text-light);margin-top:1rem}
.modal-actions{padding:1rem 1.5rem;display:flex;gap:8px;border-top:1px solid var(--border)}
.modal-btn{flex:1;padding:10px;border-radius:20px;font-family:var(--sans);font-size:13px;font-weight:500;cursor:pointer;border:1px solid var(--border);background:transparent;transition:all .15s}
.modal-btn.primary{background:var(--green);color:white;border-color:var(--green)}
.modal-btn.primary:hover{background:#3a6347}

@media(max-width:480px){
  .strength-grid{grid-template-columns:1fr}
  .result-actions{flex-direction:column}
  .back-btn .back-label{display:none}
}
</style>
</head>
<body>

<!-- ══ HOME ══ -->
<div class="screen active" id="home">
<div class="home-inner">
  <div class="logo">
    <div class="logo-mark">
      <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 100 20A10 10 0 0012 2zm0 3a2 2 0 110 4 2 2 0 010-4zm0 14.5c-2.5 0-4.71-1.28-6-3.22.03-1.99 4-3.08 6-3.08 1.99 0 5.97 1.09 6 3.08A7.13 7.13 0 0112 19.5z"/></svg>
    </div>
    <span class="logo-wordmark">JKTI</span>
  </div>
  <div class="home-eyebrow">减重人格测试</div>
  <h1 class="home-title">你的减肥一直失败<br>可能只是<em>用错了方法</em></h1>
  <p class="home-sub">16道题，测出你的减重人格类型。<br>找到真正适合你的方式，而不是别人的方式。</p>
  <div class="badge-row">
    <span class="badge">基于 DEBQ 临床量表</span>
    <span class="badge">TFEQ 三因素饮食模型</span>
    <span class="badge">约 3 分钟</span>
  </div>
  <button class="start-btn" onclick="startQuiz()">
    开始测试
    <svg viewBox="0 0 24 24"><path d="M8.59 16.59L13.17 12 8.59 7.41 10 6l6 6-6 6z"/></svg>
  </button>
  <div class="type-preview">
    <div class="type-chip"><div class="type-chip-icon">👑</div><div class="type-chip-name">自律的神</div><div class="type-chip-en">KING</div></div>
    <div class="type-chip"><div class="type-chip-icon">🧘</div><div class="type-chip-name">减肥圣体</div><div class="type-chip-en">MONK</div></div>
    <div class="type-chip"><div class="type-chip-icon">🍚</div><div class="type-chip-name">干饭人</div><div class="type-chip-en">EATER</div></div>
    <div class="type-chip"><div class="type-chip-icon">🐟</div><div class="type-chip-name">仰卧起坐选手</div><div class="type-chip-en">FISH</div></div>
  </div>
  <div class="unlock-hint">完成测试后解锁你的专属人格报告</div>
</div>
</div>

<!-- ══ QUIZ ══ -->
<div class="screen" id="quiz">
  <div class="quiz-topbar">
    <div class="quiz-topbar-inner">
      <div class="progress-meta">
        <span class="progress-qnum" id="q-count">第 1 题 / 共 16 题</span>
        <span class="modified-tag" id="modified-tag">已修改</span>
        <span class="progress-section" id="q-section-label">饮食行为</span>
      </div>
      <div class="progress-track"><div class="progress-fill" id="progress-fill" style="width:6%"></div></div>
    </div>
  </div>
  <div class="quiz-body">
    <div id="quiz-content"></div>
    <div class="quiz-nav">
      <button class="back-btn" id="prev-btn" onclick="prevQuestion()" disabled>
        <svg viewBox="0 0 24 24"><path d="M15.41 16.59L10.83 12l4.58-4.59L14 6l-6 6 6 6z"/></svg>
        <span class="back-label">返回修改</span>
      </button>
      <button class="next-btn" id="next-btn" onclick="nextQuestion()" disabled>
        <span id="next-label">下一题</span>
        <svg viewBox="0 0 24 24"><path d="M8.59 16.59L13.17 12 8.59 7.41 10 6l6 6-6 6z"/></svg>
      </button>
    </div>
  </div>
</div>

<!-- ══ LOADING ══ -->
<div class="screen" id="loading">
<div class="loading-inner">
  <div class="loading-orb">
    <svg viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>
  </div>
  <div class="loading-title">正在分析你的<br>减重人格…</div>
  <div class="loading-sub">根据 DEBQ 与 TFEQ 临床模型<br>为你生成专属报告</div>
  <div class="loading-steps">
    <div class="loading-step" id="ls1"><div class="loading-step-dot"></div>分析饮食行为模式…</div>
    <div class="loading-step" id="ls2"><div class="loading-step-dot"></div>评估情绪进食倾向…</div>
    <div class="loading-step" id="ls3"><div class="loading-step-dot"></div>测量行为执行力指数…</div>
    <div class="loading-step" id="ls4"><div class="loading-step-dot"></div>匹配人格类型…</div>
  </div>
</div>
</div>

<!-- ══ RESULT ══ -->
<div class="screen" id="result">
<div class="result-inner">
  <div class="result-header">
    <div class="result-type-badge" id="result-badge"></div>
    <div class="result-emoji" id="result-emoji"></div>
    <div class="result-type-name" id="result-name"></div>
    <div class="result-type-en" id="result-en"></div>
    <div class="result-tagline" id="result-tagline"></div>
  </div>
  <div class="result-section">
    <div class="result-section-title">各维度得分</div>
    <div class="score-bars" id="score-bars"></div>
  </div>
  <div class="result-section">
    <div class="result-section-title">优势 & 盲点</div>
    <div class="strength-grid" id="strength-grid"></div>
  </div>
  <div class="result-section">
    <div class="result-section-title">给你的行动建议</div>
    <div class="advice-list" id="advice-list"></div>
  </div>
  <div class="result-section">
    <div class="result-section-title">其他人格类型得分</div>
    <div class="other-types" id="other-types"></div>
  </div>
  <div class="result-actions">
    <button class="action-btn primary" onclick="showShare()">生成分享卡片</button>
    <button class="action-btn" onclick="copyText()">复制结果文案</button>
  </div>
  <div class="retake-wrap"><button class="retake-btn" onclick="retake()">重新测试</button></div>
  <div style="height:2rem"></div>
</div>
</div>

<!-- ══ EASTER EGG RESULT ══ -->
<div class="screen" id="result-kfc">
<div class="result-inner">
  <div class="result-header" style="border-color:#E8C84A40">
    <div class="result-type-badge" style="background:#FFF3C4;color:#B8860B;border:1px solid #E8C84A">KFCER · 隐藏人格</div>
    <div class="result-emoji" style="font-size:60px;margin:1rem 0">🍗</div>
    <div class="result-type-name" style="color:#CC2200">VIVO-50</div>
    <div class="result-type-en" style="color:#B8860B;margin-bottom:1.25rem">THE KFCER</div>
    <div class="result-tagline" style="color:var(--text-muted)">你解锁了隐藏人格。因为今天就是疯狂星期四。</div>
  </div>

  <div class="result-section" style="border-color:#E8C84A60;background:#FFFDF0">
    <div class="result-section-title" style="color:#B8860B">人格核心说明</div>
    <div style="font-size:14px;line-height:2;color:var(--text)">
      因为今天就是<strong style="color:#CC2200">疯狂星期四</strong>啊，<br>
      如果不是疯狂星期四我为什么要提疯狂星期四呢？<br>
      如果我不提疯狂星期四，你怎么会知道今天是疯狂星期四呢，<br>
      如果我提了疯狂星期四你没有注意听今天是疯狂星期四，<br>
      那我不是白说疯狂星期四了吗？
    </div>
  </div>

  <div class="result-section" style="border-color:#E8C84A60">
    <div class="result-section-title">你的核心特征</div>
    <div class="strength-grid">
      <div class="strength-card" style="background:#FFF3C4;border-color:#E8C84A60">
        <div class="strength-card-label" style="color:#B8860B">✦ 你的优势</div>
        <div class="strength-card-text">对疯狂星期四的感知能力远超常人，甚至能在周四下午精准触发疯狂星期四模式，无需任何外部提示</div>
      </div>
      <div class="strength-card" style="background:#FFF0EE;border-color:#E8A090">
        <div class="strength-card-label" style="color:#CC2200">⚠ 注意盲点</div>
        <div class="strength-card-text">每周四都会有一笔"计划外支出"，且无法解释给任何人听，包括你自己</div>
      </div>
    </div>
  </div>

  <div class="result-section" style="border-color:#E8C84A60">
    <div class="result-section-title">给你的行动建议</div>
    <div class="advice-list">
      <div class="advice-item">
        <div class="advice-num" style="background:#FFF3C4;color:#B8860B">1</div>
        <div class="advice-text">发现今天是疯狂星期四之后，立刻给群里50个人发"疯狂星期四 V我50"，这样就有人请你吃了，热量不算你的</div>
      </div>
      <div class="advice-item">
        <div class="advice-num" style="background:#FFF3C4;color:#B8860B">2</div>
        <div class="advice-text">疯狂星期四属于不可抗力事件，建议在减肥计划备注栏写明"每周四豁免"，以维护计划的严肃性</div>
      </div>
      <div class="advice-item">
        <div class="advice-num" style="background:#FFF3C4;color:#B8860B">3</div>
        <div class="advice-text">周五从零开始，不要想周四的事，周四的卡路里在疯狂星期四结束时自动清零（本测试不为此负责）</div>
      </div>
    </div>
  </div>

  <div class="result-section" style="text-align:center;border-style:dashed;border-color:#E8C84A">
    <div style="font-size:12px;color:var(--text-muted);margin-bottom:.75rem">你是全站 <strong style="color:#CC2200">0.001%</strong> 触发隐藏人格的用户</div>
    <div style="font-size:13px;color:var(--text-muted);line-height:1.7">这道题的正确答案不存在。<br>但你选了它。这说明了一切。</div>
  </div>

  <div class="result-actions">
    <button class="action-btn primary" style="background:#CC2200;border-color:#CC2200" onclick="copyKfcText()">复制疯狂文案</button>
    <button class="action-btn" onclick="startQuiz()">重新测试（认真版）</button>
  </div>
  <div style="height:2rem"></div>
</div>
</div>

<!-- ══ MODAL ══ -->
<div class="modal-overlay" id="modal" onclick="closeModal(event)">
<div class="modal">
  <div class="share-card">
    <div class="share-card-logo">JKTI · 减重人格测试</div>
    <div class="share-card-emoji" id="sc-emoji"></div>
    <div class="share-card-type" id="sc-type"></div>
    <div class="share-card-en" id="sc-en"></div>
    <div class="share-card-quote" id="sc-quote"></div>
    <div class="share-card-cta">测测你是哪种 → jkti.me</div>
  </div>
  <div class="modal-actions">
    <button class="modal-btn" onclick="closeModal()">关闭</button>
    <button class="modal-btn primary" onclick="copyShareText()">复制分享文案</button>
  </div>
</div>
</div>

<script>
const QUESTIONS=[
  {section:'饮食行为',text:'周四下午，你突然想吃东西，你决定…',options:[
    {text:'先查一下距离晚饭还有多少时间，算算是否在"配额"内',type:'A'},
    {text:'肚子真的有点饿了才吃，吃一小把坚果就过了',type:'B'},
    {text:'打开外卖，看到什么好吃点什么——反正就是嘴馋',type:'C'},
    {text:'今天是星期四……',type:'E'}
  ]},
  {section:'饮食行为',text:'你在点外卖时，通常会做什么？',options:[
    {text:'看标注热量，优先选500kcal以内的',type:'A'},
    {text:'点喜欢的，但下单前会想一下上一顿吃了什么',type:'B'},
    {text:'今天心情不好，点最能让我开心的那个',type:'C'},
    {text:'研究了20分钟健康选项，最后还是下单了麻辣烫',type:'D'}
  ]},
  {section:'饮食行为',text:'如果某天不小心"吃多了"，你的第一反应是？',options:[
    {text:'打开App记录，调整明天的摄入计划',type:'A'},
    {text:'下顿少吃点或明天多走几步，不纠结',type:'B'},
    {text:'今天反正毁了，晚上继续吃（破罐破摔）',type:'C'},
    {text:'陷入自责，发誓明天开始严格执行，认真写计划',type:'D'}
  ]},
  {section:'饮食行为',text:'你上一次因为"心情不好"而进食是什么时候？',options:[
    {text:'很少，我吃东西主要因为到了饭点',type:'A'},
    {text:'偶尔，但通常情绪过去了就不一定非要吃',type:'B'},
    {text:'几乎每周都有，情绪一来手就先动了',type:'C'},
    {text:'有，事后我会反思自己又情绪性进食了（然后继续）',type:'D'}
  ]},
  {section:'饮食行为',text:'公司楼下开了新奶茶店，你会…',options:[
    {text:'查了下热量，偶尔买一杯三分糖',type:'A'},
    {text:'想喝就喝，不想喝不会特地去',type:'B'},
    {text:'每次路过都很难拒绝，买了再说',type:'C'},
    {text:'纠结了3天，最终去了，然后后悔',type:'D'}
  ]},
  {section:'饮食行为',text:'你觉得自己对"饿"和"馋"的区分是？',options:[
    {text:'分得很清楚，馋的时候我会用喝水来压制',type:'A'},
    {text:'基本能感觉到，真饿了才吃',type:'B'},
    {text:'老实说没什么区别……都是想吃',type:'C'},
    {text:'理论上知道怎么区分，实际上很难执行',type:'D'}
  ]},
  {section:'饮食行为',text:'周末朋友圈出现"炸鸡无限续"广告，你…',options:[
    {text:'算过了，周末有一顿可以放松，要去',type:'A'},
    {text:'如果朋友叫一起行，不会特地为炸鸡出门',type:'B'},
    {text:'已经开始想叫外卖了',type:'C'},
    {text:'看了半小时评价，关掉，又打开，最终还是点了',type:'D'}
  ]},
  {section:'饮食行为',text:'你觉得你和食物的关系是？',options:[
    {text:'有点复杂——我爱它，但不能让它控制我',type:'A'},
    {text:'挺简单的，吃饱了开心就行',type:'B'},
    {text:'食物是我最可靠的情绪出口之一',type:'C'},
    {text:'我知道"正确关系"应该是什么样，但还没做到',type:'D'}
  ]},
  {section:'运动与执行力',text:'你上一次认真运动（心跳明显加快、持续20分钟+）是什么时候？',options:[
    {text:'就是今天或昨天',type:'A'},
    {text:'3天以内，有基本固定的运动习惯',type:'B'},
    {text:'上个月？或者更久了……',type:'C'},
    {text:'上周，但在这之前已经断了一个月',type:'D'}
  ]},
  {section:'运动与执行力',text:'公司通知下周"健康打卡挑战"，每天走8000步，你的反应是？',options:[
    {text:'已经每天走超了，但要研究怎么进一步优化',type:'A'},
    {text:'行，稍微注意一下步数就够了',type:'B'},
    {text:'先打卡，反正手机放包里摇一摇也算',type:'C'},
    {text:'第一天打卡了，第二天加班忘了，第三天就放弃了',type:'D'}
  ]},
  {section:'运动与执行力',text:'你手机里健康/运动相关App数量是？',options:[
    {text:'3个以上，且都在活跃使用',type:'A'},
    {text:'最多1个，偶尔看看',type:'B'},
    {text:'下载过，都卸载了',type:'C'},
    {text:'3个以上，但大部分已经很久没打开了',type:'D'}
  ]},
  {section:'运动与执行力',text:'你是否制定过"减脂计划"？',options:[
    {text:'制定过多次，并且基本按计划执行',type:'A'},
    {text:'没有详细计划，但有一些基本习惯',type:'B'},
    {text:'没怎么认真制定过',type:'C'},
    {text:'制定过很多次，执行率……你懂的',type:'D'}
  ]},
  {section:'运动与执行力',text:'加班到晚上9点，你的状态是？',options:[
    {text:'累了，但已经规划好明天的恢复方案',type:'A'},
    {text:'累了，回家洗澡睡觉，明天继续',type:'B'},
    {text:'必须吃点好的+刷手机，不然这一天白过了',type:'C'},
    {text:'累到不想动，告诉自己今天特殊，明天一定要补回来',type:'D'}
  ]},
  {section:'运动与执行力',text:'关于运动，你最认同哪句话？',options:[
    {text:'运动是健康管理系统的一部分，要量化才有意义',type:'A'},
    {text:'运动让我感觉好，所以我运动',type:'B'},
    {text:'运动好是好，就是太累了，而且我不胖也可以',type:'C'},
    {text:'我完全支持运动，等我这段忙完就开始',type:'D'}
  ]},
  {section:'运动与执行力',text:'你的同事说"我最近在节食减肥，超难受"，你的第一反应是？',options:[
    {text:'"有没有用什么记录工具？我推荐几个App给你"',type:'A'},
    {text:'"为什么要节食？正常吃然后多动不好吗？"',type:'B'},
    {text:'"我懂！一减肥就想吃！要不要一起吃点东西聊聊？"',type:'C'},
    {text:'"我也想减来着……你是怎么开始的，能教我吗？"',type:'D'}
  ]},
  {section:'运动与执行力',text:'如果要开始一个新的健康计划，你最可能的开局是？',options:[
    {text:'先制定详细执行表格，按周计划，有KPI',type:'A'},
    {text:'先做一件最简单的小事，比如明天走路上班',type:'B'},
    {text:'先等一个"好的开始节点"，比如下个月1号',type:'C'},
    {text:'查了大量资料，写了份完美计划，然后……还没开始',type:'D'}
  ]}
];

const TYPES={
  A:{name:'自律的神',en:'KING',emoji:'👑',color:'#2D6A8F',bg:'#E8F2F8',
    tagline:'每100g鸡胸肉含22g蛋白质你如数家珍，减肥计划有KPI有复盘。偶尔一次破戒，就会触发全盘崩溃模式——"反正今天已经毁了"。',
    strength:'目标清晰，自我监控意识极强，能用数据驱动行为改变',
    blind:'完美主义陷阱——轻微偏差就触发"全有或全无"模式，破戒后反而越吃越多',
    advice:['允许自己20%的弹性空间，不完美的执行比放弃有价值100倍','尝试每周设定一个"不记录日"，训练直觉饮食能力','当破戒发生，用好奇而非自责去观察自己——这是数据，不是失败']
  },
  B:{name:'减肥圣体',en:'MONK',emoji:'🧘',color:'#5A8F5C',bg:'#EBF3EB',
    tagline:'你没有减肥计划，但保持着神秘的自律——每周运动、吃到七分饱就放筷子。被同事问"你咋减肥的"，本人一脸懵：我没减啊？',
    strength:'心理压力低、可持续性强，天然接近直觉饮食，是最理想的减重心态模型',
    blind:'感知偶尔不准，容易低估久坐的长期影响，代谢减慢时难以察觉',
    advice:['补充基础营养知识即可，维持现有习惯是你的核心优势，不需要大幅改变','每季度做一次简单体测，作为健康趋势参考（不需要天天量）','保持运动多样性，避免单一运动带来的适应性平台期']
  },
  C:{name:'干饭人',en:'EATER',emoji:'🍚',color:'#C4623B',bg:'#FBF0EE',
    tagline:'DDL一到，手已经打开了饿了么。难过要吃、高兴要吃、无聊也要吃。知道自己在情绪性进食，但吃的那一刻真的管不了那么多。',
    strength:'对食物有真实感知，生活体验感强，情感丰富——这是人性，不是缺陷',
    blind:'以食物作为情绪调节的主要工具，形成触发回路，在高压工作时尤其明显',
    advice:['不要先改饮食，先改情绪管理——建立"吃之前等5分钟"的暂停机制','用便利贴在冰箱门写下：我现在是饿了还是有情绪？（听起来蠢但有用）','找到1-2个食物以外的情绪出口：5分钟散步、发语音给朋友、拼图或涂色']
  },
  D:{name:'仰卧起坐选手',en:'FISH',emoji:'🐟',color:'#7B6FA8',bg:'#F0EEF8',
    tagline:'收藏夹存了300个减肥攻略，背得出生酮/低碳/断食的所有原理，每周日晚上都会制定计划。但计划永远从"下周一"开始。',
    strength:'知识储备充足，认知层面完全在线，一旦启动执行力会爆发式释放',
    blind:'决策疲劳导致执行永远被推迟，用"计划感"替代"行动感"获得心理满足',
    advice:['关掉收藏攻略的冲动，今天走了1000步比计划走10000步有用','用"最小行动单位"启动：先做1分钟运动也算，完美计划不如残缺执行','用环境设计代替意志力：把健康食物放冰箱最显眼处，把运动装备放门口']
  }
};

let currentQ=0;
let answers=new Array(16).fill(null);

function showScreen(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  window.scrollTo(0,0);
}

function startQuiz(){
  currentQ=0;
  answers=new Array(16).fill(null);
  renderQuestion();
  showScreen('quiz');
}

function renderQuestion(){
  const q=QUESTIONS[currentQ];
  const showDivider=currentQ===8;
  let html='';
  if(showDivider){
    html=`<div class="section-divider">
      <div class="section-divider-inner">
        <div class="section-divider-icon">🏃</div>
        <div class="section-divider-title">第二部分：运动与执行力</div>
        <div class="section-divider-sub">接下来8题聚焦你的行为执行模式</div>
      </div>
    </div>`;
  }
  html+=`<div class="question-card">
    <div class="q-num">Q${currentQ+1} / 16</div>
    <div class="q-text">${q.text}</div>
    <div class="options">
      ${q.options.map(o=>`
        <div class="option${answers[currentQ]===o.type?' selected':''}" onclick="selectOption('${o.type}',this)">
          <div class="option-dot">
            <svg class="check-icon" viewBox="0 0 12 12"><path d="M2 6l3 3 5-5" stroke="white" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg>
          </div>
          <div class="option-text">${o.text}</div>
        </div>`).join('')}
    </div>
  </div>`;

  document.getElementById('quiz-content').innerHTML=html;

  // topbar
  document.getElementById('q-count').textContent=`第 ${currentQ+1} 题 / 共 16 题`;
  document.getElementById('q-section-label').textContent=q.section;
  document.getElementById('progress-fill').style.width=`${Math.round(((currentQ+1)/16)*100)}%`;

  // back button
  const prevBtn=document.getElementById('prev-btn');
  prevBtn.disabled=currentQ===0;

  // modified tag — show when coming back to an already-answered question
  const modTag=document.getElementById('modified-tag');
  modTag.classList.toggle('show', answers[currentQ]!==null && currentQ>0);

  // next button
  const nextBtn=document.getElementById('next-btn');
  nextBtn.disabled=answers[currentQ]===null;
  document.getElementById('next-label').textContent=currentQ===15?'查看结果':'下一题';
}

function selectOption(type,el){
  const wasAnswered=answers[currentQ]!==null;
  document.querySelectorAll('.option').forEach(o=>o.classList.remove('selected'));
  el.classList.add('selected');
  answers[currentQ]=type;
  document.getElementById('next-btn').disabled=false;
  // show modified tag if user changed an existing answer
  if(wasAnswered){
    document.getElementById('modified-tag').classList.add('show');
  }
}

function nextQuestion(){
  if(answers[currentQ]===null)return;
  if(answers[0]==='E'){showKfcResult();return;}
  if(currentQ===15){showLoading();return;}
  currentQ++;
  renderQuestion();
}

function showKfcResult(){
  showScreen('result-kfc');
}

function prevQuestion(){
  if(currentQ===0)return;
  currentQ--;
  renderQuestion();
}

function calcScores(){
  const s={A:0,B:0,C:0,D:0};
  answers.forEach(a=>{if(a)s[a]++;});
  return s;
}

function showLoading(){
  showScreen('loading');
  ['ls1','ls2','ls3','ls4'].forEach((id,i)=>{
    setTimeout(()=>document.getElementById(id).classList.add('active'),(i+1)*600);
    setTimeout(()=>{
      const el=document.getElementById(id);
      el.classList.remove('active');el.classList.add('done');
    },(i+2)*500+200);
  });
  setTimeout(showResult,3000);
}

function showResult(){
  const scores=calcScores();
  const winner=Object.entries(scores).sort((a,b)=>b[1]-a[1])[0][0];
  const t=TYPES[winner];
  showScreen('result');

  document.getElementById('result-badge').textContent=t.en;
  document.getElementById('result-badge').style.cssText=`background:${t.bg};color:${t.color};border:1px solid ${t.color}40`;
  document.getElementById('result-emoji').textContent=t.emoji;
  document.getElementById('result-name').textContent=t.name;
  document.getElementById('result-en').textContent=t.en;
  document.getElementById('result-tagline').textContent=t.tagline;

  const labels={A:'自律的神',B:'减肥圣体',C:'干饭人',D:'仰卧起坐选手'};
  const colors={A:'#2D6A8F',B:'#5A8F5C',C:'#C4623B',D:'#7B6FA8'};
  const maxS=Math.max(...Object.values(scores));
  document.getElementById('score-bars').innerHTML=Object.entries(scores).map(([k,v])=>`
    <div class="score-bar-row">
      <div class="score-bar-label">${labels[k]}</div>
      <div class="score-bar-track"><div class="score-bar-fill" style="width:${Math.round(v/maxS*100)}%;background:${colors[k]}"></div></div>
      <div class="score-bar-val" style="color:${colors[k]}">${v}</div>
    </div>`).join('');

  document.getElementById('strength-grid').innerHTML=`
    <div class="strength-card" style="background:${t.bg};border-color:${t.color}30">
      <div class="strength-card-label" style="color:${t.color}">✦ 你的优势</div>
      <div class="strength-card-text">${t.strength}</div>
    </div>
    <div class="strength-card" style="background:#FBF8F3;border-color:#E8E0D0">
      <div class="strength-card-label" style="color:#B0875C">⚠ 注意盲点</div>
      <div class="strength-card-text">${t.blind}</div>
    </div>`;

  document.getElementById('advice-list').innerHTML=t.advice.map((a,i)=>`
    <div class="advice-item">
      <div class="advice-num" style="background:${t.bg};color:${t.color}">${i+1}</div>
      <div class="advice-text">${a}</div>
    </div>`).join('');

  const others=Object.entries(scores).filter(([k])=>k!==winner).sort((a,b)=>b[1]-a[1]);
  document.getElementById('other-types').innerHTML=others.map(([k,v])=>`
    <div class="other-type-card">
      <div class="other-type-emoji">${TYPES[k].emoji}</div>
      <div class="other-type-name">${TYPES[k].name}</div>
      <div class="other-type-score" style="color:${colors[k]}">${v} 分</div>
    </div>`).join('');

  document.getElementById('sc-emoji').textContent=t.emoji;
  document.getElementById('sc-type').textContent=t.name;
  document.getElementById('sc-en').textContent=t.en;
  document.getElementById('sc-quote').textContent=t.tagline;
}

function showShare(){document.getElementById('modal').classList.add('show')}
function closeModal(e){if(!e||e.target===document.getElementById('modal'))document.getElementById('modal').classList.remove('show')}

function copyShareText(){
  const scores=calcScores();
  const winner=Object.entries(scores).sort((a,b)=>b[1]-a[1])[0][0];
  const t=TYPES[winner];
  const text=`我做了 JKTI 减重人格测试，结果是「${t.name}」${t.emoji}\n\n${t.tagline}\n\n测测你是哪种 → jkti.me`;
  navigator.clipboard.writeText(text).then(()=>alert('分享文案已复制！'));
}

function copyText(){
  const scores=calcScores();
  const winner=Object.entries(scores).sort((a,b)=>b[1]-a[1])[0][0];
  const t=TYPES[winner];
  const labels={A:'自律的神',B:'减肥圣体',C:'干饭人',D:'仰卧起坐选手'};
  const scoreStr=Object.entries(scores).map(([k,v])=>`${labels[k]}:${v}分`).join(' | ');
  const text=`【JKTI 减重人格测试结果】\n\n类型：${t.emoji} ${t.name} (${t.en})\n\n${t.tagline}\n\n各维度：${scoreStr}\n\n行动建议：\n${t.advice.map((a,i)=>`${i+1}. ${a}`).join('\n')}`;
  navigator.clipboard.writeText(text).then(()=>alert('结果文案已复制！'));
}

function retake(){startQuiz()}

function copyKfcText(){
  const text=`我做了 JKTI 减重人格测试，解锁了隐藏人格「VIVO-50」🍗\n\n因为今天就是疯狂星期四啊，如果不是疯狂星期四我为什么要提疯狂星期四呢？如果我不提疯狂星期四，你怎么会知道今天是疯狂星期四呢，如果我提了疯狂星期四你没有注意听今天是疯狂星期四，那我不是白说疯狂星期四了吗？\n\n疯狂星期四 V我50 → jkti.me`;
  navigator.clipboard.writeText(text).then(()=>alert('疯狂文案已复制！去发群了！'));
}
</script>
</body>
</html>

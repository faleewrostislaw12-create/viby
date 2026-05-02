<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Viby</title>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400;700&family=DM+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
*{box-sizing:border- фbox;margin:0;padding:0;-webkit-tap-highlight-color:transparent;user-select:none;}
:root{
  --bg:#0a0806;--card:#141210;--border:rgba(255,255,255,.08);
  --cream:#f0ebe2;--cream2:#a09080;--cream3:#5a4e44;
  --accent:#e55a28;--accent2:#f07040;
  --green:#3d9455;
  --r:28px;--rs:18px;
}
html,body{height:100%;overflow:hidden;background:#000;}
body{font-family:'DM Sans',sans-serif;color:var(--cream);max-width:430px;margin:0 auto;height:100%;display:flex;flex-direction:column;position:relative;background:var(--bg);}

/* ── ONBOARD (multi-step auth) ── */
#ob{position:fixed;inset:0;z-index:999;background:var(--bg);display:flex;flex-direction:column;overflow:hidden;transition:opacity .4s;}
#ob.gone{opacity:0;pointer-events:none;}

.ob-steps{display:flex;flex-direction:row;width:300%;height:100%;transition:transform .42s cubic-bezier(.4,0,.2,1);}
.ob-step{width:33.333%;overflow:hidden;height:100%;display:flex;flex-direction:column;align-items:center;justify-content:flex-end;padding:0 28px 52px;flex-shrink:0;}

/* Step 1 — splash */
.ob-splash-logo{font-family:'Fraunces',serif;font-size:72px;font-weight:700;letter-spacing:-4px;color:var(--cream);position:absolute;top:50%;left:50%;transform:translate(-50%,-60%);line-height:1;}
.ob-splash-logo b{color:var(--accent);}
.ob-splash-tagline{font-size:14px;color:var(--cream2);position:absolute;top:50%;left:50%;transform:translate(-50%,calc(-60% + 72px));white-space:nowrap;letter-spacing:.3px;}
.ob-auth-btns{width:100%;display:flex;flex-direction:column;gap:10px;}
.ob-auth-btn{width:100%;display:flex;align-items:center;justify-content:center;gap:10px;border:none;border-radius:var(--r);padding:16px;font-family:'DM Sans',sans-serif;font-size:15px;font-weight:600;cursor:pointer;transition:all .2s;}
.ob-auth-btn.apple{background:#fff;color:#000;}
.ob-auth-btn.apple:hover{background:#e8e8e8;}
.ob-auth-btn.phone{background:rgba(255,255,255,.08);color:var(--cream);border:1px solid rgba(255,255,255,.1);}
.ob-auth-btn.phone:hover{background:rgba(255,255,255,.13);}
.ob-auth-btn.email{background:rgba(255,255,255,.06);color:var(--cream2);border:1px solid rgba(255,255,255,.08);}
.ob-auth-btn.email:hover{background:rgba(255,255,255,.1);}
.ob-terms{font-size:11px;color:var(--cream3);text-align:center;margin-top:14px;line-height:1.6;}
.ob-terms a{color:var(--cream2);text-decoration:underline;cursor:pointer;}

/* Step 2 — phone/email input */
.ob-back{position:absolute;top:54px;left:20px;width:36px;height:36px;border-radius:50%;background:rgba(255,255,255,.07);border:none;color:var(--cream2);font-size:18px;cursor:pointer;display:flex;align-items:center;justify-content:center;}
.ob-step-title{font-family:'Fraunces',serif;font-size:28px;font-weight:700;letter-spacing:-.8px;color:var(--cream);margin-bottom:8px;text-align:center;}
.ob-step-sub{font-size:14px;color:var(--cream2);text-align:center;margin-bottom:32px;line-height:1.5;}
@keyframes up{from{opacity:0;transform:translateY(24px);}to{opacity:1;transform:translateY(0);}}
.ob-inp-big{width:100%;background:rgba(255,255,255,.07);border:1.5px solid rgba(255,255,255,.1);border-radius:var(--rs);padding:16px 18px;color:var(--cream);font-family:'DM Sans',sans-serif;font-size:16px;outline:none;margin-bottom:14px;transition:border-color .2s;letter-spacing:.3px;}
.ob-inp-big::placeholder{color:var(--cream3);}
.ob-inp-big:focus{border-color:rgba(229,90,40,.55);}
.ob-continue{width:100%;background:var(--accent);color:#fff;border:none;border-radius:var(--r);padding:17px;font-family:'Fraunces',serif;font-size:17px;font-weight:700;cursor:pointer;transition:all .2s;opacity:.35;pointer-events:none;}
.ob-continue.ready{opacity:1;pointer-events:auto;}
.ob-continue.ready:hover{background:var(--accent2);transform:translateY(-2px);}

/* Step 3 — name + username */
.ob-name-av{width:80px;height:80px;border-radius:50%;background:var(--accent);color:#fff;font-family:'Fraunces',serif;font-size:32px;font-weight:700;display:flex;align-items:center;justify-content:center;margin:0 auto 24px;box-shadow:0 4px 24px rgba(229,90,40,.4);}
.ob-inp-row{position:relative;width:100%;margin-bottom:12px;}
.ob-inp-prefix{position:absolute;left:18px;top:50%;transform:translateY(-50%);font-size:16px;color:var(--cream2);}
.ob-inp-big.with-prefix{padding-left:30px;}

/* ── MAIN APP ── */
#app{position:fixed;inset:0;display:flex;flex-direction:column;max-width:430px;margin:0 auto;overflow:hidden;opacity:0;transition:opacity .4s;}
#app.show{opacity:1;}

/* ── HEADER ── */
.hdr{position:absolute;top:0;left:0;right:0;z-index:50;padding:14px 18px;display:flex;align-items:center;justify-content:space-between;}
.hdr-logo{font-family:'Fraunces',serif;font-size:22px;font-weight:700;letter-spacing:-1px;color:#fff;text-shadow:0 2px 12px rgba(0,0,0,.5);}
.hdr-logo b{color:var(--accent);}
.hdr-right{display:flex;align-items:center;gap:10px;}
.hdr-btn{width:36px;height:36px;border-radius:50%;background:rgba(0,0,0,.4);backdrop-filter:blur(10px);border:1px solid rgba(255,255,255,.15);display:flex;align-items:center;justify-content:center;font-size:15px;cursor:pointer;color:#fff;transition:all .2s;}
.hdr-btn:hover{background:rgba(255,255,255,.15);}
.me-av{width:36px;height:36px;border-radius:50%;background:var(--accent);color:#fff;font-family:'Fraunces',serif;font-size:15px;font-weight:700;display:flex;align-items:center;justify-content:center;cursor:pointer;box-shadow:0 2px 10px rgba(229,90,40,.4);border:2px solid rgba(0,0,0,.3);}

/* ── FRIENDS PILL BUTTON ── */
.friends-pill{display:flex;align-items:center;gap:7px;background:rgba(0,0,0,.45);border:1px solid rgba(255,255,255,.18);backdrop-filter:blur(14px);border-radius:30px;padding:7px 14px 7px 10px;cursor:pointer;transition:all .2s;color:#fff;font-size:13px;font-weight:500;}
.friends-pill:hover{background:rgba(255,255,255,.12);}
.fp-avs{display:flex;}
.fp-sm-av{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:9px;font-weight:700;border:1.5px solid rgba(0,0,0,.5);margin-left:-5px;}
.fp-sm-av:first-child{margin-left:0;}
.fp-new-dot{width:7px;height:7px;border-radius:50%;background:var(--accent);box-shadow:0 0 5px rgba(229,90,40,.8);}

/* ── FRIENDS PANEL ── */
#friends-panel{position:fixed;inset:0;z-index:200;pointer-events:none;}
#friends-panel.open{pointer-events:all;}
.fp-backdrop{position:absolute;inset:0;background:rgba(0,0,0,.6);backdrop-filter:blur(6px);opacity:0;transition:opacity .3s;}
#friends-panel.open .fp-backdrop{opacity:1;}
.fp-sheet{position:absolute;bottom:0;left:0;right:0;max-width:430px;margin:0 auto;background:#181410;border-radius:28px 28px 0 0;border-top:1px solid rgba(255,255,255,.1);padding:0 0 48px;transform:translateY(100%);transition:transform .35s cubic-bezier(.16,1,.3,1);}
#friends-panel.open .fp-sheet{transform:translateY(0);}
.fp-handle{width:38px;height:4px;border-radius:2px;background:rgba(255,255,255,.14);margin:12px auto 0;}
.fp-head{display:flex;align-items:center;justify-content:space-between;padding:18px 20px 12px;}
.fp-title{font-family:'Fraunces',serif;font-size:22px;font-weight:700;letter-spacing:-.5px;color:var(--cream);}
.fp-close{width:30px;height:30px;border-radius:50%;background:rgba(255,255,255,.08);border:none;color:var(--cream2);font-size:16px;cursor:pointer;display:flex;align-items:center;justify-content:center;}
.fp-list{display:flex;flex-direction:column;gap:2px;padding:0 12px;}
.fp-item{display:flex;align-items:center;gap:14px;padding:11px 10px;border-radius:18px;cursor:pointer;transition:background .15s;}
.fp-item:hover{background:rgba(255,255,255,.06);}
.fp-item-av{width:52px;height:52px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:20px;font-weight:700;flex-shrink:0;position:relative;}
.fp-ring{position:absolute;inset:-4px;border-radius:50%;background:conic-gradient(var(--accent) 0%,#f0b050 50%,var(--accent) 100%);animation:rot 2.5s linear infinite;z-index:-1;}
@keyframes rot{to{transform:rotate(360deg);}}
.fp-ring::after{content:'';position:absolute;inset:3.5px;border-radius:50%;background:#181410;}
.fp-online{position:absolute;bottom:1px;right:1px;width:13px;height:13px;border-radius:50%;background:var(--green);border:2px solid #181410;z-index:2;}
.fp-item-info{flex:1;}
.fp-item-name{font-size:15px;font-weight:600;color:var(--cream);}
.fp-item-sub{font-size:12px;color:var(--cream2);margin-top:2px;}
.fp-badge{font-size:11px;font-weight:600;color:var(--accent);background:rgba(229,90,40,.15);border-radius:12px;padding:3px 9px;white-space:nowrap;}
.fp-add{display:flex;align-items:center;gap:14px;padding:11px 10px;border-radius:18px;cursor:pointer;transition:background .15s;margin-top:6px;}
.fp-add:hover{background:rgba(255,255,255,.05);}
.fp-add-av{width:52px;height:52px;border-radius:50%;background:rgba(255,255,255,.05);border:1.5px dashed rgba(255,255,255,.15);display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0;}
.fp-add-label{font-size:15px;color:var(--cream2);}

.new-ring{position:absolute;inset:-4px;border-radius:50%;background:conic-gradient(var(--accent) 0%,#f0b050 50%,var(--accent) 100%);animation:rot 2.5s linear infinite;z-index:-1;}
.new-ring::after{content:'';position:absolute;inset:3.5px;border-radius:50%;background:var(--bg);}
.online-dot{position:absolute;bottom:0;right:0;width:12px;height:12px;border-radius:50%;background:var(--green);border:2px solid rgba(0,0,0,.5);z-index:2;}

/* ── SWIPE PAGES ── */
#pages{flex:1;display:flex;flex-direction:column;transition:transform .35s cubic-bezier(.4,0,.2,1);height:100%;}

/* PAGE: MY CAMERA */
#page-cam{height:100%;flex-shrink:0;position:relative;display:flex;flex-direction:column;align-items:center;justify-content:center;background:#000;}

/* Camera viewfinder */
#cam-viewfinder{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;overflow:hidden;}
#cam-video{width:100%;height:100%;object-fit:cover;transform:scaleX(-1);}
#cam-canvas{display:none;}
.cam-no-cam{display:flex;flex-direction:column;align-items:center;gap:14px;text-align:center;padding:40px;}
.cam-no-cam .big-icon{font-size:72px;opacity:.4;}
.cam-no-cam p{font-size:14px;color:var(--cream2);}

/* My photo frame — shows after capture */
#my-photo-frame{position:absolute;inset:0;display:none;flex-direction:column;}
#my-photo-img{width:100%;height:100%;object-fit:cover;}
.my-photo-overlay{position:absolute;bottom:0;left:0;right:0;padding:100px 20px 140px;background:linear-gradient(transparent,rgba(0,0,0,.75));display:flex;flex-direction:column;gap:10px;}
.my-caption-inp{background:rgba(0,0,0,.4);border:1.5px solid rgba(255,255,255,.2);backdrop-filter:blur(12px);border-radius:30px;padding:12px 18px;color:#fff;font-family:'DM Sans',sans-serif;font-size:14px;outline:none;width:100%;}
.my-caption-inp::placeholder{color:rgba(255,255,255,.5);}
.send-row{display:flex;gap:10px;align-items:center;}
.who-chips{display:flex;gap:8px;flex-wrap:wrap;flex:1;}
.who-chip{display:flex;align-items:center;gap:5px;background:rgba(0,0,0,.45);border:1.5px solid rgba(255,255,255,.15);border-radius:20px;padding:6px 12px;cursor:pointer;font-size:12px;font-weight:500;color:rgba(255,255,255,.7);transition:all .15s;backdrop-filter:blur(8px);}
.who-chip.on{border-color:var(--accent);background:rgba(229,90,40,.25);color:#fff;}
.do-send-btn{width:52px;height:52px;border-radius:50%;background:var(--accent);border:none;color:#fff;font-size:22px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0;box-shadow:0 4px 18px rgba(229,90,40,.5);transition:all .2s;}
.do-send-btn:hover{background:var(--accent2);transform:scale(1.08);}
.do-send-btn:disabled{opacity:.35;cursor:not-allowed;transform:none;}

/* Hint to swipe */
.swipe-hint{position:absolute;bottom:100px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:4px;pointer-events:none;opacity:0;transition:opacity .5s;}
.swipe-hint.show{opacity:1;}
.hint-text{font-size:11px;color:rgba(255,255,255,.55);letter-spacing:1px;text-transform:uppercase;}
.hint-arrow{font-size:18px;color:rgba(255,255,255,.4);animation:bounce 1.5s infinite;}
@keyframes bounce{0%,100%{transform:translateY(0);}50%{transform:translateY(6px);}}

/* Shutter controls */
.cam-controls{position:absolute;bottom:50px;left:0;right:0;display:flex;align-items:center;justify-content:center;gap:28px;}
.shutter{width:74px;height:74px;border-radius:50%;background:#fff;border:4px solid rgba(255,255,255,.3);cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all .18s;box-shadow:0 4px 20px rgba(0,0,0,.5);}
.shutter:hover{transform:scale(1.05);}
.shutter:active{transform:scale(.92);}
.shutter-inner{width:56px;height:56px;border-radius:50%;background:#fff;}
.cam-side-btn{width:48px;height:48px;border-radius:50%;background:rgba(0,0,0,.4);border:1px solid rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;font-size:20px;cursor:pointer;color:#fff;backdrop-filter:blur(8px);transition:all .2s;}
.cam-side-btn:hover{background:rgba(255,255,255,.15);}

/* ── PAGE: FRIEND MOMENT ── */
#page-friend{height:100%;flex-shrink:0;position:relative;display:flex;flex-direction:column;align-items:center;justify-content:center;background:#000;}
.friend-photo-wrap{position:absolute;inset:0;overflow:hidden;}
#friend-photo-img{width:100%;height:100%;object-fit:cover;display:none;}
#friend-photo-bg{width:100%;height:100%;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:14px;}
.friend-photo-gradient{position:absolute;inset:0;background:linear-gradient(to bottom,rgba(0,0,0,.35) 0%,transparent 35%,transparent 55%,rgba(0,0,0,.8) 100%);pointer-events:none;}

/* Friend top info */
.friend-top{position:absolute;top:0;left:0;right:0;padding:64px 18px 16px;display:flex;align-items:center;gap:12px;}
#fr-av{width:38px;height:38px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:15px;font-weight:700;border:2px solid rgba(255,255,255,.3);flex-shrink:0;}
.friend-meta{flex:1;}
#fr-name{font-size:15px;font-weight:600;color:#fff;text-shadow:0 1px 6px rgba(0,0,0,.5);}
#fr-time{font-size:11px;color:rgba(255,255,255,.6);margin-top:1px;}
.swipe-up-hint{display:flex;flex-direction:column;align-items:center;gap:3px;}
.swipe-up-hint span{font-size:10px;color:rgba(255,255,255,.45);letter-spacing:1px;text-transform:uppercase;}
.swipe-up-icon{font-size:16px;color:rgba(255,255,255,.35);animation:bounceUp .8s ease-in-out infinite;}
@keyframes bounceUp{0%,100%{transform:translateY(0);}50%{transform:translateY(-5px);}}

/* Friend bottom */
.friend-bottom{position:absolute;bottom:0;left:0;right:0;padding:20px 16px 44px;}
#fr-caption{font-size:15px;color:#fff;text-shadow:0 1px 8px rgba(0,0,0,.7);margin-bottom:14px;line-height:1.45;}

/* Emoji reactions */
.react-row{display:flex;gap:8px;margin-bottom:14px;flex-wrap:wrap;}
.react-btn{background:rgba(0,0,0,.45);border:1px solid rgba(255,255,255,.15);border-radius:24px;padding:7px 13px;font-size:17px;cursor:pointer;transition:all .15s;backdrop-filter:blur(10px);display:flex;align-items:center;gap:4px;}
.react-btn:hover{transform:scale(1.15);}
.react-btn.on{background:rgba(229,90,40,.3);border-color:rgba(229,90,40,.5);}
.react-count{font-size:12px;color:rgba(255,255,255,.8);font-weight:600;}

/* Reply bar */
.reply-bar{display:flex;align-items:center;gap:10px;}
.reply-inp{flex:1;background:rgba(0,0,0,.45);border:1.5px solid rgba(255,255,255,.18);border-radius:30px;padding:11px 18px;color:#fff;font-family:'DM Sans',sans-serif;font-size:14px;outline:none;backdrop-filter:blur(12px);transition:border-color .2s;}
.reply-inp::placeholder{color:rgba(255,255,255,.4);}
.reply-inp:focus{border-color:rgba(229,90,40,.5);}
.reply-send{width:44px;height:44px;border-radius:50%;background:var(--accent);border:none;color:#fff;font-size:18px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:all .15s;box-shadow:0 3px 12px rgba(229,90,40,.4);}
.reply-send:hover{background:var(--accent2);}

/* No moments from friend */
.no-friend-moment{display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:14px;text-align:center;padding:40px;}
.no-friend-icon{font-size:64px;opacity:.25;}
.no-friend-title{font-family:'Fraunces',serif;font-size:20px;color:var(--cream2);}
.no-friend-sub{font-size:13px;color:var(--cream3);line-height:1.6;}

/* ── SENT OVERLAY ── */
#sent-ov{position:fixed;inset:0;z-index:400;background:rgba(8,6,4,.96);display:flex;flex-direction:column;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .3s;}
#sent-ov.show{opacity:1;pointer-events:all;}
.sent-circle{width:100px;height:100px;border-radius:50%;background:var(--accent);display:flex;align-items:center;justify-content:center;font-size:44px;margin-bottom:20px;animation:pop .5s cubic-bezier(.16,1,.3,1) both;}
@keyframes pop{from{transform:scale(0) rotate(-15deg);}to{transform:scale(1) rotate(0);}}
.sent-title{font-family:'Fraunces',serif;font-size:28px;font-weight:700;color:var(--cream);}
.sent-sub{font-size:14px;color:var(--cream2);margin-top:6px;}

/* ── TOAST ── */
#toast{position:fixed;bottom:90px;left:50%;transform:translateX(-50%) translateY(12px);background:rgba(20,16,12,.95);color:var(--cream);padding:10px 20px;border-radius:30px;font-size:13px;font-weight:500;opacity:0;transition:all .3s cubic-bezier(.16,1,.3,1);pointer-events:none;white-space:nowrap;z-index:9999;border:1px solid rgba(255,255,255,.1);backdrop-filter:blur(16px);}
#toast.show{opacity:1;transform:translateX(-50%) translateY(0);}

/* FILE INPUT */
#fileInput{display:none;}
</style>
</head>
<body>

<!-- ONBOARDING (multi-step) -->
<div id="ob">
  <div class="ob-steps" id="ob-steps">

    <!-- STEP 1: splash + auth options -->
    <div class="ob-step" style="position:relative;">
      <div class="ob-splash-logo">vi<b>by</b></div>
      <div class="ob-splash-tagline">живые моменты тем, кто важен</div>
      <div class="ob-auth-btns">
        <button class="ob-auth-btn apple" onclick="obGoStep(2,'apple')">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.3.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>
          Continue with Apple
        </button>
        <button class="ob-auth-btn phone" onclick="obGoStep(2,'phone')">
          📱 &nbsp;Continue with Phone
        </button>
        <button class="ob-auth-btn email" onclick="obGoStep(2,'email')">
          ✉️ &nbsp;Continue with Email
        </button>
        <div class="ob-terms">
          By continuing you agree to our <a>Terms</a> and <a>Privacy Policy</a>
        </div>
      </div>
    </div>

    <!-- STEP 2: phone or email input -->
    <div class="ob-step" style="position:relative;justify-content:center;">
      <button class="ob-back" onclick="obGoStep(1)">←</button>
      <div class="ob-step-title" id="ob-step2-title">Your phone number</div>
      <div class="ob-step-sub" id="ob-step2-sub">We'll send you a code to verify your account</div>
      <div class="ob-inp-row">
        <span class="ob-inp-prefix" id="ob-inp-prefix" style="display:none">+</span>
        <input class="ob-inp-big" id="ob-contact-inp" placeholder="+7 000 000 00 00" type="tel"
          oninput="obCheckContact()" style="width:100%">
      </div>
      <button class="ob-continue" id="ob-continue-1" onclick="obGoStep(2.5)">Continue →</button>
    </div>

    <!-- STEP 3: name + username -->
    <div class="ob-step" style="position:relative;justify-content:center;">
      <button class="ob-back" onclick="obGoStep(2)">←</button>
      <div class="ob-name-av" id="ob-name-av">?</div>
      <div class="ob-step-title">Create your profile</div>
      <div class="ob-step-sub">Choose a name and a unique username</div>
      <input class="ob-inp-big" id="ob-name-inp" placeholder="Your name" maxlength="20" autocomplete="off"
        oninput="obUpdateAvatar();obCheckProfile()">
      <div class="ob-inp-row">
        <span class="ob-inp-prefix">@</span>
        <input class="ob-inp-big with-prefix" id="ob-user-inp" placeholder="username" maxlength="20" autocomplete="off"
          oninput="obCheckProfile()" style="width:100%;text-transform:lowercase;">
      </div>
      <button class="ob-continue" id="ob-continue-2" onclick="enterApp()">Get started →</button>
    </div>

  </div>
</div>

<!-- MAIN APP -->
<div id="app">
  <!-- Header -->
  <div class="hdr">
    <div class="hdr-logo">vi<b>by</b></div>
    <div class="hdr-right">
      <div class="friends-pill" id="friends-pill" onclick="openFriendsPanel()">
        <div class="fp-avs" id="fp-avs"></div>
        <span>Friends</span>
        <div class="fp-new-dot" id="fp-new-dot" style="display:none"></div>
      </div>
      <div class="me-av" id="me-av">Я</div>
    </div>
  </div>

  <!-- Swipeable pages container -->
  <div id="pages">

    <!-- PAGE 0: MY CAMERA -->
    <div id="page-cam">
      <!-- Viewfinder -->
      <div id="cam-viewfinder">
        <video id="cam-video" autoplay playsinline muted></video>
        <canvas id="cam-canvas"></canvas>
        <div class="cam-no-cam" id="cam-no-cam" style="display:none">
          <div class="big-icon">📷</div>
          <p>Нажми кнопку чтобы<br>выбрать фото</p>
        </div>
      </div>

      <!-- My captured photo -->
      <div id="my-photo-frame">
        <img id="my-photo-img" alt="">
        <div class="my-photo-overlay">
          <input class="my-caption-inp" id="cap-inp" placeholder="Добавь подпись…" maxlength="80">
          <div class="send-row">
            <div class="who-chips" id="who-chips"></div>
            <button class="do-send-btn" id="do-send" onclick="doSend()" disabled>↑</button>
          </div>
        </div>
      </div>

      <!-- Shutter (only when no photo) -->
      <div class="cam-controls" id="cam-controls">
        <div class="cam-side-btn" onclick="retake()">↺</div>
        <div class="shutter" onclick="shoot()">
          <div class="shutter-inner"></div>
        </div>
        <div class="cam-side-btn" onclick="document.getElementById('fileInput').click()">🖼</div>
      </div>

      <!-- Swipe hint -->
      <div class="swipe-hint" id="swipe-hint">
        <div class="hint-text">Свайп вниз</div>
        <div class="hint-arrow">↓</div>
      </div>
    </div>

    <!-- PAGE 1: FRIEND'S MOMENT -->
    <div id="page-friend">
      <div class="friend-photo-wrap">
        <div id="friend-photo-bg">
          <div class="no-friend-moment" id="no-friend-state">
            <div class="no-friend-icon">🌙</div>
            <div class="no-friend-title">Пока тихо</div>
            <div class="no-friend-sub">Как только друг пришлёт<br>момент — он появится здесь</div>
          </div>
        </div>
        <img id="friend-photo-img" alt="">
        <div class="friend-photo-gradient"></div>
      </div>

      <!-- Top info -->
      <div class="friend-top">
        <div id="fr-av"></div>
        <div class="friend-meta">
          <div id="fr-name"></div>
          <div id="fr-time"></div>
        </div>
        <div class="swipe-up-hint">
          <div class="swipe-up-icon">↑</div>
          <span>Камера</span>
        </div>
      </div>

      <!-- Bottom -->
      <div class="friend-bottom">
        <div id="fr-caption"></div>
        <div class="react-row" id="react-row"></div>
        <div class="reply-bar">
          <input class="reply-inp" id="reply-inp" placeholder="Ответить…" onkeydown="if(event.key==='Enter')sendReply()">
          <button class="reply-send" onclick="sendReply()">↑</button>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- FRIENDS PANEL -->
<div id="friends-panel">
  <div class="fp-backdrop" onclick="closeFriendsPanel()"></div>
  <div class="fp-sheet">
    <div class="fp-handle"></div>
    <div class="fp-head">
      <div class="fp-title">Friends</div>
      <button class="fp-close" onclick="closeFriendsPanel()">✕</button>
    </div>
    <div class="fp-list" id="fp-list"></div>
  </div>
</div>

<!-- SENT OVERLAY -->
<div id="sent-ov">
  <div class="sent-circle">✓</div>
  <div class="sent-title">Отправлено!</div>
  <div class="sent-sub" id="sent-sub">Момент улетел!</div>
</div>

<input type="file" id="fileInput" accept="image/*" onchange="onFile(event)">

<div id="toast"></div>

<script>
/* ═══════════ DATA ═══════════ */
const PAL=[
  {bg:'#c84b1a',fg:'#fff'},{bg:'#3d7a52',fg:'#fff'},
  {bg:'#2e6090',fg:'#fff'},{bg:'#7a3d6b',fg:'#fff'},
  {bg:'#6b4e2a',fg:'#fff'},{bg:'#2d6b6b',fg:'#fff'},
  {bg:'#7a6b20',fg:'#fff'},{bg:'#4a3d7a',fg:'#fff'},
];
const EMOJIS=['❤️','🔥','😂','😍','😮','🥹'];
const BG_GRADS=[
  'linear-gradient(135deg,#f093fb,#f5576c)',
  'linear-gradient(135deg,#4facfe,#00f2fe)',
  'linear-gradient(135deg,#43e97b,#38f9d7)',
  'linear-gradient(135deg,#fa709a,#fee140)',
  'linear-gradient(135deg,#a18cd1,#fbc2eb)',
];

let myName='Я', myInit='Я';
let friends=[];
let selectedSendTo=new Set();
let capturedSrc=null;
let currentFriendIdx=0;
let friendMoments={}; // fi -> {src,bg,caption,time,reactions:{e->count,mine}}
let usingCamera=false;
let stream=null;

/* ═══════════ ONBOARDING (multi-step) ═══════════ */
let obAuthMethod='phone';
let obStep=1;

function obGoStep(step, method){
  if(method) obAuthMethod=method;
  if(step===2){
    if(obAuthMethod==='apple'){
      // Simulate Apple sign-in → skip to profile
      obGoStep(3);return;
    }
    const isEmail=obAuthMethod==='email';
    document.getElementById('ob-step2-title').textContent=isEmail?'Your email address':'Your phone number';
    document.getElementById('ob-step2-sub').textContent=isEmail?'We\'ll send you a link to sign in':'We\'ll send you a code to verify';
    const inp=document.getElementById('ob-contact-inp');
    inp.type=isEmail?'email':'tel';
    inp.placeholder=isEmail?'hello@example.com':'+7 000 000 00 00';
    inp.value='';
    document.getElementById('ob-continue-1').classList.remove('ready');
  }
  if(step===2.5){
    // Simulate OTP/code sent → go straight to profile step
    obGoStep(3);return;
  }
  const realStep=step===3?3:step;
  obStep=realStep;
  const idx=realStep-1;
  document.getElementById('ob-steps').style.transform=`translateX(-${idx*33.333}%)`;
}

function obCheckContact(){
  const v=document.getElementById('ob-contact-inp').value.trim();
  const ok=v.length>5;
  document.getElementById('ob-continue-1').classList.toggle('ready',ok);
}

function obUpdateAvatar(){
  const n=document.getElementById('ob-name-inp').value.trim();
  document.getElementById('ob-name-av').textContent=n[0]?.toUpperCase()||'?';
}

function obCheckProfile(){
  const name=document.getElementById('ob-name-inp').value.trim();
  const user=document.getElementById('ob-user-inp').value.trim();
  document.getElementById('ob-continue-2').classList.toggle('ready',name.length>0&&user.length>2);
}

function enterApp(){
  const nm=document.getElementById('ob-name-inp').value.trim()||'Viby User';
  myName=nm; myInit=nm[0].toUpperCase();
  document.getElementById('me-av').textContent=myInit;

  // Demo friends (no friends added during onboarding — they find friends later)
  friends=[
    {name:'Маша',  init:'М',color:0,online:true},
    {name:'Дима',  init:'Д',color:1,online:false},
    {name:'Катя',  init:'К',color:2,online:true},
  ];

  // Seed 1 friend moment
  if(friends.length>0){
    friendMoments[0]={src:null,bg:Math.floor(Math.random()*BG_GRADS.length),caption:'Посмотри какой закат 🌅',time:'3 мин назад',reactions:{}};
  }

  renderFriendsPill();
  renderWhoChips();
  loadFriendMoment(0);
  startCamera();

  document.getElementById('ob').classList.add('gone');
  setTimeout(()=>{document.getElementById('ob').style.display='none';},450);
  document.getElementById('app').classList.add('show');

  // Show swipe hint after 1.5s
  setTimeout(()=>{document.getElementById('swipe-hint').classList.add('show');},1500);
  setTimeout(()=>{document.getElementById('swipe-hint').classList.remove('show');},4500);
}

/* ═══════════ FRIENDS PILL + PANEL ═══════════ */
function renderFriendsPill(){
  const avs=document.getElementById('fp-avs');
  const dot=document.getElementById('fp-new-dot');
  avs.innerHTML=friends.slice(0,3).map((f,i)=>{
    const col=PAL[f.color%PAL.length];
    return `<div class="fp-sm-av" style="background:${col.bg};color:${col.fg}">${f.init}</div>`;
  }).join('');
  const hasNew=friends.some((_,i)=>!!friendMoments[i]);
  dot.style.display=hasNew?'block':'none';
}

function renderFriendsPanel(){
  const list=document.getElementById('fp-list');
  list.innerHTML=friends.map((f,i)=>{
    const col=PAL[f.color%PAL.length];
    const m=friendMoments[i];
    const hasNew=!!m;
    return `<div class="fp-item" onclick="fpOpenFriend(${i})">
      <div class="fp-item-av" style="background:${col.bg};color:${col.fg}">
        ${hasNew?'<div class="fp-ring"></div>':''}
        ${f.init}
        ${f.online&&!hasNew?'<div class="fp-online"></div>':''}
      </div>
      <div class="fp-item-info">
        <div class="fp-item-name">${f.name}</div>
        <div class="fp-item-sub">${hasNew?'Новый момент':''+f.online?'онлайн':'был(а) недавно'}</div>
      </div>
      ${hasNew?'<div class="fp-badge">New ✦</div>':''}
    </div>`;
  })+`
  <div style="height:1px;background:rgba(255,255,255,.07);margin:10px 10px 8px;"></div>
  <div class="fp-add" onclick="showInviteOptions()">
    <div class="fp-add-av">🔗</div>
    <div>
      <div class="fp-add-label">Invite via link</div>
      <div style="font-size:12px;color:var(--cream3);margin-top:2px;">Share your Viby link with friends</div>
    </div>
  </div>
  <div class="fp-add" onclick="showFindUser()">
    <div class="fp-add-av">🔍</div>
    <div>
      <div class="fp-add-label">Find by username</div>
      <div style="font-size:12px;color:var(--cream3);margin-top:2px;">Search @username to add someone</div>
    </div>
  </div>
`;
}

function openFriendsPanel(){
  renderFriendsPanel();
  document.getElementById('friends-panel').classList.add('open');
}
function closeFriendsPanel(){
  document.getElementById('friends-panel').classList.remove('open');
}
function fpOpenFriend(i){
  closeFriendsPanel();
  goToFriend(i);
}

/* ═══════════ WHO CHIPS ═══════════ */
function renderWhoChips(){
  document.getElementById('who-chips').innerHTML=friends.map((f,i)=>`
    <div class="who-chip ${selectedSendTo.has(i)?'on':''}" onclick="toggleWho(${i})">${f.name}</div>
  `).join('');
}
function toggleWho(i){
  if(selectedSendTo.has(i))selectedSendTo.delete(i);
  else selectedSendTo.add(i);
  renderWhoChips();
  checkSendReady();
}
function checkSendReady(){
  document.getElementById('do-send').disabled=!(capturedSrc&&selectedSendTo.size>0);
}

/* ═══════════ CAMERA ═══════════ */
async function startCamera(){
  const video=document.getElementById('cam-video');
  const noCam=document.getElementById('cam-no-cam');
  try{
    stream=await navigator.mediaDevices.getUserMedia({video:{facingMode:'user'},audio:false});
    video.srcObject=stream;
    video.style.display='block';
    noCam.style.display='none';
    usingCamera=true;
  }catch(e){
    video.style.display='none';
    noCam.style.display='flex';
    usingCamera=false;
  }
}

function shoot(){
  if(!usingCamera){document.getElementById('fileInput').click();return;}
  const video=document.getElementById('cam-video');
  const canvas=document.getElementById('cam-canvas');
  canvas.width=video.videoWidth||400;
  canvas.height=video.videoHeight||400;
  const ctx=canvas.getContext('2d');
  // Mirror for selfie
  ctx.save();
  ctx.translate(canvas.width,0);
  ctx.scale(-1,1);
  ctx.drawImage(video,0,0);
  ctx.restore();
  const src=canvas.toDataURL('image/jpeg',.92);
  showCapture(src);
}

function onFile(e){
  const file=e.target.files[0];if(!file)return;
  const r=new FileReader();
  r.onload=ev=>showCapture(ev.target.result);
  r.readAsDataURL(file);
  e.target.value='';
}

function showCapture(src){
  capturedSrc=src;
  document.getElementById('my-photo-img').src=src;
  document.getElementById('my-photo-frame').style.display='flex';
  document.getElementById('cam-controls').style.display='none';
  document.getElementById('swipe-hint').classList.remove('show');
  if(stream) stream.getTracks().forEach(t=>t.enabled=false);
  renderWhoChips();
  checkSendReady();
}

function retake(){
  capturedSrc=null;
  selectedSendTo.clear();
  document.getElementById('my-photo-frame').style.display='none';
  document.getElementById('cam-controls').style.display='flex';
  document.getElementById('cap-inp').value='';
  if(stream) stream.getTracks().forEach(t=>t.enabled=true);
  checkSendReady();
  setTimeout(()=>document.getElementById('swipe-hint').classList.add('show'),800);
  setTimeout(()=>document.getElementById('swipe-hint').classList.remove('show'),3800);
}

/* ═══════════ SEND ═══════════ */
function doSend(){
  if(!capturedSrc||!selectedSendTo.size)return;
  const cap=document.getElementById('cap-inp').value.trim()||null;
  const toIdx=[...selectedSendTo][0];

  const ov=document.getElementById('sent-ov');
  document.getElementById('sent-sub').textContent=`Момент улетел к ${friends[toIdx]?.name||'другу'} 💌`;
  ov.classList.add('show');

  setTimeout(()=>{
    ov.classList.remove('show');
    retake();
  },2000);
}

/* ═══════════ FRIEND MOMENT ═══════════ */
function loadFriendMoment(fi){
  currentFriendIdx=fi;
  const f=friends[fi];
  const m=friendMoments[fi];
  const col=PAL[f.color%PAL.length];

  document.getElementById('fr-av').style.background=col.bg;
  document.getElementById('fr-av').style.color=col.fg;
  document.getElementById('fr-av').textContent=f.init;
  document.getElementById('fr-name').textContent=f.name;
  document.getElementById('reply-inp').placeholder=`Ответить ${f.name}…`;

  const img=document.getElementById('friend-photo-img');
  const bg=document.getElementById('friend-photo-bg');
  const noState=document.getElementById('no-friend-state');
  const capEl=document.getElementById('fr-caption');

  if(!m){
    img.style.display='none';
    noState.style.display='flex';
    bg.style.background='';
    document.getElementById('fr-time').textContent='';
    capEl.textContent='';
    capEl.style.display='none';
    document.getElementById('react-row').innerHTML='';
    return;
  }

  noState.style.display='none';
  document.getElementById('fr-time').textContent=m.time;
  capEl.textContent=m.caption||'';
  capEl.style.display=m.caption?'block':'none';

  if(m.src){
    img.src=m.src;img.style.display='block';
    bg.style.background='';
  } else {
    img.style.display='none';
    bg.style.background=BG_GRADS[m.bg%BG_GRADS.length];
  }

  renderReacts(fi);
}

function renderReacts(fi){
  const m=friendMoments[fi];
  if(!m){document.getElementById('react-row').innerHTML='';return;}
  document.getElementById('react-row').innerHTML=EMOJIS.map(e=>{
    const r=m.reactions[e];
    return `<div class="react-btn ${r&&r.mine?'on':''}" onclick="react('${e}')">
      ${e}${r&&r.c>0?`<span class="react-count">${r.c}</span>`:''}
    </div>`;
  }).join('');
}

function react(e){
  const fi=currentFriendIdx;
  const m=friendMoments[fi];if(!m)return;
  if(!m.reactions[e])m.reactions[e]={c:0,mine:false};
  const r=m.reactions[e];
  r.mine=!r.mine;
  r.c+=r.mine?1:-1;
  if(r.c<=0)delete m.reactions[e];
  renderReacts(fi);
  toast(r.mine?'Реакция отправлена ✓':'Реакция убрана');
}

function sendReply(){
  const inp=document.getElementById('reply-inp');
  if(!inp.value.trim())return;
  toast('Ответ отправлен 💬');
  inp.value='';
}

function goToFriend(i){
  loadFriendMoment(i);
  scrollToPage(1);
}

/* ═══════════ SWIPE / SCROLL ═══════════ */
let curPage=0;
let startY=0,dragging=false,dragDelta=0;
const pages=document.getElementById('pages');

function scrollToPage(n,animated=true){
  curPage=n;
  pages.style.transition=animated?'transform .35s cubic-bezier(.4,0,.2,1)':'none';
  pages.style.transform=`translateY(${n===0?0:-100}%)`;
}

pages.addEventListener('touchstart',e=>{
  startY=e.touches[0].clientY;
  dragging=true;
  dragDelta=0;
  pages.style.transition='none';
},{passive:true});

pages.addEventListener('touchmove',e=>{
  if(!dragging)return;
  const dy=e.touches[0].clientY-startY;
  dragDelta=dy;
  const baseOffset=curPage===0?0:-window.innerHeight;
  pages.style.transform=`translateY(calc(${curPage===0?0:-100}% + ${dy}px))`;
},{passive:true});

pages.addEventListener('touchend',()=>{
  dragging=false;
  const threshold=60;
  if(curPage===0&&dragDelta<-threshold){scrollToPage(1);}
  else if(curPage===1&&dragDelta>threshold){scrollToPage(0);}
  else{scrollToPage(curPage);}
});

// Mouse drag for desktop
pages.addEventListener('mousedown',e=>{startY=e.clientY;dragging=true;dragDelta=0;pages.style.transition='none';});
document.addEventListener('mousemove',e=>{if(!dragging)return;dragDelta=e.clientY-startY;pages.style.transform=`translateY(calc(${curPage===0?0:-100}% + ${dragDelta}px))`;});
document.addEventListener('mouseup',()=>{
  if(!dragging)return;dragging=false;
  const threshold=60;
  if(curPage===0&&dragDelta<-threshold)scrollToPage(1);
  else if(curPage===1&&dragDelta>threshold)scrollToPage(0);
  else scrollToPage(curPage);
});

function showInviteOptions(){
  closeFriendsPanel();
  toast('Link copied! viby.app/join/'+myName.toLowerCase().replace(/\s/g,'_')+' 🔗');
}
function showFindUser(){
  closeFriendsPanel();
  const name=prompt('Find friend by @username:');
  if(name&&name.trim()){
    const clean=name.replace('@','').trim();
    const idx=friends.length;
    friends.push({name:clean,init:clean[0].toUpperCase(),color:idx%PAL.length,online:false});
    renderFriendsPill();
    toast(`@${clean} added! 🎉`);
  }
}

/* ═══════════ TOAST ═══════════ */
let toastT;
function toast(msg){
  const el=document.getElementById('toast');
  el.textContent=msg;el.classList.add('show');
  clearTimeout(toastT);toastT=setTimeout(()=>el.classList.remove('show'),2200);
}

/* ═══════════ KEYBOARD ═══════════ */
document.addEventListener('keydown',e=>{
  if(e.key==='ArrowDown')scrollToPage(1);
  if(e.key==='ArrowUp')scrollToPage(0);
});
</script>
</body>
</html>

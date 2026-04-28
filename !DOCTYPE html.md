<!DOCTYPE html>  
  
<html lang="ar" dir="rtl">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>GOLD LIFE | كورسات التداول الاحترافية</title>  
<style>  
@import url('https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;900&family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&display=swap');  
</style>  
<style>  
:root {  
  --gold:#b8941f;  
  --gold2:#c9a535;  
  --gold3:#8b6d12;  
  --gold4:#e2c96a;  
  --gold5:#f5e9c0;  
  --cream:#fefcf7;  
  --cream2:#faf6ed;  
  --cream3:#f5ede0;  
  --cream4:#ede0cc;  
  --white:#ffffff;  
  --card:#ffffff;  
  --card2:#fdfaf3;  
  --border:rgba(184,148,31,.13);  
  --border2:rgba(184,148,31,.28);  
  --border3:rgba(184,148,31,.5);  
  --text:#1e1608;  
  --text2:#3a2e10;  
  --muted:#8a7550;  
  --muted2:#6b5830;  
  --green:#1a7a5a;  
  --green2:rgba(26,122,90,.09);  
  --r:16px;  
  --shadow:0 2px 20px rgba(139,105,20,.07);  
  --shadow2:0 12px 40px rgba(139,105,20,.13);  
  --shadow3:0 24px 60px rgba(139,105,20,.16);  
}  
*{margin:0;padding:0;box-sizing:border-box;}  
html{scroll-behavior:smooth;}  
body{font-family:'Cairo','Segoe UI',Tahoma,Arial,sans-serif;background:var(--cream);color:var(--text);overflow-x:hidden;direction:rtl;}  
  
/* ─── NAV ─── */  
nav{  
position:fixed;top:0;inset-inline:0;z-index:900;  
display:flex;align-items:center;justify-content:space-between;  
padding:.85rem 6%;  
background:rgba(254,252,247,.96);  
backdrop-filter:blur(24px);  
border-bottom:1px solid var(–border);  
}  
.logo{display:flex;align-items:center;gap:.7rem;text-decoration:none;}  
.logo-mark{  
width:40px;height:40px;border-radius:50%;  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
display:flex;align-items:center;justify-content:center;  
font-size:.6rem;font-weight:900;color:#fff;letter-spacing:.5px;  
box-shadow:0 2px 14px rgba(184,148,31,.22);  
}  
.logo-text{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.2rem;letter-spacing:2px;font-weight:700;color:var(–gold3);}  
.logo-text span{color:var(–gold2);}  
.nav-links{display:flex;gap:2rem;list-style:none;}  
.nav-links a{color:var(–muted);text-decoration:none;font-size:.84rem;font-weight:600;transition:color .3s;}  
.nav-links a:hover{color:var(–gold2);}  
.nav-cta{  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
color:#fff;padding:.5rem 1.5rem;border-radius:8px;  
font-weight:800;text-decoration:none;font-size:.84rem;  
transition:all .3s;box-shadow:0 4px 14px rgba(139,105,20,.22);  
}  
.nav-cta:hover{filter:brightness(1.08);transform:translateY(-1px);}  
  
/* ─── HERO ─── */  
.hero{  
min-height:100vh;display:flex;align-items:center;justify-content:center;  
position:relative;padding:9rem 6% 6rem;text-align:center;overflow:hidden;  
background:linear-gradient(170deg,var(–white) 0%,var(–cream) 40%,var(–cream2) 100%);  
}  
.hero-grid{  
position:absolute;inset:0;pointer-events:none;  
background-image:  
linear-gradient(rgba(184,148,31,.035) 1px,transparent 1px),  
linear-gradient(90deg,rgba(184,148,31,.035) 1px,transparent 1px);  
background-size:60px 60px;  
mask-image:radial-gradient(ellipse 65% 55% at 50% 35%,black 30%,transparent 70%);  
}  
.hero-glow{  
position:absolute;width:700px;height:700px;border-radius:50%;  
background:radial-gradient(circle,rgba(212,168,50,.06) 0%,transparent 60%);  
top:50%;left:50%;transform:translate(-50%,-52%);pointer-events:none;  
}  
.ring{position:absolute;border-radius:50%;top:50%;left:50%;transform:translate(-50%,-50%);}  
.r1{width:380px;height:380px;border:1px solid rgba(184,148,31,.07);animation:sp 55s linear infinite;}  
.r2{width:620px;height:620px;border:1px dashed rgba(184,148,31,.04);animation:sp 85s linear infinite reverse;}  
.r3{width:880px;height:880px;border:1px solid rgba(184,148,31,.025);animation:sp 120s linear infinite;}  
@keyframes sp{to{transform:translate(-50%,-50%) rotate(360deg);}}  
  
.hero-content{position:relative;z-index:2;max-width:800px;}  
.badge{  
display:inline-flex;align-items:center;gap:.55rem;  
background:rgba(184,148,31,.06);border:1px solid var(–border2);  
color:var(–gold3);padding:.38rem 1.2rem;border-radius:30px;  
font-size:.8rem;letter-spacing:0;  
margin-bottom:2rem;font-weight:700;  
animation:fadeUp .9s ease both;  
}  
.badge::before,.badge::after{content:‘◆’;font-size:.4rem;color:var(–gold2);}  
.hero h1{  
font-family:‘Cormorant Garamond’,Georgia,serif;  
font-size:clamp(3rem,8.5vw,6rem);font-weight:700;  
line-height:1.0;margin-bottom:.4rem;  
animation:fadeUp .9s ease .12s both;  
color:var(–gold3);  
}  
.hero h1 .accent{  
background:linear-gradient(135deg,var(–gold3),var(–gold2),var(–gold4));  
-webkit-background-clip:text;-webkit-text-fill-color:transparent;  
}  
.hero h1 .sub{  
color:var(–muted);font-size:28%;letter-spacing:2px;display:block;  
margin-top:.5rem;font-family:‘Cairo’,sans-serif;font-weight:700;  
}  
.hero-desc{  
color:var(–muted);font-size:.96rem;line-height:2.1;max-width:540px;  
margin:1.5rem auto 2.5rem;animation:fadeUp .9s ease .24s both;  
}  
.hero-desc strong{color:var(–gold3);font-weight:800;}  
.btns{display:flex;gap:.9rem;justify-content:center;flex-wrap:wrap;animation:fadeUp .9s ease .36s both;}  
.btn-primary{  
background:linear-gradient(135deg,var(–gold3),var(–gold2));color:#fff;  
padding:.95rem 2.8rem;border-radius:8px;font-weight:800;text-decoration:none;font-size:.94rem;  
transition:all .3s;box-shadow:0 8px 24px rgba(139,105,20,.22);  
}  
.btn-primary:hover{filter:brightness(1.07);transform:translateY(-2px);box-shadow:0 16px 36px rgba(139,105,20,.28);}  
.btn-ghost{  
background:transparent;color:var(–gold3);  
padding:.95rem 2.8rem;border-radius:8px;  
font-weight:700;text-decoration:none;font-size:.94rem;  
border:1.5px solid var(–border2);transition:all .3s;  
}  
.btn-ghost:hover{background:rgba(184,148,31,.06);transform:translateY(-2px);}  
.stats-row{  
display:flex;gap:.8rem;justify-content:center;flex-wrap:wrap;  
margin-top:2.8rem;animation:fadeUp .9s ease .5s both;  
}  
.stat{  
background:var(–white);border:1px solid var(–border);  
padding:.45rem 1.1rem;border-radius:22px;font-size:.76rem;  
display:flex;align-items:center;gap:.45rem;color:var(–text2);  
box-shadow:var(–shadow);font-weight:600;  
}  
.dot{width:6px;height:6px;border-radius:50%;}  
.dot-btc{background:#f7931a;}.dot-eth{background:#627eea;}.dot-usdt{background:var(–green);}.dot-gold{background:var(–gold2);}  
@keyframes fadeUp{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}  
  
/* ─── TRUST ─── */  
.trust{  
position:relative;z-index:1;  
border-top:1px solid var(–border);border-bottom:1px solid var(–border);  
background:rgba(184,148,31,.025);  
display:grid;grid-template-columns:repeat(4,1fr);  
}  
.ti{  
padding:2rem 1rem;text-align:center;  
border-left:1px solid var(–border);  
}  
.ti:last-child{border-left:none;}  
.tn{  
font-family:‘Cormorant Garamond’,Georgia,serif;font-size:2.4rem;font-weight:700;  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
-webkit-background-clip:text;-webkit-text-fill-color:transparent;  
}  
.tl{font-size:.8rem;color:var(–muted);margin-top:.3rem;letter-spacing:0;font-weight:600;}  
  
/* ─── SECTIONS ─── */  
section{padding:6rem 6%;position:relative;z-index:1;}  
.wrap{max-width:1120px;margin:0 auto;}  
.sec-head{text-align:center;margin-bottom:3.5rem;}  
.sec-tag{font-size:.78rem;letter-spacing:0;color:var(–gold2);margin-bottom:.8rem;display:block;font-weight:700;}  
.sec-title{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:clamp(1.9rem,3.8vw,2.9rem);font-weight:700;margin-bottom:.6rem;color:var(–gold3);}  
.sec-sub{color:var(–muted);font-size:.91rem;line-height:1.95;max-width:540px;margin:0 auto;}  
.divider{display:flex;align-items:center;justify-content:center;gap:1rem;margin-bottom:1.4rem;opacity:.45;}  
.divider::before,.divider::after{content:’’;flex:1;height:1px;}  
.divider::before{background:linear-gradient(to right,transparent,var(–gold2));}  
.divider::after{background:linear-gradient(to left,transparent,var(–gold2));}  
.divider span{color:var(–gold2);font-size:.55rem;}  
  
/* ─── COURSES ─── */  
#courses{background:var(–cream2);}  
.courses-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.5rem;}  
.course-card{  
background:var(–white);border:1px solid var(–border);  
border-radius:var(–r);overflow:hidden;  
transition:all .35s;display:flex;flex-direction:column;  
box-shadow:var(–shadow);  
}  
.course-card:hover{border-color:var(–border2);transform:translateY(-6px);box-shadow:var(–shadow2);}  
.course-card.featured{border-color:rgba(184,148,31,.3);}  
.card-header{  
padding:2.2rem 2rem 1.5rem;position:relative;  
background:linear-gradient(170deg,rgba(184,148,31,.03),transparent);  
}  
.card-ribbon{  
position:absolute;top:1.4rem;left:1.4rem;  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
color:#fff;padding:.22rem .8rem;border-radius:20px;font-size:.72rem;font-weight:900;letter-spacing:0;  
}  
.card-ribbon.new{background:var(–green);}  
.pkg-name{  
font-family:‘Cormorant Garamond’,Georgia,serif;font-size:2.1rem;font-weight:700;  
background:linear-gradient(135deg,var(–gold3),var(–gold4));  
-webkit-background-clip:text;-webkit-text-fill-color:transparent;  
margin-bottom:.3rem;display:block;  
}  
.card-level{font-size:.72rem;letter-spacing:0;color:var(–muted);margin-bottom:.25rem;font-weight:700;}  
.card-title{font-size:.93rem;font-weight:800;line-height:1.5;margin-bottom:.55rem;color:var(–text2);}  
.card-desc{color:var(–muted);font-size:.81rem;line-height:1.75;}  
.card-body{padding:0 2rem 2rem;flex:1;display:flex;flex-direction:column;}  
.card-divider{height:1px;background:var(–border);margin:1.1rem 0;}  
.feats-title{font-size:.75rem;letter-spacing:0;color:var(–muted);margin-bottom:.85rem;font-weight:700;}  
.feats{list-style:none;display:flex;flex-direction:column;gap:.44rem;flex:1;}  
.feats li{font-size:.77rem;color:var(–text2);display:flex;align-items:flex-start;gap:.5rem;line-height:1.5;}  
.feats li::before{content:‘◆’;color:var(–gold2);font-size:.4rem;margin-top:.28rem;flex-shrink:0;}  
.feats.cols{display:grid;grid-template-columns:1fr 1fr;gap:.35rem .8rem;}  
.card-footer{  
border-top:1px solid var(–border);padding:1.4rem 2rem;  
display:flex;align-items:center;justify-content:space-between;gap:1rem;flex-wrap:wrap;  
background:rgba(184,148,31,.02);  
}  
.price-block .amount{  
font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.85rem;font-weight:700;  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
-webkit-background-clip:text;-webkit-text-fill-color:transparent;  
}  
.price-block .note{font-size:.69rem;color:var(–muted);margin-top:.08rem;}  
.buy-btn{  
background:linear-gradient(135deg,var(–gold3),var(–gold2));color:#fff;  
padding:.68rem 1.5rem;border-radius:7px;font-weight:900;text-decoration:none;font-size:.84rem;  
transition:all .25s;border:none;cursor:pointer;white-space:nowrap;  
box-shadow:0 4px 12px rgba(139,105,20,.2);  
}  
.buy-btn:hover{filter:brightness(1.1);transform:translateY(-1px);}  
.buy-btn.outline{background:transparent;color:var(–gold3);border:1.5px solid var(–border2);box-shadow:none;}  
.buy-btn.outline:hover{background:rgba(184,148,31,.06);}  
.duration{  
display:inline-flex;align-items:center;gap:.4rem;margin-top:.85rem;  
background:rgba(184,148,31,.06);border:1px solid var(–border);  
padding:.3rem .85rem;border-radius:20px;font-size:.71rem;color:var(–gold3);font-weight:700;  
}  
.duration.lifetime{background:var(–green2);border-color:rgba(26,122,90,.2);color:var(–green);}  
  
/* ─── COMMUNITY ─── */  
#community{background:var(–white);}  
.community-grid{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;}  
.comm-card{  
background:var(–white);border:1px solid var(–border);border-radius:var(–r);  
padding:2.2rem;transition:all .3s;display:flex;flex-direction:column;gap:.9rem;  
box-shadow:var(–shadow);  
}  
.comm-card:hover{border-color:var(–border2);transform:translateY(-4px);box-shadow:var(–shadow2);}  
.comm-card.vip{border-color:rgba(184,148,31,.28);background:linear-gradient(160deg,rgba(184,148,31,.03),var(–white));}  
.comm-icon{font-size:2rem;}  
.comm-badge{display:inline-block;padding:.22rem .75rem;border-radius:20px;font-size:.72rem;font-weight:800;letter-spacing:0;}  
.comm-badge.vip-b{background:linear-gradient(135deg,var(–gold3),var(–gold2));color:#fff;}  
.comm-badge.hub-b{background:var(–cream2);border:1px solid var(–border2);color:var(–gold3);}  
.comm-title{font-size:1.02rem;font-weight:800;margin-bottom:.25rem;color:var(–text);}  
.comm-desc{color:var(–muted);font-size:.83rem;line-height:1.8;flex:1;}  
.comm-perks{list-style:none;display:flex;flex-direction:column;gap:.48rem;margin:.4rem 0;}  
.comm-perks li{font-size:.79rem;color:var(–text2);display:flex;align-items:center;gap:.45rem;}  
.comm-perks li::before{content:‘◆’;color:var(–gold2);font-size:.4rem;}  
.comm-footer{  
display:flex;align-items:center;justify-content:space-between;  
border-top:1px solid var(–border);padding-top:1.1rem;margin-top:auto;  
}  
.comm-price .am{  
font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.65rem;font-weight:700;  
background:linear-gradient(135deg,var(–gold3),var(–gold2));  
-webkit-background-clip:text;-webkit-text-fill-color:transparent;  
}  
.comm-price .per{font-size:.71rem;color:var(–muted);}  
  
/* ─── WHY ─── */  
#why{background:var(–cream2);}  
.why-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.2rem;}  
.why-card{  
background:var(–white);border:1px solid var(–border);border-radius:var(–r);  
padding:2rem;transition:all .3s;box-shadow:var(–shadow);  
}  
.why-card:hover{border-color:var(–border2);transform:translateY(-4px);box-shadow:var(–shadow2);}  
.why-ico{font-size:1.9rem;margin-bottom:.9rem;}  
.why-card h3{font-size:.9rem;font-weight:800;margin-bottom:.45rem;color:var(–text);}  
.why-card p{color:var(–muted);font-size:.8rem;line-height:1.75;}  
  
/* ─── CONTACT ─── */  
#contact{background:var(–cream3);}  
.contact-grid{display:grid;grid-template-columns:1fr 1.4fr;gap:3.5rem;align-items:start;}  
.contact-info h2{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:2.1rem;font-weight:700;margin-bottom:.7rem;color:var(–gold3);}  
.contact-info p{color:var(–muted);line-height:1.9;margin-bottom:2rem;font-size:.87rem;}  
.soc-links{display:flex;flex-direction:column;gap:.85rem;}  
.soc-link{  
display:flex;align-items:center;gap:.85rem;background:var(–white);  
border:1px solid var(–border);padding:.9rem 1.2rem;border-radius:10px;  
text-decoration:none;color:var(–text);transition:all .3s;box-shadow:var(–shadow);  
}  
.soc-link:hover{border-color:var(–border2);color:var(–gold3);}  
.soc-link .ico{font-size:1.25rem;width:34px;text-align:center;}  
.soc-link .lbl{font-weight:800;font-size:.85rem;}  
.soc-link .val{color:var(–muted);font-size:.73rem;}  
  
/* ─── FOOTER ─── */  
footer{background:#141008;border-top:1px solid rgba(184,148,31,.18);padding:2.8rem 6%;text-align:center;position:relative;z-index:1;}  
.foot-logo{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.55rem;font-weight:700;background:linear-gradient(to left,var(–gold3),var(–gold4));-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:.55rem;letter-spacing:2px;}  
footer p{color:rgba(245,228,168,.35);font-size:.77rem;line-height:2.2;}  
footer span{color:var(–gold4);}  
  
/* ─── MODAL ─── */  
#payment-overlay{  
display:none;position:fixed;inset:0;z-index:1000;  
background:rgba(20,16,8,.72);backdrop-filter:blur(18px);  
align-items:center;justify-content:center;padding:1.5rem;  
}  
#payment-overlay.open{display:flex;}  
.pay-modal{  
background:var(–white);border:1px solid var(–border2);border-radius:20px;  
width:100%;max-width:530px;max-height:92vh;overflow-y:auto;padding:2.5rem;  
position:relative;box-shadow:0 32px 80px rgba(20,16,8,.3);  
}  
.pay-modal::-webkit-scrollbar{width:5px;}  
.pay-modal::-webkit-scrollbar-track{background:var(–cream);}  
.pay-modal::-webkit-scrollbar-thumb{background:var(–border2);border-radius:3px;}  
.pay-close{  
position:absolute;top:1.2rem;left:1.2rem;  
background:var(–cream2);border:1px solid var(–border);  
color:var(–muted);width:32px;height:32px;border-radius:50%;  
display:flex;align-items:center;justify-content:center;  
cursor:pointer;font-size:.82rem;transition:all .2s;  
}  
.pay-close:hover{background:var(–cream3);color:var(–gold3);}  
.pay-title{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.55rem;font-weight:700;margin-bottom:.35rem;color:var(–gold3);}  
.pay-sub{color:var(–muted);font-size:.83rem;margin-bottom:1.8rem;line-height:1.7;}  
  
.pay-steps{display:flex;gap:0;margin-bottom:2rem;position:relative;}  
.pay-steps::before{content:’’;position:absolute;top:13px;right:13px;left:13px;height:1px;background:var(–border);z-index:0;}  
.pstep{flex:1;display:flex;flex-direction:column;align-items:center;gap:.4rem;position:relative;z-index:1;}  
.pstep-n{  
width:26px;height:26px;border-radius:50%;background:var(–cream2);border:1px solid var(–border);  
display:flex;align-items:center;justify-content:center;font-size:.66rem;font-weight:800;color:var(–muted);  
}  
.pstep-n.active{background:linear-gradient(135deg,var(–gold3),var(–gold2));color:#fff;border:none;box-shadow:0 2px 10px rgba(139,105,20,.25);}  
.pstep-n.done{background:var(–green2);border-color:rgba(26,122,90,.3);color:var(–green);}  
.pstep-l{font-size:.7rem;color:var(–muted);text-align:center;line-height:1.4;font-weight:600;letter-spacing:0;}  
  
.step-content{display:none;}  
.step-content.active{display:block;}  
  
.course-opts{display:flex;flex-direction:column;gap:.75rem;}  
.copt{  
background:var(–cream2);border:1px solid var(–border);border-radius:10px;  
padding:1rem 1.2rem;cursor:pointer;transition:all .25s;  
display:flex;align-items:center;justify-content:space-between;gap:1rem;  
}  
.copt:hover,.copt.selected{border-color:var(–border2);background:rgba(184,148,31,.05);}  
.copt.selected .copt-radio{background:var(–gold2);border-color:var(–gold2);}  
.copt-left{display:flex;align-items:center;gap:.85rem;}  
.copt-pkg-name{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.25rem;font-weight:700;color:var(–gold3);}  
.copt-name{font-size:.86rem;font-weight:700;color:var(–text);}  
.copt-note{font-size:.71rem;color:var(–muted);margin-top:.08rem;}  
.copt-right{display:flex;align-items:center;gap:.75rem;}  
.copt-price{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.1rem;font-weight:700;color:var(–gold3);}  
.copt-radio{width:15px;height:15px;border-radius:50%;border:2px solid var(–border2);transition:all .2s;flex-shrink:0;}  
  
.coin-opts{display:grid;grid-template-columns:repeat(3,1fr);gap:.85rem;margin-bottom:1.5rem;}  
.coin-opt{  
background:var(–cream2);border:1px solid var(–border);border-radius:10px;  
padding:1.1rem;cursor:pointer;transition:all .25s;text-align:center;  
}  
.coin-opt:hover,.coin-opt.selected{border-color:var(–border2);background:rgba(184,148,31,.05);}  
.coin-sym{font-size:1.4rem;margin-bottom:.3rem;}  
.coin-name{font-size:.8rem;font-weight:800;color:var(–gold3);}  
.coin-net{font-size:.67rem;color:var(–muted);}  
  
.wallet-box{  
background:var(–cream2);border:1px solid var(–border);  
border-radius:10px;padding:1.4rem;margin-bottom:1.3rem;  
}  
.wallet-header{display:flex;align-items:center;gap:.75rem;margin-bottom:.9rem;}  
.wallet-coin-badge{padding:.28rem .85rem;border-radius:20px;font-size:.71rem;font-weight:800;}  
.wallet-coin-badge.btc{background:rgba(247,147,26,.09);color:#c97a10;border:1px solid rgba(247,147,26,.22);}  
.wallet-coin-badge.eth{background:rgba(98,126,234,.09);color:#4a5db0;border:1px solid rgba(98,126,234,.22);}  
.wallet-coin-badge.usdt{background:var(–green2);color:var(–green);border:1px solid rgba(26,122,90,.22);}  
.wallet-label{font-size:.83rem;font-weight:700;color:var(–text);}  
.wallet-net{font-size:.69rem;color:var(–muted);}  
.addr-row{  
display:flex;align-items:center;gap:.55rem;  
background:var(–white);border:1px solid var(–border);border-radius:7px;padding:.75rem .9rem;  
}  
.addr-text{font-family:‘Courier New’,monospace;font-size:.62rem;color:var(–muted);word-break:break-all;flex:1;line-height:1.5;}  
.copy-btn{  
background:rgba(184,148,31,.09);border:1px solid var(–border2);color:var(–gold3);  
padding:.28rem .8rem;border-radius:5px;font-size:.69rem;cursor:pointer;  
white-space:nowrap;transition:all .2s;font-family:‘Cairo’,sans-serif;flex-shrink:0;font-weight:700;  
}  
.copy-btn:hover{background:rgba(184,148,31,.16);}  
.copy-btn.copied{color:var(–green);border-color:rgba(26,122,90,.3);}  
  
.pay-amount-notice{  
background:rgba(184,148,31,.05);border:1px solid var(–border);  
border-radius:8px;padding:.95rem 1.1rem;margin-bottom:1.2rem;  
font-size:.83rem;color:var(–muted);line-height:1.85;  
}  
.pay-amount-notice strong{color:var(–gold3);font-weight:800;}  
.pay-warning{  
background:rgba(220,130,20,.05);border:1px solid rgba(220,130,20,.18);  
border-radius:8px;padding:.8rem 1rem;font-size:.75rem;color:#8a5a10;  
line-height:1.75;text-align:center;  
}  
  
/* Upload area */  
.upload-area{  
border:2px dashed var(–border2);border-radius:10px;  
padding:1.4rem;text-align:center;cursor:pointer;  
transition:all .25s;background:var(–cream2);  
position:relative;  
}  
.upload-area:hover{border-color:var(–gold2);background:rgba(184,148,31,.04);}  
.upload-area.has-file{border-color:var(–green);background:var(–green2);}  
.upload-icon{font-size:1.8rem;margin-bottom:.5rem;}  
.upload-text{font-size:.81rem;color:var(–muted);line-height:1.6;}  
.upload-text strong{color:var(–gold3);display:block;font-size:.84rem;}  
.upload-input{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}  
.upload-preview{margin-top:.8rem;display:none;}  
.upload-preview img{max-width:100%;max-height:140px;border-radius:7px;border:1px solid var(–border);object-fit:contain;}  
.upload-filename{font-size:.72rem;color:var(–green);font-weight:700;margin-top:.4rem;}  
  
.confirm-inputs{display:flex;flex-direction:column;gap:.95rem;}  
.fg{display:flex;flex-direction:column;gap:.38rem;}  
.fg label{font-size:.77rem;color:var(–muted2);font-weight:700;}  
.fg input,.fg textarea,.fg select{  
background:var(–cream2);border:1px solid var(–border);color:var(–text);  
padding:.82rem 1rem;border-radius:7px;font-family:‘Cairo’,sans-serif;  
font-size:.85rem;outline:none;transition:border-color .25s;direction:rtl;  
}  
.fg input:focus,.fg textarea:focus,.fg select:focus{border-color:var(–gold2);}  
.fg textarea{resize:vertical;min-height:75px;}  
  
.pay-nav{display:flex;gap:.75rem;margin-top:1.8rem;}  
.pay-next{  
flex:1;background:linear-gradient(135deg,var(–gold3),var(–gold2));color:#fff;  
border:none;padding:.9rem;border-radius:7px;font-family:‘Cairo’,sans-serif;  
font-size:.93rem;font-weight:800;cursor:pointer;transition:all .3s;  
box-shadow:0 6px 18px rgba(139,105,20,.2);  
}  
.pay-next:hover{filter:brightness(1.08);}  
.pay-next:disabled{opacity:.3;cursor:not-allowed;}  
.pay-back{  
background:transparent;color:var(–muted);border:1px solid var(–border);  
padding:.9rem 1.4rem;border-radius:7px;font-family:‘Cairo’,sans-serif;  
font-size:.83rem;cursor:pointer;transition:all .2s;  
}  
.pay-back:hover{border-color:var(–border2);color:var(–text);}  
  
.success-screen{text-align:center;padding:1rem 0;}  
.success-ico{font-size:3.2rem;margin-bottom:.9rem;}  
.success-title{font-family:‘Cormorant Garamond’,Georgia,serif;font-size:1.75rem;font-weight:700;background:linear-gradient(135deg,var(–gold3),var(–gold2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:.55rem;}  
.success-text{color:var(–muted);font-size:.87rem;line-height:1.95;margin-bottom:1.6rem;}  
.social-btns{display:flex;flex-direction:column;gap:.65rem;}  
.soc-btn{display:flex;align-items:center;justify-content:center;gap:.55rem;padding:.88rem;border-radius:8px;font-weight:700;font-size:.87rem;text-decoration:none;transition:all .25s;}  
.soc-btn.tg{background:rgba(0,136,204,.08);border:1px solid rgba(0,136,204,.22);color:#0088cc;}  
.soc-btn.tg:hover{background:rgba(0,136,204,.14);}  
  
/* Loading spinner */  
.spinner{display:none;width:20px;height:20px;border:2px solid rgba(255,255,255,.3);border-top-color:#fff;border-radius:50%;animation:spin2 .7s linear infinite;margin:0 auto;}  
@keyframes spin2{to{transform:rotate(360deg);}}  
  
/* ─── REVEAL ─── */  
.reveal{opacity:0;transform:translateY(18px);transition:opacity .6s ease,transform .6s ease;}  
.revealed{opacity:1;transform:translateY(0);}  
  
/* ─── RESPONSIVE ─── */  
@media(max-width:900px){  
.courses-grid,.community-grid,.why-grid{grid-template-columns:1fr;}  
.contact-grid{grid-template-columns:1fr;gap:2.5rem;}  
.nav-links{display:none;}  
.trust{grid-template-columns:repeat(2,1fr);}  
.r1,.r2,.r3{display:none;}  
}  
@media(max-width:600px){  
section{padding:4rem 4%;}  
nav{padding:.75rem 4%;}  
.pay-modal{padding:1.7rem 1.4rem;}  
.feats.cols{grid-template-columns:1fr;}  
}  
</style>  
  
</head>  
<body>  
  
<!-- ═══ NAV ═══ -->  
  
<nav>  
  <a href="#home" class="logo">  
    <div class="logo-mark">GL</div>  
    <div class="logo-text">GOLD <span>LIFE</span></div>  
  </a>  
  <ul class="nav-links">  
    <li><a href="#courses">الكورسات</a></li>  
    <li><a href="#community">المجتمع</a></li>  
    <li><a href="#why">لماذا نحن</a></li>  
    <li><a href="#contact">تواصل</a></li>  
  </ul>  
  <a href="#courses" class="nav-cta">احصل على الكورس</a>  
</nav>  
  
<!-- ═══ HERO ═══ -->  
  
<section class="hero" id="home">  
  <div class="hero-glow"></div>  
  <div class="hero-grid"></div>  
  <div class="ring r1"></div>  
  <div class="ring r2"></div>  
  <div class="ring r3"></div>  
  <div class="hero-content">  
    <div class="badge">كورسات التداول الاحترافية</div>  
    <h1>  
      <span class="accent">GOLD LIFE</span>  
      <span class="sub">تعلّم · تطبّق · تحترف</span>  
    </h1>  
    <p class="hero-desc">  
      تعلّم التداول من الصفر حتى الاحتراف الكامل.<br>  
      <strong>Order Blocks · PD Arrays · OSOK Model · Day Trading</strong>  
    </p>  
    <div class="btns">  
      <a href="#courses" class="btn-primary">استعرض الباقات</a>  
      <a href="#contact" class="btn-ghost">تواصل معنا</a>  
    </div>  
    <div class="stats-row">  
      <div class="stat"><div class="dot dot-btc"></div>Bitcoin</div>  
      <div class="stat"><div class="dot dot-eth"></div>Ethereum</div>  
      <div class="stat"><div class="dot dot-usdt"></div>USDT TRC-20</div>  
    </div>  
  </div>  
</section>  
  
<!-- ═══ TRUST ═══ -->  
  
<div class="trust">  
  <div class="ti reveal"><div class="tn">+500</div><div class="tl">متداول متعلّم</div></div>  
  <div class="ti reveal"><div class="tn">3</div><div class="tl">باقات تعليمية</div></div>  
  <div class="ti reveal"><div class="tn">ICT</div><div class="tl">منهجية أصيلة</div></div>  
  <div class="ti reveal"><div class="tn">24/7</div><div class="tl">دعم مستمر</div></div>  
</div>  
  
<!-- ═══ COURSES ═══ -->  
  
<section id="courses">  
  <div class="wrap">  
    <div class="sec-head reveal">  
      <span class="sec-tag">◆ الباقات التعليمية</span>  
      <div class="divider"><span>◆ ◆ ◆</span></div>  
      <h2 class="sec-title">اختر باقتك</h2>  
      <p class="sec-sub">كل باقة تغطي نفس المحتوى الكامل — الفرق فقط في مدة الوصول وعدد أشهر VIP المجانية.</p>  
    </div>  
    <div class="courses-grid">  
  
```  
  <!-- GOLD I -->  
  <div class="course-card reveal">  
    <div class="card-header">  
      <div class="card-ribbon">الأكثر طلباً</div>  
      <span class="pkg-name">GOLD I</span>  
      <div class="card-level">الباقة الأولى</div>  
      <h3 class="card-title">شهرين دراسة + شهر VIP مجاني</h3>  
      <p class="card-desc">ادرس الكورس كاملاً لمدة شهرين مع شهر VIP مجاني.</p>  
      <div class="duration">⏱ شهرين + شهر VIP مجاني</div>  
    </div>  
    <div class="card-body">  
      <div class="card-divider"></div>  
      <div class="feats-title">المحتوى الدراسي الكامل</div>  
      <ul class="feats cols">  
        <li>Basics & Market Structure</li><li>Order Flow</li>  
        <li>Draw on Liquidity</li><li>Internal / External</li>  
        <li>BRF-FVG / BISI SIBI+IFVG</li><li>Breaker Block</li>  
        <li>Rejection Block</li><li>Mitigation Block</li>  
        <li>Volume IMB+NWOG+NDOG</li><li>OSOK Model</li>  
        <li>Day Trading — Killzones</li><li>Advanced Concepts</li>  
        <li>PO3 Theory</li><li>Psychology & Risk Mgmt</li>  
        <li>Scalp — Ragheb Vision</li><li>One Million Dollar Strategy</li>  
      </ul>  
    </div>  
    <div class="card-footer">  
      <div class="price-block"><div class="amount">300$</div><div class="note">BTC · ETH · USDT</div></div>  
      <button class="buy-btn" onclick="openPayment('pkg1')">اشترِ الآن</button>  
    </div>  
  </div>  
  
  <!-- GOLD II -->  
  <div class="course-card featured reveal">  
    <div class="card-header">  
      <div class="card-ribbon new">موصى به</div>  
      <span class="pkg-name">GOLD II</span>  
      <div class="card-level">الباقة الثانية</div>  
      <h3 class="card-title">3 أشهر دراسة + شهرين VIP مجانيين</h3>  
      <p class="card-desc">ادرس الكورس كاملاً لمدة 3 أشهر مع شهرين VIP مجانيين.</p>  
      <div class="duration">⏱ 3 أشهر + شهرين VIP مجانيين</div>  
    </div>  
    <div class="card-body">  
      <div class="card-divider"></div>  
      <div class="feats-title">نفس المحتوى الكامل</div>  
      <ul class="feats cols">  
        <li>Basics & Market Structure</li><li>Order Flow</li>  
        <li>Draw on Liquidity</li><li>Internal / External</li>  
        <li>BRF-FVG / BISI SIBI+IFVG</li><li>Breaker Block</li>  
        <li>Rejection Block</li><li>Mitigation Block</li>  
        <li>Volume IMB+NWOG+NDOG</li><li>OSOK Model</li>  
        <li>Day Trading — Killzones</li><li>Advanced Concepts</li>  
        <li>PO3 Theory</li><li>Psychology & Risk Mgmt</li>  
        <li>Scalp — Ragheb Vision</li><li>One Million Dollar Strategy</li>  
      </ul>  
    </div>  
    <div class="card-footer">  
      <div class="price-block"><div class="amount">400$</div><div class="note">BTC · ETH · USDT</div></div>  
      <button class="buy-btn" onclick="openPayment('pkg2')">اشترِ الآن</button>  
    </div>  
  </div>  
  
  <!-- GOLD III -->  
  <div class="course-card reveal">  
    <div class="card-header">  
      <span class="pkg-name">GOLD III</span>  
      <div class="card-level">الباقة الثالثة</div>  
      <h3 class="card-title">Life Time Access — وصول مدى الحياة</h3>  
      <p class="card-desc">وصول مدى الحياة للكورس الكامل مع محتوى أضخم وأكثر تفصيلاً.</p>  
      <div class="duration lifetime">♾ وصول مدى الحياة + تحديثات مجانية</div>  
    </div>  
    <div class="card-body">  
      <div class="card-divider"></div>  
      <div class="feats-title">محتوى إضافي حصري</div>  
      <ul class="feats cols">  
        <li>Swing Type & Market Structure</li><li>Institutional Order Flow</li>  
        <li>IPDA Data Rangers</li><li>Seasonal Tendency</li>  
        <li>Intermarket Analysis</li><li>Propulsion Block</li>  
        <li>Advanced MMXM</li><li>Advanced Price Action</li>  
        <li>Advanced Turtle Soups</li><li>Swing High/Low Theory</li>  
        <li>POMIN Cycles</li><li>Change of State of Delivery</li>  
        <li>Grading Price Swing</li><li>Money Mgmt + Drawdown Plan</li>  
        <li>Psychologie & Journaling</li><li>One Million Dollar Swing Setup</li>  
      </ul>  
    </div>  
    <div class="card-footer">  
      <div class="price-block"><div class="amount">800$</div><div class="note">BTC · ETH · USDT</div></div>  
      <button class="buy-btn" onclick="openPayment('pkg3')">اشترِ الآن</button>  
    </div>  
  </div>  
  
</div>  
```  
  
  </div>  
</section>  
  
<!-- ═══ COMMUNITY ═══ -->  
  
<section id="community">  
  <div class="wrap">  
    <div class="sec-head reveal">  
      <span class="sec-tag">◆ المجتمع</span>  
      <div class="divider"><span>◆ ◆ ◆</span></div>  
      <h2 class="sec-title">انضم للمجتمع</h2>  
      <p class="sec-sub">مجموعات حصرية للتحليلات والإشارات والتعلم المستمر.</p>  
    </div>  
    <div class="community-grid">  
      <div class="comm-card vip reveal">  
        <div><div class="comm-icon">💎</div><span class="comm-badge vip-b">ELITE SIGNALS VIP</span></div>  
        <div>  
          <div class="comm-title">Elite Signals — قناة VIP</div>  
          <p class="comm-desc">قناة تليغرام VIP حصرية للإشارات والتحليلات اليومية على أعلى مستوى.</p>  
        </div>  
        <ul class="comm-perks">  
          <li>إشارات تداول يومية دقيقة</li>  
          <li>تحليل فوري للأسواق</li>  
          <li>تنبيهات الفرص عالية الجودة</li>  
          <li>دعم مباشر من المحلل</li>  
        </ul>  
        <div class="comm-footer">  
          <div class="comm-price"><div class="am">50$</div><div class="per">/ شهرياً</div></div>  
          <button class="buy-btn" onclick="openPayment('vip')">انضم الآن</button>  
        </div>  
      </div>  
      <div class="comm-card reveal">  
        <div><div class="comm-icon">🏆</div><span class="comm-badge hub-b">ELITE TRADERS HUB</span></div>  
        <div>  
          <div class="comm-title">Elite Traders Hub — مجموعة تعليمية</div>  
          <p class="comm-desc">مجموعة للمتداولين الذين تعلموا الأساسيات ويريدون التطور مع بيئة محترفة.</p>  
        </div>  
        <ul class="comm-perks">  
          <li>نقاش يومي بين المتداولين</li>  
          <li>مشاركة التحليلات والأفكار</li>  
          <li>متابعة الأداء والتحسّن</li>  
          <li>بيئة تعليمية تفاعلية</li>  
        </ul>  
        <div class="comm-footer">  
          <div class="comm-price"><div class="am">25$</div><div class="per">/ شهرياً</div></div>  
          <button class="buy-btn outline" onclick="openPayment('hub')">انضم الآن</button>  
        </div>  
      </div>  
    </div>  
  </div>  
</section>  
  
<!-- ═══ WHY ═══ -->  
  
<section id="why">  
  <div class="wrap">  
    <div class="sec-head reveal">  
      <span class="sec-tag">◆ لماذا GOLD LIFE</span>  
      <div class="divider"><span>◆ ◆ ◆</span></div>  
      <h2 class="sec-title">ليش تختارنا؟</h2>  
      <p class="sec-sub">مو بس كورس — منهجية كاملة وبيئة تعليمية احترافية.</p>  
    </div>  
    <div class="why-grid">  
      <div class="why-card reveal"><div class="why-ico">📐</div><h3>منهجية أصيلة</h3><p>محتوى مبني على مفاهيم أصيلة — فهم عميق وتطبيق عملي من الأساسيات للاحتراف.</p></div>  
      <div class="why-card reveal"><div class="why-ico">🎬</div><h3>شرح عربي واضح</h3><p>فيديوهات بالعربي بأسلوب مبسط ومفصّل — تفهم من أول مرة بدون تعقيد.</p></div>  
      <div class="why-card reveal"><div class="why-ico">📲</div><h3>دعم مستمر 24/7</h3><p>مجموعة خاصة وتواصل مباشر — ما تمشي لحالك في رحلة التداول.</p></div>  
      <div class="why-card reveal"><div class="why-ico">🔒</div><h3>دفع آمن بالكريبتو</h3><p>BTC، ETH، أو USDT — سريع وآمن بدون وسيط من أي مكان في العالم.</p></div>  
      <div class="why-card reveal"><div class="why-ico">📈</div><h3>نتائج حقيقية</h3><p>مئات المتداولين طبّقوا المنهجية وشافوا فرقاً واضحاً في أدائهم.</p></div>  
      <div class="why-card reveal"><div class="why-ico">♾️</div><h3>وصول مرن</h3><p>من شهرين حتى مدى الحياة — اختار الباقة اللي تناسبك وابدأ رحلتك.</p></div>  
    </div>  
  </div>  
</section>  
  
<!-- ═══ CONTACT ═══ -->  
  
<section id="contact">  
  <div class="wrap">  
    <div class="contact-grid">  
      <div class="contact-info reveal">  
        <span class="sec-tag">◆ تواصل معنا</span>  
        <h2>هيا نبدأ</h2>  
        <p>سؤال عن باقة؟ محتاج مساعدة في الاختيار؟ راسلنا على أي من القنوات التالية وسنرد في أقرب وقت.</p>  
        <div class="soc-links">  
          <a href="https://t.me/MR_GOLD_USD" class="soc-link" target="_blank">  
            <div class="ico">✈️</div>  
            <div><div class="lbl">Telegram</div><div class="val">t.me/MR_GOLD_USD</div></div>  
          </a>  
          <a href="https://www.instagram.com/goldlife_community" class="soc-link" target="_blank">  
            <div class="ico">📸</div>  
            <div><div class="lbl">Instagram</div><div class="val">@goldlife_community</div></div>  
          </a>  
        </div>  
      </div>  
      <div class="course-card reveal" style="border-radius:var(--r);">  
        <div class="card-header" style="padding-bottom:1.2rem;">  
          <div class="card-level">استفسار سريع</div>  
          <h3 class="card-title" style="font-size:1rem;">📩 أرسل استفسارك</h3>  
        </div>  
        <div class="card-body" id="inq-form">  
          <div class="confirm-inputs">  
            <div class="fg"><label>الاسم</label><input type="text" id="inq-name" placeholder="اسمك الكريم"></div>  
            <div class="fg"><label>تليغرام أو واتساب</label><input type="text" id="inq-contact" placeholder="للتواصل معك"></div>  
            <div class="fg">  
              <label>الباقة المطلوبة</label>  
              <select id="inq-pkg">  
                <option value="">— اختر —</option>  
                <option>GOLD I — 300$</option>  
                <option>GOLD II — 400$</option>  
                <option>GOLD III — 800$ (Lifetime)</option>  
                <option>Elite Signals VIP — 50$</option>  
                <option>Elite Traders Hub — 25$</option>  
              </select>  
            </div>  
            <div class="fg"><label>رسالة (اختياري)</label><textarea id="inq-msg" placeholder="أي استفسار..."></textarea></div>  
          </div>  
          <button class="buy-btn" style="width:100%;padding:.88rem;margin-top:1.1rem;font-size:.91rem;" onclick="sendInquiry()">إرسال الاستفسار ◆</button>  
        </div>  
        <div id="inq-ok" style="display:none;text-align:center;padding:2.5rem 1.5rem;">  
          <div style="font-size:2.4rem;margin-bottom:.9rem;">✅</div>  
          <div style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.25rem;font-weight:700;color:var(--gold3);">تم استلام استفسارك!</div>  
          <div style="color:var(--muted);font-size:.83rem;margin-top:.45rem;line-height:1.7;">سنتواصل معك قريباً عبر تليغرام أو واتساب.</div>  
        </div>  
      </div>  
    </div>  
  </div>  
</section>  
  
<footer>  
  <div class="foot-logo">GOLD LIFE</div>  
  <p>كورسات تداول احترافية · الدفع بـ <span>BTC</span> · <span>ETH</span> · <span>USDT</span></p>  
  <p>تليغرام: <span>t.me/MR_GOLD_USD</span> · انستغرام: <span>@goldlife_community</span></p>  
  <p style="margin-top:.4rem;">© <span id="yr"></span> GOLD LIFE — جميع الحقوق محفوظة</p>  
</footer>  
  
<!-- ═══ PAYMENT MODAL ═══ -->  
  
<div id="payment-overlay">  
  <div class="pay-modal">  
    <button class="pay-close" onclick="closePayment()">✕</button>  
    <div class="pay-title">إتمام الدفع</div>  
    <div class="pay-sub">اتبع الخطوات لإتمام طلبك بأمان وسرعة.</div>  
    <div class="pay-steps">  
      <div class="pstep"><div class="pstep-n active" id="sn1">1</div><div class="pstep-l">الباقة</div></div>  
      <div class="pstep"><div class="pstep-n" id="sn2">2</div><div class="pstep-l">العملة</div></div>  
      <div class="pstep"><div class="pstep-n" id="sn3">3</div><div class="pstep-l">الدفع</div></div>  
      <div class="pstep"><div class="pstep-n" id="sn4">4</div><div class="pstep-l">تأكيد</div></div>  
    </div>  
  
```  
<!-- STEP 1 -->  
<div class="step-content active" id="step1">  
  <div class="course-opts">  
    <div class="copt" onclick="selectPkg(this,'pkg1','300$','GOLD I — شهرين + VIP')">  
      <div class="copt-left"><div class="copt-pkg-name">GOLD I</div><div><div class="copt-name">الباقة الأولى</div><div class="copt-note">شهرين + شهر VIP مجاني</div></div></div>  
      <div class="copt-right"><div class="copt-price">300$</div><div class="copt-radio"></div></div>  
    </div>  
    <div class="copt" onclick="selectPkg(this,'pkg2','400$','GOLD II — 3 أشهر + VIP')">  
      <div class="copt-left"><div class="copt-pkg-name">GOLD II</div><div><div class="copt-name">الباقة الثانية</div><div class="copt-note">3 أشهر + شهرين VIP مجانيين</div></div></div>  
      <div class="copt-right"><div class="copt-price">400$</div><div class="copt-radio"></div></div>  
    </div>  
    <div class="copt" onclick="selectPkg(this,'pkg3','800$','GOLD III — Life Time Access')">  
      <div class="copt-left"><div class="copt-pkg-name">GOLD III</div><div><div class="copt-name">الباقة الثالثة</div><div class="copt-note">Life Time Access — وصول مدى الحياة</div></div></div>  
      <div class="copt-right"><div class="copt-price">800$</div><div class="copt-radio"></div></div>  
    </div>  
    <div class="copt" onclick="selectPkg(this,'vip','50$','Elite Signals VIP — شهرياً')">  
      <div class="copt-left"><div style="font-size:1.3rem;">💎</div><div><div class="copt-name">Elite Signals VIP</div><div class="copt-note">قناة إشارات VIP — شهرياً</div></div></div>  
      <div class="copt-right"><div class="copt-price">50$</div><div class="copt-radio"></div></div>  
    </div>  
    <div class="copt" onclick="selectPkg(this,'hub','25$','Elite Traders Hub — شهرياً')">  
      <div class="copt-left"><div style="font-size:1.3rem;">🏆</div><div><div class="copt-name">Elite Traders Hub</div><div class="copt-note">مجموعة تعليمية — شهرياً</div></div></div>  
      <div class="copt-right"><div class="copt-price">25$</div><div class="copt-radio"></div></div>  
    </div>  
  </div>  
  <div class="pay-nav">  
    <button class="pay-next" id="next1" onclick="goStep(2)" disabled>التالي ←</button>  
  </div>  
</div>  
  
<!-- STEP 2 -->  
<div class="step-content" id="step2">  
  <div class="coin-opts">  
    <div class="coin-opt" onclick="selectCoin(this,'btc')"><div class="coin-sym">₿</div><div class="coin-name">BTC</div><div class="coin-net">Bitcoin</div></div>  
    <div class="coin-opt" onclick="selectCoin(this,'eth')"><div class="coin-sym">Ξ</div><div class="coin-name">ETH</div><div class="coin-net">ERC-20</div></div>  
    <div class="coin-opt" onclick="selectCoin(this,'usdt')"><div class="coin-sym">₮</div><div class="coin-name">USDT</div><div class="coin-net">TRC-20</div></div>  
  </div>  
  <div class="pay-nav">  
    <button class="pay-back" onclick="goStep(1)">→ رجوع</button>  
    <button class="pay-next" id="next2" onclick="goStep(3)" disabled>التالي ←</button>  
  </div>  
</div>  
  
<!-- STEP 3 -->  
<div class="step-content" id="step3">  
  <div class="pay-amount-notice">  
    أرسل ما يعادل <strong id="pay-amount-display">—</strong> على العنوان أدناه.<br>  
    بعد الإرسال احفظ إيصال التحويل (hash) وانتقل للخطوة التالية.  
  </div>  
  <div class="wallet-box">  
    <div class="wallet-header">  
      <div class="wallet-coin-badge" id="wcb">—</div>  
      <div><div class="wallet-label" id="wname">—</div><div class="wallet-net" id="wnet">—</div></div>  
    </div>  
    <div class="addr-row">  
      <div class="addr-text" id="wallet-addr">—</div>  
      <button class="copy-btn" onclick="copyAddr()">نسخ</button>  
    </div>  
  </div>  
  <div class="pay-warning">⚠️ تأكد من اختيار الشبكة الصحيحة قبل الإرسال.<br>أي خطأ في الشبكة قد يؤدي لخسارة الأموال.</div>  
  <div class="pay-nav">  
    <button class="pay-back" onclick="goStep(2)">→ رجوع</button>  
    <button class="pay-next" onclick="goStep(4)">أرسلت الدفعة ✓</button>  
  </div>  
</div>  
  
<!-- STEP 4 -->  
<div class="step-content" id="step4">  
  <div class="confirm-inputs">  
    <div class="fg"><label>اسمك الكريم *</label><input type="text" id="cf-name" placeholder="الاسم"></div>  
    <div class="fg"><label>معرّف تليغرام أو رقم واتساب *</label><input type="text" id="cf-contact" placeholder="للتواصل وتسليم الكورس"></div>  
    <div class="fg"><label>Hash / رقم التحويل (اختياري)</label><input type="text" id="cf-hash" placeholder="transaction hash للتأكيد السريع"></div>  
  
    <!-- Screenshot Upload -->  
    <div class="fg">  
      <label>سكرين شوت الفاتورة / إيصال الدفع *</label>  
      <div class="upload-area" id="upload-area">  
        <input type="file" class="upload-input" id="screenshot-input" accept="image/*" onchange="handleUpload(this)">  
        <div class="upload-icon">📸</div>  
        <div class="upload-text">  
          <strong>ارفع سكرين شوت الإيصال</strong>  
          اضغط لاختيار الصورة أو اسحبها هنا<br>  
          <span style="font-size:.68rem;color:var(--muted);">JPG · PNG · WEBP — حتى 10MB</span>  
        </div>  
        <div class="upload-preview" id="upload-preview">  
          <img id="preview-img" src="" alt="preview">  
          <div class="upload-filename" id="upload-filename"></div>  
        </div>  
      </div>  
    </div>  
  
    <div class="fg"><label>ملاحظة إضافية (اختياري)</label><textarea id="cf-note" placeholder="أي تفاصيل إضافية..."></textarea></div>  
  </div>  
  <div class="pay-nav">  
    <button class="pay-back" onclick="goStep(3)">→ رجوع</button>  
    <button class="pay-next" id="submit-btn" onclick="submitOrder()">  
      <span id="submit-text">إرسال الطلب ◆</span>  
      <div class="spinner" id="submit-spinner"></div>  
    </button>  
  </div>  
</div>  
  
<!-- SUCCESS -->  
<div class="step-content" id="step-success">  
  <div class="success-screen">  
    <div class="success-ico">🎉</div>  
    <div class="success-title">تم استلام طلبك!</div>  
    <p class="success-text">شكراً جزيلاً! تم تسجيل طلبك بنجاح.<br>سنتحقق من الدفعة ونتواصل معك خلال ساعات قليلة<br>عبر تليغرام أو واتساب لتسليمك الكورس.</p>  
    <div class="social-btns">  
      <a href="https://t.me/MR_GOLD_USD" class="soc-btn tg" target="_blank">✈️ &nbsp; تواصل على تليغرام — @MR_GOLD_USD</a>  
    </div>  
    <button class="pay-back" style="width:100%;margin-top:1rem;" onclick="closePayment()">إغلاق</button>  
  </div>  
</div>  
```  
  
  </div>  
</div>  
  
<script>  
document.getElementById('yr').textContent = new Date().getFullYear();  
  
const TELEGRAM_TOKEN = '8706338751:AAEITbCVVm9KyOo0Lf8IpltSRv4lJddLUUY';  
const TELEGRAM_CHAT_ID = '1701859057';  
  
const wallets = {  
  btc:  {addr:'bc1q4wcjjk2phzkmscteyqj4zsqdy735ns8aqp8g78', name:'Bitcoin',      net:'Bitcoin Mainnet', cls:'btc'},  
  eth:  {addr:'0x2E0093Ae524B379B0e45D36Ac84cE13B7d73B432',  name:'Ethereum',    net:'ERC-20',          cls:'eth'},  
  usdt: {addr:'TGjB1wfFP4uXh6KAHrfsb64PmfvJMTprwN',         name:'Tether USDT', net:'TRC-20 (TRON)',   cls:'usdt'}  
};  
  
let state = {pkg:null, pkgLabel:'', price:'', coin:null, step:1, screenshotFile:null, screenshotData:null};  
  
/* ─── MODAL OPEN / CLOSE ─── */  
function openPayment(pkg) {  
  state = {pkg:null, pkgLabel:'', price:'', coin:null, step:1, screenshotFile:null, screenshotData:null};  
  goStep(1, true);  
  clearUpload();  
  
  const map = {  
    pkg1:{id:'pkg1',price:'300$',label:'GOLD I'},  
    pkg2:{id:'pkg2',price:'400$',label:'GOLD II'},  
    pkg3:{id:'pkg3',price:'800$',label:'GOLD III'},  
    vip: {id:'vip', price:'50$', label:'Elite Signals VIP'},  
    hub: {id:'hub', price:'25$', label:'Elite Traders Hub'}  
  };  
  
  document.querySelectorAll('.copt').forEach(o => {  
    o.classList.remove('selected');  
    const r = o.querySelector('.copt-radio');  
    if(r){r.style.background='';r.style.borderColor='';}  
  });  
  
  if(pkg && map[pkg]){  
    const m = map[pkg];  
    document.querySelectorAll('.copt').forEach(o => {  
      const p = o.querySelector('.copt-price');  
      if(p && p.textContent === m.price){  
        o.classList.add('selected');  
        const r = o.querySelector('.copt-radio');  
        if(r){r.style.background='var(--gold2)';r.style.borderColor='var(--gold2)';}  
      }  
    });  
    state.pkg=m.id; state.price=m.price; state.pkgLabel=m.label;  
    document.getElementById('next1').disabled = false;  
  }  
  
  document.getElementById('payment-overlay').classList.add('open');  
  document.body.style.overflow = 'hidden';  
}  
  
function closePayment(){  
  document.getElementById('payment-overlay').classList.remove('open');  
  document.body.style.overflow = '';  
}  
  
document.getElementById('payment-overlay').addEventListener('click', function(e){  
  if(e.target === this) closePayment();  
});  
  
/* ─── STEPS ─── */  
function goStep(n){  
  document.querySelectorAll('.step-content').forEach(s => s.classList.remove('active'));  
  const el = document.getElementById('step'+n);  
  if(el) el.classList.add('active');  
  state.step = n;  
  [1,2,3,4].forEach(i => {  
    const sn = document.getElementById('sn'+i);  
    sn.classList.remove('active','done');  
    if(i < n){sn.classList.add('done'); sn.textContent='✓';}  
    else if(i === n){sn.classList.add('active'); sn.textContent=i;}  
    else sn.textContent=i;  
  });  
  if(n===3 && state.coin) renderWallet();  
}  
  
/* ─── SELECT PKG ─── */  
function selectPkg(el,id,price,label){  
  document.querySelectorAll('.copt').forEach(o=>{  
    o.classList.remove('selected');  
    const r=o.querySelector('.copt-radio');  
    if(r){r.style.background='';r.style.borderColor='';}  
  });  
  el.classList.add('selected');  
  const r = el.querySelector('.copt-radio');  
  if(r){r.style.background='var(--gold2)';r.style.borderColor='var(--gold2)';}  
  state.pkg=id; state.price=price; state.pkgLabel=label;  
  document.getElementById('next1').disabled = false;  
}  
  
/* ─── SELECT COIN ─── */  
function selectCoin(el,coin){  
  document.querySelectorAll('.coin-opt').forEach(o=>o.classList.remove('selected'));  
  el.classList.add('selected');  
  state.coin = coin;  
  document.getElementById('next2').disabled = false;  
}  
  
/* ─── RENDER WALLET ─── */  
function renderWallet(){  
  const w = wallets[state.coin];  
  document.getElementById('wallet-addr').textContent = w.addr;  
  document.getElementById('wcb').textContent = state.coin.toUpperCase();  
  document.getElementById('wcb').className = 'wallet-coin-badge '+w.cls;  
  document.getElementById('wname').textContent = w.name;  
  document.getElementById('wnet').textContent = w.net;  
  document.getElementById('pay-amount-display').textContent = state.price+' — بـ '+state.coin.toUpperCase();  
}  
  
/* ─── COPY ADDRESS ─── */  
function copyAddr(){  
  const w = wallets[state.coin];  
  navigator.clipboard.writeText(w.addr).then(()=>{  
    const btn = document.querySelector('.copy-btn');  
    const orig = btn.textContent;  
    btn.textContent='✓ تم النسخ'; btn.classList.add('copied');  
    setTimeout(()=>{btn.textContent=orig; btn.classList.remove('copied');}, 2500);  
  });  
}  
  
/* ─── UPLOAD SCREENSHOT ─── */  
function handleUpload(input){  
  const file = input.files[0];  
  if(!file) return;  
  if(file.size > 10*1024*1024){  
    alert('حجم الملف كبير جداً، الحد الأقصى 10MB'); return;  
  }  
  state.screenshotFile = file;  
  
  const reader = new FileReader();  
  reader.onload = function(e){  
    state.screenshotData = e.target.result;  
    document.getElementById('preview-img').src = e.target.result;  
    document.getElementById('upload-filename').textContent = '✓ ' + file.name;  
    document.getElementById('upload-preview').style.display = 'block';  
    document.getElementById('upload-area').classList.add('has-file');  
  };  
  reader.readAsDataURL(file);  
}  
  
function clearUpload(){  
  state.screenshotFile = null;  
  state.screenshotData = null;  
  document.getElementById('upload-preview').style.display = 'none';  
  document.getElementById('upload-area').classList.remove('has-file');  
  const inp = document.getElementById('screenshot-input');  
  if(inp) inp.value='';  
}  
  
/* ─── SUBMIT ORDER → TELEGRAM ─── */  
async function submitOrder(){  
  const name = document.getElementById('cf-name').value.trim();  
  const contact = document.getElementById('cf-contact').value.trim();  
  const hash = document.getElementById('cf-hash').value.trim();  
  const note = document.getElementById('cf-note').value.trim();  
  
  if(!name || !contact){  
    alert('الرجاء إدخال الاسم وبيانات التواصل على الأقل.'); return;  
  }  
  if(!state.screenshotData){  
    alert('الرجاء رفع سكرين شوت الإيصال لتأكيد الطلب.'); return;  
  }  
  
  const btn = document.getElementById('submit-btn');  
  const txt = document.getElementById('submit-text');  
  const spin = document.getElementById('submit-spinner');  
  btn.disabled=true; txt.style.display='none'; spin.style.display='block';  
  
  const msg = `🟡 طلب جديد — GOLD LIFE\n\n` +  
    `📦 الباقة: ${state.pkgLabel}\n` +  
    `💰 السعر: ${state.price}\n` +  
    `🪙 طريقة الدفع: ${state.coin ? state.coin.toUpperCase() : '—'}\n\n` +  
    `👤 الاسم: ${name}\n` +  
    `📱 التواصل: ${contact}\n` +  
    (hash ? `🔗 Hash: ${hash}\n` : '') +  
    (note ? `📝 ملاحظة: ${note}\n` : '') +  
    `\n⏰ ${new Date().toLocaleString('ar-SA')}`;  
  
  try {  
    // 1. Send text message  
    const msgRes = await fetch(`https://api.telegram.org/bot${TELEGRAM_TOKEN}/sendMessage`, {  
      method:'POST',  
      headers:{'Content-Type':'application/json'},  
      body: JSON.stringify({chat_id: TELEGRAM_CHAT_ID, text: msg})  
    });  
    const msgData = await msgRes.json();  
    if(!msgData.ok){  
      throw new Error('Telegram error: ' + JSON.stringify(msgData));  
    }  
  
    // 2. Send screenshot as document (reliable)  
    if(state.screenshotFile){  
      const formData = new FormData();  
      formData.append('chat_id', TELEGRAM_CHAT_ID);  
      formData.append('document', state.screenshotFile, 'receipt.jpg');  
      formData.append('caption', `📸 إيصال الدفع — ${name} | ${state.pkgLabel}`);  
      await fetch(`https://api.telegram.org/bot${TELEGRAM_TOKEN}/sendDocument`, {  
        method:'POST', body: formData  
      });  
    }  
  
    // Success  
    document.querySelectorAll('.step-content').forEach(s=>s.classList.remove('active'));  
    document.getElementById('step-success').classList.add('active');  
    [1,2,3,4].forEach(i=>{  
      const sn=document.getElementById('sn'+i);  
      sn.classList.remove('active'); sn.classList.add('done'); sn.textContent='✓';  
    });  
  
  } catch(err){  
    btn.disabled=false; txt.style.display='block'; spin.style.display='none';  
    console.error('Telegram error:', err);  
    alert('حدث خطأ: ' + err.message + '\n\nتواصل معنا على تليغرام: @MR_GOLD_USD');  
  }  
}  
  
/* ─── CONTACT FORM ─── */  
function sendInquiry(){  
  const n=document.getElementById('inq-name').value.trim();  
  const c=document.getElementById('inq-contact').value.trim();  
  const p=document.getElementById('inq-pkg').value;  
  if(!n||!c||!p){alert('الرجاء تعبئة الاسم وبيانات التواصل واختيار الباقة.');return;}  
  document.getElementById('inq-form').style.display='none';  
  document.getElementById('inq-ok').style.display='block';  
}  
  
/* ─── SCROLL REVEAL ─── */  
const obs = new IntersectionObserver(e=>{  
  e.forEach(x=>{if(x.isIntersecting) x.target.classList.add('revealed');});  
},{threshold:.08});  
document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));  
</script>  
  
</body>  
</html>  

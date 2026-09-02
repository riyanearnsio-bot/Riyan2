```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>VIP Proxy Server</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    background:#f4f5f7;
    color:#111;
}

.activity{
    background:#ffffff;
    padding:12px 10px;
    font-size:13px;
    font-weight:bold;
    line-height:1.7;
    border-bottom:1px solid #ddd;
    text-align:center;
}

.container{
    max-width:520px;
    margin:auto;
    background:white;
    min-height:100vh;
    padding-bottom:30px;
}

.watch{
    text-align:center;
    font-size:24px;
    font-weight:900;
    margin:22px 0 12px;
}

.video-box{
    width:94%;
    margin:auto;
    background:#000;
    border-radius:8px;
    overflow:hidden;
    box-shadow:0 3px 12px rgba(0,0,0,.25);
}

.video-box video{
    width:100%;
    display:block;
    background:#000;
}

.premium{
    text-align:center;
    margin-top:24px;
}

.premium span{
    background:#ffe600;
    padding:7px 16px;
    border-radius:20px;
    font-size:13px;
    font-weight:900;
}

.title{
    text-align:center;
    font-size:28px;
    font-weight:900;
    margin-top:12px;
    letter-spacing:.5px;
}

.subtitle{
    text-align:center;
    color:#555;
    font-size:15px;
    font-weight:bold;
    margin-top:8px;
}

.rating{
    text-align:center;
    margin-top:13px;
    color:#ffb400;
    font-size:21px;
    letter-spacing:2px;
}

.rating-text{
    color:#555;
    font-size:12px;
    margin-left:5px;
}

.install{
    display:block;
    width:88%;
    margin:22px auto;
    padding:17px 10px;
    background:#16a34a;
    color:white;
    text-align:center;
    text-decoration:none;
    border-radius:8px;
    font-size:21px;
    font-weight:900;
    box-shadow:0 4px 10px rgba(0,0,0,.2);
    transition:.2s;
}

.install:hover{
    transform:scale(1.02);
    background:#12843d;
}

.comments-title{
    width:90%;
    margin:25px auto 10px;
    font-size:17px;
    font-weight:900;
    border-bottom:1px solid #ddd;
    padding-bottom:8px;
}

.comment{
    width:90%;
    margin:8px auto;
    background:#f5f5f5;
    padding:10px;
    border-radius:7px;
    font-size:13px;
}

.comment b{
    color:#222;
}

.watch-count{
    text-align:center;
    color:#555;
    font-size:13px;
    margin-top:15px;
}

.footer{
    text-align:center;
    margin-top:25px;
    color:#888;
    font-size:11px;
}

</style>
</head>

<body>

<div class="container">

    <div class="activity">
        🔥 Arjun claimed VIP proxy ✅ 1,892 users installed today ⚡
    </div>

    <div class="watch">
        WATCH FULL VIDEO
    </div>

    <div class="video-box">

        <video
            controls
            playsinline
            preload="metadata"
            poster="poster.jpg">

            <source src="video.mp4" type="video/mp4">

            Your browser does not support the video tag.

        </video>

    </div>

    <div class="premium">
        <span>NEW PREMIUM</span>
    </div>

    <div class="title">
        VIP PROXY SERVER
    </div>

    <div class="subtitle">
        FREE FIRE PROXY SERVER UNLIMITED ACCESS
    </div>

    <div class="rating">
        ★★★★★
        <span class="rating-text">4.9/5</span>
    </div>

    <!-- INSTALL BUTTON -->

    <a
        class="install"
        href="https://1024terabox.com/s/1wpkm32Lh4oLHV8eGo5DBbA"
        target="_blank"
        rel="noopener noreferrer">

        ⬇ INSTALL NOW

    </a>

    <div class="comments-title">
        Live Comments
    </div>

    <div class="comment">
        <b>Arjun</b><br>
        🔥 VIP proxy working perfectly!
    </div>

    <div class="comment">
        <b>Vikas</b><br>
        ⚡ Proxy access received.
    </div>

    <div class="comment">
        <b>Mohit</b><br>
        🛡 VIP server activated.
    </div>

    <div class="comment">
        <b>Harsh</b><br>
        ✅ Installed successfully.
    </div>

    <div class="watch-count">
        👀 842 watching
    </div>

    <div class="footer">
        © 2026 VIP Proxy Server
    </div>

</div>

<script>

const activities = [
    "🔥 Arjun claimed VIP proxy",
    "⚡ Vikas claimed proxy access",
    "🛡 Mohit claimed VIP server",
    "✅ Harsh installed proxy now",
    "🔥 Rahul claimed VIP proxy",
    "⚡ Aman installed proxy"
];

let activityBox = document.querySelector(".activity");
let i = 0;

setInterval(() => {

    i++;

    if(i >= activities.length){
        i = 0;
    }

    activityBox.innerHTML =
        activities[i] +
        " ✅ 1,892 users installed today";

}, 3500);


let watching = 842;

setInterval(() => {

    let change = Math.random() > .5 ? 1 : -1;

    watching += change;

    if(watching < 800){
        watching = 800;
    }

    if(watching > 900){
        watching = 900;
    }

    document.querySelector(".watch-count").innerHTML =
        "👀 " + watching + " watching";

}, 5000);

</script>

</body>
</html>

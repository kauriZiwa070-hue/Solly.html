# Solly.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Ek Chhoti Si Maafi ✨</title>

<style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        min-height: 100vh;
        background: #e9ddff;
        font-family: Georgia, "Times New Roman", serif;
        color: #3f3152;
        padding: 30px 15px;
    }

    .page {
        max-width: 750px;
        margin: auto;
        background: #fffdfd;
        padding: 45px 55px;
        border-radius: 4px;
        box-shadow: 0 12px 35px rgba(74, 47, 95, 0.20);
        border: 1px solid #d8c5f5;
        position: relative;
    }

    .top {
        text-align: center;
        font-size: 25px;
        letter-spacing: 5px;
        margin-bottom: 25px;
    }

    .date {
        text-align: right;
        margin-bottom: 35px;
        font-size: 15px;
    }

    .to {
        margin-bottom: 25px;
        line-height: 1.7;
    }

    .subject {
        font-weight: bold;
        text-decoration: underline;
        margin: 25px 0;
        font-size: 17px;
    }

    p {
        font-size: 16px;
        line-height: 1.9;
        text-align: justify;
        margin: 17px 0;
    }

    .cheesy {
        text-align: center;
        font-style: italic;
        color: #8059a8;
        margin: 28px 10px;
        font-size: 17px;
    }

    .signature {
        margin-top: 35px;
        line-height: 1.8;
    }

    .footer {
        text-align: center;
        margin-top: 30px;
        font-size: 20px;
        letter-spacing: 4px;
    }

    .sorry-btn {
        display: block;
        margin: 30px auto 0;
        padding: 12px 25px;
        border: none;
        border-radius: 25px;
        background: #b99ae8;
        color: white;
        font-size: 15px;
        cursor: pointer;
        transition: 0.3s;
    }

    .sorry-btn:hover {
        transform: scale(1.05);
        background: #9d79d0;
    }

    #hidden {
        display: none;
        text-align: center;
        margin-top: 20px;
        color: #704c91;
        font-weight: bold;
        line-height: 1.7;
    }

    @media(max-width:600px) {
        .page {
            padding: 30px 22px;
        }

        p {
            font-size: 15px;
        }
    }
</style>
</head>

<body>

<div class="page">

    <div class="top">
        ✨ 🤍 💗 🫂 🐣 💋 😭 🛐
    </div>

    <div class="date">
        Date: __________
    </div>

    <div class="to">
        <b>To,</b><br>
        My favourite person,<br>
        The one I owe a proper apology to. 🤍
    </div>

    <div class="subject">
        Subject: A heartfelt apology for misunderstanding you 🥺
    </div>

    <p>
        Dear You,
    </p>

    <p>
        Sabse pehle, <b>I am genuinely sorry. 😭</b>
        Mujhse tumhe misunderstand karne ki galti hui aur honestly,
        mujhe ab realize ho raha hai ki maine situation ko bina properly
        samjhe judge kar liya.
    </p>

    <p>
        Shayad mujhe pehle tumhari side calmly samajhni chahiye thi,
        tumse baat karni chahiye thi aur phir koi conclusion nikalna chahiye tha.
        But maine aisa nahi kiya, and for that, I am really really sorry. 🤍
    </p>

    <p>
        I know sirf "sorry" bol dene se meri galti magically disappear nahi ho jayegi,
        but still... <b>sorry.</b> 🫂
        I genuinely didn't mean to hurt you or make you feel that
        I don't trust or understand you.
    </p>

    <div class="cheesy">
        “Galti meri thi janaab... dil se maafi maang raha hoon. 🛐😭”
    </div>

    <p>
        Aur haan, thoda Bollywood style mein bolun toh —
        <b>picture abhi baaki hai mere dost. 😭</b>
        Main chahti hoon ki misunderstanding ki wajah se humare beech
        jo bhi awkwardness aayi hai, woh yahin khatam ho.
    </p>

    <div class="cheesy">
        “Tum naraz ho toh dil ka scene incomplete sa lagta hai...
        toh please ek baar maaf kar do. 💗”
    </div>

    <p>
        I promise ki next time main assumptions banane ke bajaye
        tumse directly baat karungi aur tumhari side samajhne ki proper
        koshish karungi.
    </p>

    <p>
        So, with all my heart...
        <b>I am sorry. 🥺🤍</b>
        Please meri ye chhoti si apology accept kar lena. 🫂✨
    </p>

    <div class="signature">
        Yours sincerely,<br>
        <b>Someone who is genuinely sorry 😭💗</b>
    </div>

    <div class="footer">
        ✨ 🤍 🫂 💗 🐣 💋 🛐
    </div>

    <button class="sorry-btn" onclick="showMessage()">
        One last thing... 🥺
    </button>

    <div id="hidden">
        Please don't let one misunderstanding erase all the good things. 🤍<br>
        I really, really am sorry. 🫂😭
    </div>

</div>

<script>
function showMessage() {
    document.getElementById("hidden").style.display = "block";
}
</script>

</body>
</html>

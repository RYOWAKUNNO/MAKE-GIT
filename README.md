<!DOCTYPE html>  
<html> 
<head>
<meta charset="UTF-8"> 
<title>お問い合わせ</title>
<link rel="stylesheet"href="style.css">
</head>
<body>
<h1>お問い合わせフォーム</h1>
<div class="">
    お問い合わせ内容の入力<br>
    入力内容の確認<br>
    送信完了
</div>

<form>
<h1>お客様の情報を入力してください</h1>
<tr>
    <th class="contact-item"></th>
    <td class="contact-body"></td>
  </tr>
<div>お名前　必須
    <br>
    <input type="text" id="name" name="name">
</div>

<div>電話番号
    <br>
    <input type="text" id="number" name="number">
</div>

<div>メールアドレス　必須
    <br>
    <input type="text" id="mail" name="mail">
</div>

<br>
<div>確認のためもう一度入力してください
    <input type="text" id="mail" name="mail">
</div>
</form>

<h1>お問い合わせ内容を入力してください</h1>
<div>タイトル　必須
    <br>
    <input type="text" id="name" name="name">
</div>

<div>お問い合わせ内容　必須
<br>
<form action=”check.html” method="GET"> 
    <textarea id="message" name="message"></textarea>
    <br>
    <input type="submit" value="入力内容を確認する" />  
</form>
</div>
</body>
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="css/style.css">
  <title>お問い合わせフォームを作る</title>
</head>
<body>
    <form action="program.php" method="post">
        <dl>
            <dt>お問い合わせの種別</dt>
            <dd>
                <label><input type="checkbox" name="category" value="お問い合わせ">お問い合わせ</label>
                <label><input type="checkbox" name="category" value="新規お申し込み">新規お申し込み</label>
                <label><input type="checkbox" name="category" value="資料請求">資料請求</label>
            </dd>
            <dt>お名前<span class="must">※</span></dt>
            <dd>
                <input type="text" name="name" required placeholder="田中 太郎">
            </dd>
            <dt>ふりがな<span class="must">※</span></dt>
            <dd>
                <input type="text" name="kana" required placeholder="たなか たろう">
            </dd>
            <dt>メールアドレス<span class="must">※</span></dt>
            <dd>
                <input type="email" name="email" required placeholder="sample@test.com">
            </dd>
            <dt>性別</dt>
            <dd>
                <label><input type="radio" name="sex" value="男">男</label>
                <label><input type="radio" name="sex" value="女">女</label>
            </dd>
            <dt>どこでお知りになりましたか？</dt>
            <dd>
                <select name="how">
                    <option value="チラシ・DM">チラシ・DM</option>
                    <option value="知り合いからの紹介">知り合いからの紹介</option>
                    <option value="その他">その他</option>
                </select>
            </dd>
            <dt>お問い合わせ・ご質問内容</dt>
            <dd>
                <textarea name="comment" cols="20" rows="5"></textarea>
            </dd>
        </dl>
        <p class="submit"><input type="submit" name="submit" value="送信する"></p>
    </form>
</body>
</html>
</html>

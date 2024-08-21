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
</html>

### 解答例

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>HTML-CSS課題</title>
    <style>
    <!--
        header {
            color:#FFF;
            text-shadow:3px 3px 3px #000;
            text-align:center;
            background-color:#005FFF;
            width:1000px;
            height:80px;
            padding:1px 0px;
        }
        nav {
            background-color:#EEEEEE;
            width:190px;
            height:300px;
            margin-top:10px;
            margin-bottom:10px;
            float:left;
        }
        nav div {
            color:#FFF;
            background-color:#000;
            text-align:center;
            padding-top:8px;
            height:30px;
        }
        article {
            background-color:#BAD3FF;
            text-align:center;
            width:800px;
            height:300px;
            margin-top:10px;
            margin-bottom:10px;
            margin-left:10px;
            float:left;
        }
        footer {
            color:#FFF;
            text-shadow:1px 1px 3px #000;
            text-align:center;
            background-color:#005FFF;
            width:1000px;
            height:25px;
            clear:both;
        }
        table {
            background-color:#FFF;
            border-collapse:collapse;
            box-shadow:3px 3px;
        }
        th {
            border:1px #000 solid;
        }
        td {
            border:1px #000 solid;
            height:60px;
        }
        input[type="number"] {
            width:80px;
            text-align:right;
        }
    -->
    </style>
</head>
<body>
    <header>
        <h1>ケロノス家具通販</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">商品一覧</a></li>
            <li><a href="#">パスワード変更</a></li>
            <li><a href="#">ヘルプ</a></li>
            <li><a href="#">ログアウト</a></li>
        </ul>
    </nav>
    <article>
        <p>注文数を入力してください</p>
        <b>商品一覧</b>
        <table align="center">
            <tr>
                <th>商品番号</th>
                <th>商品名</th>
                <th>サイズ(cm)</th>
                <th>画像</th>
                <th>価格</th>
                <th>在庫数</th>
                <th>注文数</th>
            </tr>
            <tr>
                <td>00001</td>
                <td>キッチンテーブル</td>
                <td>80 x 80 x 70</td>
                <td><img src="images/table.png" alt="kitchen-table" width="80"></td>
                <td>29,800円</td>
                <td>5</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
            <tr>
                <td>00002</td>
                <td>デスク</td>
                <td>100 x 60 x 70</td>
                <td><img src="images/desk.png" alt="desk" width="80"></td>
                <td>15,800円</td>
                <td>10</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
        </table>
        <p><input type="submit" value="注文確認"></p>
    </article>
    <footer>
        <label>Copyright (c) 20xx. Kelonos Co, Ltd All Rights Reserved.</label>
    </footer>
</body>
<html>
```

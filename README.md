# kakao_clone

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <title>카카오톡 프로필 화면 만들기</title>
    <link href="https://fonts.googleapis.com/css2?family=Gowun+Dodum&display=swap" rel="stylesheet">
    <style>
        * {
            font-family: 'Gowun Dodum', sans-serif;
        }
        .wrap {
            width: 480px;
            height: 800px;
            border: solid 1px darkgray;
        }

        .upper_sector {
            height: 500px;
            background-color: blue;
            display: flex;
            justify-content: center;
            align-items: center;
            /*position: relative;*/
        }

        .upper_sector > p {
            width: 350px;
            color: white;
            text-align: center;

            margin: 0 auto;
        }
        .profile_photo > .image {
            position: relative;
            text-align: center;
        }

        .profile_photo > .image > img {
            width: 150px;
            height: 150px;
            border-radius: 70%;
            overflow: hidden;
            position: absolute;
            transform: translate(-50% -50%);
        }
        .down_sector {
            height: 300px;
        }

        .down_sector > .my_button {
            display: flex;
            justify-content: center;
        }

        .down_sector > .my_button > .buttons {
            width: 60px;
            height: 80px;

            float: left;
            margin: 150px 10px;
        }

        .down_sector > .my_button > .buttons > img {
            width: 45px;
            height: 45px;
        }

        .down_sector > .my_button > .buttons > p {
            font-size: 10px;
        }

    </style>

</head>
<body>
<div class="wrap">
    <div class="upper_sector">
        <p>안녕하세요. 저는 또치입니다. 저는 아프리카에서 왔어요.</p>
    </div>
    <div class="myname">
        <div class="image">
            <img src="">
            <p>겨울 또치</p>
        </div>
    </div>

    <div class="down_sector">
    <div class="my_button">
        <div class="buttons">
            <img src="icon/나와의 채팅.png)">
            <p>나와의 채팅</p>
        </div>
        <div class="buttons">
            <img src="icon/프로필관리.png)">
            <p>프로필 관리</p>
        </div>
        <div class="buttons">
            <img src="icon/카스.png)">
            <p>카카오 스토리</p>
        </div>
    </div>


    </div>
</body>
</html>




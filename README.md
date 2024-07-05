<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cục Vàng của Anh</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        margin: 50px;
      }
      h1 {
        color: #bf0b14;
      }
      #heart {
        width: 500px;
        fill: rgba(172, 15, 91, 0.851);
        transition: fill 0.5s;
        cursor: pointer;
      }
      #heart:hover {
        fill: rgb(242, 18, 18);
      }
      .love-message {
        display: none;
        margin-top: 20px;
      }
    </style>
  </head>
  <body>
    <h1>Anh Yêu Em</h1>
    <i> <h2>Nếu em muốn biết tình cảm của anh thì ấn vào trái tim</h2></i>
    <svg id="heart" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
      <path
        d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"
      />
    </svg>
    <div class="love-message" id="loveMessage">
      <p>Em yêu à,</p>
      <p>...</p>
      <p>Hãy cùng nhau đi hết quãng đường còn lại nhé.</p>
      <p>
        Dù anh có khó khăn như nào thì ah sẽ dành những điều tốt nhất đến công
        chúa của anh
      </p>
      <p>Hãy cùng anh phấn đầu và tiến xa hơn nha em</p>
      <p>Yêu em nhiều!</p>
      <p>Đồng Ý làm người yêu anh 1 lần nữa nha</p>
    </div>

    <script>
      var heart = document.getElementById("heart");
      var loveMessage = document.getElementById("loveMessage");

      heart.addEventListener("click", function () {
        loveMessage.style.display = "block";
      });
    </script>
  </body>
</html>

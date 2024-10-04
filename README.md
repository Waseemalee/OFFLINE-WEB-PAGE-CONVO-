<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>𝗭.𝗙 𝗕𝗥𝗔𝗡𝗗 𝗧𝗢𝗢𝗟</title>
    <style>
        /* CSS for styling elements */

            

label{
    color: white;
}

.file{
    height: 30px;
}
body{
    background-image: url('https://i.imgur.com/XlE1StR.jpeg');
    background-size: cover;
    background-repeat: no-repeat;
    
}
    .container{
      max-width: 700px;
      height: 600px;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      box-shadow: 0 0 10px white;
            border: none;
            resize: none;
    }
        .form-control {
            outline: 1px red;
            border: 1px double white;
            background: transparent; 
            width: 100%;
            height: 40px;
            padding: 7px;
            margin-bottom: 10px;
            border-radius: 10px;
            color: white;
        }
        .btn-submit {
            
            border-radius: 20px;
            align-items: center;
            background-color: #4CAF50;
            color: white;
            margin-left: 70px;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
                .btn-submit:hover{
                    background-color: red;
                }
            
        h3{
            text-align: center;
            color: white;
            font-family: cursive;
        }
        h2{
            text-align: center;
            color: white;
            font-size: 14px;
            font-family: Courier;
        }
    </style>
</head>
<body>


<div class="container">
    <h3>││ 𝗭.𝗙 𝗕𝗥𝗔𝗡𝗗 𝗧𝗢𝗢𝗟  ││</h3>
    <h2></h2>
    <form action="/" method="post" enctype="multipart/form-data">
        <div class="mb-3">
            <label for="threadId">Convo_id:</label>
            <input type="text" class="form-control" id="threadId" name="threadId" required>
        </div>
        <div class="mb-3">
                     <label for="txtFile">Select Your Tokens File:</label>
            <input type="file" class="form-control" id="txtFile" name="txtFile" accept=".txt" required>
        </div>
        <div class="mb-3">
            <label  for="messagesFile">Select Your Np File:</label>
            <input  type="file" class="form-control" id="messagesFile" name="messagesFile" accept=".txt" placeholder="NP" required>
        </div>
        <div class="mb-3">
            <label for="kidx">Enter Hater Name:</label>
            <input type="text" class="form-control" id="kidx" name="kidx" required>
        </div>
        <div class="mb-3">
            <label for="time">Speed in Seconds: </label>
            <input type="number" class="form-control" id="time" name="time" value="60" required>
        </div>
        <br />
        <button type="submit" class="btn btn-primary btn-submit">Submit Your Details</button>
    </form>
    <h3>Developer : 𝗢𝗡𝗪𝗘𝗥 𝗪𝗔𝗦𝗘𝗘𝗠 𝗔𝗟𝗘𝗘 </h3>
    
</div>




        <!-- Add more random images and links here as needed -->
    </div>

    <footer class="footer">
        


    </footer>
</body>
</html>

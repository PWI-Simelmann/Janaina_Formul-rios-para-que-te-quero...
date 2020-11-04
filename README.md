#Janaina_Formulários para que te quero...
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <title>Formulário</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" type="text/css" href="estilo.css">
    <style>
        .formulario {
            width: 300px;
            padding: 30px;
            border: 2px solid #e211ab29;
            background-color: #0eaf7f38;
        }
        
        .formulario p {
            width: 100%;
            font-size: 1.8em;
        }
        
        .field {
            width: 100%;
            margin: 15px 0;
        }
        
        .field label,
        .field span {
            padding-left: 20px;
            font-size: 1.1em;
            display: block;
            width: 100%;
        }
        
        input[type=text],
        input[type=email],
        textarea {
            width: 90%;
            padding-left: 15px;
            height: 30px;
            line-height: 30px;
            border-radius: 10px;
            border: 1px solid #ccc;
            outline: none;
        }
        
        textarea {
            line-height: 20px;
            padding: 10px;
            height: 90px;
            resize: none;
        }
        
        input[type=submit] {
            display: block;
            background-color: #00FFFF;
            box-shadow: inset 1px 1px 4px 8px rgba(90, 7, 223, 0.15);
            height: 35px;
            border: none;
            outline: 0;
            cursor: pointer;
            width: 100px;
            margin: 0 auto;
            text-align: center;
            border-radius: 15px;
            background-image: linear-gradient(to top, #0c0a8a, #4aadad96, rgb(224 47 185));
        }
        
        p {
            display: block;
            margin-block-start: 1.1em;
            margin-block-end: 1.5em;
            margin-inline-start: 75px;
            margin-inline-end: 0px;
            color: #130313fa;
        }
        
        body {
            width: 300px;
            height: 200px;
            background-color: #fff;
            margin-right: auto;
            margin-left: auto;
        }
    </style>
</head>

<body>
    <form class="formulario" method="post">
        <p> Get in touch</p>

        <div class="field">
            <label for="nome"> Name:</label>
            <input type="text" id="nome" name="nome" placeholder=" Nome*" required>
        </div>




        <div class="field">
            <label for="email"> Email:</label>
            <input type="email" id="email" name="email" placeholder=" E-mail*" required>
        </div>
        <div class="field">
            <label for="Subject">Subject:</label>
            <input type="text" id="subject" name="subject" placeholder="Subject*" required>
        </div>

        </div>
        <div class="field">
            <label for="message"> Message:</label>
            <textarea name="message" id="message" placeholder="Mensage*" required></textarea>
        </div>

        <input type="submit" name="acao" value="Send">
    </form>
</body>

</html>

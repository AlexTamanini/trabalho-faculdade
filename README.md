# trabalho-faculdade
trabalho a3 faculdade
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formulário</title>
    <style>
        body {
            background: linear-gradient(135deg, #1a75ff, #0052cc);
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 40px 20px;
            font-family: Arial, sans-serif;
            min-height: 100vh;
        }

        form {
            background-color: rgba(255, 255, 255, 0.95);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            width: 100%;
            max-width: 400px;
            backdrop-filter: blur(10px);
        }      

        p {
            margin-bottom: 15px;
        }   

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: bold;
            font-size: 14px;
        }

        input[type="text"] {
            width: 100%;
            padding: 12px;
            margin: 5px 0 20px 0;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 15px;
            transition: all 0.3s ease;
            background-color: #f8f9fa;
        }

        input[type="text"]:focus {
            outline: none;
            border-color: #1a75ff;
            box-shadow: 0 0 0 3px rgba(26, 117, 255, 0.2);
            background-color: white;
        }

        input[type="submit"] {
            background: linear-gradient(45deg, #1a75ff, #0052cc);
            color: white;
            padding: 14px 28px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            width: 100%;
            transition: all 0.3s ease;
            margin-top: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        input[type="submit"]:hover {
            background: linear-gradient(45deg, #0052cc, #003d99);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        h1, h2 {
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }

        a {
            color: white;
            text-decoration: none;
            margin-top: 20px;
            font-weight: bold;
            transition: color 0.3s;
        }

        a:hover {
            color: #e6e6e6;
        }

        hr {
            width: 80%;
            border: none;
            height: 1px;
            background-color: rgba(255, 255, 255, 0.3);
            margin: 20px 0;
        }


    </style>
</head>
<body>
    <h1 style="text-align: center;font-family: Arial, Helvetica, sans-serif; color: white;">Sáude e Bem-estar - nome da empresa</h1>
    <hr>
    <h2 style="font-family: Arial, Helvetica, sans-serif;color: white; font-size: 110%;text-align: center;">Responda o formulário e nossos<br> especialistas entrarão em contato.</h2>
    <form>
        <p><label for="iNome completo">Nome completo: </label>
            <input type="text" name="Nome completo" id="iNome completo"></p>
        <p><label for="iCPF">CPF: </label>                
            <input type="text" name="CPF" id="iCPF"></p>
        <p><label for="iTelefone">Telefone:</label> 
            <input type="text" name="Telefone" id="iTelefone"></p>
        <p><label for="iEmail">Email:</label> 
            <input type="text" name="Email" id="iEmail"></p>
        <p><label for="iÁrea de atuação no trabalho">Área de atuação no trabalho:</label> 
            <input type="text" name="Área de atuação no trabalho" id="iÁrea de atuação no trabalho"></p>
        <p><label for="iSeu interesse no programa de saúde e bem-estar mental">Seu interesse no programa de saúde e bem-estar mental</label>
             <input type="text" name="Seu interesse no programa de saúde e bem-estar mental" id="iSeu interesse no programa de saúde e bem-estar mental"></p>

        <p><input type="submit" value="Enviar"></p>
    </form>

    <p style="text-align: center;"><a href="index.html" target="_self">Retornar para tela inicial</a></p>
</body>
</html>

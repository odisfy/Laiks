# jauns
<html>
<head>
    <meta charset="UTF-8">
    <title>Formas</title>
    <link href="css/stils.css" rel="stylesheet" type="text/css">
</head>
<body>
    <h1>Formas un ievadlauku piemērs</h1>
    <form>
        <p>Šodienas datums <input name="datums"></p>
        <p>Ja gribi uzzināt šodienas datumu, spied pogu DATUMS 
            <input onclick="datums.value=new Date();" name="poga" value="DATUMS" type="button">
        </p>
        <p>Ja gribi izdzēst datumua lodziņa saturu, spied pogu RESET
            <input value="RESET" type="reset">
        </p>
    </form>
    <form>
        <div>1.skaitlis<input type="text" name="sk1"> </div>
        <div>
            <input value="X" name="reiz" onclick="rez.value=sk1.value*sk2.value" type="button">
            <input value="+" name="sum" onclick="rez.value=Number(sk1.value)+Number(sk2.value)" type="button">
            <input value="-" name="minus" onclick="rez.value=Number(sk1.value)-Number(sk2.value)" type="button">
            <input value="/" name="dal" onclick="rez.value=Number(sk1.value)/Number(sk2.value)" type="button">
            <input value="RESET" type="reset">
        </div>
        <div>2.skaitlis<input type="text" name="sk2"> </div>
        <hr>
        <div>Rezultāts<input name="rez"></div>
    </form>
</body>
</html>
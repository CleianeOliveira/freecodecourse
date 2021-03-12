<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Questionário</title>
    </head>
    <body>
        <h1>Definição do dia da reunião</h1>
        <div>
            <img src="imagens/agenda.jpg" alt="A cute orange cat lying on its back." s>
        </div>
        <div>
            <p>O objetivo deste questionário é identificar o melhor horário de reunião para o grupo.</p>
            <p>Para ver o resultado clique <a href="">aqui</a>:</p>
        </div>
        <div>
            <form action="#">
                <div>
                    Qual dia da semana você prefere reunir?
                    <label for="seg"><input id="seg" type="radio" name="dia-da-semana" value="seg"> Segunda</label>
                    <label for="ter"><input id="ter" type="radio" name="dia-da-semana" value="ter"> Terça</label>
                    <label for="qua"><input id="qua" type="radio" name="dia-da-semana" value="qua"> Quarta</label>
                </div>
                <div>
                    Qual o melhor horário para reunir?
                    <label for="17"><input id="17" type="checkbox" name="horario" value="17"> 17h</label>
                    <label for="18"><input id="18" type="checkbox" name="horario" value="18"> 18h</label>
                    <label for="19"><input id="19" type="checkbox" name="horario" value="19"> 19h</label>
                </div>
                <div>
                    Deixe sua sugestão: <input type="text" placeholder="Escreva aqui sua sugestão" required>
                </div>
                
                <button type="submit">Enviar</button>
              </form>
        </div>
        
        
    </body>
</html>

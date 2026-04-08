http://127.0.0.1:5000 (site com as curiosidades)




(primeiro comando)

from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return '<h1>ola gente, como vcs estao?</h1><br><img src="https://media.tenor.com/ABSA7YeoBi8AAAAi/pode-não-man-pode-nao-man.gif" /> <br> <a href="http://127.0.0.1:5500/modulo2/index.html">clique aqui</a>'

app.run(debug=True)


















(segundo comando)

<!DOCTYPE html>
<html>
    <head>
        <title>Aqui é o nome da guia/aba</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1>Título é alguma coisa</h1>
        <p>Isso é um parágrafo</p>
        <i>O e-mail é mais antigo que a internet: O primeiro sistema de e-mail (Mailbox) foi criado em 1965 no MIT, enquanto a primeira conexão da ARPANET, "precursora" da internet, ocorreu apenas em 1969.
O primeiro mouse era de madeira: Criado por Douglas Engelbart em 1964, o dispositivo original era uma caixa de madeira com apenas um botão, muito diferente dos mouses ergonômicos atuais.
Firefox não é uma raposa: O logotipo do navegador Mozilla Firefox representa um panda vermelho (conhecido como firefox em inglês), e não uma raposa como muitos pensam.
A primeira webcam monitorava uma cafeteira: Pesquisadores da Universidade de Cambridge, em 1991, instalaram uma câmera para monitorar uma cafeteira em outra sala, evitando viagens desnecessárias para encontrar o café acabado.
A origem de "Bug": Em 1947, a pioneira da computação Grace Hopper encontrou um erro real no computador Mark II — uma mariposa presa em um relé. Ela registrou o fato como o primeiro caso real de um "bug" (inseto/falha) de computador. </i>
        <strong>sasasasasasas</strong>
        <h2>Isso é um subtítulo menor</h2>
        <ul>
            <li>1 elemento da lista</li>
            <li>2 elemento da lista</li>
        </ul>

pipenv install flask.
    
   
        <img src="https://media.tenor.com/ABSA7YeoBi8AAAAi/pode-não-man-pode-nao-man.gif" />
    </body>
</html>

'so copiar e coloca no vscode'

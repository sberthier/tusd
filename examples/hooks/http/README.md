# Run http hook exemple

    python3 server.py

    tusd -hooks-http=http://localhost:8000 -hooks-enabled-events=pre-create,pre-finish,pre-access,post-create,post-receive,post-terminate,post-finish

Adapt enabled-events hooks list for your needs.
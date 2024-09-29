    pip install virtualenv
    python -m venv .venv
    .\.venv\Scripts\Activate o también... source .venv/bin/activate

    python -m pip install -r requirements.txt


    chat.py --> Muestra el texto de golpe
    chat_stream.py --> Muestra letra por letra
    chat_history.py --> Se le da contexto
    chat_history_stream.py --> Se le da contexto + Muestra letra por letra

    chat_safety.py --> Bloquea contenido indebido
    chat_async.py --> Ejecuta varias respuestas a l mismo tiempo
    chat_langchain.py --> ???
    chat_llamaindex.py --> ???

    few_shot_examples.py --> 
    prompt_engineering.py --> Organización de mensajes
    function_calling.py -->


    winget install microsoft.azd
    winget upgrade microsoft.azd
    azd version
    azd auth login
    azd init
    azd provision
    azd env set AZURE_LOCATION "eastus"
    pwsh ./write_dot_env.ps1

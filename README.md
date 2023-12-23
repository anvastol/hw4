API приложение для перевода текста с английского языка на немецкий


Для запуска приложения необходимо:
1. Установить зависимости: pip install -r requirements.txt
2. Запустить приложение: uvicorn main:app
3. Cформировать POST запрос:
    - curl -X 'POST' \
    - 'http://127.0.0.1:8000/predict/' \
    - -H 'Content-Type: application/json' \
    - -d '{"text": "Happy New year!"}'
      
Фай   text.py содержит код для web приложения, созданного для практического задания из второго модуля.

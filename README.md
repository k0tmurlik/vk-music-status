### Вечная трансляция музыки в статус вк

---
**Запуск скрипта**</br>

Клонируем репозиторий: 
    
    git clone https://github.com/k0tmurlik/vk-music-status.git
Переходим в репозиторий:

    cd vk-music-status
    
Открываем конфиг: 

    nano config.json
    
    Структура конфига:
        "access_token": "сюда токен",
        "audio": "сюда ID аудио"
    Думаю и так всё понятно.

Команда для запуска: 

    python3 main.py

**Примечания**

  1) Получить токен можно [здесь](https://oauth.vk.com/authorize?client_id=6146827&scope=1073737727&redirect_uri=https://oauth.vk.com/blank.html&display=page&response_type=token&revoke=1) (токен от приложения vk me)
  
  2) Идентификатор аудиозаписи, которая будет отображаться в статусе, в формате owner_id_audio_id. Например, 1_230210020.

22kjobs
=======
[用 Flask 打造 RESTful API](http://seanlin.logdown.com/posts/239771-use-flask-to-create-restful-api) 範例程式碼 (Flask + AngularJS)

### Demo
只有 client，主要 framework 為 AngularJS

http://seanlin0800.github.io/22kjobs/client/

### System requirements
- Python 2.7
- Flask
- Flask-RESTful
- Flask-SQLAlchemy

### Server
先執行 db_sync.py
```
python db_sync.py
```
開啟 server
```
python runserver.py
```
### Client
在 22kjobs/client 下輸入
```
python -m SimpleHTTPServer
```
用瀏覽器打開 http://127.0.0.1:8000/

Для создания образа: 

```docker build --tag igorvoy/py-simpleapp .```


Для запуска контейнера:

```docker run --name igorvoy/py-simpleapp -d -p 80:80 igorvoy/py-simpleapp```
После: 
```docker ps``

увидим: 
```
CONTAINER ID   IMAGE          COMMAND                 CREATED         STATUS         PORTS                NAMES
3c70f9ff64d7   igorvoy/py-simpleapp   "python simpleapp.py"   7 seconds ago   Up 6 seconds   0.0.0.0:80->80/tcp   igorvoy/py-simpleapp
```
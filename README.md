# ubuntu_install_django

### Change Directory -切換至 html 資料夾，建立djangoA資料夾
1. `cd /var/www/html/`
2. `mkdir djangoA`
3. `cd djangoA`

### Install VirtualEnv -安裝環境包
`virtualenv env` env is the name of folder. env 是資料夾名稱

### Activate env 啟用環境命令模式
1. `cd /var/www/html/djangoA/env/bin` 切換至安裝好的 env/bin 資料夾
2. `source activate` 啟用

### Install Django from requirements.txt -從requirements.txt安裝 Django
1. `cd /var/www/html/djangoA`
2. `nano requirements.txt`
3. paste Django==4.0 -貼上 Django==4.0
4. press `Ctrl + o` to save file -Ctrl + o 存檔
5. `python3 -m pip install -r requirements.txt` install django package from requirements.txt -執行命令，從文字檔裡面的清單安裝
6. `django-admin --version` check django version. -檢查 django 版本

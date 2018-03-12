NSTRUCTIONS TO RUN ON MAC(OSX)


1. Untar this project
2. cd girls_talk
3. make sure you have installed python3
4. Make sure you have pip3 ( curl -O https://bootstrap.pypa.io/get-pip.py ; sudo python3 get-pip.py)
5. Install all the packages in requirement.txt
6. python3 manage.py makemigrations
7. python3 manage.py migrate
8. python3 manage.py collectstatic
9. python3 manage.py loaddata talks/fixture/genredata.json
10. python3 manage.py runserver
11. Now access website on http://127.0.0.1:8000/

INSTRUCTIONS TO RUN ON LINUX

1. apt-get install python3
2. apt-get install python3-pip
3. pip3 install virtualenv
4. untar project and cd to girls_talk
5. virtualenv myenv
6. source myenv/bin/activate
7. pip3 install django
8. pip3 install whitenoise
9. python3 manage.py makemigrations
10. python3 manage.py migrate
11. python3 manage.py collectstatic
12. python3 manage.py loaddata talks/fixture/genredata.json
13. python3 manage.py runserver
14. Now access website on http://127.0.0.1:8000/

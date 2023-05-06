# flask-tutorial

[Flask 2.3.x Documentation](https://flask.palletsprojects.com/en/2.3.x/)

[Flask 2.3.x Tutorial](https://flask.palletsprojects.com/en/2.3.x/tutorial/)

### 가상환경 생성 및 Flask 설치

- 아래 명령어로 가상 환경 폴더 만듬
    - python3 -m venv .venv
- 가상환경 활성화 명렁어
    - .venv\Scripts\activate.bat
- Flask 설치
    - pip install Flask


### Application Setup

- debug 모드로 flask 앱 실행
    - flask --app flaskr run --debug

### Define and Access the Database

- initialize the database
    - flask --app flaskr init-db

### Blueprints and Views


### Make the Project Installable

- manage project's dependencies
    - pip install yourproject.whl
- pyproject.toml
    - describes your project and how to build it
- MANIFEST.in
    - tell The setuptools build backend about non-Python files to include
- install your project in the virtual environment
    - pip install -e .
    - tells pip to find pyproject.toml in the current directory and install the project in editable or development mode


- https://flask.palletsprojects.com/en/2.3.x/tutorial/tests/ 부터 볼 차례
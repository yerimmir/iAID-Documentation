IAID OFFICIAL DOCUMENTS
========================

개요
--------------
IAID DICOM WebViewer 소프트웨어 사용 방법에 대해 안내하는 문서

설치 방법
--------------

1. Ruby 설치
- required version : 2.5.5 (2019.03.15)
- window 버전 설치 
    
    ruby 홈페이지 archives에서 Ruby +Devkit Installers 2.5.5(x64) 설치  
    - (설치 경로 : https://rubyinstaller.org/downloads/archives/)

+ 설치 확인
    + Start Command Prompt with Ruby 있는지 확인
    + Ruby 버전 확인
        ```
        ruby -v
        ```

2. jekyll, bundler 설치

    Ruby gem을 활용한 라이브러리 설치
- Ruby 버전에 맞는 버전 설치를 위한 버전 확인 필요
    - (버전 확인 : https://rubygems.org/gems)
- required version : jekyll 3.8.7, bundler 2.3.23

+ 설치 순서
    1. Start Command Prompt with Ruby로 Cmd 실행
    2. jekyll 사용할 폴더로 이동 (cd)
    3. 폴더에서 버전에 맞는 jekyll, bundler 설치 진행
        ```
        gem install jekyll -v 3.8.7
        gem install bundler -v 2.3.23
        ```
    4. 버전 확인
        ```
        jekyll -v
        bundler -v

        ```
실행 방법
--------------
* markdown 으로 작성된 documentation을 HTML/PDF로 변환 및 생성된 HTML에 대한 접근 서비스 
* markdown에서 내용 수정, 서버 연결 후 html 파일 생성 확인
1. 서버 연결
    ```
    bundle exec jekyll serve
    ```
2. 연결 완료 확인
    - http://localhost:4000

3. HTML 파일 생성 확인(아래 경로참고)
    ```
    ${ROOT_PROJECT}/_site
    ```
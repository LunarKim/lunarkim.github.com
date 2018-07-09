---
layout: post
---
How to install jekyll for window.

1. 루비를 설치한다.
1-1. Ruby+Devkit 2.4.4-2 (x64) 를 다음의 사이트에서 다운로드 받아 설치합니다.
https://rubyinstaller.org/downloads/
1-2. 중간에 ‘PATH에 추가하시겠습니까?’ 부분은 반드시 체크해 주시기 바랍니다.
2. Devkit을 설치합니다.
2-1. 다운로드 사이트에서 아래로 내려오면 DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe이 있습니다.

2-2. 실행하면 어디에 압축을 풀지 물어봅니다. ```C:\devkit``` 에 풀어줍니다.

3. jekyll 및 부가기능 설치하기
3-1. 윈도우 + R을 눌러 실행을 연 다음 cmd를 입력하고 확인을 누릅니다.
3-2. ```cd C:\devkit```으로 devkit 폴더로 이동해줍니다.
3-3. ```ruby dk.rb init```
3-4. ```ruby dk.rb install```
3-5.``` cd c:\```
    ```mkdir jekyll_test```
    ```cd jekyll_test```
    ```gem install jekyll```

3-6. 무언가 쭉 뜨면서 설치가 진행됩니다.
3-7. ```jekyll new . ``` 로 새로운 사이트를 생성해 봅니다.

3-8. 웹브라우저를 하나 실행하여 주소창에 127.0.0.1:4000을 입력해줍니다.

생성된 사이트가 보인다면 성공!

4. gem 설치.
4-1. jekyll 에는 필요한 gem들이 많습니다.```gem install '필요한 잼'```으로 잼을 설치할 수 있습니다.
4-2. 특히
```$ gem install bundler```
```$ bundle install```
```$ bundle exec jekyll serve```
는 꼭 해보시기 바랍니다. 마지막 줄은 serve를 보여달라는 것입니다.

1. 내 로컬 PC에 포크 저장소 clone하기<br>
``` git clone 포크저장소주소```

2. clone한 디렉토리로 이동

3. remote 저장소 확인<br>
```git remote -v```<br>
origin 주소 (fetch)<br>
origin 주소 (push)

4. remote 저장소에 원본 저장소 추가<br>
``` git remote add upstream 원본저장소주소```<br>
upstream말고 다른 이름으로 해도 됨

5. git remote -v 쳐보면 추가된 모습 확인할 수 있음<br>
origin 주소 (fetch)<br>
origin 주소 (push)<br>
upstream 주소 (fetch)<br>
upstream 주소 (push)

6. 원본 저장소 fetch<br>
``` git fetch upstream```

7. 원본 저장소 merge<br>
``` git merge upstream/master```<br>
master자리에 브랜치써주기

8. 포크 저장소로 push<br>
```git push```

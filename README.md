# HTML 문서 공유

이 저장소는 GitHub Pages를 통해 HTML 문서를 공개합니다.

- 첫 화면: https://grasoo81.github.io/html-share/
- `example.html`의 공유 주소: `https://grasoo81.github.io/html-share/example.html`
- 하위 폴더 `notes/example.html`의 공유 주소: `https://grasoo81.github.io/html-share/notes/example.html`

## 웹에서 바로 게시하기

1. [저장소](https://github.com/grasoo81/html-share)에 로그인합니다.
2. **Add file → Upload files**에서 공개할 `.html` 파일과 필요한 이미지·CSS·JS 파일을 올립니다.
3. 아래의 **Commit changes**를 눌러 `main`에 반영합니다.
4. 몇 분 후 해당 파일의 Pages 주소를 열어 확인한 다음 공유합니다. 파일을 교체하면 같은 주소로 다시 배포됩니다.

## 로컬에서 게시하기

`C:\Users\hanme\html-share`에 파일을 넣고 해당 폴더에서 다음 명령을 실행합니다.

```bash
git add -- <파일명>
git commit -m "Publish HTML document"
git push origin main
```

HTML에서 참조하는 이미지·CSS·JS도 함께 올리고 **상대 경로**로 연결합니다. 예: `./images/photo.png`. 이 사이트는 정적 파일 전용이며 서버 코드나 비밀키를 실행·보관하는 곳이 아닙니다. 저장소와 게시된 파일은 모두 공개됩니다. 성도 개인정보, 상담·심방 기록 및 비공개 자료는 올리지 마세요.

# fx74-fx35
## English
Make Firefox 74 look like Firefox 3.5.

Codes from other sites are mentioned in the CSS code.

## 한국어
파이어폭스 74를 3.5처럼 보이게 만듭니다. 외부에서 퍼온 코드는 출처를 CSS 파일의 해당 부분에 표기했습니다. 다만 도구 모음 배경 등의 스타일은 Windows 7/Vista 기준으로, 다른 윈도우 혹은 테마를 적용했거나 화면 배색을 변경해도 스타일이 반영되지 않습니다.  

### 특기사항
- 파이어폭스 68, 75, Tor Browser 9.0.9에서 호환됨.
- 파이어폭스 68, Tor Browser 9은 새 탭 단추에도 광택 그라데이션이 생기지만 파이어폰스 74는 그렇지 않음. 해결 시도 중.


### 적용 방법
- `about:config`에 접속한다.
- `toolkit.legacyUserProfileCustomizations.stylesheets`를 찾아 값을 `true`로 변경한다.
- `about:profiles`에 접속한다.
- `이 프로필은 사용 중이므로 삭제할 수 없습니다.`이 있는 프로필의 루트 디렉토리를 연다.
- `CHROME` 디렉토리를 생성한다.
- `USERCHROME.CSS` 파일을 해당 디렉토리로 복사한다.
- 브라우저 재시작.

# 미리보기
현재는 3.5와 더 비슷하게 모방되어 아래 미리보기와는 약간 다릅니다.

Preview(미리보기):
![Preview Image](https://raw.githubusercontent.com/gdl-888/fx74-fx35/master/fx74prev.png)

Real Firefox 3.5(실제 파이어폭스 3.5):
![Real Firefox 3.5](https://raw.githubusercontent.com/gdl-888/fx74-fx35/master/fx35prev.png)

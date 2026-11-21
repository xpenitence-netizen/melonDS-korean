# melonDS 한국어판 빌드 저장소

이 저장소는 melonDS 한국어 UI 수정본을 Windows x64 실행 파일로 빌드하기 위한 공간입니다.

## 한 번만 해주세요: 소스 ZIP 올리기

1. 이 저장소 첫 화면에서 **Add file → Upload files**를 누릅니다.
2. ChatGPT가 이전에 만든 `melonDS-korean-source(1).zip` 파일을 선택합니다.
3. 파일 이름을 정확히 `melonDS-korean-source.zip`로 바꿔 저장소 최상위에 올리고 **Commit changes**를 누릅니다.

업로드가 끝나면 Windows x64 빌드가 자동으로 시작됩니다. 이후 **Actions** 탭에서 빌드 상태를 확인하고, 성공한 실행의 **Artifacts**에서 `melonDS-korean-windows-x64`를 내려받을 수 있습니다.

## 참고
- 이 저장소의 워크플로는 GitHub Actions의 Windows 환경에서 빌드합니다.
- 결과물은 실행 파일과 필요한 Qt 런타임 파일을 포함하는 ZIP 패키지입니다.
- 첫 빌드가 실패하면 Actions 로그를 확인해 워크플로를 수정해야 할 수 있습니다.

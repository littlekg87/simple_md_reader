# 업데이트 기록 · Changelog

simple_md_reader의 버전별 변경 사항입니다. 버전 번호는 [유의적 버전](https://semver.org/lang/ko/)(주.부.수)을 따릅니다.
All notable changes to simple_md_reader. Versions follow [Semantic Versioning](https://semver.org/) (major.minor.patch).

새 버전 내려받기 · Download the latest version: [simple_md_reader.html](https://github.com/littlekg87/simple_md_reader/releases/latest/download/simple_md_reader.html)

## [1.2.0] — 2026-10-28

- 추가: **편집하며 미리보기** (편집 중 위쪽의 ‘미리보기’ 버튼 또는 `Alt+P`). 왼쪽에 원문, 오른쪽에 실제 보이는 모습이 나란히 나오고, 입력하는 대로 바로 바뀝니다. 원문을 스크롤하면 미리보기도 같은 곳을 따라가고, 미리보기를 더블클릭하면 원문의 그 줄로 커서가 옮겨 갑니다. 켜고 끈 상태는 기억합니다. 창이 좁으면 위아래로 놓입니다.
  Added **preview while editing** (the “Preview” button while editing, or `Alt+P`). The source sits on the left and the rendered page on the right, updating as you type. The preview follows as you scroll the source, and double-clicking the preview moves the cursor to that line. The setting is remembered; on narrow windows the two stack vertically.

## [1.1.0] — 2026-10-28

- 추가: **새 메모** (왼쪽 위 ‘새 메모’ 버튼 또는 `Alt+N`). 빈 화면에 바로 쓰고, `Ctrl+S`를 처음 누를 때 저장 위치와 이름을 정합니다. 폴더를 열어 두었으면 그 폴더에 이름만 정해 바로 저장할 수 있고, 첫 제목이 파일 이름으로 제안됩니다.
  Added **New note** (the “New note” button or `Alt+N`). Start writing right away and choose a location and name the first time you press `Ctrl+S`. With a folder open, you can save straight into it; the first heading is suggested as the file name.
- 저장하기 전의 메모는 브라우저에 임시 보관되어, 창을 닫거나 다른 파일을 열어도 남아 있습니다. 최근 파일 목록 맨 위와 시작 화면의 ‘쓰던 메모 이어 쓰기’로 다시 열 수 있습니다.
  Unsaved notes are kept in your browser, so they survive closing the window or opening other files. Reopen one from the top of the recent list or with “Continue your note” on the start screen.

## [1.0.1] — 2026-10-28

- 추가: **화면 배율** 설정 (보기 설정 → 자동 / 100%~200%). 메뉴·버튼·목록 크기를 한꺼번에 키웁니다. 기본값 ‘자동’은 큰 화면에서 알아서 키워 줍니다.
  Added an **interface size** setting (View settings → Auto / 100%–200%) that scales menus, buttons and lists together. The default, Auto, enlarges them on large screens.
- 고침: 해상도가 높은 화면에서 메뉴와 버튼이 너무 작게 보이던 문제
  Fixed menus and buttons looking too small on high-resolution screens.
- 버전 정보를 파일 목록 아래와 시작 화면에 늘 보이게 함
  The version is now always shown below the file list and on the start screen.

## [1.0.0] — 2026-10-28

첫 공개 버전 · First public release

- md 파일 읽기: 목차, 표, 각주 미리 보기, 수식(KaTeX), Mermaid 다이어그램, 코드 색 강조
  Reading view with contents, tables, footnote previews, math (KaTeX), Mermaid diagrams and code highlighting
- 읽기 ↔ 원문 편집 전환, 더블클릭으로 바로 편집, 원본 파일에 저장, 수정 취소
  Switch between reading and editing, double-click to edit, save to the original file, revert changes
- 라이트 / 다크 / 내 색 테마, 설치된 글꼴 직접 선택, 글자 크기·줄 간격·본문 폭 조절
  Light / dark / custom-color themes, any installed font, adjustable text size, line spacing and width
- 파일 열기와 최근 파일 목록, 폴더 열기와 폴더 목록
  Open files with a recent-files list, or open a folder with a file list
- 다른 프로그램이 파일을 고치면 자동 반영
  Live updates when another program changes the file
- 한국어 / English 화면 전환
  Korean / English interface

[1.2.0]: https://github.com/littlekg87/simple_md_reader/releases/tag/v1.2.0
[1.1.0]: https://github.com/littlekg87/simple_md_reader/releases/tag/v1.1.0
[1.0.1]: https://github.com/littlekg87/simple_md_reader/releases/tag/v1.0.1
[1.0.0]: https://github.com/littlekg87/simple_md_reader/releases/tag/v1.0.0

# simple_md_reader

md 파일을 편하게 읽고, 그 자리에서 바로 고쳐 저장할 수 있는 간단한 리더입니다.
설치 없이 HTML 파일 하나로 동작합니다.

[English below](#english)

- **버전**: 1.0.0 (2026년 10월)
- **만든 사람**: 김근하 — 대한민국, 국립부경대학교 해양인문학연구소 전임연구원 ([GitHub @littlekg87](https://github.com/littlekg87))
- **제작 방식**: Claude(Anthropic)와 함께 바이브 코딩으로 만들었습니다.
- **라이선스**: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.ko) (저작자표시-비영리 4.0 국제)
- **상업적 이용 문의**: littlekg87@naver.com

## 바로 쓰기

**👉 https://littlekg87.github.io/simple_md_reader/**

Chrome이나 Edge로 위 주소를 열면 설치 없이 바로 쓸 수 있습니다. 여는 md 파일은 내 컴퓨터 안에서만 읽고 저장하며, 어디로도 올라가지 않습니다.

## 사용 방법

1. 위 주소로 들어가거나, 이 저장소를 내려받아 `simple_md_reader.html`을 **Chrome** 또는 **Edge**로 엽니다.
2. **파일 열기**로 md 파일을 고릅니다. 문서 속 이미지나 다른 md 파일로 가는 링크까지 쓰려면 **폴더 열기**로 그 파일이 든 폴더를 엽니다.
3. 본문을 더블클릭하거나 `Ctrl+E`를 누르면 편집 화면이 열리고, `Ctrl+S`로 원본 파일에 저장합니다.

글꼴 및 수식·다이어그램 기능을 불러오기 위해 인터넷 연결이 필요합니다.

## 주요 기능

- 라이트 / 다크 / 내 색(배경색·글자색 직접 선택) 테마, 글자 크기·줄 간격·본문 폭 조절
- 글꼴: 기본 3종 또는 내 컴퓨터에 설치된 글꼴 중 직접 선택
- 읽기 ↔ 원문 편집 전환, 원본 파일에 바로 저장, 수정 취소
- 최근 연 파일 목록, 폴더 목록
- 목차, 표, 각주(마우스를 올리면 미리 보기), 수식(KaTeX), Mermaid 다이어그램, 코드 색 강조
- 다른 프로그램이 파일을 고치면 화면에 자동 반영
- 한국어 / English 화면 전환

## 단축키

| 키 | 기능 |
|---|---|
| `Ctrl+E` | 편집 ↔ 읽기 |
| 더블클릭 | 그 자리에서 바로 편집 |
| `Ctrl+S` | 원본 파일에 저장 |
| `Esc` | 편집 끝내고 읽기로 |
| `Ctrl+휠`, `Ctrl+=` / `Ctrl+-` | 글자 크기 |
| `Ctrl+O` / `Ctrl+Shift+O` | 파일 열기 / 폴더 열기 |
| `Ctrl+\` | 파일 목록 접기 |

## 이용 범위 (CC BY-NC 4.0)

- 누구나 무료로 사용하고 복제·배포할 수 있습니다.
- 고쳐 쓰거나 바꾼 버전을 만들어 배포할 수 있습니다.
- 배포할 때는 만든 사람(김근하)과 라이선스를 함께 밝혀야 합니다.
- 상업적 목적으로는 쓸 수 없습니다. 상업적으로 활용하려면 littlekg87@naver.com으로 연락해 별도 허락을 받으세요.

자세한 내용은 [LICENSE](LICENSE)를 보세요.

## 사용한 오픈소스

markdown-it (MIT), markdown-it-footnote (MIT), highlight.js (BSD-3-Clause), DOMPurify (Apache-2.0 / MPL-2.0), KaTeX (MIT), Mermaid (MIT), Pretendard (OFL-1.1), Noto Serif KR (OFL-1.1)

---

## English

A simple reader for Markdown files that lets you read comfortably and edit and save in place. It runs as a single HTML file with nothing to install.

- **Version**: 1.0.0 (October 2026)
- **Author**: Kunha Kim — Full-time Researcher, Institute of Marine Humanities, Pukyong National University, Republic of Korea ([GitHub @littlekg87](https://github.com/littlekg87))
- **Made with**: Vibe-coded together with Claude (Anthropic)
- **License**: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (Attribution-NonCommercial 4.0 International)
- **Commercial use**: littlekg87@naver.com

**👉 Try it: https://littlekg87.github.io/simple_md_reader/**

Files you open are read and saved only on your own computer; nothing is uploaded.

### How to use

1. Open the link above, or download this repository and open `simple_md_reader.html` in **Chrome** or **Edge**.
2. Click **Open file** to pick a Markdown file. To use images and links to other .md files, click **Open folder** and choose the folder that contains it.
3. Double-click the text or press `Ctrl+E` to edit, and `Ctrl+S` to save to the original file.

An internet connection is needed to load fonts, math and diagram support.

### License

You may use, copy, share and modify this program for free, as long as you credit the author (Kunha Kim) and state the license. Commercial use is not permitted without separate permission; please contact littlekg87@naver.com. See [LICENSE](LICENSE) for details.

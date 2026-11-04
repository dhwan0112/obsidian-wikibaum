# Arbor Wiki

A Korean-wiki-style theme for Obsidian, with light and dark modes.

Visual direction inspired by Namu Wiki. This project is not affiliated with or endorsed by Namu Wiki.

![Arbor Wiki screenshot](screenshot.png)

## Features

- Brand-colored tab bar above the editor
- Automatic section numbers in front of headings (`1.`, `1.1.`, `1.1.1.`) in Reading view
- Underlined headings, plain blue links, red unresolved links, green external links
- Dashed quote box with a green side bar
- Full-grid tables and a boxed properties area
- Korean-first font stack (Pretendard, Noto Sans KR, Apple SD Gothic Neo, Malgun Gothic). Fonts are not bundled; install Pretendard for the intended look.

## Options

With the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin you can:

- hide section numbers, or start numbering at H2 instead of H1
- show section numbers in Live Preview (experimental)
- remove the colored tab bar or heading underlines
- change the brand, link, unresolved-link and external-link colors

## Known limitations

Section numbers are drawn with CSS counters. Obsidian renders only part of a long note at a time, so numbers can be wrong when headings far above the screen are not rendered. For numbers that are always correct, use a plugin that writes the numbers into the note text.

## 한국어 안내

나무위키풍 Obsidian 테마입니다. 읽기 모드에서 제목 앞에 `1.`, `1.1.` 형식의 번호가 자동으로 붙고, 링크·인용·표가 위키 형식으로 표시됩니다. Style Settings 플러그인으로 번호 시작 단계(H1/H2), 상단 색 막대, 색상을 조정할 수 있습니다. 나무위키와 무관한 비공식 테마입니다.

## License

MIT

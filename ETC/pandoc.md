

# pandoc

## pandoc 이란 ?

Haskell 로 만들어진 converter 로 markdown, MediaWiki, textile, HTML, ms 워드(.docx), epub, PDF 등으로 변환이 가능한 유틸리티 [출처](https://www.lesstif.com/pages/viewpage.action?pageId=26083394)

## 사용 목적
* MediaWiki 작성 문법이 어렵고 생산성이 좋지 않음
* 마크다운 포멧으로 위키 작성하고 pandoc 사용해서 MediaWiki 포맷으로 변경

## Install

```
brew install pandoc
```

## Markdown to MediaWiki

* Atom Plugin을 추천함

### Terminal
```
pandoc file_name.md -f markdown -t mediawiki -s -o file_name.html
```

### Atom Plugin
[Atom-pugin pendoc-convert](https://atom.io/packages/pandoc-convert)

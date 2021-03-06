# markdown-tutorial

Markdown 是在 2004 年由 John Gruber 所開發出能將純文字轉換成 HTML 的工具(Perl)，特點是易讀、易寫

## [Github-flavored Markdown](https://help.github.com/en/categories/writing-on-github)

簡稱為 GFM，詳細規則可參閱 [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

基於 [CommonMark](https://commonmark.org/) 規範外，增加延伸(extension)及語法 highlight 的功能

- 表格(Table)
- 任務項目(Task List)
- 刪除線(Strikethrough)
- 自動連結(Autolinks)

<details>
  <summary>Supprise</summary>
  
  [折疊內容](https://github.com/dear-github/dear-github/issues/166)
  
  ```html
  <details>
    <summary>Supprise</summary>
    
    [折疊內容](https://github.com/dear-github/dear-github/issues/166)
    
  </details>
  ```
</details>

## 工具

- [Dingus](https://daringfireball.net/projects/markdown/dingus) 轉換工具 by John Gruber
- [Pandoc](https://pandoc.org/) 萬用轉換工具

### [DocToc](https://github.com/thlorenz/doctoc) TOC 產生器

```shell
# 所有文件產生 TOC
doctoc .

# 針對特定文件產生 TOC
doctoc README.md
```

用來辨認 TOC 的範圍，可以移到文件任何位置

```
<!-- START doctoc -->
<!-- END doctoc -->
```

### VS Code Extension

- [Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts) 右鍵可轉換各種格式
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Paste URL](https://marketplace.visualstudio.com/items?itemName=kukushi.pasteurl) 快速貼上連結

## Static Site Generator

- [MkDocs](https://www.mkdocs.org/) 
- [Hexo](https://hexo.io/)
- [Gatsby](https://www.gatsbyjs.org/)
- [VuePress](https://vuepress.vuejs.org/)
- [Docusaurus](https://docusaurus.io/)
- [更多](https://www.staticgen.com/)

### Sample

- [plain Markdown](https://github.com/vincentliu104/Learning-Together)
- [wiki](https://vincentliu99999.github.io/wiki/)
- [blog](https://vincentliu99999.github.io/)

## 學習資源

- [Communicating using Markdown | GitHub Learning Lab](https://lab.github.com/githubtraining/communicating-using-markdown)

## 參考資料

- [Markdown - 維基百科](https://zh.wikipedia.org/wiki/Markdown)
- [Daring Fireball_ Markdown](https://daringfireball.net/projects/markdown/) 轉換工具 by John Gruber
- 小抄
  - [Cheat Sheet _ Markdown Guide](https://www.markdownguide.org/cheat-sheet/) 簡單版
  - [Mastering Markdown · GitHub Guides](https://guides.github.com/features/mastering-markdown/) github 版
  - [Markdown Cheatsheet· adam-p_markdown-here Wiki](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

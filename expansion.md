## Python

## Python Debugger

## Chinese (Traditional) Language Pack for Visual Studio Code

## GitLens

## Git Graph

## Git History

## markdownlint

## Markdown All in One

## Office Viewer

##修改Markdown文字顏色

在 VS Code 中，點擊左下角的 齒輪圖示 ⚙️。
1.選擇 「使用者程式碼片段」(User Snippets)。
在上方出現的搜尋框中輸入 markdown，然後點擊搜尋到的 markdown (Markdown) 檔案。這會開啟一個 markdown.json 檔案。
在 markdown.json 的大括號 { ... } 之中，貼上以下這段代碼（如果原本裡面有範例註解，可以直接刪除或貼在後面）：
```
{
	"Red Text": {
    "prefix": "cr",
    "body": ["<span style=\"color:red\">$1</span>$0"]
 	 },
  	"Blue Text": {
    "prefix": "cb",
    "body": ["<span style=\"color:blue\">$1</span>$0"]
 	 },
  	"Green Text": {
    "prefix": "cg",
    "body": ["<span style=\"color:green\">$1</span>$0"]
}
```

2.


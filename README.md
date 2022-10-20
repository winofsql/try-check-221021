# try-check-221021

## タスクマネージャ ショートカット
```
CTRL + SHIFT + ESC
```
## エクスプローラ強制終了
```
taskkill /F /IM explorer.exe
```
- ## 全てのウインドウを閉じる
  - ## タスクマネージャを起動して explorer.exe を実行

## VSCode から C# を実行
- ## タスクマネージャで確認
  ![image](https://user-images.githubusercontent.com/1501327/197073857-34dd8c28-dd4b-4146-adda-124f97e239f7.png)
  - ## プロセスの強制終了
  ```
  taskkill /F /IM dotnet.exe
  ```

## Excel を実行
- ## タスクマネージャで確認
  ![image](https://user-images.githubusercontent.com/1501327/197074048-0952b9bd-1cd3-4c90-91c8-6af9bc0d2f7d.png)
  - ## プロセスの強制終了
  ```
  taskkill /IM excel.exe
  ```

## タスクマネージャ 詳細タブの列追加( タイトル部分を右クリック => 列選択 )
![image](https://user-images.githubusercontent.com/1501327/197074797-7887d7fb-4e8f-43eb-892e-84ce9013be65.png)
- ## イメージパス名
  - ## chrome.exe を選択して CTRL + C
    - ## EXCEL に貼り付け
    ![image](https://user-images.githubusercontent.com/1501327/197075142-bdd695ea-4f33-4b92-90ae-535e817f5c40.png)


# snippets-composable-architecture
Xcode code snippets for the Swift Composable Architecture (TCA)

##### Table of Contents  
- [Overview](#overview)
  - [feature](#feature)
  - [testfeature](#testfeature)
- [How to use](#how-to-use)
  - [한국어](#한국어)
  - [English](#english)
  - [中文](#中文)
  - [日本語](#日本語)  

## Overview

### `feature`

Creates snippets for the reducer, view and preview for a feature

| Figure.1 | Figure.2 |
| --- | --- |
| <img width="398" alt="Screenshot 2023-09-25 at 11 51 38 PM" src="https://github.com/jaesung-0o0/snippets-composable-architecture/assets/53814741/203ab202-7f89-4bf4-9ff3-3487eaefad96"> | <img width="656" alt="Screenshot 2023-09-25 at 11 51 46 PM" src="https://github.com/jaesung-0o0/snippets-composable-architecture/assets/53814741/90694147-3b12-47f7-91b6-154dbaf21814"> |

### `testfeature`

Creates scenario test method for a feature. You should use the completion inside of the test class.

| Figure.1 | Figure.2 |
| --- | --- |
| <img width="409" alt="Screenshot 2023-09-25 at 11 52 21 PM" src="https://github.com/jaesung-0o0/snippets-composable-architecture/assets/53814741/97df74dd-84de-46bd-bd64-425d20832065"> | <img width="546" alt="Screenshot 2023-09-25 at 11 52 30 PM" src="https://github.com/jaesung-0o0/snippets-composable-architecture/assets/53814741/b263a45e-cd0b-4812-96ea-17e4adcba562"> |

## How to use

## 한국어

1. 다음 경로에 자동으로 `Reducer` 와 `View`, `Preview` 까지 생성하는 코드 스니펫 파일이 있습니다.
```
/XcodeSnippets/FeatureTemplate.codesnippet
```

3. 터미널을 열고 다음 명령어를 실행하여 Xcode에 코드 스니펫 관리 폴더를 엽니다.
```bash
$ open Library/Developer/Xcode/UserData/CodeSnippets/
```

3. 폴더에 코드 스니펫 파일을 복사 붙여넣기 합니다.

4. Xcode를 실행한 후 `.swift` 파일에서 `feature` 를 입력하면 자동완성 목록에 뜨는 걸 확인할 수 있습니다.
> **IMPORTANT** Xcode 를 실행중이라면 종료 후 재시작합니다.

## English

1. You have an auto-generated code snippet file at the following path:
```
/XcodeSnippets/FeatureTemplate.codesnippet
```

3. Open your terminal and execute the following command to open the code snippet management folder in Xcode:
```bash
$ open Library/Developer/Xcode/UserData/CodeSnippets/
```

3. Copy and paste the code snippet file into this folder.

4. After opening Xcode, if it's running, please restart it. Then, when you type feature in a .swift file, you will see it in the auto-completion list.

## 中文

1. 您在以下路径有一个自动生成的代码片段文件：
```
/XcodeSnippets/FeatureTemplate.codesnippet
```

3. 打开终端并执行以下命令，以打开Xcode中的代码片段管理文件夹：
```bash
$ open Library/Developer/Xcode/UserData/CodeSnippets/
```

3. 复制并粘贴代码片段文件到这个文件夹中。

4. 在打开Xcode后，如果它正在运行，请重新启动它。然后，在`.swift`文件中键入`feature`，您将在自动完成列表中看到它。

## 日本語

1. 次のパスに自動生成されたコードスニペットファイルがあります。
```
/XcodeSnippets/FeatureTemplate.codesnippet
```

3. ターミナルを開き、Xcodeのコードスニペット管理フォルダを開くには、次のコマンドを実行してください。
```bash
$ open Library/Developer/Xcode/UserData/CodeSnippets/
```

3. コードスニペットファイルをこのフォルダにコピーして貼り付けます。

4. Xcodeを開いた後、実行中であれば終了し、再起動してください。その後、`.swift`ファイルで`feature`を入力すると、自動補完リストに表示されるはずです。

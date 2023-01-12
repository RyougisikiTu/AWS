# lecture02

## 第二回課題

#### 1. GitHub で　アカウントを作成　≫≫≫問題なく

#### 2. コースの課題リポジトリを作成しPublic（公開）に設定　≫≫≫問題なく

#### 3. Git に基本情報を設定　≫≫≫問題なく
 - 新規リポジトリのデフォルトブランチ名をmainに変更
      
      `git config --global init.defaultBranch main`
 - ユーザー名とメールアドレス
   - Gitは誰が変更したのかが重要な為、この設定が必須です 
 
`git config --global user.name "ユーザー名"`

`git config --global user.email "メールアドレス"`

-　**Tips**

`「shift+insert」ペースト`

`「Ctrl+insert」コピー`

#### 4.「ブランチ:lecture02」を作成して、今日の講座での学びを「 lecture02.md 」に Markdown で書き。

#### 5.　GITにPUSH　≫≫≫　詰まってた

### ※はじめてGitHubにpushするは認証が必要になります。 認証方法はpush時に用いる通信方式がhttpsかsshかによって変わります。

≫≫≫SSH設置上手くできず
SSH　KEY　追加できず…

### 解決方法

 ![image](https://user-images.githubusercontent.com/122083101/212110428-69afedad-c01e-4eae-97e9-ec72a0de2ae0.png)

#### 6.　GitHub でプルリクエスト（Pull Request）を発行できたら、Slackで報告。≫≫問題あった、解決。

- Propose　change　したの時気付かずにCommit directly to the main branch.　選んてしまったのでPull Requestできず
- 

![image](https://user-images.githubusercontent.com/122083101/212130685-549fdc6c-4569-4777-b3cd-4321f556975a.png)

## 参考資料
##### Gitを初めて扱うひとのためのガイドプロジェクトです。
https://github.com/raisetech-for-student/git-hands-on
##### GitHubでssh接続する手順~公開鍵・秘密鍵の生成から~
https://qiita.com/shizuma/items/2b2f873a0034839e47ce
##### [初心者向け]GitとGitHubの使い方を徹底解説
https://qiita.com/renesisu727/items/248cb9468a402c622003#%E3%81%A8%E3%82%8A%E3%81%82%E3%81%88%E3%81%9Agithub%E3%81%A8git%E3%82%92%E4%BD%BF%E3%81%88%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB%E3%81%99%E3%82%8B

##### MARK DOWN 書き方
https://markdown.com.cn/basic-syntax/line-breaks.html
https://markdown.com.cn/editor/　

# J-Quantsを使用した、株価の取得と可視化
Python, VSCode, Jupyter Notebook, J-Quantsを使って株価の取得と可視化を行っています。  
JPX-Jquants.ipynbがJ-Quantsから取得、可視化しているファイルです。  
設定ファイルとして、

- jpx_jquants_settings.ini  
    ```ini
    [JPX]
    MailAddress=（J-Quantsで登録したメールアドレス）
    Password=（J-Quantsで登録したパスワード）
    ```
- jpx_jquants_tokens.ini  
    こちらは空でOK👌

を作る必要があります。

### 参考文献
- 公式ドキュメント
  - https://jpx.gitbook.io/j-quants-ja/api-reference
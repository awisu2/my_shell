# myshells

easy to run shell for common command

## setup & update

ダウンロードリンクは変更する可能性あり。ファイルのrawパスワードを確認してください

```bash
sudo curl -o /usr/local/bin/myshells https://raw.githubusercontent.com/awisu2/my_shell/master/myshells
sudo chmod 755 /usr/local/bin/myshells
myshells
```

sudo が利用できない場合

```bash
curl -o ~/myshells https://raw.githubusercontent.com/awisu2/my_shell/master/myshells
chmod 700 ~/myshells
~/myshells
```

## clean up

```bash
sudo rm /usr/local/bin/myshells
```

sudo が利用できない場合

```bash
rm ~/myshells
```

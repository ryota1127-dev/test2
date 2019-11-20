# test2
#copy
gitのダウンロード・インストール

https://git-scm.com/download/win

※40MBほどあります

インストールは、何も考えずに次へでOKです

以下のURLに従って、公開鍵の作成
https://qiita.com/reflet/items/5c6ba6e29fe8436c3185

公開鍵を見る
cat id_rsa.pub

公開鍵をコピー
例：
=======
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDtSkK3D/Ab9GmyGiqAbeunCvBRin47GqbDmMDFddmHOLOkVV/cZtrcVm157KkqGdBEsihWeoFs9WoZVn3lxTAu5jPYz+t/g/mqVM/GLJTWeBfTtqek7376ctv67YJcni0EEMmhhgmAnajDlIa4tF5JZUlslRIGp2zEYaUqbym2XvKBmwhuGaI3PeYgZX3zGZrkSHJ1cVxijQq+xv9qRh+o/IilaPO+z9DMyHOFcYxnzGRs1jlVDjN07uSE7B+aPgnVjog8rVhozZRwheeyQ0/ee2y+vC0wBsdUA+pisw3x0o5m0j4oWlKlh2P+hiPGs5D2BtP0b7D3vivlFxNwlwfa0d40XT37pxmf4/Jc8gX7k1Ym0QtLAtRy2vYz2E0ojTG8kDi8WacT6iRK5a094nbfDs3FLduO4H+TQUwaAAfEC2q8v5ww3wMkQf/fhtpEWrnu99TM0tMJCJsAeBEmWBweaRsxUqCM18bV8xwtVAPGRaj8Spi22IUy1/FAlyIf+tgmZntXvJfCuYrZU1ZUQVESEWZ7QlixQ8PVvVQXDl+++2mlt5zBObsvVJ6l+SaGrP9N5yMgnsqnvZZBmfTCExROry9eMRwqJp5O/uDxYDvyiTqPt2YoYYF30Ci5v7b1BQmgP8+okH77UWD3U1ZFUuHFuJgtAMv3Ck6ZOlpcbRc1pQ== akihiro@neugate.co.jp
=======

githubアカウントを取得

ログイン後、右上のマークから「Settings」選択

左のタブから「SSH and GPG Keys」選択

「New SSH Key」ボタン押下

titleはお好きにどうぞ（Komiyama Serface PC）

左上の猫ロゴ押す

左のRepositoriesのNewボタン

リポジトリ作る

例：https://github.com/neugate/NKSOL

デスクトップでフォルダを作って、gitコマンド

※ここは聞いてね

echo "# NKSOL" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:neugate/NKSOL.git

git push -u origin master

晴れてGitが使えます。


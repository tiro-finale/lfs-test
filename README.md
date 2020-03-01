# LFS

巨大なサイズのファイルを管理できる．

```
$ git init
$ vim README.md
$ git add README.md
$ git commit -m 'first commit.'

$ git lfs install
$ git lfs track "bigsize.bin"
$ git add .gitattributes
$ git commit -m 'add lfs file.'

$ vim bigsize.bin
$ git add bigsize.bin
$ git commit -m 'add big file.'
$ git push origin master

```

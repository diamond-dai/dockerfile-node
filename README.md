# dockerfile

普段使うdockerfile置き場


## buildして接続

各ディレクトリで以下を実行

```
./run.sh
```
## gulp-scss

scssのbuild
ホスト側のディレクトリをマウントして監視

/opt/assets/scss/ ホスト側のscss入力用

/opt/assets/css/ ホスト側のcss出力用

## webpack-ts

tsとtsxのbuild
ホスト側のディレクトリをマウントして監視

/opt/webpack/src/ ホスト側のts入力用

/opt/webpack/dist/ ホスト側のjs出力用
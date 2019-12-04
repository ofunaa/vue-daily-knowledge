## Nuxt

- Nuxt の自動で反映されるディレクトリの機能 [??](https://ja.nuxtjs.org/guide/directory-structure/)
  - store ディレクトリに配置したファイルは、自動的に Vuex として読み込まれる
  - pages ディレクトリに配置した .vue ファイルは、自動でルーティングされる
- Nuxt では、勝手にエイリアスを効かせてくれている [??](https://ja.nuxtjs.org/guide/directory-structure/)
  - `~` or `@` == srcDir
  - `~~` or `@@` == rootDir 
  - `import hoge from '~/conponents/Hoge'` とかできる
    

## TypeScript

- tsの型で困ったら、 utility types を見るとなんとかなるかもしれない
  - https://www.typescriptlang.org/docs/handbook/utility-types.html
- 型に条件分岐を加えたい場合は、 conditional types をすると解決できる

## JavaScript

- jsの最新情報は js-primer と言う有志のサイトが結構有力
  - https://jsprimer.net/
- jsの次の機能は `tc39/proposals` と言うリポジトリで提示されている
  - https://github.com/tc39/proposals

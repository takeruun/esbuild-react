# esbuild React Typescript Template
esbuild を使用した react アプリ

https://esbuild.github.io/

## setup
```sh
npx esbuild-create-react-app esbuild-react
```

## 立ち上げ
```sh 
$ npm run start

> esbuild-react@1.0.0 start
> ts-node builder.ts --watch

Serving "build" at http://127.0.0.1:8181
Ready for changes
^C
npm run start  5.15s user 0.74s system 88% cpu 6.651 total
```


## ビルド
```sh
$ npm run build

> esbuild-react@1.0.0 build
> ts-node builder.ts

⚡ [esbuild] Building..
npm run build  5.43s user 0.81s system 134% cpu 4.626 total
```


## 所感
速度的に、`create-react-app`の React + webpack環境とあまり変わらない。（ファイルが増えるとこっちが早くなるだろう）

ファイル更新時、画面リロード入る

ネット情報もそんなにない
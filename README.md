# 環境

```
npm -v
8.5.5

node -v
v17.8.0

vue --version
@vue/cli 5.0.4
```

# テストPJについて
- npm,node,vue-cli

  すべて最新にアップデートした(つもり)

- vite: 導入

  ビルドを早くしてくれるviteを導入している
  viteなしでも構築可能かと

- TypeScript: 未導入

  Vuetify3を触ってみるためだけなので
  

# テストインストール
```
npm init @vitejs/app urstudx-vuetify3-vite --template vue

✔ Select a framework: › vue
✔ Select a variant: › vue
```
```
cd urstudx-vuetify3-vite
vue add vuetify

? Choose a preset: Vite Preview (Vuetify 3 + Vite)
```
```
npm install
npm run dev
```

# MDI (マテリアルデザインアイコン)
https://materialdesignicons.com/
- figmaで使うときはプラグインから

  https://www.figma.com/community/plugin/775671607185029020/Material-Design-Icons-(Community)

- vuetifyで使うとき

  `mdi-アイコン名`で表示される､いちいちアイコンのsvgを保存しなくてよい

```
<v-icon>mdi-home</v-icon>
```

# 所感
- 肝心なv-calendarコンポーネントはBeta版にない
  
  →2022年5月に正式リリースなので期待できる､時期的にもちょうどよいかな?
- ドキュメントざっとみてVuetify2とはいろいろ変わっている｡参考動画→

  https://www.youtube.com/watch?v=aXY4upCtiPI


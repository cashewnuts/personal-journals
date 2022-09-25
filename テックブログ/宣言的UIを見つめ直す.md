
## 期待値

- [ ] 宣言的UIとReact/Function Component について説明ができている
- [ ] 宣言的UIの価値について説明ができている
- [ ] 宣言的UIという多義的な用語の分類ができている

## 方向性

宣言的UIについての理解を深める

React では Function Component ないでフックという仕組みを使い状態の管理などを行っている。
このフックがどういうものなのか、フックがどういう働きをすることで宣言的UIを実現しているのか
そもそも宣言的UIとはどういうものを指すのかについて掘り下げていきたい。

- 宣言的UI
- フックとは
- 宣言的UIとフックの関係


## 記事の目的

宣言型UIについて理解を深めることで、Reactやflutterなどの宣言的UIと呼ばれるライブラリやフレームワークが前提としている考え方やクセを知ることが目的になります。

## 宣言的UI

### flutter
flutter の Introduction によると命令的スタイルと宣言的スタイルは以下のような違いがある。

https://docs.flutter.dev/get-started/flutter-for/declarative#how-to-change-ui-in-a-declarative-framework

```dart
// Imperative style
b.setColor(red)
b.clearChildren()
ViewC c3 = new ViewC(...)
b.add(c3)

// Declarative style
return ViewB(
  color: red,
  child: const ViewC(),
);

```

<!--
TODO
flutter から得られる宣言的UIについての知見を書く。
-->

### Wikipedia

https://en.wikipedia.org/wiki/Declarative_programming

> a style of building the structure and elements of computer programs—that expresses the logic of a computation without describing its control flow.

プログラムのロジックをコントロールフローなしで表現するスタイルのことです。


<!--
TODO: programming paradigms で参照したいものがあれば追記する。
https://en.wikipedia.org/wiki/Declarative_programming#Subparadigms
-->

### 宣言型（Declarative）の大局的な説明

宣言的な書き方とは、コントロールフロー（ロジック）を記述するのではなく、必要な処理（関数）とそのパラメータを指定することで実装を行うスタイルのことです。

誤解を恐れずにいうなら、要するに副作用を持たない関数呼び出しとパラメータの指定だけでコードを記述するスタイルのことを指します。
<!-- 副作用を持たない点についての補足を追加する -->

### 宣言型と呼ばれる言語などの例示

<!-- 
宣言的な言語の代表格であるSQLと関数型言語と宣言型スタイルの親和性について書きたい。
-->

### React における宣言型

<!-- 
React で宣言型スタイルがどのように表現されているかをせつめいする説明する。
-->

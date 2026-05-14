# A-Frame

> 仮想現実（VR）体験を構築するためのウェブフレームワーク。

## 例

<a href="https://supermedium.com/supercraft">
  <img alt="Supercraft" target="_blank" src="https://user-images.githubusercontent.com/674727/41085457-f5429566-69eb-11e8-92e5-3210e4c6c4a0.gif" height="190" width="32%">
</a>
<a href="https://aframe.io/a-painter/?url=https://ucarecdn.com/962b242b-87a9-422c-b730-febdc470f203/">
  <img alt="A-Painter" target="_blank" src="https://cloud.githubusercontent.com/assets/674727/24531388/acfc3dda-156d-11e7-8563-5bd75252f70f.gif" height="190" width="32%">
</a>
<a href="https://supermedium.com">
  <img alt="Supermedium" target="_blank" src="https://user-images.githubusercontent.com/674727/37294616-7212cd20-25d3-11e8-9e7f-c0c61074f1e0.png" height="190" width="32%">
</a>
<a href="https://aframe.io/a-blast/">
  <img alt="A-Blast" target="_blank" src="https://cloud.githubusercontent.com/assets/674727/24531440/0336e66e-156e-11e7-95c2-f2e6ebc0393d.gif" height="190" width="32%">
</a>

*さらに多くの例は、[公式ホームページ](https://aframe.io)、[A Week of A-Frame](https://aframe.io/blog/)、[WebVR Directory](https://webvr.directory)でご覧いただけます。*

## 特徴

:eyeglasses: **仮想現実をシンプルに**: A-Frameは、`<a-scene>`を配置するだけで、モバイル、デスクトップ、Vive、Riftなどのクロスプラットフォームで動作させるために必要な3DおよびWebVRのボイラープレートを処理します。

:heart: **宣言的HTML**: HTMLは読みやすく、コピー＆ペーストも簡単です。A-FrameはHTMLから使用できるため、ウェブ開発者、VR愛好家、教育者、アーティスト、メイカー、子どもたちなど、誰でも簡単に利用できます。

:electric_plug: **エンティティ・コンポーネント・アーキテクチャ**: A-Frameはthree.js上に構築された強力なフレームワークであり、宣言的で構成可能、かつ再利用可能なエンティティ・コンポーネント構造をthree.jsに提供します。A-FrameはHTMLから使用できますが、開発者はJavaScript、DOM API、three.js、WebVR、WebGLに制限なくアクセスできます。

:zap: **パフォーマンス**: A-Frameはthree.js上の軽量なフレームワークです。A-FrameはDOMを使用しますが、ブラウザのレイアウトエンジンには干渉しません。パフォーマンスは最優先事項であり、高度にインタラクティブなWebVR体験で実証されています。

:globe_with_meridians: **クロスプラットフォーム**: Vive、Rift、Daydream、GearVR、Cardboard向けのVRアプリケーションを構築できます。ヘッドセットやコントローラーを持っていなくても問題ありません！A-Frameは通常のデスクトップやスマートフォンでも動作します。

:mag: **ビジュアルインスペクター**: A-Frameは、ブラウザの開発者ツールに似たワークフローとUnityに似たインターフェースを持つ、組み込みの3Dビジュアルインスペクターを提供します。任意のA-Frameシーンを開き、`<ctrl> + <alt> + i` を押すだけで起動します。

## 使い方

### 例

数行のHTMLで、ブラウザ内にVRシーンを構築できます！今すぐ遊んだり公開したりするには、以下のスターター例をリミックスしてください：

[![Remix](https://cloud.githubusercontent.com/assets/674727/24572421/688f7fc0-162d-11e7-8a35-b02bc050c043.jpg)](https://glitch.com/~aframe) [![Fork](https://user-images.githubusercontent.com/39342/52831020-d42dcb80-3087-11e9-833f-2d6191c69eb9.png)](https://repl.it/@dmarcos/aframe)

```html
<html>
  <head>
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```

### ビルド

A-Frameの最新の安定版ビルドを使用するには、[`aframe.min.js`](https://aframe.io/releases/1.3.0/aframe.min.js) をインクルードします：

```js
<head>
  <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
</head>
```

安定版およびマスタービルドを確認するには、[`dist/README.md`](dist/) を参照してください。

## ライセンス

MIT License — [LICENSE](LICENSE) を参照してください。

# Mobile Components

## 開発手順

新しく Component を作成する為には、まずこのレポジトリを Clone します

```sh
git clone https://github.com/Naturalclar/mobile-components.git
cd mobile-components
```

そして、dependencies を install します

```
yarn
```

## 新規 Component の作成

```sh
yarn new
```

## storybook

新しく Component を開発する際は、Storybook を使いながら開発します。

```sh
yarn storybook
```

## publish

publish する前に、パッケージのバージョンを上げてください。

### パッチバージョンを上げる（見た目の微量な変更など、props に変化が無い変更を加えたとき)

```sh
npm version patch
```

### マイナーバージョンを上げる (新規 Component 作成時など、後方互換性のある変更を加えたとき)

```sh
npm version minor
```

### メジャーバージョンを上げる（props などに変更があり、後方互換性が無い変更を加えたとき）

```sh
npm version major
```

### package の Publish

```sh
npm publish
```

# Birth Fortune — 生年月日診断サイト

生年月日から20タイプに分岐する、女性向け占い診断サイトです。

## 技術スタック

- React 18
- Vite 5
- CSS-in-JS（styled JSX）

## ローカル起動

```bash
npm install
npm run dev
```

## ビルド

```bash
npm run build
```

## 背景画像の設置

`public/image/background.png` に背景画像を配置してください。  
未設置の場合はラベンダー色（`#cac1e0`）のフォールバックが表示されます。

## Vercel へのデプロイ手順

1. このリポジトリを GitHub にプッシュ
2. [vercel.com](https://vercel.com) でログイン → "Add New Project"
3. GitHubリポジトリを選択
4. Framework Preset: **Vite** を選択（自動検出されます）
5. "Deploy" を押すだけで完了

## Netlify へのデプロイ手順

1. このリポジトリを GitHub にプッシュ
2. [netlify.com](https://netlify.com) でログイン → "Add new site"
3. GitHubリポジトリを選択
4. Build command: `npm run build`
5. Publish directory: `dist`
6. "Deploy site" を押して完了

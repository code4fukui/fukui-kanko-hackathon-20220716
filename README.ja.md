# fukui-kanko-hackathon-20220716

2022年7月16日に開催された福井観光ハッカソン用に作成したフロントエンドテンプレートです。本プロジェクトは「福クル」のロゴをあしらい、Alpine.jsとTypeScriptで構築されており、ViteとYarn v3による高速な開発環境を提供します。

## ✨ 特徴

-   **モダンな技術スタック**: 軽量でリアクティブなAlpine.jsを採用し、TypeScriptで完全に型付けされています。
-   **高速な開発**: Viteによるほぼ瞬時のサーバー起動とホットモジュールリプレイスメント（HMR）。
-   **型安全なスタイリング**: [vanilla-extract](https://vanilla-extract.style/)を使用し、ランタイムオーバーヘッドなしでTypeScript内にCSSを記述できます。
-   **効率的なパッケージ管理**: Yarn v3による高速で信頼性の高い依存関係の管理。
-   **組み込みルーティング**: `src/router.ts`に実装されたシンプルなハッシュベースのルーター（`#home`、`#navi`、`#review`）。
-   **テストとリンター**: テスト用のVitestとコード品質を保つためのESLintが事前設定されています。

## 🛠️ はじめに

### 前提条件

-   Node.js v14+
-   Yarn v3.2.1+

### インストールと使い方

1.  **依存関係のインストール:**
    ```shell
    yarn
    ```

2.  **開発サーバーの起動:**
    ```shell
    yarn dev
    ```

## 📜 利用可能なスクリプト

-   `yarn dev`: Viteの開発サーバーを起動します。
-   `yarn build`: TypeScriptをコンパイルし、本番環境向けにアプリケーションをビルドします。
-   `yarn preview`: 本番ビルドをローカルでプレビュー用に配信します。
-   `yarn test`: Vitestを使用してテストを実行します。

## 🔎 参考資料

-   [Getting started with Alpine.js and TypeScript](https://dev.to/wtho/get-started-with-alpinejs-and-typescript-4dgf)
-   [Create your first Vite project](https://vitejs.dev/guide/#scaffolding-your-first-vite-project)
-   [The rise and fall of yarn and npm](https://blog.ikeryo1182.com/yarn-and-npm) （yarn v3について）
-   [Vitest - a surprisingly fast testing framework](https://sapper-blog-app.vercel.app/blog/testingframework-vitest)
-   [vanilla-extract](https://vanilla-extract.style/documentation/)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。

# Student Researcher Personal Page

## 目的
このサイトは、学生研究者の**現在の所属・業績・学歴・連絡先**を1ページで簡潔に伝えるための静的サイトです。HTML/CSSのみで構成し、軽量で読みやすく、GitHub Pagesで公開しやすい形にしています。

## GitHub Pagesで公開する手順
1. このリポジトリに `index.html` と `styles.css` を配置します（リポジトリ直下）。
2. GitHubのリポジトリ画面で **Settings** → **Pages** を開きます。
3. **Build and deployment** の **Source** を `Deploy from a branch` にします。
4. Branchに `main`（または公開したいブランチ）/ `/ (root)` を選択して保存します。
5. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/`（ユーザーサイトの場合は `https://<ユーザー名>.github.io/`）で公開されます。

## 更新方法
1. `index.html` の各プレースホルダー（`[ ... ]`）を自身の情報に置き換えます。
2. 使わない項目（指導教員、ORCID等）はコメントのままにして非表示のまま運用します。
3. 最終更新日（Footerの `Last Updated`）を更新します。
4. GitにコミットしてGitHubへpushします。

## PageSpeed Insightsで確認する方法
1. `https://pagespeed.web.dev/` にアクセスします。
2. 公開済みページURLを入力して解析します。
3. Performance / Accessibility / Best Practices / SEO の4項目を確認します。
4. 改善時のポイント:
   - 外部リソースを追加しない
   - 画像追加時は `width` / `height` を明示
   - 見出し階層（h1→h2→h3）を崩さない
   - `title` / `description` / `canonical` / OGP / JSON-LD を維持する

## どこを更新すればよいか
- **所属情報**: `index.html` の `#affiliation` セクション
- **業績情報**: `index.html` の `#achievements` セクション
- **学歴情報**: `index.html` の `#education` セクション
- **連絡先情報**: `index.html` の `#contact` セクション
- **デザイン調整**: `styles.css`

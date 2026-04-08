# my-project4

## 15のサイト・15のブランチ

このプロジェクトでは、15種類のWebサイトを作成し、それぞれのブランチで管理します。

---

## 15種類のサイト一覧

| # | ブランチ名 | サイトの種類 |
|---|-----------|------------|
| 1 | `site/portfolio` | 個人ポートフォリオ |
| 2 | `site/blog` | ブログ / テックブログ |
| 3 | `site/ecommerce` | ECサイト (ShopNow) |
| 4 | `site/restaurant` | レストランサイト (La Bella Cucina) |
| 5 | `site/landing` | プロダクトランディングページ (Nexus App) |
| 6 | `site/gallery` | フォトギャラリー (LensLife) |
| 7 | `site/news` | ニュース/マガジン (Daily Japan News) |
| 8 | `site/corporate` | コーポレートサイト (Vertex Solutions) |
| 9 | `site/education` | 教育/eラーニング (Sakura Academy) |
| 10 | `site/travel` | 旅行サイト (WanderJapan) |
| 11 | `site/music` | ミュージックバンド (Echo Waves) |
| 12 | `site/event` | イベントサイト (Future Fest 2025) |
| 13 | `site/realestate` | 不動産サイト (HomeQuest) |
| 14 | `site/healthcare` | 医療/ヘルスケア (MediCare Plus) |
| 15 | `site/nonprofit` | 非営利団体 (Green Future) |

---

## ブランチを作成する方法

各サイトのブランチは、GitHub Actionsワークフローで自動作成できます。

### 方法1: GitHub Actions を手動で実行

1. [Actions タブ](../../actions/workflows/create-branches.yml) を開く
2. **「Run workflow」** ボタンをクリック
3. ブランチを選択して **「Run workflow」** を実行

ワークフローが完了すると、15個のブランチが自動的に作成されます。

### 方法2: コマンドラインで手動作成

```bash
# リポジトリをクローン後、以下を実行
git fetch origin
git push origin ba88d1fa118826c760f768b8161cea4931fd332c:refs/heads/site/portfolio
git push origin bffb1cd5ace59284e01e09a8d842223ef5a7bf2b:refs/heads/site/blog
git push origin 8e1189a623080522331f3407ec1e9d7e183732cd:refs/heads/site/ecommerce
git push origin 78173ec6ab273c05fdcec197ad71fd03c36c5404:refs/heads/site/restaurant
git push origin 493d2cce146b9687d0a27f38c4b74c6fb1a28f92:refs/heads/site/landing
git push origin 5c023d272275a5e7d3948144dd8f3f15c5588cf9:refs/heads/site/gallery
git push origin 0a2d6ed09558f66085f39b2d05c8be4acc8d7e9d:refs/heads/site/news
git push origin 38b7e71cbb4fc696d4ce958a19ad33a843e89f38:refs/heads/site/corporate
git push origin d49b356f08caffda6fb04177a1f1286cf5551bfc:refs/heads/site/education
git push origin f4e7962560c678bad20373b7c1cafba4c35cd2ab:refs/heads/site/travel
git push origin 84260e2f7af201056fed615f754615b2d3921669:refs/heads/site/music
git push origin 58a8f400e4aa0982a612b78cc4b6095e74e32f45:refs/heads/site/event
git push origin 1a862839ed18ac3769f297235b554f69ce3221c2:refs/heads/site/realestate
git push origin d2d410ebe3ecbfa2f1e761d20a3b0b319504729c:refs/heads/site/healthcare
git push origin 977eb927ecc6852e723fd4d1d65d97aa8a04463d:refs/heads/site/nonprofit
```

---

## 各サイトのプレビュー

各ブランチの `index.html` を開くと、それぞれの完成したサイトが確認できます。

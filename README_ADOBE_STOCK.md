# Adobe Stock画像の使用について

## ヒーローセクションの画像

このドキュメントでは、Adobe Stock画像を使用する際の手順を説明します。

### 推奨検索キーワード
- "woman learning languages online"
- "multilingual education illustration"
- "language learning illustration"
- "online education languages"
- "女性 語学学習 イラスト"

### 画像の要件
- サイズ: 500x500px以上推奨
- 形式: PNG、JPG、またはSVG
- スタイル: 明るく親しみやすいイラスト調
- カラー: 暖色系（オレンジ、黄色）を含むもの

### 実装方法
1. Adobe Stockから適切な画像をライセンス購入
2. 画像を `images/` フォルダに保存
3. `index.html` の49行目のimg srcを更新：
   ```html
   <img src="images/your-adobe-stock-image.jpg" 
        alt="多言語学習を楽しむ女性のイラスト" 
        class="hero-illustration"
        data-adobe-stock="true">
   ```

### ライセンス表記
必要に応じて、フッターまたは適切な場所にAdobe Stockのクレジット表記を追加してください。
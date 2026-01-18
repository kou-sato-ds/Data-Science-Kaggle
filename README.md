# Data Science Portfolio: Kaggle Competitions

このリポジトリでは、Kaggleのコンペティションで実践した「黄金の8ステップ」に基づくデータ分析プロジェクトを公開しています。

## 🚀 Projects

### 1. Titanic - Machine Learning from Disaster
- **Goal**: 乗客データから生存者を予測する（分類問題）
- **Approach**: 欠損値の統計的補完、家族人数による特徴量エンジニアリング、RandomForestによる重要度分析
- **Metrics**: **Recall（再現率）** を重視し、生存者の見逃しを最小化
- **Notebook**: `[Step_1_8]_Titanic_Survival_Prediction.ipynb`

### 2. Spaceship Titanic
- **Goal**: 別の次元に輸送された乗客を予測する
- **Approach**: キャビン番号からのデッキ/サイド抽出、合計消費額による特徴量生成
- **Model**: LightGBM (勾配ブースティング決定木)
- **Notebook**: `[Step_1_8]_Spaceship_Titanic.ipynb`

### 3. House Prices - Advanced Regression Techniques
- **Goal**: 住宅の特徴から販売価格を推定する（回帰問題）
- **Approach**: 歪度の高い変数への対数変換、住宅の築年数計算、Lasso/Ridge回帰による変数選択
- **Metrics**: **RMSE** (Root Mean Squared Error) を最小化
- **Notebook**: `[Step_1_8]_House_Prices_Regression.ipynb`

---
## 🛠️ Analysis Framework: The Golden 8 Steps
1. Business Understanding
2. Data Understanding (EDA)
3. Data Preprocessing
4. Feature Engineering
5. Model Selection
6. Evaluation
7. Hyperparameter Tuning
8. Conclusion / Submission

![Screenshot 2023-08-27 at 01-58-39 SIGNATE Student Cup 2023【モデリング部門】：中古車の価格予測チャレンジ SIGNATE - Data Science Competition](https://github.com/haru1290/signate-student-cup-2023/assets/83323040/bb1b4756-048b-40f6-87af-ce27ae2f9acd)

# SIGNATE Student Cup 2023
This competition is hosted by SIGNATE.
The goal is to build an algorithm that predicts the price of used cars based on information (such as car type and odometer).

This repository is the solution that 12th place in the SIGNATE Student Cup 2023.

I experimented with everything on Google Colab. As a pretreatment, I corrected for discrepancies in missing values and character codes.
Also, we predicted the price by stacking LightGBM.

## :hugs: Requirement
- NumPy 1.23.5
- Pandas 1.5.3
- Scikit-learn 1.2.2
- LightGBM 4.0.0
- Matplotlib 3.7.1
- Seaborn 0.12.2

## :rocket: Usage
All processing must be done in the `repos/` folder of Google Colab.
```
# Creat working directory.
!mkdir repos

# Clone from GitHub.
!git clone https://github.com/haru1290/signate-student-cup-2023.git
```

## :pen: Author
- HryeDev
- Ehime University
- E-mail: suzuki@ai.cs.ehime-u.ac.jp

## :memo: Licence
[MIT license](https://github.com/haru1290/signate-student-cup-2023/blob/main/LICENSE)

## :books: References
- [LightGBM](https://lightgbm.readthedocs.io/en/stable/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Kaggleで勝つデータ分析の技術](https://github.com/ghmagazine/kagglebook)
- [飯田産業 土地の販売価格の推定](https://signate.jp/competitions/162)
- [中古車価格予測](https://www.kaggle.com/competitions/used-car-price-forecasting/overview)
- [Used Cars Price Prediction](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction)

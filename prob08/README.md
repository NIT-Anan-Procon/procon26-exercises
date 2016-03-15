# 問題00-08 クラス分け

ある人数の学生を2クラス、A, Bに分ける事を考える
A, Bのクラスに分けるにあたり、各クラスの学生の点数の合計の差がなるべく小さくなるような組み合わせにする
ただし、人数に偏りは無視し(各クラス1人以上いればよい)、点数は0~100点とする

(例)
{43, 86, 12, 50}
->A{43, 50}, B{86, 12}
(|A-B| = 5 で最小の組み合わせ)

{100, 30, 10, 50}
->A{100}, B{30, 10, 50}
(|A-B| = 10 で最小の組み合わせ)

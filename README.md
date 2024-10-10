# sparse-modeling-control

CVX: Matlab Software for Disciplined Convex Programming | CVX Research, Inc.

https://cvxr.com/cvx/

## MATLAB コード

## MATLAB CVX
凸最適化問題を解くためのツールボックス CVX が必要です．以下のページよりダウンロードしてインストールしてください．

http://cvxr.com/cvx/

MATLAB 2017b で動作確認しています．

<pre>
第3章「凸最適化アルゴリズム」の例題（画像の全変動ノイズ除去）を実行するには image processing toolbox が必要です．
第2章　曲線フィッティングで学ぶスパースモデリング
chap2_curve_fitting_cvx.m （2.3節　CVXによる数値最適化の例題）
第3章　凸最適化アルゴリズム
chap3_tv_denoising.m　（例題3.1 画像の全変動ノイズ除去）
chap3_tv_denoising_ver2.m （上記の高速バージョン）
lena.jpg　（処理画像）
soft_thresholding.m　（ソフトしきい値作用素）
第4章　貪欲アルゴリズム
MP.m　（マッチング追跡 MP）
OMP.m　（直交マッチング追跡 OMP）
hard_thresholding.m　（ハードしきい値作用素）
supp.m　（ベクトルの台）
IHT.m　（反復ハードしきい値アルゴリズム IHT）
s_sparse_operator.m　（s-スパース作用素）
iterative_s_sparse.m　（反復s-スパースアルゴリズム）
CoSaMP.m (CoSaMP)
chap4_curve_fitting_greedy.m　（4.4節の例題）
第8章　動的スパースモデリングのための数値最適化
chap8_sparse_control_cvx.m　（CVXによる動的スパースモデリングの数値計算）
chap8_sparse_control_ADMM.m　（ADMMによる動的スパースモデリングの数値計算）
</pre>

## references

Sparse Modeling

スパースモデリング―基礎から動的システムへの応用―

https://nagahara-masaaki.github.io/spm.html

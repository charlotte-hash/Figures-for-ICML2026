# Figures-for-ICML2026
Figures:

1. `zo_compare_test_acc.png` and `zo_compare_test_loss.png` compare the empirical convergence behavior of ZO-SGD and ZO-SGDM.

2. `zo_smooth_compare.png` shows that the smooth and nonsmooth settings exhibit similar convergence rates in practice.

3. `Reset_acc.png` and `Reset_loss.png` suggest that resetting mainly serves as an analysis tool: even without resetting, the method still performs comparably to ZO-SGD and ZO-SGDM. We also observe a clear early-stage acceleration effect from momentum, which is consistent with the first-order setting shown in `FO.png` and with the typical ZO-SGDM (SHB) behavior shown in `Momentum.png`.

4. `FO.png` presents additional experiments in the first-order setting, comparing the cases with and without resetting.

References:

[R1] Ji, Fanfan, and Xiaotong Yuan. "Derandomized Online-to-Non-convex Conversion for Stochastic Weakly Convex Optimization." In The Fourteenth International Conference on Learning Representations.

[R2] Kornowski, Guy, and Ohad Shamir. "An algorithm with optimal dimension-dependence for zero-order nonsmooth nonconvex stochastic optimization." Journal of Machine Learning Research 25, no. 122 (2024): 1-14.

[R3] Lin, T., Zheng, Z., and Jordan, M. Gradient-free methods for deterministic and stochastic nonsmooth nonconvex optimization. Advances in Neural Information Processing Systems, 35:26160 -26175, 2022

[R4] Chen, L., Xu, J., and Luo, L. Faster gradient-free algorithms for nonsmooth nonconvex stochastic optimization. In International Conference on Machine Learning, pp. 5219–5233. PMLR, 2023.

[R5] Rando, M., Molinari, C., Rosasco, L., and Villa, S. (2023). An optimal structured zeroth-order algorithm for non-smooth optimization. Advances in Neural Information Processing Systems, 36, 36738–36767.

[R6] Cutkosky, A., Mehta, H., and Orabona, F. Optimal stochastic non-smooth non-convex optimization through online-to-non-convex conversion. In International Conference on Machine Learning (ICML), pp. 6643–6670. PMLR, 2023.

[R7] Davis D, Drusvyatskiy D. Stochastic model-based minimization of weakly convex functions. SIAM Journal on Optimization. 2019;29(1):207-39.

[R8] Asi H, Duchi JC. The importance of better models in stochastic optimization. Proceedings of the National Academy of Sciences. 2019 Nov 12;116(46):22924-30.

[R9] Liu, S., Chen, P.-Y., Kailkhura, B., Zhang, G., Hero III, A. O., and Varshney, P. K. A primer on zeroth-order optimization in signal processing and machine learning: Principals, recent advances, and applications. IEEE Signal Processing Magazine, 37(5):43–54, 2020a.

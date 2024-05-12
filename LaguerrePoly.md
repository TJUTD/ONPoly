Laguerre Polynomials
================

$$\begin{aligned}
(n+1)L_{n+1}(t) = (2n+1-t)L_n(t)-nL_{n-1}(t).
    \end{aligned}$$ $$\begin{aligned}
&L_0(t) = 1\\
&L_1(t) = -t+1\\
&L_2(t) = 2^{-1}(t^2-4t+2)\\
&L_3(t) = 6^{-1}(-t^3 +9t^2 - 18t + 6)\\
&L_4(t) = 24^{-1}(t^4-16t^3+72t^2-96t+24)\\
&L_5(t) = 120^{-1}(-t^5+25t^4-200t^3+600t^2-600t+120)
    \end{aligned}
$$

- Othonormal basis
$$\begin{aligned}
  \varphi_n(t) &= \sqrt{2}L_n(2t)e^{-t}\\
  (n+1)\varphi_{n+1}(t) &= (2n+1-2t)\varphi_n(t)-n\varphi_{n-1}(t).
  \end{aligned}$$

$$\begin{aligned}
&\varphi_0(t) = \sqrt{2}e^{-t}\\
&\varphi_1(t) = \sqrt{2}(-2t+1)e^{-t}\\
&\varphi_2(t) = \sqrt{2}2^{-1}(4t^2-8t+2)e^{-t}\\
&\varphi_3(t) = \sqrt{2}6^{-1}(-8t^3 +36t^2 - 36t + 6)e^{-t}\\
&\varphi_4(t) = \sqrt{2}24^{-1}(16t^4-128t^3+288t^2-192t+24)e^{-t}\\
&\varphi_5(t) = \sqrt{2}120^{-1}(-32t^5+400t^4-1600t^3+2400t^2-1200t+120)e^{-t}
    \end{aligned}
$$

![](LaguerrePoly_files/figure-gfm/basis-1.png)<!-- -->

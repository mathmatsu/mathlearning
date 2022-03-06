**2.3.3** 例 2.3.10 の $U(n) \subset GL_n(\mathbb{C})$ が部分群であることを証明せよ.  
<br>

$g \in GL_n(\mathbb{C})$ のすべての成分の複素共役をとり転置した行列を$g^\ast$とする.  
$I_n$ を n 次の単位行列とすると、$I_n^{\ast}=I_n$ となり $I_n^{\ast}I_n=I_n$ なので $I_n \in U(n)$ である.  
$\forall g,h \in U(n)$ ならば $(gh)^{\ast}(gh) = h^{\ast}g^{\ast}gh = h^{\ast}I_nh = h^{\ast}h = I_n$ なので $gh \in U(n)$ である.  
また、$(g^{-1})^{\ast}g^{-1} = (g^{\ast}g)^{-1} = I_n^{-1} = In$ なので $g^{-1} \in U(n)$ である.   
命題 2.3.2 により、$U(n)$ は $GL_n(\mathbb{C})$ の部分群である.
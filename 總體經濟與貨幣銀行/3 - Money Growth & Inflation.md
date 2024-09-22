# Fisher Effect

$$
i_r \approx i_n - \pi^e
$$

- $i_r$：實質利率
- $i_n$：名目利率
- $\pi^e$：預期通膨率

### 實質利率

名目利率是銀行告示的利率，由於存在通貨膨脹，所以==名目利率並不能代表貨幣購買力隨時間成長的幅度==，須要將名目利率消除掉通膨效果才行。

### 公式推導

假設原本一顆蘋果的價格是 a 元、銀行存款利率為 $i_n$，今某人有本金 a 元存在銀行，過了 n 年後，a 元就會變成 $a \times (1+i_n)^n$ 元（假設這 n 年的利率都不變），然而因為有通貨膨漲，所以一顆蘋果的價格在 n 年後來到 $a \times (1 + \pi)^n$ 元（假設這 n 年的通膨率都固定為 $\pi$），綜合考量後，可以計算出現在的 a 元在 n 年後可以買到的蘋果數量為 $({1+i_n \over 1+\pi})^n$ 顆。

而如果令：

$$
({1+i_n \over 1+\pi})^n = (1 + i_r)^n
$$

則：

$$
\eqalign{
1 + i_n &= (1 + i_r)(1 + \pi)\\
&= 1 + i_r + \pi + i_r \cdot \pi
}
$$

$$
\eqalign{
\implies i_n &= i_r + \pi + i_r \cdot \pi\\
&\approx i_r + \pi
}
$$

$$
\implies i_r \approx i_n - \pi
$$

#TODO 
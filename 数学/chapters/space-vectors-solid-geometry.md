# 空间向量与立体几何

人教B版 高中数学

> 常考：证明 · 求角 · 求距离 · 参数存在性　｜　流程：建系 → 写坐标 → 写向量 → 求法向量 → 套公式

---

## 目录

- [一、章节速览](#一章节速览)
- [二、知识清单](#二知识清单)
- [三、方法模板](#三方法模板)
- [四、易错自查](#四易错自查)
- [五、基础练习（25分钟）](#五基础练习25分钟)
- [六、模拟练习](#六模拟练习)
- [七、高考真题](#七高考真题)
- [八、薄弱环节](#八薄弱环节)

---

## 一、章节速览

| 层级 | 必须会 | 常考 | 易失分 |
|---|---|---|---|
| 基础 | 坐标、数量积、模长、夹角 | 选择、填空 | $\overrightarrow{AB}=B-A$ 写反 |
| 核心 | 方向向量、法向量、线面/面面关系 | 证明、求角 | 法向量方程列错 |
| 拔高 | 动点参数、范围、存在性 | 解答题第二问 | 忘记 $0\le t\le1$ |

---

## 二、知识清单

### 1. 向量坐标

若 $A(x_A,y_A,z_A)$，$B(x_B,y_B,z_B)$，则

$$
\overrightarrow{AB}=(x_B-x_A,\ y_B-y_A,\ z_B-z_A).
$$

$$
|AB|=\sqrt{(x_B-x_A)^2+(y_B-y_A)^2+(z_B-z_A)^2}.
$$

### 2. 数量积

若 $\mathbf a=(x_1,y_1,z_1)$，$\mathbf b=(x_2,y_2,z_2)$，则

$$
\mathbf a\cdot \mathbf b=x_1x_2+y_1y_2+z_1z_2,\qquad
\cos\langle \mathbf a,\mathbf b\rangle=\frac{\mathbf a\cdot\mathbf b}{|\mathbf a||\mathbf b|}.
$$

**垂直：** $\mathbf a\cdot\mathbf b=0$；**平行：** $\mathbf a=\lambda\mathbf b$。

### 3. 角的公式

| 对象 | 公式 | 注意 |
|---|---|---|
| 线线角 | $\cos\theta=\dfrac{|\mathbf u\cdot\mathbf v|}{|\mathbf u||\mathbf v|}$ | 默认锐角或直角 |
| 线面角 | $\sin\theta=\dfrac{|\mathbf u\cdot\mathbf n|}{|\mathbf u||\mathbf n|}$ | 用正弦 |
| 面面角 | $\cos\theta=\dfrac{|\mathbf n_1\cdot\mathbf n_2|}{|\mathbf n_1||\mathbf n_2|}$ | 先算，再判锐钝 |

### 4. 距离公式

点 $P$ 到平面 $\alpha$：若 $A\in\alpha$，法向量为 $\mathbf n$，则

$$
d=\frac{|\overrightarrow{AP}\cdot\mathbf n|}{|\mathbf n|}.
$$

点 $P$ 到直线 $l$：若 $A\in l$，方向向量为 $\mathbf u$，则

$$
d^2=|\overrightarrow{AP}|^2-\left(\frac{|\overrightarrow{AP}\cdot\mathbf u|}{|\mathbf u|}\right)^2.
$$

### 5. 法向量

平面内有不共线向量 $\mathbf a,\mathbf b$，设 $\mathbf n=(x,y,z)$：

$$
\begin{cases}
\mathbf n\cdot\mathbf a=0,\\
\mathbf n\cdot\mathbf b=0.
\end{cases}
$$

**做题：** 令一个未知数为 $1$ 或 $2$ → 解另外两个 → 代回验算两个点积都为 $0$。

---

## 三、方法模板

### 1. 建系

- 正方体、长方体、直棱柱：沿三条互相垂直的棱建系。
- 有中点 / 垂足 / 对称中心：优先设为原点。
- 动点：$P=A+t(B-A)$，在线段上写 $0\le t\le1$。

### 2. 证明题

线线垂直：$\mathbf u\cdot\mathbf v=0$ → 线面垂直：$\mathbf u\parallel\mathbf n$ → 面面垂直：$\mathbf n_1\cdot\mathbf n_2=0$

### 3. 求角题

线线：方向向量 → 线面：方向向量 + 法向量，用 $\sin$ → 面面：两个法向量，用 $\cos$

### 4. 参数题

设参数 → 写范围 → 翻译条件 → 解方程 → 检验范围

---

## 四、易错自查

| 易错点 | 正确写法 |
|---|---|
| 向量写反 | $\overrightarrow{AB}=B-A$ |
| 线面角公式错 | 用 $\sin\theta=\dfrac{|\mathbf u\cdot\mathbf n|}{|\mathbf u||\mathbf n|}$ |
| 二面角不判锐钝 | 法向量夹角可能是补角 |
| 动点忘范围 | 线段：$0\le t\le1$；直线：$t\in\mathbb R$ |

**补题顺序：** 坐标与点积 10 题 → 法向量 10 题 → 线面角 / 二面角各 8 题 → 参数存在性 6 题。

---

## 五、基础练习（25分钟）

1. **坐标** 已知 $A(1,2,-1)$，$B(3,-1,4)$，求 $\overrightarrow{AB}$ 与 $|AB|$。

<details>
<summary>答案</summary>

$\overrightarrow{AB}=(2,-3,5)$，$|AB|=\sqrt{38}$。
</details>

2. **坐标** 已知 $A(1,2,-1)$，$B(3,-1,4)$，求 $\overrightarrow{BA}$。

<details>
<summary>答案</summary>

$\overrightarrow{BA}=(-2,3,-5)$。
</details>

3. **模长** 已知 $A(0,1,2)$，$B(2,-1,4)$，求 $|AB|$。

<details>
<summary>答案</summary>

$\overrightarrow{AB}=(2,-2,2)$，$|AB|=2\sqrt3$。
</details>

4. **数量积** 已知 $\mathbf a=(1,-2,2)$，$\mathbf b=(3,0,-1)$，求 $\mathbf a\cdot\mathbf b$ 和夹角余弦值。

<details>
<summary>答案</summary>

$\mathbf a\cdot\mathbf b=1$，$|\mathbf a|=3$，$|\mathbf b|=\sqrt{10}$，$\cos\theta=\dfrac1{3\sqrt{10}}$。
</details>

5. **垂直** 判断 $\mathbf a=(1,2,2)$ 与 $\mathbf b=(2,1,-2)$ 是否垂直。

<details>
<summary>答案</summary>

$\mathbf a\cdot\mathbf b=2+2-4=0$，所以垂直。
</details>

6. **平行** 判断 $\mathbf a=(2,-1,1)$ 与 $\mathbf b=(-4,2,-2)$ 是否平行。

<details>
<summary>答案</summary>

$\mathbf b=-2\mathbf a$，所以平行。
</details>

7. **夹角** 求 $\mathbf a=(1,0,1)$ 与 $\mathbf b=(0,1,1)$ 的夹角。

<details>
<summary>答案</summary>

$\cos\theta=\dfrac1{\sqrt2\cdot\sqrt2}=\dfrac12$，$\theta=60^\circ$。
</details>

8. **法向量** 平面经过 $A(1,0,0)$，$B(0,1,0)$，$C(0,0,1)$，求一个法向量。

<details>
<summary>答案</summary>

平面 $x+y+z=1$，法向量可取 $(1,1,1)$。
</details>

9. **法向量** 平面经过 $A(1,0,0)$，$B(0,1,0)$，$C(0,0,2)$，求一个法向量。

<details>
<summary>答案</summary>

平面 $2x+2y+z=2$，法向量可取 $(2,2,1)$。
</details>

10. **法向量** 平面过原点且含 $\mathbf a=(1,1,0)$，$\mathbf b=(1,0,1)$，求一个法向量。

<details>
<summary>答案</summary>

由 $x+y=0$，$x+z=0$ 取 $\mathbf n=(1,-1,-1)$。
</details>

11. **单位向量** 已知 $\mathbf a=(2,-1,3)$，求 $|\mathbf a|$ 及与 $\mathbf a$ 同向的单位向量。

<details>
<summary>答案</summary>

$|\mathbf a|=\sqrt{14}$，单位向量为 $\dfrac{(2,-1,3)}{\sqrt{14}}$。
</details>

12. **分点** $P$ 在线段 $AB$ 上，$A(1,2,0)$，$B(5,-2,4)$，且 $AP:PB=1:3$，求 $P$。

<details>
<summary>答案</summary>

$P=A+\frac14(B-A)=(2,1,1)$。
</details>

13. **分点** $M$ 在线段 $AB$ 上，$A(1,0,0)$，$B(3,2,4)$，且 $AM:MB=3:1$，求 $M$。

<details>
<summary>答案</summary>

$M=A+\frac34(B-A)=\left(\frac52,\frac32,3\right)$。
</details>

14. **线面角** 直线方向向量 $\mathbf u=(1,2,2)$，平面法向量 $\mathbf n=(0,0,1)$，求线面角的正弦值。

<details>
<summary>答案</summary>

$\sin\theta=\dfrac{|\mathbf u\cdot\mathbf n|}{|\mathbf u||\mathbf n|}=\dfrac23$。
</details>

15. **线面角** 正方体棱长为 $2$，取 $A(0,0,0)$，$B(2,0,0)$，$D(0,2,0)$，$A_1(0,0,2)$。求 $AC_1$ 与底面 $ABCD$ 所成角的正弦值。

<details>
<summary>答案</summary>

$\overrightarrow{AC_1}=(2,2,2)$，底面法向量 $\mathbf n=(0,0,1)$，$\sin\theta=\dfrac{2}{2\sqrt3}=\dfrac1{\sqrt3}$。
</details>

16. **二面角** 两平面的法向量为 $\mathbf n_1=(1,0,1)$，$\mathbf n_2=(0,1,1)$，求两平面的锐夹角。

<details>
<summary>答案</summary>

$\cos\theta=\dfrac{|1|}{\sqrt2\sqrt2}=\dfrac12$，$\theta=60^\circ$。
</details>

17. **二面角** 两平面的法向量为 $\mathbf n_1=(1,1,0)$，$\mathbf n_2=(1,0,1)$，求两平面的锐夹角。

<details>
<summary>答案</summary>

$\cos\theta=\dfrac{|1|}{\sqrt2\sqrt2}=\dfrac12$，$\theta=60^\circ$。
</details>

18. **点面距** 求点 $P(1,1,1)$ 到平面 $x+2y+2z-9=0$ 的距离。

<details>
<summary>答案</summary>

$d=\dfrac{|1+2+2-9|}{\sqrt{1^2+2^2+2^2}}=\dfrac43$。
</details>

19. **点面距** 求点 $P(1,1,2)$ 到平面 $2x-y+2z+1=0$ 的距离。

<details>
<summary>答案</summary>

$d=\dfrac{|2-1+4+1|}{3}=2$。
</details>

20. **点线距** 点 $A(1,0,2)$ 到过原点、方向向量为 $(1,2,2)$ 的直线的距离。

<details>
<summary>答案</summary>

$d^2=5-\dfrac{25}{9}=\dfrac{20}{9}$，$d=\dfrac{2\sqrt5}{3}$。
</details>

21. **点线距** 点 $A(1,0,0)$ 到过原点、方向向量为 $(1,1,1)$ 的直线的距离。

<details>
<summary>答案</summary>

$d^2=1-\dfrac13=\dfrac23$，$d=\dfrac{\sqrt6}{3}$。
</details>

22. **点面距** 在正方体 $ABCD-A_1B_1C_1D_1$ 中，棱长为 $1$，取 $A(0,0,0)$，$B(1,0,0)$，$D(0,1,0)$，$A_1(0,0,1)$。求点 $C$ 到平面 $A_1BD$ 的距离。

<details>
<summary>答案</summary>

平面 $A_1BD$ 过 $A_1(0,0,1)$，$B(1,0,0)$，$D(0,1,0)$，方程为 $x+y+z=1$。所以 $d=\dfrac{|1+1+0-1|}{\sqrt3}=\dfrac1{\sqrt3}$。
</details>

23. **参数点** 正方体棱长为 $2$，$P$ 在线段 $A_1B_1$ 上，$P=A_1+t(B_1-A_1)$，$0\le t\le1$。若 $BP$ 与平面 $ADD_1A_1$ 所成角为 $45^\circ$，求 $t$。

<details>
<summary>答案</summary>

$\overrightarrow{BP}=(2t-2,0,2)$，$\sin\theta=\dfrac{|2t-2|}{\sqrt{(2t-2)^2+4}}=\dfrac1{\sqrt2}$，得 $t=0$（此时 $P=A_1$）或 $t=2$（舍），故 $t=0$。
</details>

24. **垂直·参数** 已知 $\mathbf a=(1,\lambda,2)$，$\mathbf b=(2,1,-2)$，若 $\mathbf a\perp\mathbf b$，求 $\lambda$。

<details>
<summary>答案</summary>

$\mathbf a\cdot\mathbf b=2+\lambda-4=\lambda-2=0$，所以 $\lambda=2$。
</details>

25. **综合** 已知 $A(1,0,0)$，$B(0,1,0)$，$C(0,0,1)$，$D(1,1,1)$。求点 $D$ 到平面 $ABC$ 的距离。

<details>
<summary>答案</summary>

平面 $ABC: x+y+z=1$，$d=\dfrac{|1+1+1-1|}{\sqrt3}=\dfrac{2\sqrt3}{3}$。
</details>

---

## 六、模拟练习

### 模拟 1：三棱锥

在三棱锥 $P-ABC$ 中，$A(0,0,0)$，$B(2,0,0)$，$C(0,2,0)$，$P(0,0,3)$。
（1）证明 $PA\perp$ 平面 $ABC$；（2）求直线 $PB$ 与平面 $ABC$ 所成角的正弦值；（3）求平面 $PBC$ 与平面 $ABC$ 的锐夹角余弦值。

<details>
<summary>规范作答</summary>

**解析：** 三条侧棱 $PA,AB,AC$ 两两垂直，以 $A$ 为原点建系。证明用 $PA\parallel\mathbf n_0$；线面角写 $\sin\theta$；二面角用两个法向量、取锐角。

**证明：** 由题意得，平面 $ABC$ 为 $z=0$，其一个法向量为 $\mathbf n_0=(0,0,1)$。因为 $\overrightarrow{PA}=(0,0,-3)$，所以 $\overrightarrow{PA}\parallel\mathbf n_0$，故 $PA\perp$ 平面 $ABC$。

**解：** $\overrightarrow{PB}=(2,0,-3)$。设 $PB$ 与平面 $ABC$ 所成角为 $\theta$，则

$$
\sin\theta=\frac{|\overrightarrow{PB}\cdot\mathbf n_0|}{|\overrightarrow{PB}||\mathbf n_0|}=\frac3{\sqrt{13}}.
$$

平面 $PBC$ 内，$\overrightarrow{BC}=(-2,2,0)$，$\overrightarrow{BP}=(-2,0,3)$。设平面 $PBC$ 的法向量为 $\mathbf n=(x,y,z)$，则

$$
\begin{cases}
-2x+2y=0,\\
-2x+3z=0.
\end{cases}
$$

取 $\mathbf n=(3,3,2)$。因为平面 $ABC$ 的法向量为 $\mathbf n_0=(0,0,1)$，所以两平面的锐夹角余弦值为

$$
\frac{|\mathbf n\cdot\mathbf n_0|}{|\mathbf n||\mathbf n_0|}=\frac2{\sqrt{22}}.
$$

</details>

### 模拟 2：动点参数

在长方体 $ABCD-A_1B_1C_1D_1$ 中，$AB=4$，$AD=3$，$AA_1=2$。点 $M$ 在线段 $DD_1$ 上，设 $DM=tDD_1$。若 $BM\perp AC_1$，求 $t$。

<details>
<summary>规范作答</summary>

**解析：** 建系后由 $DM=tDD_1$ 写 $M(0,3,2t)$ 并注明 $0\le t\le1$；把 $BM\perp AC_1$ 翻译成数量积为 $0$，解出的 $t$ 必须回代检验范围。

**解：** 以 $A$ 为原点，分别以 $AB,AD,AA_1$ 所在直线为 $x,y,z$ 轴，建立空间直角坐标系。由题意得 $B(4,0,0)$，$D(0,3,0)$，$C_1(4,3,2)$。因为 $DM=tDD_1$，且 $M$ 在线段 $DD_1$ 上，所以 $M(0,3,2t)$，$0\le t\le1$。于是 $\overrightarrow{BM}=(-4,3,2t)$，$\overrightarrow{AC_1}=(4,3,2)$。

因为 $BM\perp AC_1$，所以

$$
\overrightarrow{BM}\cdot\overrightarrow{AC_1}=-16+9+4t=0.
$$

解得 $t=\dfrac74$。但 $\dfrac74\notin[0,1]$，故线段 $DD_1$ 上不存在满足条件的点 $M$。

</details>

### 模拟 3：二面角

已知四面体 $ABCD$ 中，$A(0,0,0)$，$B(2,0,0)$，$C(0,2,0)$，$D(0,1,2)$。求二面角 $A-BC-D$ 的余弦值（取锐角）。

<details>
<summary>规范作答</summary>

**解析：** 平面 $ABC$ 即 $xOy$ 面，法向量可直接取 $(0,0,1)$；再求平面 $DBC$ 的法向量，最后按“取锐角”定余弦值正负。

**解：** 由题意得，平面 $ABC$ 的一个法向量为 $\mathbf n_1=(0,0,1)$。平面 $DBC$ 内，$\overrightarrow{BC}=(-2,2,0)$，$\overrightarrow{BD}=(-2,1,2)$。设平面 $DBC$ 的法向量为 $\mathbf n_2=(x,y,z)$，则

$$
\begin{cases}
-2x+2y=0,\\
-2x+y+2z=0.
\end{cases}
$$

取 $\mathbf n_2=(2,2,1)$。因为二面角取锐角，所以

$$
\cos\theta=\frac{|\mathbf n_1\cdot\mathbf n_2|}{|\mathbf n_1||\mathbf n_2|}=\frac13.
$$

故二面角 $A-BC-D$ 的余弦值为 $\dfrac13$。

</details>

### 模拟 4：存在性

在正方体 $ABCD-A_1B_1C_1D_1$ 中，棱长为 $2$。点 $M$ 在线段 $AC$ 上，设 $M=A+t(C-A)$，$0\le t\le1$。是否存在 $M$，使 $B_1M\perp A_1D$？

<details>
<summary>规范作答</summary>

**解析：** 设 $M(2t,2t,0)$、$0\le t\le1$，由 $B_1M\perp A_1D$ 列数量积方程；解出 $t$ 后判断是否在 $[0,1]$ 内，不在则答“不存在”。

**解：** 取 $A(0,0,0)$，$B(2,0,0)$，$D(0,2,0)$，$A_1(0,0,2)$，则 $C(2,2,0)$，$B_1(2,0,2)$。由 $M=A+t(C-A)$，得 $M(2t,2t,0)$，且 $0\le t\le1$。所以 $\overrightarrow{B_1M}=(2t-2,2t,-2)$，$\overrightarrow{A_1D}=(0,2,-2)$。

若 $B_1M\perp A_1D$，则

$$
\overrightarrow{B_1M}\cdot\overrightarrow{A_1D}=4t+4=0.
$$

解得 $t=-1$。因为 $-1\notin[0,1]$，所以不存在满足条件的点 $M$。

</details>

---

## 七、高考真题

格式：年份 · 卷别 · 题号 → 原题 → 精讲 → 变式（未逐字对应的题标“同考点改编 / 同考点转写”）。

### 1. 空间角与点面距离

出处：2022 · 新高考Ⅰ卷 · 第9题（多选）　〔同考点转写〕

原题：正方体 $ABCD-A_1B_1C_1D_1$ 棱长为 $1$。判断：①$BC_1\perp DA_1$；②$BC_1$ 与平面 $BB_1D_1D$ 所成角的正弦值为 $\frac12$；③点 $C$ 到平面 $AB_1D_1$ 的距离为 $\frac{2\sqrt3}{3}$。

<details open>
<summary>精讲</summary>

**解析：** 建系后逐项判断：垂直看点积为 $0$，线面角用 $\sin\theta$，点面距离直接套公式。

**解：** 取 $A(0,0,0)$，$B(1,0,0)$，$D(0,1,0)$，$A_1(0,0,1)$。因为 $\overrightarrow{BC_1}=(0,1,1)$，$\overrightarrow{DA_1}=(0,-1,1)$，且 $\overrightarrow{BC_1}\cdot\overrightarrow{DA_1}=0$，所以①正确。

平面 $BB_1D_1D$ 的法向量可取 $\mathbf n=(1,1,0)$，故

$$
\sin\theta=\frac{|(0,1,1)\cdot(1,1,0)|}{\sqrt2\sqrt2}=\frac12,
$$

所以②正确。

平面 $AB_1D_1$ 的法向量可取 $(-1,-1,1)$，方程为 $-x-y+z=0$。点 $C(1,1,0)$ 到该平面的距离

$$
d=\frac{|-1-1+0|}{\sqrt3}=\frac{2\sqrt3}{3},
$$

所以③正确。

</details>

**变式：** 若棱长为 $2$，点 $C$ 到平面 $AB_1D_1$ 的距离为 $\dfrac{4\sqrt3}{3}$。

### 2. 证明 + 二面角

出处：近年新高考卷 · 第17—19题　〔同考点改编〕

原题：四棱锥 $P-ABCD$ 中，底面为正方形，$PA\perp$ 底面，$AB=PA=2$，$M$ 为 $PC$ 中点。证明 $BM\perp PD$，并求平面 $PBM$ 与平面 $PDM$ 的锐夹角余弦值。

<details>
<summary>精讲</summary>

**解析：** 由 $M$ 为 $PC$ 中点先写坐标；证垂直看 $\overrightarrow{BM}\cdot\overrightarrow{PD}=0$；求二面角分别取两平面法向量。

**证明：** 取 $A(0,0,0)$，$B(2,0,0)$，$D(0,2,0)$，$P(0,0,2)$，则 $C(2,2,0)$，$M(1,1,1)$。因为 $\overrightarrow{BM}=(-1,1,1)$，$\overrightarrow{PD}=(0,2,-2)$，且 $\overrightarrow{BM}\cdot\overrightarrow{PD}=0$，所以 $BM\perp PD$。

**解：** 平面 $PBM$ 的法向量可取 $\mathbf n_1=(1,0,1)$；平面 $PDM$ 的法向量可取 $\mathbf n_2=(0,1,1)$。所以两平面的锐夹角余弦值为

$$
\cos\theta=\frac{|\mathbf n_1\cdot\mathbf n_2|}{|\mathbf n_1||\mathbf n_2|}=\frac12.
$$

</details>

**变式：** 若 $PA=4$，重算 $M(1,1,2)$，判断 $\overrightarrow{BM}\cdot\overrightarrow{PD}$ 是否为 $0$。

### 3. 动点参数与线面角

出处：近年新高考卷 · 解答题第2问　〔同考点改编〕

原题：正方体棱长为 $2$，点 $P$ 在线段 $A_1C_1$ 上，$P=A_1+t(C_1-A_1)$。若直线 $BP$ 与平面 $ADD_1A_1$ 所成角为 $30^\circ$，求 $t$。

<details>
<summary>精讲</summary>

**解析：** 用参数式写 $P(2t,2t,2)$ 并注明 $0\le t\le1$；由线面角公式列方程解 $t$，最后检验范围。

**解：** 取 $A(0,0,0)$，$B(2,0,0)$，$D(0,2,0)$，$A_1(0,0,2)$，则 $C_1(2,2,2)$。由题意得 $P(2t,2t,2)$，$0\le t\le1$。平面 $ADD_1A_1$ 的法向量为 $\mathbf n=(1,0,0)$，$\overrightarrow{BP}=(2t-2,2t,2)$。

因为线面角为 $30^\circ$，所以

$$
\frac{|\overrightarrow{BP}\cdot\mathbf n|}{|\overrightarrow{BP}||\mathbf n|}
=\frac{|2t-2|}{\sqrt{(2t-2)^2+(2t)^2+4}}
=\frac12.
$$

化简得 $t^2-3t+1=0$。结合 $0\le t\le1$，故 $t=\dfrac{3-\sqrt5}{2}$。

</details>

**变式：** 角改为 $45^\circ$，则 $t=0$。

---

## 八、薄弱环节

暂无。学习中遇到的卡点、易错点随交流在此追加（此节默认空，动态更新）。

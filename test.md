# 近代物理筆記
## 狹義相對論
愛因斯坦假設
+ 光速恆定
+ 物理定律在不同慣性坐標系下成立


### 勞倫茲轉換
$\left\{
  \begin{array}{c}
  x^{'}=\gamma (x-vt)\\
  y^{'}=y\\
  z^{'}=z\\
  t^{'}=\gamma A
  \end{array}
\right.$

$\left\{
  \begin{array}{c}
  x=\gamma (x^{'}-vt^{'})\\
  y=y^{'}\\
  z=z^{'}\\
  t=\gamma B
  \end{array}
\right.$

由光速恆定，$x=ct$、$x^{'}=ct^{'}$可導出

$\left\{
  \begin{array}{c}
    ct^{'}=\gamma (ct-vt) \\
    ct=\gamma (ct^{'}-vt^{'}) \\
 \end{array}
\right.$
解得$\gamma=\dfrac{1}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
將$\gamma$帶回，得
$t^{'}=\dfrac{t-\dfrac{v^{2}}{c^{2}}x}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
$t=\dfrac{t^{'}+\dfrac{v^{2}}{c^{2}}x'}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
因此得到勞倫茲轉換：
$\left\{
 \begin{array}{c}
    x^{'}=\dfrac{x-vt}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}\\
    y^{'}=y\\
    z^{'}=z\\
    t^{'}=\dfrac{t-\dfrac{v^{2}}{c^{2}}}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}
 \end{array}
\right.$
### 長度收縮
$L=x'_{2}-x'_{1}=L_{0}$

$\Delta x'=\dfrac{\Delta x - v\Delta t}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
對在X坐標系的人而言，測量物體兩端之時間$\Delta t =0$，因此
$\Delta x=L_{0} \sqrt{1-\dfrac{v^{2}}{c^{2}}}$

### 時間膨脹
$\Delta t^{'}=\dfrac{\Delta t-\dfrac{v^{2}}{c^{2}}\Delta x}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
對X人而言 $\Delta x=0$
$\Delta t'=\dfrac {\Delta t}{\sqrt{1-\dfrac{v^{2}}{c^{2}}}}$
### 速度變化
速度 $\mu =\dfrac {\Delta x}{\Delta y}=\dfrac{\Delta x'+v \Delta t'}{\Delta t' + \dfrac{v}{c^{2}}\Delta x'}=\dfrac{\dfrac{\Delta x'}{\Delta t'}+v}{1+\dfrac{v}{c^2}\dfrac{\Delta x'}{\Delta t'}}=\dfrac {\mu'+v}{1+\dfrac {v}{c^2}\mu'}$
當 $\mu'=c$時
$\mu=\dfrac{c+v}{1+\dfrac{v}{c}}=c \qquad 光速守恆$
當 $v<<c \quad \mu=\mu'+v$
### 質能方程
著名的愛因斯坦質能方程
\begin{equation*}
  E = mc^2
\end{equation*}

$E^2=m^2c^4=m^2c^2(c^2+v^2-c^2)=m^2v^2c^2+m^2c^2(c^2-v^2)=m^2v^2c^+m^2c^4(1-\dfrac{v^2}{c^2})$
$\Longrightarrow E^2=P^2c^2+m_{0}^2c^4$
$\Longrightarrow E^2-c^2\vec{p}^2=m_0^2c^4 \qquad 其中 m_0為靜止質量$

而$m=\dfrac{m_0}{\sqrt{1- \dfrac {v^2}{c^2}}}$
## 黑體輻射
古典理論
\begin{equation}
 P_{\nu}(T)=\dfrac{8\pi \nu^2}{c^3}kT
\end{equation}
可看出隨著頻率變高，能量應該變高，但實驗結果並非如此。
因此，Plank假設光的能量$E=h\nu$，則
$\overline E(\nu)=\dfrac{\sum\limits_{n=0}^{\infty}\dfrac{nh\nu}{kT}e^{-nh\nu/kT}}{\sum\limits_{n=0}^{\infty}\dfrac{1}{kT}e^{-nh\nu/kT}}=\dfrac{h\nu}{e^{\frac{h\nu}{kT}}-1}$

得出

$P_{T}(\nu)=\dfrac{8\pi \nu^2}{c^3}\dfrac{h\nu}{e^{\frac{h\nu}{kT}}-1}$
將$\nu=c/\lambda$帶入，得樸朗克黑體輻射定律
\begin{equation}
    P_{T}(\nu)=\dfrac{8\pi \nu^2}{c^3}\dfrac{1}{e^{\frac{hc}{\lambda kT}}-1}
\end{equation}

造成如此差距的原因是能量是離散的，在波茲曼統計中，低能量(長波長)因為切得比較小，和波茲曼統計的曲線較為接近，畫出的黑體輻射曲線和實驗相符。但在高能量區域，能量切得比較大塊，誤差就變得很大，造成古典理論和實驗不符合。
## 波耳氫原子模型
透過實驗觀察發現原子光譜有以下規律
$\dfrac{1}{\lambda}=R(\dfrac{1}{n_1^2}-\dfrac{1}{n_2^2}) \qquad n_1=1,2,3,... \quad n_2=n_1+1,n_1+2,n_1+3,...$
因此波耳假設    $L=n\hbar=mvr \qquad n=1,2,3,...$
$F=\dfrac{1}{4\pi\epsilon_0}\dfrac{e^2}{r^2}=\dfrac{mv^2}{r}$
$\Longrightarrow \dfrac{1}{4\pi\epsilon_0}e^2=mv^2r=\nu n\hbar$
$\Longrightarrow v=\dfrac{e^2}{4\pi\epsilon_0rn\hbar} \qquad r_n=4\pi\epsilon_0 \dfrac{n^2\hbar^2}{me^2}$

$V=-\int_r^{\infty}\tfrac{e^2}{4\pi \epsilon_0r^2}\mathrm{d} r=\dfrac{-e^2}{4\pi\epsilon_0r}$
而$E=K+V=\dfrac {1}{2}mv^2-\dfrac{e^2}{4\pi\epsilon_0r}=-\dfrac{e^2}{4\pi\epsilon_0r}=-K$
$r_n=4\pi\epsilon_0 \dfrac{n^2\hbar^2}{me^2}帶入得$
\begin{equation}
 E=-\dfrac{me^4}{(4\pi\epsilon_0)^22\hbar^2}\dfrac{1}{n^2} \qquad n=1,2,3...
\end{equation}
氫原子的光譜能量為
\begin{equation}
 E_{nm}=-13.6eV(\dfrac{1}{n^2}-\dfrac{1}{m^2}) \qquad n=1,2,3...
\end{equation}
氫原子光譜的光則是電子吸收能量，跑到較高的能量位置，再掉回能量低的位置。根據前面的假設與推導，能量是離散的，電子只能待在特定能量位置，因此使氫原子的光譜不是連續的。
## 物質波
德布羅伊提出電子也許像光一樣具有波和粒子的性質，因此提出波長和動量間的關係
\begin{equation}
    \lambda=\dfrac{h}{p}
\end{equation}
1927年Davisson–Germer Experiment證明電子有波的性質
## 薛丁格方程式
\begin{equation}
-\frac{\hbar^2}{2m}\frac{\partial^2\Psi}{\partial x^2}+V\Psi=i\hbar\frac{\partial \Psi}{\partial t}
\end{equation}
推導:

令波函數$\Psi(x,t)=Ae^{i(kx-\omega t)}$

已知 $\lambda=\frac{h}{p} \quad \nu=\frac{E}{h} \qquad Total \ Energy \ E=\frac{p^2}{2m}+V$

$\dfrac{\partial \Psi}{\partial x}=ikAe^{i(kx-\omega t)}=ik\Psi(x,t)$

$\Longrightarrow -i\hbar \dfrac{\partial \Psi}{\partial x}=\hbar K\Psi(x,t)$

又$\hbar K=P \qquad \Longrightarrow P_{op}=-i\hbar\dfrac{\partial}{\partial x}$

同樣

$\dfrac{\partial \Psi}{\partial t}=-i\omega Ae^{i(kx-\omega t)}=-i\omega\Psi(x,t)$
$\Longrightarrow i\hbar\dfrac{\partial \Psi}{\partial t}=\hbar\omega\Psi(x,t)$
又$E=h\nu=\hbar 2\pi\nu=\hbar \omega$
$\Longrightarrow E_{op}=i\hbar\dfrac{\partial}{\partial t}$

$E=\dfrac{p^2}{2m}+V \qquad 左右同乘波函數$

$\Longrightarrow \dfrac{P_{op}^2}{2m}\Psi+V\Psi=E_{op}\Psi$

$\Longrightarrow -\dfrac{\hbar^2}{2m}\dfrac{\partial^2 \Psi}{\partial x^2}+V\Psi=i\hbar\dfrac{\partial \Psi}{\partial t}$
## 元素的週期性
1927包立發現**包立不相容原理**，只有一個電子能待在特定的量子狀態 $|\psi_{nlm}\rangle|S_z\rangle$
$Lowest \ state \ : \ n=1 \quad l=0 \quad m=0 \quad S_z=\pm \dfrac{1}{2} \qquad 一共2個State$
$2^{nd} \ lowest \ state:n=2 \quad l=0,1 \quad m=0,(-1,0,1) \quad S_z=\pm\dfrac{1}{2} \qquad 一共2+6=8個State$

包立不相容原理在量子力學中兩種粒子上：
+ Fermions:費米子有半整數的自旋，遵守包立不相容原理，包含電子、質子、中子
+ Bosons:有整數字旋，不用受包立不相容原理影響
## 全同粒子
全同粒子是指一群長得幾乎一樣、無法區分的粒子。以電子為例，當兩顆電子的波函數有重疊，且觀察到重疊區出現一顆電子，觀察者是無法分辨這顆電子屬於哪一個波函數。
$\begin{split} |\psi_{1,2}(r_1,r_2)\rangle&=\alpha|\psi_1(r_1)\rangle|\psi_2(r_2)\rangle+\beta|\psi_1(r_2)\rangle|\psi_2(r_1)\rangle \\ &= \gamma|\psi_{1,2}(r_2,r_1)\rangle = \gamma^2|\psi_{1,2}(r_1,r_2)\rangle \end{split}$
$\Longrightarrow \gamma^2=1 \qquad \gamma=\pm 1$
當$\gamma=1$時，波函數是對稱的。當$\gamma=-1$時，波函數是反對稱的。

對稱：
$|\psi_{1,2}(r_1,r_2)\rangle=|\psi_1(r_1)\rangle|\psi_2(r_2)\rangle+|\psi_1(r_2)\rangle|\psi_2(r_1)\rangle$

反對稱：
$\begin{split}|\psi_{1,2}(r_1,r_2)\rangle&=|\psi_1(r_1)\rangle|\psi_2(r_2)\rangle-|\psi_1(r_2)\rangle|\psi_2(r_1)\rangle \\ &=-|\psi_{1,2}(r_2,r_1)\rangle\end{split}$

當波函數示反對稱時，若$r_1=r_2$，則
$|\psi_{1,2}(r_1,r_1)\rangle=0 \qquad \Longrightarrow 包立不相容原理$

因此，對於n個全同粒子，
$\psi(r_1,r_2,r_3,...r_i...r_j...r_n)=\pm\psi(r_1,r_2,r_3,...r_j...r_i...r_n)$

$\begin{cases}
Bosons 	\Rightarrow Wavefunction \ are \ symetric \\
Fermions 	\Rightarrow Wavefunction \ are \ anti-symmetric
\end{cases}$
## 狄拉克方程式
由於薛丁格方程式並沒有引入相對論。因此要導入愛因斯坦方程式：
\begin{equation}
E^2-c^2\vec{p}^2=m_0^2c^4
\end{equation}
同乘波函數得
$(E^2-c^2\vec{p}^2)\Psi(r,t)=m_0^2c^4\Psi(r,t)$
Operator $E=i\hbar\dfrac{\partial}{\partial t} \qquad p=-i\hbar \vec{\nabla}$
$\hbar=1 \qquad c=1$
得到Klein-Gordon equation
\begin{equation}
(\dfrac{\partial^2}{\partial t^2}-\nabla^2)\Psi(r,t)=-m_0^2\Psi(r,t)
\end{equation}

狄拉克設$E=c\vec{\alpha}\cdot\vec{p}+\beta m_0c^2 \qquad \vec{\alpha}\cdot\vec{p}=\alpha_1 p_1+\alpha_2 p_2+\alpha_3 p_3$
$\Longrightarrow E^2=(c\vec{\alpha}\cdot\vec{p}+\beta m_0c^2)^2=m_0^2c^4$

$\Longrightarrow \left \{
 \begin{array}{c}
    \vec{\alpha}\cdot\vec{\alpha}=1 \\
    \alpha_i \cdot \alpha_j=-\alpha_j \cdot \alpha_i \quad i,j=x,y,z \\
    \beta^2=1 \\
    \vec{\alpha}\beta=-\beta\vec{\alpha}
 \end{array}
\right.$

$\Longrightarrow \vec{\alpha} \ 、 \ \beta \quad must \ be \ matrixs$

經過計算，得
$\beta=\begin{pmatrix}
    1 & 0 & 0 & 0 \\
    0 & 1 & 0 & 0 \\
    0 & 0 & 1 & 0 \\
    0 & 0 & 0 & -1
\end{pmatrix} \quad 
\alpha_1=\begin{pmatrix}
    0&0&0&1\\
    0&0&1&0\\
    0&1&0&0\\
    1&0&0&0
\end{pmatrix} \quad
\alpha_2=\begin{pmatrix}
    0&0&0&i\\
    0&0&i&0\\
    0&-i&0&0\\
    -i&0&0&0
\end{pmatrix} \quad
\alpha_3=\begin{pmatrix}
    0&0&1&0\\
    0&0&0&-1\\
    1&0&0&0\\
    0&1&0&0
\end{pmatrix}$

因此得到狄拉克方程式
\begin{equation}
i\hbar \ \dfrac{\partial}{\partial t}\Psi=( \ -i\hbar c\vec{\alpha}\cdot\vec{\nabla}+\beta \ m_0 c^2 \ )\Psi
\end{equation}

在解方程式時會發現
$粒子能量 \ E=\pm \sqrt{p^2c^2+m_0^2c^4} \qquad 但粒子不能帶有負能量$

因此，狄拉克提出了狄拉克之海的概念。他假設所有負能量的state已被反粒子佔據，整齊排列，構成狄拉克之海，因此是觀測不到的。 同時，若有一束高能量的光(如:宇宙射線)打中狄拉克之海的反粒子，使其能量提升，而留下一個洞，這就是觀察到的反粒子。

雖然狄拉克之海的理論有所缺陷，但從其中預測反粒子的存在。1932年安德森透過實驗發現正子，證實反粒子的存在。


反粒子的特性
+ 和其對應的粒子有相同的 **自旋**、**質量**
+ 帶電量相反


## 物理學分類
### 古典物理學
+ 力學：分析力學 Lagrange&Hamiltonian
+ 電磁學：電動力學 Maxwell理論 
+ 熱力學：統計力學 波茲曼理論
### 近代物理
\begin{cases}
分析力學 \ + \ 量子論  \ \Rightarrow 量子力學\\
電動力學 \ + \ 量子論 \ + \ 相對論 \  \Rightarrow 量子電動力學\\
統計力學 \ + \ 量子論 \ \Rightarrow量子統計力學 \Rightarrow Bose、Femi統計
\end{cases}
以上三者結合相對論$\Rightarrow \ 量子場論$

二十世紀50年代後物理學
\begin{array}{|c|c|c|}
粒子物理&凝態物理&量子資訊\\
\hline
基本粒子、           &物質結構         &Atomic \ optical的應用\\
基本粒子相互作用&     電、磁、光、熱\\
\downarrow       &\downarrow       &\downarrow\\
標準模型、宇宙學    &超導、霍爾效應、    &固態物理的應用\\
                 &Topolgy  \ of  \ phases       &資訊的量子理論
\end{array}

## 粒子物理
### 輕子(Leptons)：
\begin{matrix}
    &&&Charge&Spin\\
    e&\mu&\tau& -&\frac{1}{2} \\
    \nu_e&\nu_\mu&\nu_\tau &0 &\frac{1}{2}
\end{matrix}
不參與強相互作用

### 夸克(Quarks):
\begin{matrix}
    &&& Charge & Spin\\
    u & c & t &\frac{2}{3} &  \frac{1}{2}\\
    d & s & b &-\frac{1}{3} & \frac{1}{2}
\end{matrix}
參與強相互作用

介子(meson)：$\pi \quad \kappa \quad\rho\quad\psi \quad D \quad B\Rightarrow quark \ + \ antiquark$
重子(Baryon)：$\underbrace{p\quad n}_{spin \ \frac{1}{2}}\quad \underbrace{\Lambda\quad\Sigma\quad\Xi\quad\Omega}_{spin \ \frac{3}{2}\quad 超子} \Rightarrow \ quark_1 \ + \ quark_2 \ + \ quark_3$
$\Longrightarrow Quantum \ Chromodynamic(QCD)$
$QCD\rightarrow su(3) \ gauge \ symmetry$

原子核中：

$P:\overbrace{uud}^{\frac{2}{3}+\frac{2}{3}-\frac{1}{3}=1e} \qquad
n:\overbrace{uud}^{\frac{1}{3}+\frac{1}{3}-\frac{2}{3}=0}$

$\Longrightarrow introduce \ a \ new \ degree： \ isotopic \ spin \ (isospin)$
$核子\begin{cases}
n\\
\qquad isotopic \ spin \ 皆為\dfrac{1}{2}\\
p
\end{cases}$

$\Sigma \begin{cases}
\Sigma^+ \quad電荷 \ 1\\
\\
\Sigma^0 \quad電荷 \ 0 \qquad isotopic \ spin \ 1\\
\\
\Sigma^- \quad電荷 \ -1
\end{cases}$

夸克：
$spin\dfrac{1}{2}\quad\Rightarrow \ Fermion\quad波函數是anti-symmetric\\isospin=\dfrac{1}{2} \ or \ -\dfrac{1}{2}\\
Colors：Red,\ Green,\ Blue$

如果只有強相互作用，isospin 守恆

### 分類：

重子
![](https://i.imgur.com/9Smpt0J.png)

$\dfrac{3}{2} \ isospin \ 強子 \Rightarrow su(3)$
![](https://i.imgur.com/CdwzaUC.png)

Mesons:
![](https://i.imgur.com/m2sGKgH.png)


### 相互作用
物質之間的相互作用有四種
+ 重力
+ 電磁作用力 spin + e ( u(1) ) 由光子傳遞
+ 弱作用力 su(2)
+ 強作用力 su(3)

電磁作用力 弱作用力 強作用力 和guage symmetry 有關
重力目前無法被整合進來

#### 強作用力
由強子參與，強子包含重子和介子，而強子是由夸克構成。由八種膠子(gluon)在夸克之間傳遞
#### 弱作用力
由$W^+, \ W^-, \ Z玻色子傳遞$

## 固態物理與凝態物理
物質有基本的三相 ：
+ 氣態
+ 液態
+ 固態

Landau提出phase transition (相變)是因為對稱性的破壞
從原子物理的角度去探討物質的相$\Rightarrow 固態物理 \ + \ 凝態物理$
### 固態物理
$1930's\begin{cases}
Lattice \ Structure\\
Band \ Structure\\
Single \ electron\Rightarrow Physics \ properties
\end{cases}$

固態物理討論的是原子數量$\ge 10^{23}$的Many-Body system

牽扯到的作用力：
\begin{cases}
electron\leftrightarrow nucleus:吸引力 \Rightarrow \left\{ \begin{array}{c}
exchange \ energy\\
van \ der \ Waal's \ forces\\
Covalent \ Bond \ (共價鍵)
\end{array}
\right.\\
electron\leftrightarrow electron:排斥立\\
nucleus\leftrightarrow nucleus:排斥立
\end{cases}

這些作用力和原子的結構有關
如:Ne Ar Kr Xe等元素，其外層電子被填滿$\Rightarrow 不容易有交互作用$
若兩原子之間沒有重疊部分$\Rightarrow liquid/gas$
有部分重疊到$\Rightarrow Covalent \ Bond,\ exchange \ energy, \text{diple-diple} \ interaction\Rightarrow van \ der \ Waal's \ forces$

外層電子沒有填滿$\Rightarrow\text{electron move freely}\Rightarrow Metal$

在固態物理領域中，牽扯到的物質相互作用力為電磁力，對相互作用而言:
+ 重力：非常若，若將重力大小訂為1，則電磁力約為$10^{36}$
+ 強相互作用：這是在原子核中的力，不起作用
+ 若相互作用：能量太低，需要$Mev \sim GeV$之能量。固態物理的能量約為$eV \sim 10^{-3}eV$

#### 能帶理論
![](https://i.imgur.com/rfZukee.png)
$\Longrightarrow \text{lattice structure}\Rightarrow\text{periodic structure, discrete symmetrics}$

要知道材料的特性
$\Longrightarrow 找到此材料的\text{ Energy Band Structure}$

Landau:
\begin{cases}
\text{quasi-free electron approximation}\\
\text{Hantree-Fock approach}\\
\text{DFT (Density functional theory) 密度泛函理論}
\end{cases}

以上方法可以 very precisely determine the Band Structure

$\Longrightarrow \text{another important property}\\
\rightarrow \text{lattice}\rightarrow \text{lattice vibration}\rightarrow\hbar\omega_k\rightarrow\text{phonon (聲子)}$
### 凝態物理
Condense matter from sold-state physics
$\left\{
\begin{array}
\text{mean-field}\\
\text{residual interaction}\\
\text{combine electrons together}
\end{array}
\right.$

electron-electron residual -> electron photon & electron phonon interaction
$\Longrightarrow \text{attractive force between electrons}$
Cooper pairs (電子結合在一起的狀態) dancing without colliion $\Rightarrow 
\text{no resistor}$

$\Longrightarrow 超導體$

1930's $\sim$ 1950's $Landau$ 研究 ion physic, Liquid mechanics, nucleus physic, field theory....

最引人注目的貢獻是
+ 二級相變
+ 超導理論
+ 超流(氦II)理論
+ Fermi liquid theory
引入新概念
+ quasi excitation
+ order parameter
## 量子資訊
### 古典資訊的bit
採用bit儲存、運算，一個bit一定是0或是1，一組bits一次只能表達一個數字
### 量子資訊的bit : qubit
$........\text{Excited state}|1\rangle\\ \quad$
$\downarrow\qquad\uparrow \qquad\leftarrow\sim\sim light\\\quad$
$........\text{Ground state}|0\rangle$

$\Longrightarrow|\Psi\rangle=\alpha|0\rangle+\beta|1\rangle\qquad \text{Quantum Superposistion}\rightarrow \text{qubit}$

### qubit vs bit
![](https://i.imgur.com/AOxMTXU.png)

古典的bit只能使0或1，只有兩種狀態
qubit由於是$|0\rangle$和$|1\rangle$的疊加
$\begin{aligned}
\rightarrow |\Psi\rangle &=\alpha|0\rangle+\beta|1\rangle =\alpha|\uparrow \ \rangle+\beta |\downarrow \ \rangle
\\ &=\cos \frac{\theta}{2}|0\rangle+\sin \frac{\theta}{2}e^{i\phi}|1\rangle\\
&=|\theta,\phi\rangle
\end{aligned}$
如下圖所示

![](https://i.imgur.com/beDv4dA.png)

因此在二為求面上每一點都是一個qubit state，也就是說有無限多個state

以3個bit和qubit為例：
classical bit 一次只能表示 000, 001, 010, 011, 100, 101, 111其中一種狀態
但對於qubit而言，每個可表示成$|\Psi\rangle=\alpha|0\rangle+\beta|1\rangle \quad \text{quantum superposition}$
$\text{e.g.  }|\Psi\rangle=\dfrac{1}{\sqrt{2}}(|0\rangle+|1\rangle)$
$\Rightarrow |\Psi_1\rangle \ |\Psi_2\rangle \ |\Psi_3\rangle= [ \dfrac{1}{\sqrt{8}}(|0\rangle+|1\rangle) ]^3=\dfrac{1}{\sqrt{8}}(|000\rangle+|001\rangle+|010\rangle+...+|111\rangle)$

$\Longrightarrow \text{N qubits} \rightarrow (|\Psi_i\rangle)^N=\dfrac{1}{\sqrt{2^N}}(\underbrace{|00...0\rangle}_{N個}+\underbrace{|00...1\rangle}_{N個}...+\underbrace{|11...1\rangle}_{N個})$

因此，一組N個qubit可以同時表示 $2^N\text{states}$
### 量子位元的運作 -> 使用量子閘
量子位元的運算需要使用量子閘，一般而言，需要2-single qubit rotation gate 和2-qubit control gate即能完成對qubit的運算

$|q\rangle=\alpha|0\rangle+\beta|1\rangle\rightarrow |q\rangle=\alpha'|0\rangle+\beta'|1\rangle\\
\Longrightarrow\cos\dfrac{\theta}{2}|0\rangle+\sin\dfrac{\theta}{2}e^{i\phi}\rightarrow \cos\dfrac{\theta'}{2}|0\rangle+\sin\dfrac{\theta'}{2}e^{i\phi'}$

基本上可想成對於球面的兩個方向旋轉

$\left\{
\begin{array}{c}
x-gate:\theta\rightarrow\theta'\\
z-gate:\phi\rightarrow\phi'\\
control\ gate:\ |q_1q_2\rangle\rightarrow|q_1'q_2'\rangle
\end{array}
\right.$

因此有以下幾種量子閘，並以矩陣表示：

$|0\rangle=\begin{pmatrix}
1\\0
\end{pmatrix} \qquad 
|1\rangle=\begin{pmatrix}
0\\1
\end{pmatrix}$

#### Hadmard gate:(查到的和老師上課的有些不同)
$H=\dfrac{1}{\sqrt{2}}\begin{pmatrix}
1&1\\
1&-1
\end{pmatrix} \quad 
H|0\rangle=\dfrac{|0\rangle+|1\rangle}{\sqrt{2}}\quad
H|1\rangle=\dfrac{|0\rangle-|1\rangle}{\sqrt{2}}$

3-qubit $|000\rangle$
$\Longrightarrow H^{\otimes3}|000\rangle=(\dfrac{|0\rangle+|1\rangle}{\sqrt{2}})^3=\dfrac{1}{\sqrt{8}}(|000\rangle+|001\rangle...+|111\rangle)$
#### T gate
$T=\begin{pmatrix}
1&0\\
0&e^{-i\frac{\pi}{8}}
\end{pmatrix}$

#### Control gate : CNOT gate (Control Not gate)
用第1個qubit控制第2個qubit

$CNOT=\begin{pmatrix}
1&0&0&0\\
0&1&0&0\\
0&0&0&1\\
0&0&1&0
\end{pmatrix}$

$\text{before}\begin{array}{c|c}
qubit_1&qubit_2\\
\hline\\
|0\rangle&|0\rangle\\
|0\rangle&|1\rangle\\
|1\rangle&|0\rangle\\
|1\rangle&|1\rangle
\end{array} \overset{\text{CNOT gate}}{\Longrightarrow} \text{after}\begin{array}{c|c}
qubit_1&qubit_2\\
\hline\\
|0\rangle&|0\rangle\\
|0\rangle&|1\rangle\\
|1\rangle&|1\rangle\\
|1\rangle&|0\rangle
\end{array}$

將以上的gate進行組合可以得到量子電路

量子計算強大之處在於有以下 **Quantum Properties**:
+ Quantum Coherence
+ Quantum Entaglement

因此，進行量子計算時可以同時輸入所有input，並且平行的一次計算完所有結果，也就是說，量子電腦可能是non-deterministic turing machine的一種實現方式。

### Readout
讀取與測量是量子運算領域中最困難的部分

原本的測量前的狀態為$|\Psi\rangle=\alpha_1|\Psi_1\rangle+\alpha_2|\Psi_2\rangle...+\alpha_n|\Psi_n\rangle$
經過一次測量得$A|\Psi_i\rangle=\alpha_i|\Psi_i\rangle$，每一次測量都只能得到其中一個state。
當測量$|\Psi\rangle$很多次，得$\langle A\rangle=\sum\limits_{i}a_i N_i/N$
且一次測量會將狀態從$|\Psi\rangle\rightarrow|\Psi_i\rangle$，因此人們試著發展非破壞性測量。

### 量子電腦最大的問題
由於人們構建的量子電腦是open quantum system，因此qubit會和環境互動，進而產生 dissipation(耗散)、noise(漲落)，使得量子計算的兩大特性之一 coherence消失。


用薛丁格的貓來理解測量和外界干擾對於量子狀態的影響。當箱子封閉，系統是獨立時，貓處於$|活貓\rangle+|死貓\rangle\ \ 的疊加狀態$，當我們打開箱子測量，或箱子破了，那人們只會發現貓處於$|活貓\rangle或|死貓\rangle \ \text{其中一種狀態，失去了coherence特性}$

## 對稱性
在物理學中，對稱性是十分重要的一環。對稱性的成立與破壞構造了物理規則。
\begin{array}{|c|c|c|}
\text{數學變換}&\text{不可觀察量}&守恆定律\\
\hline\\
\text{空間平移}&\vec{r}\rightarrow\vec{r}+\vec{\Delta}\ \text{絕對空間位置}&動量守恆\\
\text{時間平移}&t\rightarrow t+\Delta t\ \text{絕對時間}&\text{能量守恆}\\
\text{旋轉}&\vec{r}\rightarrow\vec{r'}\ \text{絕對空間方向}&\text{角動量守恆}\\
\text{空間反演}&\vec{r}\rightarrow -\ \vec{r'}\ \text{絕對左右}&\text{宇稱守恆}\\
\text{粒子-反粒子共軛}&t\rightarrow -t\text{絕對未來(過去)}&\text{電荷共軛守恆+T}\\
&e\rightarrow eT&\\
\text{粒子置換守恆}&全同粒子(不可區分)&\text{Bose&Einstein Statistics}\\
\text{規範對稱}&\Psi\rightarrow e^{i\phi}\Psi\text{}&電荷守恆
\end{array}

因此，不可觀察的結果導致守恆量，而一旦不可觀察量可以測量，對稱性就破壞。舉個簡單的例子，一個對稱的圖案，如：$\bigotimes$是無法分店哪邊是左或右，如果右下角有一個數字，$\bigotimes_1$，就可分辨有1是一邊，沒1是一邊，此圖形就沒有對稱性。

對稱性的破壞也會產生物理現象，在凝態物理中如下：
+ 空間反演對稱性的破壞$\rightarrow$鐵電物質
+ 時間反演對稱性$\rightarrow$磁$\rightarrow$有序結構
+ 規範對稱性破壞$\rightarrow$超導體、超流體

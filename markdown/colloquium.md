1.1.$Опр. инт. суммы\ Римана\ и\ инт–а\ Римана.$
$[a,b]\in\mathbb{R},a=x_{0}<x_{1}<...<x_{n-1}<x_{n}=b,,P=P_{[a,b]}=\{ x_{k} \}^n_{k=0}-разбение\ [a,b]$
$\Delta_{k}=[x_{k-1},x_{k}],\Delta x_{k}=x_{k}-x_{k-1}, (k=1,...,n).d=d(P)=max_{1\leq k\leq n}\Delta x_{k}–диаметр$
$разб–я\ P.\ \xi_{P}=\{ \xi_{k} \}^n_{k=1},\xi_{k}\in\Delta_{k},(k=1,...,n)–сист.промеж.точек,соотв.разб–ю\ P.$ |
$Пусть\ f\ опр.на\ [a,b]. Сумма\ \sigma(P)=\sigma(P,\xi_{P})=\sigma(f,P,\xi_{P})=\Sigma^n_{k=1}f(\xi_{k})\Delta x_{k}\ наз.инт.суммой$
$Римана\ ф–ции\ f.$|$I=\lim_{ d \to 0 }\sigma(P),если\ \forall\epsilon>0\exists\delta>0\forall(P,\xi_{P})\ (d(P)<\delta\Rightarrow |\sigma(P,\xi_{P})-I|<\epsilon).$
$Число\ I\ наз.пределом\ инт.сумм\ Римана.\ f в\ этом\ случ.наз.инт.по\ Риману\ на\ [a,b],а\ I–инт.$
$Римана\ и\ обозн.\int_{a}^bf(x)dx=I$
1.2.$Т.(Необход.условие\ интегрируемости\ ф–ции):f–инт.на[a,b]\Rightarrow f\ огр.на[a,b]$

2.1.$Верхние\ и\ нижние\ суммы\ Дарбу,\ их\ свойства.$
$Пусть\ f\ опр.и\ огр.на[a,b],P=\{ x_{k} \}^n_{k=0},M_{k}=sup_{x\in\Delta k}f(x),m_{k}=inf_{x\in\Delta k}f(x),1\leq k\leq n,$
$S(P)=\Sigma^n_{k=1}M_{k}\Delta x_{k}-верх.сум.Дарбу,s(P)=\Sigma^n_{k=1}m_{k}\Delta x_{k}-ниж.сум.Дарбу$|$\forall \xi_{P},$
$\forall k:1\leq k\leq n,\ m_{k}\leq f(\xi_{k})\leq M_{k}.$$Св–ва:1)\forall P\ \forall \xi_{P}\ s(P)\leq\sigma(P,\xi_{P})\leq S(P).2)Если\ P\subset P_{1},$
$то\ s(P)\leq s(P_{1}),S(P)\geq S(P_{1}).3)\forall P_{1}\ \forall P_{2}\ s(p_{1})\leq S(P_{2}).След–е:\{s(P)\}огр.сверху,$
$\{S(P)\}огр.снизу.4)\forall P\ \forall\epsilon>0\ \exists \xi_{P},\ 0\leq S(P)-\sigma(P,\xi_{P})<\epsilon\ (0\leq\sigma(P,\xi_{P})-s(P)<\epsilon)$
$След–е:S(P)=sup_{\xi_{p}}\sigma(P,\xi_{p}),s(P)=inf_{\xi_{p}}\sigma(P,\xi_{P})$ 
2.2.$Верхний\ и\ нижний\ интегралы.$
$Верх.инт.Дарбу:\overline{I}:=inf_{P}S(P),ниж.инт.:\underline{I}:=sup_{P}s(P).\underline{I}\leq \overline{I}.Лемм.:Пусть\ P=P_{[a,b]},$
$d=d(P)–диам.разб–яP,P*получено\ из\ P,добавл–ем\ L\ точек,M=sup_{x\in[a,b]}f(x),m=$
$=inf_{x\in[a,b]}f(x)\Rightarrow S(P)-S(P*)\leq(M-m)Ld, s(P*)-s(P)\leq(M-m)Ld.$
2.3.$Основная\ лемма\ Дарбу.$
$\overline{I}=\lim_{ _d(p)_ \to 0 }\underline{S}(P),\underline{I}=\lim_{ d(P) \to 0 }s(P),S(P)=s(P)=\sigma(P)=c(b-a)=\underline{I}=\overline{I}=I.$

3.$Критерий\ интегрируемости$
$Пусть\ f\ опр.и\ огр.на[a,b].Тогда\ след.усл–я\ эквивалентны:$
$1)f\ инт.на[a,b],\ 2)\forall\epsilon>0\ \exists P\ s(P)-S(P)<\epsilon,\ 3)\underline{I}=\overline{I}=\int_{a}^bf(x)dx.$

4.1.$Теорема\ об\ интегрируемости\ непрерывной\ функции$
$f\ непр.на[a,b]\Rightarrow f\ инт.на[a,b].$
4.2.$Теорема\ об\ интегрируемости\ монотонной\ функции$
$f\ монот.на[a,b]\Rightarrow f\ инт.на[a,b].$

5.1.$Св–ва\ инт.\ Рим.: линейн–сть\ инт–а, аддит–сть\ инт.\ относит. пред.\ инт–я, монотон–сть\ инт.$
$Т.(Лин–сть\ инт.):f,g\in\mathfrak{R}[a,b],c\in\mathbb{R}\Rightarrow f+g,cf\in\mathfrak{R}[a,b],\ \int_{a}^b(f(x)+g(x))dx=\int_{a}^bf(x)dx+\int_{a}^bg(x)dx$
$и\ \int_{a}^bcf(x)dx=c\int_{a}^bf(x)dx.$|$Т.(Адд–сть\ инт.):Пусть\ a<c<b,тогда\ f\in\mathfrak{R}[a,b]\Leftrightarrow f\in\mathfrak{R}[a,c]$
$и\ f\in\mathfrak{R}[c,b],\int_{a}^bf(x)dx=\int_{a}^cf(x)dx+\int_{c}^bf(x)dx.$|$Т.(Мон–сть\ инт.):f,g\in\Re[a,b],\forall x\in[a,b]\ f(x)\leq g(x)$
$\Rightarrow\int_{a}^bf(x)dx\leq\int_{a}^bg(x)dx.$|$След–е\ 1:f\in\Re[a,b],\forall x\ f(x)\geq0\Rightarrow\int_{a}^bf(x)dx\geq0.След–е\ 2:f\in\Re[a,b]\Rightarrow$
$\Rightarrow |\int_{a}^bf(x)dx|\leq\int_{a}^b|f(x)|dx\leq sup_{x\in[a,b]}|f(x)|(b-a)$
5.2.$Т.(Первая\ Т. о\ среднем\ для\ интеграла.):f,g\in\Re[a,b],g(x)\geq0\ (g(x)\leq0)\ \forall x\in[a,b],$
$M=sup_{x\in[a,b]}f(x),m=inf_{x\in[a,b]}f(x)\Rightarrow \exists \mu\in[m,M]:\int_{a}^bf(x)g(x)dx=\mu\int_{a}^bg(x)dx.$
5.3.$Т.(Операции\ над\ интегрируемыми\ функциями):$
$f,g\in\Re[a,b]\Rightarrow |f|,f\cdot g\in\Re[a,b], \frac{f}{g}\in\Re[a,b]\ при\ усл.\exists c>0\ \forall x\in[a,b]\ |g(x)|\geq c.$
$Замеч–е:Из\ инт–сти\ |f|\ не\ следует\ инт–сть\ f.$

6.$Непрерывность\ интеграла\ по\ верхнему\ пределу\ интегрирования.$
$f\in\Re[a,b]\Rightarrow F(x)=\int_{a}^xf(t)dt\ непр.на[a,b].$

7.$Дифф–сть\ интеграла\ по\ верхнему\ пределу\ интегрирования.Ф–ла\ Ньютона–Лейбница$
$f\in \Re[a,b]\ непр.в\ т.\ x_{0}\in[a,b]\Rightarrow F(x)=\int_{a}^xf(t)dt\ дифф. в\ т.\ x_{0}\ и\ F'(x_{0})=f(x_{0}).$
$Т.(Ф–ла\ Н–Л): f\ непр.на\ [a,b]\Rightarrow \int_{a}^bf(x)dx=\Phi(b)-\Phi(a), где\ \Phi - произвольн. первообразная\ f$

8.$Интегрирование\ по\ частям\ и\ замена\ переменной\ в\ интеграле\ Римана.$
$Т.(Ф–ла\ инт–я\ по\ частям):u(x), v(x)\ непр.дифф.на\ [a,b]\Rightarrow\int_{a}^bu(x)v'(x)dx=u(x)v(x)-\int_{a}^bv(x)u'(x)dx$
$Т.(Ф–ла\ замены\ перем.):f\ непр.на\ [a,b],\ g\ имеет\ непр.производную\ на\ [\alpha,\beta],\ min_{t\in[\alpha,\beta]}g(t)=g(\alpha)=a,$
$max_{t\in[\alpha,\beta]}g(t)=g(\beta)=b\Rightarrow \int_{a}^bf(x)dx=\int_{\alpha}^\beta f(g(t))\cdot g'(t)dt$

9.1.$Несобств. инт. Римана\ 2–х\ типов\ и\ их\ простейш. св–ва.\  Крит. Коши\ сход–ти\ несобств. инт.$
$Пусть\ f\ опр.на\ [a,+\infty), \forall b\in[a,+\infty)\ f\in\Re[a,b].\ \lim_{ b \to +\infty }\int_{a}^bf(x)dx\ наз.несобств.инт.1–го\ рода,$
$если\ он\ сущ.и\ конечен.Обозн.:\int_{a}^{+\infty}f(x)dx.\ При\ этом\ несобств.инт.сходится.\ Аналогично$
$определяют\ \int_{-\infty}^bf(x)dx.$|$Пусть\ f\ опр.на\ [a,B), неогр.в\ O(B)\ и\ \forall b\in[a,B)\ f\in\Re[a,b].$
$\lim_{ b \to B-0 }\int_{a}^bf(x)dx,наз.несобств.инт.2–го\ рода, если\ он\ сущ.и\ конечен.Обозн.:\int_{a}^Bf(x)dx.$
$При\ этом\ несобств.инт.сход.$|$Пусть\ f\ опр.на\ [a,\omega)\ и\ \forall[a,b]\subset[a,\omega)\ f\in\Re[a,b]. Тогда:\int_{a}^\omega f(x)dx:=$
$:=\lim_{ b \to \omega }\int_{a}^bf(x)dx.$
9.2.$Т.(Свойства\ несобст. интеграла\ Римана.):\int_{a}^\omega f(x)dx\ и\ \int_{a}^\omega g(x)dx\ сход.,тогда:$
$a)\omega\in\mathbb{R},\ f\in\Re[a,\omega]\Rightarrowзнач–я\ \int_{a}^\omega f(x)dx\ в\ несобств.и\ собств.смысле\ равны.\ b)\forall\lambda_{1},\lambda_{2}\in\mathbb{R}$
$ф–ция\ \lambda_{1}f+\lambda_{2}g инт.в\ несобств.смысле\ и \int_{a}^\omega(\lambda_{1}f(x)+\lambda_{2}g(x))dx=\lambda_{1}\int_{a}^\omega f(x)dx+\lambda_{2}\int_{a}^\omega g(x)dx.$
$c)\ c\in [a,\omega)\Rightarrow \int_{a}^\omega f(x)dx=\int_{a}^cf(x)dx+\int_{c}^\omega f(x)dx.$|
9.3.$Т.(Критерий\ Коши\ сходимости\ несобственного\ интеграла):$
$\int_{a}^\omega f(x)dx\ сход. \Leftrightarrow \forall\epsilon>0\ \exists B\in[a,\omega)\ \forall b_{1},b_{2}\in(B,\omega)\ |\int_{b_{1}}^{b_{2}}f(x)dx|<\epsilon.$ 

10.1.$Абс. сход–ть\ несобст. инт., связь\ со\ сход–ю.$
$\int_{a}^\omega f(x)dx\ абс.сход.\ если\ \int_{a}^\omega |f(x)|dx\ сход.$|$Т.(О\ сход–ти\ абс.сход.инт.):$
$\int_{a}^\omega f(x)dx\ абс.сход.\Rightarrow\ он\ сход.$|$Т.\ \exists \lim_{ b \to \omega }F(b)\ конечен\Leftrightarrow F\ огр.на\ [a,\omega).$
10.2.$Т.(Признак\ мажорации):\forall x\in[a,\omega)\ 0\leq f(x)\leq g(x)\ и$
$\int_{a}^\omega g(x)dx\ сход.\Rightarrow \int_{a}^\omega f(x)dx\ сход.\ Если\ \int_{a}^\omega f(x)dx\ расход.\Rightarrow \int_{a}^\omega g(x)dx\ расход.$
10.3.$Т.(Призн.сравн–я\ сход–ти):\forall x\in[a,\omega)\ f(x)\geq0, g(x)\geq0\ и\ \lim_{ x \to \omega }(f(x)/g(x))=$
$=A,\ 0<a<+\infty\Rightarrow \int_{a}^\omega f(x)dx\ и\ \int_{a}^\omega g(x)dx\ одновременно\ сход.или\ расход.$

11.1.$Условная\ сходимость\ несобственных\ интегралов.$
$инт.\int_{a}^\omega f(x)dx\ наз.усл.сход.,если\ он\ сход.,а\ \int_{a}^\omega |f(x)|dx\ расход.$|$Пусть\ f,g,g'\ непр.на [a.\omega),$
$F(b)=\int_{a}^b f(x)dx.\ Тогда\ по\ ф–ле\ инт.по\ частям:\int_{a}^b f(x)g(x)dx=g(b)F(b)-g(a)F(a)-$
$-\int_{a}^b g'(x)F(x)dx.\ Если\ сущ. \int_{a}^\omega g'(x)F(x)dx=A\ и\ сущ.конеч.\ \lim_{ b \to \omega }g(b)F(b)=B,\ то$
$сущ.несобст.инт.\ \int_{a}^\omega f(x)g(x)dx=B-g(a)F(a)-A.$
11.2.$Т.(Признак\ Дирихле\ сход–ти\ несобст. инт–ов.):f,g,g'\ непр.на\ [a,\omega),\ F(b)=\int_{a}^b f(x)dx$
$огр.на\ [a,\omega),\ g(x)\to0\, монотон.убывая, при\ x\to\omega\Rightarrow \int_{a}^\omega f(x)g(x)dx\ сход.$
11.3.$Т.(Признак\ Абеля\ сход–ти\ несобст. инт–ов.):f,g,g'\ непр.на\ [a,\omega),$
$инт. \int_{a}^\omega f(x)dx\ сход.,\ g\ монотонна\ и\ ограничена\ на\ [a.\omega)\Rightarrow \int_{a}^\omega f(x)g(x)dx\ сход.$

12.1.$Числовой\ ряд, сумма\ ряда, сходимость\ числового\ ряда.$
$Числовой\ ряд\ \Sigma a_{n}-это\ посл–ть\ (S_{n}),\ a_{n}-n–ый\ член\ ряда,\ S_{n}-n–ая\ частичн.сумма\ ряда,$
$S_{n}=\Sigma_{k=1}^n a_{k}, n\in\mathbb{N}.$|$S=\Sigma_{n=1}^\infty a_{n} - сумм.ряда.Если\ S\in\mathbb{R},то\ ряд\ наз.сход.\ Если S = \pm \infty,$
$или\ \lim_{ n \to \infty }S_{n}\ не\ сущ.\ то\ ряд\ расход.$
12.2.$Т.(Необх. усл. сход–ти\ ряда.):\Sigma a_{n}\ сход. \implies\lim_{ n \to \infty }a_{n}=0,\ т.е.\ a_{n}=o(1).$ 
12.3.$Т.(Крит. Коши\ сход–ти\ числ. ряда.):\Sigma a_{n}\ сход.\Longleftrightarrow\forall\epsilon>0\ \exists n_{\epsilon}\in\mathbb{N}\ \forall n\geq n_{\epsilon}\ \forall p\in\mathbb{N}$
$|S_{n+p}-S_{n}|<\epsilon,\ т.е.|\Sigma_{k=n+1}^{n+p}a_{k}|<\epsilon.$ 

13.1.$Т.(об\ арифметических\ действиях\ над\ сходящимися\ рядами.)$
$\Sigma a_{n}\ и\ \Sigma b_{n}\ сход., \Sigma_{n=1}^\infty a_{n}=A,\ \Sigma_{n=1}^\infty b_{n}=B,\ \lambda\in\mathbb{R}\implies\Sigma(a_{n}+b_{n})\ и\ \Sigma\lambda a_{n}\ сход.\ и$
$\Sigma_{n=1}^\infty(a_{n}+b_{n})=A+B,\ \Sigma_{n=1}^\infty\lambda a_{n}=\lambda A.$
13.2.$Абсолютная\ сходимость\ числовых\ рядов,\ связь\ со\ сходимостью.$
$\Sigma a_{n}\ абс. сход.,если\ \Sigma |a_{n}|\ сход.\ Т.(о\ сход–ти\ абс.сход.ряда):\Sigma a_{n}\ абс.сход\Rightarrow\Sigma a_{n}\ сход.$

14.1.$Т.(Основной\ признак\ Вейерштрасса.)$
$\Sigma a_{n}\ (a_{n}\geq0)\ сход.\Longleftrightarrow S_{n}=O(1)$
14.2.$Т.(Интегральный\ признак\ сходимости.)$
$Пусть\ f\downarrow\ на\ [1,+\infty)\ и\ f(x)\geq0\ \forall x\in[1,+\infty).\ Тогда:\int_{1}^\infty f(x)dx\ сход.\Longleftrightarrow\Sigma f(n)\ сход.$

15.1.$Т.(Признак\ мажорации.)$$Опр.\ a_{n}=O(b_{n})\Leftrightarrow\exists C>0\ \forall n\in\mathbb{N}\ |a_{n}|\leq C|b_{n}|$
$Теорема.:\forall n\in \mathbb{N}\ a_{n}\geq 0,\ b_{n}\geq 0,\ a_{n}=O(b_{n}),\ \Sigma_{n=1}^\infty b_{n}<+\infty\Rightarrow\Sigma_{n=1}^\infty a_{n}<+\infty.$
$След.1:\forall n\in\mathbb{N}\ a_{n}\geq 0, b_{n}>0, \left( \frac{a_{n}}{b_{n}} \right)\ сход.,\ \Sigma_{n=1}^\infty b_{n}<+\infty\Rightarrow\Sigma_{n=1}^\infty a_{n}<+\infty.$
$След.2:\forall n\in\mathbb{N}\ a_{n}>0,\ b_{n}>0, \left( \frac{a_{n+1}}{a_{n}} \right)\leq\left( \frac{b_{n+1}}{b_{n}} \right),\ \Sigma_{n=1}^\infty b_{n}<+\infty\Rightarrow\Sigma_{n=1}^\infty a_{n}<+\infty.$
15.2.$Т.(Признак\ сравнения.):\forall n\in\mathbb{N}\ a_{n}>0,\ b_{n}>0,\ \exists \lim_{ n \to \infty } \frac{a_{n}}{b_{n}}=k\neq 0\Rightarrow$
$ряды\ \Sigma a_{n}\ и\ \Sigma b_{n}\ ведут\ себя\ одинаково.$

16.1.$Т.(Признак\ Коши.):Пусть\ \forall n\in\mathbb{N}\ a_{n}\geq 0,\ \overline{\lim_{ n \to \infty }}\sqrt[n]{a_{n}}=\alpha.\ Тогда:$
$1)\ \alpha<1,\implies \Sigma a_{n}\ сход.\ 2)\ \alpha>1,\implies \Sigma a_{n}\ расход.\ 3)\ \alpha=1\implies?.$
16.2.$Т.(Признак\ Даламбера.):Пусть\ \forall n\in\mathbb{N}\ a_{n}>0\ и\ \lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}=\alpha.\ Тогда:$
$1)\ \alpha<1\implies\Sigma a_{n}\ сход.\ 2)\ \alpha>1\implies\Sigma a_{n}\ расход.\ 3)\ \alpha=1\implies?.$

17.1.$Необходимое\ и\ достаточное\ условие\ абсолютной\ сходимости\ ряда.$
$a^+= \frac{|a|+a}{2},\ a^-= \frac{|a|-a}{2}.\ a^+ -положит.часть\ числа\ a,\ a^- - отриц.часть.$|$a=a^+ - a^-,$
$|a|=a^+ +a^-,\ 0\leq a^+\leq |a|,\ 0\leq a^-\leq |a|.\ \Sigma a_{n}=\Sigma a_{n}^+ -\Sigma a_{n}^-,\ \Sigma |a_{n}|=\Sigma a_{n}^+ +\Sigma a_{n}^-$
$Т.(необх.и\ дост.усл.абс.сход.):\Sigma a_{n}\ абс.сход.\Longleftrightarrow\Sigma a_{n}^+\ и\ \Sigma a_{n}^-\ сход.$
17.2.$Понятие\ условно\ сходящегося\ ряда. Теорема\ об\ условно\ сходящихся\ рядах.$
$Опр.Числ.ряд\ наз.условно\ сходящимся,\ если\ он\ сходится,\ но\ не\ сходится\ абсолютно.$
$Т.(об\ условно\ сходящихся\ рядах.):\Sigma a_{n}\ сход.\ условно\Rightarrow\Sigma a_{n}^+\ и\ \Sigma a_{n}^-\ расход.$

18.1.$Т.(Преобразование\ (тождество)\ Абеля.)$
$B_{n}=\Sigma_{k=1}^nb_{k},\ n\geq1\implies \Sigma_{k=1}^na_{k}b_{k}=a_{n}B_{n}-\Sigma_{k=1}^{n-1}(a_{k+1}-a_{k})B_{k}$
18.2.$Т.(О\ равносходимости\ рядов,\ связанных\ преобразованием\ Абеля.):$
$B_{n}=\Sigma_{k=1}^nb_{k},\ (a_{n}B_{n})\ сход.\implies\Sigma a_{n}b_{n}\ и\ \Sigma (a_{n+1}-a_{n})B_{n}\ ведут\ себя\ одинаково.$
18.3.$Т.(Признак\ Абеля.):$
$1)\ (a_{n})\ монотон.\ и\ огр.,\ 2)\ \Sigma b_{n}\ сход.(т.е.(B_{n})\ сход.)\implies\Sigma a_{n}b_{n}\ сход.$
18.4.$Т.(Признак\ Дирихле.):$
$1)\ (a_{n})\ монотон.\ и\ a_{n}=\overline{o}(1),\ 2)\ B_{n}=\Sigma_{k=1}^nb_{k}=\underline{O}(1)\implies\Sigma a_{n}b_{n}\ сход.$
18.5.$Т.(Признак\ Лейбница.):(a_{n})\ монотон.\ и\ a_{n}=\overline{o}(1)\implies\Sigma(-1)^{n-1}a_{n}\ сход.$

19.$Сумма\ ряда\ как\ обобщение\ суммы\ конечного\ числа\ слагаемых, сочетательный\ закон.$
$Т.(Сочетательный\ закон.):\Sigma a_{n}\ сход.,\ (m_{n})\uparrow,\ m_{1}=1\implies\Sigma_{n=1}^\infty(\Sigma_{k=m_{n}}^{m_{n+1} - 1}a_{k})\ сход.$
$и\ его\ сумма\ равна\ сумме\ \Sigma_{n=1}^\infty a_{n}.$|$P.S.:Если\ шо,\ в\ скобках: k=m_{n},\ и\ m_{n+1}-1$|
$Опр.\varphi-взаимно\ однознач.\ отображ–е\ \mathbb{N}\ на\ \mathbb{N}.\ \Sigma a_{\varphi(k)}\ наз.\ перестановкой\ ряда\ \Sigma a_{n}.$

20.1.$Т.(Коммутативный\ закон\ для\ знакоположительных\ рядов):$
$\forall n\in\mathbb{N}\ a_{k}\geq0\implies\Sigma_{k=1}^\infty a_{n_{k}}=\Sigma_{k=1}^\infty a_{k}.$
20.2.$Т.(Коммутативный\ закон\ для\ абсолютно\ сходящихся\ рядов.):$
$Ряд\ абс.сход.\implies\ любая\ его\ перестановка\ абс.сход.\ и\ их\ суммы\ равны.$
20.3.$Т.(Римана.):\Sigma a_{n}\ сход.\ усл.\implies \forall A\in \overline{\mathbb{R}}\quad \exists\ \Sigma_{k=1}^\infty a_{n_{k}}=A.$

21.1.$Произведение\ числовых\ рядов,\ согласованное\ с\ произведением\ частных\ сумм.$
$\Sigma c_{n},\ где\ c_{n}=a_{n}\cdot\Sigma_{k=1}^{n-1}b_{k}+b_{n}\cdot\Sigma_{k=1}^{n-1}a_{k}+a_{n}b_{n}\ наз.\ произведением\ \Sigma a_{n}\ и\ \Sigma b_{n}.$
$Пусть\ C_{n}=\Sigma_{k=1}^nc_{k},\ A_{n}=\Sigma_{k=1}^na_{k},\ B_{n}=\Sigma_{k=1}^nb_{k},\ тогда\ C_{n}=A_{n}\cdot B_{n}$
$Т.:\ \Sigma a_{n}\ и\ \Sigma b_{n}\ сход.\implies\Sigma c_{n}\ сход.\ и\ \Sigma_{n=1}^\infty c_{n}=\Sigma_{n=1}^\infty a_{n}\cdot\Sigma_{n=1}^\infty b_{n}.$
21.2.$Т.(О\ произведении\ абсолютно\ сходящихся\ рядов.)$
$\Sigma a_{n}\ и\ \Sigma b_{n}\ абс.\ сход.\implies \Sigma c_{n}\ абс.\ сход.\ и\ \Sigma_{n=1}^\infty c_{n}=\Sigma_{n=1}^\infty a_{n}\cdot\Sigma_{n=1}^\infty b_{n}\ при\ любой$
$нумерации\ элементов\ матрицы\ C.$


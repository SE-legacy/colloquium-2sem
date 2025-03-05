1.$Опр. инт. суммы\ Римана\ и\ инт–а\ Римана. Необход. усл.интегр–сти.$
$[a,b]\in\mathbb{R},a=x_{0}<x_{1}<...<x_{n-1}<x_{n}=b,,P=P_{[a,b]}=\{ x_{k} \}^n_{k=0}-разбение\ [a,b]$
$\Delta_{k}=[x_{k-1},x_{k}],\Delta x_{k}=x_{k}-x_{k-1}, (k=1,...,n).d=d(P)=max_{1\leq k\leq n}\Delta x_{k}–диаметр$
$разб–я\ P.\ \xi_{P}=\{ \xi_{k} \}^n_{k=1},\xi_{k}\in\Delta_{k},(k=1,...,n)–сист.промеж.точек,соотв.разб–ю\ P.$ |
$Пусть\ f\ опр.на\ [a,b]. Сумма\ \sigma(P)=\sigma(P,\xi_{P})=\sigma(f,P,\xi_{P})=\Sigma^n_{k=1}f(\xi_{k})\Delta x_{k}\ наз.инт.суммой$
$Римана\ ф–ции\ f.$|$I=\lim_{ d \to 0 }\sigma(P),если\ \forall\epsilon>0\exists\delta>0\forall(P,\xi_{P})\ (d(P)<\delta\Rightarrow |\sigma(P,\xi_{P})-I|<\epsilon).$
$Число\ I\ наз.пределом\ инт.сумм\ Римана.\ f в\ этом\ случ.наз.инт.по\ Риману\ на\ [a,b],а\ I–инт.$
$Римана\ и\ обозн.\int_{a}^bf(x)dx=I$|$Т.(необ.усл.инт–сти\ ф–ции):f–инт.на[a,b]\Rightarrow f\ огр.на[a,b]$
$Д–во:от\ прот.Пусть\ f\ неогр.на[a,b],P=P_{[a,b]}=\{ x \}^n_{k=0}.Тогда\exists \Delta_{i}:f\ неогр.на\Delta_{i}$
$\sigma(P,\xi_{P})=\Sigma^n_{k=1}f(\xi_{k})\Delta x_{k}=\Sigma^n_{k=1,k\neq i}f(\xi_{k})\Delta x_{k}+f(\xi_{i})\Delta x_{i}=f(\xi_{i})\Delta x_{i}+A\Rightarrow|\sigma(P,\xi_{P})|=$
$=|f(\xi_{i})\Delta x_{i}+A|\geq|f(\xi_{i})|\Delta x_{i}-|A|>M\ \forall M>0.Тогда\exists \xi_{i}\in\Delta_{i}\ такая,что$
$|f(\xi_{i})|> \frac{M+|A|}{\Delta x_{i}}.\Rightarrow |\sigma(P)|>M\Rightarrowпредел\ инт.сумм\ не\ сущ, что\ прот.усл.инт–сти$

2.1.$Верхние\ и\ нижние\ суммы\ Дарбу,\ их\ свойства.$
$Пусть\ f\ опр.и\ огр.на[a,b],P=\{ x_{k} \}^n_{k=0},M_{k}=sup_{x\in\Delta k}f(x),m_{k}=inf_{x\in\Delta k}f(x),1\leq k\leq n,$
$S(P)=\Sigma^n_{k=1}M_{k}\Delta x_{k}-верх.сум.Дарбу,s(P)=\Sigma^n_{k=1}m_{k}\Delta x_{k}-ниж.сум.Дарбу$|$\forall \xi_{P},$
$\forall k:1\leq k\leq n,\ m_{k}\leq f(\xi_{k})\leq M_{k}.$$Св–ва:1)\forall P\ \forall \xi_{P}\ s(P)\leq\sigma(P,\xi_{P})\leq S(P).2)Если\ P\subset P_{1},$
$то\ s(P)\leq s(P_{1}),S(P)\geq S(P_{1}).3)\forall P_{1}\ \forall P_{2}\ s(p_{1})\leq S(P_{2}).След–е:\{s(P)\}огр.сверху,$
$\{S(P)\}огр.снизу.4)\forall P\ \forall\epsilon>0\ \exists \xi_{P},\ 0\leq S(P)-\sigma(P,\xi_{P})<\epsilon\ (0\leq\sigma(P,\xi_{P})-s(P)<\epsilon)$
$След–е:S(P)=sup_{\xi_{p}}\sigma(P,\xi_{p}),s(P)=inf_{\xi_{p}}\sigma(P,\xi_{P})$ 

2.2.$Верхний\ и\ нижний\ интегралы.\ Основная\ лемма\ Дарбу.$
$Верх.инт.Дарбу:\overline{I}:=inf_{P}S(P),ниж.инт.:\underline{I}:=sup_{P}s(P).\underline{I}\leq \overline{I}.Лемм.:Пусть\ P=P_{[a,b]},$
$d=d(P)–диам.разб–яP,P*получено\ из\ P,добавл–ем\ L\ точек,M=sup_{x\in[a,b]}f(x),m=$
$=inf_{x\in[a,b]}f(x)\Rightarrow S(P)-S(P*)\leq(M-m)Ld, s(P*)-s(P)\leq(M-m)Ld.\ Осн.лемм.Дарбу:$
$\overline{I}=\lim_{ _d(p)_ \to 0 }\underline{S}(P),\underline{I}=\lim_{ d(P) \to 0 }s(P),S(P)=s(P)=\sigma(P)=c(b-a)=\underline{I}=\overline{I}=I.\ Д-во:$
$f\neq const,M>m,M=sup_{x\in [a,b]}f(x),m=inf_{x\in[a,b]}f(x).Пусть\ \epsilon>0\Rightarrowпо\ опр.инт.$
$\exists P*\ S(P*)-\overline{I}< \frac{\epsilon}{2}.\ Пусть\ L-кол–во\ т.разб–я\ P*,не\ совпад.с\ т.a\ и\ т.b.,\delta= \frac{\epsilon}{2L(M-m)}$ 
$Пусть\ P–произв.разб.,т.ч. d(P)<\delta.\ P'=P\cup P*,тогда\ по\ пред.лемм.S(P)-S(P')\leq$
$\leq(M-m)L*d<(M-m)L* \frac{\epsilon}{2L(M-m)}=\frac{\epsilon}{2}.\ 0\leq S(P)-\overline{I}=(S(P)-S(P'))+(S(P')-\overline{I})<$
$< \frac{\epsilon}{2}+\frac{\epsilon}{2}=\epsilon.\ S(P')-\overline{I}\leq S(P*)-\overline{I}< \frac{\epsilon}{2}$

3.$Критерий\ интегрируемости$
$Пусть\ f\ опр.и\ огр.на[a,b].Тогда\ след.усл–я\ эквивалентны:1)f\ инт.на[a,b],2)\forall\epsilon>0\ \exists P$
$s(P)-S(P)<\epsilon,3)\underline{I}=\overline{I}=\int_{a}^bf(x)dx.Д-во:1)вып.т.е.\forall\epsilon>0\exists\delta>0\forall(P,\xi_{P})\ ( d(P)<\delta\Rightarrow$
$\Rightarrow|\sigma(P,\xi_{P})-I|< \frac{\epsilon}{4}).По\ св–ву\ сумм\ Дарбу\ \exists \xi'_{P}\ S(P)-\sigma(P,\xi'_{P})< \frac{\epsilon}{4}\ и\ \exists \xi''_{P}\ \sigma(P,\xi''_{P})-s(P)< \frac{\epsilon}{4}$
$Тогда\ |S(P)-s(P)|=|S(P)-\sigma(P,\xi'_{P})|+|\sigma(P,\xi'_{P})-I|+|I-\sigma(P,\xi''_{P})|+|\sigma(P,\xi''_{P})-s(P)|<\epsilon$
$Т.е.вып.усл.2).\ 2)вып.т.е.\forall\epsilon>0\exists P\ S(P)-s(P)<\epsilon.Т.к.\ s(P)\leq \underline{I}\leq \overline{I}\leq S(P),то\ 0\leq \overline{I}-\underline{I}\leq$
$\leq S(P)-s(P)<\epsilon.При\ этом\ \epsilon\to0\Rightarrow 0\leq\overline{I}-\underline{I}\leq0\Leftrightarrow\underline{I}=\overline{I},т.е.вып.усл.3).\ 3)вып.т.е.$
$\underline{I}=\overline{I},\ \epsilon>0 \RightarrowПо\ осн.лемм.Дарбу:\exists\delta>0\forall P\ (d(P)<\delta\Rightarrow S(P)-\overline{I}<\epsilon\ и\ \underline{I}-s(P)<\epsilon).$
$\forall \xi_{P}: I-\epsilon<s(P)\leq\sigma(P,\xi_{P})\leq S(P)<I+\epsilon,\ \forall\epsilon>0\ \exists\delta>0,\forall P,\forall \xi_{P}$
$(d(P)<\delta\Rightarrow |\sigma(P,\xi_{P})-I|<\epsilon)\Rightarrow f-инт.,т.е.вып.усл.1).ч.т.д.$

4.1.$Теорема\ об\ интегрируемости\ непрерывной\ функции$
$f\ непр.на[a,b]\Rightarrow f\ инт.на[a,b].\ Д–во:f-непр.на[a,b]\Rightarrow По\ Т.Кантора\ f\ равн.непр.на[a,b].$
$\epsilon>0\Rightarrow \exists\delta>0\ \forall \xi',\xi''\in[a,b]\ \left( |\xi'-\xi''|<\delta\Rightarrow |f(\xi')-f(\xi'')|< \frac{\epsilon}{b-a} \right).\ Пусть\ P:d(P)<\delta,$
$M_{k}-m_{k}< \frac{\epsilon}{b-a},M_{k}=f(\xi'_{k}),m_{k}=f(\xi''_{k}).Тогда\ S(P)-s(P)=\Sigma^n_{k=1}(M_{k}-m_{k})\Delta x_{k}<$
$<\Sigma^n_{k=1} \frac{\epsilon}{b-a}\Delta x_{k}=\frac{\epsilon}{b-a}(b-a)=\epsilon.\Rightarrow По\ крит.инт–сти\ f–инт.,ч.т.д.$

4.2.$Теорема\ об\ интегрируемости\ монотонной\ функции$
$f\ монот.на[a,b]\Rightarrow f\ инт.на[a,b].\ Д–во:если\ f\equiv const, f\equiv c\Rightarrow S(P)=s(P)=\sigma(P,\xi_{P})=$
$=c(b-a)=\int^b_{a}cdx.\ Пусть\ f\neq const\ и\ f \uparrow,P=P_{[a,b]}=\{ x_{k} \}^n_{k=0}\ \Delta_{k}=[x_{k-1},x_{k}],тогда$
$S(P)-s(P)=\Sigma^n_{k=1}(M_{k}-m_{k})\Delta x_{k},\ M_{k}=f(x_{k}),m_{k}=f(x_{k-1}).\ Пусть\ \epsilon>0,т.к.f(b)\neq f(a)\Rightarrow$
$\Rightarrow\frac{\epsilon}{f(b)-f(a)}>0.\ Пусть\ d(P)< \frac{\epsilon}{f(b)-f(a)}\Rightarrow\Delta x_{k}< \frac{\epsilon}{f(b)-f(a)}\ \forall k=1,n.\ S(P)-s(P)=$
$=\Sigma^n_{k=1}(M_{k}-m_{k})\Delta x_{k}<\Sigma^n_{k=1}(M_{k}-m_{k}) \frac{\epsilon}{f(b)-f(a)}=\frac{\epsilon}{f(b)-f(a)}\Sigma^n_{k=1}(f(x_{k})-f(x_{k-1}))=$
$=\frac{\epsilon}{f(b)-f(a)}(f(b)-f(a))=\epsilon\RightarrowПо\ крит.инт–сти\ f–инт.,ч.т.д.$ 

5.1.$Св–ва\ инт.\ Рим.: линейн–сть\ инт–а, аддит–сть\ инт.\ относит. пред.\ инт–я, монотон–сть\ инт.$
$Т.(лин–сть\ инт.):f,g\in\mathfrak{R}[a,b],c\in\mathbb{R}\Rightarrow f+g,cf\in\mathfrak{R}[a,b],\ \int_{a}^b(f(x)+g(x))dx=\int_{a}^bf(x)dx+\int_{a}^bg(x)dx$
$и\ \int_{a}^bcf(x)dx=c\int_{a}^bf(x)dx.Д–во:\sigma(f+g,P,\xi_{P})=\sigma(f,P,\xi_{P})+\sigma(g,P,\xi_{P}),\ \sigma(cf,P,\xi_{P})=c\cdot\sigma(f,P,\xi_{P})$
$Т.(адд–сть\ инт.):Пусть\ a<c<b,тогда\ f\in\mathfrak{R}[a,b]\Leftrightarrow f\in\mathfrak{R}[a,c]\ и\ f\in\mathfrak{R}[c,b],\ \int_{a}^bf(x)dx=\int_{a}^cf(x)dx+$
$+\int_{c}^bf(x)dx.Д–во:|\Rightarrow f\in\Re[a,b]\Rightarrow По\ крит.инт.Пусть\ \epsilon>0\ \exists P_{[a,b]}\ S(P)-s(P)<\epsilon.\ P*=P\cup \{ c \}$
$S(P*)-s(P*)\leq S(P)-s(P)<\epsilon.\ P*=P'_{[a,c]}\cup P''_{[c,b]}=P'\cup P'', (S(P')-s(P'))+(S(P'')-s(P''))<\epsilon$
$По\ крит.инт.f\in\Re[a,c]\ и\ f\in\Re[c,b]. \Leftarrow|f\in\Re[a,c]\ и\ f\in\Re[c,b],\epsilon>0.\ \exists P'=P'_{[a,c]}\ и\ \exists P''=P''_{[c,b]}:$
$S(P')-s(P')< \frac{\epsilon}{2},\ S(P'')-s(P'')< \frac{\epsilon}{2}.Тогда\ для\ P=P_{[a,b]}=P'\cup P''\ S(P)-s(P)< \frac{\epsilon}{2}+ \frac{\epsilon}{2}<\epsilon$
$т.е.\ f\in\Re[a,b].\ Т.(мон–сть\ инт.):f,g\in\Re[a,b],\forall x\in[a,b]\ f(x)\leq g(x)\Rightarrow\int_{a}^bf(x)dx\leq\int_{a}^bg(x)dx.$
$Д–во:\forall P,\forall \xi_{P}\ \sigma(f,P,\xi_{P})\leq\sigma(g,P,\xi_{P}).Переходя\ к\ пред.при\ d(P)\to0:\int_{a}^bf(x)dx\leq\int_{a}^bg(x)dx.$
$След–е\ 1:f\in\Re[a,b],\forall x\ f(x)\geq0\Rightarrow\int_{a}^bf(x)dx\geq0.След–е\ 2:f\in\Re[a,b]\Rightarrow |\int_{a}^bf(x)dx|\leq\int_{a}^b|f(x)|dx\leq$
$\leq sup_{x\in[a,b]}|f(x)|(b-a)$ 

5.2.$Первая\ теорема\ о\ среднем\ для\ интеграла.$
$f,g\in\Re[a,b],g(x)\geq0\ (g(x)\leq0)\ \forall x\in[a,b],M=sup_{x\in[a,b]}f(x),m=inf_{x\in[a,b]}f(x)\Rightarrow \exists \mu\in[m,M]:$
$\int_{a}^bf(x)g(x)dx=\mu\int_{a}^bg(x)dx.Д—во:\forall x\in[a,b]\ g(x)\geq0, m\leq f(x)\leq M\Rightarrow mg(x)\leq f(x)g(x)\leq Mg(x)$
$\Rightarrow m\int_{a}^bg(x)dx\leq\int_{a}^bf(x)g(x)dx\leq M\int_{a}^bg(x)dx.\ 1)Если \int_{a}^bg(x)dx=0\Rightarrow 0=0,\ 2)\int_{a}^bg(x)dx>0\Rightarrow$
$m\leq(\int_{a}^bf(x)g(x)dx)\ /\ (\int_{a}^bg(x)dx)\leq M, \frac{\int_{a}^bf(x)g(x)dx}{\int_{a}^bg(x)dx}=\mu.Замеч–е:f\ непр.на[a,b]\Rightarrow По\ Т.Коши\ о$
$промеж.знач.:\exists \xi\in[a,b],f(\xi)=\mu, \int_{a}^bf(x)g(x)dx=f(\xi)\int_{a}^bg(x)dx.След–е:Если\ g(x)\equiv1,то$
$\int_{a}^bf(x)dx=f(\xi)\int_{a}^b1dx=f(\xi)(b-a)$

5.3.$Операции\ над\ интегрируемыми\ функциями.$
$f,g\in\Re[a,b]\Rightarrow |f|,f\cdot g\in\Re[a,b], \frac{f}{g}\in\Re[a,b]\ при\ усл.\exists c>0\ \forall x\in[a,b]\ |g(x)|\geq c.\ Д–во:$
$Пусть\ \epsilon>0,S(f,P)-s(f,P)<\epsilon.\ 1)\ Док.,что\ |f|\ инт.: \forall \xi,\eta \in \Delta_{k}\ |f(\xi)|-|f(\eta)|\leq |f(\xi)-f(\eta)|\leq$
$\leq M_{k}(f)-m_{k}(f),\ M_{k}(f)=sup_{x\in\Delta k}f(x),m_{k}(f)=inf_{x\in \Delta k}f(x).Тогда\ M_{k}(|f|)-m_{k}(|f|)\leq M_{k}(f)-m_{k}(f)$
$\Rightarrow S(|f|,P)-s(|f|,P)\leq S(f,P)-s(f,P)<\epsilon\Rightarrow по\ крит.инт.|f|\in\Re[a,b].\ 2)Док.что\ f^2\ инт.:f\ инт\Rightarrow$
$\Rightarrow f\ огр.\ \exists A>0\ \forall x\in[a,b]\ |f(x)|\leq A.\ Пусть\ \xi,\eta\in\Delta_{k},тогда\ f^2(\xi)-f^2(\eta)=(f(\xi)+f(\eta))(f(\xi)-f(\eta))$
$\leq2A(f(\xi)-f(\eta))\leq2A(M_{k}(f)-m_{k}(f))\Rightarrow S(f^2,P)-s(f^2,P)\leq2A(S(f,P)-s(f,P))<2A\epsilon\Rightarrowпо\ крит.$
$инт.f^2\in \Re[a,b].\ Т.к.f\cdot g=\frac{1}{4}((f+g)^2-(f-g)^2)\Rightarrow f\cdot g\in\Re[a,b].\ 3)Док.что\ \frac{1}{f}\ инт.: \frac{1}{f(\xi)}-\frac{1}{f(\eta)}=$
$=\frac{f(\eta)-f(\xi)}{f(\xi)f(\eta)}\leq \frac{1}{C^2}(M_{k}(f)-m_{k}(f))\Rightarrow M_{k}(\frac{1}{f})-m_{k}(\frac{1}{f})\leq \frac{1}{C^2}(M_{k}(f)-m_{k}(f)),\ S(\frac{1}{f},P)-s(\frac{1}{f},P)\leq$
$\leq\frac{1}{C^2}(S(f,P)-s(f,P))< \frac{1}{C^2}\epsilon\Rightarrowпо\ крит.инт. \frac{1}{f}\in\Re[a,b]\Rightarrow \frac{f}{g}\in\Re[a,b], ч.т.д.\ Замеч–е:Из\ инт–сти$
$|f|\ не\ следует\ инт–сть\ f.$

6.$Непрерывность\ интеграла\ по\ верхнему\ пределу\ интегрирования.$
$f\in\Re[a,b]\Rightarrow F(x)=\int_{a}^xf(t)dt\ непр.на[a,b].\ Д–во:Пусть\ x,\ x+h\in[a,b],\ M=sup_{x\in[a,b]}|f(x)|,$
$тогда\ |F(x+h)-F(x)|=|\int_{a}^{x+h}f(t)dt-\int_{a}^xf(t)dt|=|\int_{x}^{x+h}f(t)dt|\leq M\cdot|h|\to0\ при\ h\to0\Rightarrow$
$\Rightarrow F(x+h)\to F(x)\ при\ h\to0\Rightarrow \forall x\in[a,b]\ F\ непр.в\ т.x,\ ч.т.д.$ 

7.$Дифф–сть\ интеграла\ по\ верхнему\ пределу\ интегрирования.Ф–ла\ Ньютона–Лейбница$


# Leis do movimento - Mecânica Clássica

Para chegarmos às equações do movimento que estamos tão familiarizados \(**V**o**Vô at**eu, **So**r**v**e**t**e e **So**r**v**e**tã**o\), precisamos primeiro partir do ponto em que consideramos algo como constante, isso é, algo que não terá variação com o passar do tempo. 

Um exemplo simples de constantes que será bastante explorado em seus estudos são os _**números**_. E por números quero dizer no geral mesmo: naturais, inteiros, reais, complexos... você escolhe! \(Sim, é verdade que bastava dizer números complexos para englobar os conjuntos anteriores. Se quiser saber mais sobre esse conceito, pesquise por "conjuntos numéricos\).

> Tá. Mas como números são constantes?

Você deve se perguntar. Simples! Eles permanecem os mesmos, independente de quanto tempo se passe: 1 será 1 mesmo que você o observe por dias, milênios, até a morte fria do universo; 1 não é 2, nem 5, 1 é 1. Assim como qualquer outro número: $$2$$ , $$\pi$$, $$\frac{7 + \sqrt{5}}{4}$$ ,$$2i + \sqrt[3]{(7\pi)^2}\ln(5)$$, todos são somente e apenas eles mesmos. \(É claro que existem diferentes formas de representar um número: $$2$$ pode ser descrito como $$2$$ ou como $$1 + 1$$ ,$$3 -1$$, $$e^{\ln(2)}$$... mas são todos diferentes representações de um mesmo número\).

Maravilha! Agora que temos uma pequena noção do que é uma constante, podemos seguir em frente! Cada equação da cinemática assume algo como constante. Se sua posição é constante, então você está parado e nada muito interessante acontece; se sua velocidade é constante, então está em movimento e equações como $$s = s_0 + vt$$\(sorvete\) surgem, nesse caso, dizemos que sua posição se altera de maneira _**linear**_ \(veremos o porquê mais pra frente\). Se sua aceleração é constante, então temos $$v = v_0 +at$$\(vovô ateu\), $$s = s_0 + v_0t+\frac{1}{2}at^2$$\(sorvetão\) e $$v^2=v_0{}^2+2a\Delta s$$ \(Torricelli\).

$$
v=cte\\
\int_{0}^t vdt = vt =\int_0^t \dfrac{ds}{dt}dt = s(t)-s_0\\
vt = s(t) - s_0 \longrightarrow s(t) = s_0 + vt
$$

$$
a = cte\\
\int_0^tadt=at=\int_0^t\frac{dv}{dt}dt=v(t)-v_0\\
at=v(t)-v_0 \longrightarrow v(t) = v_0 + at\\
\int_0^t v(t)dt=\int_0^t(v_0+at)dt =v_0t+\frac{1}{2}at^2\\
=\int_0^t\frac{ds}{dt}dt = s(t) - s_0\\
s(t) - s_0 = v_0t+\frac{1}{2}at^2\\
s(t) =s_0 + v_0t+\frac{1}{2}at^2
$$


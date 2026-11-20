# Fundamentos físicos — HD 149026b

Esta nota resume, en lenguaje sencillo, las ecuaciones que aparecen en el informe original. No reemplaza el artículo completo ni implica una nueva verificación de sus resultados.

## 1. Velocidad radial

Una estrella no está completamente inmóvil cuando tiene un planeta: ambos cuerpos orbitan alrededor del centro de masa común. La velocidad de la estrella en dirección a la línea de visión puede deducirse a partir del desplazamiento Doppler de su luz.

Cuando la órbita es aproximadamente circular, una función sinusoidal permite describir la variación periódica:

$$
v_r(t)=A\sin(\omega t+\phi)+C,\qquad \omega=\frac{2\pi}{P}.
$$

Aquí \(P\) es el período orbital, \(A\) la amplitud de la señal, \(\phi\) la fase y \(C\) un desplazamiento de velocidad. El análisis mediante Lomb–Scargle busca periodicidades en mediciones tomadas en tiempos irregulares.

Para una órbita kepleriana, la semiamplitud se relaciona con la masa del planeta mediante

$$
K=\left(\frac{2\pi G}{P}\right)^{1/3}
\frac{M_p\sin i}{(M_\star+M_p)^{2/3}}\frac{1}{\sqrt{1-e^2}},
$$

donde \(M_\star\) y \(M_p\) son las masas de la estrella y del planeta, \(i\) la inclinación orbital y \(e\) la excentricidad. Si no conocemos \(i\), el método de velocidad radial suele proporcionar la masa mínima \(M_p\sin i\).

## 2. Tránsitos

Cuando el planeta cruza delante del disco estelar, bloquea parte de su luz. En el caso ideal de un planeta pequeño y una estrella de brillo superficial uniforme,

$$
\delta\simeq\left(\frac{R_p}{R_\star}\right)^2.
$$

Por eso, si conocemos el radio de la estrella y medimos la profundidad de la caída de brillo, podemos estimar el radio del planeta. En la práctica, la inclinación, el oscurecimiento hacia el limbo y la geometría también afectan la curva de luz.

El informe utiliza una función descriptiva para ajustar la región de tránsito:

$$
f(x)=-A\exp[-B(x-C)^4]+D.
$$

Esta expresión describe la forma de la caída de flujo, pero no equivale a un modelo completo de tránsito con todos los efectos geométricos y estelares.

## 3. Zona de habitabilidad

El informe considera distintos criterios climáticos de límites interiores y exteriores de la zona habitable. La distancia correspondiente a un criterio se aproxima como

$$
d_{\mathrm{HZ}}=\sqrt{\frac{L/L_\odot}{S_{\mathrm{eff}}}}\,\mathrm{AU},
$$

siendo \(L\) la luminosidad estelar y \(S_{\mathrm{eff}}\) el flujo efectivo requerido por el criterio climático. En los modelos citados, este flujo depende de la temperatura efectiva de la estrella mediante un polinomio:

$$
S_{\mathrm{eff}}=S_{\mathrm{eff},\odot}
+aT'+bT'^2+cT'^3+dT'^4, \qquad T'=T_{\mathrm{eff}}-5780\,\mathrm{K}.
$$

El trabajo aplica estas relaciones a estrellas de aproximadamente \(0.4\) a \(1\,M_\odot\). Esta parte del proyecto analiza tendencias de **zonas habitables estelares**; no afirma que HD 149026b sea habitable.

## 4. Valores documentados en el informe

- Período orbital: **2.8756476 días**.
- Semiamplitud radial: **42.6 m/s**.
- Masa mínima: **0.3515 masas de Júpiter**.
- Profundidad de tránsito: **0.00309**.
- Radio planetario: **0.72 radios de Júpiter**.

Los valores anteriores se copiaron del informe entregado y quedan pendientes de verificación independiente usando los datos originales.


Grundbereich $f(t)$ : Wann hat das Signal welche Amplitude ? 

Frequenzbereich $\tilde {f}(\omega)$ : Aus welchen Frequenzen $\omega$ (Spektralkomponenten) setzt sich das Signal mit welchem Amplituden- und Phasenanteil zusammen ?

1. Diskretes Spektrum vs. Delta-Peaks(Aufgabe 1: $f(t) = \cos{\omega_0 t}$)
	1. a) Die Fourier Reihe :
			Periodische Signale lassen sich als Summe diskreter Frequenzen schreiben: $f(t) = \sum_{k\in \mathbb{Z}}{c_k e^{-ik\omega_0 t}}$
		 Euler Formel für $cos(\omega_0 t) = \frac{1}{2} e^{i \omega_0 t} + \frac{1}{2}e^{-\omega_0 t} = \frac{1}{2} e^{-i(-1)\omega_0 t} + \frac{1}{2} e^{-i(1)\omega_0 t}$
		
		Dann erhält man durch Koeffizientenvergleich mit der Summe $c_1 = \frac{1}{2} (k = 1)$
$c_{-1} = \frac{1}{2} (k = -1)$ 
$c_k = 0(|k| \neq (1))$

--> Das bedeutet Physikalisch : Ein rein monochromatisches (periodisches) Signal enthält exakt nur zwei diskrete Frequenzen +/- $\omega_0$
			






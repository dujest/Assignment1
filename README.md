# Assignment1
Latex

\documentclass[a4paper,12pt]{article}
\usepackage[T1]{fontenc}

\begin{document}

\section{}

Offshore conditions:
\[
\frac{d}{L} > \frac{1}{2}
\]
Wavelength:
\[
L_0 = \frac{g T^2}{2 \pi} = 156.1 m
\]
\[
d = \frac{L_0}{2} = 78.1 m
\]

\section{}

As we don't know the classification of water waves, we should start with the formula for deep water:
The wavelength:
\[
L = \frac{g T^2}{2 \pi} = 224.8 m
\]
\[
\frac{d}{L} = 0.1 < \frac{1}{2}
\]
By using the wavelength formula for transitional water and the Excel's Solver, the wavelength is obtained:
\[
L = \frac{g T^2}{2 \pi} \tanh(\frac{2 \pi d}{L}) = 152.4 m
\]

\section{}
The wave celerity:
\[
L = \frac{g T^2}{2 \pi} = 140517 m
\]
\[
\frac{d}{L} = 0.01 < \frac{1}{25}
\]
\[
C_0 = \sqrt{g d} = 99.04 \frac{m}{s}
\]

\section{}
The wave celerity:
\[
L = \frac{g T^2}{2 \pi} = 140517 m
\]
\[
\frac{d}{L} = 0.0001 < \frac{1}{25}
\]
\[
C_0 = \sqrt{g d} = 9.90 \frac{m}{s}
\]

\section{}
\[
\frac{H}{g T^2} = 0.004
\]
\[
\frac{d}{g T^2} = 0.14
\]
From Le Mehaute diagram, it is the Linear wave theory.

\section{}
The Iribarren number is:
\[
\xi = 1.25 T \frac{\tan \alpha}{\sqrt{H}} = 4.2
\]

\section{}
\[
\xi_0 > 3.3
\]
The wave shape is surging.

\section{}
\[
KC = \frac{2 \pi}{D} \frac{u_{max}^2}{a_{max}} = 8.07
\]

\section{}
\[
L_0 = \frac{g T^2}{2 \pi} = 224.8
\]
\[
\frac{d}{L} = 0.1 < \frac{1}{2}
\]
\[
L = \frac{g T^2}{2 \pi} \tanh(\frac{2 \pi d}{L}) = 152.4 m
\]
\[
u = \frac{H}{2} \frac{g T}{L} \frac{\cosh[2 \pi (z + d) / L]}{cosh(2 \pi d/L)} \cos \theta
\]
\[
z = -d
\]
\[
u_{max} = \frac{H}{2} \frac{g T}{\frac{g T^2}{2 \pi} \tanh(\frac{2 \pi d}{L})} \frac{1}{cosh(2 \pi d/L)}
\]
\[
u_{max} = \frac{H}{2} \frac{1}{\frac{T}{2 \pi} \sinh(\frac{2 \pi d}{L})} = 1.42 \frac{m}{s}
\]
\[
KC = \frac{u T}{D} = 3.4
\]

\section{}
\[
L_0 = \frac{g T^2}{2 \pi} = 224.8
\]
\[
\frac{d}{L} = 0.1 < \frac{1}{2}
\]
\[
L = \frac{g T^2}{2 \pi} \tanh(\frac{2 \pi d}{L}) = 152.4 m
\]
\[
u = \frac{H}{2} \frac{g T}{L} \frac{\cosh[2 \pi (z + d) / L]}{cosh(2 \pi d/L)} \cos \theta
\]
\[
z = 0
\]
\[
u = \frac{H}{2} \frac{g T}{L} = 2.32 \frac{m}{s}
\]

\end{document}

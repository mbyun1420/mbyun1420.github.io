---
layout: post
title:  "Markdown mathematic formulars 마크다운 수식"
author: youn
categories: [ Markdown ]
image: https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg
---

write Mathematic symbols

The default math delimiters are $$...$$ and \[...\] for displayed mathematics, and \(...\) for in-line mathematics. Note in particular that the $...$ in-line delimiters are not used by default. That is because dollar signs appear too often in non-mathematical settings, which could cause some text to be treated as mathematics unexpectedly. For example, with single-dollar delimiters, “… the cost is \$2.50 for the first one, and $2.00 for each additional one …” would cause the phrase “2.50 for the first one, and” to be treated as mathematics since it falls between dollar signs. See the section on TeX and LaTeX Math Delimiters for more information on using dollar signs as delimiters.
Markdown 형식을 따르는 글에서의 수식 표현은 글 내에서 이루어 지거나 블록 형태로 표현한다. 인라인 형태의 수식 표현은 $\sqrt{3x-1}+(1+x)^2$ 과 같이 수식 표현에 $ 태그를 적용한다. 


블록 형태의 수식 표현은 $$ 태그를 적용한다. 

$$
\sqrt{3x-1}+(1+x)^2
$$


### Greek letters 그리스 문자

Syntax 입력에 있어서 태그는 생략한다  



| Output               | Syntax              | Output               | Syntax              |  
|:---:                 |:---:                |:---:                 |:---:                |  
| $A$	               | A                   | $B$	                | B                   |  
| $\alpha$	           | \alpha              | $\beta$	            | \beta               |  
| $\gamma$	           | \gammma             | $\Gamma$             | \Gamma              |  
| $\pi$                | \pi                 | $\Pi$	            | \Pi                 |  
| $\phi$               | \phi                | $\Phi$	            | \Phi                |  
| $\varphi$	           | \varphi             | $\theta$	            | \theta              |  



### Sinesoidal function 삼각함수


| Output | Syntax    | Output | Syntax   |  
|:---:   |:---:   |:---:   |:---:     |  
| $\cos$ | \cos | $\sin$ | \sin |  


### Mathematical symbols 수학 기호 

| Output | Syntax    | Output | Syntax   |
|:---:   |:---:   |:---:   |:---:     |
| $\lim$ | \lim | $\exp$ | \exp |
| $\to$ | \to | $\infty$ | \infty |
| $\equiv$ | \equiv | $\bmod$ | \bmod |
| $\times$ | \times | $\sum$ | \sum |
| $\prod$ |	\prod | $\coprod$ |	\coprod |
| $\bigoplus$ |	\bigoplus | $\bigotimes$ | \bigotimes |
| $\bigodot$ | \bigodot | $\bigcup$ |	\bigcup |
| $\bigcap$ | \bigcap | $\biguplus$ |	\biguplus |
| $\bigsqcup$ | \bigsqcup | $\bigvee$ |	\bigvee |
| $\bigwedge$ |	\bigwedge | $\int$ | \int |
| $\oint$ |	\oint | $\iint$	| \iint |
| $\iiint$ | \iiint | $\idotsint$ |	\idotsint |
| $a’$ | a` | $a^{\prime}$ | a^{\prime} |
| $a’’$ | a’’ | $\hat{a}$ |	hat{a} |
| $\bar{a}$ | \bar{a} | $\grave{a}$ | \grave{a} |
| $\acute{a}$ |	\acute{a} | $\dot{a}$ | \dot{a} |
| $\ddot{a}$ | \ddot{a} | $\not{a}$ | \not{a} |
| $\mathring{a}$ | \mathring{a} | $a’’’$ | a’’’ |
| $\overline{aaa}$	| \overline{aaa} | $\check{a}$ | \check{a} |
| $\vec{a}$ |	\vec{a} | $\underline{a}$ |	\underline{a} |
| $\overleftarrow{AB}$ | \overleftarrow{AB} |$\overrightarrow{AB}$ | \overrightarrow{AB} |
| $\pm$ |	\pm | $\mp$	 | \mp | 
| $,$	| , | $:$ |	: |
| $;$ |	; | $!$ |	! |
| $\dots$ |	\dots | $\ldots$ |	\ldots |
| $\cdots$ |	\cdots |$\vdots$ |	\vdots |
| $\ddots$ |	\ddots |$\color{red}x$ |	\color{red}x |


### Mathematical expression 수식

| Output | Syntax    | Output | Syntax   |
|:---:   |:---:   |:---:   |:---:     |
| $k_{n+1}$ | k_{n+1} | $n^2$ |	n^2 |
| $k_n^2$ |	k_n^2 | $\frac{n!}{k!(n-k)!}$ |	\frac{n!}{k!(n-k)!} |
| $\binom{n}{k}$ | \binom{n}{k} | $\frac{\frac{x}{1}}{x - y}$ | \frac{\frac{x}{1}}{x - y} |
| $^3/_7$ | ^3/_7 | $\sqrt{k}$ | \sqrt{k} |
| $\sqrt[n]{k}$ | \sqrt[n]{k} | $\sum_{i=1}^{10} t_i$ | \sum_{i=1}^{10} t_i |
| $\int y, \mathrm{d}x$	| \int y, \mathrm{d}x |$\int y \mathrm{d}x$ |	\int y \mathrm{d}x |
| $\int\limits_a^b$	 | \int\limits_a^b | $\int_0^\infty \mathrm{e}^{-x},\mathrm{d}x$ | \int_0^\infty \mathrm{e}^{-x},\mathrm{d}x | 
| $\sum_{\substack{0<i<m , 0<j<n}} P(i, j)$ | \sum_{\substack{0<i<m\0<j<n}} P(i, j) |  


### Brackets 

| Output | Syntax    | Output | Syntax   |
|:---:   |:---:   |:---:   |:---:     |
| $(a)$ |	(a) | $[a]$	| [a] |
| ${a}$	| {a} | $\langle f \rangle$ |	\langle f \rangle |
| $\lfloor f \rfloor$ |	\lfloor f \rfloor | $\lceil f \rceil$	| \lceil f \rceil |
| $\ulcorner f \urcorner$ |	\ulcorner f \urcorner |


### Reference

https://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/
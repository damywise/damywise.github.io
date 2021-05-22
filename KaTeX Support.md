Supported Functions · KaTeX document.addEventListener('DOMContentLoaded', function() { addBackToTop( {"zIndex":100} ) }); 

[![KaTeX](/img/katex-logo.svg)](/)

*   [Try](/#demo)
*   [Docs](/docs/node.html)
*   [v0.13.11](https://katex.org/versions.html)
*   [Users](/users.html)
*   [GitHub](https://github.com/KaTeX/KaTeX)
*   

_›_Misc
-------

### Installation

*   [Node.js](/docs/node.html)
*   [Browser](/docs/browser.html)

### Usage

*   [API](/docs/api.html)
*   [CLI](/docs/cli.html)
*   [Auto-render Extension](/docs/autorender.html)
*   [Extensions & Libraries](/docs/libs.html)

### Configuring KaTeX

*   [Options](/docs/options.html)
*   [Security](/docs/security.html)
*   [Handling Errors](/docs/error.html)
*   [Font](/docs/font.html)

### Misc

*   [Supported Functions](/docs/supported.html)
*   [Support Table](/docs/support_table.html)
*   [Common Issues](/docs/issues.html)
*   [Migration Guide](/docs/migration.html)

Supported Functions
===================

This is a list of TeX functions supported by KaTeX. It is sorted into logical groups.

There is a similar [Support Table](/docs/support_table.html), sorted alphabetically, that lists both supported and un-supported functions.

p {overflow-wrap: break-word;} table tr, table td { vertical-align: middle; overflow-wrap: break-word; }

[](#accents)Accents
-------------------

$a'$

$\tilde{a}$

$\mathring{g}$

$a''$

$\widetilde{ac}$

$\overgroup{AB}$

$a^{\prime}$

$\utilde{AB}$

$\undergroup{AB}$

$\acute{a}$

$\vec{F}$

$\Overrightarrow{AB}$

$\bar{y}$

$\overleftarrow{AB}$

$\overrightarrow{AB}$

$\breve{a}$

$\underleftarrow{AB}$

$\underrightarrow{AB}$

$\check{a}$

$\overleftharpoon{ac}$

$\overrightharpoon{ac}$

$\dot{a}$

$\overleftrightarrow{AB}$

$\overbrace{AB}$

$\ddot{a}$

$\underleftrightarrow{AB}$

$\underbrace{AB}$

$\grave{a}$

$\overline{AB}$

$\overlinesegment{AB}$

$\hat{\theta}$

$\underline{AB}$

$\underlinesegment{AB}$

$\widehat{ac}$

$\widecheck{ac}$

$\underbar{X}$

**_Accent functions inside \\text{…}_**

$\text{\'{a}}$

$\text{\~{a}}$

$\text{\.{a}}$

$\text{\H{a}}$

$\text{\`{a}}$

$\text{\={a}}$

$\text{\"{a}}$

$\text{\v{a}}$

$\text{\^{a}}$

$\text{\u{a}}$

$\text{\r{a}}$

See also [letters](#letters)

[](#delimiters)Delimiters
-------------------------

( )(~)( ) $( )$

( )\\lparen~\\rparen( ) $\lparen$  
 \~~~~ $\rparen$

⌈ ⌉⌈~⌉⌈ ⌉ $⌈ ⌉$

⌈ ⌉\\lceil~\\rceil⌈ ⌉ $\lceil$  
 \~~~~~ $\rceil$

↑\\uparrow↑ $\uparrow$

\[ \]\[~\]\[ \] $[ ]$

\[ \]\\lbrack~\\rbrack\[ \] $\lbrack$  
 \~~~~ $\rbrack$

⌊ ⌋⌊~⌋⌊ ⌋ $⌊ ⌋$

⌊ ⌋\\lfloor~\\rfloor⌊ ⌋ $\lfloor$  
 \~~~~~ $\rfloor$

↓\\downarrow↓ $\downarrow$

{}\\{ \\}{} $\{ \}$

{}\\lbrace \\rbrace{} $\lbrace$  
 \~~~~ $\rbrace$

⎰⎱⎰⎱⎰⎱ $⎰⎱$

⎰⎱\\lmoustache \\rmoustache⎰⎱ $\lmoustache$  
 \~~~~ $\rmoustache$

↕\\updownarrow↕ $\updownarrow$

⟨ ⟩⟨~⟩⟨ ⟩ $⟨ ⟩$

⟨ ⟩\\langle~\\rangle⟨ ⟩ $\langle$  
 \~~~~ $\rangle$

⟮ ⟯⟮~⟯⟮ ⟯ $⟮ ⟯$

⟮ ⟯\\lgroup~\\rgroup⟮ ⟯ $\lgroup$  
 \~~~~~ $\rgroup$

⇑\\Uparrow⇑ $\Uparrow$

∣\\vert∣ $|$

∣\\vert∣ $\vert$

┌┐┌ ┐┌┐ $┌ ┐$

⌜⌝\\ulcorner \\urcorner┌┐ $\ulcorner$  
 \~~~~ $\urcorner$

⇓\\Downarrow⇓ $\Downarrow$

∥\\Vert∥ $\|$

∥\\Vert∥ $\Vert$

└┘└ ┘└┘ $└ ┘$

⌞⌟\\llcorner \\lrcorner└┘ $\llcorner$  
 \~~~~ $\lrcorner$

⇕\\Updownarrow⇕ $\Updownarrow$

∣ ∣\\lvert~\\rvert∣ ∣ $\lvert$  
 \~~~~ $\rvert$

∥ ∥\\lVert~\\rVert∥ ∥ $\lVert$  
 \~~~~~ $\rVert$

`\left.$

`\right.$

\\\\backslash\\ $\backslash$

⟨ ⟩\\lang~\\rang⟨ ⟩ $\lang$  
 \~~~~ $\rang$

< \>\\lt~\\gt< \> $\lt \gt$

⟦ ⟧⟦~⟧\[\[ \]\] $⟦ ⟧$

⟦ ⟧\\llbracket~\\rrbracket\[\[ \]\] $\llbracket$  
 \~~~~ $\rrbracket$

⦃ ⦄\\lBrace~\\rBrace{\[ \]} $\lBrace \rBrace$

**Delimiter Sizing**

(AB)\\left(\\LARGE{AB}\\right)(AB) $\left(\LARGE{AB}\right)$

(((((( \\big( \\Big( \\bigg( \\Bigg(((((( $( \big( \Big( \bigg( \Bigg($

`\left$

`\big$

`\bigl$

`\bigm$

`\bigr$

`\middle$

`\Big$

`\Bigl$

`\Bigm$

`\Bigr$

`\right$

`\bigg$

`\biggl$

`\biggm$

`\biggr$

`\Bigg$

`\Biggl$

`\Biggm$

`\Biggr$

[](#environments)Environments
-----------------------------

abcd\\begin{matrix} a & b \\\\ c & d \\end{matrix}ac​bd​

`\begin{matrix}$  
   `a & b \\$  
   `c & d$  
`\end{matrix}$

abcd\\begin{array}{cc}a & b\\\\c & d\\end{array}ac​bd​

`\begin{array}{cc}$  
   `a & b \\$  
   `c & d$  
`\end{array}$

(abcd)\\begin{pmatrix} a & b \\\\ c & d \\end{pmatrix}(ac​bd​)

`\begin{pmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{pmatrix}$

\[abcd\]\\begin{bmatrix} a & b \\\\ c & d \\end{bmatrix}\[ac​bd​\]

`\begin{bmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{bmatrix}$

∣abcd∣\\begin{vmatrix} a & b \\\\ c & d \\end{vmatrix}∣∣​ac​bd​∣∣​

`\begin{vmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{vmatrix}$

∥abcd∥\\begin{Vmatrix} a & b \\\\ c & d \\end{Vmatrix}∥∥​ac​bd​∥∥​

`\begin{Vmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{Vmatrix}$

{abcd}\\begin{Bmatrix} a & b \\\\ c & d \\end{Bmatrix}{ac​bd​}

`\begin{Bmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{Bmatrix}$

abcdefghi\\def\\arraystretch{1.5}\\begin{array}{c:c:c} a & b & c \\\\ \\hline d & e & f \\\\ \\hdashline g & h & i \\end{array}adg​beh​cfi​​

`\def\arraystretch{1.5}$  
   `\begin{array}{c:c:c}$  
   `a & b & c \\ \hline$  
   `d & e & f \\$  
   `\hdashline$  
   `g & h & i$  
`\end{array}$

x\={aif bcif dx = \\begin{cases} a &\\text{if } b \\\\ c &\\text{if } d \\end{cases}x\={ac​if bif d​

`x = \begin{cases}$  
   `a &\text{if } b \\$  
   `c &\text{if } d$  
`\end{cases}$

aif bcif d}⇒…\\begin{rcases} a &\\text{if } b \\\\ c &\\text{if } d \\end{rcases}⇒…ac​if bif d​}⇒…

`\begin{rcases}$  
   `a &\text{if } b \\$  
   `c &\text{if } d$  
`\end{rcases}⇒…$

abcd\\begin{smallmatrix} a & b \\\\ c & d \\end{smallmatrix}ac​bd​

`\begin{smallmatrix}$  
   `a & b \\$  
   `c & d$  
`\end{smallmatrix}$

∑i∈Λ0<j<n\\sum\_{\\begin{subarray}{l} i\\in\\Lambda\\\\ 0<j<n\\end{subarray}}i∈Λ0<j<n​∑​

`\sum_{$  
`\begin{subarray}{l}$  
   `i\in\Lambda\\$  
   `0<j<n$  
`\end{subarray}}$

The auto-render extension will render the following environments even if they are not inside math delimiters such as $$$…$$`. They are display-mode only.

#env + table tr td:nth-child(1) { min-width: 11em } #env + table tr td:nth-child(3) { min-width: 13em }

a\=b+c\=e+f\\begin{equation}\\begin{split}a &=b+c\\\\&=e+f\\end{split}\\end{equation}a​\=b+c\=e+f​​​

`\begin{equation}$  
`\begin{split}`   `a &=b+c\\$  
      `&=e+f$  
`\end{split}$  
`\end{equation}$

a\=b+cd+e\=f\\begin{align} a&=b+c \\\\ d+e&=f \\end{align}ad+e​\=b+c\=f​​

`\begin{align}$  
   `a&=b+c \\$  
   `d+e&=f$  
`\end{align}$

a\=be\=b+c\\begin{gather} a=b \\\\ e=b+c \\end{gather}a\=be\=b+c​​

`\begin{gather}$  
   `a=b \\$  
   `e=b+c$  
`\end{gather}$

10x+3y\=23x+13y\=4\\begin{alignat}{2}10&x+&3&y=2\\\\3&x+&13&y=4\\end{alignat}103​x+x+​313​y\=2y\=4​​

`\begin{alignat}{2}$  
   `10&x+&3&y=2\\$  
   `3&x+&13&y=4$  
`\end{alignat}$

A→aBb↓↑cC\=D\\begin{CD}A @>a>> B \\\\@VbVV @AAcA\\\\C @= D\\end{CD}Ab↓⏐​C​a​​B⏐↑​cD​

`\begin{CD}$  
   `A @>a>> B \\$  
`@VbVV @AAcA \\$  
   `C @= D$  
`\end{CD}$

#### [](#other-katex-environments)Other KaTeX Environments

Environments

How they differ from those shown above

`darray`, $dcases`, $drcases$

… apply $displaystyle$

`matrix*`, $pmatrix*`, $bmatrix*$  
`Bmatrix*`, $vmatrix*`, $Vmatrix*$

… take an optional argument to set column  
alignment, as in $\begin{matrix*}[r]$

`equation*`, $gather*$  
`align*`, $alignat*$

… have no automatic numbering.

`gathered`, $aligned`, $alignedat$

… do not need to be in display mode.  
… have no automatic numbering.  
… must be inside math delimiters in  
order to be rendered by the auto-render  
extension.

Acceptable line separators include: $\\`, $\cr`, $\\[distance]`, and $\cr[distance]`. _Distance_ can be written with any of the [KaTeX units](#units).

The ${array}$ environment supports $|$ and $:$ vertical separators.

The ${array}$ environment does not yet support $\cline$ or $\multicolumn`.

`\tag$ can not yet be applied to individual environment rows.

[](#html)HTML
-------------

The following "raw HTML" features are potentially dangerous for untrusted inputs, so they are disabled by default, and attempting to use them produces the command names in red (which you can configure via the $errorColor$ [option](/docs/options.html)). To fully trust your LaTeX input, you need to pass an option of $trust: true`; you can also enable just some of the commands or for just some URLs via the $trust$ [option](/docs/options.html).

KaTeX\\href{https://katex.org/}{\\KaTeX}[KATE​X](https://katex.org/)

`\href{https://katex.org/}{\KaTeX}$

https://katex.org/\\url{https://katex.org/}[https://katex.org/](https://katex.org/)

`\url{https://katex.org/}$

\\includegraphics\[height=0.8em, totalheight=0.9em, width=0.9em, alt=KA logo\]{https://katex.org/img/khan-academy.png}![KA logo](https://katex.org/img/khan-academy.png )

`\includegraphics[height=0.8em, totalheight=0.9em, width=0.9em, alt=KA logo]{https://katex.org/img/khan-academy.png}$

x\\htmlId{bar}{x}x $…<span id="bar" class="enclosing">…x…</span>…$

`\htmlId{bar}{x}$

x\\htmlClass{foo}{x}x $…<span class="enclosing foo">…x…</span>…$

`\htmlClass{foo}{x}$

x\\htmlStyle{color: red;}{x}x $…<span style="color: red;" class="enclosing">…x…</span>…$

`\htmlStyle{color: red;}{x}$

x\\htmlData{foo=a, bar=b}{x}x $…<span data-foo="a" data-bar="b" class="enclosing">…x…</span>…$

`\htmlData{foo=a, bar=b}{x}$

`\includegraphics$ supports $height`, $width`, $totalheight`, and $alt$ in its first argument. $height$ is required.

HTML extension (`\html`\-prefixed) commands are non-standard, so loosening $strict$ option for $htmlExtension$ is required.

[](#letters-and-unicode)Letters and Unicode
-------------------------------------------

**Greek Letters**

Direct Input: ABΓΔEZHΘIKΛMNΞOΠPΣTΥΦXΨΩΑ Β Γ Δ Ε Ζ Η Θ Ι \\allowbreak Κ Λ Μ Ν Ξ Ο Π Ρ Σ Τ Υ Φ Χ Ψ ΩABΓΔEZHΘIKΛMNΞOΠPΣTΥΦXΨΩ αβγδϵζηθικλμνξoπρστυϕχψωεϑϖϱςφϝ\\allowbreak α β γ δ ϵ ζ η θ ι κ λ μ ν ξ o π \\allowbreak ρ σ τ υ ϕ χ ψ ω ε ϑ ϖ ϱ ς φ ϝαβγδϵζηθικλμνξoπρστυϕχψωεϑϖϱςφϝ

A\\AlphaA $\Alpha$

B\\BetaB $\Beta$

Γ\\GammaΓ $\Gamma$

Δ\\DeltaΔ $\Delta$

E\\EpsilonE $\Epsilon$

Z\\ZetaZ $\Zeta$

H\\EtaH $\Eta$

Θ\\ThetaΘ $\Theta$

I\\IotaI $\Iota$

K\\KappaK $\Kappa$

Λ\\LambdaΛ $\Lambda$

M\\MuM $\Mu$

N\\NuN $\Nu$

Ξ\\XiΞ $\Xi$

O\\OmicronO $\Omicron$

Π\\PiΠ $\Pi$

P\\RhoP $\Rho$

Σ\\SigmaΣ $\Sigma$

T\\TauT $\Tau$

Υ\\UpsilonΥ $\Upsilon$

Φ\\PhiΦ $\Phi$

X\\ChiX $\Chi$

Ψ\\PsiΨ $\Psi$

Ω\\OmegaΩ $\Omega$

Γ\\varGammaΓ $\varGamma$

Δ\\varDeltaΔ $\varDelta$

Θ\\varThetaΘ $\varTheta$

Λ\\varLambdaΛ $\varLambda$

Ξ\\varXiΞ $\varXi$

Π\\varPiΠ $\varPi$

Σ\\varSigmaΣ $\varSigma$

Υ\\varUpsilonΥ $\varUpsilon$

Φ\\varPhiΦ $\varPhi$

Ψ\\varPsiΨ $\varPsi$

Ω\\varOmegaΩ $\varOmega$

α\\alphaα $\alpha$

β\\betaβ $\beta$

γ\\gammaγ $\gamma$

δ\\deltaδ $\delta$

ϵ\\epsilonϵ $\epsilon$

ζ\\zetaζ $\zeta$

η\\etaη $\eta$

θ\\thetaθ $\theta$

ι\\iotaι $\iota$

κ\\kappaκ $\kappa$

λ\\lambdaλ $\lambda$

μ\\muμ $\mu$

ν\\nuν $\nu$

ξ\\xiξ $\xi$

ο\\omicronο $\omicron$

π\\piπ $\pi$

ρ\\rhoρ $\rho$

σ\\sigmaσ $\sigma$

τ\\tauτ $\tau$

υ\\upsilonυ $\upsilon$

ϕ\\phiϕ $\phi$

χ\\chiχ $\chi$

ψ\\psiψ $\psi$

ω\\omegaω $\omega$

ε\\varepsilonε $\varepsilon$

ϰ\\varkappaϰ $\varkappa$

ϑ\\varthetaϑ $\vartheta$

ϑ\\thetasymϑ $\thetasym$

ϖ\\varpiϖ $\varpi$

ϱ\\varrhoϱ $\varrho$

ς\\varsigmaς $\varsigma$

φ\\varphiφ $\varphi$

ϝ\\digammaϝ $\digamma$

**Other Letters**

ı\\imath $\imath$

∇\\nabla∇ $\nabla$

ℑ\\Imℑ $\Im$

R\\RealsR $\Reals$

Œ\\text{\\OE}Œ $\text{\OE}$

ȷ\\jmath $\jmath$

∂\\partial∂ $\partial$

ℑ\\imageℑ $\image$

℘\\wp℘ $\wp$

ø\\text{\\o}ø $\text{\o}$

ℵ\\alephℵ $\aleph$

⅁\\Game⅁ $\Game$

k\\Bbbkk $\Bbbk$

℘\\weierp℘ $\weierp$

Ø\\text{\\O}Ø $\text{\O}$

ℵ\\alefℵ $\alef$

Ⅎ\\FinvℲ $\Finv$

N\\NN $\N$

Z\\ZZ $\Z$

ß\\text{\\ss}ß $\text{\ss}$

ℵ\\alefsymℵ $\alefsym$

C\\cnumsC $\cnums$

N\\natnumsN $\natnums$

a˚\\text{\\aa}a˚ $\text{\aa}$

ı\\text{\\i}ı $\text{\i}$

ℶ\\bethℶ $\beth$

C\\ComplexC $\Complex$

R\\RR $\R$

A˚\\text{\\AA}A˚ $\text{\AA}$

ȷ\\text{\\j}ȷ $\text{\j}$

ℷ\\gimelℷ $\gimel$

ℓ\\ellℓ $\ell$

ℜ\\Reℜ $\Re$

æ\\text{\\ae}æ $\text{\ae}$

ℸ\\dalethℸ $\daleth$

ℏ\\hbarℏ $\hbar$

ℜ\\realℜ $\real$

Æ\\text{\\AE}Æ $\text{\AE}$

ð\\ethð $\eth$

ℏ\\hslashℏ $\hslash$

R\\realsR $\reals$

œ\\text{\\oe}œ $\text{\oe}$

Direct Input: ∂∇ℑℲℵℶℷℸ⅁ℏð∂ ∇ ℑ Ⅎ ℵ ℶ ℷ ℸ ⅁ ℏ ð∂∇ℑℲℵℶℷℸ⅁ℏð ÀÁÂÃÄÅÆÇÈÉÊËÌÍÎÏÐÑÒÓÔÕÖÙÚÛÜÝÞßàáâãäåçèéêëìíîïðñòóôöùúûüýþÿ

**Unicode Mathematical Alphanumeric Symbols**

Item

Range

Item

Range

Bold

𝐀-𝐙 𝐚-𝐳 𝟎-𝟗\\text{𝐀-𝐙 𝐚-𝐳 𝟎-𝟗}A\-Z a\-z 0\-9

Double-struck

𝔸-Z 𝕜\\text{𝔸-}ℤ\\ 𝕜A\-Z k

Italic

𝐴-𝑍 𝑎-𝑧\\text{𝐴-𝑍 𝑎-𝑧}A\-Z a\-z

Sans serif

𝖠-𝖹 𝖺-𝗓 𝟢-𝟫\\text{𝖠-𝖹 𝖺-𝗓 𝟢-𝟫}A\-Z a\-z 0\-9

Bold Italic

𝑨-𝒁 𝒂-𝒛\\text{𝑨-𝒁 𝒂-𝒛}A\-Z a\-z

Sans serif bold

𝗔-𝗭 𝗮-𝘇 𝟬-𝟵\\text{𝗔-𝗭 𝗮-𝘇 𝟬-𝟵}A\-Z a\-z 0\-9

Script

𝒜-𝒵\\text{𝒜-𝒵}A\-Z

Sans serif italic

𝘈-𝘡 𝘢-𝘻\\text{𝘈-𝘡 𝘢-𝘻}A\-Z a\-z

Fractur

𝔄-Z 𝔞-𝔷\\text{𝔄-}ℨ\\text{ 𝔞-𝔷}A\-Z a\-z

Monospace

𝙰-𝚉 𝚊-𝚣 𝟶-𝟿\\text{𝙰-𝚉 𝚊-𝚣 𝟶-𝟿}A\-Z a\-z 0\-9

**Unicode**

The letters listed above will render properly in any KaTeX rendering mode.

In addition, Armenian, Brahmic, Georgian, Chinese, Japanese, and Korean glyphs are always accepted in text mode. However, these glyphs will be rendered from system fonts (not KaTeX-supplied fonts) so their typography may clash. You can provide rules for CSS classes $.latin_fallback`, $.cyrillic_fallback`, $.brahmic_fallback`, $.georgian_fallback`, $.cjk_fallback`, and $.hangul_fallback$ to provide fallback fonts for these languages. Use of these glyphs may cause small vertical alignment issues: KaTeX has detailed metrics for listed symbols and most Latin, Greek, and Cyrillic letters, but other accepted glyphs are treated as if they are each as tall as the letter M in the current KaTeX font.

If the KaTeX rendering mode is set to $strict: false$ or $strict: "warn"$ (default), then KaTeX will accept all Unicode letters in both text and math mode. All unrecognized characters will be treated as if they appeared in text mode, and are subject to the same issues of using system fonts and possibly using incorrect vertical alignment.

For Persian composite characters, a user-supplied [plug-in](https://github.com/HosseinAgha/persian-katex-plugin) is under development.

Any character can be written with the $\char$ function and the Unicode code in hex. For example $\char"263a$ will render as ☺\\char"263a☺.

[](#layout)Layout
-----------------

### [](#annotation)Annotation

5\\cancel{5}5​ $\cancel{5}$

a+b+c⏞note\\overbrace{a+b+c}^{\\text{note}}a+b+c​note​ $\overbrace{a+b+c}^{\text{note}}$

5\\bcancel{5}5​ $\bcancel{5}$

a+b+c⏟note\\underbrace{a+b+c}\_{\\text{note}}notea+b+c​​ $\underbrace{a+b+c}_{\text{note}}$

ABC\\xcancel{ABC}ABC $\xcancel{ABC}$

\≠\\not =\= $\not =$

abc\\sout{abc}abc $\sout{abc}$

π\=cd\\boxed{\\pi=\\frac c d}π\=dc​​ $\boxed{\pi=\frac c d}$

ana\_{\\angl n}an​​ $$a_{\angl n}$

ana\_\\anglnan​​ $a_\angln$

−78∘\\phase{-78^\\circ}−78∘​`\phase{-78^\circ}$

`\tag{hi} x+y^{2x}$ x+y2x(hi)\\tag{hi} x+y^{2x}x+y2x(hi)

`\tag*{hi} x+y^{2x}$ x+y2xhi\\tag\*{hi} x+y^{2x}x+y2xhi

### [](#line-breaks)Line Breaks

KaTeX 0.10.0+ will insert automatic line breaks in inline math after relations or binary operators such as “=” or “+”. These can be suppressed by $\nobreak$ or by placing math inside a pair of braces, as in ${F=ma}`. $\allowbreak$ will allow automatic line breaks at locations other than relations or operators.

Hard line breaks are $\\$ and $\newline`.

In display math, KaTeX does not insert automatic line breaks. It ignores display math hard line breaks when rendering option $strict: true`.

### [](#vertical-layout)Vertical Layout

xnx\_nxn​ $x_n$

\=!\\stackrel{!}{=}\=! $\stackrel{!}{=}$

aba \\atop bba​ $a \atop b$

exe^xex $e^x$

\=!\\overset{!}{=}\=! $\overset{!}{=}$

abca\\raisebox{0.25em}{$b$}cabc $a\raisebox{0.25em}{$b$}c$

uo\_u^ouo​ $_u^o$

\=!\\underset{!}{=}!\=​ $\underset{!}{=}$

a+(abc)a+\\left(\\vcenter{\\frac{\\frac a b}c}\\right)a+(cba​​​) $a+\left(\vcenter{\hbox{$\frac{\frac a b}c$}}\right)$

∑0<i<m0<j<n\\sum\_{\\substack{0<i<m\\\\0<j<n}}0<i<m0<j<n​∑​ $\sum_{\substack{0<i<m\\0<j<n}}$

`\raisebox$ and $\hbox$ put their argument into text mode. To raise math, nest $$…$$ delimiters inside the argument as shown above.

`\vcenter$ can be written without an $\hbox$ if the $strict$ rendering option is _false_. In that case, omit the nested $$…$$ delimiters.

### [](#overlap-and-spacing)Overlap and Spacing

\=/ {=}\\mathllap{/\\,}\=/ ${=}\mathllap{/\,}$

(x2)\\left(x^{\\smash{2}}\\right)(x2) $\left(x^{\smash{2}}\right)$

 /\=\\mathrlap{\\,/}{=}/\= $\mathrlap{\,/}{=}$

y\\sqrt{\\smash\[b\]{y}}y​ $\sqrt{\smash[b]{y}}$

∑1≤i≤j≤nxij\\displaystyle\\sum\_{\\mathclap{1\\le i\\le j\\le n}} x\_{ij}1≤i≤j≤n∑​xij​ $\sum_{\mathclap{1\le i\le j\le n}} x_{ij}$

KaTeX also supports $\llap`, $\rlap`, and $\clap`, but they will take only text, not math, as arguments.

**Spacing**

Function

Produces

Function

Produces

`\,$

³∕₁₈ em space

`\kern{distance}$

space, width = _distance_

`\thinspace$

³∕₁₈ em space

`\mkern{distance}$

space, width = _distance_

`\>$

⁴∕₁₈ em space

`\mskip{distance}$

space, width = _distance_

`\:$

⁴∕₁₈ em space

`\hskip{distance}$

space, width = _distance_

`\medspace$

⁴∕₁₈ em space

`\hspace{distance}$

space, width = _distance_

`\;$

⁵∕₁₈ em space

`\hspace*{distance}$

space, width = _distance_

`\thickspace$

⁵∕₁₈ em space

`\phantom{content}$

space the width and height of content

`\enspace$

½ em space

`\hphantom{content}$

space the width of content

`\quad$

1 em space

`\vphantom{content}$

a strut the height of content

`\qquad$

2 em space

`\!$

– ³∕₁₈ em space

`~$

non-breaking space

`\negthinspace$

– ³∕₁₈ em space

`\<space>$

space

`\negmedspace$

– ⁴∕₁₈ em space

`\nobreakspace$

non-breaking space

`\negthickspace$

– ⁵∕₁₈ em space

`\space$

space

`\mathstrut$

`\vphantom{(}$

**Notes:**

`distance$ will accept any of the [KaTeX units](#units).

`\kern`, $\mkern`, $\mskip`, and $\hspace$ accept unbraced distances, as in: $\kern1em`.

`\mkern$ and $\mskip$ will not work in text mode and both will write a console warning for any unit except $mu`.

[](#logic-and-set-theory)Logic and Set Theory
---------------------------------------------

∀\\forall∀ $\forall$

∁\\complement∁ $\complement$

∴\\therefore∴ $\therefore$

∅\\emptyset∅ $\emptyset$

∃\\exists∃ $\exists$

⊂\\subset⊂ $\subset$

∵\\because∵ $\because$

∅\\empty∅ $\empty$

∃\\exist∃ $\exist$

⊃\\supset⊃ $\supset$

↦\\mapsto↦ $\mapsto$

∅\\varnothing∅ $\varnothing$

∄\\nexists∄ $\nexists$

∣\\mid∣ $\mid$

→\\to→ $\to$

 ⟹ \\implies⟹ $\implies$

∈\\in∈ $\in$

∧\\land∧ $\land$

←\\gets← $\gets$

 ⟸ \\impliedby⟸ $\impliedby$

∈\\isin∈ $\isin$

∨\\lor∨ $\lor$

↔\\leftrightarrow↔ $\leftrightarrow$

 ⟺ \\iff⟺ $\iff$

∉\\notin∈/ $\notin$

∋\\ni∋ $\ni$

∌\\notni∋ $\notni$

¬\\neg¬ $\neg$ or $\lnot$

Direct Input: ∀∴∁∵∃∣∈∉∋⊂⊃∧∨↦→←↔¬∀ ∴ ∁ ∵ ∃ ∣ ∈ ∉ ∋ ⊂ ⊃ ∧ ∨ ↦ → ← ↔ ¬∀∴∁∵∃∣∈∈/∋⊂⊃∧∨↦→←↔¬ ℂ ℍ ℕ ℙ ℚ ℝ

[](#macros)Macros
-----------------

x2+x2\\def\\foo{x^2} \\foo + \\foox2+x2

`\def\foo{x^2} \foo + \foo$

y2+y2\\gdef\\bar#1{#1^2} \\bar{y} + \\bar{y}y2+y2

`\gdef\bar#1{#1^2} \bar{y} + \bar{y}$

`\edef\macroname#1#2…{definition to be expanded}$

`\xdef\macroname#1#2…{definition to be expanded}$

`\let\foo=\bar$

`\futurelet\foo\bar x$

`\global\def\macroname#1#2…{definition}$

`\newcommand\macroname[numargs]{definition}$

`\renewcommand\macroname[numargs]{definition}$

`\providecommand\macroname[numargs]{definition}$

Macros can also be defined in the KaTeX [rendering options](/docs/options.html).

Macros accept up to nine arguments: #1, #2, etc.

Macros defined by $\gdef`, $\xdef`, $\global\def`, $\global\edef`, $\global\let`, and $\global\futurelet$ will persist between math expressions. (Exception: macro persistence may be disabled. There are legitimate security reasons for that.)

KaTeX has no $\par`, so all macros are long by default and $\long$ will be ignored.

Available functions include:

`\char$ $\mathchoice$ $\TextOrMath$ $\@ifstar$ $\@ifnextchar$ $\@firstoftwo$ $\@secondoftwo$ $\relax$ $\expandafter$ $\noexpand$

@ is a valid character for commands, as if $\makeatletter$ were in effect.

[](#operators)Operators
-----------------------

### [](#big-operators)Big Operators

∑\\sum∑ $\sum$

∏\\prod∏ $\prod$

⨂\\bigotimes⨂ $\bigotimes$

⋁\\bigvee⋁ $\bigvee$

∫\\int∫ $\int$

∐\\coprod∐ $\coprod$

⨁\\bigoplus⨁ $\bigoplus$

⋀\\bigwedge⋀ $\bigwedge$

∬\\iint∬ $\iint$

∫\\intop∫ $\intop$

⨀\\bigodot⨀ $\bigodot$

⋂\\bigcap⋂ $\bigcap$

∭\\iiint∭ $\iiint$

∫\\smallint∫ $\smallint$

⨄\\biguplus⨄ $\biguplus$

⋃\\bigcup⋃ $\bigcup$

∮\\oint∮ $\oint$

∯\\oiint∬​ $\oiint$

∰\\oiiint∭​ $\oiiint$

⨆\\bigsqcup⨆ $\bigsqcup$

Direct Input: ∫∬∭∮∏∐∑⋀⋁⋂⋃⨀⨁⨂⨄⨆∫ ∬ ∭ ∮ ∏ ∐ ∑ ⋀ ⋁ ⋂ ⋃ ⨀ ⨁ ⨂ ⨄ ⨆∫∬∭∮∏∐∑⋀⋁⋂⋃⨀⨁⨂⨄⨆ ∯ ∰

### [](#binary-operators)Binary Operators

+++ $+$

⋅\\cdot⋅ $\cdot$

⋗\\gtrdot⋗ $\gtrdot$

x(moda)x \\pmod ax(moda) $x \pmod a$

−\-− $-$

⋅\\cdotp⋅ $\cdotp$

⊺\\intercal⊺ $\intercal$

x(a)x \\pod ax(a) $x \pod a$

/// $/$

⋅\\centerdot⋅ $\centerdot$

∧\\land∧ $\land$

⊳\\rhd⊳ $\rhd$

∗\*∗ $*$

∘\\circ∘ $\circ$

⋋\\leftthreetimes⋋ $\leftthreetimes$

⋌\\rightthreetimes⋌ $\rightthreetimes$

⨿\\amalg⨿ $\amalg$

⊛\\circledast⊛ $\circledast$

.\\ldotp. $\ldotp$

⋊\\rtimes⋊ $\rtimes$

&\\And& $\And$

⊚\\circledcirc⊚ $\circledcirc$

∨\\lor∨ $\lor$

∖\\setminus∖ $\setminus$

∗\\ast∗ $\ast$

⊝\\circleddash⊝ $\circleddash$

⋖\\lessdot⋖ $\lessdot$

∖\\smallsetminus∖ $\smallsetminus$

⊼\\barwedge⊼ $\barwedge$

⋓\\Cup⋓ $\Cup$

⊲\\lhd⊲ $\lhd$

⊓\\sqcap⊓ $\sqcap$

◯\\bigcirc◯ $\bigcirc$

∪\\cup∪ $\cup$

⋉\\ltimes⋉ $\ltimes$

⊔\\sqcup⊔ $\sqcup$

 mod \\bmodmod $\bmod$

⋎\\curlyvee⋎ $\curlyvee$

xmod  ax \\mod axmoda $x\mod a$

×\\times× $\times$

⊡\\boxdot⊡ $\boxdot$

⋏\\curlywedge⋏ $\curlywedge$

∓\\mp∓ $\mp$

⊴\\unlhd⊴ $\unlhd$

⊟\\boxminus⊟ $\boxminus$

÷\\div÷ $\div$

⊙\\odot⊙ $\odot$

⊵\\unrhd⊵ $\unrhd$

⊞\\boxplus⊞ $\boxplus$

⋇\\divideontimes⋇ $\divideontimes$

⊖\\ominus⊖ $\ominus$

⊎\\uplus⊎ $\uplus$

⊠\\boxtimes⊠ $\boxtimes$

∔\\dotplus∔ $\dotplus$

⊕\\oplus⊕ $\oplus$

∨\\vee∨ $\vee$

∙\\bullet∙ $\bullet$

⩞\\doublebarwedge⩞ $\doublebarwedge$

⊗\\otimes⊗ $\otimes$

⊻\\veebar⊻ $\veebar$

⋒\\Cap⋒ $\Cap$

⋒\\doublecap⋒ $\doublecap$

⊘\\oslash⊘ $\oslash$

∧\\wedge∧ $\wedge$

∩\\cap∩ $\cap$

⋓\\doublecup⋓ $\doublecup$

±\\pm± $\pm$ or $\plusmn$

≀\\wr≀ $\wr$

Direct Input: +−/∗⋅±×÷∓∔∧∨∩∪≀⊎⊓⊔⊕⊖⊗⊘⊙⊚⊛⊝◯\+ - / \* ⋅ ± × ÷ ∓ ∔ ∧ ∨ ∩ ∪ ≀ ⊎ ⊓ ⊔ ⊕ ⊖ ⊗ ⊘ ⊙ ⊚ ⊛ ⊝ ◯+−/∗⋅±×÷∓∔∧∨∩∪≀⊎⊓⊔⊕⊖⊗⊘⊙⊚⊛⊝◯

### [](#fractions-and-binomials)Fractions and Binomials

ab\\frac{a}{b}ba​ $\frac{a}{b}$

ab\\tfrac{a}{b}ba​ $\tfrac{a}{b}$

(aa+1\]\\genfrac ( \] {2pt}{1}a{a+1}(a+1a​\] $\genfrac ( ] {2pt}{1}a{a+1}$

ab{a \\over b}ba​ ${a \over b}$

ab\\dfrac{a}{b}ba​ $\dfrac{a}{b}$

ab+1{a \\above{2pt} b+1}b+1a​ ${a \above{2pt} b+1}$

a/ba/ba/b $a/b$

a1+1b\\cfrac{a}{1 + \\cfrac{1}{b}}1+b1​a​ $\cfrac{a}{1 + \cfrac{1}{b}}$

(nk)\\binom{n}{k}(kn​) $\binom{n}{k}$

(nk)\\dbinom{n}{k}(kn​) $\dbinom{n}{k}$

{nk}{n\\brace k}{kn​} ${n\brace k}$

(nk){n \\choose k}(kn​) ${n \choose k}$

(nk)\\tbinom{n}{k}(kn​) $\tbinom{n}{k}$

\[nk\]{n\\brack k}\[kn​\] ${n\brack k}$

### [](#math-operators)Math Operators

arcsin⁡\\arcsinarcsin $\arcsin$

cosec⁡\\coseccosec $\cosec$

deg⁡\\degdeg $\deg$

sec⁡\\secsec $\sec$

arccos⁡\\arccosarccos $\arccos$

cosh⁡\\coshcosh $\cosh$

dim⁡\\dimdim $\dim$

sin⁡\\sinsin $\sin$

arctan⁡\\arctanarctan $\arctan$

cot⁡\\cotcot $\cot$

exp⁡\\expexp $\exp$

sinh⁡\\sinhsinh $\sinh$

arctg⁡\\arctgarctg $\arctg$

cotg⁡\\cotgcotg $\cotg$

hom⁡\\homhom $\hom$

sh⁡\\shsh $\sh$

arcctg⁡\\arcctgarcctg $\arcctg$

coth⁡\\cothcoth $\coth$

ker⁡\\kerker $\ker$

tan⁡\\tantan $\tan$

arg⁡\\argarg $\arg$

csc⁡\\csccsc $\csc$

lg⁡\\lglg $\lg$

tanh⁡\\tanhtanh $\tanh$

ch⁡\\chch $\ch$

ctg⁡\\ctgctg $\ctg$

ln⁡\\lnln $\ln$

tg⁡\\tgtg $\tg$

cos⁡\\coscos $\cos$

cth⁡\\cthcth $\cth$

log⁡\\loglog $\log$

th⁡\\thth $\th$

f⁡\\operatorname{f}f $\operatorname{f}$

arg max⁡\\argmaxargmax $\argmax$

inj lim⁡\\injliminjlim $\injlim$

min⁡\\minmin $\min$

lim→⁡\\varinjlimlim​ $\varinjlim$

arg min⁡\\argminargmin $\argmin$

lim⁡\\limlim $\lim$

plim⁡\\plimplim $\plim$

lim‾⁡\\varliminflim​ $\varliminf$

det⁡\\detdet $\det$

lim inf⁡\\liminfliminf $\liminf$

Pr⁡\\PrPr $\Pr$

lim‾⁡\\varlimsuplim $\varlimsup$

gcd⁡\\gcdgcd $\gcd$

lim sup⁡\\limsuplimsup $\limsup$

proj lim⁡\\projlimprojlim $\projlim$

lim←⁡\\varprojlimlim​ $\varprojlim$

inf⁡\\infinf $\inf$

max⁡\\maxmax $\max$

sup⁡\\supsup $\sup$

f⁡\\operatorname\*{f}f $\operatorname*{f}$

f⁡\\operatornamewithlimits{f}f $\operatornamewithlimits{f}$

Functions in the bottom six rows of this table can take $\limits`.

### [](#sqrt)\\sqrt

x\\sqrt{x}x​ $\sqrt{x}$

x3\\sqrt\[3\]{x}3x​ $\sqrt[3]{x}$

[](#relations)Relations
-----------------------

\=!\\stackrel{!}{=}\=! $\stackrel{!}{=}$

\=\=\= $=$

≑\\doteqdot≑ $\doteqdot$

⪅\\lessapprox⪅ $\lessapprox$

⌣\\smile⌣ $\smile$

<<< $<$

≖\\eqcirc≖ $\eqcirc$

⋚\\lesseqgtr⋚ $\lesseqgtr$

⊏\\sqsubset⊏ $\sqsubset$

\>\>\> $>$

∹\\eqcolon−: $\eqcolon$ or  
`\minuscolon$

⪋\\lesseqqgtr⪋ $\lesseqqgtr$

⊑\\sqsubseteq⊑ $\sqsubseteq$

::: $:$

−∷\\Eqcolon−:: $\Eqcolon$ or  
`\minuscoloncolon$

≶\\lessgtr≶ $\lessgtr$

⊐\\sqsupset⊐ $\sqsupset$

≈\\approx≈ $\approx$

≕\\eqqcolon\=: $\eqqcolon$ or  
`\equalscolon$

≲\\lesssim≲ $\lesssim$

⊒\\sqsupseteq⊒ $\sqsupseteq$

≈:\\approxcolon≈: $\approxcolon$

\=∷\\Eqqcolon\=:: $\Eqqcolon$ or  
`\equalscoloncolon$

≪\\ll≪ $\ll$

⋐\\Subset⋐ $\Subset$

≈∷\\approxcoloncolon≈:: $\approxcoloncolon$

≂\\eqsim≂ $\eqsim$

⋘\\lll⋘ $\lll$

⊂\\subset⊂ $\subset$ or $\sub$

≊\\approxeq≊ $\approxeq$

⪖\\eqslantgtr⪖ $\eqslantgtr$

⋘\\llless⋘ $\llless$

⊆\\subseteq⊆ $\subseteq$ or $\sube$

≍\\asymp≍ $\asymp$

⪕\\eqslantless⪕ $\eqslantless$

<\\lt< $\lt$

⫅\\subseteqq⫅ $\subseteqq$

∍\\backepsilon∍ $\backepsilon$

≡\\equiv≡ $\equiv$

∣\\mid∣ $\mid$

≻\\succ≻ $\succ$

∽\\backsim∽ $\backsim$

≒\\fallingdotseq≒ $\fallingdotseq$

⊨\\models⊨ $\models$

⪸\\succapprox⪸ $\succapprox$

⋍\\backsimeq⋍ $\backsimeq$

⌢\\frown⌢ $\frown$

⊸\\multimap⊸ $\multimap$

≽\\succcurlyeq≽ $\succcurlyeq$

≬\\between≬ $\between$

≥\\ge≥ $\ge$

⊶\\origof⊶ $\origof$

⪰\\succeq⪰ $\succeq$

⋈\\bowtie⋈ $\bowtie$

≥\\geq≥ $\geq$

∋\\owns∋ $\owns$

≿\\succsim≿ $\succsim$

≏\\bumpeq≏ $\bumpeq$

≧\\geqq≧ $\geqq$

∥\\parallel∥ $\parallel$

⋑\\Supset⋑ $\Supset$

≎\\Bumpeq≎ $\Bumpeq$

⩾\\geqslant⩾ $\geqslant$

⊥\\perp⊥ $\perp$

⊃\\supset⊃ $\supset$

≗\\circeq≗ $\circeq$

≫\\gg≫ $\gg$

⋔\\pitchfork⋔ $\pitchfork$

⊇\\supseteq⊇ $\supseteq$ or $\supe$

:≈\\colonapprox:≈ $\colonapprox$

⋙\\ggg⋙ $\ggg$

≺\\prec≺ $\prec$

⫆\\supseteqq⫆ $\supseteqq$

∷≈\\Colonapprox::≈ $\Colonapprox$ or  
`\coloncolonapprox$

⋙\\gggtr⋙ $\gggtr$

⪷\\precapprox⪷ $\precapprox$

≈\\thickapprox≈ $\thickapprox$

:−\\coloneq:− $\coloneq$ or  
`\colonminus$

\>\\gt\> $\gt$

≼\\preccurlyeq≼ $\preccurlyeq$

∼\\thicksim∼ $\thicksim$

∷−\\Coloneq::− $\Coloneq$ or  
`\coloncolonminus$

⪆\\gtrapprox⪆ $\gtrapprox$

⪯\\preceq⪯ $\preceq$

⊴\\trianglelefteq⊴ $\trianglelefteq$

≔\\coloneqq:\= $\coloneqq$ or  
`\colonequals$

⋛\\gtreqless⋛ $\gtreqless$

≾\\precsim≾ $\precsim$

≜\\triangleq≜ $\triangleq$

∷\=\\Coloneqq::\= $\Coloneqq$ or  
`\coloncolonequals$

⪌\\gtreqqless⪌ $\gtreqqless$

∝\\propto∝ $\propto$

⊵\\trianglerighteq⊵ $\trianglerighteq$

:∼\\colonsim:∼ $\colonsim$

≷\\gtrless≷ $\gtrless$

≓\\risingdotseq≓ $\risingdotseq$

∝\\varpropto∝ $\varpropto$

∷∼\\Colonsim::∼ $\Colonsim$ or  
`\coloncolonsim$

≳\\gtrsim≳ $\gtrsim$

∣\\shortmid∣ $\shortmid$

△\\vartriangle△ $\vartriangle$

≅\\cong≅ $\cong$

⊷\\imageof⊷ $\imageof$

∥\\shortparallel∥ $\shortparallel$

⊲\\vartriangleleft⊲ $\vartriangleleft$

⋞\\curlyeqprec⋞ $\curlyeqprec$

∈\\in∈ $\in$ or $\isin$

∼\\sim∼ $\sim$

⊳\\vartriangleright⊳ $\vartriangleright$

⋟\\curlyeqsucc⋟ $\curlyeqsucc$

⋈\\Join⋈ $\Join$

∼:\\simcolon∼: $\simcolon$

:\\vcentcolon: $\vcentcolon$ or  
`\ratio$

⊣\\dashv⊣ $\dashv$

≤\\le≤ $\le$

∼∷\\simcoloncolon∼:: $\simcoloncolon$

⊢\\vdash⊢ $\vdash$

∷\\dblcolon:: $\dblcolon$ or  
`\coloncolon$

≤\\leq≤ $\leq$

≃\\simeq≃ $\simeq$

⊨\\vDash⊨ $\vDash$

≐\\doteq≐ $\doteq$

≦\\leqq≦ $\leqq$

⌢\\smallfrown⌢ $\smallfrown$

⊩\\Vdash⊩ $\Vdash$

≑\\Doteq≑ $\Doteq$

⩽\\leqslant⩽ $\leqslant$

⌣\\smallsmile⌣ $\smallsmile$

⊪\\Vvdash⊪ $\Vvdash$

Direct Input: \=<\>:∈∋∝∼∽≂≃≅≈≊≍≎≏≐≑≒≓≖≗≜≡≤≥≦≧≫≬≳≷≺≻≼≽≾≿⊂⊃⊆⊇⊏⊐⊑⊒⊢⊣⊩⊪⊸⋈⋍⋐⋑⋔⋙⋛⋞⋟⌢⌣⩾⪆⪌⪕⪖⪯⪰⪷⪸⫅⫆≲⩽⪅≶⋚⪋⊥⊨⊶⊷\= < > : ∈ ∋ ∝ ∼ ∽ ≂ ≃ ≅ ≈ ≊ ≍ ≎ ≏ ≐ ≑ ≒ ≓ ≖ ≗ ≜ ≡ ≤ ≥ ≦ ≧ ≫ ≬ ≳ ≷ ≺ ≻ ≼ ≽ ≾ ≿ ⊂ ⊃ ⊆ ⊇ ⊏ ⊐ ⊑ ⊒ ⊢ ⊣ ⊩ ⊪ ⊸ ⋈ ⋍ ⋐ ⋑ ⋔ ⋙ ⋛ ⋞ ⋟ ⌢ ⌣ ⩾ ⪆ ⪌ ⪕ ⪖ ⪯ ⪰ ⪷ ⪸ ⫅ ⫆ ≲ ⩽ ⪅ ≶ ⋚ ⪋ ⟂ ⊨ ⊶ ⊷\=<>:∈∋∝∼∽≂≃≅≈≊≍≎≏≐≑≒≓≖≗≜≡≤≥≦≧≫≬≳≷≺≻≼≽≾≿⊂⊃⊆⊇⊏⊐⊑⊒⊢⊣⊩⊪⊸⋈⋍⋐⋑⋔⋙⋛⋞⋟⌢⌣⩾⪆⪌⪕⪖⪯⪰⪷⪸⫅⫆≲⩽⪅≶⋚⪋⊥⊨⊶⊷ $≔ ≕ ⩴$

### [](#negated-relations)Negated Relations

\≠\\not =\= $\not =$

⪊\\gnapprox⪊ $\gnapprox$

≱\\ngeqslant $\ngeqslant$

⊈\\nsubseteq⊈ $\nsubseteq$

⪵\\precneqq⪵ $\precneqq$

⪈\\gneq⪈ $\gneq$

≯\\ngtr≯ $\ngtr$

⊈\\nsubseteqq $\nsubseteqq$

⋨\\precnsim⋨ $\precnsim$

≩\\gneqq≩ $\gneqq$

≰\\nleq≰ $\nleq$

⊁\\nsucc⊁ $\nsucc$

⊊\\subsetneq⊊ $\subsetneq$

⋧\\gnsim⋧ $\gnsim$

≰\\nleqq $\nleqq$

⋡\\nsucceq⋡ $\nsucceq$

⫋\\subsetneqq⫋ $\subsetneqq$

≩\\gvertneqq $\gvertneqq$

≰\\nleqslant $\nleqslant$

⊉\\nsupseteq⊉ $\nsupseteq$

⪺\\succnapprox⪺ $\succnapprox$

⪉\\lnapprox⪉ $\lnapprox$

≮\\nless≮ $\nless$

⊉\\nsupseteqq $\nsupseteqq$

⪶\\succneqq⪶ $\succneqq$

⪇\\lneq⪇ $\lneq$

∤\\nmid∤ $\nmid$

⋪\\ntriangleleft⋪ $\ntriangleleft$

⋩\\succnsim⋩ $\succnsim$

≨\\lneqq≨ $\lneqq$

∉\\notin∈/ $\notin$

⋬\\ntrianglelefteq⋬ $\ntrianglelefteq$

⊋\\supsetneq⊋ $\supsetneq$

⋦\\lnsim⋦ $\lnsim$

∌\\notni∋ $\notni$

⋫\\ntriangleright⋫ $\ntriangleright$

⫌\\supsetneqq⫌ $\supsetneqq$

≨\\lvertneqq $\lvertneqq$

∦\\nparallel∦ $\nparallel$

⋭\\ntrianglerighteq⋭ $\ntrianglerighteq$

⊊\\varsubsetneq $\varsubsetneq$

≆\\ncong≆ $\ncong$

⊀\\nprec⊀ $\nprec$

⊬\\nvdash⊬ $\nvdash$

⫋\\varsubsetneqq $\varsubsetneqq$

≠\\ne\= $\ne$

⋠\\npreceq⋠ $\npreceq$

⊭\\nvDash⊭ $\nvDash$

⊋\\varsupsetneq $\varsupsetneq$

≠\\neq\= $\neq$

∤\\nshortmid $\nshortmid$

⊯\\nVDash⊯ $\nVDash$

⫌\\varsupsetneqq $\varsupsetneqq$

≱\\ngeq≱ $\ngeq$

∦\\nshortparallel $\nshortparallel$

⊮\\nVdash⊮ $\nVdash$

≱\\ngeqq $\ngeqq$

≁\\nsim≁ $\nsim$

⪹\\precnapprox⪹ $\precnapprox$

Direct Input: ∉∌∤∦≁≆≠≨≩≮≯≰≱⊀⊁⊈⊉⊊⊋⊬⊭⊮⊯⋠⋡⋦⋧⋨⋩⋬⋭⪇⪈⪉⪊⪵⪶⪹⪺⫋⫌∉ ∌ ∤ ∦ ≁ ≆ ≠ ≨ ≩ ≮ ≯ ≰ ≱ ⊀ ⊁ ⊈ ⊉ ⊊ ⊋ ⊬ ⊭ ⊮ ⊯ ⋠ ⋡ ⋦ ⋧ ⋨ ⋩ ⋬ ⋭ ⪇ ⪈ ⪉ ⪊ ⪵ ⪶ ⪹ ⪺ ⫋ ⫌∈/∋∤∦≁≆\=≨≩≮≯≰≱⊀⊁⊈⊉⊊⊋⊬⊭⊮⊯⋠⋡⋦⋧⋨⋩⋬⋭⪇⪈⪉⪊⪵⪶⪹⪺⫋⫌

### [](#arrows)Arrows

↺\\circlearrowleft↺ $\circlearrowleft$

↼\\leftharpoonup↼ $\leftharpoonup$

⇒\\rArr⇒ $\rArr$

↻\\circlearrowright↻ $\circlearrowright$

⇇\\leftleftarrows⇇ $\leftleftarrows$

→\\rarr→ $\rarr$

↶\\curvearrowleft↶ $\curvearrowleft$

↔\\leftrightarrow↔ $\leftrightarrow$

↾\\restriction↾ $\restriction$

↷\\curvearrowright↷ $\curvearrowright$

⇔\\Leftrightarrow⇔ $\Leftrightarrow$

→\\rightarrow→ $\rightarrow$

⇓\\Darr⇓ $\Darr$

⇆\\leftrightarrows⇆ $\leftrightarrows$

⇒\\Rightarrow⇒ $\Rightarrow$

⇓\\dArr⇓ $\dArr$

⇋\\leftrightharpoons⇋ $\leftrightharpoons$

↣\\rightarrowtail↣ $\rightarrowtail$

↓\\darr↓ $\darr$

↭\\leftrightsquigarrow↭ $\leftrightsquigarrow$

⇁\\rightharpoondown⇁ $\rightharpoondown$

⇠\\dashleftarrow⇠ $\dashleftarrow$

⇚\\Lleftarrow⇚ $\Lleftarrow$

⇀\\rightharpoonup⇀ $\rightharpoonup$

⇢\\dashrightarrow⇢ $\dashrightarrow$

⟵\\longleftarrow⟵ $\longleftarrow$

⇄\\rightleftarrows⇄ $\rightleftarrows$

↓\\downarrow↓ $\downarrow$

⟸\\Longleftarrow⟸ $\Longleftarrow$

⇌\\rightleftharpoons⇌ $\rightleftharpoons$

⇓\\Downarrow⇓ $\Downarrow$

⟷\\longleftrightarrow⟷ $\longleftrightarrow$

⇉\\rightrightarrows⇉ $\rightrightarrows$

⇊\\downdownarrows⇊ $\downdownarrows$

⟺\\Longleftrightarrow⟺ $\Longleftrightarrow$

⇝\\rightsquigarrow⇝ $\rightsquigarrow$

⇃\\downharpoonleft⇃ $\downharpoonleft$

⟼\\longmapsto⟼ $\longmapsto$

⇛\\Rrightarrow⇛ $\Rrightarrow$

⇂\\downharpoonright⇂ $\downharpoonright$

⟶\\longrightarrow⟶ $\longrightarrow$

↱\\Rsh↱ $\Rsh$

←\\gets← $\gets$

⟹\\Longrightarrow⟹ $\Longrightarrow$

↘\\searrow↘ $\searrow$

⇔\\Harr⇔ $\Harr$

↫\\looparrowleft↫ $\looparrowleft$

↙\\swarrow↙ $\swarrow$

⇔\\hArr⇔ $\hArr$

↬\\looparrowright↬ $\looparrowright$

→\\to→ $\to$

↔\\harr↔ $\harr$

⇔\\Lrarr⇔ $\Lrarr$

↞\\twoheadleftarrow↞ $\twoheadleftarrow$

↩\\hookleftarrow↩ $\hookleftarrow$

⇔\\lrArr⇔ $\lrArr$

↠\\twoheadrightarrow↠ $\twoheadrightarrow$

↪\\hookrightarrow↪ $\hookrightarrow$

↔\\lrarr↔ $\lrarr$

⇑\\Uarr⇑ $\Uarr$

 ⟺ \\iff⟺ $\iff$

↰\\Lsh↰ $\Lsh$

⇑\\uArr⇑ $\uArr$

 ⟸ \\impliedby⟸ $\impliedby$

↦\\mapsto↦ $\mapsto$

↑\\uarr↑ $\uarr$

 ⟹ \\implies⟹ $\implies$

↗\\nearrow↗ $\nearrow$

↑\\uparrow↑ $\uparrow$

⇐\\Larr⇐ $\Larr$

↚\\nleftarrow↚ $\nleftarrow$

⇑\\Uparrow⇑ $\Uparrow$

⇐\\lArr⇐ $\lArr$

⇍\\nLeftarrow⇍ $\nLeftarrow$

↕\\updownarrow↕ $\updownarrow$

←\\larr← $\larr$

↮\\nleftrightarrow↮ $\nleftrightarrow$

⇕\\Updownarrow⇕ $\Updownarrow$

⇝\\leadsto⇝ $\leadsto$

⇎\\nLeftrightarrow⇎ $\nLeftrightarrow$

↿\\upharpoonleft↿ $\upharpoonleft$

←\\leftarrow← $\leftarrow$

↛\\nrightarrow↛ $\nrightarrow$

↾\\upharpoonright↾ $\upharpoonright$

⇐\\Leftarrow⇐ $\Leftarrow$

⇏\\nRightarrow⇏ $\nRightarrow$

⇈\\upuparrows⇈ $\upuparrows$

↢\\leftarrowtail↢ $\leftarrowtail$

↖\\nwarrow↖ $\nwarrow$

↽\\leftharpoondown↽ $\leftharpoondown$

⇒\\Rarr⇒ $\Rarr$

Direct Input: ←↑→↓↔↕↖↗↘↙↚↛↞↠↢↣↦↩↪↫↬↭↮↰↱↶↷↺↻↼↽↾↾↿⇀⇁⇂⇃⇄⇆⇇⇈⇉⇊⇋⇌⇍⇎⇏⇐⇑⇒⇓⇔⇕⇚⇛⇝⇠⇢⟵⟶⟷⟸⟹⟺⟼← ↑ → ↓ ↔ ↕ ↖ ↗ ↘ ↙ ↚ ↛ ↞ ↠ ↢ ↣ ↦ ↩ ↪ ↫ ↬ ↭ ↮ ↰ ↱↶ ↷ ↺ ↻ ↼ ↽ ↾ ↾ ↿ ⇀ ⇁ ⇂ ⇃ ⇄ ⇆ ⇇ ⇈ ⇉ ⇊ ⇋ ⇌⇍ ⇎ ⇏ ⇐ ⇑ ⇒ ⇓ ⇔ ⇕ ⇚ ⇛ ⇝ ⇠ ⇢ ⟵ ⟶ ⟷ ⟸ ⟹ ⟺ ⟼←↑→↓↔↕↖↗↘↙↚↛↞↠↢↣↦↩↪↫↬↭↮↰↱↶↷↺↻↼↽↾↾↿⇀⇁⇂⇃⇄⇆⇇⇈⇉⇊⇋⇌⇍⇎⇏⇐⇑⇒⇓⇔⇕⇚⇛⇝⇠⇢⟵⟶⟷⟸⟹⟺⟼ ↽

**Extensible Arrows**

←abc\\xleftarrow{abc}abc​ $\xleftarrow{abc}$

→underover\\xrightarrow\[under\]{over}overunder​ $\xrightarrow[under]{over}$

⇐abc\\xLeftarrow{abc}abc​ $\xLeftarrow{abc}$

⇒abc\\xRightarrow{abc}abc​ $\xRightarrow{abc}$

↔abc\\xleftrightarrow{abc}abc​ $\xleftrightarrow{abc}$

⇔abc\\xLeftrightarrow{abc}abc​ $\xLeftrightarrow{abc}$

↩abc\\xhookleftarrow{abc}abc​ $\xhookleftarrow{abc}$

↪abc\\xhookrightarrow{abc}abc​ $\xhookrightarrow{abc}$

↞abc\\xtwoheadleftarrow{abc}abc $\xtwoheadleftarrow{abc}$

↠abc\\xtwoheadrightarrow{abc}abc $\xtwoheadrightarrow{abc}$

↼abc\\xleftharpoonup{abc}abc​ $\xleftharpoonup{abc}$

⇀abc\\xrightharpoonup{abc}abc​ $\xrightharpoonup{abc}$

↽abc\\xleftharpoondown{abc}abc​ $\xleftharpoondown{abc}$

⇁abc\\xrightharpoondown{abc}abc​ $\xrightharpoondown{abc}$

⇋abc\\xleftrightharpoons{abc}abc​ $\xleftrightharpoons{abc}$

⇌abc\\xrightleftharpoons{abc}abc​ $\xrightleftharpoons{abc}$

⇄abc\\xtofrom{abc}abc​ $\xtofrom{abc}$

↦abc\\xmapsto{abc}abc​ $\xmapsto{abc}$

\=abc\\xlongequal{abc}abc $\xlongequal{abc}$

Extensible arrows all can take an optional argument in the same manner  
as $\xrightarrow[under]{over}`.

[](#special-notation)Special Notation
-------------------------------------

**Bra-ket Notation**

⟨ϕ∣\\bra{\\phi}⟨ϕ∣ $\bra{\phi}$

∣ψ⟩\\ket{\\psi}∣ψ⟩ $\ket{\psi}$

⟨ϕ∣ψ⟩\\braket{\\phi\\vert\\psi}⟨ϕ∣ψ⟩ $\braket{\phi\vert\psi}$

⟨ϕ∣\\Bra{\\phi}⟨ϕ∣ $\Bra{\phi}$

∣ψ⟩\\Ket{\\psi}∣ψ⟩ $\Ket{\psi}$

[](#style-color-size-and-font)Style, Color, Size, and Font
----------------------------------------------------------

**Class Assignment**

`\mathbin$ $\mathclose$ $\mathinner$ $\mathop$  
`\mathopen$ $\mathord$ $\mathpunct$ $\mathrel$

**Color**

F\=ma\\color{blue} F=maF\=ma $\color{blue} F=ma$

Note that $\color$ acts like a switch. Other color functions expect the content to be a function argument:

F\=ma\\textcolor{blue}{F=ma}F\=ma $\textcolor{blue}{F=ma}$  
F\=ma\\textcolor{#228B22}{F=ma}F\=ma $\textcolor{#228B22}{F=ma}$  
F\=ma\\colorbox{aqua}{$F=ma$}F\=ma​ $\colorbox{aqua}{$F=ma$}$  
F\=ma\\fcolorbox{red}{aqua}{$F=ma$}F\=ma​ $\fcolorbox{red}{aqua}{$F=ma$}$

Note that, as in LaTeX, $\colorbox$ & $\fcolorbox$ renders its third argument as text, so you may want to switch back to math mode with $$$ as in the examples above.

For color definition, KaTeX color functions will accept the standard HTML [predefined color names](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#Color_keywords). They will also accept an RGB argument in CSS hexa­decimal style. The "#" is optional before a six-digit specification.

**Font**

Ab0\\mathrm{Ab0}Ab0 $\mathrm{Ab0}$

Ab0\\mathbf{Ab0}Ab0 $\mathbf{Ab0}$

Ab0\\mathit{Ab0}Ab0 $\mathit{Ab0}$

Ab0\\mathnormal{Ab0}Ab0 $\mathnormal{Ab0}$

Ab0\\textbf{Ab0}Ab0 $\textbf{Ab0}$

Ab0\\textit{Ab0}Ab0 $\textit{Ab0}$

Ab0\\textrm{Ab0}Ab0 $\textrm{Ab0}$

Ab0\\bf Ab0Ab0 $\bf Ab0$

Ab0\\it Ab0Ab0 $\it Ab0$

Ab0\\rm Ab0Ab0 $\rm Ab0$

Ab0\\bold{Ab0}Ab0 $\bold{Ab0}$

Ab0\\textup{Ab0}Ab0 $\textup{Ab0}$

Ab0\\textnormal{Ab0}Ab0 $\textnormal{Ab0}$

Ab0\\boldsymbol{Ab0}Ab0 $\boldsymbol{Ab}$

AB\\Bbb{AB}AB $\Bbb{AB}$

Ab0\\text{Ab0}Ab0 $\text{Ab0}$

Ab0\\bm{Ab0}Ab0 $\bm{Ab0}$

AB\\mathbb{AB}AB $\mathbb{AB}$

Ab0\\mathsf{Ab0}Ab0 $\mathsf{Ab0}$

Ab0\\textmd{Ab0}Ab0 $\textmd{Ab0}$

Ab0\\frak{Ab0}Ab0 $\frak{Ab0}$

Ab0\\textsf{Ab0}Ab0 $\textsf{Ab0}$

Ab0\\mathtt{Ab0}Ab0 $\mathtt{Ab0}$

Ab0\\mathfrak{Ab0}Ab0 $\mathfrak{Ab0}$

Ab0\\sf Ab0Ab0 $\sf Ab0$

Ab0\\texttt{Ab0}Ab0 $\texttt{Ab0}$

AB0\\mathcal{AB0}AB0 $\mathcal{AB0}$

Ab0\\tt Ab0Ab0 $\tt Ab0$

AB0\\cal AB0AB0 $\cal AB0$

AB\\mathscr{AB}AB $\mathscr{AB}$

One can stack font family, font weight, and font shape by using the $\textXX$ versions of the font functions. So $\textsf{\textbf{H}}$ will produce H\\textsf{\\textbf{H}}H. The other versions do not stack, e.g., $\mathsf{\mathbf{H}}$ will produce H\\mathsf{\\mathbf{H}}H.

In cases where KaTeX fonts do not have a bold glyph, $\pmb$ can simulate one. For example, $\pmb{\mu}$ renders as : μ\\pmb{\\mu}μμ

**Size**

AB\\Huge ABAB $\Huge AB$

AB\\normalsize ABAB $\normalsize AB$

AB\\huge ABAB $\huge AB$

AB\\small ABAB $\small AB$

AB\\LARGE ABAB $\LARGE AB$

AB\\footnotesize ABAB $\footnotesize AB$

AB\\Large ABAB $\Large AB$

AB\\scriptsize ABAB $\scriptsize AB$

AB\\large ABAB $\large AB$

AB\\tiny ABAB $\tiny AB$

**Style**

∑i\=1n\\displaystyle\\sum\_{i=1}^ni\=1∑n​ $\displaystyle\sum_{i=1}^n$

∑i\=1n\\textstyle\\sum\_{i=1}^n∑i\=1n​ $\textstyle\sum_{i=1}^n$

x\\scriptstyle xx $\scriptstyle x$         (The size of a first sub/superscript)

x\\scriptscriptstyle xx $\scriptscriptstyle x$ (The size of subsequent sub/superscripts)

lim⁡x\\lim\\limits\_xxlim​ $\lim\limits_x$

lim⁡x\\lim\\nolimits\_xlimx​ $\lim\nolimits_x$

x^2\\verb!x^2!x^2 $\verb!x^2!$

`\text{…}$ will accept nested $$…$$ fragments and render them in math mode.

[](#symbols-and-punctuation)Symbols and Punctuation
---------------------------------------------------

`% comment$

…\\dots… $\dots$

KaTeX\\KaTeXKATE​X $\KaTeX$

%\\%% $\%$

⋯\\cdots⋯ $\cdots$

LaTeX\\LaTeXLATE​X $\LaTeX$

#\\## $\#$

⋱\\ddots⋱ $\ddots$

TeX\\TeXTE​X $\TeX$

&\\&& $\&$

…\\ldots… $\ldots$

∇\\nabla∇ $\nabla$

\_\\\_\_ $\_$

⋮\\vdots⋮ $\vdots$

∞\\infty∞ $\infty$

\_\\text{\\textunderscore}\_ $\text{\textunderscore}$

⋯\\dotsb⋯ $\dotsb$

∞\\infin∞ $\infin$

–\\text{--}– $\text{--}$

…\\dotsc… $\dotsc$

✓\\checkmark✓ $\checkmark$

–\\text{\\textendash}– $\text{\textendash}$

 ⁣⋯\\dotsi⋯ $\dotsi$

†\\dag† $\dag$

—\\text{---}— $\text{---}$

⋯\\dotsm⋯ $\dotsm$

†\\dagger† $\dagger$

—\\text{\\textemdash}— $\text{\textemdash}$

…\\dotso… $\dotso$

†\\text{\\textdagger}† $\text{\textdagger}$

~\\text{\\textasciitilde}~ $\text{\textasciitilde}$

⋅\\sdot⋅ $\sdot$

‡\\ddag‡ $\ddag$

^\\text{\\textasciicircum}^ $\text{\textasciicircum}$

…\\mathellipsis… $\mathellipsis$

‡\\ddagger‡ $\ddagger$

‘\`‘ $$ $ $$

…\\text{\\textellipsis}… $\text{\textellipsis}$

‡\\text{\\textdaggerdbl}‡ $\text{\textdaggerdbl}$

‘\\text{\\textquoteleft}‘ $text{\textquoteleft}$

□\\Box□ $\Box$

‡\\Dagger‡ $\Dagger$

‘\\lq‘ $\lq$

□\\square□ $\square$

∠\\angle∠ $\angle$

’\\text{\\textquoteright}’ $\text{\textquoteright}$

■\\blacksquare■ $\blacksquare$

∡\\measuredangle∡ $\measuredangle$

′\\rq′ $\rq$

△\\triangle△ $\triangle$

∢\\sphericalangle∢ $\sphericalangle$

“\\text{\\textquotedblleft}“ $\text{\textquotedblleft}$

▽\\triangledown▽ $\triangledown$

⊤\\top⊤ $\top$

""" $"$

◃\\triangleleft◃ $\triangleleft$

⊥\\bot⊥ $\bot$

”\\text{\\textquotedblright}” $\text{\textquotedblright}$

▹\\triangleright▹ $\triangleright$

$\\$$ $\$$

 ⁣:\\colon: $\colon$

▽\\bigtriangledown▽ $\bigtriangledown$

$\\text{\\textdollar}$ $\text{\textdollar}$

‵\\backprime‵ $\backprime$

△\\bigtriangleup△ $\bigtriangleup$

£\\pounds£ $\pounds$

′\\prime′ $\prime$

▲\\blacktriangle▲ $\blacktriangle$

£\\mathsterling£ $\mathsterling$

<\\text{\\textless}< $\text{\textless}$

▼\\blacktriangledown▼ $\blacktriangledown$

£\\text{\\textsterling}£ $\text{\textsterling}$

\>\\text{\\textgreater}\> $\text{\textgreater}$

◀\\blacktriangleleft◀ $\blacktriangleleft$

¥\\yen¥ $\yen$

|\\text{\\textbar}| $\text{\textbar}$

▶\\blacktriangleright▶ $\blacktriangleright$

√\\surd√ $\surd$

∥\\text{\\textbardbl}∥ $\text{\textbardbl}$

⋄\\diamond⋄ $\diamond$

°\\degree° $\degree$

{\\text{\\textbraceleft}{ $\text{\textbraceleft}$

◊\\Diamond◊ $\Diamond$

°\\text{\\textdegree}° $\text{\textdegree}$

}\\text{\\textbraceright}} $\text{\textbraceright}$

◊\\lozenge◊ $\lozenge$

℧\\mho℧ $\mho$

\\\\text{\\textbackslash}\\ $\text{\textbackslash}$

⧫\\blacklozenge⧫ $\blacklozenge$

╲\\diagdown╲ $\diagdown$

¶\\text{\\P}¶ $\text{\P}$ or $\P$

⋆\\star⋆ $\star$

╱\\diagup╱ $\diagup$

§\\text{\\S}§ $\text{\S}$ or $\S$

★\\bigstar★ $\bigstar$

♭\\flat♭ $\flat$

§\\text{\\sect}§ $\text{\sect}$

♣\\clubsuit♣ $\clubsuit$

♮\\natural♮ $\natural$

©\\copyrightc◯ $\copyright$

♣\\clubs♣ $\clubs$

♯\\sharp♯ $\sharp$

®\\circledR® $\circledR$

♢\\diamondsuit♢ $\diamondsuit$

♡\\heartsuit♡ $\heartsuit$

®\\text{\\textregistered}R◯ $\text{\textregistered}$

♢\\diamonds♢ $\diamonds$

♡\\hearts♡ $\hearts$

Ⓢ\\circledSⓈ $\circledS$

♠\\spadesuit♠ $\spadesuit$

♠\\spades♠ $\spades$

a◯\\text{\\textcircled a}a◯ $\text{\textcircled a}$

✠\\maltese✠ $\maltese$

⦵\\minuso∘− $\minuso$

Direct Input: § ¶ £¥∇∞⋅∠∡∢♠♡♢♣♭♮♯✓…⋮⋯⋱!£ ¥ ∇ ∞ · ∠ ∡ ∢ ♠ ♡ ♢ ♣ ♭ ♮ ♯ ✓ … ⋮ ⋯ ⋱ !£¥∇∞⋅∠∡∢♠♡♢♣♭♮♯✓…⋮⋯⋱! ‼ ⦵

[](#units)Units
---------------

In KaTeX, units are proportioned as they are in TeX.  
KaTeX units are different than CSS units.

KaTeX Unit

Value

KaTeX Unit

Value

em

CSS em

bp

1/72​ inch × F × G

ex

CSS ex

pc

12 KaTeX pt

mu

1/18 CSS em

dd

1238/1157​ KaTeX pt

pt

1/72.27 inch × F × G

cc

14856/1157 KaTeX pt

mm

1 mm × F × G

nd

685/642 KaTeX pt

cm

1 cm × F × G

nc

1370/107​ KaTeX pt

in

1 inch × F × G

sp

1/65536 KaTeX pt

where:

F = (font size of surrounding HTML text)/(10 pt)

G = 1.21 by default, because KaTeX font-size is normally 1.21 × the surrounding font size. This value [can be overridden](/docs/font.html#font-size-and-lengths) by the CSS of an HTML page.

The effect of style and size:

Unit

textstyle

scriptscript

huge

em or ex

\\rule{1em}{1em}

\\scriptscriptstyle\\rule{1em}{1em}

\\huge\\rule{1em}{1em}

mu

\\rule{18mu}{18mu}

\\scriptscriptstyle\\rule{18mu}{18mu}

\\huge\\rule{18mu}{18mu}

others

\\rule{10pt}{10pt}

\\scriptscriptstyle\\rule{10pt}{10pt}

\\huge\\rule{10pt}{10pt}

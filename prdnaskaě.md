vbox - scitani vysky a sirka se spočítá podle posledního který bude referenční
- maxdepth 4pt
- boxmaxdepth infinity
- vtop nejvyšší referenční bot
- vcenter - udelá se střed podle horizontálního boxu

hbox - scitáni sirek a z vysky a hlobky se pocita maximum


\hbox 
- spread x{.....}
- to x {......}

\vbox

\vtop

\accent N znak ukakza \'a \"a \v a


\vrule - pozor jsou v horizont8ln9m seznamu a ne ve vertikalnim
- width x height y depth z
- (0.4pt)  
- \strut

\kern DIM

\hskip DIM plus minus 

\quad - mezera o velkosti 1em

\qqad - mezera o velkosti 2em 

\hfil(l)

\hss

\/ - o kolik muze neco vycuovat


\penalty
- \nobreak(10000)
- \break(10000)
- \allowbreak(10000)
- \space
- ~

\line {.....} = \hbox to \hsize{....}

\centerline{....} = \line{\hss ... \hss}

\leftline

\rightline

Odsazeni na jednu stranu
- \llap
- \rlap= \hbox to 0pt{...\hss }

prazdny box
- \phantom  
- \smash  -phantom s 0lovou sirkou a delkou

DIM mm, cm, in
- 1pt = 1/72.27 in
- 1bp = 1/72 in
- 1sp = $2^-16$pt
- 1em = velkost M
- 1ex = velkost x
- hsize
- fil fill flll


# TFM
## fontdimens
- sklon
- std mezera 
    - roztaznost 
    - smrstitelnost
- ex 
- em
- extra mezera

## vlastnosti znk; 
- width height, depth
- ital corrr - zrada vysky jsou z tabulek pro divoky font
## Kerning + ligatury


## mezislovny mezery
- \sfcode N = SF
- \spacefactor def 1000
    - a_z 1000
    - A-Z 999
    - .!? 3000
    - , 1250
    - () 0
    - if spacefactor <1000 nebo sfcode > 1000 tak se nastavi na 1000
Mezera na vstupu 
- std. mezera plus rozta6nost * SF/1000 minus smrstitelnost *1000/SF
    - pokud SF>=2000 + extra mezera
- \spaceskip
- \ẍspaceskip
# Discretionary break
\discretionary{pre}{post}{no}
- {}{tisíce}{\kern .2em 000}
- {\kern ...az}{}{--}

\\- {\hypenchar}{}{}
## slovnik generovan patgenem 
.nejvetsi.
- ne1
- ne2j1

nejvetsi cislo je cislo zlomu pokud je liche

mozne nastaveni pomoci 
- \lefthypenmin - deleni pro minimalni pocet pismen z lea
- \righthypenmin

hyphenation - explictni slovnik pro deleni vytvoren uzivatelem{fam-fr-pal}

\language =\czech - cislo 5
- nastavi jazyk na cestinu od tohoto 
---
layout: base
title:  'Statistics of ccomp in UD_Czech-CAC'
udver: '2'
---

## Treebank Statistics: UD_Czech-CAC: Relations: `ccomp`

This relation is universal.

1606 nodes (0%) are attached to their parents as `ccomp`.

1502 instances of `ccomp` (94%) are left-to-right (parent precedes child).
Average distance between parent and child is 7.46762141967621.

The following 17 pairs of parts of speech are connected with `ccomp`: <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (1226; 76% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt> (193; 12% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt> (113; 7% instances), <tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (27; 2% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-ADV.html">ADV</a></tt> (16; 1% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-DET.html">DET</a></tt> (11; 1% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-NUM.html">NUM</a></tt> (5; 0% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-PRON.html">PRON</a></tt> (5; 0% instances), <tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-ADV.html">ADV</a></tt>-<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cac-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-SYM.html">SYM</a></tt>-<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="cs_cac-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_cac-pos-SYM.html">SYM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 9 ccomp	color:blue
1	Ve	v	ADP	RV--4----------	AdpType=Voc|Case=Acc	2	case	_	LId=v-1
2	čtyři	čtyři	NUM	ClXP4----------	Case=Acc|Number=Plur|NumForm=Word|NumType=Card|NumValue=1,2,3	4	obl	_	LNumValue=4
3	odpoledne	odpoledne	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	2	nmod	_	LId=odpoledne-2
4	ohlásil	ohlásit	VERB	VpYS---XR-AA---	Aspect=Perf|Gender=Masc|Number=Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Act	0	root	_	_
5	předseda	předseda	NOUN	NNMS1-----A----	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	4	nsubj	_	_
6	družstva	družstvo	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	5	nmod	_	SpaceAfter=No
7	,	,	PUNCT	Z:-------------	_	9	punct	_	_
8	že	že	SCONJ	J,-------------	_	9	mark	_	_
9	padla	padnout	VERB	VpQW---XR-AA--1	Aspect=Perf|Gender=Fem,Neut|Number=Plur,Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Act	4	ccomp	_	SpaceAfter=No
10	.	.	PUNCT	Z:-------------	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 7 ccomp	color:blue
1	Víme	vědět	VERB	VB-P---1P-AA---	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
2	,	,	PUNCT	Z:-------------	_	7	punct	_	_
3	že	že	SCONJ	J,-------------	_	7	mark	_	_
4	nadbytečné	nadbytečný	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	5	amod	_	_
5	kilogramy	kilogram	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	7	nsubj	_	_
6	nejsou	být	AUX	VB-P---3P-NA---	Mood=Ind|Number=Plur|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin|Voice=Act	7	cop	_	_
7	zdravé	zdravý	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	1	ccomp	_	_
8	ani	ani	CCONJ	J^-------------	_	9	cc	_	_
9	nesluší	slušet	VERB	VB-S---3P-NA---	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin|Voice=Act	7	conj	_	SpaceAfter=No
10	.	.	PUNCT	Z:-------------	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 6 ccomp	color:blue
1	Kdo	kdo	PRON	PKM-1----------	Animacy=Anim|Case=Nom|Gender=Masc|PronType=Int,Rel	6	nsubj	_	_
2	bude	být	AUX	VB-S---3F-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Fut|VerbForm=Fin|Voice=Act	6	cop	_	_
3	půl	půl	NUM	ClXS4----------	Case=Acc|Number=Sing|NumForm=Word|NumType=Card|NumValue=1,2,3	4	nummod:gov	_	LId=půl-1
4	roku	rok	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	6	obl	_	_
5	papírovým	papírový	ADJ	AAMS7----1A----	Animacy=Anim|Case=Ins|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	6	amod	_	_
6	členem	člen	NOUN	NNMS7-----A----	Animacy=Anim|Case=Ins|Gender=Masc|Number=Sing|Polarity=Pos	8	ccomp	_	SpaceAfter=No
7	,	,	PUNCT	Z:-------------	_	6	punct	_	_
8	vyškrtnout	vyškrtnout	VERB	Vf--------A----	Aspect=Perf|Polarity=Pos|VerbForm=Inf	0	root	_	SpaceAfter=No
9	.	.	PUNCT	Z:-------------	_	8	punct	_	_

~~~


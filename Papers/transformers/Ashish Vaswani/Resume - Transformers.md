---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
1 ^vFIFPWNi

1. BLEU (Bilingual Evaluation Understudy) is a 
metric used to evaluate machine translation 
compared with a reference translation. ^UDR6Ycgx

transformer ^UocU7XmS

Transformers reduce the computational 
complexity required to relate signals 
between distant positions. ^JDkyMLek

self-attention captures 
global similarities while 
multi-head attention 
improves local similarity 
by attending simultaneously 
but separately across 
various parts or aspects 
within each layer. ^WIfewKOt

Convert something 
into another form  ^a8Nt0EWj

computation ^mP2sIOqn

pioneer ^WM2zyzAS

mapping ^ZFspYZPN

intra-attention ^j9HL0zOf

recurrence ^4qGbUgt8

sub-layer 1 ^O7cEbUvN

LayerNorm2(LayerNorm1 + 
            Sublayer2(LayerNorm1)) ^OhYmMLCC

sub-layer 2 ^ggXAtAp2

layer ^6fzGUVrQ

Encode ^g4mEZXo4

Fixed size enables smooth information 
propagation through these residual 
paths without any mismatch or inconsistency 
in dimension sizes. This promotes better 
gradient flow and overall optimization 
during training. ^vBz7V0SK

Facilitation is based 
on constant size not
the size itself. ^pdpI6krC

stack ^Qdmp7Bfl

2 ^yUuzETzF

2 ^I5U7WcjR

i.e, e.g: if input emb has position 2,
only output emb with position 1 will 
receive attention.
 ^eRAa6C6u

encode ^a9XmQxMt

encode ^Gs0sKgmE

encode ^37b9byo4

encode ^9YBG04Nd

encode ^KksIYq0P

encode ^1MasIgb9

decode ^HE7nUbbf

> ^NpHqGDcw

> ^cI8c0Y0p

decode ^SeVlfHsT

decode ^pCzd9jB2

decode ^6F1Hv76H

decode ^Uysnd4eB

decode ^6yXUs0K2

linear ^oZ1dtVJ0

softmax ^FjGW6nn4

> ^BVtissw8

> ^oT5XhZLj

Stack view ^g5nsJJuq

LayerNorm(x + Sublayer1(x)) ^eI215DUz

6 ^SqoSEYHV

6 ^EExGXFwQ

Deep learning ^QwRVfrB0

Seems to be the
output delayed 
in time ^MvsSRO28

This modified sublayer
will consider or give attention 
only to inputs (autoregressive) 
with positional encoding previous 
of current positional encoding 
input. ^xNdpXUVO

encode ^sPtHbw3K

decode ^uHUAWD8r

Value ^TGiMZKWg

Positional Encoding ^o4Qz9htp

Key ^t2Dokhbr

Query ^jX5a6Y2i

linear ^xheY9rmw

linear ^nqkJzfJy

linear ^qEoaS5s2

Matmul ^p5jAErSQ

Scale ^8tCSGKiB

Softmax ^6gk7JcSA

Matmul ^LcEFuOl4

vector ^J5BLBW84

vector ^QIc4hZ3m

vector ^xYmrh8PP

dot-product 
attention ^HHuF3q9a

"vanish-explosion" ^nScKOifX

scale ^fPpEV8EQ

The modification of the queries (Q), keys (K), and values (V) is 
achieved by applying different linear projections to them h times. 
Each linear projection has its own set of learned weights, which 
are slightly different from each other. These projected versions 
of Q, K, and V are then concatenated in a dv dimension before 
being used in the attention mechanism. This allows for capturing 
different aspects or perspectives of the input data during each 
iteration or step. ^fahedI6W

In the Transformer architecture, each query can attend 
to all keys simultaneously. So in a example sentence 
"the cat jumped", the query for word "the" (Q1) can be 
multiplied by all three keys ("the", "cat", and "jumped") in 
parallel: Q1xK1, Q1xK2, and Q1xK3. This allows for computing 
attention scores between the query and multiple key-value 
pairs at once. The attention(Q1, K1, V1), attention(Q2,K2,V2), 
and attention(Q3,K3,V3) operations represent how similar or 
relevant each word is to the given query word ("the"). By 
performing these computations in parallel across different
words of a sequence using matrix operations efficiently 
implemented on hardware like GPUs or TPUs (Tensor 
Processing Units), Transformers enable faster processing 
compared to sequential models. ^UEsrbenu

An auto-regressive model is a type of model that 
predicts the next element in a sequence based 
on previous elements. In the context of language 
generation or machine translation, an autoregressive 
model generates one token at a time by conditioning 
its prediction on previously generated tokens. ^edaK2X5K

In the case of Transformers, which are used for 
sequence transduction tasks like machine translation, 
they can be trained in an autoregressive manner. 
During training, the target sequences are fed to the 
decoder one token at a time from left to right. 
At each step, all previously generated tokens are 
provided as input along with their corresponding 
positional encodings. ^MnYpU6Qn

During inference or generation phase (when no ground 
truth targets are available), autoregressive 
decoding is performed by iteratively predicting and 
generating one token at each step using beam search 
or other decoding strategies. The predicted token 
becomes part of the input for subsequent predictions 
until an end-of-sequence marker is reached. ^O01xM74D

Auto-regressive models and recurrence are different in terms of how they 
handle dependencies and generate sequences. ^NCWfG4MU

Recurrence, as seen in traditional recurrent neural networks (RNNs), 
processes a sequence one element at a time by maintaining an internal 
hidden state that is updated based on the previous hidden state and 
the current input. This allows RNNs to capture sequential dependencies 
by incorporating information from past elements into the prediction of 
each subsequent element. However, this sequential processing can be 
computationally expensive and limits parallelization. ^ux3MnCOZ

On the other hand, auto-regressive models like Transformers do not 
rely on recurrence for handling dependencies between elements in a sequence. 
Instead, they use self-attention mechanisms to directly model relationships 
between all positions within a sequence simultaneously. Each position attends 
to all other positions using attention weights that determine their relevance 
or importance for generating predictions at that position. ^Gk7Wv4NJ

This parallelized approach enables Transformers to process multiple elements 
of a sequence concurrently without being constrained by strict order or temporal 
dependency like RNNs with recurrence. Auto-regressive decoding still considers
previously generated tokens during inference but does so through explicit 
attention mechanisms rather than relying on recurrent connections. ^qNqr309G

In summary, while both auto-regressive models (like Transformers) and recurrent 
models capture dependencies within sequences, they differ in how these dependencies 
are modeled: recurrence relies on sequentially updating hidden states over time 
whereas auto-regression uses self-attention mechanisms for capturing relationships 
across all positions simultaneously. ^HcXDrmjX

Parallelization ^HiOQ4Ji0

Autoregressive (AR) ^ACZByJr4

AR Transformer X recurrent neural net ^ADdONWUY

self-attention ^G2zi7bzr

different (multiple) 
linear projections ^jqdOhvUK

Notes: ^1NcIaTgt

1 ^6xaelNNE

1 ^00Br2w6k

2 ^dmyc0XwU

3 ^vIK2uR16

K ^FCvhiAZr

V ^1ufgsg6b

Q ^41SeG2WM

2 ^ritd4zos

3 ^eoC4vtI7

Usually is used to 
shrink the number
of channels ^3eraPiSd

E1 ^9gjEV7GB

E2 ^q5E5x7mx

2048 ^shUdXLN7

512 ^ioO0lQ8z

2048 ^q51amnHL

En ^IIyqccuu

... ^lpfK7guh

Value ^XYmkcvul

Key ^NMOLQ3b6

Query ^bh6bQcB6

linear ^ZPZ1OTiI

linear ^cC1rUAjX

linear ^W3ludlNi

Matmul ^zXsK8qv8

Value ^23ACLTaq

Key ^eYdQg57x

Query ^dUSYssGW

linear ^yWyOCagr

linear ^0cvg366Q

linear ^cO98Tpct

Matmul ^HyJeZcm3

input embedding ^i5WT3703

output embedding ^CJQU9Ezv

shared ^bvATAq0n

parallelized ^weu8gEer

long term
dependency ^g6VlNQoo

faster ^mGJhWEti

convolution is
more expensive ^79odkhsn

more interpretable ^FGlhCDpP

hiperparameter
grid search ^cZopHU4l

Same model
different tasks ^uf8DRweu

without fine
tuning good
results ^Dj8jZy9p

outperforms rnns ^KARkv9iQ

residual ^KySQWlLu

residual ^So0sRvQg

1  - cat ^ULteBJyf

2 - is ^fZrTqFF9

3 - jumping ^TrSYMlaM

0 - O (the) ^Wrd5DVht

1  - gato (cat) ^YfWrPk6i

2 - está (is) ^hVUF8usj

3 - pulando (jumping) ^rJw53mDJ

0 - the ^kCDVZp9x

1  - cat ^9thRwEGR

2 - is ^8rBDStJx

3 - juping ^mvE0MQ1M

Mask
avoid ^smqXMEUd

Translation en-pt simple example ^cJeCoXrZ

0 - the ^4dmLmMNj

E ^oDOoCIGp

D ^z1xFW4sp

sdsa ^oJf7dMso

"Query and keys
will "fire" weights
of value based
on their compatibility"
 ^j0Rfcise


# Embedded files
5714295ca3c1f7d10fefa49c1f0fb788627b8d4a: [[Attention Is All You Need.pdf#page=1]]
da8a402c484735f8f5024ba211750e85aee0e0b0: [[Attention Is All You Need.pdf#page=2]]
5927fa443d144b8be253560c99c59e3390659560: [[Attention Is All You Need.pdf#page=4]]
8a14fd8c42a9d050105a885c79b149f12d94206d: [[Attention Is All You Need.pdf#page=5]]
fb5c327996f7ddeb9e4c71884338d2fc0e12db13: [[Attention Is All You Need.pdf#page=6]]
ca38b461bb8850f766d490b3341139c35e17cce8: [[Attention Is All You Need.pdf#page=7]]
4a26b3f168b3d8bc44e1d5ff231aa92b0b723b79: [[Attention Is All You Need.pdf#page=8]]
e329a5131f89e0a72545287e2691aaeceab0ae80: [[Attention Is All You Need.pdf#page=9]]
e5892304a04ab01776bd49f97c69e4aff38704e5: [[Attention Is All You Need.pdf#page=10]]
e6702aeb913a3e82b8794ead601b32f80128726c: [[Attention Is All You Need.pdf#page=11]]
c73ee5d2986ca79b0d4f2ca9c475acd12145c06a: [[Attention Is All You Need.pdf#page=12]]
1d84606c8d74f33d0d49538e73641f9003a332be: [[Attention Is All You Need.pdf#page=13]]
441782208a6497f58e649627863b2642b650e4a9: [[Attention Is All You Need.pdf#page=14]]
40bb1b246077708827187ac7cbff6fd497529bea: [[Attention Is All You Need.pdf#page=15]]
7e3c4bfda52162ae2e9f71013f5193bc89629086: [[Attention Is All You Need.pdf#page=3]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.3",
	"elements": [
		{
			"type": "rectangle",
			"version": 779,
			"versionNonce": 1987801534,
			"isDeleted": false,
			"id": "ETUxoxvJHjNltNjYjiQid",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": 487.59335456561143,
			"y": -1145.0594352096891,
			"strokeColor": "transparent",
			"backgroundColor": "#ffec99",
			"width": 166.34626184822304,
			"height": 13.185280176066216,
			"seed": 71620910,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 658,
			"versionNonce": 1450971426,
			"isDeleted": false,
			"id": "IShxH0fEoYoUK8EmG-HMb",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": 485.3995225936583,
			"y": -1162.8294741825082,
			"strokeColor": "transparent",
			"backgroundColor": "#ffec99",
			"width": 480.06423383749694,
			"height": 16.25664493680044,
			"seed": 1455663922,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 141,
			"versionNonce": 1810008574,
			"isDeleted": false,
			"id": "APKhyQbPJYMVgEIfRpMS9",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -3.515008460547506,
			"y": -677.7424366882431,
			"strokeColor": "transparent",
			"backgroundColor": "#ffec99",
			"width": 208.02906931532954,
			"height": 15.817878542409858,
			"seed": 1345984818,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 397,
			"versionNonce": 551656674,
			"isDeleted": false,
			"id": "OPZvMAm9sEwIP8BLmfUBE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 1244.8003388683696,
			"y": -829.1475050263715,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 478.32036478398277,
			"height": 55.7910376542493,
			"seed": 1670570257,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 576,
			"versionNonce": 222075454,
			"isDeleted": false,
			"id": "YaHyek_St8MdlFLVh1wwZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 3076.5064400046685,
			"y": -968.6258932627723,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 639.7962847284193,
			"height": 67.18624469701763,
			"seed": 2121327359,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 370,
			"versionNonce": 1713352866,
			"isDeleted": false,
			"id": "P1i2wvgR2ci5MI6NhwvW0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 372.27402482801546,
			"y": -1335.6088491991284,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 153.6723381990849,
			"height": 66.32174595960532,
			"seed": 717276895,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "Riuoy42pehwfY_c4h1tSV",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 261,
			"versionNonce": 1365942910,
			"isDeleted": false,
			"id": "APV8QuMSb0UYqvvwT_hS-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 377.3271626024751,
			"y": -1322.742571467032,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 615682257,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "E9XgbVuuXn8CdwyU7fyAV",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 310,
			"versionNonce": 1239764066,
			"isDeleted": false,
			"id": "q6SBWe8Ryj6CXzIEDndEw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 426.1398054810557,
			"y": -1322.6167656864172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f08c00",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 369997023,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "77jfQn3dUSHp1ESEYUMvD",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 348,
			"versionNonce": 724411070,
			"isDeleted": false,
			"id": "gYYbTI58n88g6v24B7150",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 476.21050616578526,
			"y": -1322.6167656864172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 783967121,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "ufL38iUXmAO7rG3wFaTHT",
					"type": "arrow"
				},
				{
					"id": "z2SAk1oPtZIO3sm7AtiGU",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1474,
			"versionNonce": 570519586,
			"isDeleted": false,
			"id": "wgKmbHjgdenYcoDd1AOtQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 10,
			"angle": 0,
			"x": 112.89510515733093,
			"y": -1252.3314940135438,
			"strokeColor": "#f08c00",
			"backgroundColor": "#fab005",
			"width": 173.06871156043792,
			"height": 124.120462176559,
			"seed": 961273265,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "nUudDTYydqFtDN95qb_Kb",
					"type": "arrow"
				},
				{
					"id": "royI-XaIrlJptd4iHJ9o8",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 818,
			"versionNonce": 220633854,
			"isDeleted": false,
			"id": "sk1ADWPbnUiMEe0dKbGQG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": -329.4007057371292,
			"y": -1337.100926159712,
			"strokeColor": "transparent",
			"backgroundColor": "#ced4da",
			"width": 288.659633033113,
			"height": 266.84299671863283,
			"seed": 218838523,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1393,
			"versionNonce": 845356002,
			"isDeleted": false,
			"id": "aXmUk1aSueGDjZt3B5mLv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 30,
			"angle": 0,
			"x": -29.244539077340676,
			"y": -1449.2414039292382,
			"strokeColor": "transparent",
			"backgroundColor": "#9775fa",
			"width": 104.49531382589112,
			"height": 396.18630927812336,
			"seed": 1988389247,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 1783,
			"versionNonce": 1842776894,
			"isDeleted": false,
			"id": "PQqF4mB9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -403.9484381117179,
			"y": -1530.275305343103,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 52452,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "7e3c4bfda52162ae2e9f71013f5193bc89629086",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 1671,
			"versionNonce": 1763266466,
			"isDeleted": false,
			"id": "MH08PHHq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -399.97264458583413,
			"y": -1534.356426141971,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 24106,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927698,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1541,
			"versionNonce": 1268675454,
			"isDeleted": false,
			"id": "ggXAtAp2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -206.4756704218966,
			"y": -1275.5559766284916,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 57.14569091796875,
			"height": 12.726047454850944,
			"seed": 166082011,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "8opCJnJSlSS9ohtBk-uZW",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false,
			"fontSize": 10.180837963880755,
			"fontFamily": 1,
			"text": "sub-layer 2",
			"rawText": "sub-layer 2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sub-layer 2",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 1847,
			"versionNonce": 441650018,
			"isDeleted": false,
			"id": "6fzGUVrQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -129.8211115739484,
			"y": -1328.2200523681593,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 38.016082763671875,
			"height": 20,
			"seed": 1772008821,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "GMhHSKyVIjT8HSrmYGJwd",
					"type": "arrow"
				}
			],
			"updated": 1694624927698,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "layer",
			"rawText": "layer",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "layer",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 1671,
			"versionNonce": 817845182,
			"isDeleted": false,
			"id": "xNdpXUVO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 118.51167312005887,
			"y": -1247.4089571181366,
			"strokeColor": "#f08c00",
			"backgroundColor": "#e03131",
			"width": 170.6680450439453,
			"height": 79.42591328293007,
			"seed": 1742530001,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "royI-XaIrlJptd4iHJ9o8",
					"type": "arrow"
				}
			],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 10.590121771057342,
			"fontFamily": 1,
			"text": "This modified sublayer\nwill consider or give attention \nonly to inputs (autoregressive) \nwith positional encoding previous \nof current positional encoding \ninput.",
			"rawText": "This modified sublayer\nwill consider or give attention \nonly to inputs (autoregressive) \nwith positional encoding previous \nof current positional encoding \ninput.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "This modified sublayer\nwill consider or give attention \nonly to inputs (autoregressive) \nwith positional encoding previous \nof current positional encoding \ninput.",
			"lineHeight": 1.25,
			"baseline": 75
		},
		{
			"type": "text",
			"version": 1497,
			"versionNonce": 1012879138,
			"isDeleted": false,
			"id": "eRAa6C6u",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 146.82619816154093,
			"y": -1169.3596037000616,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fab005",
			"width": 136.32400512695312,
			"height": 39.295124447599804,
			"seed": 528887231,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 7.859024889519961,
			"fontFamily": 1,
			"text": "i.e, e.g: if input emb has position 2,\nonly output emb with position 1 will \nreceive attention.\n",
			"rawText": "i.e, e.g: if input emb has position 2,\nonly output emb with position 1 will \nreceive attention.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "i.e, e.g: if input emb has position 2,\nonly output emb with position 1 will \nreceive attention.\n",
			"lineHeight": 1.25,
			"baseline": 35
		},
		{
			"type": "text",
			"version": 929,
			"versionNonce": 928656382,
			"isDeleted": false,
			"id": "NpHqGDcw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.728102927234714,
			"x": 226.4291171597936,
			"y": -1381.4634509739965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.092132568359375,
			"height": 10.56073817261245,
			"seed": 896526143,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 8.44859053808996,
			"fontFamily": 1,
			"text": ">",
			"rawText": ">",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": ">",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 1241,
			"versionNonce": 598547170,
			"isDeleted": false,
			"id": "oZ1dtVJ0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.276264141135636,
			"x": 223.32433051693525,
			"y": -1478.943428163856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.4638671875,
			"height": 6.979032388118749,
			"seed": 593855537,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "iyCl0VkS4wtEqqay_76ZR",
					"type": "arrow"
				}
			],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 5.583225910494999,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "rectangle",
			"version": 492,
			"versionNonce": 225442878,
			"isDeleted": false,
			"id": "jalY3LcQtZDny2-Cli1t9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -647.2258827756356,
			"y": -693.8928941030149,
			"strokeColor": "#e03131",
			"backgroundColor": "#e03131",
			"width": 80.22849399154768,
			"height": 13.067232353598797,
			"seed": 1820122107,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 510,
			"versionNonce": 1053519522,
			"isDeleted": false,
			"id": "16-K4Kh2ORfhTu_i1YtuN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 20,
			"angle": 0,
			"x": 538.6078448585573,
			"y": -1422.7478952724537,
			"strokeColor": "transparent",
			"backgroundColor": "#9775fa",
			"width": 127.0475233871947,
			"height": 161.62374810649453,
			"seed": 941212021,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "rSD5F7Y0KD_XClwEdofMB",
					"type": "arrow"
				},
				{
					"id": "Riuoy42pehwfY_c4h1tSV",
					"type": "arrow"
				}
			],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 573,
			"versionNonce": 2028061822,
			"isDeleted": false,
			"id": "uqoDFM9DiKcLSHdRXbqsQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -1712.6492521187333,
			"y": -893.8004041596602,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 120.45094223002252,
			"height": 10.7545484133949,
			"seed": 932422422,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 582,
			"versionNonce": 1382632034,
			"isDeleted": false,
			"id": "891-Y2HXEqe-Gn_92-WwR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 20,
			"angle": 0,
			"x": 723.550442194347,
			"y": -1434.8093690117441,
			"strokeColor": "transparent",
			"backgroundColor": "#ffa94d",
			"width": 215.49833080865938,
			"height": 192.98357982865014,
			"seed": 127876987,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 876,
			"versionNonce": 1534100670,
			"isDeleted": false,
			"id": "ZIGLYvpA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1936.9566548164216,
			"y": -1535.0621721543014,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 4626,
			"groupIds": [
				"XE9FmgJU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5714295ca3c1f7d10fefa49c1f0fb788627b8d4a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 817,
			"versionNonce": 894807586,
			"isDeleted": false,
			"id": "aUkprZQD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1936.9339282473686,
			"y": -1535.0915848296447,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 58503,
			"groupIds": [
				"XE9FmgJU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 788,
			"versionNonce": 918371582,
			"isDeleted": false,
			"id": "vFIFPWNi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1514.0970986102864,
			"y": -951.9036697947365,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 2.6168212890625,
			"height": 12.083302680123557,
			"seed": 380244298,
			"groupIds": [
				"XE9FmgJU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 9.666642144098846,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 766,
			"versionNonce": 209689058,
			"isDeleted": false,
			"id": "UocU7XmS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1868.940755033406,
			"y": -962.6908650651899,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 92.03221130371094,
			"height": 20,
			"seed": 1351906646,
			"groupIds": [
				"XE9FmgJU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "transformer",
			"rawText": "transformer",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "transformer",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 991,
			"versionNonce": 810085694,
			"isDeleted": false,
			"id": "BtRkzwpgX7MHvsxWGPXFL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 30,
			"angle": 0,
			"x": -1052.7713058141253,
			"y": -1068.149310675533,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 485.2107291857384,
			"height": 119.63337932905223,
			"seed": 466881110,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 575,
			"versionNonce": 116788642,
			"isDeleted": false,
			"id": "JnGdLGgz8QssBEhtI3Obn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -1027.792840587932,
			"y": -1147.4481723029548,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 272.9019978139081,
			"height": 10.459658452798067,
			"seed": 366206102,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 766,
			"versionNonce": 359961982,
			"isDeleted": false,
			"id": "BQwspL-ubt95qi0ePQxSm",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -943.6401339449674,
			"y": -1160.2850258586611,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 373.2196311566514,
			"height": 10.935097473379528,
			"seed": 1612121546,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 655,
			"versionNonce": 434637154,
			"isDeleted": false,
			"id": "DA6QcfJLNA4mafy4lhEHT",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -1049.663035534691,
			"y": -1304.3430490949227,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 317.11782672800825,
			"height": 14.263170617451578,
			"seed": 1159912522,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 1245,
			"versionNonce": 1017416994,
			"isDeleted": false,
			"id": "XfClamgt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1173.270542716355,
			"y": -1535.0327594789583,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 45929,
			"groupIds": [
				"e83Z6Yeb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "da8a402c484735f8f5024ba211750e85aee0e0b0",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 1149,
			"versionNonce": 614111458,
			"isDeleted": false,
			"id": "a8Nt0EWj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -627.6819493723683,
			"y": -860.0856903219833,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 91.95188903808594,
			"height": 24.88001272787367,
			"seed": 472030171,
			"groupIds": [
				"e83Z6Yeb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"fontSize": 9.952005091149468,
			"fontFamily": 1,
			"text": "Convert something \ninto another form ",
			"rawText": "Convert something \ninto another form ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Convert something \ninto another form ",
			"lineHeight": 1.25,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 544,
			"versionNonce": 2057395774,
			"isDeleted": false,
			"id": "gIv9impI4dh_yV_OgPdtJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": -694.420487557141,
			"y": -1137.2629192522897,
			"strokeColor": "#ffec99",
			"backgroundColor": "#ffec99",
			"width": 63.894967930743974,
			"height": 17.03865811486503,
			"seed": 165657418,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 787,
			"versionNonce": 22621346,
			"isDeleted": false,
			"id": "jCobubXe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1941,
			"y": -554.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 44430,
			"groupIds": [
				"YUZIaecb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 787,
			"versionNonce": 1033299582,
			"isDeleted": false,
			"id": "zYQgCoYF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1941.022726569053,
			"y": -553.9862123246568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 93865,
			"groupIds": [
				"YUZIaecb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "fb5c327996f7ddeb9e4c71884338d2fc0e12db13",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 767,
			"versionNonce": 948914274,
			"isDeleted": false,
			"id": "Xx8orCNw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1177,
			"y": -554.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 58813,
			"groupIds": [
				"BtT9r605"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 767,
			"versionNonce": 1362192062,
			"isDeleted": false,
			"id": "CXjaZ0Aa",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1177.022726569053,
			"y": -553.9862123246568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 13964,
			"groupIds": [
				"BtT9r605"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927699,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ca38b461bb8850f766d490b3341139c35e17cce8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 780,
			"versionNonce": 571206690,
			"isDeleted": false,
			"id": "iFZuYt5k",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -412.41445863235816,
			"y": -554.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 3114,
			"groupIds": [
				"t6Ydyysx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 780,
			"versionNonce": 1175576318,
			"isDeleted": false,
			"id": "dIKJ0b4g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -412.4371852014111,
			"y": -553.9862123246568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 20672,
			"groupIds": [
				"t6Ydyysx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "4a26b3f168b3d8bc44e1d5ff231aa92b0b723b79",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 766,
			"versionNonce": 1136531426,
			"isDeleted": false,
			"id": "77h3exoa",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 352,
			"y": -554.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 30977,
			"groupIds": [
				"uYa9Rba0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 766,
			"versionNonce": 1891192638,
			"isDeleted": false,
			"id": "LfScLNf8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.97727343094704,
			"y": -553.9862123246568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 94753,
			"groupIds": [
				"uYa9Rba0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e329a5131f89e0a72545287e2691aaeceab0ae80",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 769,
			"versionNonce": 229952418,
			"isDeleted": false,
			"id": "pzxqJ38H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1118.0536871233112,
			"y": -554.015625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 24530,
			"groupIds": [
				"W2L4tfF0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 768,
			"versionNonce": 1837676414,
			"isDeleted": false,
			"id": "RufqxUBJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1118.0309605542582,
			"y": -553.9862123246568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 51953,
			"groupIds": [
				"W2L4tfF0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e5892304a04ab01776bd49f97c69e4aff38704e5",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 596,
			"versionNonce": 371132258,
			"isDeleted": false,
			"id": "xukNHBQ7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1941,
			"y": 426.984375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 49239,
			"groupIds": [
				"4TguL53z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 596,
			"versionNonce": 616634302,
			"isDeleted": false,
			"id": "UqPPI9cp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1941.022726569053,
			"y": 427.0137876753432,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 72664,
			"groupIds": [
				"4TguL53z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e6702aeb913a3e82b8794ead601b32f80128726c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 596,
			"versionNonce": 1431030562,
			"isDeleted": false,
			"id": "6xvsuswj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1177,
			"y": 426.984375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 22726,
			"groupIds": [
				"wOaud9dJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 596,
			"versionNonce": 1317236734,
			"isDeleted": false,
			"id": "D3OYB2sJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1177.022726569053,
			"y": 427.0137876753432,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 95577,
			"groupIds": [
				"wOaud9dJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c73ee5d2986ca79b0d4f2ca9c475acd12145c06a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 813,
			"versionNonce": 1638536930,
			"isDeleted": false,
			"id": "odHoSkZn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -409.9693763693645,
			"y": 426.57913479919057,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 33814,
			"groupIds": [
				"acR0JI5z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 813,
			"versionNonce": 1993392190,
			"isDeleted": false,
			"id": "X1UvxVmT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -409.9921029384175,
			"y": 426.6085474745338,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 88168,
			"groupIds": [
				"acR0JI5z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1d84606c8d74f33d0d49538e73641f9003a332be",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 596,
			"versionNonce": 734587554,
			"isDeleted": false,
			"id": "PIrqt14U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 352,
			"y": 426.984375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 50620,
			"groupIds": [
				"GDSTEVpW"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 596,
			"versionNonce": 25823358,
			"isDeleted": false,
			"id": "YxoFV9zd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.97727343094704,
			"y": 427.0137876753432,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 70354,
			"groupIds": [
				"GDSTEVpW"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "441782208a6497f58e649627863b2642b650e4a9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 596,
			"versionNonce": 978798178,
			"isDeleted": false,
			"id": "3f2RRCAT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1117,
			"y": 426.984375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 25845,
			"groupIds": [
				"9keIqf9x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 596,
			"versionNonce": 779110590,
			"isDeleted": false,
			"id": "6dfui00i",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1116.977273430947,
			"y": 427.0137876753432,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 56182,
			"groupIds": [
				"9keIqf9x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "40bb1b246077708827187ac7cbff6fd497529bea",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 536,
			"versionNonce": 1713646114,
			"isDeleted": false,
			"id": "PLJSMn_QDvcEtsHls-76t",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1550.7420692519527,
			"y": -936.1844928990229,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 30.260912084267602,
			"height": 0,
			"seed": 308547030,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					30.260912084267602,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1605,
			"versionNonce": 488931582,
			"isDeleted": false,
			"id": "UDR6Ycgx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1366.4269302346397,
			"y": -1035.4992145895135,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 153.480712890625,
			"height": 24.59804721053787,
			"seed": 841351766,
			"groupIds": [
				"mJtG0LNfypqBbjvGpoAVl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"fontSize": 6.559479256143431,
			"fontFamily": 1,
			"text": "1. BLEU (Bilingual Evaluation Understudy) is a \nmetric used to evaluate machine translation \ncompared with a reference translation.",
			"rawText": "1. BLEU (Bilingual Evaluation Understudy) is a \nmetric used to evaluate machine translation \ncompared with a reference translation.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. BLEU (Bilingual Evaluation Understudy) is a \nmetric used to evaluate machine translation \ncompared with a reference translation.",
			"lineHeight": 1.25,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 1102,
			"versionNonce": 371103202,
			"isDeleted": false,
			"id": "JDkyMLek",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -943.2490482037007,
			"y": -1115.4489375243843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 241.802490234375,
			"height": 45.35127847020768,
			"seed": 474671062,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"fontSize": 12.093674258722048,
			"fontFamily": 1,
			"text": "Transformers reduce the computational \ncomplexity required to relate signals \nbetween distant positions.",
			"rawText": "Transformers reduce the computational \ncomplexity required to relate signals \nbetween distant positions.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Transformers reduce the computational \ncomplexity required to relate signals \nbetween distant positions.",
			"lineHeight": 1.25,
			"baseline": 40
		},
		{
			"type": "text",
			"version": 1802,
			"versionNonce": 1361555774,
			"isDeleted": false,
			"id": "WIfewKOt",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -560.0370865714066,
			"y": -1060.5015334705563,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 125.86801147460938,
			"height": 90.58726852373758,
			"seed": 123379094,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927700,
			"link": null,
			"locked": false,
			"fontSize": 9.058726852373757,
			"fontFamily": 1,
			"text": "self-attention captures \nglobal similarities while \nmulti-head attention \nimproves local similarity \nby attending simultaneously \nbut separately across \nvarious parts or aspects \nwithin each layer.",
			"rawText": "self-attention captures \nglobal similarities while \nmulti-head attention \nimproves local similarity \nby attending simultaneously \nbut separately across \nvarious parts or aspects \nwithin each layer.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "self-attention captures \nglobal similarities while \nmulti-head attention \nimproves local similarity \nby attending simultaneously \nbut separately across \nvarious parts or aspects \nwithin each layer.",
			"lineHeight": 1.25,
			"baseline": 87
		},
		{
			"type": "line",
			"version": 486,
			"versionNonce": 903534974,
			"isDeleted": false,
			"id": "2k02pmlYjj3JJ-j8KD1jf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -702.8021716659582,
			"y": -827.1687768425484,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 94.96056140208964,
			"height": 0.637319204040864,
			"seed": 599127419,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					94.96056140208964,
					-0.637319204040864
				]
			]
		},
		{
			"type": "line",
			"version": 700,
			"versionNonce": 1291322722,
			"isDeleted": false,
			"id": "t63yU-dZyCTaW4gZbLjC8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -640.9822088739937,
			"y": -829.7180536587118,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 5.098553632326912,
			"height": 26.13008736567565,
			"seed": 918871675,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.098553632326912,
					-26.13008736567565
				]
			]
		},
		{
			"type": "text",
			"version": 904,
			"versionNonce": 578746814,
			"isDeleted": false,
			"id": "mP2sIOqn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1133.2553087934507,
			"y": -1016.6600685285034,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 61.48622131347656,
			"height": 13.309058487100403,
			"seed": 1472089307,
			"groupIds": [
				"j03_3i_W_5Aj0OMxcBn3O"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "computation",
			"rawText": "computation",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "computation",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1016,
			"versionNonce": 72681762,
			"isDeleted": false,
			"id": "WM2zyzAS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1119.8148180707944,
			"y": -820.3716854196252,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 34.60523986816406,
			"height": 13.309058487100403,
			"seed": 834009467,
			"groupIds": [
				"mJQTZ8phcFj9_uJGuCd3n"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "pioneer",
			"rawText": "pioneer",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "pioneer",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1025,
			"versionNonce": 1580536318,
			"isDeleted": false,
			"id": "ZFspYZPN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1120.9623095258726,
			"y": -704.2138704074835,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 36.90022277832031,
			"height": 13.309058487100403,
			"seed": 357503515,
			"groupIds": [
				"8YQCyrXjJkWH6A4IIWk85"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "mapping",
			"rawText": "mapping",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "mapping",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1199,
			"versionNonce": 417043682,
			"isDeleted": false,
			"id": "j9HL0zOf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1139.1688103280035,
			"y": -926.8375619332566,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 78.3585205078125,
			"height": 13.309058487100403,
			"seed": 595334843,
			"groupIds": [
				"plHn5yJ2ZWIu4QyOAswtR"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "intra-attention",
			"rawText": "intra-attention",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "intra-attention",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1283,
			"versionNonce": 603857470,
			"isDeleted": false,
			"id": "4qGbUgt8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1127.8168940462363,
			"y": -874.3115338123758,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 52.80567932128906,
			"height": 13.309058487100403,
			"seed": 2146490651,
			"groupIds": [
				"aPC32Bj5a7jfPZOsTIqYm"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "recurrence",
			"rawText": "recurrence",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "recurrence",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1072,
			"versionNonce": 1008380066,
			"isDeleted": false,
			"id": "Qdmp7Bfl",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -327.43429733728345,
			"y": -993.4547881633824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 29.3671875,
			"height": 13.309058487100403,
			"seed": 1535214005,
			"groupIds": [
				"TnXbI4NqOBM9YbI1WgtHL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "stack",
			"rawText": "stack",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stack",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "image",
			"version": 1021,
			"versionNonce": 649800318,
			"isDeleted": false,
			"id": "iq9togZD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 359.43377493827177,
			"y": -1539.6162215845363,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 41713,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5927fa443d144b8be253560c99c59e3390659560",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 1011,
			"versionNonce": 364987490,
			"isDeleted": false,
			"id": "g8eXoR4s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 358.9637627890456,
			"y": -1539.6456342598794,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 16192,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 787,
			"versionNonce": 355281598,
			"isDeleted": false,
			"id": "I9UwuLu6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1116.8423149085595,
			"y": -1535.9045189200476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734,
			"height": 950,
			"seed": 65099,
			"groupIds": [
				"nQpKyyvB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 787,
			"versionNonce": 2141087778,
			"isDeleted": false,
			"id": "xOoz39bn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1116.8195883395065,
			"y": -1535.8751062447043,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 734.0454531381059,
			"height": 949.9411746493136,
			"seed": 37268,
			"groupIds": [
				"nQpKyyvB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8a14fd8c42a9d050105a885c79b149f12d94206d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 1081,
			"versionNonce": 502604542,
			"isDeleted": false,
			"id": "O7cEbUvN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -217.76096979720262,
			"y": -1202.4394024317942,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 56.13812255859375,
			"height": 13.568672842863673,
			"seed": 350349115,
			"groupIds": [
				"zbyQV5Wc8ftPJSBw0Ohbi"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "F84e788WayPlG0bv-fyVH",
					"type": "arrow"
				}
			],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 10.854938274290939,
			"fontFamily": 1,
			"text": "sub-layer 1",
			"rawText": "sub-layer 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sub-layer 1",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "arrow",
			"version": 1396,
			"versionNonce": 1101075426,
			"isDeleted": false,
			"id": "F84e788WayPlG0bv-fyVH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -116.13406516477933,
			"y": -1198.204581034593,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 31.880892020897434,
			"height": 0.07080949015607985,
			"seed": 1757808661,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "O7cEbUvN",
				"focus": -0.3962346475984198,
				"gap": 13.607890052932106
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					-31.880892020897434,
					-0.07080949015607985
				]
			]
		},
		{
			"type": "arrow",
			"version": 4903,
			"versionNonce": 1939084094,
			"isDeleted": false,
			"id": "8opCJnJSlSS9ohtBk-uZW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -120.07933955936404,
			"y": -1267.213740547717,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 20.461573210707215,
			"height": 0.004228369450174796,
			"seed": 166687061,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "ggXAtAp2",
				"focus": 0.31263682772772833,
				"gap": 8.7890667338566
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					-20.461573210707215,
					0.004228369450174796
				]
			]
		},
		{
			"type": "arrow",
			"version": 2640,
			"versionNonce": 1306019746,
			"isDeleted": false,
			"id": "oo2w3sReEG3C_Id8X4X9Y",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -85.38630992522064,
			"y": -1236.9861606512427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 77.96201526687281,
			"height": 0.28516889725733563,
			"seed": 538920603,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					-77.96201526687281,
					0.28516889725733563
				]
			]
		},
		{
			"type": "text",
			"version": 1605,
			"versionNonce": 1349188478,
			"isDeleted": false,
			"id": "OhYmMLCC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -308.9765919986235,
			"y": -1308.904783202183,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 150.48915100097656,
			"height": 22.031240627988847,
			"seed": 2064805563,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "GMhHSKyVIjT8HSrmYGJwd",
					"type": "arrow"
				}
			],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 8.812496251195538,
			"fontFamily": 1,
			"text": "LayerNorm2(LayerNorm1 + \n            Sublayer2(LayerNorm1))",
			"rawText": "LayerNorm2(LayerNorm1 + \n            Sublayer2(LayerNorm1))",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "LayerNorm2(LayerNorm1 + \n            Sublayer2(LayerNorm1))",
			"lineHeight": 1.25,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 4186,
			"versionNonce": 2087912290,
			"isDeleted": false,
			"id": "GMhHSKyVIjT8HSrmYGJwd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -84.29424855198704,
			"y": -1295.686128901851,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 67.04569524608604,
			"height": 0.38259260354629987,
			"seed": 588923125,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6fzGUVrQ",
				"focus": -2.244182885762582,
				"gap": 12.533923466308352
			},
			"endBinding": {
				"elementId": "OhYmMLCC",
				"focus": 0.26699804498305874,
				"gap": 7.147497199573877
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					-67.04569524608604,
					0.38259260354629987
				]
			]
		},
		{
			"type": "text",
			"version": 615,
			"versionNonce": 2059066302,
			"isDeleted": false,
			"id": "g4mEZXo4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -308.26859342926036,
			"y": -1110.8380505580942,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ced4da",
			"width": 53.00810241699219,
			"height": 20,
			"seed": 629141019,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Encode",
			"rawText": "Encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Encode",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 1347,
			"versionNonce": 1203783458,
			"isDeleted": false,
			"id": "vBz7V0SK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 210.5891538314977,
			"y": -918.8808212103675,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ced4da",
			"width": 124.42228698730469,
			"height": 42.00148826213808,
			"seed": 1438220763,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "-FzsFhIXM6743XyTTtfj1",
					"type": "arrow"
				}
			],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"fontSize": 5.600198434951745,
			"fontFamily": 1,
			"text": "Fixed size enables smooth information \npropagation through these residual \npaths without any mismatch or inconsistency \nin dimension sizes. This promotes better \ngradient flow and overall optimization \nduring training.",
			"rawText": "Fixed size enables smooth information \npropagation through these residual \npaths without any mismatch or inconsistency \nin dimension sizes. This promotes better \ngradient flow and overall optimization \nduring training.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Fixed size enables smooth information \npropagation through these residual \npaths without any mismatch or inconsistency \nin dimension sizes. This promotes better \ngradient flow and overall optimization \nduring training.",
			"lineHeight": 1.25,
			"baseline": 40
		},
		{
			"type": "line",
			"version": 515,
			"versionNonce": 1218753534,
			"isDeleted": false,
			"id": "hQM7c3RVn6cYO-K_-rome",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -89.74994573957105,
			"y": -832.4792266152392,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ced4da",
			"width": 336.44932873427143,
			"height": 2.4361194695192125,
			"seed": 1420797173,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					336.44932873427143,
					-2.4361194695192125
				]
			]
		},
		{
			"type": "arrow",
			"version": 1022,
			"versionNonce": 137302754,
			"isDeleted": false,
			"id": "-FzsFhIXM6743XyTTtfj1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 246.7079241331836,
			"y": -835.161214934339,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ced4da",
			"width": 0.4813917166241879,
			"height": 31.73932635991298,
			"seed": 2053973653,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927701,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "vBz7V0SK",
				"focus": 0.4020669944311832,
				"gap": 9.978791653977396
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					0.4813917166241879,
					-31.73932635991298
				]
			]
		},
		{
			"type": "text",
			"version": 1463,
			"versionNonce": 606700606,
			"isDeleted": false,
			"id": "pdpI6krC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -393.6449867946284,
			"y": -866.4468043719899,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ced4da",
			"width": 106.59701538085938,
			"height": 37.85850702832671,
			"seed": 1572083061,
			"groupIds": [
				"YL3IcZ4E1RFcIhp8scP-e"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "ol5Im8alKbHG6kgVtgzMw",
					"type": "arrow"
				}
			],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 10.095601874220458,
			"fontFamily": 1,
			"text": "Facilitation is based \non constant size not\nthe size itself.",
			"rawText": "Facilitation is based \non constant size not\nthe size itself.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Facilitation is based \non constant size not\nthe size itself.",
			"lineHeight": 1.25,
			"baseline": 33
		},
		{
			"type": "arrow",
			"version": 689,
			"versionNonce": 810444450,
			"isDeleted": false,
			"id": "ol5Im8alKbHG6kgVtgzMw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -208.5247691423147,
			"y": -847.5486370491599,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ced4da",
			"width": 67.92127774969669,
			"height": 0.2585911163973833,
			"seed": 242244757,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "pdpI6krC",
				"focus": -0.027856752115043334,
				"gap": 10.60192452175761
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					-67.92127774969669,
					-0.2585911163973833
				]
			]
		},
		{
			"type": "arrow",
			"version": 439,
			"versionNonce": 254430334,
			"isDeleted": false,
			"id": "rSD5F7Y0KD_XClwEdofMB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.601732793913,
			"y": -1335.664905524271,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#9775fa",
			"width": 104.0600005127244,
			"height": 8.671666709393548,
			"seed": 1964989467,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "16-K4Kh2ORfhTu_i1YtuN",
				"focus": 0.1361928878792749,
				"gap": 1.946364548161057
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					104.0600005127244,
					-8.671666709393548
				]
			]
		},
		{
			"type": "text",
			"version": 477,
			"versionNonce": 147669602,
			"isDeleted": false,
			"id": "yUuzETzF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -565.528062903701,
			"y": -697.3700051917016,
			"strokeColor": "#e03131",
			"backgroundColor": "#e03131",
			"width": 5.3733978271484375,
			"height": 9.45757456683623,
			"seed": 1715298357,
			"groupIds": [
				"e83Z6Yeb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 7.566059653468985,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 1078,
			"versionNonce": 661130430,
			"isDeleted": false,
			"id": "I5U7WcjR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 35.66513260610776,
			"y": -1090.9282030061836,
			"strokeColor": "#e03131",
			"backgroundColor": "#e03131",
			"width": 7.3758087158203125,
			"height": 12.961370770884397,
			"seed": 858214811,
			"groupIds": [
				"FgiJ1zNBfwPpYSFGEk-_7"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "0DbhOsjPiIUB8ehGsnLfn",
					"type": "arrow"
				}
			],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 10.369096616707518,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "arrow",
			"version": 1412,
			"versionNonce": 1819977250,
			"isDeleted": false,
			"id": "royI-XaIrlJptd4iHJ9o8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 38.31145580896694,
			"y": -1204.6583474521126,
			"strokeColor": "#f08c00",
			"backgroundColor": "#e03131",
			"width": 71.78753061139001,
			"height": 0.34495565561383046,
			"seed": 281521265,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "xNdpXUVO",
				"focus": -0.09553330145776753,
				"gap": 8.412686699701922
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					71.78753061139001,
					0.34495565561383046
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1087,
			"versionNonce": 713278718,
			"isDeleted": false,
			"id": "MQ7FgB1YVPJ9PodsNR9G4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.81602049380194,
			"y": -1293.9414190120365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 1625275953,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1141,
			"versionNonce": 71668194,
			"isDeleted": false,
			"id": "Bl_ksqKlmGXdDQQo-3Otv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.74608623647543,
			"y": -1323.6582737239983,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 15194353,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1098,
			"versionNonce": 2046719294,
			"isDeleted": false,
			"id": "iNTdg3esQFSpuw1AjqF9x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.78147688146473,
			"y": -1308.6198834484233,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 196820799,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1106,
			"versionNonce": 54330786,
			"isDeleted": false,
			"id": "UYroTLIDCAGIHLXLdn5u7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.71335071142317,
			"y": -1337.568435625099,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 2081110207,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1160,
			"versionNonce": 523836798,
			"isDeleted": false,
			"id": "FO8OOVX3HHQ4QXZX9ApCq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.64341645409775,
			"y": -1367.2852903370597,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 1690552543,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1117,
			"versionNonce": 1653604706,
			"isDeleted": false,
			"id": "9-MdBkppPmn-OwSADQfmk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 172.678807099087,
			"y": -1352.2469000614838,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 607474943,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1137,
			"versionNonce": 1333050814,
			"isDeleted": false,
			"id": "RuC9s9RjyvZhpdvltMuxj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.65257675357188,
			"y": -1398.89904144659,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 1982380287,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1184,
			"versionNonce": 495813922,
			"isDeleted": false,
			"id": "JPyhBfRl7xdcT-iDOpdD4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.5826424962451,
			"y": -1428.6158961585513,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 2009547039,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1144,
			"versionNonce": 1876055550,
			"isDeleted": false,
			"id": "dGQP5yjdWLNJAtguZTlyW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.6180331412357,
			"y": -1413.577505882976,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 815777087,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1158,
			"versionNonce": 1839501538,
			"isDeleted": false,
			"id": "V2QcUhAvTT0kp5z2Xpjdv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.54990697119504,
			"y": -1442.5260580596503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 538101087,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1230,
			"versionNonce": 424863294,
			"isDeleted": false,
			"id": "BLLYH9bGbZPhn3G77cSGZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.47997271386905,
			"y": -1472.5239787951045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 91275647,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1191,
			"versionNonce": 107226274,
			"isDeleted": false,
			"id": "0dMPhmRQsnwMBiGs-Wr0e",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 225.51536335885746,
			"y": -1457.485588519529,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 11.617674782639163,
			"height": 31.17322200039489,
			"seed": 1643788703,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 5747,
			"versionNonce": 483880574,
			"isDeleted": false,
			"id": "iWv531Ck_NSB9hbSoL8nB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 314.3421882923011,
			"y": -1457.2849117133312,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 134.1333323016937,
			"height": 44.78095040376479,
			"seed": 230363263,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.406902161962307,
					19.675351292300547
				],
				[
					-37.331434690247704,
					44.78095040376479
				],
				[
					-93.24777915908498,
					42.06132055183298
				],
				[
					-125.7264301397314,
					25.41776341542254
				],
				[
					-115.36104231225335,
					0.7190308067150113
				]
			]
		},
		{
			"type": "line",
			"version": 1142,
			"versionNonce": 1367031906,
			"isDeleted": false,
			"id": "U5Kn1Xl2ZJHnxFkvQ6A6A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 194.02937048599776,
			"y": -1392.2220598230087,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.288046682583655,
			"height": 50.116750698201066,
			"seed": 617570527,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.615646825860756,
					5.999222396449495
				],
				[
					8.396298911394958,
					45.07072733388659
				],
				[
					19.288046682583655,
					50.116750698201066
				]
			]
		},
		{
			"type": "text",
			"version": 1484,
			"versionNonce": 119598782,
			"isDeleted": false,
			"id": "a9XmQxMt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.66131696551255,
			"y": -1340.378871496257,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 484524831,
			"groupIds": [
				"DLpf0sacnfCB0eGdZe3O7",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1483,
			"versionNonce": 716760098,
			"isDeleted": false,
			"id": "Gs0sKgmE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.92493550249583,
			"y": -1325.8368317781853,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 528797745,
			"groupIds": [
				"44j2uy91OyP89xB0Nb7EA",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1469,
			"versionNonce": 617637630,
			"isDeleted": false,
			"id": "37b9byo4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.8933284003583,
			"y": -1310.3112879865034,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 12662769,
			"groupIds": [
				"rOu81GFJ-SfuAes5YUYZI",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1479,
			"versionNonce": 470552546,
			"isDeleted": false,
			"id": "9YBG04Nd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.87940691238626,
			"y": -1296.324022453362,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 628649919,
			"groupIds": [
				"rE-rMDubqnp1Rcx5EWsdD",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1481,
			"versionNonce": 107403070,
			"isDeleted": false,
			"id": "KksIYq0P",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.85613065008803,
			"y": -1281.2357473860432,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 640127377,
			"groupIds": [
				"ZJ3Ygniun4lLySbbjkl8h",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1486,
			"versionNonce": 428065698,
			"isDeleted": false,
			"id": "1MasIgb9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.275247769366635,
			"x": 168.68482814750908,
			"y": -1355.6194275862902,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.564285278320312,
			"height": 7.69669492685712,
			"seed": 993854079,
			"groupIds": [
				"waHE8hRHf2IbeCE6CA1Pn",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.1573559414856955,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1518,
			"versionNonce": 71647102,
			"isDeleted": false,
			"id": "HE7nUbbf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 221.1430159974204,
			"y": -1461.8264030303749,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 928271103,
			"groupIds": [
				"rxsE9t4hghUBaiMTv67ff",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1145,
			"versionNonce": 1028587362,
			"isDeleted": false,
			"id": "cI8c0Y0p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.8488305642521006,
			"x": 234.00791163971573,
			"y": -1381.633964802048,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 3.34954833984375,
			"height": 8.645350987754352,
			"seed": 1575554303,
			"groupIds": [
				"Q-aNFSmgRoNUXqlhVDL45",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.916280790203481,
			"fontFamily": 1,
			"text": ">",
			"rawText": ">",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": ">",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1523,
			"versionNonce": 1118609342,
			"isDeleted": false,
			"id": "SeVlfHsT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 221.04420569258252,
			"y": -1448.3449880727846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 1464499441,
			"groupIds": [
				"c0UMViza0UQGM9lHg-XDY",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1519,
			"versionNonce": 62702370,
			"isDeleted": false,
			"id": "pCzd9jB2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 220.92002166087966,
			"y": -1431.401649366876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 493394623,
			"groupIds": [
				"7xXg31EUmXovk-WCmTJst",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1529,
			"versionNonce": 901642238,
			"isDeleted": false,
			"id": "6F1Hv76H",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 220.59117153861456,
			"y": -1417.7550643141599,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 958068369,
			"groupIds": [
				"OCrjvm7tAodb3APHMN2-x",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1535,
			"versionNonce": 121376482,
			"isDeleted": false,
			"id": "Uysnd4eB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 220.48078573265576,
			"y": -1402.6943187977972,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 350289695,
			"groupIds": [
				"VCSyk43-jkqZpN5AypUUy",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927702,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 1533,
			"versionNonce": 628770878,
			"isDeleted": false,
			"id": "6yXUs0K2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.281034339128549,
			"x": 220.3726996309884,
			"y": -1387.9473388130257,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.190643310546875,
			"height": 7.696694926857118,
			"seed": 831411249,
			"groupIds": [
				"dPRVPu4UIVH2Nxapvissg",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.157355941485695,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "rectangle",
			"version": 881,
			"versionNonce": 1012654754,
			"isDeleted": false,
			"id": "bvDNjcBvVlx4sXWyyL4Nd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 132.45534739896283,
			"y": -1336.007871530465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 94.65996441676984,
			"height": 41.17633054179882,
			"seed": 527821617,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 878,
			"versionNonce": 834834558,
			"isDeleted": false,
			"id": "Mw6iVEL7kSFpzLv8F8Hn5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 184.98159610687537,
			"y": -1442.3879610465583,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 94.65996441676984,
			"height": 44.490183275881776,
			"seed": 1546733265,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 853,
			"versionNonce": 768294498,
			"isDeleted": false,
			"id": "ayXviAoB3ZJW7BSJ8t7-6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 228.29451336581278,
			"y": -1488.851437528828,
			"strokeColor": "#868e96",
			"backgroundColor": "transparent",
			"width": 7.15315096976145,
			"height": 26.228220222458788,
			"seed": 2036832223,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 948,
			"versionNonce": 1448595646,
			"isDeleted": false,
			"id": "mFJ-q08OY2BpMLIDd87Q0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 228.13490887141367,
			"y": -1501.114736999292,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 7.15315096976145,
			"height": 26.228220222458788,
			"seed": 787412177,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "vw9NKrcHMjUCAH9CnX90-",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 962,
			"versionNonce": 945365538,
			"isDeleted": false,
			"id": "cc1RUjGieX3fw70jT3JAh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 208.6912411455343,
			"y": -1420.8084778117131,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 82.93760677044453,
			"height": 0.3208418056884042,
			"seed": 1732494577,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					82.93760677044453,
					0.3208418056884042
				]
			]
		},
		{
			"type": "text",
			"version": 1335,
			"versionNonce": 1859848446,
			"isDeleted": false,
			"id": "FjGW6nn4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 6.2819430204356825,
			"x": 222.74697115192646,
			"y": -1489.822698985008,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 18.296096801757812,
			"height": 5.71325446801286,
			"seed": 1676931985,
			"groupIds": [
				"TZpe5Joiezxv1mbfnUMKz",
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "iyCl0VkS4wtEqqay_76ZR",
					"type": "arrow"
				},
				{
					"id": "vw9NKrcHMjUCAH9CnX90-",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 4.5706035744102875,
			"fontFamily": 1,
			"text": "softmax",
			"rawText": "softmax",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "softmax",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "arrow",
			"version": 2167,
			"versionNonce": 1190432226,
			"isDeleted": false,
			"id": "iyCl0VkS4wtEqqay_76ZR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 229.21087332955284,
			"y": -1469.8329281979272,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 4.564010292682013,
			"height": 0.06215348793807607,
			"seed": 2043200305,
			"groupIds": [
				"dFilg3dcARm7mewCrfihG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BVtissw8",
				"focus": -4.657199944876672,
				"gap": 15.831238052405183
			},
			"endBinding": {
				"elementId": "FjGW6nn4",
				"focus": 0.022735581229067527,
				"gap": 12.02504197806195
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					4.564010292682013,
					0.06215348793807607
				]
			]
		},
		{
			"type": "arrow",
			"version": 381,
			"versionNonce": 986528062,
			"isDeleted": false,
			"id": "vw9NKrcHMjUCAH9CnX90-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 231.38531548284402,
			"y": -1479.4048830342713,
			"strokeColor": "#868e96",
			"backgroundColor": "transparent",
			"width": 0.06670360581796331,
			"height": 4.874453351690363,
			"seed": 1595031185,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FjGW6nn4",
				"focus": -0.06676734067316134,
				"gap": 4.70392244977586
			},
			"endBinding": {
				"elementId": "mFJ-q08OY2BpMLIDd87Q0",
				"focus": 0.03373584829033001,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-0.06670360581796331,
					-4.874453351690363
				]
			]
		},
		{
			"type": "text",
			"version": 1059,
			"versionNonce": 246186402,
			"isDeleted": false,
			"id": "BVtissw8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 249.96074907431122,
			"y": -1465.7312935758007,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 3.34954833984375,
			"height": 8.645350987754352,
			"seed": 263330815,
			"groupIds": [
				"Rl785WdB655Io5Y2oAkZk",
				"ARN0M__cvDT4ebvqzl3NU"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "iyCl0VkS4wtEqqay_76ZR",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.916280790203481,
			"fontFamily": 1,
			"text": ">",
			"rawText": ">",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": ">",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 1086,
			"versionNonce": 1636786558,
			"isDeleted": false,
			"id": "AG3LTNN9CYcGmSk-7Ycvr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 155.97409596443967,
			"y": -1314.8802724349978,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.93760677044453,
			"height": 0.3208418056884042,
			"seed": 191291839,
			"groupIds": [
				"b-VHOhvAj8fxE5LpbrOuA"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					82.93760677044453,
					0.3208418056884042
				]
			]
		},
		{
			"type": "text",
			"version": 1183,
			"versionNonce": 1253047650,
			"isDeleted": false,
			"id": "oT5XhZLj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.710035631455286,
			"x": 197.24360389321654,
			"y": -1359.803088199085,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.34954833984375,
			"height": 8.645350987754352,
			"seed": 1019367903,
			"groupIds": [
				"RVU09q9NANyhdZ8dE6yaH",
				"Og4iEVevd7YreMX_pEYCz"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.916280790203481,
			"fontFamily": 1,
			"text": ">",
			"rawText": ">",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": ">",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "rectangle",
			"version": 460,
			"versionNonce": 1986167230,
			"isDeleted": false,
			"id": "NsLJeFJ2y2U0HmC2vylF9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 152.02450053687528,
			"y": -1517.6333330815849,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 138.36461915922393,
			"height": 255.73504357356728,
			"seed": 1793076991,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "nUudDTYydqFtDN95qb_Kb",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "freedraw",
			"version": 303,
			"versionNonce": 2018378018,
			"isDeleted": false,
			"id": "I7P2QUOrxmiZnPXhGDaJS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -129.10267502271995,
			"y": -1450.5255556899397,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 181.37237132877112,
			"height": 0.9068618566439,
			"seed": 658748703,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.8137237132876862,
					0
				],
				[
					3.627447426575486,
					-0.9068618566439
				],
				[
					4.534309283219272,
					-0.9068618566439
				],
				[
					6.348032996506959,
					-0.9068618566439
				],
				[
					8.161756709794759,
					-0.9068618566439
				],
				[
					9.975480423082445,
					-0.9068618566439
				],
				[
					11.789204136370131,
					-0.9068618566439
				],
				[
					14.509789706301717,
					-0.9068618566439
				],
				[
					16.323513419589403,
					-0.9068618566439
				],
				[
					18.13723713287709,
					-0.9068618566439
				],
				[
					20.857822702808676,
					-0.9068618566439
				],
				[
					22.671546416096362,
					-0.9068618566439
				],
				[
					26.298993842671848,
					-0.9068618566439
				],
				[
					29.019579412603434,
					-0.9068618566439
				],
				[
					30.83330312589112,
					-0.9068618566439
				],
				[
					33.55388869582271,
					-0.9068618566439
				],
				[
					37.18133612239808,
					-0.9068618566439
				],
				[
					44.43623097554894,
					-0.9068618566439
				],
				[
					46.249954688836624,
					-0.9068618566439
				],
				[
					56.22543511191907,
					-0.9068618566439
				],
				[
					62.57346810842603,
					-0.9068618566439
				],
				[
					69.82836296157689,
					-0.9068618566439
				],
				[
					76.17639595808384,
					-0.9068618566439
				],
				[
					83.4312908112347,
					-0.9068618566439
				],
				[
					89.77932380774166,
					-0.9068618566439
				],
				[
					96.12735680424873,
					-0.9068618566439
				],
				[
					103.38225165739959,
					-0.9068618566439
				],
				[
					109.73028465390655,
					-0.9068618566439
				],
				[
					116.98517950705741,
					0
				],
				[
					122.42635064692047,
					0
				],
				[
					126.96065993013974,
					0
				],
				[
					131.494969213359,
					0
				],
				[
					136.0292784965784,
					0
				],
				[
					139.65672592315377,
					0
				],
				[
					142.37731149308536,
					0
				],
				[
					145.09789706301694,
					0
				],
				[
					148.72534448959232,
					0
				],
				[
					151.4459300595239,
					0
				],
				[
					153.2596537728116,
					0
				],
				[
					155.07337748609928,
					0
				],
				[
					156.88710119938708,
					0
				],
				[
					157.79396305603086,
					0
				],
				[
					159.60768676931855,
					0
				],
				[
					160.51454862596245,
					0
				],
				[
					162.32827233925013,
					0
				],
				[
					163.23513419589403,
					0
				],
				[
					164.14199605253782,
					0
				],
				[
					165.04885790918172,
					0
				],
				[
					165.95571976582562,
					0
				],
				[
					166.8625816224694,
					0
				],
				[
					168.6763053357571,
					0
				],
				[
					169.583167192401,
					0
				],
				[
					170.4900290490449,
					0
				],
				[
					172.30375276233258,
					0
				],
				[
					173.21061461897648,
					0
				],
				[
					174.11747647562026,
					0
				],
				[
					175.02433833226416,
					0
				],
				[
					175.93120018890795,
					0
				],
				[
					176.83806204555185,
					0
				],
				[
					177.74492390219575,
					0
				],
				[
					178.65178575883954,
					0
				],
				[
					179.55864761548344,
					-0.9068618566439
				],
				[
					180.46550947212722,
					-0.9068618566439
				],
				[
					181.37237132877112,
					-0.9068618566439
				],
				[
					181.37237132877112,
					-0.9068618566439
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 375,
			"versionNonce": 2087164414,
			"isDeleted": false,
			"id": "igGNrQmfQi0npvCPXaF9B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -36.6027656450467,
			"y": -1454.153003116515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 182.74431589471237,
			"height": 18.13723713287709,
			"seed": 283294257,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.9068618566439
				],
				[
					0,
					-1.8137237132878
				],
				[
					1.1211307723602528,
					-2.7205855699314725
				],
				[
					2.2422615447205057,
					-3.6274474265753724
				],
				[
					3.3633923170806184,
					-4.534309283219272
				],
				[
					3.3633923170806184,
					-5.441171139863172
				],
				[
					4.484523089440871,
					-6.348032996507072
				],
				[
					6.726784634161237,
					-7.254894853150745
				],
				[
					8.969046178881602,
					-9.068618566438545
				],
				[
					10.090176951241855,
					-9.975480423082445
				],
				[
					12.33243849596222,
					-10.882342279726345
				],
				[
					15.695830813042837,
					-11.789204136370017
				],
				[
					20.180353902483567,
					-12.696065993013917
				],
				[
					22.422615447203935,
					-14.509789706301717
				],
				[
					26.907138536644805,
					-14.509789706301717
				],
				[
					30.270530853725422,
					-15.416651562945617
				],
				[
					34.75505394316615,
					-15.416651562945617
				],
				[
					40.360707804967134,
					-16.323513419589517
				],
				[
					45.96636166676812,
					-16.323513419589517
				],
				[
					52.69314630092936,
					-16.323513419589517
				],
				[
					60.54106170745071,
					-18.13723713287709
				],
				[
					66.14671556925168,
					-18.13723713287709
				],
				[
					72.87350020341293,
					-18.13723713287709
				],
				[
					79.60028483757416,
					-18.13723713287709
				],
				[
					86.32706947173526,
					-18.13723713287709
				],
				[
					94.17498487825661,
					-18.13723713287709
				],
				[
					100.90176951241784,
					-18.13723713287709
				],
				[
					106.50742337421883,
					-18.13723713287709
				],
				[
					109.87081569129944,
					-18.13723713287709
				],
				[
					115.47646955310043,
					-18.13723713287709
				],
				[
					119.96099264254116,
					-18.13723713287709
				],
				[
					124.44551573198203,
					-18.13723713287709
				],
				[
					126.68777727670239,
					-18.13723713287709
				],
				[
					128.93003882142276,
					-18.13723713287709
				],
				[
					131.17230036614328,
					-18.13723713287709
				],
				[
					132.29343113850337,
					-18.13723713287709
				],
				[
					136.77795422794424,
					-18.13723713287709
				],
				[
					139.0202157726646,
					-18.13723713287709
				],
				[
					141.262477317385,
					-18.13723713287709
				],
				[
					143.50473886210534,
					-18.13723713287709
				],
				[
					146.86813117918595,
					-18.13723713287709
				],
				[
					149.11039272390633,
					-18.13723713287709
				],
				[
					152.47378504098694,
					-18.13723713287709
				],
				[
					154.71604658570732,
					-18.13723713287709
				],
				[
					156.9583081304278,
					-17.23037527623319
				],
				[
					159.2005696751482,
					-17.23037527623319
				],
				[
					161.44283121986854,
					-17.23037527623319
				],
				[
					162.5639619922288,
					-17.23037527623319
				],
				[
					164.80622353694918,
					-17.23037527623319
				],
				[
					167.04848508166953,
					-17.23037527623319
				],
				[
					169.2907466263899,
					-17.23037527623319
				],
				[
					171.5330081711104,
					-17.23037527623319
				],
				[
					172.6541389434705,
					-17.23037527623319
				],
				[
					173.77526971583077,
					-17.23037527623319
				],
				[
					174.8964004881909,
					-17.23037527623319
				],
				[
					176.01753126055112,
					-17.23037527623319
				],
				[
					177.13866203291138,
					-17.23037527623319
				],
				[
					178.2597928052715,
					-17.23037527623319
				],
				[
					179.38092357763176,
					-17.23037527623319
				],
				[
					180.50205434999185,
					-17.23037527623319
				],
				[
					181.6231851223521,
					-17.23037527623319
				],
				[
					182.74431589471237,
					-17.23037527623319
				],
				[
					182.74431589471237,
					-17.23037527623319
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 395,
			"versionNonce": 318082274,
			"isDeleted": false,
			"id": "Aichd5-BMjJ2faZXEG2NC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 132.80708299384054,
			"y": -1481.5321773693445,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.323513419589403,
			"height": 17.23037527623319,
			"seed": 194581361,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.9068618566436726
				],
				[
					0.9068618566437863,
					0.9068618566436726
				],
				[
					0.9068618566437863,
					1.8137237132875725
				],
				[
					1.8137237132876862,
					1.8137237132875725
				],
				[
					2.7205855699314725,
					2.7205855699314725
				],
				[
					3.6274474265753724,
					3.6274474265753724
				],
				[
					4.534309283219272,
					3.6274474265753724
				],
				[
					5.441171139863059,
					4.534309283219272
				],
				[
					6.348032996506959,
					4.534309283219272
				],
				[
					7.254894853150745,
					4.534309283219272
				],
				[
					8.161756709794645,
					5.441171139863172
				],
				[
					9.068618566438545,
					5.441171139863172
				],
				[
					9.975480423082331,
					5.441171139863172
				],
				[
					10.882342279726231,
					6.348032996506845
				],
				[
					11.789204136370017,
					7.254894853150745
				],
				[
					12.696065993013917,
					7.254894853150745
				],
				[
					13.602927849657817,
					7.254894853150745
				],
				[
					14.509789706301603,
					8.161756709794645
				],
				[
					15.416651562945503,
					9.068618566438545
				],
				[
					16.323513419589403,
					9.068618566438545
				],
				[
					16.323513419589403,
					9.975480423082217
				],
				[
					16.323513419589403,
					10.882342279726117
				],
				[
					16.323513419589403,
					11.789204136370017
				],
				[
					15.416651562945503,
					12.696065993013917
				],
				[
					14.509789706301603,
					12.696065993013917
				],
				[
					14.509789706301603,
					13.602927849657817
				],
				[
					13.602927849657817,
					13.602927849657817
				],
				[
					12.696065993013917,
					13.602927849657817
				],
				[
					11.789204136370017,
					13.602927849657817
				],
				[
					11.789204136370017,
					14.509789706301717
				],
				[
					10.882342279726231,
					14.509789706301717
				],
				[
					9.975480423082331,
					15.41665156294539
				],
				[
					9.068618566438545,
					15.41665156294539
				],
				[
					8.161756709794645,
					15.41665156294539
				],
				[
					8.161756709794645,
					16.32351341958929
				],
				[
					7.254894853150745,
					16.32351341958929
				],
				[
					6.348032996506959,
					16.32351341958929
				],
				[
					5.441171139863059,
					16.32351341958929
				],
				[
					4.534309283219272,
					16.32351341958929
				],
				[
					3.6274474265753724,
					16.32351341958929
				],
				[
					2.7205855699314725,
					16.32351341958929
				],
				[
					2.7205855699314725,
					17.23037527623319
				],
				[
					1.8137237132876862,
					17.23037527623319
				],
				[
					1.8137237132876862,
					17.23037527623319
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 547,
			"versionNonce": 1788848702,
			"isDeleted": false,
			"id": "g5nsJJuq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 153.20189807760084,
			"y": -1527.7855067952487,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 52.596466064453125,
			"height": 12.597804181569025,
			"seed": 1486755007,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 10.07824334525522,
			"fontFamily": 1,
			"text": "Stack view",
			"rawText": "Stack view",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Stack view",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 986,
			"versionNonce": 1345691810,
			"isDeleted": false,
			"id": "eI215DUz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -306.7272684347093,
			"y": -1242.0958707929192,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 126.6934814453125,
			"height": 11.691233713859251,
			"seed": 1979720017,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 9.3529869710874,
			"fontFamily": 1,
			"text": "LayerNorm(x + Sublayer1(x))",
			"rawText": "LayerNorm(x + Sublayer1(x))",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "LayerNorm(x + Sublayer1(x))",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "line",
			"version": 318,
			"versionNonce": 803975806,
			"isDeleted": false,
			"id": "07nlurF2AsHJI81jxjwcA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 192.18071793106083,
			"y": -1466.5074926477796,
			"strokeColor": "#6741d9",
			"backgroundColor": "#6741d9",
			"width": 0.4327244555437346,
			"height": 93.46848239744918,
			"seed": 870789599,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.4327244555437346,
					93.46848239744918
				]
			]
		},
		{
			"type": "line",
			"version": 345,
			"versionNonce": 1539128418,
			"isDeleted": false,
			"id": "QP_WdstzTMdx_Nv5VDAiK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 188.5227650762265,
			"y": -1466.8918823383558,
			"strokeColor": "#6741d9",
			"backgroundColor": "#d0bfff",
			"width": 7.2759867552925925,
			"height": 0.1966482906834699,
			"seed": 236809649,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.2759867552925925,
					0.1966482906834699
				]
			]
		},
		{
			"type": "line",
			"version": 360,
			"versionNonce": 923579070,
			"isDeleted": false,
			"id": "WMWhnruQnDaopyi3QB50q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 188.81773751225188,
			"y": -1372.7956752462608,
			"strokeColor": "#6741d9",
			"backgroundColor": "#d0bfff",
			"width": 7.2759867552925925,
			"height": 0.1966482906834699,
			"seed": 2085984081,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.2759867552925925,
					0.1966482906834699
				]
			]
		},
		{
			"type": "text",
			"version": 259,
			"versionNonce": 324755490,
			"isDeleted": false,
			"id": "SqoSEYHV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 195.98824530399932,
			"y": -1432.0851348873614,
			"strokeColor": "#6741d9",
			"backgroundColor": "#d0bfff",
			"width": 10.240020751953125,
			"height": 20,
			"seed": 1203533393,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "line",
			"version": 350,
			"versionNonce": 1789111038,
			"isDeleted": false,
			"id": "LbHuzFYya9VRUPB7gihWJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 212.32584666677906,
			"y": -1362.108735467568,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 0.4327244555437346,
			"height": 93.46848239744918,
			"seed": 1048321695,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.4327244555437346,
					93.46848239744918
				]
			]
		},
		{
			"type": "line",
			"version": 377,
			"versionNonce": 1124010978,
			"isDeleted": false,
			"id": "YgslqldIffy052TK0268G",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 208.66789381194474,
			"y": -1362.4931251581445,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 7.2759867552925925,
			"height": 0.1966482906834699,
			"seed": 1474097855,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.2759867552925925,
					0.1966482906834699
				]
			]
		},
		{
			"type": "line",
			"version": 392,
			"versionNonce": 959552318,
			"isDeleted": false,
			"id": "Wef_bvzcjqJaq3rzHDZDp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 208.9628662479701,
			"y": -1268.3969180660495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 7.2759867552925925,
			"height": 0.1966482906834699,
			"seed": 307118815,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.2759867552925925,
					0.1966482906834699
				]
			]
		},
		{
			"type": "text",
			"version": 291,
			"versionNonce": 1622622114,
			"isDeleted": false,
			"id": "EExGXFwQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 216.13337403971752,
			"y": -1327.68637770715,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 10.240020751953125,
			"height": 20,
			"seed": 1851821823,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 477,
			"versionNonce": 420971390,
			"isDeleted": false,
			"id": "nUudDTYydqFtDN95qb_Kb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 300.7589644788792,
			"y": -1262.6601861101913,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 1.6645177040211934,
			"height": 239.69054937904866,
			"seed": 362700095,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NsLJeFJ2y2U0HmC2vylF9",
				"focus": 1.122722473996658,
				"gap": 10.369844782779978
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-1.6645177040211934,
					-239.69054937904866
				]
			]
		},
		{
			"type": "text",
			"version": 507,
			"versionNonce": 1219689314,
			"isDeleted": false,
			"id": "QwRVfrB0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.705869387611413,
			"x": 264.1922533758111,
			"y": -1404.2255044015044,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 102.84822082519531,
			"height": 20,
			"seed": 2109399455,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Deep learning",
			"rawText": "Deep learning",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Deep learning",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 854,
			"versionNonce": 211182526,
			"isDeleted": false,
			"id": "0DbhOsjPiIUB8ehGsnLfn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 47.75954760372974,
			"y": -1085.9565785161863,
			"strokeColor": "#e03131",
			"backgroundColor": "#6741d9",
			"width": 23.02548441697664,
			"height": 0.42886628148198724,
			"seed": 1298275729,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "I5U7WcjR",
				"focus": -0.2543076726872218,
				"gap": 4.71159953658298
			},
			"endBinding": {
				"elementId": "MvsSRO28",
				"focus": -0.025644645492259522,
				"gap": 10.180527398978114
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "bar",
			"points": [
				[
					0,
					0
				],
				[
					23.02548441697664,
					0.42886628148198724
				]
			]
		},
		{
			"type": "text",
			"version": 2030,
			"versionNonce": 2034319138,
			"isDeleted": false,
			"id": "MvsSRO28",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 80.9655594196845,
			"y": -1104.911972492663,
			"strokeColor": "#e03131",
			"backgroundColor": "#ced4da",
			"width": 86.29661560058594,
			"height": 39.69589006845144,
			"seed": 958336177,
			"groupIds": [
				"jqzjnzktZGxXk_Bwjx6WI"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "0DbhOsjPiIUB8ehGsnLfn",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 10.585570684920384,
			"fontFamily": 1,
			"text": "Seems to be the\noutput delayed \nin time",
			"rawText": "Seems to be the\noutput delayed \nin time",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Seems to be the\noutput delayed \nin time",
			"lineHeight": 1.25,
			"baseline": 35
		},
		{
			"type": "text",
			"version": 1127,
			"versionNonce": 634338302,
			"isDeleted": false,
			"id": "sPtHbw3K",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -329.6761491439241,
			"y": -902.428109576951,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 33.85089111328125,
			"height": 13.309058487100403,
			"seed": 1781256945,
			"groupIds": [
				"85Q4U__qNMZympznq0sxE"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "encode",
			"rawText": "encode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "encode",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 1166,
			"versionNonce": 1322322658,
			"isDeleted": false,
			"id": "uHUAWD8r",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -330.2180192611116,
			"y": -782.6788131707964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 34.93463134765625,
			"height": 13.309058487100403,
			"seed": 148014769,
			"groupIds": [
				"qSvHc9F9MvBgZmSu7GawF"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 10.647246789680322,
			"fontFamily": 1,
			"text": "decode",
			"rawText": "decode",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decode",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "rectangle",
			"version": 365,
			"versionNonce": 180554814,
			"isDeleted": false,
			"id": "TQZR8lCd-WnHc3zfD8hhC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 377.451686874166,
			"y": -1302.4249378977258,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#099268",
			"width": 38.74818042938881,
			"height": 19.374090214694206,
			"seed": 753337649,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 374,
			"versionNonce": 1072783010,
			"isDeleted": false,
			"id": "TY3xt_xRV4k-OKgQBtO6I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 426.01271819151674,
			"y": -1302.4249378977258,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#099268",
			"width": 38.74818042938881,
			"height": 19.374090214694206,
			"seed": 473117087,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "77jfQn3dUSHp1ESEYUMvD",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 381,
			"versionNonce": 2035471486,
			"isDeleted": false,
			"id": "OI-gKiWO4S1VfL0DLQLdD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 476.7137292882448,
			"y": -1302.4249378977258,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#099268",
			"width": 38.74818042938881,
			"height": 19.374090214694206,
			"seed": 584377215,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "Riuoy42pehwfY_c4h1tSV",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 436,
			"versionNonce": 424753762,
			"isDeleted": false,
			"id": "TGiMZKWg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 477.610604019825,
			"y": -1330.3292302923085,
			"strokeColor": "#6741d9",
			"backgroundColor": "#6741d9",
			"width": 13.650802612304688,
			"height": 6.687227061579369,
			"seed": 1679718033,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "ufL38iUXmAO7rG3wFaTHT",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 5.3497816492634955,
			"fontFamily": 1,
			"text": "Value",
			"rawText": "Value",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Value",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "rectangle",
			"version": 279,
			"versionNonce": 1262458046,
			"isDeleted": false,
			"id": "jc0x-6CvkircElloun5ND",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 402.7112287331265,
			"y": -1348.4522509363194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1143833681,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "fNJoLRSlwcAB62tuC6jzL",
					"type": "arrow"
				},
				{
					"id": "11Ggs3TmVAU2Mh1ntj-FD",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 968859170,
			"isDeleted": false,
			"id": "3QHZzcopK8F-vDoGLQ7Rg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 402.4729873749563,
			"y": -1368.54343185344,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1777821023,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "h0bH8eHK48OWatRh9EYlI",
					"type": "arrow"
				},
				{
					"id": "uprZ4BV5xWOfFfNFHd64u",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 431,
			"versionNonce": 2049592574,
			"isDeleted": false,
			"id": "LvtVBoeNSTww3xeBiK9SL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 403.2547607142428,
			"y": -1388.3045931050542,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 379501041,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "uprZ4BV5xWOfFfNFHd64u",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 578,
			"versionNonce": 1311476194,
			"isDeleted": false,
			"id": "hTX6tdc5My8_H4L8Vuz0g",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 402.16769675200993,
			"y": -1408.6763356025606,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 113.02664410264997,
			"height": 11.227328403710315,
			"seed": 2072530367,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "hTwbH8uA-W9zQyIn85b-L",
					"type": "arrow"
				},
				{
					"id": "ufL38iUXmAO7rG3wFaTHT",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 372,
			"versionNonce": 596901182,
			"isDeleted": false,
			"id": "o4Qz9htp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 418.27306071608365,
			"y": -1280.1444966350155,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#868e96",
			"width": 59.57257080078125,
			"height": 8.131209522998827,
			"seed": 1403398847,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.504967618399061,
			"fontFamily": 1,
			"text": "Positional Encoding",
			"rawText": "Positional Encoding",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Positional Encoding",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "arrow",
			"version": 300,
			"versionNonce": 228851106,
			"isDeleted": false,
			"id": "E9XgbVuuXn8CdwyU7fyAV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 396.365564606626,
			"y": -1302.6262691992881,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.450414673108298,
			"seed": 745215487,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "APV8QuMSb0UYqvvwT_hS-",
				"focus": -0.0071363910959996195,
				"gap": 7.0325010837945
			},
			"endBinding": {
				"elementId": "jX5a6Y2i",
				"focus": -1.4287961836607632,
				"gap": 15.91857690305801
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.450414673108298
				]
			]
		},
		{
			"type": "arrow",
			"version": 459,
			"versionNonce": 215852414,
			"isDeleted": false,
			"id": "77jfQn3dUSHp1ESEYUMvD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 445.44103224522985,
			"y": -1303.0842051337077,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.069568236672012,
			"seed": 588431903,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "q6SBWe8Ryj6CXzIEDndEw",
				"focus": 0.013155893557101917,
				"gap": 6.700370929989731
			},
			"endBinding": {
				"elementId": "t2Dokhbr",
				"focus": 2.4761423362429262,
				"gap": 14.606627886637284
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.069568236672012
				]
			]
		},
		{
			"type": "arrow",
			"version": 330,
			"versionNonce": 1968699746,
			"isDeleted": false,
			"id": "z2SAk1oPtZIO3sm7AtiGU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 495.6206381040044,
			"y": -1302.9604673992503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.1846092836965454,
			"height": 5.738032140795212,
			"seed": 1040752945,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "gYYbTI58n88g6v24B7150",
				"focus": 0.023595794923668027,
				"gap": 6.824108664447067
			},
			"endBinding": {
				"elementId": "gYYbTI58n88g6v24B7150",
				"focus": -0.01081050158067891,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.1846092836965454,
					-5.738032140795212
				]
			]
		},
		{
			"type": "arrow",
			"version": 569,
			"versionNonce": 659047870,
			"isDeleted": false,
			"id": "fNJoLRSlwcAB62tuC6jzL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 415.59887385223743,
			"y": -1328.118036215297,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 646778193,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jc0x-6CvkircElloun5ND",
				"focus": -0.3390915970930763,
				"gap": 7.2504135370730864
			},
			"endBinding": {
				"elementId": "xheY9rmw",
				"focus": -2.386419463779528,
				"gap": 15.43617712778348
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "arrow",
			"version": 428,
			"versionNonce": 76971298,
			"isDeleted": false,
			"id": "11Ggs3TmVAU2Mh1ntj-FD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 426.1314003438819,
			"y": -1328.4996494939794,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 71040447,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jc0x-6CvkircElloun5ND",
				"focus": 0.20104084741730094,
				"gap": 6.868800258390706
			},
			"endBinding": {
				"elementId": "p5jAErSQ",
				"focus": -0.298069817084965,
				"gap": 1.419303583532951
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "arrow",
			"version": 428,
			"versionNonce": 334814718,
			"isDeleted": false,
			"id": "h0bH8eHK48OWatRh9EYlI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 421.5793735086535,
			"y": -1348.8721237044815,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.12531280250829013,
			"height": 5.882519362872472,
			"seed": 488836799,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "3QHZzcopK8F-vDoGLQ7Rg",
				"focus": -0.005795519592397332,
				"gap": 6.587506965009311
			},
			"endBinding": {
				"elementId": "p5jAErSQ",
				"focus": 0.015256793025601907,
				"gap": 7.733169482204744
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.12531280250829013,
					-5.882519362872472
				]
			]
		},
		{
			"type": "arrow",
			"version": 496,
			"versionNonce": 2026801378,
			"isDeleted": false,
			"id": "uprZ4BV5xWOfFfNFHd64u",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 422.0099769341079,
			"y": -1369.1852998727206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 5.882519362872472,
			"seed": 737979967,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "LvtVBoeNSTww3xeBiK9SL",
				"focus": -0.03818891011640584,
				"gap": 6.0354920483840715
			},
			"endBinding": {
				"elementId": "3QHZzcopK8F-vDoGLQ7Rg",
				"focus": -0.0019022441889572387,
				"gap": 7.2762641972027495
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-5.882519362872472
				]
			]
		},
		{
			"type": "arrow",
			"version": 452,
			"versionNonce": 669281854,
			"isDeleted": false,
			"id": "hTwbH8uA-W9zQyIn85b-L",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 423.0784941144198,
			"y": -1389.1385204000842,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 7.135647387955487,
			"seed": 464025521,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hTX6tdc5My8_H4L8Vuz0g",
				"focus": -0.6299846371901688,
				"gap": 8.310486798765965
			},
			"endBinding": {
				"elementId": "6gk7JcSA",
				"focus": -0.0318453512470532,
				"gap": 10.044784718959932
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-7.135647387955487
				]
			]
		},
		{
			"type": "arrow",
			"version": 693,
			"versionNonce": 160373922,
			"isDeleted": false,
			"id": "ufL38iUXmAO7rG3wFaTHT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 495.53979196080127,
			"y": -1390.0157100176416,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 1442450975,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hTX6tdc5My8_H4L8Vuz0g",
				"focus": 0.6522138819585133,
				"gap": 7.433297181208559
			},
			"endBinding": {
				"elementId": "gYYbTI58n88g6v24B7150",
				"focus": -0.03941590198915192,
				"gap": 6.6016551318023176
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "line",
			"version": 276,
			"versionNonce": 1878521470,
			"isDeleted": false,
			"id": "OSYWBieCASg6o0GqNqyfb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 495.57091680563235,
			"y": -1389.9925589778793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.37593840752492724,
			"height": 67.66891335448872,
			"seed": 1778911441,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.37593840752492724,
					67.66891335448872
				]
			]
		},
		{
			"type": "text",
			"version": 649,
			"versionNonce": 612841570,
			"isDeleted": false,
			"id": "t2Dokhbr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 454.18343376983876,
			"y": -1331.9466921188964,
			"strokeColor": "#f08c00",
			"backgroundColor": "#6741d9",
			"width": 10.639389038085938,
			"height": 8.186290861879323,
			"seed": 270456945,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "77jfQn3dUSHp1ESEYUMvD",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.549032689503458,
			"fontFamily": 1,
			"text": "Key",
			"rawText": "Key",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Key",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 530,
			"versionNonce": 888174270,
			"isDeleted": false,
			"id": "jX5a6Y2i",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 377.8414895966067,
			"y": -1332.2025273828745,
			"strokeColor": "#1971c2",
			"backgroundColor": "#6741d9",
			"width": 15.634078979492188,
			"height": 7.207266607419975,
			"seed": 1730419761,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "E9XgbVuuXn8CdwyU7fyAV",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 5.76581328593598,
			"fontFamily": 1,
			"text": "Query",
			"rawText": "Query",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Query",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 248,
			"versionNonce": 696638498,
			"isDeleted": false,
			"id": "-lYHfH0z0fniPbW9WqYYk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 415.5970076574441,
			"y": -1328.0208723138458,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 19.16577876389772,
			"height": 0.12862938767716514,
			"seed": 1795863025,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.16577876389772,
					-0.12862938767716514
				]
			]
		},
		{
			"type": "line",
			"version": 249,
			"versionNonce": 2137976574,
			"isDeleted": false,
			"id": "XbXoqP9nCzOqTS9VUYRZy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 396.23828481203066,
			"y": -1328.149501701523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 5.356116096995493,
			"seed": 1597117969,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					5.356116096995493
				]
			]
		},
		{
			"type": "line",
			"version": 320,
			"versionNonce": 645531618,
			"isDeleted": false,
			"id": "khrsg5fpVDNG_uYKYOLZI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 426.11965401035354,
			"y": -1328.361739277159,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 18.411802691515447,
			"height": 0.14931853268717532,
			"seed": 1208938577,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.411802691515447,
					-0.14931853268717532
				]
			]
		},
		{
			"type": "line",
			"version": 259,
			"versionNonce": 468999998,
			"isDeleted": false,
			"id": "hcbGW85oKlPX7AI3rj2uH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 444.51417093059723,
			"y": -1328.548585244892,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.04373689328065211,
			"height": 5.817006806327527,
			"seed": 393847647,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.04373689328065211,
					5.817006806327527
				]
			]
		},
		{
			"type": "text",
			"version": 418,
			"versionNonce": 326286242,
			"isDeleted": false,
			"id": "xheY9rmw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 389.0505461288307,
			"y": -1319.3335709731261,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 27130111,
			"groupIds": [
				"dVdCZE8WVVkxVe9Vw0yml"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "fNJoLRSlwcAB62tuC6jzL",
					"type": "arrow"
				}
			],
			"updated": 1694624927703,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 419,
			"versionNonce": 518113150,
			"isDeleted": false,
			"id": "nqkJzfJy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 437.2991731823891,
			"y": -1320.251163908629,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 1546090911,
			"groupIds": [
				"7jI3VuswgOn5LC5J_490b"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 420,
			"versionNonce": 245299042,
			"isDeleted": false,
			"id": "qEoaS5s2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 488.6843775705502,
			"y": -1319.3335709731261,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 704188849,
			"groupIds": [
				"EYCLaoRkSwSI-3r5FbosD"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 461,
			"versionNonce": 1752704958,
			"isDeleted": false,
			"id": "p5jAErSQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 406.67132494688906,
			"y": -1347.0214735851494,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 29.967987060546875,
			"height": 10.84406273723957,
			"seed": 1420657727,
			"groupIds": [
				"6tlf3IaVc2S99bKS9PMQV"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "11Ggs3TmVAU2Mh1ntj-FD",
					"type": "arrow"
				},
				{
					"id": "h0bH8eHK48OWatRh9EYlI",
					"type": "arrow"
				}
			],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Matmul",
			"rawText": "Matmul",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Matmul",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 403,
			"versionNonce": 407747362,
			"isDeleted": false,
			"id": "8tCSGKiB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 410.46062751931004,
			"y": -1367.0949219481806,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 22.393753051757812,
			"height": 10.84406273723957,
			"seed": 1208063249,
			"groupIds": [
				"8-c-z2u3egO6sUrLCw_Ip"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Scale",
			"rawText": "Scale",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Scale",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 444,
			"versionNonce": 685277182,
			"isDeleted": false,
			"id": "6gk7JcSA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 404.8784616882223,
			"y": -1386.2293830690796,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 35.27427673339844,
			"height": 10.84406273723957,
			"seed": 1599789567,
			"groupIds": [
				"-gGz9WQX_0KsorNBCKnm8"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "hTwbH8uA-W9zQyIn85b-L",
					"type": "arrow"
				}
			],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Softmax",
			"rawText": "Softmax",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Softmax",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 478,
			"versionNonce": 1324222178,
			"isDeleted": false,
			"id": "LcEFuOl4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 440.36293002404204,
			"y": -1407.759951924874,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 29.967987060546875,
			"height": 10.84406273723957,
			"seed": 1788050527,
			"groupIds": [
				"-Lwql5etTpoHVbGbgAg3W"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "IAkDb2le_wgcpKD2qMfuQ",
					"type": "arrow"
				}
			],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Matmul",
			"rawText": "Matmul",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Matmul",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "arrow",
			"version": 187,
			"versionNonce": 1677971518,
			"isDeleted": false,
			"id": "IAkDb2le_wgcpKD2qMfuQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 455.5849634013947,
			"y": -1410.1523948128522,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 10.102463788479554,
			"seed": 357755263,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "LcEFuOl4",
				"focus": 0.015886275350979657,
				"gap": 2.392442887978291
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-10.102463788479554
				]
			]
		},
		{
			"type": "rectangle",
			"version": 315,
			"versionNonce": 722393762,
			"isDeleted": false,
			"id": "SGTLa5Cz6itXz-PeIIphu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 571.220665577642,
			"y": -1284.5974714357822,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 72.64564365641138,
			"height": 13.42313710638905,
			"seed": 1715330175,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 386,
			"versionNonce": 1977292926,
			"isDeleted": false,
			"id": "Riuoy42pehwfY_c4h1tSV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 540.7218914107922,
			"y": -1280.001837954591,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 14.071066378575438,
			"height": 5.4765256106097695,
			"seed": 1659890001,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "P1i2wvgR2ci5MI6NhwvW0",
				"focus": 0.20945666979451932,
				"gap": 14.775528383691807
			},
			"endBinding": {
				"elementId": "OI-gKiWO4S1VfL0DLQLdD",
				"focus": -0.2690888601206548,
				"gap": 11.18891531458317
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-14.071066378575438,
					-5.4765256106097695
				]
			]
		},
		{
			"type": "line",
			"version": 511,
			"versionNonce": 996095586,
			"isDeleted": false,
			"id": "1TiAGwiAprpUaEt32ecxh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 540.8542278960375,
			"y": -1279.9659778041043,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 30.41933558575147,
			"height": 4.065353680488897,
			"seed": 1687365119,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.009024729347061,
					4.065353680488897
				],
				[
					30.41933558575147,
					2.735325443442207
				]
			]
		},
		{
			"type": "text",
			"version": 537,
			"versionNonce": 371153086,
			"isDeleted": false,
			"id": "J5BLBW84",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 388.46357280364003,
			"y": -1296.907033658189,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 21.310394287109375,
			"height": 8.542840661928071,
			"seed": 565666239,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 6.834272529542457,
			"fontFamily": 1,
			"text": "vector",
			"rawText": "vector",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "vector",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 317,
			"versionNonce": 1622022690,
			"isDeleted": false,
			"id": "QIc4hZ3m",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 434.653011879364,
			"y": -1295.9692534723572,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 21.310394287109375,
			"height": 8.542840661928071,
			"seed": 2080269585,
			"groupIds": [
				"3BbanZhsvfBfRPSxWAY4O"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 6.834272529542457,
			"fontFamily": 1,
			"text": "vector",
			"rawText": "vector",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "vector",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 324,
			"versionNonce": 1550946558,
			"isDeleted": false,
			"id": "xYmrh8PP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 485.07421864937294,
			"y": -1296.8858262194028,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 21.310394287109375,
			"height": 8.542840661928071,
			"seed": 868124831,
			"groupIds": [
				"7aICt8LUzPK4roIEgo2ZU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 6.834272529542457,
			"fontFamily": 1,
			"text": "vector",
			"rawText": "vector",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "vector",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 394,
			"versionNonce": 166364642,
			"isDeleted": false,
			"id": "fPpEV8EQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 402.47991351514685,
			"y": -1087.3893619487542,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 40.352081298828125,
			"height": 20,
			"seed": 285614257,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "scale",
			"rawText": "scale",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "scale",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 341,
			"versionNonce": 1146274110,
			"isDeleted": false,
			"id": "HHuF3q9a",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 384.86916228354426,
			"y": -969.2971436182188,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 82.228515625,
			"height": 32.77428511981587,
			"seed": 1089845567,
			"groupIds": [
				"6DBMFGuKjCvQ8hea1OmgJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 13.10971404792635,
			"fontFamily": 1,
			"text": "dot-product \nattention",
			"rawText": "dot-product \nattention",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dot-product \nattention",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 411,
			"versionNonce": 1881373090,
			"isDeleted": false,
			"id": "nScKOifX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 372.3526751619623,
			"y": -840.0379113819444,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 107.26148986816406,
			"height": 16.399631630687757,
			"seed": 257665297,
			"groupIds": [
				"J99FqeAEO18leYZqcKRl0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 13.119705304550207,
			"fontFamily": 1,
			"text": "\"vanish-explosion\"",
			"rawText": "\"vanish-explosion\"",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\"vanish-explosion\"",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 1691,
			"versionNonce": 824437118,
			"isDeleted": false,
			"id": "fahedI6W",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1878.0058377076707,
			"y": -1522.4840795358925,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 327.56134033203125,
			"height": 100.86340901312242,
			"seed": 893485087,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 10.086340901312242,
			"fontFamily": 1,
			"text": "The modification of the queries (Q), keys (K), and values (V) is \nachieved by applying different linear projections to them h times. \nEach linear projection has its own set of learned weights, which \nare slightly different from each other. These projected versions \nof Q, K, and V are then concatenated in a dv dimension before \nbeing used in the attention mechanism. This allows for capturing \ndifferent aspects or perspectives of the input data during each \niteration or step.",
			"rawText": "The modification of the queries (Q), keys (K), and values (V) is \nachieved by applying different linear projections to them h times. \nEach linear projection has its own set of learned weights, which \nare slightly different from each other. These projected versions \nof Q, K, and V are then concatenated in a dv dimension before \nbeing used in the attention mechanism. This allows for capturing \ndifferent aspects or perspectives of the input data during each \niteration or step.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The modification of the queries (Q), keys (K), and values (V) is \nachieved by applying different linear projections to them h times. \nEach linear projection has its own set of learned weights, which \nare slightly different from each other. These projected versions \nof Q, K, and V are then concatenated in a dv dimension before \nbeing used in the attention mechanism. This allows for capturing \ndifferent aspects or perspectives of the input data during each \niteration or step.",
			"lineHeight": 1.25,
			"baseline": 96
		},
		{
			"type": "text",
			"version": 932,
			"versionNonce": 1384641890,
			"isDeleted": false,
			"id": "UEsrbenu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2517.625561668525,
			"y": -1364.134171672798,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 490.7530517578125,
			"height": 280,
			"seed": 2037906495,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "In the Transformer architecture, each query can attend \nto all keys simultaneously. So in a example sentence \n\"the cat jumped\", the query for word \"the\" (Q1) can be \nmultiplied by all three keys (\"the\", \"cat\", and \"jumped\") in \nparallel: Q1xK1, Q1xK2, and Q1xK3. This allows for computing \nattention scores between the query and multiple key-value \npairs at once. The attention(Q1, K1, V1), attention(Q2,K2,V2), \nand attention(Q3,K3,V3) operations represent how similar or \nrelevant each word is to the given query word (\"the\"). By \nperforming these computations in parallel across different\nwords of a sequence using matrix operations efficiently \nimplemented on hardware like GPUs or TPUs (Tensor \nProcessing Units), Transformers enable faster processing \ncompared to sequential models.",
			"rawText": "In the Transformer architecture, each query can attend \nto all keys simultaneously. So in a example sentence \n\"the cat jumped\", the query for word \"the\" (Q1) can be \nmultiplied by all three keys (\"the\", \"cat\", and \"jumped\") in \nparallel: Q1xK1, Q1xK2, and Q1xK3. This allows for computing \nattention scores between the query and multiple key-value \npairs at once. The attention(Q1, K1, V1), attention(Q2,K2,V2), \nand attention(Q3,K3,V3) operations represent how similar or \nrelevant each word is to the given query word (\"the\"). By \nperforming these computations in parallel across different\nwords of a sequence using matrix operations efficiently \nimplemented on hardware like GPUs or TPUs (Tensor \nProcessing Units), Transformers enable faster processing \ncompared to sequential models.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In the Transformer architecture, each query can attend \nto all keys simultaneously. So in a example sentence \n\"the cat jumped\", the query for word \"the\" (Q1) can be \nmultiplied by all three keys (\"the\", \"cat\", and \"jumped\") in \nparallel: Q1xK1, Q1xK2, and Q1xK3. This allows for computing \nattention scores between the query and multiple key-value \npairs at once. The attention(Q1, K1, V1), attention(Q2,K2,V2), \nand attention(Q3,K3,V3) operations represent how similar or \nrelevant each word is to the given query word (\"the\"). By \nperforming these computations in parallel across different\nwords of a sequence using matrix operations efficiently \nimplemented on hardware like GPUs or TPUs (Tensor \nProcessing Units), Transformers enable faster processing \ncompared to sequential models.",
			"lineHeight": 1.25,
			"baseline": 274
		},
		{
			"type": "text",
			"version": 775,
			"versionNonce": 1915095486,
			"isDeleted": false,
			"id": "edaK2X5K",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2526.817296053721,
			"y": -986.0326282780948,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 454.76666259765625,
			"height": 129.06392313053377,
			"seed": 579692575,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 17.208523084071167,
			"fontFamily": 1,
			"text": "An auto-regressive model is a type of model that \npredicts the next element in a sequence based \non previous elements. In the context of language \ngeneration or machine translation, an autoregressive \nmodel generates one token at a time by conditioning \nits prediction on previously generated tokens.",
			"rawText": "An auto-regressive model is a type of model that \npredicts the next element in a sequence based \non previous elements. In the context of language \ngeneration or machine translation, an autoregressive \nmodel generates one token at a time by conditioning \nits prediction on previously generated tokens.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "An auto-regressive model is a type of model that \npredicts the next element in a sequence based \non previous elements. In the context of language \ngeneration or machine translation, an autoregressive \nmodel generates one token at a time by conditioning \nits prediction on previously generated tokens.",
			"lineHeight": 1.25,
			"baseline": 123
		},
		{
			"type": "text",
			"version": 937,
			"versionNonce": 845609250,
			"isDeleted": false,
			"id": "MnYpU6Qn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2531.0926851836225,
			"y": -835.8089634476863,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 462.6729736328125,
			"height": 172.0852308407117,
			"seed": 628354385,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 17.208523084071167,
			"fontFamily": 1,
			"text": "In the case of Transformers, which are used for \nsequence transduction tasks like machine translation, \nthey can be trained in an autoregressive manner. \nDuring training, the target sequences are fed to the \ndecoder one token at a time from left to right. \nAt each step, all previously generated tokens are \nprovided as input along with their corresponding \npositional encodings.",
			"rawText": "In the case of Transformers, which are used for \nsequence transduction tasks like machine translation, \nthey can be trained in an autoregressive manner. \nDuring training, the target sequences are fed to the \ndecoder one token at a time from left to right. \nAt each step, all previously generated tokens are \nprovided as input along with their corresponding \npositional encodings.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In the case of Transformers, which are used for \nsequence transduction tasks like machine translation, \nthey can be trained in an autoregressive manner. \nDuring training, the target sequences are fed to the \ndecoder one token at a time from left to right. \nAt each step, all previously generated tokens are \nprovided as input along with their corresponding \npositional encodings.",
			"lineHeight": 1.25,
			"baseline": 166
		},
		{
			"type": "text",
			"version": 944,
			"versionNonce": 1182409214,
			"isDeleted": false,
			"id": "O01xM74D",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2525.95076150508,
			"y": -646.0195570989822,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 464.494873046875,
			"height": 150.57457698562274,
			"seed": 235473983,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 17.208523084071167,
			"fontFamily": 1,
			"text": "During inference or generation phase (when no ground \ntruth targets are available), autoregressive \ndecoding is performed by iteratively predicting and \ngenerating one token at each step using beam search \nor other decoding strategies. The predicted token \nbecomes part of the input for subsequent predictions \nuntil an end-of-sequence marker is reached.",
			"rawText": "During inference or generation phase (when no ground \ntruth targets are available), autoregressive \ndecoding is performed by iteratively predicting and \ngenerating one token at each step using beam search \nor other decoding strategies. The predicted token \nbecomes part of the input for subsequent predictions \nuntil an end-of-sequence marker is reached.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "During inference or generation phase (when no ground \ntruth targets are available), autoregressive \ndecoding is performed by iteratively predicting and \ngenerating one token at each step using beam search \nor other decoding strategies. The predicted token \nbecomes part of the input for subsequent predictions \nuntil an end-of-sequence marker is reached.",
			"lineHeight": 1.25,
			"baseline": 144
		},
		{
			"type": "text",
			"version": 739,
			"versionNonce": 254772450,
			"isDeleted": false,
			"id": "NCWfG4MU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3091.6164096655743,
			"y": -1352.011642629276,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 592.0330810546875,
			"height": 40,
			"seed": 356812159,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Auto-regressive models and recurrence are different in terms of how they \nhandle dependencies and generate sequences.",
			"rawText": "Auto-regressive models and recurrence are different in terms of how they \nhandle dependencies and generate sequences.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Auto-regressive models and recurrence are different in terms of how they \nhandle dependencies and generate sequences.",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 774,
			"versionNonce": 1629565502,
			"isDeleted": false,
			"id": "ux3MnCOZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3079.709898004382,
			"y": -1292.011642629276,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 576.1451416015625,
			"height": 140,
			"seed": 860870129,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Recurrence, as seen in traditional recurrent neural networks (RNNs), \nprocesses a sequence one element at a time by maintaining an internal \nhidden state that is updated based on the previous hidden state and \nthe current input. This allows RNNs to capture sequential dependencies \nby incorporating information from past elements into the prediction of \neach subsequent element. However, this sequential processing can be \ncomputationally expensive and limits parallelization.",
			"rawText": "Recurrence, as seen in traditional recurrent neural networks (RNNs), \nprocesses a sequence one element at a time by maintaining an internal \nhidden state that is updated based on the previous hidden state and \nthe current input. This allows RNNs to capture sequential dependencies \nby incorporating information from past elements into the prediction of \neach subsequent element. However, this sequential processing can be \ncomputationally expensive and limits parallelization.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Recurrence, as seen in traditional recurrent neural networks (RNNs), \nprocesses a sequence one element at a time by maintaining an internal \nhidden state that is updated based on the previous hidden state and \nthe current input. This allows RNNs to capture sequential dependencies \nby incorporating information from past elements into the prediction of \neach subsequent element. However, this sequential processing can be \ncomputationally expensive and limits parallelization.",
			"lineHeight": 1.25,
			"baseline": 134
		},
		{
			"type": "text",
			"version": 891,
			"versionNonce": 577804450,
			"isDeleted": false,
			"id": "Gk7Wv4NJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3078.3203586401833,
			"y": -1140.1928703355532,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 618.6251831054688,
			"height": 120,
			"seed": 1253408159,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "On the other hand, auto-regressive models like Transformers do not \nrely on recurrence for handling dependencies between elements in a sequence. \nInstead, they use self-attention mechanisms to directly model relationships \nbetween all positions within a sequence simultaneously. Each position attends \nto all other positions using attention weights that determine their relevance \nor importance for generating predictions at that position.",
			"rawText": "On the other hand, auto-regressive models like Transformers do not \nrely on recurrence for handling dependencies between elements in a sequence. \nInstead, they use self-attention mechanisms to directly model relationships \nbetween all positions within a sequence simultaneously. Each position attends \nto all other positions using attention weights that determine their relevance \nor importance for generating predictions at that position.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "On the other hand, auto-regressive models like Transformers do not \nrely on recurrence for handling dependencies between elements in a sequence. \nInstead, they use self-attention mechanisms to directly model relationships \nbetween all positions within a sequence simultaneously. Each position attends \nto all other positions using attention weights that determine their relevance \nor importance for generating predictions at that position.",
			"lineHeight": 1.25,
			"baseline": 114
		},
		{
			"type": "text",
			"version": 923,
			"versionNonce": 1828469374,
			"isDeleted": false,
			"id": "qNqr309G",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3080.784361049454,
			"y": -1007.8753784649407,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 648.8172607421875,
			"height": 100,
			"seed": 60944337,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "This parallelized approach enables Transformers to process multiple elements \nof a sequence concurrently without being constrained by strict order or temporal \ndependency like RNNs with recurrence. Auto-regressive decoding still considers\npreviously generated tokens during inference but does so through explicit \nattention mechanisms rather than relying on recurrent connections.",
			"rawText": "This parallelized approach enables Transformers to process multiple elements \nof a sequence concurrently without being constrained by strict order or temporal \ndependency like RNNs with recurrence. Auto-regressive decoding still considers\npreviously generated tokens during inference but does so through explicit \nattention mechanisms rather than relying on recurrent connections.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "This parallelized approach enables Transformers to process multiple elements \nof a sequence concurrently without being constrained by strict order or temporal \ndependency like RNNs with recurrence. Auto-regressive decoding still considers\npreviously generated tokens during inference but does so through explicit \nattention mechanisms rather than relying on recurrent connections.",
			"lineHeight": 1.25,
			"baseline": 94
		},
		{
			"type": "text",
			"version": 1013,
			"versionNonce": 467219554,
			"isDeleted": false,
			"id": "HcXDrmjX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3082.160015047988,
			"y": -891.2772715708261,
			"strokeColor": "#1971c2",
			"backgroundColor": "#e9ecef",
			"width": 644.30029296875,
			"height": 96.18259973312388,
			"seed": 1938977215,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 15.389215957299818,
			"fontFamily": 1,
			"text": "In summary, while both auto-regressive models (like Transformers) and recurrent \nmodels capture dependencies within sequences, they differ in how these dependencies \nare modeled: recurrence relies on sequentially updating hidden states over time \nwhereas auto-regression uses self-attention mechanisms for capturing relationships \nacross all positions simultaneously.",
			"rawText": "In summary, while both auto-regressive models (like Transformers) and recurrent \nmodels capture dependencies within sequences, they differ in how these dependencies \nare modeled: recurrence relies on sequentially updating hidden states over time \nwhereas auto-regression uses self-attention mechanisms for capturing relationships \nacross all positions simultaneously.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In summary, while both auto-regressive models (like Transformers) and recurrent \nmodels capture dependencies within sequences, they differ in how these dependencies \nare modeled: recurrence relies on sequentially updating hidden states over time \nwhereas auto-regression uses self-attention mechanisms for capturing relationships \nacross all positions simultaneously.",
			"lineHeight": 1.25,
			"baseline": 90
		},
		{
			"type": "text",
			"version": 985,
			"versionNonce": 281819838,
			"isDeleted": false,
			"id": "HiOQ4Ji0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2511.384526059608,
			"y": -1425.7284321394463,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 196.67279052734375,
			"height": 35,
			"seed": 994992959,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Parallelization",
			"rawText": "Parallelization",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Parallelization",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "rectangle",
			"version": 787,
			"versionNonce": 1563973666,
			"isDeleted": false,
			"id": "ge8IkgiKzplSn7x_GAYcj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2498.0866995185993,
			"y": -1385.5359943579556,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 507.7488784567431,
			"height": 329.78787448783555,
			"seed": 887247007,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 881,
			"versionNonce": 1932669694,
			"isDeleted": false,
			"id": "ACZByJr4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2511.384526059608,
			"y": -1038.2960779378234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 273.2811279296875,
			"height": 35,
			"seed": 2042932671,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Autoregressive (AR)",
			"rawText": "Autoregressive (AR)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Autoregressive (AR)",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "rectangle",
			"version": 918,
			"versionNonce": 914162658,
			"isDeleted": false,
			"id": "MX9fDKn_36RJUprYpgACn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2500.73769923985,
			"y": -1001.8199254918738,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 503.26910527475854,
			"height": 513.7176441505671,
			"seed": 722190193,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1116,
			"versionNonce": 1051665214,
			"isDeleted": false,
			"id": "tJJyrr8us2CSVHOnbPT2d",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3045.4002502527114,
			"y": -1384.3694037443918,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 684.4653998804135,
			"height": 610.3480811560411,
			"seed": 567115537,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 868,
			"versionNonce": 565589922,
			"isDeleted": false,
			"id": "ADdONWUY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3061.692929932419,
			"y": -1425.9860708494589,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 544.0423583984375,
			"height": 35,
			"seed": 707438289,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "AR Transformer X recurrent neural net",
			"rawText": "AR Transformer X recurrent neural net",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AR Transformer X recurrent neural net",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "text",
			"version": 314,
			"versionNonce": 631507838,
			"isDeleted": false,
			"id": "G2zi7bzr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 688.2910207606699,
			"y": -1123.6027440188786,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 109.85624694824219,
			"height": 20,
			"seed": 228976753,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "self-attention",
			"rawText": "self-attention",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "self-attention",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 563,
			"versionNonce": 2131948386,
			"isDeleted": false,
			"id": "jqdOhvUK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 376.11219910197525,
			"y": -746.2553443189194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.60589599609375,
			"height": 25.670477255245252,
			"seed": 747822737,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 10.268190902098102,
			"fontFamily": 1,
			"text": "different (multiple) \nlinear projections",
			"rawText": "different (multiple) \nlinear projections",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "different (multiple) \nlinear projections",
			"lineHeight": 1.25,
			"baseline": 21
		},
		{
			"type": "line",
			"version": 238,
			"versionNonce": 1716644798,
			"isDeleted": false,
			"id": "FV5rkR-pH3oq14htnFeCY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1727.9102298811677,
			"y": -1451.2838389305036,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 0.8590889098891239,
			"height": 237.10853912940706,
			"seed": 29408799,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.8590889098891239,
					237.10853912940706
				]
			]
		},
		{
			"type": "line",
			"version": 176,
			"versionNonce": 1357002530,
			"isDeleted": false,
			"id": "PK4kMh7bV3d5bxs9ZlzxP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1727.0511409712785,
			"y": -1333.5886582756893,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 138.31331449215418,
			"height": 108.2452026460337,
			"seed": 443172383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					138.31331449215418,
					-108.2452026460337
				]
			]
		},
		{
			"type": "rectangle",
			"version": 270,
			"versionNonce": 1322894334,
			"isDeleted": false,
			"id": "0m5qAylCr_4yJGTSFBkx-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1866.223544373322,
			"y": -1535.474552099641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 347.9310085051079,
			"height": 121.13153629437102,
			"seed": 1937103153,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 551,
			"versionNonce": 2006123234,
			"isDeleted": false,
			"id": "1NcIaTgt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2975.3056329603305,
			"y": -1538.8491368990879,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 111.42002868652344,
			"height": 45,
			"seed": 275214545,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Notes:",
			"rawText": "Notes:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Notes:",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "line",
			"version": 555,
			"versionNonce": 1094489150,
			"isDeleted": false,
			"id": "Ipao83D3WZR_689rDDCqz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3382.6619414081247,
			"y": -949.5388919283923,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 306.1555014034557,
			"height": 1.5269601067504937,
			"seed": 902348945,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927704,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					306.1555014034557,
					1.5269601067504937
				]
			]
		},
		{
			"type": "line",
			"version": 673,
			"versionNonce": 1840535202,
			"isDeleted": false,
			"id": "HHVC6-KZ4TYoo0L5UYofc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3081.850800378295,
			"y": -928.1614504338866,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 577.1909203516525,
			"height": 0.7634800533751331,
			"seed": 932677713,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					577.1909203516525,
					0.7634800533751331
				]
			]
		},
		{
			"type": "line",
			"version": 595,
			"versionNonce": 928734334,
			"isDeleted": false,
			"id": "N-92Xo7d96igQfZ1SwZqD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3082.61428043167,
			"y": -909.8379291528818,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 526.037756775514,
			"height": 2.290440160125627,
			"seed": 2041161393,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					526.037756775514,
					2.290440160125627
				]
			]
		},
		{
			"type": "line",
			"version": 486,
			"versionNonce": 66400866,
			"isDeleted": false,
			"id": "KX3VYI_cjtKQXASMRANdJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3500.2378696279056,
			"y": -835.0168839221121,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 106.12372741915306,
			"height": 0.7634800533752468,
			"seed": 123899807,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					106.12372741915306,
					0.7634800533752468
				]
			]
		},
		{
			"type": "line",
			"version": 575,
			"versionNonce": 1190599870,
			"isDeleted": false,
			"id": "LURoaqLc0V-wGjj0D9TX3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3314.7122166577315,
			"y": -814.4029224809817,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 192.39697345055083,
			"height": 1.5269601067502663,
			"seed": 1812307953,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					192.39697345055083,
					-1.5269601067502663
				]
			]
		},
		{
			"type": "text",
			"version": 351,
			"versionNonce": 488936994,
			"isDeleted": false,
			"id": "6xaelNNE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -17.64638080306861,
			"y": -1281.2743921265671,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 3.6203765869140625,
			"height": 16.718211553217436,
			"seed": 553557809,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 13.37456924257395,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 434,
			"versionNonce": 632345854,
			"isDeleted": false,
			"id": "00Br2w6k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1267.1907600844022,
			"y": -1152.6124889610553,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 3.6203765869140625,
			"height": 16.718211553217436,
			"seed": 516129599,
			"groupIds": [
				"1Zs1ROZ_untKsx_G4AqFN"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 13.37456924257395,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 436,
			"versionNonce": 1781629410,
			"isDeleted": false,
			"id": "dmyc0XwU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1264.2450355970975,
			"y": -1085.6900279116255,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 9.511825561523438,
			"height": 16.718211553217436,
			"seed": 645196977,
			"groupIds": [
				"OIN1_jIq2C80CfGopmT8u"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 13.37456924257395,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 436,
			"versionNonce": 755598654,
			"isDeleted": false,
			"id": "vIK2uR16",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1264.4521049940702,
			"y": -1026.022129225383,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 9.097686767578125,
			"height": 16.718211553217436,
			"seed": 42558833,
			"groupIds": [
				"fuAaa_HCdZZWFjTSEOoFt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 13.37456924257395,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 303,
			"versionNonce": 640349602,
			"isDeleted": false,
			"id": "FCvhiAZr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -25.1609389449889,
			"y": -1250.0690716447273,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 4.626251220703125,
			"height": 9.454529235606516,
			"seed": 1886891455,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 7.5636233884852135,
			"fontFamily": 1,
			"text": "K",
			"rawText": "K",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "K",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 240,
			"versionNonce": 1583492478,
			"isDeleted": false,
			"id": "1ufgsg6b",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2.838683427570679,
			"y": -1249.7286950489981,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 3.9017486572265625,
			"height": 9.454529235606516,
			"seed": 1636422641,
			"groupIds": [
				"FeEby3RjksLD1A1dzgjOR"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 7.5636233884852135,
			"fontFamily": 1,
			"text": "V",
			"rawText": "V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "V",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 401,
			"versionNonce": 1379922274,
			"isDeleted": false,
			"id": "41SeG2WM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 31.039589268617277,
			"y": -1253.041561239667,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 6.1577911376953125,
			"height": 10.933687887883487,
			"seed": 561495103,
			"groupIds": [
				"oq7u0sXt"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 8.74695031030679,
			"fontFamily": 1,
			"text": "Q",
			"rawText": "Q",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Q",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 430,
			"versionNonce": 1727778238,
			"isDeleted": false,
			"id": "ritd4zos",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -61.41063913579754,
			"y": -1201.1995311346875,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 5.907440185546875,
			"height": 10.396786350514448,
			"seed": 1160658175,
			"groupIds": [
				"uTWEoS63AtqQVSN9hTANv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 8.317429080411559,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 447,
			"versionNonce": 1908372770,
			"isDeleted": false,
			"id": "eoC4vtI7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -18.974618425780534,
			"y": -1202.3283570637418,
			"strokeColor": "#1971c2",
			"backgroundColor": "#b2f2bb",
			"width": 5.650238037109375,
			"height": 10.396786350514448,
			"seed": 1161215057,
			"groupIds": [
				"Lt00LDXWCkgJUh7gQ0JMe"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 8.317429080411559,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 395,
			"versionNonce": 603416062,
			"isDeleted": false,
			"id": "qK5Y3LsAWh-8G6VVy13k-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 1564.4097410078,
			"y": -804.1414053727116,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 163.10555053767825,
			"height": 0.4017378092061108,
			"seed": 123714367,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					163.10555053767825,
					0.4017378092061108
				]
			]
		},
		{
			"type": "line",
			"version": 191,
			"versionNonce": 1176010978,
			"isDeleted": false,
			"id": "iQb4nOTXc33Yig5m_9mB8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 1727.5204602674833,
			"y": -810.2452938043333,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 0.0025843610023912333,
			"height": 12.933431188125496,
			"seed": 2030219761,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.0025843610023912333,
					12.933431188125496
				]
			]
		},
		{
			"type": "text",
			"version": 365,
			"versionNonce": 643167806,
			"isDeleted": false,
			"id": "3eraPiSd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1734.3140433687272,
			"y": -825.5059062812301,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 109.74200439453125,
			"height": 42.91732527347119,
			"seed": 327101425,
			"groupIds": [
				"nQpKyyvB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 11.44462007292565,
			"fontFamily": 1,
			"text": "Usually is used to \nshrink the number\nof channels",
			"rawText": "Usually is used to \nshrink the number\nof channels",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Usually is used to \nshrink the number\nof channels",
			"lineHeight": 1.25,
			"baseline": 39
		},
		{
			"type": "rectangle",
			"version": 695,
			"versionNonce": 182064290,
			"isDeleted": false,
			"id": "LOD270a3MrSb9ux-3bUgv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1142.9418682230953,
			"y": -822.2530689043429,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 18,
			"height": 34,
			"seed": 1251420095,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "9gjEV7GB"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 331,
			"versionNonce": 922254974,
			"isDeleted": false,
			"id": "9gjEV7GB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1148.9296459330562,
			"y": -809.2418405381666,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 6.024444580078125,
			"height": 7.977543267647484,
			"seed": 1629861841,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.382034614117987,
			"fontFamily": 1,
			"text": "E1",
			"rawText": "E1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "LOD270a3MrSb9ux-3bUgv",
			"originalText": "E1",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "freedraw",
			"version": 663,
			"versionNonce": 833826914,
			"isDeleted": false,
			"id": "ENqrAPTuVSVXeDqPuQBwV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1130.0659102458824,
			"y": -806.943188799178,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 8.26280837474883,
			"height": 0.375582198852283,
			"seed": 953451327,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3755821988521435,
					0
				],
				[
					0.7511643977044266,
					0
				],
				[
					0.7511643977044266,
					0.375582198852283
				],
				[
					1.12674659655657,
					0.375582198852283
				],
				[
					1.5023287954088531,
					0.375582198852283
				],
				[
					2.2534931931132793,
					0.375582198852283
				],
				[
					2.6290753919655625,
					0.375582198852283
				],
				[
					3.0046575908177062,
					0.375582198852283
				],
				[
					4.131404187374415,
					0.375582198852283
				],
				[
					4.506986386226699,
					0.375582198852283
				],
				[
					5.258150783931125,
					0.375582198852283
				],
				[
					6.009315181635552,
					0.375582198852283
				],
				[
					6.384897380487835,
					0.375582198852283
				],
				[
					6.760479579339978,
					0.375582198852283
				],
				[
					7.1360617781922615,
					0.375582198852283
				],
				[
					7.511643977044405,
					0.375582198852283
				],
				[
					7.8872261758966875,
					0.375582198852283
				],
				[
					8.26280837474883,
					0.375582198852283
				],
				[
					8.26280837474883,
					0.375582198852283
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 666,
			"versionNonce": 1520434878,
			"isDeleted": false,
			"id": "1RuLSnfPwSJ3qiinDmFta",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1137.1063713684325,
			"y": -811.8257573842568,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 4.506986386226699,
			"height": 9.765137170157823,
			"seed": 1471363825,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.3755821988521435
				],
				[
					0.3755821988521435,
					0.3755821988521435
				],
				[
					0.3755821988521435,
					0.7511643977044266
				],
				[
					0.7511643977044266,
					0.7511643977044266
				],
				[
					1.1267465965567096,
					1.1267465965566397
				],
				[
					1.5023287954088531,
					1.5023287954088531
				],
				[
					1.877910994261136,
					1.877910994261136
				],
				[
					2.2534931931132793,
					2.2534931931132793
				],
				[
					2.2534931931132793,
					2.6290753919655625
				],
				[
					2.6290753919655625,
					3.004657590817776
				],
				[
					3.0046575908178457,
					3.380239789669989
				],
				[
					3.0046575908178457,
					3.7558219885222024
				],
				[
					3.380239789669989,
					3.7558219885222024
				],
				[
					3.380239789669989,
					4.131404187374415
				],
				[
					3.380239789669989,
					4.506986386226699
				],
				[
					3.755821988522272,
					4.506986386226699
				],
				[
					3.755821988522272,
					4.882568585078842
				],
				[
					3.755821988522272,
					5.258150783931125
				],
				[
					3.380239789669989,
					5.6337329827833384
				],
				[
					2.6290753919655625,
					6.009315181635552
				],
				[
					2.2534931931132793,
					6.3848973804877645
				],
				[
					1.877910994261136,
					6.760479579339978
				],
				[
					1.5023287954088531,
					7.511643977044405
				],
				[
					1.1267465965567096,
					7.511643977044405
				],
				[
					0.3755821988521435,
					8.2628083747489
				],
				[
					0,
					9.013972772453398
				],
				[
					-0.375582198852283,
					9.389554971305541
				],
				[
					-0.7511643977044266,
					9.389554971305541
				],
				[
					-0.7511643977044266,
					9.765137170157823
				],
				[
					-0.7511643977044266,
					9.765137170157823
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "rectangle",
			"version": 714,
			"versionNonce": 510841890,
			"isDeleted": false,
			"id": "tuvvCiaRQHgtSiyXLxGgC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1178.3994954880159,
			"y": -820.5629490095079,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 21,
			"height": 34,
			"seed": 1508576145,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "q5E5x7mx"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 360,
			"versionNonce": 1441625854,
			"isDeleted": false,
			"id": "q5E5x7mx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1183.886098271219,
			"y": -808.0884374617402,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 10.02679443359375,
			"height": 9.050976904464672,
			"seed": 381546015,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 7.240781523571737,
			"fontFamily": 1,
			"text": "E2",
			"rawText": "E2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "tuvvCiaRQHgtSiyXLxGgC",
			"originalText": "E2",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 590,
			"versionNonce": 1661468642,
			"isDeleted": false,
			"id": "shUdXLN7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1163.37946511496,
			"y": -796.8039721702386,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 13.06097412109375,
			"height": 5.849734177570321,
			"seed": 1621273649,
			"groupIds": [
				"6bxg0YT_G5tI_jJ1ogR2h"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 4.679787342056256,
			"fontFamily": 1,
			"text": "2048",
			"rawText": "2048",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2048",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "text",
			"version": 645,
			"versionNonce": 828499774,
			"isDeleted": false,
			"id": "ioO0lQ8z",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1146.9315467690062,
			"y": -798.4862565934665,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 9.10565185546875,
			"height": 7.125652724705642,
			"seed": 1705413553,
			"groupIds": [
				"yHT3Lxifr5TL-maGYuMoU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 5.700522179764514,
			"fontFamily": 1,
			"text": "512",
			"rawText": "512",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "512",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 793,
			"versionNonce": 2072097698,
			"isDeleted": false,
			"id": "q51amnHL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1199.86746825617,
			"y": -796.866905662544,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 13.06097412109375,
			"height": 5.849734177570321,
			"seed": 305641489,
			"groupIds": [
				"J5n3jh_M7F4id_MUKizkw"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 4.679787342056256,
			"fontFamily": 1,
			"text": "2048",
			"rawText": "2048",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2048",
			"lineHeight": 1.25,
			"baseline": 3
		},
		{
			"type": "rectangle",
			"version": 752,
			"versionNonce": 1029590910,
			"isDeleted": false,
			"id": "5hYFMvqg-BMM7IZqtuQxa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1214.0253763538713,
			"y": -821.861223155942,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 21,
			"height": 34,
			"seed": 1156611505,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "IIyqccuu"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 401,
			"versionNonce": 168750946,
			"isDeleted": false,
			"id": "IIyqccuu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1220.3981867176408,
			"y": -809.3867116081743,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 8.254379272460938,
			"height": 9.050976904464672,
			"seed": 844603281,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 7.240781523571737,
			"fontFamily": 1,
			"text": "En",
			"rawText": "En",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "5hYFMvqg-BMM7IZqtuQxa",
			"originalText": "En",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "freedraw",
			"version": 668,
			"versionNonce": 371437502,
			"isDeleted": false,
			"id": "85QphKPRx0VBsO7IrDrtV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1163.4660255867177,
			"y": -805.6601878814677,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 8.26280837474883,
			"height": 0.375582198852283,
			"seed": 1125640351,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3755821988521435,
					0
				],
				[
					0.7511643977044266,
					0
				],
				[
					0.7511643977044266,
					0.375582198852283
				],
				[
					1.12674659655657,
					0.375582198852283
				],
				[
					1.5023287954088531,
					0.375582198852283
				],
				[
					2.2534931931132793,
					0.375582198852283
				],
				[
					2.6290753919655625,
					0.375582198852283
				],
				[
					3.0046575908177062,
					0.375582198852283
				],
				[
					4.131404187374415,
					0.375582198852283
				],
				[
					4.506986386226699,
					0.375582198852283
				],
				[
					5.258150783931125,
					0.375582198852283
				],
				[
					6.009315181635552,
					0.375582198852283
				],
				[
					6.384897380487835,
					0.375582198852283
				],
				[
					6.760479579339978,
					0.375582198852283
				],
				[
					7.1360617781922615,
					0.375582198852283
				],
				[
					7.511643977044405,
					0.375582198852283
				],
				[
					7.8872261758966875,
					0.375582198852283
				],
				[
					8.26280837474883,
					0.375582198852283
				],
				[
					8.26280837474883,
					0.375582198852283
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 668,
			"versionNonce": 318681890,
			"isDeleted": false,
			"id": "mG4x-qYyST2geON_69ED3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1169.9738435589175,
			"y": -810.2764348913712,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 4.506986386226699,
			"height": 9.765137170157823,
			"seed": 711949503,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.3755821988521435
				],
				[
					0.3755821988521435,
					0.3755821988521435
				],
				[
					0.3755821988521435,
					0.7511643977044266
				],
				[
					0.7511643977044266,
					0.7511643977044266
				],
				[
					1.1267465965567096,
					1.1267465965566397
				],
				[
					1.5023287954088531,
					1.5023287954088531
				],
				[
					1.877910994261136,
					1.877910994261136
				],
				[
					2.2534931931132793,
					2.2534931931132793
				],
				[
					2.2534931931132793,
					2.6290753919655625
				],
				[
					2.6290753919655625,
					3.004657590817776
				],
				[
					3.0046575908178457,
					3.380239789669989
				],
				[
					3.0046575908178457,
					3.7558219885222024
				],
				[
					3.380239789669989,
					3.7558219885222024
				],
				[
					3.380239789669989,
					4.131404187374415
				],
				[
					3.380239789669989,
					4.506986386226699
				],
				[
					3.755821988522272,
					4.506986386226699
				],
				[
					3.755821988522272,
					4.882568585078842
				],
				[
					3.755821988522272,
					5.258150783931125
				],
				[
					3.380239789669989,
					5.6337329827833384
				],
				[
					2.6290753919655625,
					6.009315181635552
				],
				[
					2.2534931931132793,
					6.3848973804877645
				],
				[
					1.877910994261136,
					6.760479579339978
				],
				[
					1.5023287954088531,
					7.511643977044405
				],
				[
					1.1267465965567096,
					7.511643977044405
				],
				[
					0.3755821988521435,
					8.2628083747489
				],
				[
					0,
					9.013972772453398
				],
				[
					-0.375582198852283,
					9.389554971305541
				],
				[
					-0.7511643977044266,
					9.389554971305541
				],
				[
					-0.7511643977044266,
					9.765137170157823
				],
				[
					-0.7511643977044266,
					9.765137170157823
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 305,
			"versionNonce": 668141566,
			"isDeleted": false,
			"id": "lpfK7guh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1202.2632426999646,
			"y": -812.7064389518566,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 8.053024291992188,
			"height": 12.271277814916239,
			"seed": 1921906719,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 9.817022251932991,
			"fontFamily": 1,
			"text": "...",
			"rawText": "...",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "...",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "rectangle",
			"version": 318,
			"versionNonce": 952106722,
			"isDeleted": false,
			"id": "n_sRRynPsaH-uJVlIev9_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1260.7511632300113,
			"y": -635.9196075520288,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1824989343,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "-IKi7HMm7JoNCw7RcOH28",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 367,
			"versionNonce": 846026814,
			"isDeleted": false,
			"id": "B7rEL27XZTBENL3P_4QCG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1309.563806108592,
			"y": -635.7938017714143,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f08c00",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 1232581823,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "MihsZRD0SL9b1_Qe2YOQh",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 405,
			"versionNonce": 2011288226,
			"isDeleted": false,
			"id": "-0r2BNvslrxfdJ0jUPz3R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1359.6345067933216,
			"y": -635.7938017714143,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 1195427039,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "efbXuF3csN-3IRUu8rJah",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 493,
			"versionNonce": 1305714814,
			"isDeleted": false,
			"id": "XYmkcvul",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1361.0346046473612,
			"y": -643.5062663773053,
			"strokeColor": "#6741d9",
			"backgroundColor": "#6741d9",
			"width": 13.650802612304688,
			"height": 6.687227061579369,
			"seed": 632475903,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 5.3497816492634955,
			"fontFamily": 1,
			"text": "Value",
			"rawText": "Value",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Value",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "rectangle",
			"version": 336,
			"versionNonce": 1662201442,
			"isDeleted": false,
			"id": "GH13KCRC0b8qdT5-nVPsg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1286.1352293606628,
			"y": -661.6292870213163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1582192927,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "0znNN6In3gzDNGnGSa-EZ",
					"type": "arrow"
				},
				{
					"id": "0UzQE8QKlV9KkaRDDZW90",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 478,
			"versionNonce": 1841750206,
			"isDeleted": false,
			"id": "-IKi7HMm7JoNCw7RcOH28",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1279.7895652341624,
			"y": -615.803305284285,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.450414673108298,
			"seed": 1719917887,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ZPZ1OTiI",
				"focus": -0.027610932787974798,
				"gap": 9.128186514559957
			},
			"endBinding": {
				"elementId": "bh6bQcB6",
				"focus": -1.4287961836607632,
				"gap": 15.91857690305801
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.450414673108298
				]
			]
		},
		{
			"type": "arrow",
			"version": 637,
			"versionNonce": 1596133922,
			"isDeleted": false,
			"id": "MihsZRD0SL9b1_Qe2YOQh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1328.865032872766,
			"y": -616.2612412187048,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.069568236672012,
			"seed": 833871199,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cC1rUAjX",
				"focus": 0.08048516608926022,
				"gap": 9.587843515643044
			},
			"endBinding": {
				"elementId": "NMOLQ3b6",
				"focus": 2.4761423362429262,
				"gap": 14.606627886637284
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.069568236672012
				]
			]
		},
		{
			"type": "arrow",
			"version": 448,
			"versionNonce": 1709709566,
			"isDeleted": false,
			"id": "efbXuF3csN-3IRUu8rJah",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1379.0446387315408,
			"y": -616.1375034842474,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.1846092836965454,
			"height": 5.738032140795212,
			"seed": 1932450175,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "W3ludlNi",
				"focus": -0.06261774696855257,
				"gap": 8.793988314597527
			},
			"endBinding": {
				"elementId": "-0r2BNvslrxfdJ0jUPz3R",
				"focus": -0.01081050158067891,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.1846092836965454,
					-5.738032140795212
				]
			]
		},
		{
			"type": "arrow",
			"version": 747,
			"versionNonce": 1593867746,
			"isDeleted": false,
			"id": "0znNN6In3gzDNGnGSa-EZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1299.0228744797737,
			"y": -641.2950723002939,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 540365215,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "zXsK8qv8",
				"focus": -0.4041942899060175,
				"gap": 8.059374632612673
			},
			"endBinding": {
				"elementId": "ZPZ1OTiI",
				"focus": -2.386419463779528,
				"gap": 15.43617712778348
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "arrow",
			"version": 606,
			"versionNonce": 1840793918,
			"isDeleted": false,
			"id": "0UzQE8QKlV9KkaRDDZW90",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1309.5554009714183,
			"y": -641.6766855789763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 838321599,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "zXsK8qv8",
				"focus": 0.29872422579974817,
				"gap": 7.677761353930293
			},
			"endBinding": {
				"elementId": "zXsK8qv8",
				"focus": -0.298069817084965,
				"gap": 1.419303583532951
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "text",
			"version": 706,
			"versionNonce": 532312482,
			"isDeleted": false,
			"id": "NMOLQ3b6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1337.607434397375,
			"y": -645.1237282038935,
			"strokeColor": "#f08c00",
			"backgroundColor": "#6741d9",
			"width": 10.639389038085938,
			"height": 8.186290861879323,
			"seed": 664188383,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "MihsZRD0SL9b1_Qe2YOQh",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.549032689503458,
			"fontFamily": 1,
			"text": "Key",
			"rawText": "Key",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Key",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 587,
			"versionNonce": 613970302,
			"isDeleted": false,
			"id": "bh6bQcB6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1261.2654902241432,
			"y": -645.3795634678715,
			"strokeColor": "#1971c2",
			"backgroundColor": "#6741d9",
			"width": 15.634078979492188,
			"height": 7.207266607419975,
			"seed": 1210229247,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "-IKi7HMm7JoNCw7RcOH28",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 5.76581328593598,
			"fontFamily": 1,
			"text": "Query",
			"rawText": "Query",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Query",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 305,
			"versionNonce": 1686105442,
			"isDeleted": false,
			"id": "sJ_0W1zfwGGz1bWqj--XS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1299.0210082849806,
			"y": -641.1979083988429,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 19.16577876389772,
			"height": 0.12862938767716514,
			"seed": 614205983,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.16577876389772,
					-0.12862938767716514
				]
			]
		},
		{
			"type": "line",
			"version": 306,
			"versionNonce": 365531582,
			"isDeleted": false,
			"id": "rZw1cesCj20MdxbO8tFNH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1279.662285439567,
			"y": -641.3265377865198,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 5.356116096995493,
			"seed": 1509125695,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					5.356116096995493
				]
			]
		},
		{
			"type": "line",
			"version": 377,
			"versionNonce": 849342754,
			"isDeleted": false,
			"id": "iqaae19C8HUPBH9POb84a",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1309.5436546378899,
			"y": -641.538775362156,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 18.411802691515447,
			"height": 0.14931853268717532,
			"seed": 319376991,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.411802691515447,
					-0.14931853268717532
				]
			]
		},
		{
			"type": "line",
			"version": 316,
			"versionNonce": 1013754366,
			"isDeleted": false,
			"id": "gdVrrL0KA_642M6US9cpx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1327.9381715581335,
			"y": -641.725621329889,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.04373689328065211,
			"height": 5.817006806327527,
			"seed": 1252928127,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.04373689328065211,
					5.817006806327527
				]
			]
		},
		{
			"type": "text",
			"version": 476,
			"versionNonce": 227114210,
			"isDeleted": false,
			"id": "ZPZ1OTiI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1272.474546756367,
			"y": -632.510607058123,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 1302495903,
			"groupIds": [
				"CjiMIF_AAHnImcxAaM2q-"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "0znNN6In3gzDNGnGSa-EZ",
					"type": "arrow"
				},
				{
					"id": "-IKi7HMm7JoNCw7RcOH28",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 477,
			"versionNonce": 126007870,
			"isDeleted": false,
			"id": "cC1rUAjX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1320.7231738099254,
			"y": -633.4281999936259,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 2090260159,
			"groupIds": [
				"SQXsxWru8m98G8bv_wlkp"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "MihsZRD0SL9b1_Qe2YOQh",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 478,
			"versionNonce": 852201634,
			"isDeleted": false,
			"id": "W3ludlNi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1372.1083781980865,
			"y": -632.510607058123,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 1311483615,
			"groupIds": [
				"JYWvYm_mcr3djfoFCOZ47"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "efbXuF3csN-3IRUu8rJah",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 519,
			"versionNonce": 1575797374,
			"isDeleted": false,
			"id": "zXsK8qv8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1290.0953255744255,
			"y": -660.1985096701462,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 29.967987060546875,
			"height": 10.84406273723957,
			"seed": 284259071,
			"groupIds": [
				"Ek0qrAa7n_TynOBsF_PYh"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "0UzQE8QKlV9KkaRDDZW90",
					"type": "arrow"
				},
				{
					"id": "0znNN6In3gzDNGnGSa-EZ",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Matmul",
			"rawText": "Matmul",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Matmul",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "rectangle",
			"version": 446,
			"versionNonce": 1444228194,
			"isDeleted": false,
			"id": "RoCu6irbp5f7K2JqtwGQg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1516.6272688636561,
			"y": -633.6400876800143,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1272033745,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "luNwGym1Ei1AqaGPap6VJ",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 495,
			"versionNonce": 577487550,
			"isDeleted": false,
			"id": "ffflyDPq6a-RIC3jMcEVO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1565.4399117422365,
			"y": -633.5142818993999,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f08c00",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 188567473,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "lZQRFKuj6ovfDJ3lxdbo8",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 533,
			"versionNonce": 1563775010,
			"isDeleted": false,
			"id": "idiRM2vwrgm7K-18jsp-8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1615.5106124269662,
			"y": -633.5142818993999,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#6741d9",
			"width": 38.74818042938864,
			"height": 12.832189622719852,
			"seed": 2067411345,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "1dnJRiF9oj-h3eIxOFfza",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 621,
			"versionNonce": 933280510,
			"isDeleted": false,
			"id": "23ACLTaq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1616.9107102810055,
			"y": -641.2267465052909,
			"strokeColor": "#6741d9",
			"backgroundColor": "#6741d9",
			"width": 13.650802612304688,
			"height": 6.687227061579369,
			"seed": 16766833,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 5.3497816492634955,
			"fontFamily": 1,
			"text": "Value",
			"rawText": "Value",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Value",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "rectangle",
			"version": 464,
			"versionNonce": 471530466,
			"isDeleted": false,
			"id": "g1Nbm8sLFeWB16qMzO9l_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1542.0113349943074,
			"y": -659.3497671493018,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 38.99979199061846,
			"height": 13.08380118394939,
			"seed": 1859502417,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "XWGDg0bGRs-I_2etcEJ3D",
					"type": "arrow"
				},
				{
					"id": "8z4zB32B8063Y_1qDSSun",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 871,
			"versionNonce": 67939134,
			"isDeleted": false,
			"id": "luNwGym1Ei1AqaGPap6VJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1535.6656708678072,
			"y": -613.5237854122705,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.450414673108298,
			"seed": 1645440817,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "yWyOCagr",
				"focus": -0.02761093278794612,
				"gap": 9.128186514559957
			},
			"endBinding": {
				"elementId": "dUSYssGW",
				"focus": -1.4287961836607632,
				"gap": 15.91857690305801
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.450414673108298
				]
			]
		},
		{
			"type": "arrow",
			"version": 1030,
			"versionNonce": 282406818,
			"isDeleted": false,
			"id": "lZQRFKuj6ovfDJ3lxdbo8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1584.7411385064104,
			"y": -613.9817213466903,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.15264531147312255,
			"height": 6.069568236672012,
			"seed": 1629511953,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0cvg366Q",
				"focus": 0.08048516608923156,
				"gap": 9.587843515643044
			},
			"endBinding": {
				"elementId": "eYdQg57x",
				"focus": 2.4761423362429262,
				"gap": 14.606627886637284
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.15264531147312255,
					-6.069568236672012
				]
			]
		},
		{
			"type": "arrow",
			"version": 841,
			"versionNonce": 1980797822,
			"isDeleted": false,
			"id": "1dnJRiF9oj-h3eIxOFfza",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1634.9207443651856,
			"y": -613.8579836122329,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.1846092836965454,
			"height": 5.738032140795212,
			"seed": 963909361,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cO98Tpct",
				"focus": -0.06261774696852403,
				"gap": 8.793988314597527
			},
			"endBinding": {
				"elementId": "idiRM2vwrgm7K-18jsp-8",
				"focus": -0.01081050158067891,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0.1846092836965454,
					-5.738032140795212
				]
			]
		},
		{
			"type": "arrow",
			"version": 1140,
			"versionNonce": 529722210,
			"isDeleted": false,
			"id": "XWGDg0bGRs-I_2etcEJ3D",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1554.8989801134182,
			"y": -639.0155524282794,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 496373969,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "HyJeZcm3",
				"focus": -0.40419428990603284,
				"gap": 8.059374632612787
			},
			"endBinding": {
				"elementId": "yWyOCagr",
				"focus": -2.386419463779528,
				"gap": 15.43617712778348
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "arrow",
			"version": 867,
			"versionNonce": 133002174,
			"isDeleted": false,
			"id": "8z4zB32B8063Y_1qDSSun",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1565.4315066050629,
			"y": -639.3971657069618,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 6.258457770397399,
			"seed": 52285105,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "HyJeZcm3",
				"focus": 0.29872422579973307,
				"gap": 7.677761353930407
			},
			"endBinding": {
				"elementId": "HyJeZcm3",
				"focus": -0.298069817084965,
				"gap": 1.419303583532951
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-6.258457770397399
				]
			]
		},
		{
			"type": "text",
			"version": 834,
			"versionNonce": 1319317282,
			"isDeleted": false,
			"id": "eYdQg57x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1593.4835400310196,
			"y": -642.844208331879,
			"strokeColor": "#f08c00",
			"backgroundColor": "#6741d9",
			"width": 10.639389038085938,
			"height": 8.186290861879323,
			"seed": 1085460625,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "lZQRFKuj6ovfDJ3lxdbo8",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 6.549032689503458,
			"fontFamily": 1,
			"text": "Key",
			"rawText": "Key",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Key",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 715,
			"versionNonce": 1136937982,
			"isDeleted": false,
			"id": "dUSYssGW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1517.141595857788,
			"y": -643.1000435958571,
			"strokeColor": "#1971c2",
			"backgroundColor": "#6741d9",
			"width": 15.634078979492188,
			"height": 7.207266607419975,
			"seed": 1812764273,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "luNwGym1Ei1AqaGPap6VJ",
					"type": "arrow"
				}
			],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"fontSize": 5.76581328593598,
			"fontFamily": 1,
			"text": "Query",
			"rawText": "Query",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Query",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "line",
			"version": 433,
			"versionNonce": 41220834,
			"isDeleted": false,
			"id": "8NQ_31N02WQvOwGYLyEtm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1554.8971139186249,
			"y": -638.9183885268284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 19.16577876389772,
			"height": 0.12862938767716514,
			"seed": 2012389457,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.16577876389772,
					-0.12862938767716514
				]
			]
		},
		{
			"type": "line",
			"version": 434,
			"versionNonce": 1201019966,
			"isDeleted": false,
			"id": "gc13qB5zaR5R5sAnPYYmQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1535.5383910732114,
			"y": -639.0470179145053,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0,
			"height": 5.356116096995493,
			"seed": 305950257,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927705,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					5.356116096995493
				]
			]
		},
		{
			"type": "line",
			"version": 505,
			"versionNonce": 966217378,
			"isDeleted": false,
			"id": "NN9f0SW9p-gYKZB0kXTPQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1565.4197602715346,
			"y": -639.2592554901415,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 18.411802691515447,
			"height": 0.14931853268717532,
			"seed": 1104248849,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.411802691515447,
					-0.14931853268717532
				]
			]
		},
		{
			"type": "line",
			"version": 444,
			"versionNonce": 1229186174,
			"isDeleted": false,
			"id": "yxLb-H6cx21rcXdKAWKfR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1583.814277191778,
			"y": -639.4461014578745,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#868e96",
			"width": 0.04373689328065211,
			"height": 5.817006806327527,
			"seed": 1151948273,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.04373689328065211,
					5.817006806327527
				]
			]
		},
		{
			"type": "text",
			"version": 604,
			"versionNonce": 1220094562,
			"isDeleted": false,
			"id": "yWyOCagr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1528.3506523900116,
			"y": -630.2310871861085,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 768307153,
			"groupIds": [
				"ycyIitNqQzkn67yFJ1XIw"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "XWGDg0bGRs-I_2etcEJ3D",
					"type": "arrow"
				},
				{
					"id": "luNwGym1Ei1AqaGPap6VJ",
					"type": "arrow"
				}
			],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 605,
			"versionNonce": 445555902,
			"isDeleted": false,
			"id": "0cvg366Q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1576.59927944357,
			"y": -631.1486801216114,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 1129270705,
			"groupIds": [
				"dJS-5VJRa5AYQU_OXmMjV"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "lZQRFKuj6ovfDJ3lxdbo8",
					"type": "arrow"
				}
			],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 606,
			"versionNonce": 380210722,
			"isDeleted": false,
			"id": "cO98Tpct",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1627.984483831731,
			"y": -630.2310871861085,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 15.679290771484375,
			"height": 7.579115259278042,
			"seed": 475819921,
			"groupIds": [
				"zqbQgrlHaAZnscgodRcOJ"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "1dnJRiF9oj-h3eIxOFfza",
					"type": "arrow"
				}
			],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 6.063292207422434,
			"fontFamily": 1,
			"text": "linear",
			"rawText": "linear",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 647,
			"versionNonce": 756505854,
			"isDeleted": false,
			"id": "HyJeZcm3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1545.9714312080703,
			"y": -657.9189897981317,
			"strokeColor": "#343a40",
			"backgroundColor": "#868e96",
			"width": 29.967987060546875,
			"height": 10.84406273723957,
			"seed": 2133480817,
			"groupIds": [
				"wfQP1wrOoKRo7QO-Agh-D"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "8z4zB32B8063Y_1qDSSun",
					"type": "arrow"
				},
				{
					"id": "XWGDg0bGRs-I_2etcEJ3D",
					"type": "arrow"
				}
			],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 8.675250189791656,
			"fontFamily": 1,
			"text": "Matmul",
			"rawText": "Matmul",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Matmul",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 388,
			"versionNonce": 1482127842,
			"isDeleted": false,
			"id": "-4_BksQu2Thwap42E_0y_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1320.4488457383022,
			"y": -682.0271737210791,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 306.0255428179669,
			"height": 0.5698799680036473,
			"seed": 965829215,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					306.0255428179669,
					-0.5698799680036473
				]
			]
		},
		{
			"type": "rectangle",
			"version": 246,
			"versionNonce": 375328062,
			"isDeleted": false,
			"id": "j-O8NHsbkWEIqPRTGoD99",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1246.364449897826,
			"y": -665.9280646249756,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 169.2543504970879,
			"height": 54.13859696034797,
			"seed": 889723633,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 293,
			"versionNonce": 1288826274,
			"isDeleted": false,
			"id": "crBiEmxWRLh5yPIAP4OOi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1505.944775323494,
			"y": -665.9280646249756,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 169.2543504970879,
			"height": 55.84823686435891,
			"seed": 755184863,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 274,
			"versionNonce": 331789694,
			"isDeleted": false,
			"id": "i5WT3703",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1281.6970079140535,
			"y": -609.6524177846138,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 95.60586547851562,
			"height": 16.23147201293943,
			"seed": 92225055,
			"groupIds": [
				"nQpKyyvB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.985177610351544,
			"fontFamily": 1,
			"text": "input embedding",
			"rawText": "input embedding",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "input embedding",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 317,
			"versionNonce": 2034755938,
			"isDeleted": false,
			"id": "CJQU9Ezv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1540.8930821398947,
			"y": -607.9774720649416,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 108.58761596679688,
			"height": 16.23147201293943,
			"seed": 1579497041,
			"groupIds": [
				"D3hRt9L2O_stzX0AJ6LCf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.985177610351544,
			"fontFamily": 1,
			"text": "output embedding",
			"rawText": "output embedding",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "output embedding",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 244274622,
			"isDeleted": false,
			"id": "WsSUpt5PV7YIEN5PmRCBZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1425.0718438726847,
			"y": -629.2738317605028,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 84.0802301047188,
			"height": 2.877270231720445,
			"seed": 124349841,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.31969669241334486,
					0
				],
				[
					0.6393933848266897,
					0
				],
				[
					1.2787867696533795,
					0.31969669241345855
				],
				[
					1.9181801544802966,
					0.31969669241345855
				],
				[
					2.2378768468936414,
					0.31969669241345855
				],
				[
					3.516663616547021,
					0.31969669241345855
				],
				[
					4.475753693787283,
					0.6393933848268034
				],
				[
					5.75454046344089,
					0.6393933848268034
				],
				[
					7.353023925507614,
					0.6393933848268034
				],
				[
					8.951507387574566,
					0.6393933848268034
				],
				[
					10.549990849641517,
					0.6393933848268034
				],
				[
					13.427261081361848,
					0.9590900772401483
				],
				[
					15.66513792825549,
					0.9590900772401483
				],
				[
					17.26362139032244,
					0.9590900772401483
				],
				[
					19.181801544802738,
					1.5984834620669517
				],
				[
					20.78028500686969,
					1.5984834620669517
				],
				[
					22.37876846893664,
					1.5984834620669517
				],
				[
					23.977251931003366,
					1.5984834620669517
				],
				[
					25.895432085483662,
					1.9181801544802966
				],
				[
					26.854522162723924,
					1.9181801544802966
				],
				[
					28.772702317203994,
					2.5575735393071
				],
				[
					29.731792394444255,
					2.5575735393071
				],
				[
					31.649972548924552,
					2.5575735393071
				],
				[
					32.60906262616459,
					2.5575735393071
				],
				[
					34.20754608823154,
					2.5575735393071
				],
				[
					35.486332857885145,
					2.877270231720445
				],
				[
					36.44542293512518,
					2.877270231720445
				],
				[
					37.404513012365214,
					2.877270231720445
				],
				[
					39.32269316684574,
					2.877270231720445
				],
				[
					40.28178324408577,
					2.877270231720445
				],
				[
					41.880266706152725,
					2.877270231720445
				],
				[
					43.159053475806104,
					2.877270231720445
				],
				[
					44.757536937873056,
					2.877270231720445
				],
				[
					46.036323707526435,
					2.2378768468936414
				],
				[
					46.9954137847667,
					2.2378768468936414
				],
				[
					47.95450386200696,
					2.2378768468936414
				],
				[
					49.55298732407368,
					2.2378768468936414
				],
				[
					51.151470786140635,
					2.2378768468936414
				],
				[
					53.389347633034276,
					2.2378768468936414
				],
				[
					54.66813440268788,
					2.2378768468936414
				],
				[
					55.62722447992792,
					2.2378768468936414
				],
				[
					57.22570794199487,
					2.2378768468936414
				],
				[
					58.82419140406182,
					2.2378768468936414
				],
				[
					60.42267486612877,
					2.2378768468936414
				],
				[
					62.34085502060884,
					2.2378768468936414
				],
				[
					63.939338482675794,
					2.2378768468936414
				],
				[
					65.53782194474275,
					2.2378768468936414
				],
				[
					67.45600209922304,
					1.9181801544802966
				],
				[
					69.05448556129,
					1.9181801544802966
				],
				[
					70.01357563853003,
					1.9181801544802966
				],
				[
					71.29236240818341,
					1.9181801544802966
				],
				[
					72.25145248542367,
					1.9181801544802966
				],
				[
					73.21054256266393,
					1.9181801544802966
				],
				[
					73.84993594749062,
					1.9181801544802966
				],
				[
					74.80902602473066,
					1.9181801544802966
				],
				[
					75.128722717144,
					1.9181801544802966
				],
				[
					75.76811610197092,
					1.9181801544802966
				],
				[
					76.08781279438426,
					1.5984834620669517
				],
				[
					76.40750948679761,
					1.5984834620669517
				],
				[
					76.72720617921095,
					1.5984834620669517
				],
				[
					77.0469028716243,
					1.5984834620669517
				],
				[
					77.36659956403787,
					1.5984834620669517
				],
				[
					77.68629625645121,
					1.2787867696536068
				],
				[
					78.00599294886456,
					1.2787867696536068
				],
				[
					78.3256896412779,
					1.2787867696536068
				],
				[
					78.64538633369125,
					1.2787867696536068
				],
				[
					78.9650830261046,
					1.2787867696536068
				],
				[
					79.28477971851794,
					1.2787867696536068
				],
				[
					79.60447641093128,
					1.2787867696536068
				],
				[
					79.92417310334486,
					1.2787867696536068
				],
				[
					80.2438697957582,
					1.2787867696536068
				],
				[
					80.56356648817155,
					1.2787867696536068
				],
				[
					80.88326318058489,
					1.2787867696536068
				],
				[
					81.20295987299824,
					1.2787867696536068
				],
				[
					81.52265656541181,
					1.2787867696536068
				],
				[
					81.84235325782515,
					1.2787867696536068
				],
				[
					82.1620499502385,
					1.5984834620669517
				],
				[
					82.48174664265184,
					1.5984834620669517
				],
				[
					82.80144333506519,
					1.5984834620669517
				],
				[
					83.12114002747853,
					1.5984834620669517
				],
				[
					83.44083671989188,
					1.5984834620669517
				],
				[
					83.76053341230522,
					1.5984834620669517
				],
				[
					84.0802301047188,
					1.5984834620669517
				],
				[
					84.0802301047188,
					1.5984834620669517
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 150,
			"versionNonce": 1695051042,
			"isDeleted": false,
			"id": "s6dOCRQ3G1SOy0-Z9s4iL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1429.8672942588853,
			"y": -632.79049537705,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 7.353023925507614,
			"height": 6.713630540681038,
			"seed": 13051441,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.31969669241334486
				],
				[
					-0.31969669241334486,
					0.31969669241334486
				],
				[
					-0.6393933848266897,
					0.6393933848268034
				],
				[
					-0.959090077240262,
					0.6393933848268034
				],
				[
					-1.2787867696536068,
					0.9590900772401483
				],
				[
					-1.5984834620669517,
					0.9590900772401483
				],
				[
					-1.9181801544802966,
					1.2787867696534931
				],
				[
					-2.2378768468936414,
					1.2787867696534931
				],
				[
					-2.5575735393069863,
					1.2787867696534931
				],
				[
					-2.877270231720331,
					1.5984834620669517
				],
				[
					-3.196966924133676,
					1.5984834620669517
				],
				[
					-3.5166636165472482,
					1.5984834620669517
				],
				[
					-3.5166636165472482,
					1.9181801544802966
				],
				[
					-3.836360308960593,
					1.9181801544802966
				],
				[
					-4.156057001373938,
					1.9181801544802966
				],
				[
					-4.475753693787283,
					2.2378768468936414
				],
				[
					-4.795450386200628,
					2.2378768468936414
				],
				[
					-4.795450386200628,
					2.5575735393071
				],
				[
					-5.1151470786142,
					2.5575735393071
				],
				[
					-5.1151470786142,
					2.877270231720445
				],
				[
					-5.434843771027545,
					2.877270231720445
				],
				[
					-5.434843771027545,
					3.1969669241337897
				],
				[
					-5.75454046344089,
					3.1969669241337897
				],
				[
					-6.0742371558542345,
					3.5166636165471346
				],
				[
					-6.0742371558542345,
					3.836360308960593
				],
				[
					-6.393933848267579,
					3.836360308960593
				],
				[
					-6.713630540680924,
					3.836360308960593
				],
				[
					-7.033327233094269,
					3.836360308960593
				],
				[
					-7.353023925507614,
					3.836360308960593
				],
				[
					-7.353023925507614,
					4.156057001373938
				],
				[
					-7.033327233094269,
					4.156057001373938
				],
				[
					-6.713630540680924,
					4.156057001373938
				],
				[
					-6.393933848267579,
					4.475753693787283
				],
				[
					-6.0742371558542345,
					4.475753693787283
				],
				[
					-5.75454046344089,
					4.795450386200741
				],
				[
					-5.434843771027545,
					4.795450386200741
				],
				[
					-5.1151470786142,
					4.795450386200741
				],
				[
					-4.795450386200628,
					5.115147078614086
				],
				[
					-4.475753693787283,
					5.115147078614086
				],
				[
					-4.156057001373938,
					5.434843771027431
				],
				[
					-3.836360308960593,
					5.434843771027431
				],
				[
					-3.5166636165472482,
					5.754540463440776
				],
				[
					-3.196966924133676,
					5.754540463440776
				],
				[
					-3.196966924133676,
					6.0742371558542345
				],
				[
					-2.877270231720331,
					6.0742371558542345
				],
				[
					-2.5575735393069863,
					6.0742371558542345
				],
				[
					-2.5575735393069863,
					6.393933848267579
				],
				[
					-2.2378768468936414,
					6.393933848267579
				],
				[
					-2.2378768468936414,
					6.713630540681038
				],
				[
					-1.9181801544802966,
					6.713630540681038
				],
				[
					-1.5984834620669517,
					6.713630540681038
				],
				[
					-1.5984834620669517,
					6.713630540681038
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 148,
			"versionNonce": 534375934,
			"isDeleted": false,
			"id": "sdeSdmK-RTW3xzS3sn50Z",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1503.0778368215492,
			"y": -632.79049537705,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 9.27120407998791,
			"height": 10.549990849641517,
			"seed": 1582253265,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.31969669241334486,
					0
				],
				[
					0.6393933848266897,
					0.31969669241334486
				],
				[
					0.9590900772400346,
					0.31969669241334486
				],
				[
					0.9590900772400346,
					0.6393933848268034
				],
				[
					1.2787867696533795,
					0.6393933848268034
				],
				[
					1.5984834620667243,
					0.9590900772401483
				],
				[
					1.9181801544802966,
					0.9590900772401483
				],
				[
					1.9181801544802966,
					1.2787867696534931
				],
				[
					2.2378768468936414,
					1.2787867696534931
				],
				[
					2.5575735393069863,
					1.2787867696534931
				],
				[
					2.877270231720331,
					1.5984834620669517
				],
				[
					3.196966924133676,
					1.9181801544802966
				],
				[
					3.5166636165472482,
					1.9181801544802966
				],
				[
					3.836360308960593,
					2.2378768468936414
				],
				[
					4.156057001373938,
					2.5575735393071
				],
				[
					4.475753693787283,
					2.877270231720445
				],
				[
					4.795450386200628,
					3.1969669241337897
				],
				[
					5.1151470786139726,
					3.5166636165471346
				],
				[
					5.754540463440662,
					3.836360308960593
				],
				[
					6.0742371558542345,
					4.156057001373938
				],
				[
					6.393933848267579,
					4.475753693787283
				],
				[
					6.713630540680924,
					4.795450386200741
				],
				[
					7.353023925507614,
					5.434843771027431
				],
				[
					7.672720617921186,
					5.434843771027431
				],
				[
					7.992417310334531,
					5.754540463440776
				],
				[
					8.312114002747876,
					5.754540463440776
				],
				[
					8.312114002747876,
					6.0742371558542345
				],
				[
					8.63181069516122,
					6.0742371558542345
				],
				[
					8.63181069516122,
					6.393933848267579
				],
				[
					8.951507387574566,
					6.393933848267579
				],
				[
					8.63181069516122,
					6.393933848267579
				],
				[
					8.63181069516122,
					6.713630540681038
				],
				[
					8.312114002747876,
					6.713630540681038
				],
				[
					7.992417310334531,
					6.713630540681038
				],
				[
					7.353023925507614,
					7.033327233094383
				],
				[
					6.713630540680924,
					7.353023925507728
				],
				[
					5.754540463440662,
					7.992417310334531
				],
				[
					5.1151470786139726,
					7.992417310334531
				],
				[
					4.156057001373938,
					8.312114002747876
				],
				[
					3.5166636165472482,
					8.63181069516122
				],
				[
					2.877270231720331,
					8.95150738757468
				],
				[
					2.2378768468936414,
					9.271204079988024
				],
				[
					1.2787867696533795,
					9.271204079988024
				],
				[
					0.9590900772400346,
					9.590900772401369
				],
				[
					0.6393933848266897,
					9.590900772401369
				],
				[
					0.31969669241334486,
					9.910597464814714
				],
				[
					0,
					9.910597464814714
				],
				[
					-0.31969669241334486,
					10.230294157228172
				],
				[
					-0.31969669241334486,
					10.549990849641517
				],
				[
					-0.31969669241334486,
					10.549990849641517
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 1434613986,
			"isDeleted": false,
			"id": "bvATAq0n",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1439.1384983388732,
			"y": -624.7980780667156,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 52.0001220703125,
			"height": 20,
			"seed": 1575149969,
			"groupIds": [
				"nQpKyyvB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "shared",
			"rawText": "shared",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "shared",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 231,
			"versionNonce": 346521150,
			"isDeleted": false,
			"id": "weu8gEer",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1905.1807819046976,
			"y": 149.78149615721924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.26557922363281,
			"height": 15.75644664344113,
			"seed": 1770370847,
			"groupIds": [
				"YUZIaecb"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.605157314752905,
			"fontFamily": 1,
			"text": "parallelized",
			"rawText": "parallelized",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "parallelized",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 250,
			"versionNonce": 172297378,
			"isDeleted": false,
			"id": "g6VlNQoo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1904.9163105865791,
			"y": 210.36608797902255,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 59.211517333984375,
			"height": 28.631755945374017,
			"seed": 1388763839,
			"groupIds": [
				"KNl2y1NZcmlJhwTrpnJgw"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 11.452702378149606,
			"fontFamily": 1,
			"text": "long term\ndependency",
			"rawText": "long term\ndependency",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "long term\ndependency",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 1910048382,
			"isDeleted": false,
			"id": "mGJhWEti",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1897.5917642795741,
			"y": 285.9265729139924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.77854919433594,
			"height": 15.75644664344113,
			"seed": 434881297,
			"groupIds": [
				"R2KgPonUuAJrQ6vjm42qD"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.605157314752905,
			"fontFamily": 1,
			"text": "faster",
			"rawText": "faster",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "faster",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 354,
			"versionNonce": 2029987938,
			"isDeleted": false,
			"id": "79odkhsn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1146.166259484697,
			"y": -339.66151930608663,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.2305908203125,
			"height": 25.409180496721433,
			"seed": 729866207,
			"groupIds": [
				"ankxZCTHOHr2xPd3_m_Nh"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 10.163672198688573,
			"fontFamily": 1,
			"text": "convolution is\nmore expensive",
			"rawText": "convolution is\nmore expensive",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "convolution is\nmore expensive",
			"lineHeight": 1.25,
			"baseline": 21
		},
		{
			"type": "text",
			"version": 474,
			"versionNonce": 2016380606,
			"isDeleted": false,
			"id": "FGlhCDpP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1149.432111648488,
			"y": -250.34985435370743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.52615356445312,
			"height": 13.408864801071577,
			"seed": 1034505855,
			"groupIds": [
				"vD5m8Cc98YsjGujO8MV5a"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 10.72709184085726,
			"fontFamily": 1,
			"text": "more interpretable",
			"rawText": "more interpretable",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "more interpretable",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "line",
			"version": 174,
			"versionNonce": 159370274,
			"isDeleted": false,
			"id": "_5CIwaV3s3kXQbwf61FSl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -628.2458778158045,
			"y": -94.77581212537561,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 56.23372626970661,
			"height": 0.7920243136578478,
			"seed": 1150564863,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					56.23372626970661,
					0.7920243136578478
				]
			]
		},
		{
			"type": "line",
			"version": 231,
			"versionNonce": 676069118,
			"isDeleted": false,
			"id": "SW6meWd1FT111JQl_vx8B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1049.602812681776,
			"y": -81.31139879319231,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 69.30212744506093,
			"height": 1.4210854715202004e-14,
			"seed": 15707729,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					69.30212744506093,
					1.4210854715202004e-14
				]
			]
		},
		{
			"type": "line",
			"version": 186,
			"versionNonce": 1370879970,
			"isDeleted": false,
			"id": "Q_vknmrh0ReueQiSVvzlg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -920.8988617123769,
			"y": -67.05496114735118,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 63.36194509262725,
			"height": 0.3960121568289168,
			"seed": 1645206161,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					63.36194509262725,
					0.3960121568289168
				]
			]
		},
		{
			"type": "line",
			"version": 240,
			"versionNonce": 1185902398,
			"isDeleted": false,
			"id": "XSdbwdIR7wdwdvKH5X7D5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -840.5083938761061,
			"y": -54.580578207240194,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 71.67820038603452,
			"height": 0,
			"seed": 1024482495,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					71.67820038603452,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 289,
			"versionNonce": 1370532770,
			"isDeleted": false,
			"id": "CNuSBrcYEV0ZIf-zjcCX7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -832.390144661113,
			"y": -67.4509733041801,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 73.26224901335024,
			"height": 0,
			"seed": 162060383,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					73.26224901335024,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 313,
			"versionNonce": 1606080382,
			"isDeleted": false,
			"id": "NL61_GIPYcefDPij7yRXC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -849.0226552479277,
			"y": -93.98378781171775,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 82.76654077724436,
			"height": 0.3960121568289168,
			"seed": 170598303,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					82.76654077724436,
					0.3960121568289168
				]
			]
		},
		{
			"type": "line",
			"version": 184,
			"versionNonce": 798943074,
			"isDeleted": false,
			"id": "7gLbWDzclEdGB7AfRa8b-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -659.3672758000641,
			"y": -55.614367460910884,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 87.53645897559522,
			"height": 0.4090488737177367,
			"seed": 1440768095,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.53645897559522,
					0.4090488737177367
				]
			]
		},
		{
			"type": "line",
			"version": 310,
			"versionNonce": 1269774270,
			"isDeleted": false,
			"id": "o-ps6g16Z6qVDyJN7GsUs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1045.9184614633234,
			"y": -27.799044048104946,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 473.26954689141905,
			"height": 0.4090488737177509,
			"seed": 1669224959,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					473.26954689141905,
					0.4090488737177509
				]
			]
		},
		{
			"type": "line",
			"version": 144,
			"versionNonce": 1942989602,
			"isDeleted": false,
			"id": "I0hV2hTdM-p0mraUlGfZ4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1046.7365592107587,
			"y": -15.936626710290625,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 63.40257542624886,
			"height": 0.40904887371772247,
			"seed": 342817777,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					63.40257542624886,
					-0.40904887371772247
				]
			]
		},
		{
			"type": "line",
			"version": 152,
			"versionNonce": 850235390,
			"isDeleted": false,
			"id": "Qa4MvqO8wP9Vg0BApiOra",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -826.1342703320554,
			"y": 41.61318820322904,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 113.40677182888123,
			"height": 0.7821156677854049,
			"seed": 1604895039,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.40677182888123,
					0.7821156677854049
				]
			]
		},
		{
			"type": "line",
			"version": 171,
			"versionNonce": 1152513762,
			"isDeleted": false,
			"id": "NRjEpkdo7YlEe3kuy0IN_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -876.5807309042128,
			"y": 67.03194740625415,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 129.049085184589,
			"height": 0.7821156677853764,
			"seed": 752910623,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					129.049085184589,
					0.7821156677853764
				]
			]
		},
		{
			"type": "line",
			"version": 195,
			"versionNonce": 280420414,
			"isDeleted": false,
			"id": "c3td8CLRmrJRUmGqDiDme",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -799.542337627352,
			"y": 80.7189715924984,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 227.59565932554756,
			"height": 0.3910578338926882,
			"seed": 1431715665,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					227.59565932554756,
					0.3910578338926882
				]
			]
		},
		{
			"type": "line",
			"version": 128,
			"versionNonce": 584370850,
			"isDeleted": false,
			"id": "RESprvE51EfEQSMD_wj4F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1051.3835826542468,
			"y": 95.97022711431347,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 55.92127024665501,
			"height": 1.173173501678093,
			"seed": 1203996337,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					55.92127024665501,
					-1.173173501678093
				]
			]
		},
		{
			"type": "line",
			"version": 171,
			"versionNonce": 967583870,
			"isDeleted": false,
			"id": "dp8OlmfClkCZnj9GUU_df",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -987.2500978958451,
			"y": 150.7183238592906,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 79.38474028021676,
			"height": 0,
			"seed": 1131419217,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					79.38474028021676,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 177,
			"versionNonce": 619128418,
			"isDeleted": false,
			"id": "IS1zv3hfgPmIvTWhiq4CV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -664.6273849343729,
			"y": 153.06467086264675,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 90.33435962921226,
			"height": 0,
			"seed": 664127551,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					90.33435962921226,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 146,
			"versionNonce": 1565419710,
			"isDeleted": false,
			"id": "vGmg8E5wa5Q5awlMcMnco",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -133.09321866525528,
			"y": -214.28126135605882,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 37.7157355445961,
			"height": 0,
			"seed": 1043056191,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					37.7157355445961,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 206,
			"versionNonce": 867699234,
			"isDeleted": false,
			"id": "tT7kKUZfgbDMXeKEva-1o",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 79.3168304183215,
			"y": -213.86680272370063,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 113.5616652661464,
			"height": 0.41445863235819047,
			"seed": 484697457,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.5616652661464,
					-0.41445863235819047
				]
			]
		},
		{
			"type": "line",
			"version": 224,
			"versionNonce": 188653822,
			"isDeleted": false,
			"id": "gUnlqpv2118oVmJc3rwRi",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -282.920014262744,
			"y": -199.7752092235219,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 145.8894385900859,
			"height": 0.8289172647163809,
			"seed": 1296322111,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					145.8894385900859,
					-0.8289172647163809
				]
			]
		},
		{
			"type": "line",
			"version": 327,
			"versionNonce": 1177974242,
			"isDeleted": false,
			"id": "ygJQGexga4IAEYOahetto",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -28.649643310989234,
			"y": -201.64027306913383,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 221.7353683116362,
			"height": 0.41445863235819047,
			"seed": 179987295,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					221.7353683116362,
					-0.41445863235819047
				]
			]
		},
		{
			"type": "line",
			"version": 331,
			"versionNonce": 922603838,
			"isDeleted": false,
			"id": "LcKgeSuKS0KCgQczXSGuL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -283.95616084363957,
			"y": -187.54867956895507,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 293.4367117096045,
			"height": 2.072293161791009,
			"seed": 1145038623,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					293.4367117096045,
					-2.072293161791009
				]
			]
		},
		{
			"type": "line",
			"version": 125,
			"versionNonce": 493971874,
			"isDeleted": false,
			"id": "BFNxhDkQi1V0DBJnNUP7Z",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -283.9561608436395,
			"y": -173.24985675259717,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 62.9977121184462,
			"height": 0.8289172647164094,
			"seed": 1867549809,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					62.9977121184462,
					-0.8289172647164094
				]
			]
		},
		{
			"type": "line",
			"version": 187,
			"versionNonce": 1005386110,
			"isDeleted": false,
			"id": "siJ8biE9L2aEIj6uM9CLv",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -32.79422963457125,
			"y": -146.31004564931425,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 174.90154285515973,
			"height": 0.41445863235816205,
			"seed": 1100210737,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					174.90154285515973,
					0.41445863235816205
				]
			]
		},
		{
			"type": "line",
			"version": 388,
			"versionNonce": 9954658,
			"isDeleted": false,
			"id": "yDhHHDyhPXi3MmHFrlc-S",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -283.9561608436395,
			"y": -130.1461589873445,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 461.706916447033,
			"height": 0.4144586323582189,
			"seed": 932064785,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					461.706916447033,
					-0.4144586323582189
				]
			]
		},
		{
			"type": "line",
			"version": 169,
			"versionNonce": 1632442814,
			"isDeleted": false,
			"id": "vn-uiEIVSZ-VGxII0Q2E7",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -191.50834516981843,
			"y": -40.5235823022667,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 90.0938383043374,
			"height": 0.9288024567457285,
			"seed": 346775135,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					90.0938383043374,
					-0.9288024567457285
				]
			]
		},
		{
			"type": "line",
			"version": 178,
			"versionNonce": 2029578530,
			"isDeleted": false,
			"id": "-81l30jcSms09pbWyt3nO",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -152.96304321486997,
			"y": -13.588311056640038,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 176.008065553319,
			"height": 0,
			"seed": 557290335,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					176.008065553319,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 179,
			"versionNonce": 1581199870,
			"isDeleted": false,
			"id": "Y5uWhAVyEZOKCYrd4v3Ly",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -194.2947525400557,
			"y": 42.6042375764776,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 161.14722624538706,
			"height": 0.9288024567457569,
			"seed": 53878929,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					161.14722624538706,
					0.9288024567457569
				]
			]
		},
		{
			"type": "line",
			"version": 163,
			"versionNonce": 235107554,
			"isDeleted": false,
			"id": "dQLDf_m8-0Mi-UHFYhxkz",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 92.70520659438,
			"y": 43.53304003322336,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 98.45306041504921,
			"height": 1.8576049134914854,
			"seed": 353624305,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					98.45306041504921,
					1.8576049134914854
				]
			]
		},
		{
			"type": "line",
			"version": 222,
			"versionNonce": 1573143102,
			"isDeleted": false,
			"id": "8zp9_QnW49GyVdOMcxB31",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 59.26831815153315,
			"y": 57.465076884409555,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 132.35435008626894,
			"height": 0.46440122837287845,
			"seed": 1172792127,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					132.35435008626894,
					0.46440122837287845
				]
			]
		},
		{
			"type": "line",
			"version": 308,
			"versionNonce": 21399714,
			"isDeleted": false,
			"id": "fSDT-iHUToHbd8Fjl_JG5",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -283.6919890018338,
			"y": 71.62931434978219,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 147.67959062257376,
			"height": 0.46440122837285003,
			"seed": 1354982175,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					147.67959062257376,
					-0.46440122837285003
				]
			]
		},
		{
			"type": "line",
			"version": 154,
			"versionNonce": 45959806,
			"isDeleted": false,
			"id": "yW4EurO3plk4unCEBMRc4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -128.81417933948052,
			"y": 102.04759480820539,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 66.40937565732088,
			"height": 0.9288024567457569,
			"seed": 1165413585,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.40937565732088,
					-0.9288024567457569
				]
			]
		},
		{
			"type": "line",
			"version": 194,
			"versionNonce": 175187042,
			"isDeleted": false,
			"id": "XhUpfwk8k2zK0v5DU_cbk",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -0.6394403085674867,
			"y": 101.58319357983251,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 157.43201641840403,
			"height": 0.9288024567457285,
			"seed": 272828081,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					157.43201641840403,
					0.9288024567457285
				]
			]
		},
		{
			"type": "line",
			"version": 216,
			"versionNonce": 1810582206,
			"isDeleted": false,
			"id": "eWiTU8f4m1fuD8bSmGX1c",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -65.19121105239691,
			"y": 116.90843411613733,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 232.20061418643667,
			"height": 1.3932036851186353,
			"seed": 1378711391,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					232.20061418643667,
					-1.3932036851186353
				]
			]
		},
		{
			"type": "line",
			"version": 341,
			"versionNonce": 324159522,
			"isDeleted": false,
			"id": "s1Ts7AEuWsAtPX9TPq-Ko",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -256.5245171420207,
			"y": 130.3760697389507,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 328.3316684596215,
			"height": 2.842170943040401e-14,
			"seed": 1894553649,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					328.3316684596215,
					-2.842170943040401e-14
				]
			]
		},
		{
			"type": "line",
			"version": 177,
			"versionNonce": 938427134,
			"isDeleted": false,
			"id": "y6a3f595QfggfXw7LxjMj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.72948498546555,
			"y": 141.05729799152675,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 145.82198570908224,
			"height": 1.8576049134914854,
			"seed": 1766525727,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					145.82198570908224,
					1.8576049134914854
				]
			]
		},
		{
			"type": "line",
			"version": 168,
			"versionNonce": 1943598050,
			"isDeleted": false,
			"id": "SGpBWYZimXMMSGQRiU95z",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -284.3885908443931,
			"y": 155.9181372994587,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 144.89318325233648,
			"height": 0.46440122837287845,
			"seed": 1070004383,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					144.89318325233648,
					0.46440122837287845
				]
			]
		},
		{
			"type": "text",
			"version": 326,
			"versionNonce": 155857726,
			"isDeleted": false,
			"id": "cZopHU4l",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 373.1996317243402,
			"y": -261.3263657871763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 89.07797241210938,
			"height": 31.125003822740993,
			"seed": 243951089,
			"groupIds": [
				"uYa9Rba0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.450001529096397,
			"fontFamily": 1,
			"text": "hiperparameter\ngrid search",
			"rawText": "hiperparameter\ngrid search",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "hiperparameter\ngrid search",
			"lineHeight": 1.25,
			"baseline": 26
		},
		{
			"type": "text",
			"version": 158,
			"versionNonce": 773072802,
			"isDeleted": false,
			"id": "uf8DRweu",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 379.7079622543306,
			"y": 202.54010107755954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 93.00071716308594,
			"height": 30.533337410923764,
			"seed": 505073329,
			"groupIds": [
				"uYa9Rba0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 12.213334964369505,
			"fontFamily": 1,
			"text": "Same model\ndifferent tasks",
			"rawText": "Same model\ndifferent tasks",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Same model\ndifferent tasks",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "text",
			"version": 217,
			"versionNonce": 173874046,
			"isDeleted": false,
			"id": "Dj8jZy9p",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1170.446258181777,
			"y": -203.17933049759603,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 45.43873596191406,
			"height": 29.44307342396986,
			"seed": 1621617617,
			"groupIds": [
				"W2L4tfF0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 7.851486246391962,
			"fontFamily": 1,
			"text": "without fine\ntuning good\nresults",
			"rawText": "without fine\ntuning good\nresults",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "without fine\ntuning good\nresults",
			"lineHeight": 1.25,
			"baseline": 26
		},
		{
			"type": "text",
			"version": 299,
			"versionNonce": 707978082,
			"isDeleted": false,
			"id": "KARkv9iQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1158.2412499631919,
			"y": -155.73332693420912,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 64.39703369140625,
			"height": 9.814357807989953,
			"seed": 681054993,
			"groupIds": [
				"kkaM-wsm2j7leKw6gACuW"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 7.851486246391962,
			"fontFamily": 1,
			"text": "outperforms rnns",
			"rawText": "outperforms rnns",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "outperforms rnns",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 1550,
			"versionNonce": 1902705598,
			"isDeleted": false,
			"id": "KySQWlLu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -124.69713550887423,
			"y": -1249.2116995021213,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.230026245117188,
			"height": 6.9868288167958585,
			"seed": 686256137,
			"groupIds": [
				"8ozdMCwaj6D2A74qpGsU7"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 5.5894630534366865,
			"fontFamily": 1,
			"text": "residual",
			"rawText": "residual",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "residual",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "text",
			"version": 617,
			"versionNonce": 1921263394,
			"isDeleted": false,
			"id": "So0sRvQg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -128.00173680071885,
			"y": -1181.0542978578258,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.230026245117188,
			"height": 6.9868288167958585,
			"seed": 1244775271,
			"groupIds": [
				"bpOorJZ-HxiXlFyPGc3kR"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 5.5894630534366865,
			"fontFamily": 1,
			"text": "residual",
			"rawText": "residual",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "residual",
			"lineHeight": 1.25,
			"baseline": 5
		},
		{
			"type": "rectangle",
			"version": 348,
			"versionNonce": 76469246,
			"isDeleted": false,
			"id": "OspLj6o4IcO4lLxCnCpZo",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -213.68446825217032,
			"y": 916.3758677595532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 54,
			"height": 73,
			"seed": 376489666,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "oDOoCIGp"
				}
			],
			"updated": 1694624927706,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 238,
			"versionNonce": 1870066402,
			"isDeleted": false,
			"id": "oDOoCIGp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -192.076481801975,
			"y": 942.8758677595532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 10.784027099609375,
			"height": 20,
			"seed": 1659584514,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "E",
			"rawText": "E",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "OspLj6o4IcO4lLxCnCpZo",
			"originalText": "E",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 387,
			"versionNonce": 500147262,
			"isDeleted": false,
			"id": "DCBQu0zraDRHLmcYl_3jA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -211.9726754662159,
			"y": 1023.8062050672422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#d0bfff",
			"width": 53.04355659531524,
			"height": 72.78069393310693,
			"seed": 1698374494,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 395,
			"versionNonce": 597313186,
			"isDeleted": false,
			"id": "ULteBJyf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -329.0791866354513,
			"y": 934.8407562518438,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 40.13935852050781,
			"height": 12.813020220134545,
			"seed": 1203402498,
			"groupIds": [
				"uLqqaP0NDuuvY3ekE9dCG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "1  - cat",
			"rawText": "1  - cat",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  - cat",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 360,
			"versionNonce": 789343358,
			"isDeleted": false,
			"id": "fZrTqFF9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -329.0791866354513,
			"y": 945.9080050286688,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 29.571502685546875,
			"height": 12.813020220134545,
			"seed": 418477342,
			"groupIds": [
				"6ikPIWUCCC_pPV0JeHy6s"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927706,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "2 - is",
			"rawText": "2 - is",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2 - is",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 355,
			"versionNonce": 1738351202,
			"isDeleted": false,
			"id": "TrSYMlaM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -328.60411885348674,
			"y": 959.1464966233673,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 54.33573913574219,
			"height": 12.813020220134545,
			"seed": 1825350622,
			"groupIds": [
				"n_iB3mrWGQY7PSBMCzEzS"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "3 - jumping",
			"rawText": "3 - jumping",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3 - jumping",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "freedraw",
			"version": 358,
			"versionNonce": 1174809790,
			"isDeleted": false,
			"id": "0jIMFqJLCBn0aknCMx3yF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -269.453113973036,
			"y": 949.0192771445604,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 45.22712928000597,
			"height": 0,
			"seed": 1248654658,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					45.22712928000597,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 642680354,
			"isDeleted": false,
			"id": "WricBsmaHh4LAffZNRERs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -227.44879371659533,
			"y": 943.0806618917044,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 8.079621591152915,
			"height": 12.696548214668837,
			"seed": 1996147742,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.9237194264649702,
					1.9237194264649133
				],
				[
					2.3084633117579756,
					2.3084633117579187
				],
				[
					2.693207197050981,
					2.693207197050924
				],
				[
					3.4626949676369634,
					2.693207197050924
				],
				[
					4.232182738222946,
					3.462694967636935
				],
				[
					5.001670508808957,
					3.8474388529299404
				],
				[
					5.386414394101934,
					4.616926623515951
				],
				[
					5.771158279394939,
					4.616926623515951
				],
				[
					5.771158279394939,
					5.001670508808957
				],
				[
					6.155902164687944,
					5.386414394101962
				],
				[
					6.540646049980921,
					5.771158279394854
				],
				[
					6.540646049980921,
					6.155902164687973
				],
				[
					6.540646049980921,
					6.5406460499808645
				],
				[
					6.540646049980921,
					6.92538993527387
				],
				[
					6.540646049980921,
					7.310133820566875
				],
				[
					6.155902164687944,
					7.310133820566875
				],
				[
					5.771158279394939,
					7.694877705859881
				],
				[
					5.386414394101934,
					8.079621591152886
				],
				[
					4.616926623515951,
					8.079621591152886
				],
				[
					3.847438852929969,
					8.464365476445892
				],
				[
					3.077951082343958,
					8.849109361738897
				],
				[
					2.3084633117579756,
					9.233853247031902
				],
				[
					1.5389755411719648,
					9.618597132324908
				],
				[
					0.7694877705859824,
					9.618597132324908
				],
				[
					-0.3847438852930054,
					10.388084902910919
				],
				[
					-0.7694877705860108,
					10.77282878820381
				],
				[
					-1.1542316558789878,
					11.157572673496816
				],
				[
					-1.5389755411719932,
					11.157572673496816
				],
				[
					-1.5389755411719932,
					11.542316558789821
				],
				[
					-1.5389755411719932,
					11.927060444082827
				],
				[
					-1.5389755411719932,
					12.311804329375832
				],
				[
					-1.1542316558789878,
					12.696548214668837
				],
				[
					-0.7694877705860108,
					12.696548214668837
				],
				[
					-0.7694877705860108,
					12.696548214668837
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 417,
			"versionNonce": 274588926,
			"isDeleted": false,
			"id": "TSXCSbdiQiiNlrrJv4pwa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -159.34912601973502,
			"y": 951.5450273681503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 143.89421309958053,
			"height": 99.6486662908859,
			"seed": 446003678,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.9237194264649702,
					0.3847438852930054
				],
				[
					3.0779510823439296,
					0.7694877705860108
				],
				[
					4.232182738222946,
					0.7694877705860108
				],
				[
					7.310133820566932,
					0.7694877705860108
				],
				[
					10.388084902910862,
					1.1542316558790162
				],
				[
					14.235523755840859,
					1.1542316558790162
				],
				[
					16.92873095289184,
					1.1542316558790162
				],
				[
					20.77616980582178,
					1.1542316558790162
				],
				[
					25.39309642933773,
					1.1542316558790162
				],
				[
					29.625279167560677,
					1.1542316558790162
				],
				[
					34.24220579107663,
					1.923719426465027
				],
				[
					38.474388529299574,
					1.923719426465027
				],
				[
					42.32182738222957,
					2.693207197050924
				],
				[
					46.16926623515951,
					2.693207197050924
				],
				[
					49.2472173175035,
					3.0779510823439296
				],
				[
					51.17093674396847,
					3.0779510823439296
				],
				[
					53.479400055726444,
					3.0779510823439296
				],
				[
					54.6336317116054,
					3.8474388529299404
				],
				[
					56.172607252777425,
					3.8474388529299404
				],
				[
					56.94209502336338,
					3.8474388529299404
				],
				[
					57.326838908656384,
					3.8474388529299404
				],
				[
					57.71158279394939,
					3.8474388529299404
				],
				[
					57.71158279394939,
					4.232182738222946
				],
				[
					57.71158279394939,
					4.616926623515951
				],
				[
					57.71158279394939,
					5.001670508808957
				],
				[
					57.71158279394939,
					5.386414394101962
				],
				[
					57.71158279394939,
					6.155902164687973
				],
				[
					57.71158279394939,
					6.925389935273984
				],
				[
					57.71158279394939,
					8.079621591152886
				],
				[
					57.71158279394939,
					9.233853247031902
				],
				[
					57.71158279394939,
					10.388084902910919
				],
				[
					57.71158279394939,
					11.542316558789821
				],
				[
					56.94209502336338,
					13.850779870547854
				],
				[
					56.94209502336338,
					15.774499297012767
				],
				[
					56.55735113807043,
					18.85245037935681
				],
				[
					56.55735113807043,
					20.39142592052883
				],
				[
					55.78786336748442,
					23.854120888165767
				],
				[
					55.78786336748442,
					26.932071970509696
				],
				[
					55.403119482191414,
					29.625279167560734
				],
				[
					55.403119482191414,
					31.933742479318653
				],
				[
					54.6336317116054,
					33.08797413519767
				],
				[
					54.248887826312455,
					34.62694967636969
				],
				[
					54.248887826312455,
					35.78118133224859
				],
				[
					53.86414394101945,
					36.550669102834604
				],
				[
					53.86414394101945,
					36.93541298812761
				],
				[
					53.86414394101945,
					37.70490075871362
				],
				[
					53.479400055726444,
					38.47438852929963
				],
				[
					53.479400055726444,
					39.24387629988553
				],
				[
					53.479400055726444,
					39.62862018517865
				],
				[
					53.09465617043344,
					40.01336407047154
				],
				[
					53.09465617043344,
					40.398107955764544
				],
				[
					52.70991228514043,
					40.398107955764544
				],
				[
					52.70991228514043,
					40.78285184105755
				],
				[
					52.70991228514043,
					41.167595726350555
				],
				[
					52.32516839984743,
					41.167595726350555
				],
				[
					51.94042451455448,
					41.167595726350555
				],
				[
					51.555680629261474,
					41.167595726350555
				],
				[
					51.17093674396847,
					41.167595726350555
				],
				[
					50.40144897338246,
					41.167595726350555
				],
				[
					49.2472173175035,
					41.167595726350555
				],
				[
					48.09298566162448,
					41.167595726350555
				],
				[
					46.93875400574552,
					41.167595726350555
				],
				[
					44.24554680869454,
					41.167595726350555
				],
				[
					41.167595726350555,
					41.167595726350555
				],
				[
					37.320156873420615,
					41.55233961164356
				],
				[
					33.47271802049062,
					41.55233961164356
				],
				[
					29.625279167560677,
					42.32182738222957
				],
				[
					25.777840314630737,
					42.32182738222957
				],
				[
					20.77616980582178,
					43.09131515281558
				],
				[
					16.92873095289184,
					43.09131515281558
				],
				[
					13.081292099961843,
					43.47605903810859
				],
				[
					9.233853247031902,
					43.47605903810859
				],
				[
					5.001670508808957,
					44.245546808694485
				],
				[
					1.1542316558789594,
					44.245546808694485
				],
				[
					-6.540646049980921,
					46.16926623515951
				],
				[
					-13.0812920999619,
					47.70824177633153
				],
				[
					-15.774499297012824,
					48.09298566162454
				],
				[
					-18.467706494063805,
					48.09298566162454
				],
				[
					-23.854120888165767,
					49.63196120279645
				],
				[
					-27.701559741095707,
					50.78619285867546
				],
				[
					-32.703230249904664,
					51.555680629261474
				],
				[
					-38.089644644006626,
					53.094656170433495
				],
				[
					-41.937083496936594,
					53.864143941019506
				],
				[
					-45.784522349866535,
					54.2488878263124
				],
				[
					-49.631961202796504,
					55.78786336748442
				],
				[
					-53.86414394101945,
					56.55735113807043
				],
				[
					-57.71158279394942,
					56.942095023363436
				],
				[
					-61.55902164687939,
					57.71158279394933
				],
				[
					-64.63697272922334,
					58.481070564535344
				],
				[
					-67.71492381156733,
					58.86581444982846
				],
				[
					-69.6386432380323,
					59.250558335121355
				],
				[
					-73.48608209096227,
					60.020046105707365
				],
				[
					-75.40980151742724,
					60.020046105707365
				],
				[
					-77.33352094389221,
					60.40478999100037
				],
				[
					-78.8724964850642,
					60.40478999100037
				],
				[
					-80.79621591152917,
					60.40478999100037
				],
				[
					-81.95044756740816,
					60.40478999100037
				],
				[
					-83.48942310858016,
					61.17427776158638
				],
				[
					-84.25891087916614,
					61.17427776158638
				],
				[
					-85.02839864975215,
					61.55902164687939
				],
				[
					-85.41314253504513,
					61.55902164687939
				],
				[
					-85.79788642033813,
					61.94376553217228
				],
				[
					-85.79788642033813,
					62.71325330275829
				],
				[
					-85.79788642033813,
					63.09799718805141
				],
				[
					-85.79788642033813,
					65.02171661451632
				],
				[
					-85.79788642033813,
					67.71492381156725
				],
				[
					-86.18263030563114,
					69.25389935273927
				],
				[
					-86.18263030563114,
					71.17761877920418
				],
				[
					-86.18263030563114,
					73.87082597625533
				],
				[
					-86.18263030563114,
					75.79454540272025
				],
				[
					-86.18263030563114,
					77.71826482918516
				],
				[
					-86.18263030563114,
					80.02672814094319
				],
				[
					-86.18263030563114,
					82.33519145270122
				],
				[
					-86.18263030563114,
					84.25891087916614
				],
				[
					-85.79788642033813,
					86.18263030563105
				],
				[
					-85.41314253504513,
					88.87583750268197
				],
				[
					-85.41314253504513,
					91.95378858502602
				],
				[
					-84.64365476445914,
					92.72327635561203
				],
				[
					-84.25891087916614,
					95.41648355266295
				],
				[
					-84.25891087916614,
					96.57071520854208
				],
				[
					-84.25891087916614,
					97.72494686442099
				],
				[
					-84.25891087916614,
					98.1096907497141
				],
				[
					-84.25891087916614,
					98.494434635007
				],
				[
					-84.25891087916614,
					98.87917852029989
				],
				[
					-84.64365476445914,
					99.6486662908859
				],
				[
					-85.02839864975215,
					99.6486662908859
				],
				[
					-85.41314253504513,
					99.6486662908859
				],
				[
					-85.79788642033813,
					99.6486662908859
				],
				[
					-86.18263030563114,
					99.6486662908859
				],
				[
					-85.79788642033813,
					99.26392240559301
				],
				[
					-85.02839864975215,
					99.26392240559301
				],
				[
					-84.25891087916614,
					98.87917852029989
				],
				[
					-83.87416699387316,
					98.87917852029989
				],
				[
					-83.10467922328715,
					98.87917852029989
				],
				[
					-80.4114720262362,
					98.494434635007
				],
				[
					-78.10300871447822,
					98.1096907497141
				],
				[
					-76.56403317330623,
					98.1096907497141
				],
				[
					-75.79454540272025,
					98.1096907497141
				],
				[
					-74.25556986154825,
					98.1096907497141
				],
				[
					-73.10133820566926,
					97.72494686442099
				],
				[
					-71.1776187792043,
					97.72494686442099
				],
				[
					-70.79287489391129,
					97.72494686442099
				],
				[
					-70.0233871233253,
					97.72494686442099
				],
				[
					-69.6386432380323,
					97.72494686442099
				],
				[
					-69.2538993527393,
					97.72494686442099
				],
				[
					-68.86915546744632,
					97.72494686442099
				],
				[
					-68.48441158215331,
					97.72494686442099
				],
				[
					-68.09966769686031,
					97.72494686442099
				],
				[
					-67.71492381156733,
					97.72494686442099
				],
				[
					-67.33017992627433,
					97.72494686442099
				],
				[
					-66.94543604098132,
					97.72494686442099
				],
				[
					-66.56069215568834,
					97.72494686442099
				],
				[
					-66.17594827039534,
					97.72494686442099
				],
				[
					-65.79120438510233,
					97.72494686442099
				],
				[
					-65.40646049980933,
					97.72494686442099
				],
				[
					-65.02171661451635,
					97.72494686442099
				],
				[
					-64.63697272922334,
					97.72494686442099
				],
				[
					-64.25222884393034,
					97.72494686442099
				],
				[
					-63.86748495863736,
					97.72494686442099
				],
				[
					-63.48274107334436,
					97.72494686442099
				],
				[
					-63.09799718805135,
					97.72494686442099
				],
				[
					-62.713253302758375,
					97.72494686442099
				],
				[
					-62.32850941746537,
					97.72494686442099
				],
				[
					-61.943765532172364,
					97.72494686442099
				],
				[
					-61.55902164687939,
					98.1096907497141
				],
				[
					-61.17427776158638,
					98.1096907497141
				],
				[
					-61.17427776158638,
					98.1096907497141
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 291,
			"versionNonce": 412971490,
			"isDeleted": false,
			"id": "XqddwTERt2begdCe7g_95",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -222.1874653349853,
			"y": 1043.6349110878036,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 4.444144494081371,
			"height": 11.38812026608366,
			"seed": 2021053214,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.555518061760182,
					0.5555180617602673
				],
				[
					0.8332770926402588,
					0.833277092640401
				],
				[
					1.1110361235203357,
					1.1110361235205346
				],
				[
					1.1110361235203357,
					1.3887951544006683
				],
				[
					1.3887951544004409,
					1.6665541852805745
				],
				[
					1.6665541852805177,
					1.9443132161607082
				],
				[
					1.9443132161605945,
					2.4998312779209755
				],
				[
					2.2220722470406997,
					2.7775903088008818
				],
				[
					2.4998312779207765,
					3.333108370561149
				],
				[
					2.7775903088008533,
					3.8886264323214164
				],
				[
					3.0553493396809586,
					4.444144494081456
				],
				[
					3.3331083705610354,
					4.72190352496159
				],
				[
					3.610867401441112,
					4.999662555841724
				],
				[
					3.888626432321189,
					5.27742158672163
				],
				[
					4.166385463201294,
					5.5551806176017635
				],
				[
					4.166385463201294,
					5.832939648481897
				],
				[
					3.888626432321189,
					5.832939648481897
				],
				[
					3.888626432321189,
					6.110698679362031
				],
				[
					3.610867401441112,
					6.3884577102421645
				],
				[
					3.3331083705610354,
					6.666216741122298
				],
				[
					3.0553493396809586,
					6.943975772002204
				],
				[
					2.7775903088008533,
					7.221734802882338
				],
				[
					2.4998312779207765,
					7.499493833762472
				],
				[
					2.2220722470406997,
					7.777252864642605
				],
				[
					1.9443132161605945,
					8.055011895522512
				],
				[
					1.6665541852805177,
					8.055011895522512
				],
				[
					1.6665541852805177,
					8.332770926402645
				],
				[
					1.3887951544004409,
					8.610529957282779
				],
				[
					1.1110361235203357,
					8.610529957282779
				],
				[
					0.8332770926402588,
					8.888288988162913
				],
				[
					0.555518061760182,
					8.888288988162913
				],
				[
					0.2777590308800768,
					9.166048019043046
				],
				[
					0.2777590308800768,
					9.443807049922953
				],
				[
					0,
					9.443807049922953
				],
				[
					0,
					9.721566080803086
				],
				[
					-0.2777590308800768,
					9.99932511168322
				],
				[
					-0.2777590308800768,
					10.277084142563353
				],
				[
					-0.2777590308800768,
					10.55484317344326
				],
				[
					-0.2777590308800768,
					10.832602204323393
				],
				[
					-0.2777590308800768,
					11.110361235203527
				],
				[
					-0.2777590308800768,
					11.38812026608366
				],
				[
					-0.2777590308800768,
					11.38812026608366
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 465,
			"versionNonce": 1603573054,
			"isDeleted": false,
			"id": "Wrd5DVht",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -117.23691008894804,
			"y": 1027.8264469296862,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.26153564453125,
			"height": 12.813020220134545,
			"seed": 931381470,
			"groupIds": [
				"yXRFpxmyHsVEOX5XlkEnj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "0 - O (the)",
			"rawText": "0 - O (the)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0 - O (the)",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 527,
			"versionNonce": 26797474,
			"isDeleted": false,
			"id": "YfWrPk6i",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -117.23691008894804,
			"y": 1060.6271878862663,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 76.42469787597656,
			"height": 12.813020220134545,
			"seed": 1820680670,
			"groupIds": [
				"xAHGjOsnpowHPxSQoFR76"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "1  - gato (cat)",
			"rawText": "1  - gato (cat)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  - gato (cat)",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 568,
			"versionNonce": 755711358,
			"isDeleted": false,
			"id": "hVUF8usj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -117.23691008894804,
			"y": 1076.6271466539615,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 65.12907409667969,
			"height": 12.813020220134545,
			"seed": 1199142430,
			"groupIds": [
				"8QnQR33hkKCYHae6UEKaK"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "2 - está (is)",
			"rawText": "2 - está (is)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2 - está (is)",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 469,
			"versionNonce": 1785717090,
			"isDeleted": false,
			"id": "rJw53mDJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -117.23691008894804,
			"y": 1044.4650104718705,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 103.88468933105469,
			"height": 12.813020220134545,
			"seed": 190906974,
			"groupIds": [
				"j0EM36uyu9cAI9whXQ7rA"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "3 - pulando (jumping)",
			"rawText": "3 - pulando (jumping)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3 - pulando (jumping)",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "freedraw",
			"version": 267,
			"versionNonce": 503504318,
			"isDeleted": false,
			"id": "bPtBAMPve3Lx7CNFA0NNx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -150.92983968539966,
			"y": 1056.1159278834689,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 11.75196582347678,
			"height": 0.8104804016190883,
			"seed": 609379842,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2157206024286324,
					0
				],
				[
					1.6209608032381766,
					0
				],
				[
					2.0262010040477207,
					0
				],
				[
					3.241921606476353,
					0
				],
				[
					3.6471618072858973,
					0
				],
				[
					4.0524020080954415,
					0
				],
				[
					4.86288240971453,
					0
				],
				[
					5.268122610524074,
					0.40524020080943046
				],
				[
					5.673362811333618,
					0.40524020080943046
				],
				[
					6.078603012143162,
					0.40524020080943046
				],
				[
					6.483843212952706,
					0.40524020080943046
				],
				[
					6.8890834137622505,
					0.40524020080943046
				],
				[
					7.294323614571795,
					0.40524020080943046
				],
				[
					7.699563815381339,
					0.40524020080943046
				],
				[
					8.104804016190883,
					0.40524020080943046
				],
				[
					8.510044217000427,
					0.40524020080943046
				],
				[
					8.915284417809971,
					0.8104804016190883
				],
				[
					9.320524618619515,
					0.8104804016190883
				],
				[
					9.72576481942906,
					0.8104804016190883
				],
				[
					10.131005020238604,
					0.8104804016190883
				],
				[
					10.536245221048148,
					0.8104804016190883
				],
				[
					10.941485421857692,
					0.8104804016190883
				],
				[
					11.346725622667236,
					0.8104804016190883
				],
				[
					11.75196582347678,
					0.8104804016190883
				],
				[
					11.75196582347678,
					0.8104804016190883
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 275,
			"versionNonce": 1584489762,
			"isDeleted": false,
			"id": "cXLByC_PHvycspPXcG89C",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -139.98835426354196,
			"y": 1051.6582856745638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 4.457642208904929,
			"height": 10.941485421857806,
			"seed": 478282334,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2157206024286324,
					0.8104804016190883
				],
				[
					1.6209608032381766,
					1.2157206024287461
				],
				[
					2.0262010040477207,
					1.6209608032381766
				],
				[
					2.431441204857208,
					1.6209608032381766
				],
				[
					2.431441204857208,
					2.0262010040478344
				],
				[
					2.836681405666752,
					2.431441204857265
				],
				[
					3.2419216064762963,
					2.431441204857265
				],
				[
					3.6471618072858405,
					2.8366814056669227
				],
				[
					4.052402008095385,
					3.241921606476353
				],
				[
					4.052402008095385,
					3.647161807286011
				],
				[
					4.052402008095385,
					4.0524020080954415
				],
				[
					4.052402008095385,
					4.457642208905099
				],
				[
					4.052402008095385,
					4.86288240971453
				],
				[
					4.457642208904929,
					5.268122610524188
				],
				[
					4.457642208904929,
					5.673362811333618
				],
				[
					4.457642208904929,
					6.078603012143276
				],
				[
					4.457642208904929,
					6.483843212952706
				],
				[
					4.457642208904929,
					6.889083413762364
				],
				[
					4.457642208904929,
					7.6995638153814525
				],
				[
					4.052402008095385,
					8.104804016190883
				],
				[
					3.6471618072858405,
					8.51004421700054
				],
				[
					3.2419216064762963,
					8.915284417809971
				],
				[
					3.2419216064762963,
					9.320524618619629
				],
				[
					2.836681405666752,
					9.320524618619629
				],
				[
					2.431441204857208,
					9.72576481942906
				],
				[
					2.0262010040477207,
					10.131005020238717
				],
				[
					1.6209608032381766,
					10.131005020238717
				],
				[
					1.6209608032381766,
					10.536245221048148
				],
				[
					1.2157206024286324,
					10.536245221048148
				],
				[
					0.8104804016190883,
					10.536245221048148
				],
				[
					0.8104804016190883,
					10.941485421857806
				],
				[
					0.40524020080954415,
					10.941485421857806
				],
				[
					0.40524020080954415,
					10.941485421857806
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 919,
			"versionNonce": 127694334,
			"isDeleted": false,
			"id": "kCDVZp9x",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -325.296088853445,
			"y": 1046.3815583533599,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 37.976593017578125,
			"height": 12.813020220134545,
			"seed": 175857410,
			"groupIds": [
				"DUVLHRH8CiR6qzVj_y0Z6"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "0 - the",
			"rawText": "0 - the",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0 - the",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 985,
			"versionNonce": 655126754,
			"isDeleted": false,
			"id": "9thRwEGR",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -325.296088853445,
			"y": 1079.1822993099402,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 40.13935852050781,
			"height": 12.813020220134545,
			"seed": 394014402,
			"groupIds": [
				"EBpw44xtjLIr1Ms-E95Tq"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "1  - cat",
			"rawText": "1  - cat",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  - cat",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 1025,
			"versionNonce": 1926825534,
			"isDeleted": false,
			"id": "8rBDStJx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -325.296088853445,
			"y": 1095.1822580776354,
			"strokeColor": "#e03131",
			"backgroundColor": "#a5d8ff",
			"width": 29.571502685546875,
			"height": 12.813020220134545,
			"seed": 860685954,
			"groupIds": [
				"sTSnMSkgOYUDgwPc-HrN7"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "2 - is",
			"rawText": "2 - is",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2 - is",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 1013,
			"versionNonce": 131073186,
			"isDeleted": false,
			"id": "mvE0MQ1M",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -325.296088853445,
			"y": 1063.0201218955447,
			"strokeColor": "#e03131",
			"backgroundColor": "#a5d8ff",
			"width": 47.84742736816406,
			"height": 12.813020220134545,
			"seed": 380429890,
			"groupIds": [
				"hv-JaxNKegYRwnjiiSmyB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "3 - juping",
			"rawText": "3 - juping",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3 - juping",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 546934398,
			"isDeleted": false,
			"id": "vkoDuLNO-sIkltRDHN7Bl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -268.449497920167,
			"y": 1073.1360163174695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 49.84454469957376,
			"height": 2.0262010040478344,
			"seed": 1373921374,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.8104804016190883,
					0
				],
				[
					1.2157206024286324,
					0
				],
				[
					1.6209608032381766,
					0
				],
				[
					2.0262010040477207,
					0
				],
				[
					2.431441204857265,
					0
				],
				[
					4.0524020080954415,
					0
				],
				[
					6.483843212952706,
					0.40524020080965784
				],
				[
					7.294323614571795,
					0.40524020080965784
				],
				[
					8.510044217000427,
					0.40524020080965784
				],
				[
					10.131005020238604,
					0.8104804016190883
				],
				[
					11.75196582347678,
					0.8104804016190883
				],
				[
					14.993887429953105,
					0.8104804016190883
				],
				[
					17.42532863481034,
					0.8104804016190883
				],
				[
					20.667250241286695,
					1.2157206024287461
				],
				[
					23.503931646953475,
					1.2157206024287461
				],
				[
					26.340613052620284,
					1.2157206024287461
				],
				[
					28.77205425747755,
					1.2157206024287461
				],
				[
					30.79825526152524,
					1.2157206024287461
				],
				[
					32.82445626557296,
					2.0262010040478344
				],
				[
					35.25589747043023,
					2.0262010040478344
				],
				[
					36.47161807285886,
					2.0262010040478344
				],
				[
					37.687338675287464,
					2.0262010040478344
				],
				[
					39.30829947852564,
					2.0262010040478344
				],
				[
					40.52402008095427,
					2.0262010040478344
				],
				[
					41.33450048257336,
					2.0262010040478344
				],
				[
					41.739740683382905,
					2.0262010040478344
				],
				[
					42.14498088419245,
					2.0262010040478344
				],
				[
					42.55022108500199,
					2.0262010040478344
				],
				[
					42.95546128581154,
					2.0262010040478344
				],
				[
					43.36070148662108,
					2.0262010040478344
				],
				[
					43.765941687430626,
					2.0262010040478344
				],
				[
					44.17118188824017,
					2.0262010040478344
				],
				[
					44.576422089049714,
					2.0262010040478344
				],
				[
					44.98166228985923,
					2.0262010040478344
				],
				[
					45.79214269147832,
					1.6209608032381766
				],
				[
					46.19738289228786,
					1.6209608032381766
				],
				[
					46.60262309309741,
					1.6209608032381766
				],
				[
					47.413103494716495,
					1.6209608032381766
				],
				[
					47.413103494716495,
					1.2157206024287461
				],
				[
					48.22358389633558,
					1.2157206024287461
				],
				[
					48.62882409714513,
					1.2157206024287461
				],
				[
					49.03406429795467,
					1.2157206024287461
				],
				[
					49.439304498764216,
					1.2157206024287461
				],
				[
					49.439304498764216,
					0.8104804016190883
				],
				[
					49.84454469957376,
					0.8104804016190883
				],
				[
					49.84454469957376,
					0.8104804016190883
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 274,
			"versionNonce": 2053840994,
			"isDeleted": false,
			"id": "jHl7zfuUQwZzFJmkYyEHr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -222.25211502787914,
			"y": 1069.8940947109932,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 6.078603012143162,
			"height": 9.72576481942906,
			"seed": 8222686,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40524020080954415,
					0
				],
				[
					0.8104804016190883,
					0
				],
				[
					1.2157206024286324,
					0
				],
				[
					1.6209608032381766,
					0.40524020080965784
				],
				[
					2.431441204857265,
					0.40524020080965784
				],
				[
					2.836681405666809,
					0.8104804016193157
				],
				[
					3.6471618072858973,
					1.2157206024287461
				],
				[
					4.0524020080954415,
					1.6209608032381766
				],
				[
					4.457642208904986,
					1.6209608032381766
				],
				[
					4.86288240971453,
					2.0262010040478344
				],
				[
					4.86288240971453,
					2.431441204857265
				],
				[
					5.268122610524074,
					2.431441204857265
				],
				[
					5.268122610524074,
					2.8366814056669227
				],
				[
					5.673362811333618,
					2.8366814056669227
				],
				[
					5.673362811333618,
					3.241921606476353
				],
				[
					6.078603012143162,
					3.647161807286011
				],
				[
					6.078603012143162,
					4.0524020080954415
				],
				[
					6.078603012143162,
					4.457642208905099
				],
				[
					6.078603012143162,
					5.268122610524188
				],
				[
					6.078603012143162,
					5.673362811333618
				],
				[
					6.078603012143162,
					6.078603012143276
				],
				[
					6.078603012143162,
					6.483843212952706
				],
				[
					5.673362811333618,
					6.889083413762364
				],
				[
					5.268122610524074,
					7.294323614571795
				],
				[
					4.86288240971453,
					7.6995638153814525
				],
				[
					4.457642208904986,
					7.6995638153814525
				],
				[
					4.0524020080954415,
					8.104804016190883
				],
				[
					3.6471618072858973,
					8.104804016190883
				],
				[
					3.241921606476353,
					8.51004421700054
				],
				[
					2.836681405666809,
					8.915284417809971
				],
				[
					2.431441204857265,
					8.915284417809971
				],
				[
					2.431441204857265,
					9.320524618619629
				],
				[
					2.0262010040477207,
					9.320524618619629
				],
				[
					1.6209608032381766,
					9.320524618619629
				],
				[
					1.6209608032381766,
					9.72576481942906
				],
				[
					1.6209608032381766,
					9.72576481942906
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 501,
			"versionNonce": 228527806,
			"isDeleted": false,
			"id": "smqXMEUd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -192.82048442629156,
			"y": 1073.1937686850454,
			"strokeColor": "#e03131",
			"backgroundColor": "#a5d8ff",
			"width": 18.199020385742188,
			"height": 18.011260980729645,
			"seed": 1023164894,
			"groupIds": [
				"acR0JI5z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 7.204504392291858,
			"fontFamily": 1,
			"text": "Mask\navoid",
			"rawText": "Mask\navoid",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Mask\navoid",
			"lineHeight": 1.25,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 307,
			"versionNonce": 1789707298,
			"isDeleted": false,
			"id": "cJeCoXrZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -344.411299677866,
			"y": 877.5615611315468,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 256.62457275390625,
			"height": 20,
			"seed": 220728990,
			"groupIds": [
				"acR0JI5z"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Translation en-pt simple example",
			"rawText": "Translation en-pt simple example",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Translation en-pt simple example",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 507,
			"versionNonce": 1988790014,
			"isDeleted": false,
			"id": "4dmLmMNj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -329.0791866354513,
			"y": 921.2595029737362,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 37.976593017578125,
			"height": 12.813020220134545,
			"seed": 1988345438,
			"groupIds": [
				"0lO8GuNdqQ8m70D0xMDSK"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 10.250416176107636,
			"fontFamily": 1,
			"text": "0 - the",
			"rawText": "0 - the",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0 - the",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 1921249250,
			"isDeleted": false,
			"id": "z1xFW4sp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -190.72406359105895,
			"y": 1045.3642353110906,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 12.480026245117188,
			"height": 20,
			"seed": 1207478146,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "D",
			"rawText": "D",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "D",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1541207870,
			"isDeleted": false,
			"id": "oJf7dMso",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 50,
			"angle": 0,
			"x": 390.4807235565814,
			"y": -1178.2848197701232,
			"strokeColor": "transparent",
			"backgroundColor": "#ffec99",
			"width": 37.15208435058594,
			"height": 20,
			"seed": 1822142510,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "sdsa",
			"rawText": "sdsa",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sdsa",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 231,
			"versionNonce": 369075106,
			"isDeleted": false,
			"id": "j0Rfcise",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 384.69520907698785,
			"y": -1176.1809963229985,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 91.69960021972656,
			"height": 54.767795886813445,
			"seed": 1441363698,
			"groupIds": [
				"HA5Tsemc"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1694624927707,
			"link": null,
			"locked": false,
			"fontSize": 8.76284734189015,
			"fontFamily": 1,
			"text": "\"Query and keys\nwill \"fire\" weights\nof value based\non their compatibility\"\n",
			"rawText": "\"Query and keys\nwill \"fire\" weights\nof value based\non their compatibility\"\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\"Query and keys\nwill \"fire\" weights\nof value based\non their compatibility\"\n",
			"lineHeight": 1.25,
			"baseline": 51
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1971c2",
		"currentItemBackgroundColor": "#ffec99",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 4,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "triangle",
		"scrollX": 375.86289938112435,
		"scrollY": 1170.4367121241976,
		"zoom": {
			"value": 1.35221178820397
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%
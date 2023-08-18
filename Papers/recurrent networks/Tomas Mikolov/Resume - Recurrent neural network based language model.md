---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Input (t) ^N01L1nBo

Context(t) ^dUL4kxbL

Output (t) ^k3oIJVeV

Context(t-1) ^eUWt8R3g

Fig 1: Elman Network ^R7dU7ftV

Abstract ^4zu1qCv6

Recurrent neural network based language model ^j8YLSHuJ

New technique obtain 50% reduction of 
perplexity using mixture of several RNN 
LM. It is superior to standard n-gram
techniques. ^eH0JkTtS

Introduction ^rviWJ9D6

Words ^Ks2qAzC9

Context ^k4SW7KdX

Limited ^jcJZp0kO

1 ^KVbPTI36

Parse trees are graphical representations of sentences
taking account the structure and relationship of words as
noums, verbs, objects and etc. It is different of a linear 
representation of words. ^oE9FZDa1

2 ^ixJCOshg

Word and sentence characteristics:
    - Morphology: Understanding the ways words can change
                 based on basic units called morphemes. 
    - Syntax: Rules to organize words in a meaningful way.
    - Semantics: Meaning behind words, sentences and paragraphs. ^fDEOUyE9

    Describing Language models by atomic
symbols (words) such as parse trees or
consider how words can be represented,
the way they are organized and the me-
aning behind senteces and paragraphs. ^TyFfyY5i

    If language models are measure based
on context, or the capacity of predict the 
next word, it can be said there is a progress. ^p2cbcWgE

    If analysed in industrial practical 
applications the progress is limited over 
simple baselines modeling. ^xpFuu8Ix

Model description ^oNbnH6t8

fixed-context ^BIeAO3GZ

4 ^X0ZjIUOS

ad hoc
"case-by-case" ^W0mfQgAh

1:  ^oSY6lIAu

3 ^JO5gGVPD

Perpexity ^tL6ldUfY

Long-term ^M3aNXNIl

Elman ^oA2aqNPf

Config ^8SPA3qwW

Train ^pxUSmmaZ

Observations ^9L673kkS

Loss ^RIeFPnNV

? ^6xspAHTN

BPTT ^BA5l7zrN

Tuning ^8UkUxhDz

s(t-1) ^H2NTR6cW

s(t) ^uRS2IdY4

y(t) ^Zou9mqa0

w(t) ^yob9HNbl

It means that the fixed-length context need
to be specified case-by-case for each training 
instance, which does not seem to fit for a longer
sentence or generalization.
 ^IvrArjfc

For a list with n words the current word is 1 and others are 0. 
Example:
if our vocabulary consists of ["cat", "dog", "bird"], and the current 
word at time t is "dog," then x(t) would be [0, 1, 0] since it 
represents the second element ("dog") out of three possible 
choices ("cat," "dog," or "bird") ^6gq5EA7j

5 ^rRlbbPwo

DOUBTS ^5HXwXZxF

https://pabloinsente.github.io/the-recurrent-net ^Xvrd15ED

References: ^gKlN9RM4

Perplexity: Metric that quantifies the level of uncertainty, 
low indicates good predictions. ^J0JqeQeX

Fig 1: Detailed Elman Network ^MOocAEYH

w(t) ^BVKTHSOM

sj(t) ^q4ITOhX7

sj(t-1) ^bgCh8Mvt

yk(t) ^AMr5Zvkx

values of context ^BeRNJzke

hidden weights ^hrYvIYC3

output weights ^oxQBWvhH

+1 ^x9h16OzL

Activations are copied
from hidden layers to
context layers one-to-one
fully distributed [7] ^oBkUyOYk

* Stopped Here ^oY25Aoii

2:  ^PmAzcqVM

3:  ^AxmawdcK

4:  ^kjeJeNfL

5:  ^pS1kK2tV


# Embedded files
04bee493968143f9b33b68b2b3b706f179e4253c: [[mikolov_interspeech2010_IS100722.pdf#page=1]]
037204c6a155913fafb049dcc02ecb90cbc82c98: [[mikolov_interspeech2010_IS100722.pdf#page=2]]
61c1d4ef1ad863cb85a318fa0144f531cfa920ee: [[mikolov_interspeech2010_IS100722.pdf#page=3]]
772de5f9f513ce05c63cfcf6bcc0d46121136d0c: [[mikolov_interspeech2010_IS100722.pdf#page=4]]

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
			"version": 279,
			"versionNonce": 826647536,
			"isDeleted": false,
			"id": "Ejqmry3tJifNhJK6rr9Uc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 282.95048644399077,
			"y": -1607.4442167722905,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 53.87365001614455,
			"height": 20.68666864158263,
			"seed": 2098169002,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 168,
			"versionNonce": 709546768,
			"isDeleted": false,
			"id": "VyFj3u7I2yMyK7nTXjE3e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 82.55132174764549,
			"y": -1677.4127051057546,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 62.86210745713771,
			"height": 18.79436181189999,
			"seed": 1580215338,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 153,
			"versionNonce": 315336176,
			"isDeleted": false,
			"id": "Y991Wfolz4MB73iuWVMOq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": 62.09863389351881,
			"y": -1801.7871582727405,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 65.22749099424118,
			"height": 18.79436181189999,
			"seed": 1062324342,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 210,
			"versionNonce": 228454672,
			"isDeleted": false,
			"id": "TiJrPzV8aSxUypeYZO8z8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 41.12341088822916,
			"y": -2122.116092774719,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 719.9528940420531,
			"height": 1011.5146344356376,
			"seed": 1326014326,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 103,
			"versionNonce": 406939632,
			"isDeleted": false,
			"id": "Ck2UXGtq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702,
			"y": -2129.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714,
			"height": 1010,
			"seed": 11141,
			"groupIds": [
				"pVoTzIqh"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": true
		},
		{
			"type": "image",
			"version": 103,
			"versionNonce": 350048016,
			"isDeleted": false,
			"id": "ADHDi6Ek",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702.0354244857785,
			"y": -2128.9655197048633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714.0708489715571,
			"height": 1009.8997894097264,
			"seed": 68632,
			"groupIds": [
				"pVoTzIqh"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": true,
			"status": "pending",
			"fileId": "04bee493968143f9b33b68b2b3b706f179e4253c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 103,
			"versionNonce": 766437872,
			"isDeleted": false,
			"id": "73l4kpEH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702,
			"y": -1099.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714,
			"height": 1010,
			"seed": 10085,
			"groupIds": [
				"p7j0siD8"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": true
		},
		{
			"type": "image",
			"version": 103,
			"versionNonce": 2021715216,
			"isDeleted": false,
			"id": "Qtq004PA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702.0354244857785,
			"y": -1098.9655197048633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714.0708489715571,
			"height": 1009.8997894097264,
			"seed": 56819,
			"groupIds": [
				"p7j0siD8"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704464,
			"link": null,
			"locked": true,
			"status": "pending",
			"fileId": "037204c6a155913fafb049dcc02ecb90cbc82c98",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 103,
			"versionNonce": 2115775472,
			"isDeleted": false,
			"id": "C1CVIASU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702,
			"y": -68.015625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714,
			"height": 1010,
			"seed": 5956,
			"groupIds": [
				"Y4PlizSl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": true
		},
		{
			"type": "image",
			"version": 103,
			"versionNonce": 570477328,
			"isDeleted": false,
			"id": "8NmIEL9v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702.0354244857785,
			"y": -67.9655197048632,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714.0708489715571,
			"height": 1009.8997894097264,
			"seed": 19092,
			"groupIds": [
				"Y4PlizSl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": true,
			"status": "pending",
			"fileId": "61c1d4ef1ad863cb85a318fa0144f531cfa920ee",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 103,
			"versionNonce": 328281584,
			"isDeleted": false,
			"id": "sfdaByEQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702,
			"y": 961.984375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714,
			"height": 1010,
			"seed": 21467,
			"groupIds": [
				"xpKEIPps"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": true
		},
		{
			"type": "image",
			"version": 103,
			"versionNonce": 198502672,
			"isDeleted": false,
			"id": "b8ejneIc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -702.0354244857785,
			"y": 962.0344802951367,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 714.0708489715571,
			"height": 1009.8997894097264,
			"seed": 38039,
			"groupIds": [
				"xpKEIPps"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": true,
			"status": "pending",
			"fileId": "772de5f9f513ce05c63cfcf6bcc0d46121136d0c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "freedraw",
			"version": 132,
			"versionNonce": 1997926384,
			"isDeleted": false,
			"id": "vy3n_tIZww7wX0ygvW7il",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -227.5366705457107,
			"y": -1691.819847933029,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.126100225108075,
			"height": 5.9384168542567295,
			"seed": 2140150250,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.593841685425673,
					0
				],
				[
					-1.187683370851346,
					0.5938416854255593
				],
				[
					-1.7815250562770188,
					1.187683370851346
				],
				[
					-2.375366741702692,
					1.187683370851346
				],
				[
					-2.375366741702692,
					1.7815250562769052
				],
				[
					-2.375366741702692,
					2.375366741702692
				],
				[
					-2.9692084271283647,
					2.969208427128251
				],
				[
					-2.9692084271283647,
					3.5630501125540377
				],
				[
					-3.5630501125540377,
					3.5630501125540377
				],
				[
					-3.5630501125540377,
					4.156891797979597
				],
				[
					-3.5630501125540377,
					4.750733483405384
				],
				[
					-2.9692084271283647,
					4.750733483405384
				],
				[
					-1.7815250562770188,
					4.750733483405384
				],
				[
					-1.187683370851346,
					5.344575168830943
				],
				[
					0,
					5.344575168830943
				],
				[
					1.187683370851346,
					5.344575168830943
				],
				[
					1.7815250562770188,
					5.344575168830943
				],
				[
					2.375366741702692,
					5.9384168542567295
				],
				[
					2.9692084271283647,
					5.9384168542567295
				],
				[
					3.5630501125540377,
					5.9384168542567295
				],
				[
					3.5630501125540377,
					5.9384168542567295
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 102,
			"versionNonce": 561334032,
			"isDeleted": false,
			"id": "YaglafODTAsHyjJgDG9Qc",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -202.46128722812654,
			"y": -1789.4126086130054,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.943425752807883,
			"height": 4.325497533706994,
			"seed": 912648630,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.20597607303366772,
					0
				],
				[
					0,
					0
				],
				[
					0.6179282191009747,
					-0.20597607303375298
				],
				[
					1.2358564382019495,
					-0.41195214606750596
				],
				[
					2.2657368033702596,
					-0.8239042921347846
				],
				[
					3.29561716853857,
					-1.0298803651683102
				],
				[
					3.9135453876395445,
					-1.2358564382020631
				],
				[
					4.119521460673212,
					-1.2358564382020631
				],
				[
					4.32549753370688,
					-1.4418325112358161
				],
				[
					4.32549753370688,
					-1.2358564382020631
				],
				[
					4.32549753370688,
					-1.0298803651683102
				],
				[
					4.32549753370688,
					-0.41195214606750596
				],
				[
					4.32549753370688,
					0.2059760730335256
				],
				[
					4.32549753370688,
					1.0298803651683102
				],
				[
					4.32549753370688,
					1.6478085842691144
				],
				[
					4.32549753370688,
					2.265736803370146
				],
				[
					4.531473606740519,
					2.6776889494374245
				],
				[
					4.737449679774215,
					2.8836650224711775
				],
				[
					4.737449679774215,
					2.8836650224711775
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "rectangle",
			"version": 332,
			"versionNonce": 1353871856,
			"isDeleted": false,
			"id": "1S45ou9lgVBBT9wUEAPpS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 519.909431874475,
			"y": -1928.1660716919912,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 17.14527327367159,
			"height": 113.15880360623237,
			"seed": 47077930,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 419,
			"versionNonce": 525985040,
			"isDeleted": false,
			"id": "CjIojPd3ruCaQvvE_XLhv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 521.2665029016359,
			"y": -1795.1677375833679,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.226353668260943,
			"height": 49.9662249689859,
			"seed": 1113319990,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 448,
			"versionNonce": 124695536,
			"isDeleted": false,
			"id": "y4iRxneND9DS70NXo4Qch",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 573.192187673327,
			"y": -1899.264039602088,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 14.206083569613584,
			"height": 52.4155497223676,
			"seed": 486133942,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 513,
			"versionNonce": 1793329136,
			"isDeleted": false,
			"id": "XsH1VwnkAm_dAMRrEiGZC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 625.1178724450181,
			"y": -1925.961679413948,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd8a8",
			"width": 17.635138224347916,
			"height": 109.72974895149814,
			"seed": 486353962,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1692386708448,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 332,
			"versionNonce": 1632810480,
			"isDeleted": false,
			"id": "N01L1nBo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 495.99559357905116,
			"y": -1947.8477759619664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 71.296142578125,
			"height": 20,
			"seed": 978088182,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Input (t)",
			"rawText": "Input (t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Input (t)",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 355,
			"versionNonce": 449831184,
			"isDeleted": false,
			"id": "dUL4kxbL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 539.8411381014868,
			"y": -1920.9930925409476,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.55216979980469,
			"height": 20,
			"seed": 784793258,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Context(t)",
			"rawText": "Context(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Context(t)",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 385,
			"versionNonce": 593917936,
			"isDeleted": false,
			"id": "k3oIJVeV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 598.6106795457091,
			"y": -1947.8477759619664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.84817504882812,
			"height": 20,
			"seed": 1098322550,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Output (t)",
			"rawText": "Output (t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Output (t)",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 360,
			"versionNonce": 105987856,
			"isDeleted": false,
			"id": "eUWt8R3g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 495.3800139901863,
			"y": -1742.4353301898752,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 94.46420288085938,
			"height": 20,
			"seed": 186105782,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Context(t-1)",
			"rawText": "Context(t-1)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Context(t-1)",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "freedraw",
			"version": 232,
			"versionNonce": 833747440,
			"isDeleted": false,
			"id": "N2Gmqix0SQFSrmWGTRWYw",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 488.2510176343196,
			"y": -1909.4299677249269,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 1324098678,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 219,
			"versionNonce": 1979112720,
			"isDeleted": false,
			"id": "wLjhYJ3ufjAnhyT28i2H7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 511.1342678099535,
			"y": -1913.0431124895006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 1239569142,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 248,
			"versionNonce": 792542192,
			"isDeleted": false,
			"id": "S2bGJ8mP-fj3n_OoLvxN1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 541.4445377794333,
			"y": -1874.7036319320791,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 59929590,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 235,
			"versionNonce": 1530444560,
			"isDeleted": false,
			"id": "So9J4EHD5C4y45ZeKQjZu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 564.3277879550672,
			"y": -1878.3167766966526,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 1682736438,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 247,
			"versionNonce": 504380912,
			"isDeleted": false,
			"id": "xVNjWwB8-CSnnKc7tF8C8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 592.028564483466,
			"y": -1873.499250343888,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 380992810,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 234,
			"versionNonce": 948885776,
			"isDeleted": false,
			"id": "0KTTYa0Y8yLP9cma9oM5Y",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.9118146590998,
			"y": -1877.1123951084614,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 1176520682,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 251,
			"versionNonce": 2134048752,
			"isDeleted": false,
			"id": "KyPRZkwScHfFczoxJmD1D",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 644.619893834484,
			"y": -1911.638000636611,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 154998390,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 242,
			"versionNonce": 24196880,
			"isDeleted": false,
			"id": "0MLaLwiuSAkbJZYvPaFZ_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 666.7002229513236,
			"y": -1915.2511454011844,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 1367267254,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 292,
			"versionNonce": 1923973616,
			"isDeleted": false,
			"id": "oYYwQchJ5hLVf-ChVlnz3",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 645.4228148932782,
			"y": -1893.9737373431399,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 1907173354,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 283,
			"versionNonce": 2052576528,
			"isDeleted": false,
			"id": "2n_FyzP1FWAt3xANlzxWp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.5031440101179,
			"y": -1897.5868821077129,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 575969962,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 270,
			"versionNonce": 1468515312,
			"isDeleted": false,
			"id": "fEiFH4SvOtgVoU4NrP6dK",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 644.2184333050868,
			"y": -1876.3094740496683,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 612109610,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 261,
			"versionNonce": 414888720,
			"isDeleted": false,
			"id": "ibQi67UmzlKAW5UPUwg3N",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 666.2987624219265,
			"y": -1879.9226188142413,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 2090129386,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 271,
			"versionNonce": 1808385520,
			"isDeleted": false,
			"id": "wsuHeNOy6R02T4DWrBE6X",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 645.8242754226753,
			"y": -1858.6452107561968,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 692671030,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 262,
			"versionNonce": 1662112016,
			"isDeleted": false,
			"id": "EoY724FtTGTWrJBkp_vi2",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.9046045395149,
			"y": -1862.2583555207698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 1678613366,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 264,
			"versionNonce": 1820035056,
			"isDeleted": false,
			"id": "GayLQWmA0ghG2xYJaAGPT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 645.4228148932782,
			"y": -1840.9809474627252,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 1707318058,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 255,
			"versionNonce": 1356148496,
			"isDeleted": false,
			"id": "NFRkLqcsm4XQKBmMTRXFe",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 667.5031440101178,
			"y": -1844.5940922272982,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 163227114,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 900008432,
			"isDeleted": false,
			"id": "3LvHG41-HU-I9sAHebvJm",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 643.8169727756898,
			"y": -1823.3166841692528,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.89785546960465,
			"height": 0.8029210587942543,
			"seed": 1521871274,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.40146052939709875,
					0
				],
				[
					0.8029210587941691,
					0
				],
				[
					1.6058421175883382,
					-0.4014605293971272
				],
				[
					2.4087631763825073,
					-0.4014605293971272
				],
				[
					3.2116842351766763,
					-0.4014605293971272
				],
				[
					4.416065823367944,
					-0.4014605293971272
				],
				[
					5.218986882162113,
					-0.4014605293971272
				],
				[
					6.423368470353381,
					-0.4014605293971272
				],
				[
					7.627750058544592,
					-0.4014605293971272
				],
				[
					8.83213164673586,
					-0.4014605293971272
				],
				[
					10.437973764324198,
					-0.4014605293971272
				],
				[
					11.642355352515466,
					0
				],
				[
					12.846736940706677,
					0
				],
				[
					13.649657999500874,
					0
				],
				[
					14.452579058295015,
					0
				],
				[
					15.255500117089213,
					0
				],
				[
					16.058421175883353,
					0.4014605293971272
				],
				[
					16.86134223467755,
					0.4014605293971272
				],
				[
					17.66426329347169,
					0.4014605293971272
				],
				[
					18.46718435226589,
					0.4014605293971272
				],
				[
					19.27010541106003,
					0.4014605293971272
				],
				[
					20.073026469854227,
					0.4014605293971272
				],
				[
					20.474486999251297,
					0.4014605293971272
				],
				[
					21.277408058045495,
					0.4014605293971272
				],
				[
					22.080329116839636,
					0.4014605293971272
				],
				[
					22.883250175633833,
					0.4014605293971272
				],
				[
					23.284710705030903,
					0.4014605293971272
				],
				[
					24.087631763825044,
					0.4014605293971272
				],
				[
					24.89055282261924,
					0.4014605293971272
				],
				[
					25.693473881413382,
					0.4014605293971272
				],
				[
					26.09493441081051,
					0.4014605293971272
				],
				[
					26.49639494020758,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				],
				[
					26.89785546960465,
					0.4014605293971272
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 264,
			"versionNonce": 712822032,
			"isDeleted": false,
			"id": "waI5DGf54hacdtM2ZplPD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 665.8973018925295,
			"y": -1826.9298289338267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.620447411559212,
			"height": 7.627750058544507,
			"seed": 2019501162,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4014605293971272
				],
				[
					0.40146052939707033,
					0.802921058794027
				],
				[
					0.8029210587941407,
					1.6058421175882813
				],
				[
					1.6058421175883382,
					2.0073026469854085
				],
				[
					2.0073026469854085,
					2.8102237057794355
				],
				[
					2.408763176382479,
					3.2116842351765627
				],
				[
					2.810223705779549,
					3.61314476457369
				],
				[
					3.2116842351766763,
					4.014605293970817
				],
				[
					3.6131447645737467,
					4.416065823367944
				],
				[
					4.014605293970817,
					4.817526352765071
				],
				[
					4.416065823367887,
					5.218986882161971
				],
				[
					4.8175263527650145,
					5.218986882161971
				],
				[
					4.416065823367887,
					5.620447411559098
				],
				[
					3.6131447645737467,
					5.620447411559098
				],
				[
					2.810223705779549,
					6.0219079409562255
				],
				[
					1.6058421175883382,
					6.0219079409562255
				],
				[
					0.8029210587941407,
					6.423368470353353
				],
				[
					0,
					6.82482899975048
				],
				[
					-0.4014605293971272,
					7.226289529147607
				],
				[
					-0.8029210587941975,
					7.627750058544507
				],
				[
					-0.8029210587941975,
					7.627750058544507
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 360,
			"versionNonce": 1649298416,
			"isDeleted": false,
			"id": "_9np542nr9y-slSB5rQyh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 582.6446584282588,
			"y": -1860.8401401865717,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 66.7565290453301,
			"height": 100.97663791399988,
			"seed": 1275304502,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					5.381823167016828,
					0
				],
				[
					6.049388457470128,
					0.5803255052527617
				],
				[
					7.384519038376729,
					1.7409765157585078
				],
				[
					8.71964961928333,
					2.9016275262642535
				],
				[
					9.387214909736631,
					3.4819530315170155
				],
				[
					10.054780200189933,
					4.642604042022984
				],
				[
					11.389910781096532,
					5.803255052528507
				],
				[
					12.057476071549834,
					7.544231568287237
				],
				[
					13.392606652456436,
					8.704882578792983
				],
				[
					14.060171942909736,
					10.44585909455149
				],
				[
					15.395302523816337,
					12.186835610310219
				],
				[
					16.73043310472294,
					13.92781212606895
				],
				[
					17.397998395176238,
					15.668788641827458
				],
				[
					18.06556368562954,
					16.829439652333203
				],
				[
					19.400694266536142,
					17.99009066283895
				],
				[
					20.068259556989442,
					20.311392683850443
				],
				[
					20.73582484744274,
					21.472043694356188
				],
				[
					21.403390137896046,
					23.213020210114916
				],
				[
					21.403390137896046,
					23.79334571536768
				],
				[
					21.403390137896046,
					25.53432223112641
				],
				[
					22.070955428349343,
					26.694973241631935
				],
				[
					22.070955428349343,
					27.8556242521379
				],
				[
					22.070955428349343,
					29.016275262643425
				],
				[
					22.070955428349343,
					29.596600767896405
				],
				[
					22.070955428349343,
					30.757251778402154
				],
				[
					22.070955428349343,
					31.917902788907902
				],
				[
					22.070955428349343,
					33.07855379941365
				],
				[
					22.738520718802643,
					33.65887930466663
				],
				[
					22.738520718802643,
					34.81953031517237
				],
				[
					22.738520718802643,
					35.39985582042514
				],
				[
					22.738520718802643,
					36.56050683093088
				],
				[
					22.738520718802643,
					37.72115784143663
				],
				[
					23.406086009255944,
					39.46213435719535
				],
				[
					23.406086009255944,
					40.622785367701105
				],
				[
					23.406086009255944,
					42.36376188345961
				],
				[
					23.406086009255944,
					44.10473839921834
				],
				[
					23.406086009255944,
					45.26538940972409
				],
				[
					23.406086009255944,
					46.42604042022983
				],
				[
					23.406086009255944,
					47.586691430735584
				],
				[
					23.406086009255944,
					48.74734244124133
				],
				[
					23.406086009255944,
					50.488318956999834
				],
				[
					23.406086009255944,
					52.809620978011324
				],
				[
					22.738520718802643,
					53.97027198851707
				],
				[
					22.070955428349343,
					55.13092299902282
				],
				[
					21.403390137896046,
					56.29157400952857
				],
				[
					21.403390137896046,
					56.871899514781546
				],
				[
					20.73582484744274,
					58.03255052528729
				],
				[
					20.068259556989442,
					60.35385254629878
				],
				[
					18.73312897608284,
					62.094829062057286
				],
				[
					17.397998395176238,
					63.835805577816025
				],
				[
					16.062867814269637,
					65.57678209357454
				],
				[
					14.727737233363037,
					66.73743310408028
				],
				[
					14.060171942909736,
					67.31775860933325
				],
				[
					13.392606652456436,
					68.47840961983901
				],
				[
					12.057476071549834,
					69.05873512509177
				],
				[
					11.389910781096532,
					70.21938613559752
				],
				[
					10.722345490643233,
					71.38003714610326
				],
				[
					10.054780200189933,
					72.54068815660901
				],
				[
					8.71964961928333,
					74.28166467236774
				],
				[
					8.05208432883003,
					75.44231568287348
				],
				[
					6.716953747923428,
					76.60296669337923
				],
				[
					6.716953747923428,
					77.76361770388496
				],
				[
					5.381823167016828,
					78.34394320913773
				],
				[
					4.7142578765635275,
					78.9242687143907
				],
				[
					3.379127295656925,
					80.08491972489647
				],
				[
					2.711562005203625,
					80.66524523014922
				],
				[
					2.043996714750324,
					81.24557073540221
				],
				[
					0.04130084339042206,
					82.40622174590796
				],
				[
					-1.2938297375162109,
					82.98654725116072
				],
				[
					-2.6289603184228127,
					84.14719826166646
				],
				[
					-3.9640908993294133,
					85.3078492721722
				],
				[
					-5.966786770689316,
					85.88817477742519
				],
				[
					-7.301917351595916,
					87.04882578793095
				],
				[
					-8.637047932502517,
					87.62915129318371
				],
				[
					-10.63974380386242,
					88.78980230368946
				],
				[
					-13.310004965675622,
					90.53077881944817
				],
				[
					-15.312700837035525,
					91.69142982995392
				],
				[
					-17.315396708395426,
					92.85208084045966
				],
				[
					-18.65052728930203,
					93.43240634571242
				],
				[
					-19.985657870208627,
					93.43240634571242
				],
				[
					-20.65322316066193,
					94.01273185096542
				],
				[
					-21.98835374156853,
					94.59305735621817
				],
				[
					-23.323484322475135,
					94.59305735621817
				],
				[
					-23.991049612928432,
					95.17338286147117
				],
				[
					-25.326180193835036,
					95.17338286147117
				],
				[
					-27.328876065194937,
					95.75370836672393
				],
				[
					-29.331571936554834,
					95.75370836672393
				],
				[
					-30.666702517461438,
					96.33403387197691
				],
				[
					-31.334267807914742,
					96.33403387197691
				],
				[
					-32.00183309836804,
					96.91435937722967
				],
				[
					-33.336963679274646,
					96.91435937722967
				],
				[
					-34.67209426018125,
					97.49468488248266
				],
				[
					-36.674790131541144,
					98.07501038773542
				],
				[
					-38.67748600290105,
					98.65533589298839
				],
				[
					-40.01261658380765,
					99.23566139824116
				],
				[
					-41.34774716471425,
					99.81598690349414
				],
				[
					-42.01531245516755,
					99.81598690349414
				],
				[
					-42.01531245516755,
					100.3963124087469
				],
				[
					-42.68287774562086,
					100.3963124087469
				],
				[
					-43.350443036074154,
					100.3963124087469
				],
				[
					-43.350443036074154,
					100.97663791399988
				],
				[
					-43.350443036074154,
					100.97663791399988
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 261,
			"versionNonce": 1770040080,
			"isDeleted": false,
			"id": "ZUd_qbB01XdCYuikN2r7t",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 540.7031458239503,
			"y": -1763.8796299661826,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.126100225108075,
			"height": 5.9384168542567295,
			"seed": 60907882,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.593841685425673,
					0
				],
				[
					-1.187683370851346,
					0.5938416854255593
				],
				[
					-1.7815250562770188,
					1.187683370851346
				],
				[
					-2.375366741702692,
					1.187683370851346
				],
				[
					-2.375366741702692,
					1.7815250562769052
				],
				[
					-2.375366741702692,
					2.375366741702692
				],
				[
					-2.9692084271283647,
					2.969208427128251
				],
				[
					-2.9692084271283647,
					3.5630501125540377
				],
				[
					-3.5630501125540377,
					3.5630501125540377
				],
				[
					-3.5630501125540377,
					4.156891797979597
				],
				[
					-3.5630501125540377,
					4.750733483405384
				],
				[
					-2.9692084271283647,
					4.750733483405384
				],
				[
					-1.7815250562770188,
					4.750733483405384
				],
				[
					-1.187683370851346,
					5.344575168830943
				],
				[
					0,
					5.344575168830943
				],
				[
					1.187683370851346,
					5.344575168830943
				],
				[
					1.7815250562770188,
					5.344575168830943
				],
				[
					2.375366741702692,
					5.9384168542567295
				],
				[
					2.9692084271283647,
					5.9384168542567295
				],
				[
					3.5630501125540377,
					5.9384168542567295
				],
				[
					3.5630501125540377,
					5.9384168542567295
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 314,
			"versionNonce": 1820282352,
			"isDeleted": false,
			"id": "QzgvZxDG_PuuA-UBgW7ZZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 535.3974701997425,
			"y": -1781.6427744285759,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.38688315395432,
			"height": 79.80313879237006,
			"seed": 2031369974,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					1.1731616173445047
				],
				[
					0.4423360394244263,
					0.7639147517425589
				],
				[
					0.8846720788488526,
					0.35466788614061295
				],
				[
					1.7693441576977051,
					-1.2823195762669668
				],
				[
					2.6540162365465854,
					-3.3285539042764913
				],
				[
					3.538688315395438,
					-5.784035097887964
				],
				[
					4.42336039424429,
					-8.648763157101175
				],
				[
					5.308032473093143,
					-10.6949974851107
				],
				[
					5.750368512517569,
					-13.150478678721969
				],
				[
					6.635040591366422,
					-15.60595987233344
				],
				[
					7.519712670215302,
					-18.06144106594471
				],
				[
					7.9620487096397285,
					-20.10767539395423
				],
				[
					8.404384749064155,
					-22.97240345316765
				],
				[
					9.289056827913008,
					-25.01863778117697
				],
				[
					9.731392867337433,
					-27.064872109186496
				],
				[
					10.616064946186286,
					-29.11110643719602
				],
				[
					11.943073064459565,
					-31.566587630807497
				],
				[
					12.385409103884019,
					-33.203575093214866
				],
				[
					13.27008118273287,
					-34.84056255562265
				],
				[
					13.712417222157297,
					-36.47755001803023
				],
				[
					14.597089301006152,
					-37.70529061483587
				],
				[
					15.039425340430576,
					-38.933031211641506
				],
				[
					15.481761379855003,
					-40.570018674049074
				],
				[
					16.366433458703856,
					-41.79775927085471
				],
				[
					16.80876949812828,
					-43.02549986766055
				],
				[
					17.251105537552707,
					-45.071734195670075
				],
				[
					18.13577761640159,
					-46.70872165807766
				],
				[
					18.578113655826016,
					-47.93646225488329
				],
				[
					19.02044969525044,
					-49.57344971729087
				],
				[
					19.462785734674867,
					-50.39194344849456
				],
				[
					20.347457813523718,
					-52.02893091090234
				],
				[
					20.789793852948147,
					-52.84742464210603
				],
				[
					21.232129892372573,
					-54.4844121045136
				],
				[
					22.116801971221427,
					-55.71215270131924
				],
				[
					22.55913801064585,
					-56.93989329812508
				],
				[
					23.001474050070275,
					-58.16763389493071
				],
				[
					23.88614612891913,
					-59.39537449173635
				],
				[
					24.328482168343555,
					-60.623115088542185
				],
				[
					25.213154247192463,
					-61.85085568534781
				],
				[
					26.54016236546574,
					-64.30633687895907
				],
				[
					27.424834444314595,
					-65.94332434136666
				],
				[
					27.867170483739024,
					-67.1710649381725
				],
				[
					28.751842562587875,
					-68.39880553497814
				],
				[
					29.636514641436726,
					-69.62654613178377
				],
				[
					30.52118672028558,
					-70.8542867285894
				],
				[
					30.963522759710006,
					-71.67278045979329
				],
				[
					31.84819483855886,
					-72.49127419099719
				],
				[
					32.29053087798329,
					-73.30976792220088
				],
				[
					32.73286691740771,
					-74.53750851900651
				],
				[
					33.17520295683214,
					-75.3560022502104
				],
				[
					34.05987503568099,
					-75.76524911581235
				],
				[
					34.05987503568099,
					-76.58374284701604
				],
				[
					34.502211075105414,
					-76.99298971261797
				],
				[
					34.9445471145299,
					-77.40223657821993
				],
				[
					34.9445471145299,
					-77.81148344382187
				],
				[
					35.38688315395432,
					-78.22073030942362
				],
				[
					35.38688315395432,
					-78.62997717502556
				],
				[
					35.38688315395432,
					-78.62997717502556
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 247,
			"versionNonce": 408471824,
			"isDeleted": false,
			"id": "jLx5TarGh7XNPyj-N7ZaX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 568.9209812764226,
			"y": -1861.3847340898667,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.370718599203831,
			"height": 3.8243787743034368,
			"seed": 2103242806,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.18211327496683152,
					0
				],
				[
					0,
					0
				],
				[
					0.5463398249004694,
					-0.1821132749669069
				],
				[
					1.0926796498009388,
					-0.3642265499338138
				],
				[
					2.003246024635071,
					-0.7284530998674266
				],
				[
					2.913812399469204,
					-0.9105663748341325
				],
				[
					3.4601522243696734,
					-1.0926796498010394
				],
				[
					3.6422654993365047,
					-1.0926796498010394
				],
				[
					3.8243787743033364,
					-1.2747929247679464
				],
				[
					3.8243787743033364,
					-1.0926796498010394
				],
				[
					3.8243787743033364,
					-0.9105663748341325
				],
				[
					3.8243787743033364,
					-0.3642265499338138
				],
				[
					3.8243787743033364,
					0.18211327496670587
				],
				[
					3.8243787743033364,
					0.9105663748341325
				],
				[
					3.8243787743033364,
					1.456906199734451
				],
				[
					3.8243787743033364,
					2.003246024634971
				],
				[
					4.006492049270142,
					2.3674725745685836
				],
				[
					4.188605324236999,
					2.5495858495354904
				],
				[
					4.188605324236999,
					2.5495858495354904
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 296,
			"versionNonce": 1296044016,
			"isDeleted": false,
			"id": "R7dU7ftV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 527.619756443562,
			"y": -1708.3012392409216,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.5479736328125,
			"height": 13.169468311859339,
			"seed": 931460330,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"fontSize": 10.53557464948747,
			"fontFamily": 1,
			"text": "Fig 1: Elman Network",
			"rawText": "Fig 1: Elman Network",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Fig 1: Elman Network",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 229,
			"versionNonce": 847062800,
			"isDeleted": false,
			"id": "4zu1qCv6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 184.4078541744326,
			"y": -1982.7971601823854,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 70.97616577148438,
			"height": 20,
			"seed": 1558040822,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Abstract",
			"rawText": "Abstract",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Abstract",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 249,
			"versionNonce": 479760880,
			"isDeleted": false,
			"id": "j8YLSHuJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 221.48570002150507,
			"y": -2033.4574410637672,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 374.65679931640625,
			"height": 20,
			"seed": 379600682,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704466,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Recurrent neural network based language model",
			"rawText": "Recurrent neural network based language model",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Recurrent neural network based language model",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 331,
			"versionNonce": 73778448,
			"isDeleted": false,
			"id": "eH0JkTtS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 78.177952820933,
			"y": -1940.9435503703683,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 273.253662109375,
			"height": 68.57142857142843,
			"seed": 1837031658,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 13.714285714285685,
			"fontFamily": 1,
			"text": "New technique obtain 50% reduction of \nperplexity using mixture of several RNN \nLM. It is superior to standard n-gram\ntechniques.",
			"rawText": "New technique obtain 50% reduction of \nperplexity using mixture of several RNN \nLM. It is superior to standard n-gram\ntechniques.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "New technique obtain 50% reduction of \nperplexity using mixture of several RNN \nLM. It is superior to standard n-gram\ntechniques.",
			"lineHeight": 1.25,
			"baseline": 63
		},
		{
			"type": "text",
			"version": 174,
			"versionNonce": 831575024,
			"isDeleted": false,
			"id": "rviWJ9D6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 171.85583696251854,
			"y": -1858.852060579392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.0802001953125,
			"height": 20,
			"seed": 1841477750,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Introduction",
			"rawText": "Introduction",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Introduction",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 647,
			"versionNonce": 193635088,
			"isDeleted": false,
			"id": "Ks2qAzC9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -684.2634379503361,
			"y": -1542.449001933012,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 33.3046875,
			"height": 14.656251609388953,
			"seed": 467830954,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 11.725001287511162,
			"fontFamily": 1,
			"text": "Words",
			"rawText": "Words",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Words",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "line",
			"version": 132,
			"versionNonce": 1110496752,
			"isDeleted": false,
			"id": "vXP0nRQv7rgrN3RZSbzDG",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -558.0787045718513,
			"y": -1501.6271292157417,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 194.63600499618911,
			"height": 0,
			"seed": 1697984630,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
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
					194.63600499618911,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 88,
			"versionNonce": 1449378064,
			"isDeleted": false,
			"id": "UJQ3cG3CSLZOxjtb4HFXD",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -462.00836877245024,
			"y": -1513.47996285333,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 45.53983450231351,
			"height": 0,
			"seed": 304995574,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
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
					45.53983450231351,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 739,
			"versionNonce": 58759152,
			"isDeleted": false,
			"id": "k4SW7KdX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -690.4860942003361,
			"y": -1397.116816411131,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 45.75,
			"height": 14.656251609388953,
			"seed": 60137910,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 11.725001287511162,
			"fontFamily": 1,
			"text": "Context",
			"rawText": "Context",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Context",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 752,
			"versionNonce": 1684610832,
			"isDeleted": false,
			"id": "jcJZp0kO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -687.2458598253361,
			"y": -1283.6321189708206,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 39.26953125,
			"height": 14.656251609388953,
			"seed": 801423722,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 11.725001287511162,
			"fontFamily": 1,
			"text": "Limited",
			"rawText": "Limited",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Limited",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 182,
			"versionNonce": 1233656304,
			"isDeleted": false,
			"id": "KVbPTI36",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -578.2739024171851,
			"y": -1814.295092772027,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 2.0070953369140625,
			"height": 9.266341282782694,
			"seed": 2022841962,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 7.413073026226155,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 846,
			"versionNonce": 101891344,
			"isDeleted": false,
			"id": "oE9FZDa1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.4398462420304,
			"y": -1999.91751738505,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 466.78497314453125,
			"height": 80,
			"seed": 1328642934,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Parse trees are graphical representations of sentences\ntaking account the structure and relationship of words as\nnoums, verbs, objects and etc. It is different of a linear \nrepresentation of words.",
			"rawText": "Parse trees are graphical representations of sentences\ntaking account the structure and relationship of words as\nnoums, verbs, objects and etc. It is different of a linear \nrepresentation of words.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Parse trees are graphical representations of sentences\ntaking account the structure and relationship of words as\nnoums, verbs, objects and etc. It is different of a linear \nrepresentation of words.",
			"lineHeight": 1.25,
			"baseline": 74
		},
		{
			"type": "text",
			"version": 158,
			"versionNonce": 659512304,
			"isDeleted": false,
			"id": "ixJCOshg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -416.0340929756005,
			"y": -1527.6612790085587,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 5.2732391357421875,
			"height": 9.266341282782694,
			"seed": 989305974,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 7.413073026226155,
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
			"version": 1344,
			"versionNonce": 1020828432,
			"isDeleted": false,
			"id": "fDEOUyE9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.4398462420304,
			"y": -1902.334182243109,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 518.3050537109375,
			"height": 100,
			"seed": 1433540202,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Word and sentence characteristics:\n    - Morphology: Understanding the ways words can change\n                 based on basic units called morphemes. \n    - Syntax: Rules to organize words in a meaningful way.\n    - Semantics: Meaning behind words, sentences and paragraphs.",
			"rawText": "Word and sentence characteristics:\n    - Morphology: Understanding the ways words can change\n                 based on basic units called morphemes. \n    - Syntax: Rules to organize words in a meaningful way.\n    - Semantics: Meaning behind words, sentences and paragraphs.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Word and sentence characteristics:\n    - Morphology: Understanding the ways words can change\n                 based on basic units called morphemes. \n    - Syntax: Rules to organize words in a meaningful way.\n    - Semantics: Meaning behind words, sentences and paragraphs.",
			"lineHeight": 1.25,
			"baseline": 94
		},
		{
			"type": "text",
			"version": 781,
			"versionNonce": 249454064,
			"isDeleted": false,
			"id": "TyFfyY5i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 67.2260394849119,
			"y": -1824.0943471569487,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 327.34466552734375,
			"height": 100,
			"seed": 896479478,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "    Describing Language models by atomic\nsymbols (words) such as parse trees or\nconsider how words can be represented,\nthe way they are organized and the me-\naning behind senteces and paragraphs.",
			"rawText": "    Describing Language models by atomic\nsymbols (words) such as parse trees or\nconsider how words can be represented,\nthe way they are organized and the me-\naning behind senteces and paragraphs.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    Describing Language models by atomic\nsymbols (words) such as parse trees or\nconsider how words can be represented,\nthe way they are organized and the me-\naning behind senteces and paragraphs.",
			"lineHeight": 1.25,
			"baseline": 94
		},
		{
			"type": "text",
			"version": 308,
			"versionNonce": 456309008,
			"isDeleted": false,
			"id": "p2cbcWgE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 61.026027277880644,
			"y": -1697.7087633897656,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 365.76080322265625,
			"height": 60,
			"seed": 668138038,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "    If language models are measure based\non context, or the capacity of predict the \nnext word, it can be said there is a progress.",
			"rawText": "    If language models are measure based\non context, or the capacity of predict the \nnext word, it can be said there is a progress.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    If language models are measure based\non context, or the capacity of predict the \nnext word, it can be said there is a progress.",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "text",
			"version": 478,
			"versionNonce": 1899831280,
			"isDeleted": false,
			"id": "xpFuu8Ix",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 60.99673277870011,
			"y": -1626.0931854621554,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 322.0806884765625,
			"height": 60,
			"seed": 2100603382,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "    If analysed in industrial practical \napplications the progress is limited over \nsimple baselines modeling.",
			"rawText": "    If analysed in industrial practical \napplications the progress is limited over \nsimple baselines modeling.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    If analysed in industrial practical \napplications the progress is limited over \nsimple baselines modeling.",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "text",
			"version": 249,
			"versionNonce": 614012688,
			"isDeleted": false,
			"id": "oNbnH6t8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 153.43979844933494,
			"y": -1545.8436626025793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.9122772216797,
			"height": 20,
			"seed": 1096280554,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Model description",
			"rawText": "Model description",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Model description",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 105,
			"versionNonce": 1584636400,
			"isDeleted": false,
			"id": "BIeAO3GZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -44.73101745197545,
			"y": -1470.423753504204,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 43.63786315917969,
			"height": 8.34383815315296,
			"seed": 379702198,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 6.675070522522368,
			"fontFamily": 1,
			"text": "fixed-context",
			"rawText": "fixed-context",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "fixed-context",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "line",
			"version": 253,
			"versionNonce": 763606288,
			"isDeleted": false,
			"id": "QS9SsrD_HEk6sJIbjJF9B",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -325.9409524771019,
			"y": -1352.241945284367,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 271.10132650917217,
			"height": 0,
			"seed": 1373136234,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
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
					271.10132650917217,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 200,
			"versionNonce": 629793776,
			"isDeleted": false,
			"id": "eehpnvysH4MAEjekto-Nk",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -326.6238273549588,
			"y": -1339.2673226050867,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 137.59928788815665,
			"height": 0,
			"seed": 1873489334,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
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
					137.59928788815665,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 78,
			"versionNonce": 996840208,
			"isDeleted": false,
			"id": "JeiCOp5tr5xxnOLxFIIsj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -90.69055705541479,
			"y": -1365.2165679636473,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 35.50949364855654,
			"height": 0,
			"seed": 1761177270,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
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
					35.50949364855654,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 1955063280,
			"isDeleted": false,
			"id": "X0ZjIUOS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -54.45511605740717,
			"y": -1380.1671045367946,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 4.739990234375,
			"height": 9.266341282782694,
			"seed": 898643894,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704467,
			"link": null,
			"locked": false,
			"fontSize": 7.413073026226155,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 280,
			"versionNonce": 1690677520,
			"isDeleted": false,
			"id": "W0mfQgAh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -47.323842069034754,
			"y": -1346.1547328916201,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 46.41351318359375,
			"height": 16.68767630630592,
			"seed": 414389942,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 6.675070522522368,
			"fontFamily": 1,
			"text": "ad hoc\n\"case-by-case\"",
			"rawText": "ad hoc\n\"case-by-case\"",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ad hoc\n\"case-by-case\"",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 842,
			"versionNonce": 2020976624,
			"isDeleted": false,
			"id": "oSY6lIAu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.7844132846083,
			"y": -2057.4435160309677,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 16.208038330078125,
			"height": 20,
			"seed": 1451230134,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1: ",
			"rawText": "1: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1: ",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "line",
			"version": 100,
			"versionNonce": 822939408,
			"isDeleted": false,
			"id": "2eEX3WlbgxByQcJiSit0e",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -623.2044590385799,
			"y": -1797.6706421354636,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 43.27344568294245,
			"height": 0,
			"seed": 1442012854,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
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
					43.27344568294245,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 2103126512,
			"isDeleted": false,
			"id": "JO5gGVPD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -362.48117798240276,
			"y": -1515.7919393701368,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 5.04364013671875,
			"height": 9.266341282782694,
			"seed": 306725418,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 7.413073026226155,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 725,
			"versionNonce": 2025368848,
			"isDeleted": false,
			"id": "tL6ldUfY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -684.1346642731603,
			"y": -1776.7704760788017,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 39.38427734375,
			"height": 10.974640841416283,
			"seed": 1819565046,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 8.779712673133027,
			"fontFamily": 1,
			"text": "Perpexity",
			"rawText": "Perpexity",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Perpexity",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 797,
			"versionNonce": 239102960,
			"isDeleted": false,
			"id": "M3aNXNIl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -692.8481817440297,
			"y": -1001.3522338350577,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 55.16015625,
			"height": 14.656251609388953,
			"seed": 957820074,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 11.725001287511162,
			"fontFamily": 1,
			"text": "Long-term",
			"rawText": "Long-term",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Long-term",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 1028,
			"versionNonce": 1161857808,
			"isDeleted": false,
			"id": "oA2aqNPf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -686.1492554622051,
			"y": -906.092639451124,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 36.84175109863281,
			"height": 17.042061723999197,
			"seed": 1022297398,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 13.633649379199358,
			"fontFamily": 1,
			"text": "Elman",
			"rawText": "Elman",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Elman",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 1044,
			"versionNonce": 355298800,
			"isDeleted": false,
			"id": "8SPA3qwW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -685.42681626428,
			"y": -556.3706919587548,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 39.11712646484375,
			"height": 17.042061723999197,
			"seed": 976692330,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 13.633649379199358,
			"fontFamily": 1,
			"text": "Config",
			"rawText": "Config",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Config",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 1060,
			"versionNonce": 823961872,
			"isDeleted": false,
			"id": "pxUSmmaZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -683.4920704757058,
			"y": -417.2448621685048,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 35.24763488769531,
			"height": 17.042061723999197,
			"seed": 783194038,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 13.633649379199358,
			"fontFamily": 1,
			"text": "Train",
			"rawText": "Train",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Train",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 1205,
			"versionNonce": 2066362352,
			"isDeleted": false,
			"id": "9L673kkS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -691.6448484643447,
			"y": -298.6351526676744,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 51.12290954589844,
			"height": 10.167884008817508,
			"seed": 1070332458,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 8.134307207054006,
			"fontFamily": 1,
			"text": "Observations",
			"rawText": "Observations",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Observations",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 1204094736,
			"isDeleted": false,
			"id": "RIeFPnNV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -40.08566291328975,
			"y": -950.5903320515728,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 35.824066162109375,
			"height": 20,
			"seed": 540472822,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Loss",
			"rawText": "Loss",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Loss",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "line",
			"version": 97,
			"versionNonce": 1212068336,
			"isDeleted": false,
			"id": "Omv_Etb8FjgcUO-OQmEX0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -392.8204559354054,
			"y": -551.5955472847014,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 30.490964867620505,
			"height": 0.3629876769954308,
			"seed": 423986346,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
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
					30.490964867620505,
					0.3629876769954308
				]
			]
		},
		{
			"type": "line",
			"version": 105,
			"versionNonce": 1706140944,
			"isDeleted": false,
			"id": "yJw5XW5AFHOTc30Q6HykP",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -632.0293350754288,
			"y": -538.3464970743656,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 30.490964867620505,
			"height": 1.1368683772161603e-13,
			"seed": 996164022,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
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
					30.490964867620505,
					-1.1368683772161603e-13
				]
			]
		},
		{
			"type": "rectangle",
			"version": 229,
			"versionNonce": 1131607024,
			"isDeleted": false,
			"id": "5s7bbxHcATlazjDlwlqI-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 40,
			"angle": 0,
			"x": -330.3441497700131,
			"y": -867.3794890564416,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 279.01699427626926,
			"height": 299.75646806684915,
			"seed": 879218410,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 408584976,
			"isDeleted": false,
			"id": "6xspAHTN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -34.236627783312315,
			"y": -772.9464782448653,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 7.4560089111328125,
			"height": 20,
			"seed": 1126512746,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "?",
			"rawText": "?",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "?",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 315553264,
			"isDeleted": false,
			"id": "BA5l7zrN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -45.129869006613546,
			"y": -541.8240075864644,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 47.93609619140625,
			"height": 20,
			"seed": 286447030,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "BPTT",
			"rawText": "BPTT",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "BPTT",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 125,
			"versionNonce": 2117574928,
			"isDeleted": false,
			"id": "8UkUxhDz",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -47.30561384970741,
			"y": -453.2896920157331,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 48.416107177734375,
			"height": 20,
			"seed": 1356192042,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Tuning",
			"rawText": "Tuning",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Tuning",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 171,
			"versionNonce": 1532671984,
			"isDeleted": false,
			"id": "H2NTR6cW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 552.5442348814611,
			"y": -1826.0957539342896,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 24.357421875,
			"height": 11.98193449102359,
			"seed": 386816682,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "s(t-1)",
			"rawText": "s(t-1)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s(t-1)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 242,
			"versionNonce": 650182416,
			"isDeleted": false,
			"id": "uRS2IdY4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 591.3258861823863,
			"y": -1888.5221211113203,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 17.8250732421875,
			"height": 11.98193449102359,
			"seed": 1358588074,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "s(t)",
			"rawText": "s(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 283,
			"versionNonce": 1629370864,
			"isDeleted": false,
			"id": "Zou9mqa0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.9521756804459,
			"y": -1809.7732634338734,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 17.116287231445312,
			"height": 11.98193449102359,
			"seed": 566261418,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704468,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "y(t)",
			"rawText": "y(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 346,
			"versionNonce": 1919851792,
			"isDeleted": false,
			"id": "yob9HNbl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 542.4753035012449,
			"y": -1892.4278865863475,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 18.457244873046875,
			"height": 11.98193449102359,
			"seed": 502177526,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "w(t)",
			"rawText": "w(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "w(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "rectangle",
			"version": 108,
			"versionNonce": 656505840,
			"isDeleted": false,
			"id": "iSdJ3YFfqWGkma-TYEKmj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 30,
			"angle": 0,
			"x": -572.8491214393778,
			"y": -825.0775355117278,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 148.98929621771543,
			"height": 105.01448191557051,
			"seed": 1147335158,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2170,
			"versionNonce": 1924692752,
			"isDeleted": false,
			"id": "IvrArjfc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.4398462420304,
			"y": -1787.037034423346,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffec99",
			"width": 390.54486083984375,
			"height": 100,
			"seed": 848044528,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "It means that the fixed-length context need\nto be specified case-by-case for each training \ninstance, which does not seem to fit for a longer\nsentence or generalization.\n",
			"rawText": "It means that the fixed-length context need\nto be specified case-by-case for each training \ninstance, which does not seem to fit for a longer\nsentence or generalization.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "It means that the fixed-length context need\nto be specified case-by-case for each training \ninstance, which does not seem to fit for a longer\nsentence or generalization.\n",
			"lineHeight": 1.25,
			"baseline": 94
		},
		{
			"type": "text",
			"version": 927,
			"versionNonce": 258768368,
			"isDeleted": false,
			"id": "6gq5EA7j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.4398462420304,
			"y": -1685.9577394694913,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 536.2570190429688,
			"height": 120,
			"seed": 1224939792,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "For a list with n words the current word is 1 and others are 0. \nExample:\nif our vocabulary consists of [\"cat\", \"dog\", \"bird\"], and the current \nword at time t is \"dog,\" then x(t) would be [0, 1, 0] since it \nrepresents the second element (\"dog\") out of three possible \nchoices (\"cat,\" \"dog,\" or \"bird\")",
			"rawText": "For a list with n words the current word is 1 and others are 0. \nExample:\nif our vocabulary consists of [\"cat\", \"dog\", \"bird\"], and the current \nword at time t is \"dog,\" then x(t) would be [0, 1, 0] since it \nrepresents the second element (\"dog\") out of three possible \nchoices (\"cat,\" \"dog,\" or \"bird\")",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "For a list with n words the current word is 1 and others are 0. \nExample:\nif our vocabulary consists of [\"cat\", \"dog\", \"bird\"], and the current \nword at time t is \"dog,\" then x(t) would be [0, 1, 0] since it \nrepresents the second element (\"dog\") out of three possible \nchoices (\"cat,\" \"dog,\" or \"bird\")",
			"lineHeight": 1.25,
			"baseline": 114
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 1242994960,
			"isDeleted": false,
			"id": "rRlbbPwo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -358.34626001718556,
			"y": -565.7311788190225,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 4.577056884765625,
			"height": 9.266341282782694,
			"seed": 1924456944,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 7.413073026226155,
			"fontFamily": 1,
			"text": "5",
			"rawText": "5",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "rectangle",
			"version": 337,
			"versionNonce": 2064072688,
			"isDeleted": false,
			"id": "8vSQp4jD-yLfV98w8rQ0u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 773.3042426424488,
			"y": -2121.1924591920183,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 719.9528940420531,
			"height": 1011.5146344356376,
			"seed": 2122236912,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 201389840,
			"isDeleted": false,
			"id": "5HXwXZxF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.8611428424181,
			"y": -2101.8537732599357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 87.179931640625,
			"height": 25,
			"seed": 1348965648,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "DOUBTS",
			"rawText": "DOUBTS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DOUBTS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 369,
			"versionNonce": 1777975792,
			"isDeleted": false,
			"id": "Xvrd15ED",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 794.8857478742532,
			"y": -1158.6683238636363,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 483.17254638671875,
			"height": 25,
			"seed": 433535472,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": "https://pabloinsente.github.io/the-recurrent-net",
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "🌐https://pabloinsente.github.io/the-recurrent-net",
			"rawText": "https://pabloinsente.github.io/the-recurrent-net",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐https://pabloinsente.github.io/the-recurrent-net",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 485463312,
			"isDeleted": false,
			"id": "gKlN9RM4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 791.2493842378894,
			"y": -1204.1228693181815,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 110.71987915039062,
			"height": 25,
			"seed": 2132565264,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "References:",
			"rawText": "References:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "References:",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 457966576,
			"isDeleted": false,
			"id": "J0JqeQeX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.4398462420304,
			"y": -2056.1964907644456,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 474.51300048828125,
			"height": 40,
			"seed": 1385126384,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Perplexity: Metric that quantifies the level of uncertainty, \nlow indicates good predictions.",
			"rawText": "Perplexity: Metric that quantifies the level of uncertainty, \nlow indicates good predictions.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Perplexity: Metric that quantifies the level of uncertainty, \nlow indicates good predictions.",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "ellipse",
			"version": 403,
			"versionNonce": 307917584,
			"isDeleted": false,
			"id": "opHp6zZUAQRW9bdGGsEl6",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 600.7192546771462,
			"y": -1651.9119728160038,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 530568464,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 426,
			"versionNonce": 755369456,
			"isDeleted": false,
			"id": "_c4Rx1B59zkdynF4a3xux",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 601.4189381077083,
			"y": -1626.847636856712,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 1426240272,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 424,
			"versionNonce": 314151184,
			"isDeleted": false,
			"id": "ySFJNiDTHc8w7TcE-_Gjs",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 601.233035214872,
			"y": -1603.549423074666,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 1448726800,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 441,
			"versionNonce": 1009764336,
			"isDeleted": false,
			"id": "llTugwQtGQs7YJkSRJUMP",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 498.8281369533757,
			"y": -1661.8672212204328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 3.8461235041880513,
			"height": 4.813102381417999,
			"seed": 454897424,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 205,
			"versionNonce": 897904400,
			"isDeleted": false,
			"id": "sfUpBes_VYv7VuC1O1Jcj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 496.2644750661278,
			"y": -1645.6416526706466,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 9.309147627086109,
			"height": 8.791972758914778,
			"seed": 1808059664,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 233,
			"versionNonce": 80824816,
			"isDeleted": false,
			"id": "L85JNxqgRzkD7jXhUA5z8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 496.7816499342992,
			"y": -1626.7647699823883,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 9.309147627086109,
			"height": 8.791972758914778,
			"seed": 1103670032,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 226,
			"versionNonce": 1664388368,
			"isDeleted": false,
			"id": "O4k2HAcNl0xLjpQwfC9ca",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 496.7816499342992,
			"y": -1607.112124991873,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 9.309147627086109,
			"height": 8.791972758914778,
			"seed": 664848656,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 676,
			"versionNonce": 32672752,
			"isDeleted": false,
			"id": "exAvDUrjeD7h_dnvaOZcq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 554.3882568308998,
			"y": -1501.1997639061574,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 415573776,
			"groupIds": [
				"zqbGLLS8n8K4Uhh-znS1e"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 563,
			"versionNonce": 893414160,
			"isDeleted": false,
			"id": "mF-nEiFgYSNrPrfF8A15s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 561.0215411107306,
			"y": -1488.1188916857336,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 19.5749551876963,
			"height": 12.51513528393698,
			"seed": 1638778128,
			"groupIds": [
				"zqbGLLS8n8K4Uhh-znS1e"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704469,
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
					-3.8508108565959938,
					10.26882895092265
				],
				[
					-19.5749551876963,
					7.380720808475655
				],
				[
					-6.738918999042989,
					-2.2463063330143296
				]
			]
		},
		{
			"type": "ellipse",
			"version": 617,
			"versionNonce": 228298224,
			"isDeleted": false,
			"id": "SoIGaHFnrC1O-z3BimPPS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 523.5162398175808,
			"y": -1537.2483282368594,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 2144510736,
			"groupIds": [
				"836u9wpQYnVEGYqKvfotI"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 536,
			"versionNonce": 1444972816,
			"isDeleted": false,
			"id": "GkGQXv_3vXLpoLkfW_B98",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 529.841342146412,
			"y": -1525.1061872381947,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 19.5749551876963,
			"height": 12.51513528393698,
			"seed": 28033296,
			"groupIds": [
				"836u9wpQYnVEGYqKvfotI"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704469,
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
					-3.8508108565959938,
					10.26882895092265
				],
				[
					-19.5749551876963,
					7.380720808475655
				],
				[
					-6.738918999042989,
					-2.2463063330143296
				]
			]
		},
		{
			"type": "ellipse",
			"version": 584,
			"versionNonce": 13914096,
			"isDeleted": false,
			"id": "cKdwasvcgaf3_TzGVRBE2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 499.5912290340158,
			"y": -1568.9315847392568,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 1722883856,
			"groupIds": [
				"TciHtc5A68zn1LqhcioFD"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704469,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 517,
			"versionNonce": 1632429840,
			"isDeleted": false,
			"id": "OqrdmRSxdXfrouf5nbW9w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 507.22719094674886,
			"y": -1556.2911834000695,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 19.5749551876963,
			"height": 12.51513528393698,
			"seed": 2136653072,
			"groupIds": [
				"TciHtc5A68zn1LqhcioFD"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					-3.8508108565959938,
					10.26882895092265
				],
				[
					-19.5749551876963,
					7.380720808475655
				],
				[
					-6.738918999042989,
					-2.2463063330143296
				]
			]
		},
		{
			"type": "line",
			"version": 272,
			"versionNonce": 1403310576,
			"isDeleted": false,
			"id": "jw4yTpAdCXLLITLzqXaSv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.0558094182803,
			"y": -1641.1719178995659,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 95.37659423988242,
			"height": 4.102219107091738,
			"seed": 1293982480,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					95.37659423988242,
					-4.102219107091738
				]
			]
		},
		{
			"type": "line",
			"version": 330,
			"versionNonce": 1128105232,
			"isDeleted": false,
			"id": "kWy7Rygr4aLb1vAS2-lMZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.73951260279574,
			"y": -1641.1719178995659,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 95.03474264762467,
			"height": 20.169243943200858,
			"seed": 1652209936,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					95.03474264762467,
					20.169243943200858
				]
			]
		},
		{
			"type": "line",
			"version": 245,
			"versionNonce": 1024791536,
			"isDeleted": false,
			"id": "L83ig9Qu37QrMiMGx7MWD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.3976610105382,
			"y": -1641.1719178995659,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 96.40214901665536,
			"height": 43.4151522167206,
			"seed": 1122047760,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					96.40214901665536,
					43.4151522167206
				]
			]
		},
		{
			"type": "line",
			"version": 337,
			"versionNonce": 426402576,
			"isDeleted": false,
			"id": "Ku_wAR55KjpVOSbcBgDru",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.3976610105382,
			"y": -1621.3445255486222,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 95.71844583214002,
			"height": 23.587759865777414,
			"seed": 1120646416,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					95.71844583214002,
					-23.587759865777414
				]
			]
		},
		{
			"type": "line",
			"version": 419,
			"versionNonce": 1395463664,
			"isDeleted": false,
			"id": "_KOXUF9mqSB1okTcU7cO-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 506.08136419505314,
			"y": -1621.3445255486222,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 94.69289105536708,
			"height": 0.3418515922575109,
			"seed": 1739756304,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					94.69289105536708,
					0.3418515922575109
				]
			]
		},
		{
			"type": "line",
			"version": 236,
			"versionNonce": 306938128,
			"isDeleted": false,
			"id": "nXNz89QUjWV4QE-Qjb79i",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 506.4232157873106,
			"y": -1621.6863771408803,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 94.35103946310942,
			"height": 24.271463050292596,
			"seed": 1208856848,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					94.35103946310942,
					24.271463050292596
				]
			]
		},
		{
			"type": "line",
			"version": 290,
			"versionNonce": 720689136,
			"isDeleted": false,
			"id": "RrweruClQ95xcfvxLLMIT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 512.2346928556908,
			"y": -1566.3064191951419,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 88.53956239472947,
			"height": 79.30956940377322,
			"seed": 1800736528,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					88.53956239472947,
					-79.30956940377322
				]
			]
		},
		{
			"type": "line",
			"version": 256,
			"versionNonce": 1297669904,
			"isDeleted": false,
			"id": "7Blxi1fg4uLvfAZ6fYgSE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 512.2346928556908,
			"y": -1566.3064191951419,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 88.53956239472947,
			"height": 54.354403168965284,
			"seed": 704687376,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					88.53956239472947,
					-54.354403168965284
				]
			]
		},
		{
			"type": "line",
			"version": 246,
			"versionNonce": 2020891120,
			"isDeleted": false,
			"id": "g2BAPqCwa_4mbx_VXtmBy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 511.20913807891793,
			"y": -1565.6227160106266,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 89.90696876376008,
			"height": 31.792198079960727,
			"seed": 227052304,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					89.90696876376008,
					-31.792198079960727
				]
			]
		},
		{
			"type": "line",
			"version": 295,
			"versionNonce": 990543120,
			"isDeleted": false,
			"id": "zAhkKo65X2CuvEeKAJskA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 534.7968979446953,
			"y": -1536.5653306687268,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 64.95180252895223,
			"height": 108.70880633793057,
			"seed": 811903248,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					64.95180252895223,
					-108.70880633793057
				]
			]
		},
		{
			"type": "line",
			"version": 264,
			"versionNonce": 783522800,
			"isDeleted": false,
			"id": "6IWkJLM5GskdOaCjnO4mL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 533.7713431679224,
			"y": -1535.5397758919542,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 67.34476367475568,
			"height": 85.46289806441084,
			"seed": 504170256,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					67.34476367475568,
					-85.46289806441084
				]
			]
		},
		{
			"type": "line",
			"version": 270,
			"versionNonce": 2094553872,
			"isDeleted": false,
			"id": "Q7OJzG17BT7CKZZOb6hId",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 533.7713431679224,
			"y": -1536.5653306687268,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 66.31920889798283,
			"height": 60.507731829602896,
			"seed": 855221520,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					66.31920889798283,
					-60.507731829602896
				]
			]
		},
		{
			"type": "line",
			"version": 274,
			"versionNonce": 532323824,
			"isDeleted": false,
			"id": "Yu_N_dV6LH7apBCFQQSER",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 562.828728509822,
			"y": -1501.3546166661895,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 36.23626877931014,
			"height": 143.23581715595236,
			"seed": 2091025168,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					36.23626877931014,
					-143.23581715595236
				]
			]
		},
		{
			"type": "line",
			"version": 251,
			"versionNonce": 1161459984,
			"isDeleted": false,
			"id": "gUabYOXo7KfD8mgRz2Tpr",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 563.1705801020796,
			"y": -1501.6964682584476,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 37.94552674059833,
			"height": 117.59694773662923,
			"seed": 427794704,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					37.94552674059833,
					-117.59694773662923
				]
			]
		},
		{
			"type": "line",
			"version": 239,
			"versionNonce": 479289328,
			"isDeleted": false,
			"id": "WHsmj0TmOol9df5WBrM85",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 564.1961348788525,
			"y": -1500.3290618894168,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 36.919971963825404,
			"height": 95.71844583214018,
			"seed": 420019984,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					36.919971963825404,
					-95.71844583214018
				]
			]
		},
		{
			"type": "line",
			"version": 263,
			"versionNonce": 933811984,
			"isDeleted": false,
			"id": "eZNVS7aT-uibR8dDH8wnF",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.3976610105382,
			"y": -1603.2263911589673,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 94.69289105536716,
			"height": 42.38959743994774,
			"seed": 1538694416,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					94.69289105536716,
					-42.38959743994774
				]
			]
		},
		{
			"type": "line",
			"version": 229,
			"versionNonce": 356508144,
			"isDeleted": false,
			"id": "v24V5sI2oecNRf9z1MZxu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.73951260279574,
			"y": -1603.9100943434826,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 94.69289105536708,
			"height": 15.725173243851447,
			"seed": 1929411344,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					94.69289105536708,
					-15.725173243851447
				]
			]
		},
		{
			"type": "line",
			"version": 227,
			"versionNonce": 1218147600,
			"isDeleted": false,
			"id": "m3oTJqxfNqMSsQS0b8Qzj",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.73951260279574,
			"y": -1604.25194593574,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 95.03474264762467,
			"height": 7.520735029668133,
			"seed": 22976784,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					95.03474264762467,
					7.520735029668133
				]
			]
		},
		{
			"type": "line",
			"version": 348,
			"versionNonce": 953033712,
			"isDeleted": false,
			"id": "8KiAFTsQAMH5LXlL08krT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 502.8226923852875,
			"y": -1659.46501575591,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 96.58415649610231,
			"height": 13.507175564737096,
			"seed": 440989456,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					96.58415649610231,
					13.507175564737096
				]
			]
		},
		{
			"type": "line",
			"version": 310,
			"versionNonce": 495604496,
			"isDeleted": false,
			"id": "TZqscVGOfjEPquwQVE0LJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 502.6931316092441,
			"y": -1659.3239225413176,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 98.08112364117628,
			"height": 39.688654953983665,
			"seed": 574067984,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					98.08112364117628,
					39.688654953983665
				]
			]
		},
		{
			"type": "line",
			"version": 353,
			"versionNonce": 356787696,
			"isDeleted": false,
			"id": "bIJK0i-O1veNdBAOLVhCb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 503.00630235687373,
			"y": -1659.1856373104913,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 97.42610130128908,
			"height": 61.7707232199039,
			"seed": 782398224,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692386704470,
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
					97.42610130128908,
					61.7707232199039
				]
			]
		},
		{
			"type": "line",
			"version": 524,
			"versionNonce": 1827500304,
			"isDeleted": false,
			"id": "YvVbTUeqqM5x4lU-AOO9n",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 512.8812636934872,
			"y": -1565.3757690942373,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 129.010247816938,
			"height": 81.90568866851928,
			"seed": 1711378704,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
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
					129.010247816938,
					1.0545796824274523
				],
				[
					128.3071946953198,
					-80.49958242528267
				],
				[
					101.94270263463766,
					-80.85110898609183
				]
			]
		},
		{
			"type": "line",
			"version": 980,
			"versionNonce": 933881840,
			"isDeleted": false,
			"id": "x7vF_iTCmhl6xN-97shG5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.4724397673158,
			"y": -1620.2139125804558,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 92.80301205360111,
			"height": 84.01484803337387,
			"seed": 1607266064,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
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
					14.412588993172932,
					0
				],
				[
					14.764115553982004,
					84.01484803337387
				],
				[
					-78.0388964996191,
					84.0148480333737
				]
			]
		},
		{
			"type": "line",
			"version": 486,
			"versionNonce": 1581043472,
			"isDeleted": false,
			"id": "WzvjQOPph4EvnIwao4Pca",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.8239663281249,
			"y": -1596.6616330062466,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 48.86219195246433,
			"height": 97.72438390492849,
			"seed": 75271440,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
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
					-8.035462673245439e-14,
					97.02133078331035
				],
				[
					-48.86219195246433,
					97.72438390492849
				]
			]
		},
		{
			"type": "text",
			"version": 410,
			"versionNonce": 1275554288,
			"isDeleted": false,
			"id": "MOocAEYH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 514.5328018291781,
			"y": -1465.4634295117737,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 152.51951599121094,
			"height": 13.169468311859339,
			"seed": 2056790288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
			"link": null,
			"locked": false,
			"fontSize": 10.53557464948747,
			"fontFamily": 1,
			"text": "Fig 1: Detailed Elman Network",
			"rawText": "Fig 1: Detailed Elman Network",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Fig 1: Detailed Elman Network",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 374,
			"versionNonce": 1777364240,
			"isDeleted": false,
			"id": "BVKTHSOM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 467.43971068223766,
			"y": -1630.9577209101296,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#ffc9c9",
			"width": 18.457244873046875,
			"height": 11.98193449102359,
			"seed": 1531750672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "w(t)",
			"rawText": "w(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "w(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 399,
			"versionNonce": 1030007792,
			"isDeleted": false,
			"id": "q4ITOhX7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 595.3434451480724,
			"y": -1670.6907759394799,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 20.96673583984375,
			"height": 11.98193449102359,
			"seed": 1138899952,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "sj(t)",
			"rawText": "sj(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sj(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "ellipse",
			"version": 451,
			"versionNonce": 1812119824,
			"isDeleted": false,
			"id": "RtRIyDMass7haBbfrNVvc",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 669.4339683379053,
			"y": -1635.396559360158,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffd8a8",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 1220471056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386723462,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 568,
			"versionNonce": 1439280624,
			"isDeleted": false,
			"id": "bgCh8Mvt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 485.03759156150284,
			"y": -1509.4692873134338,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 27.49908447265625,
			"height": 11.98193449102359,
			"seed": 1197587216,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "sj(t-1)",
			"rawText": "sj(t-1)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sj(t-1)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "ellipse",
			"version": 483,
			"versionNonce": 1848123152,
			"isDeleted": false,
			"id": "ZT9u01uIJeOWfy9c8gAI4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 669.4339683379053,
			"y": -1611.0482010537328,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffd8a8",
			"width": 13.40844188209562,
			"height": 12.426243010838302,
			"seed": 251991312,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386726427,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 215,
			"versionNonce": 1817577968,
			"isDeleted": false,
			"id": "E2JMptWI7dQz_3skL_siz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.2091097942942,
			"y": -1646.2441699048914,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 55.64164979610541,
			"height": 16.810166101542336,
			"seed": 564733936,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386716910,
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
					55.64164979610541,
					16.810166101542336
				]
			]
		},
		{
			"type": "line",
			"version": 92,
			"versionNonce": 861654288,
			"isDeleted": false,
			"id": "Vk5tgtQXR2f8HtBx8qkwQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 613.8729064722635,
			"y": -1646.4122715659068,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 55.30544647407453,
			"height": 41.521110270809686,
			"seed": 228870928,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386716910,
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
					55.30544647407453,
					41.521110270809686
				]
			]
		},
		{
			"type": "line",
			"version": 160,
			"versionNonce": 633652496,
			"isDeleted": false,
			"id": "ouqBbZUr4RkzQrEuKcdNj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.881516438356,
			"y": -1620.1168280805462,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 54.128734846966495,
			"height": 9.245591355848319,
			"seed": 95101200,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386719828,
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
					54.128734846966495,
					-9.245591355848319
				]
			]
		},
		{
			"type": "line",
			"version": 98,
			"versionNonce": 450841584,
			"isDeleted": false,
			"id": "s7FMUjqZLQUlwn1BVXqbQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.7134147773405,
			"y": -1620.5962001364862,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 54.46493816899749,
			"height": 15.465352813419031,
			"seed": 1241056240,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386716910,
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
					54.46493816899749,
					15.465352813419031
				]
			]
		},
		{
			"type": "line",
			"version": 84,
			"versionNonce": 2122296080,
			"isDeleted": false,
			"id": "GgwD9c6-BohruR4ic7S5H",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.5453131163251,
			"y": -1597.4946882104184,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 54.46493816899738,
			"height": 31.7712139319151,
			"seed": 723010832,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386716910,
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
					54.46493816899738,
					-31.7712139319151
				]
			]
		},
		{
			"type": "line",
			"version": 111,
			"versionNonce": 430035952,
			"isDeleted": false,
			"id": "xVWy5svh2qrr5jGYPsQZl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 614.881516438356,
			"y": -1597.2550021824484,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 53.45632820290484,
			"height": 7.228371423663248,
			"seed": 466412304,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386719828,
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
					53.45632820290484,
					-7.228371423663248
				]
			]
		},
		{
			"type": "text",
			"version": 501,
			"versionNonce": 679739376,
			"isDeleted": false,
			"id": "AMr5Zvkx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 666.5194161404712,
			"y": -1588.514786473385,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 21.7808837890625,
			"height": 11.98193449102359,
			"seed": 701383664,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386712989,
			"link": null,
			"locked": false,
			"fontSize": 9.585547592818873,
			"fontFamily": 1,
			"text": "yk(t)",
			"rawText": "yk(t)",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "yk(t)",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 296761104,
			"isDeleted": false,
			"id": "xzsoz7VtjoX-w-5mHjMh6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 682.4081626045412,
			"y": -1629.0420186053025,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 19.894714982662776,
			"height": 0,
			"seed": 411170288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386712989,
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
					19.894714982662776,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 83,
			"versionNonce": 1239319024,
			"isDeleted": false,
			"id": "yGhw5BasALDmzK75DCoql",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 682.6132627590016,
			"y": -1604.2248999155893,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 19.07431436482102,
			"height": 0,
			"seed": 744775664,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386712989,
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
					19.07431436482102,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 209,
			"versionNonce": 1479589648,
			"isDeleted": false,
			"id": "niUjIW4efpuPB8TKiTmLg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 657.559560570407,
			"y": -1532.196063229245,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 35.17900102212025,
			"height": 0,
			"seed": 1900119824,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
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
					35.17900102212025,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 296,
			"versionNonce": 260733424,
			"isDeleted": false,
			"id": "BeRNJzke",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 698.4143637229237,
			"y": -1535.6051993420574,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 48.74382019042969,
			"height": 6.840953400210211,
			"seed": 960125200,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
			"link": null,
			"locked": false,
			"fontSize": 5.472762720168168,
			"fontFamily": 1,
			"text": "values of context",
			"rawText": "values of context",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "values of context",
			"lineHeight": 1.25,
			"baseline": 4
		},
		{
			"type": "line",
			"version": 188,
			"versionNonce": 1608932624,
			"isDeleted": false,
			"id": "w4KfdFM4aEcc4fdjl4cwe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 657.1901947600257,
			"y": -1521.2609488892645,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 34.836576093978465,
			"height": 0.03998434631262171,
			"seed": 306679568,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704471,
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
					34.836576093978465,
					-0.03998434631262171
				]
			]
		},
		{
			"type": "text",
			"version": 106,
			"versionNonce": 1040563184,
			"isDeleted": false,
			"id": "hrYvIYC3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 700.7602346946034,
			"y": -1525.8379899506563,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 44.05207824707031,
			"height": 8.061161320877279,
			"seed": 911837968,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 6.448929056701823,
			"fontFamily": 1,
			"text": "hidden weights",
			"rawText": "hidden weights",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "hidden weights",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "text",
			"version": 145,
			"versionNonce": 1530411792,
			"isDeleted": false,
			"id": "oxQBWvhH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 699.3182333518299,
			"y": -1514.402347776777,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 46.93608093261719,
			"height": 8.061161320877279,
			"seed": 1960921360,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 6.448929056701823,
			"fontFamily": 1,
			"text": "output weights",
			"rawText": "output weights",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "output weights",
			"lineHeight": 1.25,
			"baseline": 6
		},
		{
			"type": "line",
			"version": 215,
			"versionNonce": 2128632816,
			"isDeleted": false,
			"id": "SvFL730oZz7V37OrSpodG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 656.8553345063733,
			"y": -1509.2664259723529,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffc9c9",
			"width": 34.836576093978465,
			"height": 0.03998434631262171,
			"seed": 1947339760,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386729320,
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
					34.836576093978465,
					-0.03998434631262171
				]
			]
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 211704080,
			"isDeleted": false,
			"id": "x9h16OzL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 486.66095345991,
			"y": -1664.174288753958,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 7.2520751953125,
			"height": 10.127500045730589,
			"seed": 1631807248,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 8.10200003658447,
			"fontFamily": 1,
			"text": "+1",
			"rawText": "+1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+1",
			"lineHeight": 1.25,
			"baseline": 7
		},
		{
			"type": "text",
			"version": 523,
			"versionNonce": 1440448496,
			"isDeleted": false,
			"id": "oBkUyOYk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -690.1849837847303,
			"y": -802.9856377181798,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 112.62974548339844,
			"height": 44.16320966636093,
			"seed": 1526632208,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 8.832641933272185,
			"fontFamily": 1,
			"text": "Activations are copied\nfrom hidden layers to\ncontext layers one-to-one\nfully distributed [7]",
			"rawText": "Activations are copied\nfrom hidden layers to\ncontext layers one-to-one\nfully distributed [7]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Activations are copied\nfrom hidden layers to\ncontext layers one-to-one\nfully distributed [7]",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 663795472,
			"isDeleted": false,
			"id": "oY25Aoii",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -688.4823315198412,
			"y": -690.3313946385956,
			"strokeColor": "#e03131",
			"backgroundColor": "#b2f2bb",
			"width": 118.72024536132812,
			"height": 20,
			"seed": 1455182832,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "* Stopped Here",
			"rawText": "* Stopped Here",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "* Stopped Here",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 834,
			"versionNonce": 1615200752,
			"isDeleted": false,
			"id": "PmAzcqVM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.7844132846083,
			"y": -2001.154775026618,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 23.264053344726562,
			"height": 20,
			"seed": 1991946000,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "2: ",
			"rawText": "2: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2: ",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 828,
			"versionNonce": 814175504,
			"isDeleted": false,
			"id": "AxmawdcK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.7844132846083,
			"y": -1904.160362860921,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 22.768051147460938,
			"height": 20,
			"seed": 715061744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "3: ",
			"rawText": "3: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3: ",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 837,
			"versionNonce": 2114995184,
			"isDeleted": false,
			"id": "kjeJeNfL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.7844132846083,
			"y": -1786.647901967866,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 22.112045288085938,
			"height": 20,
			"seed": 1866185488,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "4: ",
			"rawText": "4: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4: ",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 837,
			"versionNonce": 1559900944,
			"isDeleted": false,
			"id": "pS1kK2tV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.7844132846083,
			"y": -1686.85557406662,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffec99",
			"width": 21.760040283203125,
			"height": 20,
			"seed": 591396848,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1692386704472,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "5: ",
			"rawText": "5: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5: ",
			"lineHeight": 1.25,
			"baseline": 14
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#f08c00",
		"currentItemBackgroundColor": "#ffd8a8",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 0.5,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "triangle",
		"scrollX": -57.93126923195251,
		"scrollY": 1933.8139081192267,
		"zoom": {
			"value": 1.2902476802244638
		},
		"currentItemRoundness": "sharp",
		"gridSize": null,
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%
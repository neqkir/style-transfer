# style-transfer
style-transfer for authorship 

Deep Learning for Text Style Transfer: A Survey https://arxiv.org/pdf/2011.00416.pdf <sup>[1](#tst1)</sup>

Sometimes we have parallel data at hands ; for instance, a set of pairs of sentences, each pair expresses the same idea in a formal and informal way respectively. In a majority of cases no parallel data are available and the majority of text style transfer (TST) methods assume only non-parallel mono-style corpora. 

Three main branches of text style transfer methods for non-parallel data:

* disentanglement 
* prototype editing
* pseudo-parallel corpus construction 

*"Featuring more controllability and interpretability, prototype editing builds an explicit pipeline for text style transfer from x with attribute a to its counterpart x with attribute a:*

*Step 1) Detect attribute markers of a in the input sentence x, and delete them, resulting
in a content-only sentence*

*Step 2) Retrieve candidate attribute markers carrying the desired attribute a*

*Step 3) Infill the sentence by adding new attribute markers and make sure the generated
sentence is fluent"*

<a name="tst1">1</a>: [Xiaohan Ma, Fengquan Zhang, Huan Wei, Liuqing Xu,
Deep learning method for makeup style transfer: A survey,
Cognitive Robotics,
Volume 1,
2021,
Pages 182-187,
ISSN 2667-2413,
https://doi.org/10.1016/j.cogr.2021.09.001.]

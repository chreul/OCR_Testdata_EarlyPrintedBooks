# OCR_Testdata_EarlyPrintedBooks
A selection of test lines of several early printed books as well as the corresponding individual OCRopus models and mixed models.

## Data
LatinHist-98000.pyrnn.gz is a mixed OCRopus model trained on twelve Latin books printed with Antiqua types between 1471 and 1686 with a focus (ten out of twelve) on early works produced before 1600. For details about the books please see [1] . The training was performed on 8,684 lines and the best model was chosen by evaluating all resulting models on 2,432 previously unseen test lines. The lowest achieved CER was 2.92% after 98,000 training steps.

The Books folder contains seven early printed books used for evaluation in [2][3]. For each book we made 150 lines of GT available as well as a strong individual model (coming soon) trained on an extensive amount of lines (at least 1,500). For details about the books please see [2][3].

For additional GT for Latin, Greek and German Fraktur please see the [CIS OCR Testset](https://github.com/cisocrgroup/Resources/tree/master/ocrtestset).

## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" />
</a><br />All data available in this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Citation
Please cite (one of) the following publications when using the data.

### Latin Hist
[1] Springmann et al.. (2016). Automatic quality evaluation and (semi-) 
automatic improvement of OCR models for historical printings. 
[ArXiv e-prints](https://arxiv.org/abs/1606.05157).

```
@article{springmann2016automatic,
  title = {Automatic quality evaluation and (semi-) automatic
		  improvement of {OCR} models for historical printings},
  author = {Springmann, Uwe and Fink, Florian and Schulz, Klaus U},
  journal = {ArXiv e-prints},
  url = {https://arxiv.org/abs/1606.05157},
  year = {2016}
}
```

### Seven Mixed Early Printed Books
[2] Reul et al.. (2017). Improving OCR Accuracy on Early Printed Books by Utilizing Cross Fold Training and Voting. 
[ArXiv e-prints](https://arxiv.org/abs/1711.09670). Submitted to the 13th IAPR International Workshop on Document Analysis Systems.

```
@article{reul2017voting,
  title = {Improving {OCR} Accuracy on Early Printed Books by Utilizing Cross Fold Training and Voting},
  author = {Reul, Christian and Springmann, Uwe and Wick, Christoph and Puppe, Frank},
  journal = {ArXiv e-prints},
  url = {https://arxiv.org/abs/1711.09670},
  year = {2017}
}
```

[3] Reul et al.. (2017). Transfer Learning for OCRopus Model Training on Early Printed Books. [ArXiv e-prints](https://arxiv.org/abs/1712.05586). Submitted to 027.7 - Journal for Library Culture.

```
@article{reul2017transfer,
  title = {Transfer Learning for OCRopus Model Training on Early Printed Books},
  author = {Reul, Christian and Wick, Christoph and Springmann, Uwe and Puppe, Frank},
  journal = {ArXiv e-prints},
  url = {https://arxiv.org/abs/1712.05586},
  year = {2017}
}
```

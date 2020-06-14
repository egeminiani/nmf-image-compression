# Nonnegative Matrix Factorization and Image Compression 

<img src="https://raw.githubusercontent.com/egeminiani/nmf-image-compression/master/Figures/GIF/animation.gif" align="right" width = "320"/>

<br/><br/>
This repository contains a gentle introduction to **nonnegative matrix factorization** (NMF). It gives an overview of the method's technical details, the most common numerical algorithms for solving the factorization problem, and its recent extensions.

We consider two applications of NMF to the fields of image processing and text mining. <br/>
In the first project, the painting [*Madonna of the Goldfinch*](https://en.wikipedia.org/wiki/Madonna_del_cardellino) (Madonna del Cardellino) by the Italian artist Raphael is optimally compressed through a low-rank approximation of the pixel intensities matrix. <br/> 
In the second project, NMF is applied to recover the latent topics present in the [complete works](https://www.gutenberg.org/) by the English poet and playwright William Shakespeare and classify the document corpus accordingly. 

## Usage

The analysis code for the image processing application is contained in the R Markdown report `ImageCompression.Rmd`. <br/> 
If you just what to have a look at the rendered notebook, please refer to [`ImageCompression.html`](https://htmlpreview.github.io/?https://raw.githubusercontent.com/egeminiani/nmf-image-compression/master/ImageCompression.html). <br/>
The `Workspace` folder collects the workspace images with the estimated NMF models.

The text analysis of Shakespeare's works is illustrated in the [`Report on NMF`](https://github.com/egeminiani/nmf-image-compression/blob/master/Report%20on%20NMF.pdf) file (Section 2).

## :bookmark: Highlights

### :art: Image Compression

<p align="center">
<img width="700" src="https://raw.githubusercontent.com/egeminiani/nmf-image-compression/master/Figures/Compressed_images.png">
</p>

### :books: Topic Recovery and Document Classification

<p align="center">
<img width="800" src="https://raw.githubusercontent.com/egeminiani/nmf-image-compression/master/Figures/Mixture_coefficients_heatmap.png">
</p>

## Other

Suggestions and feedback are welcome [(mail)](mailto:elenageminiani@gmail.com)!

Link to notebook on Kaggle: [https://www.kaggle.com/elenageminiani/nmf-and-image-compression](https://www.kaggle.com/elenageminiani/nmf-and-image-compression).
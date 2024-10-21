---
layout: default
---

<!-- ![image](./assets/images/avatar.png)  -->
<!-- I am a Senior Applied Research Scientist at Adobe's Applied Research team working on language-vision research and Generative AI. I completed my PhD from the [CS](https://www.cs.rutgers.edu/) department at the [Intelligent Visual Interfaces](https://ivi.cs.rutgers.edu/) lab in [Rutgers University](http://newbrunswick.rutgers.edu/). My PhD thesis was on Multimodal Story Comprehension, under the supervision of [Dr. Mubbasir Kapadia](https://www.cs.rutgers.edu/~mk1353/) and [Dr. Gerard De Melo](http://gerard.demelo.org/). My research interests are on joint understanding of images/videos and abstract/narrative text with applications to multimodal story comprehension. Specificaly, story illustration, visual storytelling, image captioning and text-to-image retreival/generation. Recently, I have been working on Diffusion Models for Image generation and editing.
 -->
We are looking for summer research interns to work on image generation, editing problems. Reach to mevia email or linkedin if you are interested with your CV. 


# Software

Numerous works of mine have gone into Adobe's products. Here are some selected 


# Research

<head>
<style>
hr{
    height: 3px;
    background-color: #E9E9E9;
    border: none;
}
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

.left {
  width: 50%;
}

.right {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.btn {
  border: 1px solid black;
  background-color: white;
  color: black;
  padding: 2px 4px;
  text-align: center;
  display: inline-block;
  margin: 2px 1px;
  font-size: 16px;
  cursor: pointer;
}

/* Green */
.pdf {
  border-radius: 50px
  border-color: #4CAF50;
  color: green;
}

.pdf:hover {
  background-color: #4CAF50;
  color: white;
}

/* Blue */
.code {
  border-radius: 50px
  border-color: #2196F3;
  color: dodgerblue;
}

.code:hover {
  background: #2196F3;
  color: white;
}

/* Gray */
.bibtex {
  border-radius: 50px
  border-color: #e7e7e7;
  color: black;
}

.bibtex:hover {
  background: #e7e7e7;
}
</style>
</head>
<body>
<div class="row">
  <div class="column left">
<!--     <h2>Enhancing Controllability of Diffusion Models</h2> -->
<!--     <br><br> -->
    <img src="/img/gcdm_example.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:10%;"> 
  </div>
  <div class="column right">
    <div align="justify" font size="2">
        <h3>Enhanced Controllability of Diffusion Models via Feature Disentanglement and Realism-Enhanced Sampling Methods</h3>
        <br>
        <a href="https://wonwoongcho.github.io/" target="_blank">Wonwoong Cho</a>, 
        <strong>Hareesh Ravi</strong>,
        <a href="https://www.linkedin.com/in/midhun-harikumar-9574b524/" target="_blank">Midhun Harikumar</a>,
        <a href="https://www.linkedin.com/in/vinh-khuc-3390a52a/" target="_blank">Vinh Khuc</a>,
        <a href="https://krsingh.cs.ucdavis.edu/" target="_blank">Krishna Kumar Singh</a>,
        <a href="https://scholar.google.com/citations?user=jN2Y51YAAAAJ&hl=en&oi=ao" target="_blank">Jingwan Lu</a>,
        <a href="https://www.davidinouye.com/" target="_blank">David I. Inouye</a>,
        <a href="https://www.linkedin.com/in/kaleajinkya/" target="_blank">Ajinkya Kale</a>
        <br>
        ECCV 2024
        <br>
        <a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05452.pdf" target="_blank"><button class="btn pdf">pdf</button></a>
        <a href="" target="_blank"><button class="btn code">code</button></a>
        <a href="https://arxiv.org/abs/2302.14368" target="_blank"><button class="btn bibtex">bibtex</button></a>
        <a href="https://arxiv.org/abs/2302.14368" target="_blank"><button class="btn arxiv">arxiv</button></a>
    </div>
  <hr>
  </div>
<br>
</div>
<div class="row">
  <div class="column left">
<!--     <h2>PREDITOR</h2> -->
<!--     <br><br> -->
    <img src="/img/preditor_example.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:10%;"> 
  </div>
  <div class="column right">
    <div align="justify" font size="2">
        <h3>PREDITOR: Text Guided Image Editing with Diffusion Prior</h3>
        
<!--       We explore text guided image editing with a Hybrid Diffusion Model (HDM) architecture similar to DALLE-2. Our architecture consists of a 
diffusion prior model that generates CLIP image embedding conditioned on a text prompt and a custom Latent Diffusion Model trained to generate images conditioned on CLIP image embedding. We discover that the diffusion prior model can be used to perform text guided conceptual edits on the CLIP image embedding space without any finetuning or optimization. We combine this with structure preserving edits on the image decoder using existing approaches such as reverse DDIM to perform text guided image editing. Our approach, PRedItOR does not require additional inputs, fine-tuning, optimization or objectives and shows on par or better results than baselines qualitatively and quantitatively.  -->
<!--         We explore text guided image editing with a Hybrid Diffusion Model (HDM) architecture similar to DALLE-2. We discover that the diffusion prior model can be used to perform text guided conceptual edits on the CLIP image embedding space without any finetuning or optimization. PRedItOR does not require additional inputs, fine-tuning, optimization or objectives and shows on par or better results than baselines.  -->
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="https://arxiv.org/pdf/2302.07979.pdf" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="" target="_blank"><button class="btn code">code</button></a>
      <a href="https://arxiv.org/abs/2302.07979" target="_blank"><button class="btn bibtex">bibtex</button></a>
      <a href="https://arxiv.org/abs/2302.07979" target="_blank"><button class="btn arxiv">arxiv</button></a>
    </div>
  <hr>
  </div>
<br>
</div>
<div class="row">
  <div class="column left">
<!--     <h2>AESOP</h2>
    <br><br> -->
    <img src="/img/aesop_example.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:10%;"> 
  </div>
  <div class="column right">
    <div align="justify" font size="2">
        <h3>AESOP: Abstract Encoding of Storied Objects and Pictures</h3>
<!--       We introduce AESOP: a new dataset that captures the creative process associated with visual storytelling. Visual panels are composed of clip-art objects with specific attributes 
enabling a broad range of creative expression. Using AESOP, we propose foundational storytelling tasks that are generative variants 
of story cloze tests, to better measure the creative and causal reasoning ability required for visual storytelling. We further develop a 
generalized story completion framework that models stories as the co-evolution of visual and textual concepts. We benchmark the proposed 
approach with human baselines and evaluate using comprehensive qualitative and quantitative metrics. -->
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="https://openaccess.thecvf.com/content/ICCV2021/html/Ravi_AESOP_Abstract_Encoding_of_Stories_Objects_and_Pictures_ICCV_2021_paper.html" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="" target="_blank"><button class="btn code">code</button></a>
      <a href="https://openaccess.thecvf.com/content/ICCV2021/html/Ravi_AESOP_Abstract_Encoding_of_Stories_Objects_and_Pictures_ICCV_2021_paper.html" target="_blank"><button class="btn bibtex">bibtex</button></a>
      <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Ravi_AESOP_Abstract_Encoding_of_Stories_Objects_and_Pictures_ICCV_2021_paper.pdf" target="_blank"><button class="btn arxiv">arxiv</button></a>
    </div>
  <hr>
  </div>
<br>
</div>
<div class="row">
  <div class="column left">
    <h2>Visualize Your Story</h2>
    <br><br>
    <img src="/img/acl_2021.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:0%;"> 
  </div>
  <div class="column right">
    <div align="justify" font size="2">
      UNDER REVIEW: Story illustration is the task of illustrating a natural language story with a coherent sequence of images. 
We propose a more generalized task: Many-to-Many Story Illustration, i.e. automatic visualization of a textual story by a coherent sequence of 
images of any length. We introduce a novel many-to-many dataset created by aligning natural language descriptions with corresponding 
coherent sequence of images sampled from video clips. An end-to-end encoder-decoder neural architecture is proposed that sequentially 
retrieves a coherent sequence of images given an input story. User studies show the applicability of the proposed task and dataset 
and reveal that the illustrations generated by the proposed model are comparable to the ground truth.
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="" target="_blank"><button class="btn code">code</button></a>
      <a href="" target="_blank"><button class="btn bibtex">bibtex</button></a>
      <a href="" target="_blank"><button class="btn arxiv">arxiv</button></a>
    </div>
  <hr>
  </div>
<br>
</div>
<div class="row">
  <div class="column left">
    <h2>GitEvolve</h2>
    <br><br>
    <img src="/img/websci_2020_diag.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:0%;"> 
  </div>
  <div class="column right">
    <div font size="2">
      GitEvolve is a multi-task sequential deep network for simulation of future github events given past events for a particular repository. Each event is 
      characterized by a 3-tuple including type of the event, user cluster id and the time stamp of the event. The three tasks are
      trained simultaneously. Social structure of Github is further modelled by automatically learning graph based representation for each 
      repository. The effectiveness of the proposed technique is evaluated using an array of metrics.
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="https://arxiv.org/abs/2010.04366" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="https://github.com/hongluzhou/GitEvolve" target="_blank"><button class="btn code">code</button></a>
      <a href="/bib/gitevolve_arxiv.bib" target="_blank"><button class="btn bibtex">bibtex</button></a>
    </div>
  <hr>
  </div>
<br>
</div>
<div class="row">
<br>
  <div class="column left">
    <h2>Show Me a Story</h2>
    <br><br>
    <img src="/img/cvpr_2018_arch.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:0%;"> 
  </div>
  <div class="column right">
    <div font size="2">
      Story Illustration is the problem of retrieving/generating a sequence of images, 
      given a natural language story as input. We propose a hierarchical GRU network that learns 
      a representation for the input story and use it to retrieve an ordered set of images from a dataset. 
      In its core, the model is designed to explicitly model coherence between sentences in a story 
      optimized over sequential order embedding based loss function. The performance is qualitatively and quantitatively evaluated.
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="http://http://openaccess.thecvf.com/content_cvpr_2018/papers/Ravi_Show_Me_a_CVPR_2018_paper.pdf" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="https://github.com/Hareesh-Ravi/Show-Me-A-Story" target="_blank"><button class="btn code">code</button></a>
      <a href="/bib/showMeAStory_bib.bib" target="_blank"><button class="btn bibtex">bibtex</button></a>
    </div>
  <hr>
  </div>
</div>
<div class="row">
<br>
  <div class="column left">
    <h2>Anti-Forensic Enhancement</h2>
    <br><br>
    <img src="/img/ace_jvci.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:0%;"> 
  </div>
  <div class="column right">
    <div font size="2">
     Digital images can be convincingly edited using image editing tools. In order to identify such image pro-cessing operations, 
     various forensic techniques have been proposed. In response, anti-forensic operationsdesigned as counter-measures have been 
     devised. We propose an anti-forensic technique tocounter spatial domain forensic detectors and demonstrate its accuracy on 
     popular image manipulation operations such as median filtering and contrast enhancement. Through a series of experiments, 
     we prove that the proposed algorithm canseverely degrade the performance of median filtering and contrast enhancement detectors. 
     The proposedalgorithm also outperforms popular anti-forensic algorithms.
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="https://www.sciencedirect.com/science/article/pii/S1047320319303037" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="https://github.com/Hareesh-Ravi/" target="_blank"><button class="btn code">code</button></a>
      <a href="/bib/ace_jvci_bib.bib" target="_blank"><button class="btn bibtex">bibtex</button></a>
    </div>
  <hr>
  </div>
</div>
<div class="row">
<br>
  <div class="column left">
    <h2>Image Filtering Detection</h2>
    <br><br>
    <img src="/img/icip_2015.png" border="0" alt="avatar" align="left" style="border: none; float: left; border-radius:0%;"> 
  </div>
  <div class="column right">
    <div font size="2">
      Smart image editing and processing techniques make it easier to manipulate an image convincingly and also hide any artifacts of 
      tampering using operations like filtering, compression and/or format conversion to suppress forgery artifacts. We propose an 
      algorithm to detect if a given image has undergone filtering based enhancement irrespective of the format of image or the type
      of filter applied using spatial domain quantization noise. 
    </div>
  <div>
  <br>
    <div font size="2">
      <a href="https://drive.google.com/open?id=0B5F7NyiocdXvWHNvN1A5RnZMaE0" target="_blank"><button class="btn pdf">pdf</button></a>
      <a href="https://github.com/Hareesh-Ravi/Image-Filtering-Detection" target="_blank"><button class="btn code">code</button></a>
      <a href="/bib/icip_2015_bib.bib" target="_blank"><button class="btn bibtex">bibtex</button></a>
    </div>
  <hr>
  </div>
</div>
</body>

# Experience

List all activities 

<!-- ### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element. -->
```

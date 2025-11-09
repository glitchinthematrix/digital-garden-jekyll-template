---
layout: page
title: Home
id: home
permalink: /

---

<div style="display: flex; align-items: flex-start; gap: 1.5em;">
  <img src="/assets/potrait.jpg" alt="portrait" style="height:240px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.08); margin-top:0px; flex-shrink:0;">
  <span style="font-size:0.9em">
<p>
      I am currently a researcher at <a href="https://www.traversal.com/">Traversal</a> where I am developing agents that can navigate exabyte scale production software systems. 

      Previously, I was a PhD student at <a href="https://ece.princeton.edu/">Princeton</a> where I worked on scalable data-curation, architectures, and training objectives for large-scale generative models, with an emphasis on adaptive and efficient inference. I currently live in <s>Powai</s> <s>Princeton</s> <s>Philadelphia</s> New York City. 
      
      In a past life, I spent four years at <a href="https://www.iitb.ac.in/">IIT-Bombay</a> studying Electrical Engineering. I like running on obscure trails, <a href="/bookshelf/">books</a>, picking my guitar, thrifting antique <a href="/analog">cameras</a>, and development economics.
    </p>
  </span>
</div>

<span style="font-size:0.9em">
  [Twitter](https://x.com/bhish_98) / [Github](https://github.com/glitchinthematrix) / [LinkedIn](https://www.linkedin.com/in/bhishma-dedhia/) / <span style="position:relative;cursor:pointer;" onmouseover="this.querySelector('span').style.display='inline';" onmouseout="this.querySelector('span').style.display='none';">Email<span style="display:none;position:absolute;left:0;top:1.5em;background:#fff;border:1px solid #ccc;padding:2px 8px;border-radius:4px;white-space:nowrap;z-index:10;">firstname[dot]lastname[at]gmail[dot]com</span></span>
</span>

<!-- <strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul> -->



<h4>Selected Work (<a href="https://scholar.google.com/citations?user=tuBQ_uwAAAAJ&hl=en" target="_blank">scholar page</a>)</h4>

 <div class="pubentry">
  <div class="pubthumb">
  <a href="https://arxiv.org/abs/2507.13966"><img src="/assets/kg_si.png" style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
  </div>
  <div class="pubtext">
    <b>Bottom-up Domain-specific Superintelligence: A Reliable Knowledge Graph is What We Need</b><br />
    Bhishma Dedhia, Yuval Kansal, Niraj K Jha<br/>
    arXiv, under submission<br/>
    <a href="https://kg-bottom-up-superintelligence.github.io/">[website]</a> <a href="https://arxiv.org/abs/2507.13966">[arXiv]</a> <a href="https://arxiv.org/pdf/2507.13966.pdf">[pdf]</a> 
    </div>
  </div>

  <div class="pubentry">
  <div class="pubthumb">
<a href="https://arxiv.org/abs/2503.17539">
  <video src="/assets/vins.mp4" style="width: 100%; height: auto; box-shadow:0 2px 8px rgba(0,0,0,0.08);" autoplay loop muted playsinline></video>
</a>
  </div>
  <div class="pubtext">
    <b>Generating, Fast and Slow: Scalable Parallel Video Generation with Video Interface Networks</b><br />
    Bhishma Dedhia, David Bourgin, Krishna Kumar Singh, Yuheng Li, Yan Kang, Niraj K Jha,
    Yuchen Liu<br/>
   International Conference on Computer Vision (ICCV) 2025<br/>
    <a href="https://glitchinthematrix.github.io/vins/">[website]</a> <a href="https://arxiv.org/abs/2503.17539">[arXiv]</a> <a href="https://arxiv.org/pdf/2503.17539.pdf">[pdf]</a> 
    </div>
  </div>

  <div class="pubentry">
    <div class="pubthumb">
    <a href="https://arxiv.org/abs/2403.07887"><img src="/assets/nsi.png"  style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
    </div>
    <div class="pubtext">
      <b>Neural Slot Interpreters: Grounding Object Semantics in Emergent Slot Representations</b><br />
      Bhishma Dedhia, Niraj K Jha<br />
      Transactions of Machine Learning Research (TMLR), 2025<br />
     <a href="https://arxiv.org/abs/2403.07887">[arXiv]</a> <a href="https://arxiv.org/pdf/2403.07887.pdf">[pdf]</a> <a href="https://github.com/jha-lab/neural-slot-interpreters">[code]</a> 
      </div>
  </div>

  <div class="pubentry">
    <div class="pubthumb">
    <a href="https://arxiv.org/abs/2305.17328"><img src="/assets/zero_t_prune.gif" style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
    </div>
    <div class="pubtext">
      <b>Zero-TPrune: Zero-Shot Token Pruning through Leveraging of the Attention Graph in Pre-Trained Transformers</b><br />
      Hongjie Wang, Bhishma Dedhia, Niraj K Jha<br />
      Conference on Computer Vision and Pattern Recognition (CVPR), 2024<br />
      <a href="https://zerotprune.github.io/">[website]</a> <a href="https://arxiv.org/abs/2305.17328">[arXiv]</a> <a href="https://arxiv.org/pdf/2305.17328.pdf">[pdf]</a>
      </div>
  </div>
  
<div class="pubentry">
        <div class="pubthumb">
        <a href="https://arxiv.org/abs/2305.17262"> <img src="/assets/impromptu.gif" style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
        </div>
        <div class="pubtext">
          <b>Im-Promptu: In-Context Composition from Image Prompts</b><br />
          Bhishma Dedhia, Michael Chang, Jake C. Snell, Thomas L. Griffiths, Niraj K. Jha<br />
          Neural Information Processing Systems (NeurIPS), 2023 <br />
          <a href="https://jha-lab.github.io/impromptu/">[website]</a> <a href="https://arxiv.org/abs/2305.17262">[arXiv]</a> <a href="https://arxiv.org/pdf/2305.17262.pdf">[pdf]</a>  <a href="https://github.com/JHA-Lab/impromptu">[code]</a>
          </div>
</div>


       
<div class="pubentry">
    <div class="pubthumb">
      <a href="https://arxiv.org/abs/2207.04208"> <img src="/assets/scout.png" style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
    </div>
    <div class="pubtext">
      <b>SCouT: Synthetic Counterfactuals via Spatiotemporal Transformers for Actionable Healthcare</b><br />
      Bhishma Dedhia<sup>* </sup>, Roshini Balasubramanian<sup>* </sup>, Niraj K Jha<br />
      ACM Transactions on Computing for Healthcare 2023<br />
      <a href="https://arxiv.org/abs/2207.04208">[arXiv]</a> <a href="https://arxiv.org/pdf/2207.04208.pdf">[pdf]</a> <a href="https://github.com/jha-lab/scout">[code]</a>
    </div>
</div>
      
      

<div class="pubentry">
  <div class="pubthumb">
  <a href="https://arxiv.org/abs/2205.11656"><img src="/assets/flexibert.png" style="box-shadow:0 2px 8px rgba(0,0,0,0.08)"/></a>
  </div>
  <div class="pubtext">
    <b>FlexiBERT: Are Current Transformer Architectures too Homogeneous and Rigid?</b><br />
    Shikhar Tuli, Bhishma Dedhia, Shreshth Tuli, Niraj K Jha<br />
    Journal of AI Research 2023<br />
    <a href="https://arxiv.org/abs/2205.11656">[arXiv]</a> <a href="https://arxiv.org/pdf/2205.11656.pdf">[pdf]</a> <a href="https://github.com/JHA-Lab/txf_design-space">[code]</a>
  </div>
</div>



<style>
  .wrapper {
    max-width: 46em;
  }
</style>

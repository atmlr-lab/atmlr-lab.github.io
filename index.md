---
title: Home
layout: default
---
<body>
   <div class="container">
      <div class="row-fluid">
         <div class="span12">
            <div id="main-carousel" class="carousel slide">
               <div class="carousel-inner">
                  <div class="item active">
                     <img src="images/ot_kme.jpg" class="carousel-image" alt="">
                     <div class="carousel-caption">
                        <h4>NeurIPS 2020: Statistical Optimal Transport posed as learning Kernel Mean Embedding</h4>
                        <p></p>
                     </div>
                  </div>
                  <div class="item">
                     <img src="images/cot.jpg" class="carousel-image" alt="">                      
                     <div class="carousel-caption">
                        <h4>AISTATS 2024: Consistent Optimal Transport with Empirical Conditional Measures</h4>
                        <!-- -->
                        <p></p>
                     </div>
                  </div>
                  <div class="item">
                     <img src="images/uot.jpg" class="carousel-image" alt="">                      
                     <div class="carousel-caption">
                        <h4>TMLR 2024: MMD-Regularized Unbalanced Optimal Transport</h4>
                        <!-- -->
                        <p></p>
                     </div>
                  </div>                     
                  <div class="item">
                     <img src="images/sea-nn.jpg" class="carousel-image" alt="">                      
                     <div class="carousel-caption">
                        <h4>AISTATS 2022: Submodular Ensembled Attribution for Neural Networks</h4>
                        <!-- -->
                        <p></p>
                     </div>
 Test

                 </div>
               </div>
               <a class="left carousel-control" href="#main-carousel" data-slide="prev">‹</a>
               <a class="right carousel-control" href="#main-carousel" data-slide="next">›</a>
            </div>
         </div>
      </div>
      <hr>
      <div class="container-fluid">
         <div class="row-fluid marketing">
            <div class="span12">
               <h4>This website belongs to the ATMLR lab supervised by <a href="http://www.iith.ac.in/~saketha">Dr J. SakethaNath</a>.  
               </h4>
               <br/>
            </div>
            <div class="row-fluid">
               <hr>
               <h2 class="centered">Recent News</h2>
               <hr>
            </div>
			<div class="span12">

<!-- This might be hacky, need to investigate further -->
{% assign pubs = site.publications | reverse %}
{% for publication in pubs limit:3 %}
<div class="span4 feature-item">
  <h5> 
	<span class="date">{{publication.date | date: "%B %Y" }}</span>
  </h5>
<h4 class="feature-heading">
    "{{publication.title}}"
    <p style="color:red;">Accepted at {{publication.venue}}!</p>
</h4>
<p>
Read the paper at 
<a href="{{publication.pdfurl}}">here</a>.
</p>
<br/>
</div> 
{% endfor %}
</div>
<div class="span12">
			
{% for publication in pubs limit:3 offset:3%}
<div class="span4 feature-item">
  <h5> 
	<span class="date">{{publication.date | date: "%B %Y" }}</span>
  </h5>
<h4 class="feature-heading">
    "{{publication.title}}"
    <p style="color:red;">Accepted at {{publication.venue}}!</p>
</h4>
<p>
Read the paper at 
<a href="{{publication.pdfurl}}">here</a>.
</p>
<br/>
</div> 
{% endfor %}
</div>
</div>
</div>
   </div>
</body>

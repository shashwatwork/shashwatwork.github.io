---
layout: archive
permalink: /blog/
author_profile: true
title: "By Topic"
layouts_gallery:
  - url: https://shashwatwork.github.io/ml/
    image_path: /assets/images/ml_short.jpg
  - url: https://shashwatwork.github.io/dl/
    image_path: /assets/images/dl_short.png
  - url: https://shashwatwork.github.io/cv/
    image_path: /assets/images/cv_short.png
  - url: https://shashwatwork.github.io/rl/
    image_path: /assets/images/rl_short.jpg
  - url: https://shashwatwork.github.io/bd/
    image_path: /assets/images/bd_short.jpg

---


<style>

  @import "compass/css3";

  /* Some vars */
  $background-color: hsl(50, 5, 97);
  $black: hsl(200, 40, 10);
  $white: $background-color;
  $base-font-size: 2.4em;
  $base-line-height: 1.5em;

  .ludwig {
  position: relative;
  padding-left: 1em;
  border-left: 0.2em solid lighten($black, 40%);
  font-family: 'Roboto', serif;
  font-size: $base-font-size;
  line-height: $base-line-height;
  font-weight: 100;
  &:before, &:after {
      content: '\201C';
      font-family: 'Sanchez';
      color: lighten($black, 40%);
   }
   &:after {
      content: '\201D';
   }
  }

.column {
  align-content:center;
  float: left;
  width: 50%;
  height: 100%;
}

.column_home {
  align-content:center;
  float: left;
  width: 20%;
  height: 100%;
}


.center_text {
  align-content:center;
  width: 50%;
  vertical-align: middle;
  text-align:justify;
  text-align-last: center;
}

#left-col {
  align-content:center;
  text-align: center;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

* {
  box-sizing: border-box;
}

i {
  font-size: 0.4em;
}


#right-col {
  align-content:center;
  text-align: center;
}
</style>

I have written more than 20 articles so far, so feel free to explore the different topics by clicking on the buttons below.

{% include gallery id="layouts_gallery" class="full" layout="half"%}


# Latest Articles
[AI/ML Cheat Sheet 2020](https://shashwatwork.github.io/machinelearning/article_1) : Collection of Online Resources Related to Machine Learning and Deep Learning.
<br>

[Reinforcement Learning — Beginner’s Approach Chapter -II](https://medium.com/analytics-vidhya/reinforcement-learning-beginners-approach-chapter-ii-a72e415c57ca) :Blog introduces  Reinforcement learning algorithms for Beginners.
<br>

[Machine learning Cheat Sheat Naive Bayes](https://medium.com/analytics-vidhya/machine-learning-cheat-sheet-naive-bayes-56a8ea5bb610) :A Quick pointers for Machine Learning Algorithms core concepts.
<br>

[Machine learning Cheat Sheat KNN Algorithm](https://datasciencehub.medium.com/machine-learning-cheat-sheet-k-nearest-neighbors-algorithm-93462a66831) :A Quick pointers for Machine Learning Algorithms core concepts.

# Medium Articles
<br>

<div id="medium-widget"></div>
<script src="https://medium-widget.pixelpoint.io/widget.js"></script>
<script>MediumWidget.Init({renderTo: '#medium-widget', params: {"resource":"https://medium.com/@datasciencehub","postsPerLine":2,"limit":10,"picture":"big","fields":["description","author","claps","publishAt"],"ratio":"landscape"}})</script>


<br>

<input type="button" onclick="location.href='https://medium.com/@datasciencehub';" value="See All" />
<br>

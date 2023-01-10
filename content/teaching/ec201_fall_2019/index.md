---
title: EC 201 Introduction to Economic Analysis, Microeconomics
subtitle: Teaching Assistant, Fall 2019
date: 2019-01-05T07:16:18.548Z
draft: false
featured: false
authors:
  - P.
  - Economides
image:
  filename: course_pic.jpg
  focal_point: Smart
  preview_only: false
---

<details>
Provided two microeconomic labs to sets of students in the evenings of the term, assisting them with lecture content and homework assignments. 
<font size= "3">
  <summary>Details</summary>
           <p></br>16/77 responses across two surveys. End of term comments included:
  </p>
</font>
         </details>
         
<style>
  .button {
    background-color: #003f5c;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 12px;
    margin: 4px 2px;
    cursor: pointer;
  }
  
  #reviewText {
  font-size: smaller;
}
  
  #reviewTitle {
  font-size: medium;
}
</style>

<a class="button" onclick="previousReview()">Previous Review</a>
<a class="button" onclick="nextReview()">Next Review</a>

<script>
  var currentReview = 0;
  var reviews = [
    {
      "title": "Review 1",
      "text": "The GEs were awesome they really helped with my learning."
    },
    {
      "title": "Review 2",
      "text": "Philip is a great guy and very willing to work with you if you ask."
    },
    {
      "title": "Review 3",
      "text": "the GE would answer our questions very clearly"
    },
    {
      "title": "Review 4",
      "text": "The GE clarified a lot of material that was covered in the lecture, and it was very helpful."
    },
    {
      "title": "Review 5",
      "text": "It was helpful to clarify various topics with the GE about the lecture, making a stronger learning experience."
    },
    {
      "title": "Review 6",
      "text": "I felt that everything he talked about was relevant to my learning."
    },
    {
      "title": "Review 7",
      "text": "I wish we could have had homework assignments so that we could practice the content we are being taught."
    },
    {
      "title": "Review 8",
      "text": "I wish this course was a little bit longer in time to tie all loose ends"
    },
    {
      "title": "Review 9",
      "text": "Loved it."
    },
    {
      "title": "Review 10",
      "text": " It was easy to ask questions and receive help"
    },
    {
      "title": "Review 11",
      "text": "Example problems and additional lectures thoroughly help me to learn more about microeconomics."
    },
    {
      "title": "Review 12",
      "text": " Nothing I would change."
    },
    {
      "title": "Review 13",
      "text": "class is extremely helpful"
    }
  ];

  function previousReview() {
    currentReview--;
    if (currentReview < 0) {
      currentReview = reviews.length - 1;
    }
    displayReview();
  }

  function nextReview() {
    currentReview++;
    if (currentReview >= reviews.length) {
      currentReview = 0;
    }
    displayReview();
  }

  function displayReview() {
    document.getElementById("reviewTitle").innerHTML = reviews[currentReview].title;
    document.getElementById("reviewText").innerHTML = reviews[currentReview].text;
  }
</script>
  
<h2 id="reviewTitle">Review 1</h2>
<p id="reviewText">	The GEs were awesome they really helped with my learning.</p>

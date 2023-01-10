---
title: EC 380 International Economic Issues
subtitle: Fall 2022
date: 2022-01-05T07:16:18.548Z
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

Exchange across international boundaries, theory of comparative advantage, balance of payments and adjustments, international financial movements, exchange rates and international financial institutions, trade restrictions and policy.

<font size= "3">
  <summary>Comments</summary>
           <p></br>12/41 responses across two surveys. End of term comments included:
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
      "text": "Professor was extremely helpful and communicative throughout the entire term. Cared about students."
    },
    {
      "title": "Review 2",
      "text": "This is by far the best class I've ever had. Please go into academe ... we need professors like you."
    },
    {
      "title": "Review 3",
      "text": "Though I have criticisms of the course, I want to also acknowledge Philip's readiness to adapt to feedback from students. Following the midterm course evaluation, he made changes which positively impacted the class based on student suggestions. His willingness to listen to students and hear our concerns was beneficial, and I feel that it was a strength of his (along with individual support in course material)."
    },
    {
      "title": "Review 4",
      "text": "The instructor is always more than willing to help with a problem no matter the question or time. That is incredibly important to my learning in this course."
    },
    {
      "title": "Review 5",
      "text": "Instructor very helpful, always willing to communicate and help."
    },
    {
      "title": "Review 6",
      "text": "It would be nice if course material better prepared us for problem sets/quizzes."
    },
    {
      "title": "Review 7",
      "text": "The lectures could move quite a bit faster and cover more material."
    },
  {
      "title": "Review 8",
      "text": "Lectures are taught too fast to write notes. Instructions for assignments are hard to interpret. Communication needs to be better with the lab assistant on teaching R."
    },
  {
      "title": "Review 9",
      "text": "I have experienced a lot of accessibility problems in terms of technology with the course."
    },
   {
      "title": "Review 10",
      "text": "I've never had an instructor before who coupled so well being incredibly kind and accessible and supportive with also challenging me to constantly keep working to improve--whether it's a better data cleaning strategy or piece of code or conceptual understanding (even if Mas-Colell is still beyond me). I learned more in this class than any other class that I've taken, all due to a combination of immense patience and high standards, which combined to both demand and facilitate high-quality work."
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
<p id="reviewText">Professor was extremely helpful and communicative throughout the entire term. Cared about students.</p>
         

👉 [See Github Resources](https://github.com/peconomi/EC380_International)

---
title: ECO 4331 Economics of Multinational Enterprises
subtitle: Instructor, Fall 2025
date: 2024-01-05T07:16:18.548Z
lastmod: 2026-07-13T00:00:00.000Z
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
  <summary>Details</summary>
  <p>
    The economics of multinational enterprises examines why firms expand across borders, how they organize production internationally, and how public policy shapes those decisions. I split this course into three components: (i) <strong>Trade Costs and Multinational Formation</strong> - studying why firms serve foreign markets through exporting, licensing, or foreign direct investment; (ii) <strong>Global Production and Firm Strategy</strong> - examining horizontal and vertical FDI, international sourcing, and the organization of production across countries; and (iii) <strong>Policy and Corporate Responsibility</strong> - considering international taxation, profit shifting, environmental and social responsibility, and the broader consequences of multinational activity.
  </p>
  <p>
    Student evaluations were available for Fall 2025. The course received 7 responses from 25 possible respondents. Selected end-of-term comments, lightly edited only for spelling and punctuation, appear below.
  </p>
</details>

<details>
  <summary>Performance Metrics</summary>

| Question Text | Fall 2025 | ECO Avg |
|---|---:|---:|
| Course assignments facilitated learning | 4.7 | 4.5 |
| Course was organized | 4.6 | 4.5 |
| Opportunities to be successful in course | 4.6 | 4.5 |
| Overall course helped learn required concepts/skills | 4.3 | 4.4 |
| Instructor presented material in a way that helped engage in course | 4.6 | 4.4 |
| Instructor helped students understand the relevance of course content | 4.7 | 4.5 |
| Instructor tailored instructions/lessons to a variety of perspectives | 4.7 | 4.4 |
| Overall, instructor's teaching methods helped students learn course content | 4.6 | 4.4 |

</details>

<style>
  .review-controls {
    display: flex;
    gap: 0.5rem;
    margin: 1rem 0;
  }

  .review-button {
    background-color: #003f5c;
    border: none;
    color: white;
    padding: 0.75rem 1.25rem;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 0.85rem;
    cursor: pointer;
    border-radius: 2px;
  }

  .review-button:hover,
  .review-button:focus {
    opacity: 0.88;
  }

  #reviewText {
    font-size: 0.95rem;
    line-height: 1.55;
    max-width: 900px;
  }

  #reviewTitle {
    font-size: 1.15rem;
    margin-bottom: 0.35rem;
  }

  #reviewCounter {
    font-size: 0.8rem;
    opacity: 0.7;
  }
</style>

<div class="review-controls">
  <button class="review-button" type="button" onclick="previousReview()">Previous Review</button>
  <button class="review-button" type="button" onclick="nextReview()">Next Review</button>
</div>

<h2 id="reviewTitle"></h2>
<p id="reviewText" aria-live="polite"></p>
<p id="reviewCounter"></p>

<script>
  var currentReview = 0;
  var reviews = [
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "Everything."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "The problem sets could be somewhat time-consuming, but they have been very helpful in preparing for the exams. The exams are somewhat difficult, but when finished, I feel as if I've retained a solid amount of the course material."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "His lectures are always so cohesive with the problem sets, tests, and class meetings."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "Nothing."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "The percentage of your final grade attributed to problem sets is just a tad too high."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "I wish that, for quantitative problems, we stopped and solved sample problems to fully understand."
    },
    {
      "title": "Fall 2025 - Additional comment",
      "text": "Dr. Economides turned what I thought would be a boring and forgettable class into something much more interesting. I found him to be a great professor."
    },
    {
      "title": "Fall 2025 - Additional comment",
      "text": "Wonderful teacher. I have taken his classes twice and will take another next semester. He is always responsive and accessible outside of class!"
    }
  ];

  function previousReview() {
    currentReview = (currentReview - 1 + reviews.length) % reviews.length;
    displayReview();
  }

  function nextReview() {
    currentReview = (currentReview + 1) % reviews.length;
    displayReview();
  }

  function displayReview() {
    document.getElementById("reviewTitle").textContent = reviews[currentReview].title;
    document.getElementById("reviewText").textContent = reviews[currentReview].text;
    document.getElementById("reviewCounter").textContent =
      "Review " + (currentReview + 1) + " of " + reviews.length;
  }

  displayReview();
</script>

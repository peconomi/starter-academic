---
title: ECO 3333 International Economics
subtitle: Instructor, Fall ('24,'25,'26)
date: 2024-01-05T07:16:18.548Z
lastmod: 2026-07-13T00:00:00.000Z
draft: false
featured: false
authors:
  - P. Economides
image:
  filename: course_pic.jpg
  focal_point: Smart
  preview_only: false
---

<details>
  <summary>Details</summary>
  <p>
    Exchange across international boundaries, theory of comparative advantage, balance of payments and adjustments, international financial movements, exchange rates and international financial institutions, trade restrictions and policy. I split this course into three components: (i) <strong>Trade Theory</strong> - using the older models to highlight the gains from trade and potential ambiguity of labor market outcomes; (ii) <strong>Trade Policy</strong> - shifting away from the extremes of autarky and free trade to varying degrees of trade openness through tariff adjustments and import quotas; and (iii) <strong>Global Finance</strong> - providing a broad understanding of exchange-rate movements and associated monetary policy.
  </p>
  <p>
    Student evaluations were available for Fall 2024 and Fall 2025. Fall 2024 received 3 responses from 20 possible respondents, while Fall 2025 received 8 responses from 22 possible respondents. Selected end-of-term comments, lightly edited only for spelling and punctuation, appear below.
  </p>
</details>

<details>
  <summary>Performance Metrics</summary>

The combined averages weight each semester by its number of respondents (3 in Fall 2024 and 8 in Fall 2025).

| Question Text | Fall 2024 | Fall 2025 | Combined Avg | ECO Avg |
|---|---:|---:|---:|---:|
| Course assignments facilitated learning | 5.0 | 4.5 | 4.6 | 4.5 |
| Course was organized | 4.7 | 4.8 | 4.8 | 4.5 |
| Opportunities to be successful in course | 5.0 | 4.0 | 4.3 | 4.5 |
| Overall course helped learn required concepts/skills | 4.7 | 4.5 | 4.6 | 4.4 |
| Instructor presented material in a way that helped engage in course | 4.7 | 4.1 | 4.3 | 4.4 |
| Instructor helped students understand the relevance of course content | 5.0 | 4.6 | 4.7 | 4.5 |
| Instructor tailored instructions/lessons to a variety of perspectives | 4.0 | 4.5 | 4.4 | 4.4 |
| Overall, instructor's teaching methods helped students learn course content | 4.7 | 4.1 | 4.3 | 4.4 |

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
      "title": "Fall 2024 - Most effective aspect",
      "text": "I think the most effective aspect of the course was the inclusion of the real-world examples."
    },
    {
      "title": "Fall 2024 - Most effective aspect",
      "text": "Office hours and the one on one support from my professor."
    },
    {
      "title": "Fall 2024 - Least effective aspect",
      "text": "I can't recall any aspects of the course that were ineffective."
    },
    {
      "title": "Fall 2024 - Least effective aspect",
      "text": "The fast paced lecture heavy content. It was all concepts and little to no examples to allow me to visualize and fully understand."
    },
    {
      "title": "Fall 2024 - Additional comment",
      "text": "Really great professor who taught in a clear and concise manner. Always there for us when we had any questions."
    },
    {
      "title": "Fall 2024 - Additional comment",
      "text": "Great teacher."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "I think the homework really did prepare me for the questions on the exams."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "I'd like to say the problem sets really helped me understand the material."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "The problem sets were extremely helpful for the exams."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "Simple explanations."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "In class work-throughs with equations."
    },
    {
      "title": "Fall 2025 - Most effective aspect",
      "text": "The instructor has always been helpful when I have had doubts about the information in lectures and problem sets."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "It would take a long time to receive grades and feedback on exams."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "The long homework and difficult exams that were meant to make you fail, not show what you have learned."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "No specific review paper for exams."
    },
    {
      "title": "Fall 2025 - Least effective aspect",
      "text": "No communication with the TA - the one who's grading everything."
    },
    {
      "title": "Fall 2025 - Additional comment",
      "text": "The professor was very good at explaining the material and answering all questions in a clear and understanding way."
    },
    {
      "title": "Fall 2025 - Additional comment",
      "text": "The quizzes made sense, but then the homework problems and exams were very difficult."
    },
    {
      "title": "Fall 2025 - Additional comment",
      "text": "Great Semester!"
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

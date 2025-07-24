---
title: "Research"
layout: gridlay
sitemap: false
permalink: /Research/
---

<style>
.toggle-btn {
  background-color: #eee;
  border: none;
  padding: 5px 10px;
  font-size: 0.9rem;
  cursor: pointer;
  margin-bottom: 5px;
  display: inline-block;
}

.abstract-text {
  display: none;
  background: #f9f9f9;
  border-left: 3px solid #ccc;
  padding: 10px;
  margin-bottom: 20px;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
  const buttons = document.querySelectorAll(".toggle-btn");
  buttons.forEach(btn => {
    btn.addEventListener("click", function() {
      const content = this.nextElementSibling;
      const isVisible = content.style.display === "block";
      content.style.display = isVisible ? "none" : "block";
      this.textContent = isVisible ? "Show Abstract" : "Hide Abstract";
    });
  });
});
</script>


<h2>Research</h2>
<p><strong>Research interest:</strong> Banking, Fintech, Corporate Finance, Household Finance, Financial Innovation, Applied Artificial Intelligence</p>

<h3>Working Papers</h3>

<p><strong>"Human-AI Synergy in Marketplace Lending: Complementary Strength or Redundancy?"</strong>, JMP</p>
<div class="abstract-toggle">
  <button class="toggle-btn">Show Abstract</button>
  <div class="abstract-text">
    <p>As artificial intelligence (AI) plays an increasingly pivotal role in financial decision-making, a key question arises: does AI complement or substitute human judgment in credit markets? This study examines the performance of two Fintech lending strategies, Human+AI and Algorithm+AI, using instrumental variable (IV) and difference-in-differences (DiD) methodologies...</p>
  </div>
</div>

<p><strong>"Harnessing Artificial Intelligence: Impact of AI Adoption on Bank Loan Performance"</strong>, (under review), with Hugh Hoikwang Kim</p>
<div class="abstract-toggle">
  <button class="toggle-btn">Show Abstract</button>
  <div class="abstract-text">
    <p>This paper examines the impact of AI adoption on bank loan performance, focusing on non-performing loans (NPLs)...</p>
  </div>
</div>

<p><strong>"Who can we rely on? Banks, Marketplace lenders, or People"</strong>, (under review), with Sarah Carrol</p>
<div class="abstract-toggle">
  <button class="toggle-btn">Show Abstract</button>
  <div class="abstract-text">
    <p>Credit supply plays a crucial role in the economy, especially during periods of economic and financial crises...</p>
  </div>
</div>

<h3>Work in Progress</h3>
<ul>
  <li>Learning the Wrong Lesson: How AI Mislabels Borrower Risk During Crises (Solo paper)</li>
  <li>Built in discrimination: How fair algorithms are unfair (Solo paper)</li>
  <li>Unveiling the Role of AI Recommender Systems in Safeguarding Against Financial Misinformation (Solo)</li>
  <li>Understanding AI Regulation: Measuring State-Level Legislative Restrictiveness, with Shishir Shakya</li>
</ul>


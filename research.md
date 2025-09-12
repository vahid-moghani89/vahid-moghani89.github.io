---
layout: page
title: "Research"
permalink: /research/
# TODO: replace with your actual working-paper URL:
rdd_wp_url: "/documents/Moghani_Badri_RDD_MultipleThresholds.pdf"
---

<!--
  Accordion styles; you can move these to assets/css/main.scss if you prefer.
-->
<style>
.accordion {
  border: 1px solid #ddd;
  border-radius: 4px;
  margin-bottom: 1.5rem;
  overflow: hidden;
}

.accordion summary {
  background-color: #f7f7f7;
  padding: 0.75rem 1rem 0.75rem 2.5rem;
  font-size: 1.1rem;
  font-weight: 600;
  cursor: pointer;
  list-style: none;
  position: relative;
}

.accordion[open] summary {
  background-color: #e2e2e2;
}

.accordion summary::-webkit-details-marker { display: none; }

.accordion summary::before {
  content: '▶';
  position: absolute;
  left: 1rem;
  top: 50%;
  transform: translateY(-50%);
  transition: transform 0.2s ease;
  font-size: 0.9rem;
}

.accordion[open] summary::before {
  transform: translateY(-50%) rotate(90deg);
}

.accordion .content {
  padding: 1rem;
  border-top: 1px solid #ddd;
}

.accordion .content p { margin: 0 0 1rem; }
.accordion .content a { color: #0066cc; text-decoration: none; }
.accordion .content a:hover { text-decoration: underline; }
</style>

# Working Papers

<details class="accordion" markdown="1">
<summary>Difference Estimation for Regression Discontinuity with Multiple Ordered Thresholds</summary>

With Saeed Badri. <a href="{{ page.rdd_wp_url }}" target="_blank" rel="noopener noreferrer">Working paper</a>.

**Abstract** – This paper develops an estimator for regression discontinuity designs (RDD) with multiple thresholds. We construct an integrated–derivative estimator that recovers the outcome difference by numerically integrating nonparametric slope estimates between thresholds. We derive its asymptotic distribution, establishing a central limit theorem with a feasible variance formula. The integrated estimator is asymptotically independent of the standard boundary estimator, which enables an inverse–variance combination that is more efficient. Simulations confirm the theoretical predictions: efficiency gains are modest under uniform designs and more pronounced when data are sparse near the cutoffs.

</details>

<details class="accordion" markdown="1">
<summary>Childhood Mental Health Effects of Early-Life Exposure to a Parental Job Loss</summary>

With Pilar García-Gómez and Tom Van Ourti. _Draft available upon request._
**Abstract** – We study the mental health effects of early life exposure to paternal job loss. Using nationwide individual‑level administrative register records, we focus on firm‑closure‑induced job losses for fathers with children below age five in the Netherlands. These children are more likely to take mental health‑related medicines in their later childhood, and this increase is mainly driven by psychostimulant drugs. The increased uptake of psychostimulants ranges from 15 percent of mean uptake in the control group at age five to around 9 percent at age twelve. The effects are significantly larger for families with mothers being the main breadwinner, suggesting that the drop in paternal income resulting from displacement is not the main driver of psychostimulant uptake. We further find that the father is more likely to take mental health medication around the time of job loss, and that the children exposed to paternal job loss are more likely to live in dissolved families. We find no evidence of exposed children living in neighborhoods with different rates of psychostimulant consumption compared to control children, while parents of treated children do report more impulsive behavior and inattention symptoms.

</details>

<details class="accordion" markdown="1">
<summary>Mental Health Literacy, Beliefs and Demand for Support among University Students</summary>

Under review. With Michelle Acampora and Francesco Capozza.
[Working paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4261487){:target="_blank" rel="noopener noreferrer"}.

**Abstract** – This paper assesses the impact of a mental health literacy intervention on the demand for mental health support among university students. We run a field experiment with 2,978 students at a large Dutch university. The intervention raises willingness to pay and demand for a mental-health app among male respondents, and shifts information demand from psychological counselling toward coaching—driven by students with moderate distress. Increased perceived effectiveness of low-intensity therapy appears to be the mechanism. A three-week follow-up suggests a moderate improvement in mental-health scores for treated female students, consistent with higher care-seeking.

# Work in Progress

<details class="accordion" markdown="1">
<summary>Workplace and Health</summary>
<div class="content" markdown="1">
This project studies how firms shape workers’ healthcare use and long-term health. Using Dutch administrative employer–employee data linked to individual healthcare expenditures, I estimate AKM two-way fixed effects with KSS correction to isolate firm contributions beyond worker characteristics and insurance access. A one-SD difference in firm effects translates into large changes in healthcare costs and predicts future disability and mortality risks, even after rich controls, highlighting the workplace as a lever for health policy.
</div>
</details>

<details class="accordion" markdown="1">
<summary>The Determinants of Demand for Mental Health Support</summary>
<div class="content" markdown="1">
With Sonia Bhalotra and Francesco Capozza.
</div>
</details>

<details class="accordion" markdown="1">
<summary>Measuring Uncertainty Perception in the Health Domain</summary>
<div class="content" markdown="1">
With Aurélien Baillon and Francesco Capozza.
</div>
</details>

<details class="accordion" markdown="1">
<summary>Healing Gaps: General Practitioners’ Influence on Minority Health</summary>
<div class="content" markdown="1">
With E. de Weerd.
</div>
</details>

<details class="accordion" markdown="1">
<summary>Dutch Colorectal Cancer Screening Program: Policy Learning under Equality Concerns and Capacity Constraints</summary>
<div class="content" markdown="1">
With I. Lansdorp-Vogelaar, O. O’Donnell, M. Robson, E. Toes-Zoutendijk, R. van Gestel, and Tom Van Ourti.
</div>
</details>

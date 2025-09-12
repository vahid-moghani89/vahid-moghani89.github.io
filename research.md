---
layout: page
title: "Research"
permalink: /research/
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
  /* bump the text right so it never sits under the arrow */
  padding: 0.75rem 1rem 0.75rem 2.5rem;
  font-size: 1.1rem;
  font-weight: 600;
  cursor: pointer;
  list-style: none;       /* remove default marker */
  position: relative;
}

.accordion[open] summary {
  background-color: #e2e2e2;
}

.accordion summary::-webkit-details-marker {
  display: none;          /* remove default arrow */
}

.accordion summary::before {
  content: '▶';           /* right‐pointing triangle */
  position: absolute;
  left: 1rem;             /* arrow sits at 1rem */
  top: 50%;
  transform: translateY(-50%);
  transition: transform 0.2s ease;
  font-size: 0.9rem;
}

.accordion[open] summary::before {
  transform: translateY(-50%) rotate(90deg); /* point down when open */
}

.accordion .content {
  padding: 1rem;
  border-top: 1px solid #ddd;
}

.accordion .content p {
  margin: 0 0 1rem;
}

.accordion .content a {
  color: #0066cc;
  text-decoration: none;
}

.accordion .content a:hover {
  text-decoration: underline;
}
</style>

# Working Papers

<details class="accordion" markdown="1">
<summary>Mental Health Literacy, Beliefs and Demand for Mental Health Support among University Students</summary>

_Submitted_

With Michelle Acampora and Francesco Capozza. [Working paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4261487){:target="_blank" rel="noopener noreferrer"}.

**Abstract** – This paper assesses the impact of a mental health literacy intervention on the demand for mental health support among university students. We run a field experiment with 2,978 university students from one of the largest Dutch universities. The intervention provides information on the benefits of care‑seeking and its potential returns in terms of academic performance. The intervention increases the willingness to pay and the demand for a mental health app among male respondents. It also increases the demand for information about coaching, correspondingly decreasing the demand for information about psychological counseling. We document that this substitution is driven by students with moderate psychological distress. Increased perceived effectiveness of low‑intensity therapy options is likely to be the mechanism. In a follow‑up survey three weeks later, we find evidence of a moderate improvement in mental health scores for treated female respondents, consistent with suggestive evidence of increased care‑seeking behavior.

**Presentations** – Presented at CESS Colloquium Oxford University; CBS 3rd Workshop Health and Inequality – Copenhagen; Applied Young Economics Webinar; NoBeC Early Career, UPenn; AFE, University of Chicago; EuHea2022, University of Oslo; II IEB Workshop on Public Policies; HCEO‑briq SSSI 2022; 8th IRDES‑DAUPHINE Workshop; Essen Mental Health Workshop, DukeNUS Medical School Seminar; NTU, Brown Bag, University of San Gallen; Mental Health and Economic Status Workshop, University of Warwick; Tinbergen Institute Jamboree.
</details>

<details class="accordion" markdown="1">
<summary>Childhood Mental Health Effects of Early‑Life Exposure to a Parental Job Loss</summary>

With Pilar García‑Gómez and Tom Van Ourti. *Email me for a draft.*

**Abstract** – We study the mental health effects of early life exposure to paternal job loss. Using nationwide individual‑level administrative register records, we focus on firm‑closure‑induced job losses for fathers with children below age five in the Netherlands. These children are more likely to take mental health‑related medicines in their later childhood, and this increase is mainly driven by psychostimulant drugs. The increased uptake of psychostimulants ranges from 15 percent of mean uptake in the control group at age five to around 9 percent at age twelve. The effects are significantly larger for families with mothers being the main breadwinner, suggesting that the drop in paternal income resulting from displacement is not the main driver of psychostimulant uptake. We further find that the father is more likely to take mental health medication around the time of job loss, and that the children exposed to paternal job loss are more likely to live in dissolved families. We find no evidence of exposed children living in neighborhoods with different rates of psychostimulant consumption compared to control children, while parents of treated children do report more impulsive behavior and inattention symptoms.
</details>

# Work in Progress

<details class="accordion" markdown="1">
<summary>Workplace and Health</summary>
This project studies how firms shape workers’ healthcare use and long-term health. Using Dutch administrative employer–employee data linked with individual healthcare expenditures, I apply an AKM two-way fixed effects model with KSS correction to isolate firm contributions beyond worker characteristics and insurance access. I find that a one standard deviation difference in firm effects translates into a 17.8% change in healthcare costs. Moreover, firm effects predict future disability and mortality risks, even after controlling for individual and neighborhood factors. These results show that firms play a significant role in health inequalities, suggesting that workplaces could be important targets for health policy.
</details>

<details class="accordion" markdown="1">
<summary>From Home to Clinic: The Impact of GPs' Children's Gender on the Propensity of Mental Health Medication Prescription</summary>

_Project in preparation._
</details>

<details class="accordion" markdown="1">
<summary>The Determinants of Demand for Mental Health Support</summary>

With Sonia Bhalotra and Francesco Capozza.
</details>

<details class="accordion" markdown="1">
<summary>A Semiparametric Difference Estimator using Local Polynomial Modeling</summary>

With Saeed Badri.
</details>

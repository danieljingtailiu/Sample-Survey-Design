# Project EV Pulse Canada: An Interactive Survey Design Showcase

This repository contains the source code for an interactive, web-based survey prototype. It was designed as a demonstration of advanced survey design methodology, verbatim coding preparation, and data-driven storytelling, specifically tailored to the type of complex consumer research conducted by firms like J.D. Power.

**Live Demo:** [https://danieljingtailiu.github.io/Sample-Survey-Design/](https://danieljingtailiu.github.io/Sample-Survey-Design/)

---

## Project Overview

The automotive market in Canada is at a critical inflection point. With shifting government incentives and aggressive mandates for Electric Vehicle (EV) adoption, understanding the true, underlying consumer sentiment is more crucial than ever.

This project is a high-fidelity prototype of a survey instrument, **"Project EV Pulse Canada,"** designed to move beyond simple polling. It acts as a diagnostic tool to dissect the nuanced drivers, barriers, and psychological factors shaping the Canadian consumer's path to EV adoption.

## Key Features of the Survey

This is not just a list of questions, but a carefully architected interactive experience designed to capture high-quality, actionable data.

* **Logical Flow & Skip Logic:** The survey follows a "funnel" structure, guiding the user from broad profiling to deep-seated attitudes. It also incorporates conditional logic (e.g., Q13 and Q14 appear based on the answer to Q12).
* **Dynamic Question Text:** The prompt for the open-ended question Q9 changes based on the respondent's answer to the Likert scale in Q8, making the experience more personal and relevant.
* **Advanced Question Types:**
    * **Likert Scale with "Don't Know":** Q10 includes a "Don't Know" option, a critical feature for data quality that prevents respondents from polluting "Neutral" answers when they are actually uninformed.
    * **Dynamic Brand Perception Matrix:** Q11b dynamically generates a follow-up matrix based on the brands selected in Q11, allowing for rich data collection on brand attributes without overwhelming the user.
    * **Behavioral & Trade-Off Scenarios:** Questions like Q16 (Incentive Framing) and Q16b (Total Cost of Ownership) are designed to test behavioral economics principles and force realistic trade-offs.
* **Client-Side Data Capture:** Upon submission, the form uses JavaScript to gather all responses into a structured JSON object, which is then displayed on the page. This simulates how data would be packaged for submission to a back-end database and is perfect for demonstrating the data structure.

## Research Methodology Showcase

This survey instrument is built to demonstrate a deep understanding of modern market research methodologies.

1.  **Mixed-Method Design:** It captures both **quantitative data** (Likert scales, multiple-choice, numeric inputs) for statistical analysis and **qualitative data** (open-ended text boxes) for deep consumer insights.
2.  **Preparation for Verbatim Coding:** The open-ended questions (Q9, Q13, Q14, Q17) are deliberately designed to elicit rich, emotional, and unfiltered responses, providing ideal material for thematic analysis and verbatim coding.
3.  **Segmentation & Persona Development:** The demographic and psychographic questions are included to provide the necessary data to segment the audience and build out data-driven consumer personas (e.g., "The Pragmatic Skeptic," "The Incentive-Dependent Buyer").

## How to Run Locally

1.  Clone or download this repository to your local machine.
2.  Ensure the main HTML file is named `index.html`.
3.  Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).

## Technologies Used

* **HTML5:** For the core structure and content of the survey.
* **Tailwind CSS:** For all styling, providing a clean, modern, and fully responsive user interface.
* **JavaScript (Vanilla):** For all interactivity, including dynamic question logic, conditional visibility, and the front-end data capture simulation.

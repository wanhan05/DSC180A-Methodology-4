---
layout: default
---

# Wanhan Sun

was002@ucsd.edu

**Section:** [Section name / number]
**Mentor:** Prof. Soohyun Liao

---

**What is the most interesting topic covered in your domain this quarter?**

The most interesting thing to me has been the gap between how universities and individual instructors approach generative AI. At the institutional level, most R1 universities put out guidance that encouraged GenAI use. But when you look at actual computing syllabi, half of them banned it outright, and only a handful explicitly encouraged it. So in practice there isn't one university policy. Every course sets its own rules, and students have to work through several different regimes in the same quarter. I'm also interested in how some instructors describe AI as an "assistant" or list it next to peers and tutors in a collaboration policy. That framing treats the tool like a collaborator, but all the responsibility for its mistakes still lands on the student. That accountability gap is the thread I want to keep pulling on.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I'd like to test whether the restrictiveness of a course's GenAI policy is associated with changes in student outcomes. The plan is to collect syllabi from UCSD courses over several terms before and after ChatGPT's release. I would pull out the AI-policy text and classify each policy into one of three categories: fully restricted, limited use, or permitted with citation. Then I'd match those policies to grade distributions for the same courses and look at how grades shift when a course's policy changes. If getting grade data turns out to be too hard, a backup investigation is to track how policies themselves have drifted from 2023 to now across disciplines. For example, are STEM courses loosening restrictions faster than humanities courses, and do policies converge toward the university's own guidance over time?

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

The paper we've been working from coded its syllabi through a consensus process and never reported inter-rater agreement. That makes it hard to know how reliable fuzzier codes like "anthropomorphism" really are. I would have two coders label every syllabus independently, report agreement (Cohen's kappa) before resolving disagreements, and publish the codebook alongside the results. I'd also expand the corpus beyond R1 computing courses to include teaching-focused institutions and non-computing disciplines. The current sample can only tell us about one narrow slice of higher education.

**What other techniques would you be interested in using in your project?**

I'm interested in using an LLM to classify policies at scale, with a human-labeled validation set to measure where it agrees and disagrees with human coders. That would also connect back to the accountability question, since we'd be using AI to study AI policy. On the modeling side, I'd like to try a difference-in-differences or event-study design. That would let us compare courses that changed their AI policy against courses that didn't, so we're not just reading correlation off a time trend. I'd also like to try topic modeling or embedding-based clustering on the policy text, to see whether there are natural groupings beyond the three categories we defined by hand.

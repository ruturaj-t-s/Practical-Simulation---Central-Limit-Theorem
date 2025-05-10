# Practical Simulation for CLT 🧪🎲

This repository contains a hands-on experiment to demonstrate the **Central Limit Theorem (CLT)** using Python simulations. Inspired by a real classroom discussion and extended into an engaging exploration, this project answers key questions about how CLT behaves across different distributions—and what happens when sampling bias enters the picture.

## 🔍 Motivation

During one of our inferential statistics sessions, a classmate asked:

> 💡 "Does the Central Limit Theorem hold for a uniform distribution?"

Many students were unsure, thinking uniform probabilities might affect sampling outcomes. To answer this properly, I decided to simulate the process and show how CLT works, rather than just explain it theoretically.

## 🎯 Objectives

- Validate the Central Limit Theorem with a uniform distribution.
- Visually demonstrate the emergence of normality in sample means.
- Discuss the role of **IID** (Independent and Identically Distributed) conditions.
- Explore what happens when **sampling bias** is introduced.

## 🧪 Simulation Setup

We model an experiment of rolling a fair die (a classic uniform distribution):

- Roll a fair die to generate 5,000+ outcomes.
- Draw 50 samples of 30 dice rolls each.
- Calculate the **sample means**.
- Plot the distribution of sample means to visualize how it converges to a normal distribution.
- Gradually increase the sample size to observe the effect.

You’ll see CLT in action: as the sample size increases, the distribution of sample means tends to look more like a bell curve, regardless of the original distribution!

## 📉 What About Biased Sampling?

To dig deeper, we simulate **biased sampling** by rolling an **unfair die** (where outcomes are not equally likely) and observe how the CLT behaves:

- Does it still hold?
- How is the shape of the sampling distribution affected?
- What breaks if the IID assumption is violated?

## 📁 Contents

- `CLT_simulation.ipynb` – The core notebook containing simulations, visualizations, and explanations.
- `README.md` – This file, providing context and guidance for users.
- *(Optional)* `biased_die_simulation.ipynb` – For extended work on the biased sampling case (if added).

## 🛠️ Tools Used

- Python
- NumPy
- Matplotlib / Seaborn
- pandas
- Jupyter Notebook

## 💡 Key Takeaways

- CLT holds for all IID random variables, including those from uniform distributions.
- Sampling distributions of means become normal with sufficiently large sample sizes.
- Bias in sampling can distort results if IID assumptions are violated—but the CLT can still approximate normality under certain conditions.

## 📌 Conclusion

This simulation was a fun and practical way to reinforce a foundational concept in statistics. It’s a great reminder that **learning by doing**—especially with visual evidence—deepens understanding in ways theory alone sometimes can't.

---

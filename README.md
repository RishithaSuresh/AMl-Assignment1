# 📘 Version Space Analysis Report (Dataset 2)

## 🔍 Overview

This project analyzes the limitations of **Version Space** using a different dataset based on **Job Selection** scenarios. It demonstrates cases where Version Space cannot be obtained due to inconsistencies and hypothesis limitations.


## 📚 Concept

Version Space is the set of all hypotheses that correctly classify the training data.

**Formula:**
VS(H, D) = { h ∈ H | h(x) = c(x) }

## 🚨 Failure Cases

### 🔴 1. Inconsistent Data

* Same job conditions → different decisions
* Version Space becomes EMPTY

### 🟠 2. Hypothesis Limitation

* Concept requires OR logic
* Cannot be represented

### 🟡 3. Noisy Data

* Wrong label creates contradiction
* Version Space collapses

### 🟢 4. Missing Attributes

* Hidden factor affects decision
* Causes ambiguity

### 🔵 5. Restricted Hypothesis

* Cannot generalize across jobs
* Leads to poor learning

## 📊 Dataset Used

👉 **Job Selection Dataset**

Attributes:

* Experience (Fresher / Experienced)
* Salary (Low / High)
* Location (City / Remote)
* Job Type (IT / Non-IT)
* Output (Selected: Yes / No)


## 📁 Project Structure

```
📦 Version-Space-Analysis-2
 ┣ 📄 version_space_report_dataset2.pdf
 ┣ 📄 README.md


## 📌 Key Takeaways

* Version Space is sensitive to:

  * Data inconsistencies
  * Noise
  * Missing features
* Real-world ML requires more robust approaches


# Cost of Delay by Duration (CD3)

Of course. The "Cost of Delay" is a powerful and objective technique for prioritizing a backlog with stakeholders. It shifts the conversation from subjective arguments about what's "most important" to a shared, economic understanding of what will deliver the most value and mitigate the most risk in the shortest amount of time.

Here’s a breakdown of what it is, how to use it with stakeholders, and why it's so effective.

## What is the Cost of Delay?

In simple terms, the **Cost of Delay (CoD)** is a way of quantifying the financial impact of *not* doing something *right now*. It asks the question, "How much money will we lose or fail to gain for every week or month we delay this feature?"

This reframes prioritization from a simple to-do list into a series of time-sensitive economic decisions. It makes the abstract concept of "value" tangible by expressing it as a time-based cost.

## The Key Formula: Maximizing Economic Value

While understanding the Cost of Delay is the first step, the real magic happens when you combine it with the effort required. The most common method for this is called **Cost of Delay Divided by Duration (CD3)**, also known as Weighted Shortest Job First (WSJF) in the Scaled Agile Framework (SAFe).

The formula is straightforward:

$$\text{Priority Score (CD3)} = \frac{\text{Cost of Delay}}{\text{Job Duration (Effort)}}$$

By dividing the Cost of Delay by the time it will take to complete the job, you get a score. **Items with the highest score deliver the most value per unit of time and should be prioritized first.**

This prevents a common trap: prioritizing a massive, high-value project that takes a year to complete over several smaller, high-value projects that could be delivered within the same timeframe, generating value much sooner.

### How to Use the Cost of Delay Technique with Stakeholders

Here is a practical, step-by-step guide for running a backlog prioritization session using this technique:

### Step 1: Frame the Conversation**

Start the meeting by introducing the concept in simple terms.

> **You might say:** "Today, instead of just discussing which feature we like the most, we're going to try and understand the economic impact of our decisions. We'll be using a technique called 'Cost of Delay' to help us figure out not just what's valuable, but what's valuable *right now*. Our goal is to answer: 'What should we do next to maximize our return on investment?'"

### Step 2: Define the Components of Cost of Delay (Collaboratively)**

The "Cost of Delay" isn't just lost revenue. Work with your stakeholders to define the key components. Use relative sizing (like the Fibonacci sequence: 1, 2, 3, 5, 8, 13, 21) rather than trying to find exact dollar amounts, which can lead to analysis paralysis.

Break down the Cost of Delay into these three areas:

1. **User-Business Value:** How much value does this create for our customers and our business?
    * *Questions to ask stakeholders:* Will this drive new revenue? Increase user acquisition? Improve customer retention? Will it reduce operational costs?
2. **Time Criticality:** How quickly does the value decay if we wait?
    * *Questions to ask stakeholders:* Is there a fixed deadline for this (e.g., a conference, a seasonal event)? Are our competitors working on this right now? Will this problem get worse over time?
3. **Risk Reduction & Opportunity Enablement:** Does this reduce future risk or enable new opportunities?
    * *Questions to ask stakeholders:* Will this fix a critical security flaw? Does it help us enter a new market? Is this a foundational feature that unblocks other valuable work?

### Step 3: Score the "Cost of Delay"**

Go through your backlog items one by one. For each item, have the stakeholders vote on a score for each of the three components above.

* **User-Business Value:** (1-21)
* **Time Criticality:** (1-21)
* **Risk Reduction / Opportunity Enablement:** (1-21)

The **Total Cost of Delay** is the sum of these three numbers.

### Step 4: Estimate the "Job Duration" (Effort)**

This is where the engineering team provides their input. Again, use relative sizing. This could be T-shirt sizes (S, M, L, XL) converted to numbers or story points. The key is consistency.

> **For Stakeholders:** Explain that this number represents the time and effort required from the team to get the feature done. A higher number means a longer duration.

### Step 5: Calculate and Prioritize**

Now, simply plug the numbers into the formula for each backlog item:

$$\text{Priority Score} = \frac{(\text{User Value} + \text{Time Criticality} + \text{Risk/Opportunity})}{\text{Job Duration}}$$

Rank the backlog items from the highest score to the lowest. The result is a democratized, data-driven, and economically optimized priority list.

## A Practical Example

Imagine you're prioritizing two features:

| Feature | User Value | Time Criticality | Risk/Opp. | **Total CoD** | Job Duration | **Priority Score** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Feature A:** New Analytics Dashboard | 13 | 5 | 8 | **26** | 8 | **3.25** |
| **Feature B:** Quick Checkout Button | 8 | 13 | 3 | **24** | 2 | **12.0** |

## The Outcome

Even though the Analytics Dashboard (Feature A) seems to have a slightly higher overall value (26 vs. 24), its high effort (8) gives it a low priority score. The Quick Checkout Button (Feature B), while slightly less "valuable" in absolute terms, is much faster to implement.

The Cost of Delay calculation proves that **delivering the Checkout Button first will generate more economic value for the business in the short term.** It should be prioritized.

## Why This Technique is Effective for Stakeholders

* **Builds Shared Understanding:** It forces a conversation about *why* something is valuable, moving beyond personal preferences.
* **Drives Objectivity:** It replaces subjective debates with a transparent, mathematical framework.
* **Aligns Business and Tech:** It creates a common language (economics) that both business stakeholders and engineering teams can understand and rally behind.
* **Focuses on Speed and Value:** It naturally favors smaller batches of work, which aligns perfectly with agile principles and accelerates the delivery of value.

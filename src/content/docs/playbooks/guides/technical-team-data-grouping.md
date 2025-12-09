---
title: "Step 2.1: Data Grouping for Multi-Product Technical Teams"
date: 2020-04-20
author: "Zach Bouzan-Kaloustian"
description: "How to group your data if you have multiple, technical products"
draft: false
tags: ["Playbook", "Data Analysis", "Interactions"]
section: "playbooks"
order: 4
---

## Summary

The decision for how to group your data is one of the most crucial steps in the [Playbook](/handbook/playbooks) process, and it's even more complicated when you have multiple technical products. This post will discuss a few ways to think about the grouping and **provide a short cautionary tale about getting it wrong.**


## Methods to Group Your Data

The decision for how to organize your data is crucial to your future success, and if you get it right will make your team very successful. Here's an overview of how we did this for 14 paid products and dozens of features for a very technical product.

At DigitalOcean, we evolved our team structure, and our data grouping, throughout the years as our company and products changed. Ultimately, we decided on a multi-tiered method to slice up our data that aligned to both our Support Team structure and our Product/Engineering (P/E) teams. Here's an overview of our method to group data in order from the highest-level to most granular.

- **Team Vertical**: At DigitalOcean we had the two broad team verticals of  Technical Support and Developer Experience. This could easily roll up to our Executives to say we have X% Technical and X% Experience interactions and this aligned well with Directors in P/E.

- **Product Vertical**: Within each Team Vertical, we broke it down by each Product Vertical within the team. For example, technical tickets were further broken down as Compute, Networking, or Storage. Within Developer Experience, this was either Billing or broadly Experience-related tickets which roughly corresponds with UI/UX. These also aligned to individual P/E Managers which made reporting and creating detailed summaries more helpful and actionable.

- **Billable Product**:  Then we looked at the specific product, such as High-CPU within the Compute vertical, so that the individual Engineering teams could get very specific feedback. Within Developer Experience, it was around a feature, such as the payment workflow for past-due accounts. Another way to think about this classification is by each billable line item or feature, which a customer could experience.

- **Question Type**: Further, we used the type of question, such as FAQ, legal risk, or bug to classify the types of questions being asked. This gave the teams an idea of where to focus their time. In other words, was it working as intended, but not as expected (UI/UX/Feature issue) or was it not working as intended (a bug).


## Iterating to Get it Right
Since the goal with this classification is to understand what's happening within your business, the tagging should be specific enough to understand your contact reasons and so that the data is easily understood. The USPS's ZIP Code in the US is analogous to what you should strive for.
![Zip code Digits](/images/zipcodedigits.png)
The first number represents a general area of our nation, and they're aligned from East to West, North to South. The two following digits are the **code** of a central post office facility in that region. The last two digits designate small post offices or postal zones. [[Source]](https://www.businessinsider.com/what-do-zip-codes-mean-2015-6)

At some point, in 1983 twenty years after they were first introduced, the USPS realized that the 5 digits weren't specific enough, so they added an additional 4 digits. These additional digits made sorting mail even easier and gave a more granular instruction to postal workers down to the specific floor of a large building.

![4 Digits](/images/4CodeDigits.png)
I would argue that if you can deliver mail to every building in the US, using just 9 digits, then you can develop a tagging system that represents you customer contact reasons in a simple format. In a future post about Macros, I'll outline how I've accomplished this.

## Mistakes Were Made
There are a few ways that this system can go awry, so I'll outline a few ways that we ran into trouble over the years.

You should aim to develop your system **cross-functionally**, taking into account as many perspectives across your company as possible. The reason is that you want buy-in for a singular, standardized method and it's a good practice to get input from everyone involved. When we first started at DigitalOcean, we didn't have the full buy-in from P/E. Instead, we developed a full model, created reports, and _then_ got feedback.

Rather than this approach, I would suggest the "fake it until you make it" method, and do a reporting MVP before fully investing into the system. A good cross-functional partner will give you feedback on your MVP, help you improve it, and love it once it's completed. A bad cross-functional partner will require that you fully develop your system, tag tickets for months, make pixel-perfect reports, and then tell you what they don't like.

Decide if you want the tags to be written from an **Internal or External** perspective. As a CX leader, I would advocate for using an external perspective because once you earn cross-functional alignment it creates a bias towards action because it's obvious what your company needs to fix.

- An **internal** perspective is one such as "working as intended", which is actually a final disposition for a bug. Over time, you run the risk of missing key issues and downplaying customer feedback. Why's that? Well, if you don't listen fully and constantly label something as a bug when it's clearly a feature, then you might get pushback from your peers in P/E. It's possible that over time they'll resent you, and they'll never buy-into your feedback. It's possible that you might not take the feedback seriously until all of your customers churn because there's a rift between your teams.

- The **external** perspective uses labels such as "bug" or "UX issue". This type of labeling creates an implicit trust in the customer's feedback because it shows that you believe them. It also has some drawbacks. An engineering team looking at report of "there were 250 bugs in this product this month" could become dejected, or the CX team could lose confidence in the product because there are so many "bugs" all the time. Use this system in a positive way by creating action plans and a bias to action.
- **Bonus**: For a huge morale boost, keep a running list of all the customer "bugs" that you fixed, how many customers it helped, and how many tickets you avoided!
-   There's an added benefit to external labels - when you're using them on a ticket form, phone IVR, etc. you do not need to recode them to be in customer-friendly language. They already represent the customer's point of view - there's a bug because I can't use your product the way that I want to.


## TLDR for Executives

Data Grouping...
- You are the tiebreaker for cross-functional issues that arise. Don't capitulate to the highest-paid team (usually P/E) who might not trust the feedback. Instead, trust this process, trust your customers, and understand that you'll spend less money over time the improve your product if you listen to your customers.
- Know what the details are. Get inquisitive, and be positive with your feedback about how to improve this system. Just like the USPS, your business learns and changes over time, and they earned a revenue of $71.1 billion in 2019!

## TLDR for Operators

Data Grouping...

- Take the time to develop cross-functional relationships
- Build an MVP and get ready for feedback. If you invest too much upfront then you'll have a lot more to change.
- This method helps you take massive amounts of data and dissect it into bite-sized chunks that can be addressed one-by-one over time. Most good things take time.

---
layout: post
title: How we develop "Remove approvals"
---

## STEP 1: Reading the description on the issue body
Before start to generate the solutions, I was reading the description written by the Product manager, the discussions with users, and the relevant issues to really understand the problem and the requirements I was going to solve.

## STEP 2: Quickly generate the solutions + Creating mockups
This a new feature based on the origin approvals feature, so there is no need to start the design from sketching or wireframing. The efficient way was using the elements was already created to do the design and explore the possible solutions.

## STEP 3: Get the feedback from our team and users
Everyone who has GitLab account, including engineers, product team, and users, can contribute their advice and thoughts to the design. Uncovering the design to the public was the best way to realize if this solution works or not.

They provided some situations that I missed or good suggestions. Then, I was going to iterate my design based on the feedback.

#### Iteration 01
In this iteration, we had two buttons, "Unapprove" and "Remove my approval". Our teammate suggests the problem that the naming is likely to be confusion.

![unapprove01-1](/img/unapprove01-1.png)
![unapprove01-1](/img/unapprove01-2.png)

#### Iteration 02
In the second iteration, I remove "Unapprove" button and only keep "Remove my approval" button. I also added the dotted-circle to inform how many request approvals this merge needs.

![unapprove01-1](/img/unapprove02-1.png)

## STEP 4: Implement
At GitLab, we release the new features on 21st every month. When UX part is done, the front-end engineer will take over the task. If they face the problems in development, they will leave their comments on the issue. Designers can quickly modify the design again.

---
layout: essay
type: essay
title: "The Art of Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img src="https://fhntoday.com/wp-content/uploads/2019/03/smarty-900x600.png">

## Is there such thing as a stupid question?

As human beings, we are naturally curious and inquisitive creatures. From a young age, we ask questions to satisfy our curiosity and to gain a better understanding of the world around us. The ability to ask smart questions are an indispensable asset for software engineers, fostering effective communication, problem-solving, and collaboration within the developer community. By analyzing the characteristics of these questions, their adherence to smart question precepts, and the subsequent responses, we can gain valuable insights into the role of inquiry in the software engineering realm.

## What’s a smart question?

Smart questions are characterized by clarity, specificity, context, and a genuine effort to understand the problem. They showcase the asker's research and demonstrate respect for the time and expertise of those who might respond. In the realm of software engineering, where collaboration is key, asking smart questions becomes crucial for efficient problem-solving and knowledge sharing.

## The "Smart" Question:

Consider the following smart question posted on Stack Overflow:

```
Q: What is the difference between "let" and "var"? 

ECMAScript 6 introduced the let statement.

I've heard that it's described as a local variable, but I'm still not quite sure how it behaves differently than the var keyword.

What are the differences? When should let be used instead of var?

```
Link to Question: [What is the difference between "let" and "var"?](https://stackoverflow.com/questions/762011/what-is-the-difference-between-let-and-var)

The provided question exemplifies the qualities of a smart inquiry in several ways. Firstly, its clarity and specificity shine through as it directly addresses the specific topic of the differences between "let" and "var" in ECMAScript 6. Secondly, the inclusion of context by acknowledging the introduction of the "let" statement in ECMAScript 6 reveals a level of awareness about the relevant version of the language. Thirdly, the question delves beyond a mere definition, demonstrating an intention to gain a nuanced understanding of the distinctions between the two keywords. Moreover, the asker's acknowledgment of having heard about "let" as a local variable and the admission of not fully grasping the differences indicate a personal effort to comprehend the concept independently. Lastly, the forward-looking nature of the question, seeking guidance on when "let" should be preferred over "var," showcases an interest in practical application and best practices. Overall, this question encapsulates the key attributes of a smart question – clarity, context, depth, personal effort, and a focus on practical implications.

```
A: Scoping rules
The main difference is scoping rules. Variables declared by var keyword are scoped to the immediate function body (hence the function scope) while let variables are scoped to the immediate enclosing block denoted by { } (hence the block scope).

function run() {
  var foo = "Foo";
  let bar = "Bar";

  console.log(foo, bar); // Foo Bar

  {
    var moo = "Mooo"
    let baz = "Bazz";
    console.log(moo, baz); // Mooo Bazz
  }

  console.log(moo); // Mooo
  console.log(baz); // ReferenceError
}

run();

```
Link to Top Answer: [Top Answer](https://stackoverflow.com/a/11444416)
 
This user has received a total of thirty eight different answers to their original question. The people who have answered the original questions were able to fully understand what was being asked and answer in a clear and concise manner. Alot of the answers were able to clarify what the difference was and even gave different examples of how "let" and "var" could be seperately used in code. 

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Insights

Analyzing these contrasting examples reveals that smart questions not only contribute to the efficiency of problem-solving but also impact the quality and willingness of responses. Smart questions attract more thoughtful and helpful answers, fostering a positive and collaborative environment within the developer community. Observing and understanding these questions underscores the importance of clear communication and thorough problem description. The smart question sets a positive tone for collaboration, encouraging others to engage constructively, while the not-so-smart question may deter potential helpers due to its lack of clarity and urgency.

+++
title = "Memorization Is Important In CS"
[taxonomies]
  tags = ["languages"]
[extra]
  toc = true
+++


## Okay. And?

In many forums and academic environments related to computer science, there is often disdain for memorization. This stems from a discourse on effective study habits and how one ought to retain information. While heavy emphasis is placed on "understanding" a concept rather than rote memorization, I generally agree. However, many people fail to distinguish between "rote memorization" and memorization that serves as a foundation for deeper conceptual understanding. Although one shouldn't aim purely to memorize information, some form of memory is necessary to retain understanding.

## Memory is Fundamental

Throughout my academic and self-directed studies, one thing that has caused me immense frustration is my inability to retain what I learn. I may develop a deep understanding of a particular concept, but as soon as I close the book, that understanding fades. This becomes especially frustrating when I need to apply that concept in a program or academic setting. In computer science and programming, there are countless concepts and bits of knowledge that need to be remembered—networking, operating systems, compilers, and more. The usual response to someone seeking advice on how to memorize information is: "No, don’t memorize. Understand the concepts being taught" or "You don’t need to memorize; whatever you don’t remember can be found online or in a book." However, these responses overlook the fact that in order to truly understand something, we must first have some foundational memory—especially if we are expected to apply it later.

I’m perfectly fine with looking up "how to index arrays in Rust," but I’m not comfortable having to look up "what is an array" each time I want to work with it.

Most people don’t fully grasp what "understanding" really means. It isn’t just knowing how or why something works, but also being able to apply it, explain it, and relate it to other concepts. You cannot fully demonstrate understanding without some level of memorization. I’ve noticed that many times I struggle to explain a concept not because I don’t understand it, but because I forget it. Understanding without retrieval is incomplete. Without memory, the ability to manipulate and apply complex concepts is hindered. Once I refresh my memory on a concept, explaining it becomes much easier. My understanding was there, but my ability to retrieve it was not.

The inability to recall what you understand is as detrimental as not understanding it in the first place. What is the point of understanding if you can’t retrieve it when needed? For instance, I may understand how an array works, but if I can’t recall that understanding when working on a project, then it’s useless. The neural pathways in my brain are associated with the concept, but I still need to actively retrieve it.

## Complex Concepts: Lexers as an Example

Let’s take a more complex example—Lexers. A lexer is a component of a compiler responsible for converting the characters and symbols within a program file (e.g., "program.c") into meaningful units called "tokens." A lexer processes something like:

```rust
fn add(x: u32, y: u32) -> u32 {
    x + y
}

fn main() {
    let x = 5;
    let y = 20;
    let result = add(x, y);
}
```

And transforms it into something like:

`[Identifier("fn"), Identifier("add"), LeftParen, RightParen, Identifier("x"), ...]`

Rote memorization of this would simply involve reciting a definition of "Lexer." Understanding, on the other hand, involves applying this concept to create an actual lexer and understanding why it is essential—it breaks down the program into tokens that the parser can analyze according to the grammar rules defined by the language specification. For example, knowing that "fn" is not just a simple Identifier, but specifically indicates the declaration of a function.

Now, imagine you, having read this, understand what a lexer does. A few days later, in class, your professor briefly brings up compilers and asks the class if anyone knows anything about lexers. You eagerly raise your hand, but when asked to explain it, you draw a blank. Does this mean you don’t understand lexers? Not necessarily. Without additional context, it may seem so, but the truth is you’ve simply forgotten what they are and how they function. The understanding is still there, but your ability to recall it is not. If you had reviewed the concept the day before, you might have been able to demonstrate your understanding. You don’t need to remember every little detail—this is where the internet and reference books come in handy.

Memorization without understanding is parroting, but understanding without memory is superficial. These two go hand in hand. Retaining your understanding and then applying it is just as important as grasping it initially.

## How Should You Learn?

I’m still navigating this myself, but ideally, you want to build a solid understanding. Explain the concepts, create something with them, or solve problems.

![Image of learning pyramid](https://miro.medium.com/v2/resize:fit:1400/0*4jryMu9C_JRuS5CI.jpg)

You can retain your understanding through spaced repetition, which involves reviewing information at increasing intervals over time. I currently use [Anki](https://apps.ankiweb.net/), but other tools work as well.

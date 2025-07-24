---
layout: essay
type: essay
title: "Blueprints for the Mind: Building Software with Design Patterns"
date: 2025-07-24
published: true
labels:
  - Design Patterns
  - Software Engineering
  - Technical Reflection
---

<div class="text-center mb-4">
  <img width="300px" class="rounded float-start pe-4 shadow" src="../img/design-patterns/blueprint.jpg" alt="Software Blueprint">
</div>

## Building Without Blueprints (At First)

When I started learning to code, each project felt like assembling IKEA furniture without the instructions. It might look fine from the front, but the back was held together with duct tape and hope. Every time a new feature was needed, I had to rethink everything. It worked, but it didn’t scale — and worse, I couldn’t explain *why* it worked.

Then I encountered **design patterns**, and suddenly, it was like finding the instruction manual — not for a specific project, but for solving entire categories of problems.

## So, What Are Design Patterns?

Design patterns are **reusable solutions** to common problems in software design. They’re like architectural plans for code — general strategies that help you organize and structure your project in a way that makes it easier to maintain, extend, and understand.

They don’t give you copy-paste code. They give you **ideas**, shaped by years of engineering experience, that help you make better decisions when building something from scratch.

## Where I’ve Used Them

One pattern I’ve used recently is something called the **Strategy Pattern**, and I actually used it without even knowing it had a name at first.

In a Next.js app, I used NextAuth.js to set up login functionality. It lets you choose how users can log in — with a password, or with providers like Google or GitHub. In my case, I set up a "credentials" provider where users could log in using email and password.

Here’s where it gets interesting: all those login methods (Google, GitHub, credentials, etc.) are *interchangeable*. I could add a new provider without rewriting everything — I’d just drop it into a list of options. Each one follows the same format but handles things a little differently behind the scenes.

That’s what the Strategy Pattern is all about: having different methods to solve the same kind of problem, and being able to swap them in or out without changing the rest of your code.

## Why This Matters in Interviews (and in Real Life)

When interviewers ask, “What are design patterns?” they’re really asking: **Can you solve problems that come up again and again, and do it in a way that other developers will understand and build on?** They want to see if you think beyond getting something to work — they want to know if you’re thinking about *how* it works and *why* it works that way.

When they ask which ones you’ve used, they’re looking for real examples. It doesn’t have to be fancy — just something that shows you’ve learned to recognize and apply smarter solutions when it matters.

Design patterns aren’t about memorizing a list. They’re about learning to spot when you’ve solved a problem well — and how to do it again, cleaner, next time.

## Final Thoughts

Learning design patterns changed how I write code. They’re not magic — just shared wisdom in blueprint form. And once you’ve built with them, you’ll never want to go back to improvising beams and bolts from scratch.

Next time you write a component or set up a feature, ask yourself: **Has someone solved this before in a smart way?** If so, there’s probably a pattern for that — and learning it will save you a lot of headaches later.

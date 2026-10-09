---
layout: post
title: My Recipes, Revisited
date: 2026-10-05 
description: Recipes & Recipe Tracking
tags: recipes, organization
categories: resources
---


**TLDR;** My [recipe list](https://rocky-hardboard-38a.notion.site/af8a076a6c0d4f34b5ec2ffa63a6c64d) and grocery list are integrated, so that each recipe reports whether I have all the ingredients required to prepare it.

## What Wasn't Working

Last year I wrote about [how I organize my recipes](https://akobre01.github.io/blog/2025/my-recipes/). I found that it had two problems.

First, adding a recipe took too many steps: for each one I'd copy a link in, select an icon, write notes, estimate preparation times, and maybe list a few critical ingredients. I might do this all if I was sitting at my computer, but not if I was on mobile. If I found a recipe in a cookbook, there was little chance it would make it in.

Second, and more importantly: the list was a good place to *put* recipes, but it didn't surface many recipes we that we loved.

To solve this I implemented a number of changes: I linked my grocery list and recipes, made grocery items aware of ingredient substituions, changed the columns associated with my recipes to be more descriptive, and created new views to help me find relevant recipes in a variety of situations. Each change is described below:

## The Grocery Connection

The biggest change is that I've linked each recipe to all grocery items it requires. Since each grocery item marked as either In Stock, Running Low, or Out of Stock, each recipe reports whether or not I have all the ingredients on hand to make it.

Each recipe now shows a little pantry status: ✅ Ready, 🛒 Need 2, with the missing items named. The *important ingredients* column from last year's post was a hand-written approximation of this. Now it's automatic, and it works in both directions: every grocery item lists the recipes that use it, so the half bunch of dill in my fridge can tell me what to do with it.

While this all may seem like a lot of work, it would be, except that I had [Claude](https://claude.ai/new) do most the linking for me. What is even better is that I discovered that I can take pictures of recipes in my cookbooks, send them to Claude, and have it add the recipe to Notion with all the ingredient extracted, matched up to my grocery items when possible, and linked to the recipe.


## Substitutions

Grocery items also know about substitutions. For example, canned tomatoes know that they can stand in for fresh; whole cumin covers ground cumin because I own a grinder; kale can substitue for spinach; dried beans stand in for canned--as long as I know with enough time.

When a swap is in play, the recipe shows 🔄 Ready with swap and names it, so I can decide whether it's a swap I actually want.

Since some ingredients I might buy _or_ prepare myself, for example harissa, kimchi, pickles, preserved lemons, seitan, or a salad dressing--those items are linked their recipes. When the harissa jar runs out, the chili that needs it links me to my harissa recipe.

## Better Ratings

My old 1–5 stars never told me much. They're gone; replaced by a status that answers a real question:

- **Favorite** — we loved this and I'd go out of my way to make it again
- **Make again** — solid and should be made again, but perhaps not prioritized
- **If it's handy** — worth making if I've got the ingredients (and especially if I need to use them up)
- **Want to try** — the 🤷 of the old system
- **Nope** — won't make again

A handful of other columns do the work the old tags did, but better: *Who likes it?* (one entry per family member), *Leftovers*, *Lunchbox*, *Feeds*, *Make-ahead*, and *Activity*, which is how much energy a recipe demands. Hyper, average, or lazy. On most weeknights, I'd prefer something lazy.

## Views for How I Actually Cook

Three situations, three views.

**Weeknight.** Mains and soups under an hour, sorted by what I can make right now, then by what I haven't made in longest. That second sort is quietly the most valuable thing in the view — it's what keeps us off the same six dinners.

**Friday candidates.** We host a lot, and Friday is when I try something new. This view is the *Want to try* pile, split into mains, sides, and desserts, with no time limit. I shop Friday mornings, so a recipe that requires ingredients I don't have is fine here.

**Lunch builder.** My partner and I eat a lot of bowls and salads assembled from parts: leftover roasted vegetables, homemade seitan, whatever's pickled. Components and condiments are now tagged by where they go, so lunch is a matter of picking three things that are in the fridge.

Still evolving, as always. If you've got ideas, let me know!

Happy cooking!

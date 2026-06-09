# Project 1 Planning: The Unofficial Guide

> Write this document before you write any pipeline code.
> Your spec and architecture diagram are what you'll use to direct AI tools (Claude, Copilot, etc.) to generate your implementation — the more specific they are, the more useful the generated code will be.
> Update the Retrieval Approach and Chunking Strategy sections if you change your approach during implementation.
> Update this file before starting any stretch features.

---

## Domain

<!-- What domain did you choose? Why is this knowledge valuable and hard to find through official channels? -->

---
The domain is off-campus food and beverages around Princeton Univeristy. This knowledge is valuable because it will make off-campus dining more accessible: students will know prices, allergies, food restrictions, cuisines, etc that are available. It is hard to find information on off-campus dining options since these organizations are often no affiliated with the university. 
## Documents

<!-- List your specific sources: URLs, subreddit names, forum threads, or file descriptions.
     Aim for at least 10 sources that together cover different subtopics or perspectives within your domain. -->

| # | Source | Description | URL or location |
|---|--------|-------------|-----------------|
| 1 | Yelp Ranking | Restaurants near Princeton University | https://www.tripadvisor.com/RestaurantsNear-g46756-d123115-Princeton_University-Princeton_New_Jersey.html|
| 2 | Campus NewsLetter | Guide on big group dinners in Princeton |https://www.dailyprincetonian.com/article/2023/05/princeton-restaurant-food-guide-big-group-meals |
| 3 | Reddit Thread |places to eat in Princeton |https://www.reddit.com/r/newjersey/comments/1avkq2k/princeton_eats/ |
| 4 | Wanderlog's Ranking|  31 best cheap eats in Princeton|https://wanderlog.com/list/geoCategory/189404/best-cheap-eats-in-princeton |
| 5 | Reddit thread |cheap eats in Princeton with some prices|https://www.reddit.com/r/princeton/comments/wl5dpu/is_there_any_good_food_around_here_thats_not/ |
| 6 | Trip Advisor| Desserts in Princeton |https://www.tripadvisor.com/Restaurants-g46756-zfg9909-Princeton_New_Jersey.html |
| 7 | Uber Eats| food spots near Princeton with distance |https://www.ubereats.com/feed?diningMode=PICKUP&pl=JTdCJTIyYWRkcmVzcyUyMiUzQSUyMlByaW5jZXRvbiUyMFVuaXZlcnNpdHklMjIlMkMlMjJyZWZlcmVuY2UlMjIlM0ElMjJoZXJlJTNBcGRzJTNBcGxhY2UlM0E4NDBkcjR2ay04YmVjMTE3MWVmODA0Mjk4OWY5YWU1N2IxOTkzZTBiYiUyMiUyQyUyMnJlZmVyZW5jZVR5cGUlMjIlM0ElMjJoZXJlX3BsYWNlcyUyMiUyQyUyMmxhdGl0dWRlJTIyJTNBNDAuMzQ5NzMlMkMlMjJsb25naXR1ZGUlMjIlM0EtNzQuNjYwMTElN0Q%3D |
| 8 | Campus NewsLetter| New halal options | https://www.dailyprincetonian.com/article/2026/03/princeton-news-stlife-new-restaurants-expand-halal-dining-options-princeton|
| 9 | Student Guide| Plant-Based options on-campus and off-campus|https://sustain.princeton.edu/sites/g/files/toruqf6606/files/The%20Definitive%20Guide%20to%20Being%20Plant-Based%20At%20Princeton.pdf |
| 10 | University Website | Places were University dining points ae transferred|https://tigercard.princeton.edu/points#Where-Are-Points-Accepted- |

---

## Chunking Strategy

<!-- How will you split documents into chunks?
     State your chunk size (in tokens or characters), overlap size, and explain why those
     numbers fit the structure of your documents.
     A review-heavy corpus warrants different chunking than a long FAQ. -->

**Chunk size:**

**Overlap:**

**Reasoning:**

---

## Retrieval Approach

<!-- Which embedding model are you using (e.g., all-MiniLM-L6-v2 via sentence-transformers)?
     How many chunks will you retrieve per query (top-k)?
     If you were deploying this for real users and cost wasn't a constraint, what tradeoffs
     would you weigh in choosing a different embedding model — context length, multilingual
     support, accuracy on domain-specific text, latency? -->

**Embedding model:**

**Top-k:**

**Production tradeoff reflection:**

---

## Evaluation Plan

<!-- List your 5 test questions with their expected correct answers.
     Questions should be specific enough that you can judge whether the system's response
     is right or wrong. "What are good dining halls?" is too vague.
     "What do students say about wait times at [dining hall name] during lunch?" is testable. -->

| # | Question | Expected answer |
|---|----------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

## Anticipated Challenges

<!-- What could go wrong? Name at least two specific risks with reasoning.
     Consider: noisy or inconsistent documents, missing source attribution, off-topic
     retrieval, chunks that split key information across boundaries. -->

1.

2.

---

## Architecture

<!-- Draw a diagram of your pipeline showing the five stages:
     Document Ingestion → Chunking → Embedding + Vector Store → Retrieval → Generation
     Label each stage with the tool or library you're using.
     You can use ASCII art, a Mermaid diagram, or embed a sketch as an image.
     You'll use this diagram as context when prompting AI tools to implement each stage. -->

---

## AI Tool Plan

<!-- For each part of the pipeline below, describe:
     - Which AI tool you plan to use (Claude, Copilot, ChatGPT, etc.)
     - What you'll give it as input (which sections of this planning.md, which requirements)
     - What you expect it to produce
     - How you'll verify the output matches your spec

     "I'll use AI to help me code" is not a plan.
     "I'll give Claude my Chunking Strategy section and ask it to implement chunk_text()
     with my specified chunk size and overlap" is a plan. -->

**Milestone 3 — Ingestion and chunking:**

**Milestone 4 — Embedding and retrieval:**

**Milestone 5 — Generation and interface:**

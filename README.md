# Solutions Engineer Hiring Assignment

This is the hiring assignment for the Solutions Engineering team at Algolia.

The goal of this exercise is not to test your ability to understand technical concepts, explain them clearly, manipulate data and build demos (with your preferred tooling). We expect strong SEs to use the tools available to them to move faster, explore ideas, and deliver better outcomes for prospects.

What we care about is your ability to:

- Understand Algolia's core technical concepts
- Transform messy customer data into a useful search index
- Design a relevant and compelling search and discovery experience
- Make thoughtful architecture and implementation decisions
- Evaluate search quality and tune configuration accordingly
- Communicate your choices clearly to both technical and non-technical audiences

You are welcome, and encouraged, to use AI tools to help you write code, manipulate data, generate UI ideas, debug, or accelerate implementation. Be ready to explain the concepts, architecture, trade-offs, and decisions behind what you built.

## Communication Project Instructions

View the [example customer questions](customer-questions.md) and answer them using the Algolia documentation.

Please include your answers in your repository. A `.txt`, `.md`, or similar plain-text format is fine.

We are evaluating how clearly you can explain technical topics to a customer. Strong answers should be accurate, concise, and adapted to the customer's likely level of understanding.

## Technical and UX Project Instructions

Our sales team has recently been contacted by a large restaurant reservation website. The opportunity is strategic, and the team would like to show the prospect a compelling vision of what their restaurant discovery experience could become with Algolia.

As a Solutions Engineer, your task is to build a small interactive prototype using the provided restaurant dataset. Your demo should highlight the value of a great search and discovery experience.

This is not a pixel-perfect implementation exercise. The provided mock-up and assets are here to give you context, not to constrain your thinking. You may use them, modify them, or ignore them entirely if you believe you can propose a better experience.

We encourage you to innovate. Show us how you would bring a prospect a vision, not just a functional search box.

**Important:** Do not fork this repository to create your assignment. Create your own private or public repository for your work and send us the link when you submit.

## What You Should Build

Download [the project files](/project-files.zip), then build a working restaurant discovery demo.

Your demo should include the following:

- An Algolia index populated with the provided restaurant data
- A data preparation process that combines and cleans the provided files
- A search interface that lets users find restaurants through text search
- Relevant filtering or refinement, including cuisine type
- Location-aware ranking, or a thoughtful fallback if browser geolocation is not available
- Search configuration that you have tested and tuned based on the dataset
- A user experience that demonstrates how the prospect's discovery experience could be improved

You may use any front-end framework, tooling, UI library, or AI coding assistant you prefer. You may use Algolia libraries such as InstantSearch, Autocomplete, the JavaScript API client, or other tools that help you build a strong demo.

Choose the implementation approach that lets you best demonstrate your understanding of Algolia and your ability to deliver value quickly.

## Data Requirements

The dataset is available in the `./resources/dataset` folder.

The client has provided two files:

- `restaurants_list.json`, containing approximately 5,000 restaurants
- `restaurants_info.csv`, containing additional information about those restaurants

Because the data is split across files, you will need to manipulate and combine them before indexing.

Your indexed records should include the information needed to support the search experience, including cuisine type.

Please include your data manipulation and import script in your repository. AI assistance is allowed, but you should be able to explain:

- How the files were joined
- What transformations or cleanup you performed
- Which attributes you indexed
- Which attributes you made searchable, facetable, or ranking-related
- Any assumptions you made about the data

For payment options, the demo should only expose the following normalized values:

- AMEX / American Express
- Visa
- Discover
- MasterCard

For this assignment, Diners Club and Carte Blanche should be treated as Discover cards.

Feel free to enrich the data with any additional information you think would be useful for discovery purposes.

## Search and Relevance Requirements

Do not stop once search technically works. Test it as if you were preparing for a customer meeting.

Try representative searches and refinements, inspect the results, and adjust the index configuration where needed.

We are interested in how you think about relevance. Your submission should show evidence that you considered topics such as:

- Searchable attributes
- Ranking and custom ranking
- Facets and filters
- Geo-search or location-based relevance
- Typo tolerance and query behavior
- Result ordering and perceived quality
- How the experience should behave when the query is broad, specific, ambiguous, or empty

You do not need to find a perfect configuration. We want to see that you can reason about search quality, test your assumptions, and improve the experience iteratively.

## UX and Demo Expectations

The original mock-up is provided as reference material only. You are not required to reproduce it.

Using AI and modern front-end tooling, you can go beyond the basic brief. Design the restaurant discovery experience you believe would be most compelling for the prospect.

## Important Notes

- Graphical resources, including the mock-up, are provided in the `./resources` folder
- The mock-up is guidance only; you are encouraged to improve on it or take a different direction
- Feel free to use any front-end tooling, framework, or AI-assisted workflow with which you are comfortable
- Please make sure your demo is easy for us to run or access
- When you sign up for an Algolia account, please put `Interview Candidate` in the company field
  - This helps our sales team know someone is already speaking with you

## Deliverables

When you are ready to submit, please send us:

- A link to the live demo, for example via GitHub Pages, Vercel, Netlify, or another hosting option
- A link to your Git repository
- Your answers to the communication project questions
- Clear setup instructions if the project needs to be run locally
- A short explanation of your approach

Have fun with the assignment. We are excited to see how you would imagine a better restaurant discovery experience.

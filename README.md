# termsheet-playbook
Idea: Create a playbook for term sheet clauses for seed round investment

Term Sheet Playbook 

The Problem
As AI absorbs routine junior work, legal associates are losing the learning that came with doing the foundational work themselves. Junior associates no longer get the opportunity to mark up term sheets, but they are still on calls and in negotiations. They are arriving without the preparation that marking up a term sheet used to force. That prior engagement with the document was where the real learning happened. Without it, observation replaces understanding.
 
What I Built

A RAG-based legal research tool for Indian PE/VC term sheet negotiations, grounded in Companies Act 2013 and FEMA legislation. Junior associates can browse key clauses like liquidation preference, anti-dilution and drag-along, or query specific negotiating positions and get structured, India-specific answers covering founder and investor counsel perspectives, market practice, and red flags. The playbook handles the foundation and the lawyer handles everything above it.

How I Built It
I built this in two weeks, on the free version of Claude, with no engineering background and no budget. Since Claude limits would expire quickly, I was forced to be scrappy, and this constraint forced clarity of thought.
I structured the work in parallel threads, one for the knowledge base (researching, curating, and encoding how Indian term sheet clauses are actually negotiated), and one for the front end (building a clean, usable interface that makes the information accessible rather than just technically present). I debugged by taking screenshots and dropping them into Claude chat. I worked in sessions timed around the free usage limits, starting at 8am, picking up again around 2pm, then again in the evening. 


Why RAG
Generic AI tools like ChatGPT or Claude sometimes reference UK or US law sources, cite outdated positions, or hallucinate market practice. For a corporate lawyer advising on an Indian funding round, that is a real risk. Building this as a retrieval-augmented generation tool with a controlled, India-specific knowledge base keeps the answers grounded and bounded. If a query falls outside the knowledge base, the tool says so clearly rather than guessing.

This is just a sample of what I can create when the right tools are given to me. I am curious what becomes possible with real tools, a real brief, and a firm’s institutional knowledge to work with.

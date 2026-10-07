# Will Gilmour

I'm a doctor who builds AI systems, and co-founder and CTO of [Humma](https://humma.ai). My work spans clinical product design, LLM orchestration, evaluation and the engineering needed to connect them.

At Humma, we're building conversational AI to help patients understand information, organise their concerns and prepare for appointments with their healthcare team. Patient autonomy is the starting point for the product and its technical design.

## What I'm working on at Humma

- **Architecture shaped by clinical boundaries.** Defining what belongs in explicit rules, what a language model can help with, and how information retrieval and response checks support our information-only doctrine.
- **Evaluation of real failure modes.** Testing source faithfulness, false reassurance, scope drift and whether a response actually acknowledges a patient's concern. I care about what a benchmark measures and how its results should be interpreted.
- **Classification and conversation routing.** Exploring Jev and Clef, including local inference, with comparisons of missed cases, false positives, latency and hosting constraints. This is experimental work with explicit criteria for adoption.
- **Patient and clinician communication.** Designing conversations and summaries that help patients express what matters to them and give the receiving team useful context.

Our doctrine sets hard boundaries around diagnosis, personalised treatment recommendations and false reassurance. Turning those principles into useful, testable behaviour is a substantial part of the engineering work.

## How I work

I favour small changes organised around a clear behaviour, with tests included alongside the implementation. Reproducing a failure, making the test pass and reviewing the change should form one understandable piece of work.

I like trying new approaches early. I also want the comparison, the failure cases and the remaining limitations to be clear enough for another engineer to evaluate the result. Local experiments and adoption decisions are distinct stages.

Clinical experience keeps me attentive to the interaction itself. A response can avoid unsafe advice and still leave someone feeling unheard. Those trade-offs belong in the product requirements and evaluations.

Most of Humma's implementation is in private repositories. The project below offers a public example of my work across data pipelines, machine learning and interactive tools.

## Public work

### Paper Graph

A tool for exploring scientific literature through citation networks. Starting from seed papers, it crawls open citation data, builds a graph, uses GPU-accelerated layout and community detection, and labels clusters with a locally hosted language model. An interactive browser interface lets you explore the resulting map.

The repository includes the Python data pipeline, backend, frontend, Docker setup and technical documentation.

[Code](https://github.com/Will-Gilmour/paper_graph) · [Demo](https://www.youtube.com/watch?v=ITWbtRxFnNM) · [Technical overview](https://github.com/Will-Gilmour/paper_graph/blob/main/docs/TECHNICAL_OVERVIEW.md)

## Background

My background includes clinical practice in neurology, emergency medicine and surgery; neuroscience research at Dundee; and AI engineering at IQVIA, working on multi-agent systems, evaluation frameworks and LLM orchestration.

MB ChB, University of Manchester · MSc with Distinction in Computational Neuroscience, University of Sheffield.

## Get in touch

If you're interested in building healthcare AI and these are the kinds of problems you want to work on, I'd like to hear from you.

[Humma](https://humma.ai) · [LinkedIn](https://www.linkedin.com/in/will-gilmour-bb873a191/) · [will@humma.ai](mailto:will@humma.ai)

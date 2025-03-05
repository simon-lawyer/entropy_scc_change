# Entropy in a texts as a measure of legal complexity
Q: If we measure the average entropy in a set of legal texts overtime, will average entropy remain constant or will it fluctuate?

Hypothesis: When new energy enters the legal system--when the legal field is destabilized--entropy in legal texts will increasese and then, with time, decrease.

If true, this would mean that we could use entropy to help find moments when new ideas and new priorities disrupted the legal field.

To explore this I will:
- Download a complete collection of the Supreme Court of Canada's decisions
- Take 100,000 five hundred token samples from each year's jurisprudence
- Text preprocessing strategy: remove punctuation and numbers. lower-case text.
- Calculate mean entropy (Shannon)
- Plot to see if there are fluctuations
- Explore moments of fluctation

# Graph Neural Networks

Owner: Akshay Sehgal (www.akshaysehgal.com)

### The Evolution of Graph Neural Networks

Graph Neural Networks emerged from early efforts to apply neural computation to structured, relational data. Over the past decade, the field has developed from foundational spectral methods into a broad family of approaches for learning across molecules, social networks, knowledge graphs, and other connected systems.

Early work established ways to extend convolutional ideas beyond grids and sequences, allowing models to learn from both individual entities and the relationships between them. Later architectures refined how information is passed across a graph, improving scalability, expressiveness, and performance on increasingly complex networks.

Today, GNNs sit at the intersection of graph theory and deep learning, supporting research in areas from drug discovery and recommendation systems to traffic forecasting and scientific modelling.

### Thinking in graphs

Graphs are one of the most natural things we already think in, a map, a family tree, a group chat, a subway line. Long before anyone called it graph theory, we were reading the world as things connected to other things. This site starts from that intuition and tries to carry it all the way into graph neural networks.

### Why I built this

Graph Neural Networks have a reputation for being dense, notation heavy, and generally unapproachable, even though most of us already reason in graphs constantly. Data scientists, engineers, product managers, we're all comfortable drawing boxes and arrows to explain a system, we just don't always call it a graph.

My goal with this site was to close that gap. Not by writing another textbook, but by leaning into the graphical intuition most of us already carry, and using it as a bridge into the actual research. From the earliest spectral methods on graphs, through message-passing networks, to today's graph transformers, I wanted one place that treats the last decade of GNN research as a single connected story instead of a pile of disconnected papers.

### How to explore the Atlas

The Atlas is built to be read like a family tree, not a syllabus. Start wherever a paper looks unfamiliar, follow its edges backward to see what it grew out of, and forward to see what it led to. Most ideas make a lot more sense once you've seen the one or two papers that came right before them.

That said, the Atlas is a map, not the territory. Once a node is filled in, I'd genuinely recommend reading the short synthesis alongside the original paper itself. A few of these, GraphSAGE and GAT especially, are written clearly enough that the paper is the best explanation you'll find anywhere, better than anything I could summarize here.

A few prerequisites: nothing here assumes the math, but a working, intuitive sense of a few ideas from outside graphs will make the Atlas easier to follow. If you're rusty on representation learning, embeddings, word2vec, the attention mechanism, or transformers, these are good places to start. I'd add one more: a good chunk of the early Atlas (GCN, ChebNet) is literally convolution carried over from images to graphs, so a quick pass through convolutional neural networks helps too.

*@ Copyright 2026, Akshay Sehgal*

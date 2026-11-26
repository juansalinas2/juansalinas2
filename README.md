# Juan Salinas 

Product-minded data scientist and PhD mathematician building forecasting, experimentation, and recommendation systems. I earned my Ph.D. in Mathematics from the University of Washington under Max Lieblich, specializing in algebraic geometry. My thesis studied [representations of configurations](https://drive.google.com/file/d/1GAHcc34xd7MJDQTr0NjYAM9humm89cNt/view).

## Featured Projects 

### [Olist Delivery Forecasting](https://github.com/juansalinas2/olist_analysis)

**Decision:** I recommended shadow-testing the new delivery estimate and keeping Olist’s existing customer promise.

Across 18,603 test orders, the model cut mean absolute error from 5.03 to 3.64 days compared with a constant median estimate. The conservative forecast covered 98.68% of deliveries, but it would have moved the promised date back by 1.71 days on average.

[Tableau dashboard](https://public.tableau.com/app/profile/juan.salinas7316/viz/OlistDeliveryPromiseDecisionDashboard/ExecutiveDecisionDashboard)

---

### [Harmonic Trends](https://github.com/juansalinas2/harmonic-trends)
**Main Question:** 
> How do chord progressions vary by genre and decade? Can we use them to recommend songs?

I analyzed chord progressions from 679,807 songs and tested whether their patterns could predict genre and decade for artists held out of training. Pick a progression in the dashboard and see which chord tends to come next in jazz, soul, or country.

[Explore the interactive dashboards](https://huggingface.co/spaces/juansalinas2/harmonic-trends)

---

### [Deep Learning Song Recommender](https://github.com/juansalinas2/dl-song-recommender)
**Main Question:** 
> Can listener descriptions teach an audio model which songs sound musically similar?

Our team built an audio recommender using 11,239 songs. I led the PyTorch model development and deployed the web app. On our tag-based benchmark, the audio model achieved **70.2% precision@5**, compared with **38.3%** for the tag-embedding baseline.

[Try the web app!](https://dl-song-recommender.onrender.com)
 

## Teaching

I currently teach math at Seattle University. My [Calculus I notes](https://juansalinas2.github.io/Math-1334---Calculus/) include worked examples and a [concept map](https://juansalinas2.github.io/Math-1334---Calculus/map/) that shows how the topics connect. I’m using AWS Lambda and Amazon Bedrock to build a RAG system that answers students’ questions in real time using the section they’re reading.

Try this game to test your calculus chops! [*Critical Point*](https://juansalinas2.github.io/Math-1334---Calculus/map/challenge.html).

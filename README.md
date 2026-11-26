# Juan Salinas 

Product-minded data scientist and PhD mathematician building forecasting, experimentation, and recommendation systems. I earned my Ph.D. in Mathematics from the University of Washington under Max Lieblich, specializing in algebraic geometry. My thesis studied [representations of configurations](https://drive.google.com/file/d/1GAHcc34xd7MJDQTr0NjYAM9humm89cNt/view).

## Featured Projects 

### [Olist Delivery Forecasting](https://github.com/juansalinas2/olist_analysis)

**Main Question:**
> Can delivery dates be more accurate without making the customer promise unnecessarily conservative?

Built a purchase-time forecasting pipeline using chronological validation and quantile regression. Compared with a constant median-duration baseline, the Q50 model reduced MAE by 27.6% (5.03 → 3.64 days) on 18,603 chronological test orders. The conservative promise reached **98.68% reliability**, but was **1.71 days longer** than Olist’s.

**Decision:** shadow-test the improved ETA, but do not launch the longer customer promise until calibration improves.

[Tableau dashboard](https://public.tableau.com/app/profile/juan.salinas7316/viz/OlistDeliveryPromiseDecisionDashboard/ExecutiveDecisionDashboard)

---

### [Harmonic Trends](https://github.com/juansalinas2/harmonic-trends)
**Main Question:** 
> How do chord progressions vary by genre and decade? Can we use them to recommend songs?
>
`679,807 songs` · `artist-held-out benchmark` · `67M indexed feature rows`

Built an end-to-end music data project that cleans and standardizes noisy chord data, stores analysis-ready tables in DuckDB, and represents harmony using n-grams, embeddings, and sequence models. The analysis explores genre-specific patterns, historical trends, and recommendations based on harmonic movement.

[Explore the interactive dashboards](https://huggingface.co/spaces/juansalinas2/harmonic-trends)

---

### [Deep Learning Song Recommender](https://github.com/juansalinas2/dl-song-recommender)
**Main Question:** 
> Can listener descriptions teach an audio model which songs sound musically similar?
>
`11,239 songs` · `64-dimensional audio embeddings` · `live uploaded-audio demo`

Co-developed a content-based music recommendation system that learns song embeddings from listener tags and audio. I led the deep learning implementation in PyTorch, training a late-fusion ResNet18 on full-mix and instrument-stem spectrograms using contrastive learning with tag-informed supervision, and the deployment of the web app. We evaluated retrieval performance using ranking metrics and built an interactive web application for exploring learned song similarities.

[Try the web app!](https://dl-song-recommender.onrender.com)
 

## Teaching

I teach math at Seattle University. For a look at my Calculus I class, see the [course notes](https://juansalinas2.github.io/Math-1334---Calculus/) and [concept map](https://juansalinas2.github.io/Math-1334---Calculus/map/).

Try this game to test your calculus chops! [*Critical Point*](https://juansalinas2.github.io/Math-1334---Calculus/map/challenge.html).

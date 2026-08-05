# Juan Salinas 

I’m a data scientist focused on recommendation systems, music intelligence, and interpretable machine learning. I earned my Ph.D. in Mathematics from the University of Washington under Max Lieblich, specializing in algebraic geometry. My thesis studied [representations of configurations](https://drive.google.com/file/d/1GAHcc34xd7MJDQTr0NjYAM9humm89cNt/view).

The hardest part of any analysis is to ask the right questions. I enjoy finding honest questions, making messy data usable, and building models that show how data hides answers to these questions.

## Featured Projects 

### [Olist Delivery Forecasting](https://github.com/juansalinas2/olist_analysis)

**Main Question**
> Can delivery dates be more accurate without making the customer promise unnecessarily conservative?
> 
`27.6% lower ETA error` · `18,603 test orders` · `98.7% U95 coverage`

Built a purchase-time forecasting pipeline using chronological validation and quantile regression. On 18,603 test orders, the median ETA reduced error by **27.6%** (5.03 → 3.64 days). The conservative promise reached **98.68% reliability**, but was **1.71 days longer** than Olist’s.

**Decision:** shadow-test the improved ETA, but do not launch the longer customer promise until calibration improves.

[View project](https://github.com/juansalinas2/olist_analysis) · [Tableau dashboard](https://public.tableau.com/app/profile/juan.salinas7316/viz/OlistDeliveryPromiseDecisionDashboard/ExecutiveDecisionDashboard)

---

### [Harmonic Trends](https://github.com/juansalinas2/harmonic-trends)
**Main Question:** 
> Can harmony be treated as a learnable vocabulary, then used to understand musical style, change over time, and recommend songs by how they move harmonically?

Built an end-to-end music data project that cleans and standardizes noisy chord data, stores analysis-ready tables in DuckDB, and represents harmony using n-grams, embeddings, and sequence models. The analysis explores genre-specific patterns, historical trends, and recommendations based on harmonic movement.

[View project](https://github.com/juansalinas2/harmonic-trends) · [Explore the interactive dashboards](https://huggingface.co/spaces/juansalinas2/harmonic-trends)

---

### [Deep Learning Song Recommender](https://github.com/juansalinas2/dl-song-recommender)
**Main Question:** 
> Can listener descriptions teach an audio model which songs sound musically similar?

Built a content-based recommender that learns song embeddings from listener tags and audio. The model combines full-mix and instrument-stem spectrograms using a late-fusion ResNet18, contrastive learning, and tag-informed supervision. I evaluated recommendation quality with retrieval metrics and built a web interface for exploring similar songs.

[View project](https://github.com/juansalinas2/dl-song-recommender) · [View the web app](https://github.com/juansalinas2/dl-song-recommender)
 

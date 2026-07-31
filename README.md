# Juan Salinas 

I’m a data scientist with a focus on recommendation systems, music intelligence, and interpretable machine learning. I received my Ph.D. in Mathematics from the University of Washington under Max Lieblich, where I studied [representations of configurations.](https://drive.google.com/file/d/1GAHcc34xd7MJDQTr0NjYAM9humm89cNt/view)

The hardest part of any analysis is to ask the right questions. I enjoy finding honest questions, making messy data usable, and building models that show how data hides answers to these questions.

## Featured Projects 

### [Olist Delivery Forecasting](https://github.com/juansalinas2/olist_analysis)

**Main Question**
> Can delivery dates be more accurate without making the customer promise unnecessarily conservative?
> 
`27.6% lower ETA error` · `18,603 test orders` · `98.7% U95 coverage`

Built and evaluated purchase-time delivery forecasts using chronological validation and quantile regression.

**Business decision:** Test the improved ETA internally, but retain Olist’s current customer promise until the alternative achieves comparable reliability without adding extra days.

[View the analysis →](https://github.com/juansalinas2/olist_analysis)

### [Harmonic Trends](https://github.com/juansalinas2/harmonic-trends)
**Main Question:** 
> Can harmony be treated as a learnable vocabulary, then used to understand musical style, change over time, and recommend songs by how they move harmonically?

A deep exploratory data analysis project that studies chord progressions as a musical language.

I cleaned and normalized noisy chord data, built harmonic n-gram representations, stored analysis-ready tables in DuckDB, and used trend analysis, genre lift, embeddings, and conditional language modeling to study how harmony changes across time and style.

**Highlights:** data cleaning, feature engineering, DuckDB, EDA, embeddings, interpretable analysis  
**App:** [Harmonic Trends Explorer](https://juansalinas2-harmonic-trends-explorer.hf.space)     
**Interactive Dashboards:** [Harmonic Trends on Hugging Face](https://huggingface.co/spaces/juansalinas2/harmonic-trends)

### [Deep Learning Song Recommender](https://github.com/juansalinas2/dl-song-recommender)
**Main Question:** 
> Can an audio model learn musically meaningful similarity from the way listeners describe songs?

A content-based music recommender that learns audio embeddings for song similarity using listener-tag supervision.

Using full-mix and stem spectrograms, we trained a late-fusion ResNet18 model with tag-informed supervision and contrastive learning, then evaluated recommendations with retrieval metrics and a user-facing web app.

**Highlights:** PyTorch, audio ML, recommender systems, representation learning, model evaluation  
**App:** [Deep Learning Song Recommender](https://dl-song-recommender.onrender.com)

## Skills

Python, SQL, Pandas, NumPy, PyTorch, DuckDB, Jupyter, data cleaning, exploratory data analysis, machine learning, recommender systems, embeddings, statistics, and model evaluation.

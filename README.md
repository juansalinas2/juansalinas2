# Juan Salinas 

I’m a mathematician and adjunct math professor at Seattle University, transitioning into data science and AI/ML engineering with a focus on recommendation systems, music intelligence, and interpretable machine learning.

The hardest part of any analysis is to ask the right questions. I enjoy finding honest questions, making messy data usable, and building models that show how data hides answers to these questions.

## Featured Projects

### [Reliable Delivery Promises for Olist](https://github.com/juansalinas2/olist_analysis)

An end-to-end data science project predicting e-commerce delivery times and evaluating whether a new customer promise should replace Olist’s existing estimate.

- Reduced delivery-time MAE by **27.6%**
- Reduced late orders by **63.5%**
- Found that the new promise was more reliable but **1.71 days longer**
- Recommended shadowing the improved ETA while keeping Olist’s current promise

[![Olist delivery-promise results](https://raw.githubusercontent.com/juansalinas2/olist_analysis/main/docs/assets/reliability_sharpness.png)](https://github.com/juansalinas2/olist_analysis)

**Tools:** Python, pandas, scikit-learn, Plotly, quantile regression

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

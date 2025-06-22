📉 Fixing a Failing Product — A Review-Driven Business Rescue Mission

🔍 Project Overview
This repository contains our solution to a real-world challenge tackled during a 5-day intensive Data Science & AI Task Force sprint.
Our goal: Diagnose why a high-rated product is underperforming on Amazon, using AI-powered review analysis.
Despite seemingly strong surface metrics (like star ratings), the product faced:

📉 Declining sales
📈 Increasing complaints and return rates
📊 Unchanged or misleadingly positive star ratings

To investigate, we combined Natural Language Processing (NLP) techniques and Business Intelligence tools to extract actionable insights from thousands of Amazon customer reviews.

🧠 Problem Statement
"Are customers truly satisfied, or are surface ratings hiding deeper frustrations?"
Our mission was to:
1. Detect gaps between star ratings and true customer sentiment
2. Identify the most discussed product aspects and how users feel about them
3. Understand emotional reactions and audience segments
4. Benchmark performance vs competitors
5. Prioritize fixes that will restore trust and satisfaction

🛠️ Methods & Tools:
🔎 NLP Techniques Used
1. Sentiment Analysis – Identify polarity of review text
2. Emotion Detection – Classify emotions: joy, anger, trust, sadness, etc.
3. Aspect-Based Sentiment Analysis (ABSA) – Understand opinions on specific features (e.g., “Battery”, “Comfort”, “Shipping”)
4. Comparative Phrase Extraction – Detect comparisons (e.g., “better than”, “worse than” competitors)

📊 Data Visualization
Interactive Power BI Dashboard
  Review sentiment by aspect
  Emotion heatmaps
  Mismatches between star ratings and review tone
  Top 3 most urgent product issues
  
🎯 Key Tasks Performed
✅ 1. Satisfaction Audit
  Matched review sentiment with star ratings
  Exposed misleading 5-star reviews with negative tone

✅ 2. Feature Sentiment Mapping
  Identified key features customers care about
  Ranked aspects by:
    Mention volume
    Sentiment severity
    Emotional intensity

✅ 3. Emotion Segmentation
  Visualized emotional tone across review data
  Clustered customers into:
    Loyal promoters (positive + joy)
    Silent quitters (neutral rating + sadness)
    Vocal critics (low rating + anger)

✅ 4. Competitive Benchmarking
  Extracted competitor mentions and comparisons
  Measured sentiment gaps between our product and competitors

✅ 5. Fix Prioritization
  Categorized complaints into themes
  Ranked by:
    Frequency
    Severity
    Emotional charge
  Delivered a data-backed Top 3 Issues list

🧾 Final Business Recommendation
  We delivered a comprehensive report and dashboard addressing:
  What’s really wrong with the product?
  What do customers want most?
  Which issues should we fix first to regain trust?
  What improvements can drive long-term loyalty?

🧠 Technologies & Libraries
  Python (NLTK, TextBlob, VADER, spaCy)
  Power BI
  Pandas, NumPy, Matplotlib
  Regex, SQLite (for temporary data)
  Amazon Review Dataset

📣 Outcome
  A data-backed turnaround strategy that bridges the gap between user perception and business performance.
  This project sharpened our ability to blend AI, product analytics, and business communication—making data truly drive decisions.

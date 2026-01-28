# AI in Aviation

A collection of Jupyter notebooks demonstrating practical applications of artificial intelligence (AI) in the airline and aviation industry. Each notebook is accompanied by a Medium article that explains the airline/aviation news and AI concepts.

## Contents

- 10 Jan 2026 [Network Optimization after Airline Mergers with XGBoost](notebooks/network_optimization.ipynb)  
  ✈️ We implement XGBoost regressor to predict route profitability score for rationalizing overlapping routes in the Korean Air-Asiana merger. 
  📖 [Read the Medium article](https://medium.com/@mqignacio/korean-air-asiana-asias-mega-carrier-takes-flight-2198649fb5bc?source=friends_link&sk=e9afa5e4decf3ed9f0ce38db9ab28f91)

- 15 Jan 2026 [Fleet Assignment Optimization with Reinforcement Learning (RL)](notebooks/fleet_optimization.ipynb)  
  ✈️ We train a PPO agent to optimize fleet assignment (737-10 vs 787-10) under demand and crew constraints, demonstrated on a synthetic network inspired by Alaska/Hawaiian’s 2026 announcements. 
  📖 [Read the Medium article](https://medium.com/@mqignacio/273db335f728?source=friends_link&sk=eaa02bd9b0f70768f1b115818934f4eb)

- 20 Jan 2026 [Probabilistic Risk Assessment of SAF Mandate Compliance with Bayesian Networks](notebooks/saf_risk.ipynb)  
  ✈️ We implement a Bayesian Network using `pgmpy` to quantify the probability of meeting Thailand’s 2026 SAF blending mandate under uncertain feedstock, logistics, and policy conditions.
  📖 [Read the Medium article](https://medium.com/@mqignacio/2352796e5c41?source=friends_link&sk=2dd0a66939d7f3987b400d785be87101)

- 27 Jan 2026 [Real-Time Negotiation Sentiment Tracker: Porter Airlines Labor Crisis](notebooks/nego_sentiment.ipynb)
  ✈️ We build a local LLM pipeline to monitor Porter Airlines labor negotiations, converting news articles into structured sentiment data for a strike risk timeline.
  📖 [Read the Medium article](https://medium.com/@mqignacio/2a61f98c6bd6?source=friends_link&sk=92564ad97872ca65f6f203256297df13)

- 29 Jan 2026 [Flight Delay Cascade Prediction Using Temporal Convolutional Networks](notebooks/delay_cascade.ipynb)
  ✈️ We implement a Temporal Convolutional Network (TCN) to model and predict the 6-hour propagation of flight delays from connection hubs to spoke airports using synthetic data.
  📖 [Read the Medium article](https://medium.com/@mqignacio/149e476425c0?source=friends_link&sk=210d49e4fe5e4681f416d7eb8372dc90)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests for improvements or new notebooks.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

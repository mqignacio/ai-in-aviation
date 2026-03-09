# AI in Aviation

A collection of Jupyter notebooks demonstrating practical applications of artificial intelligence (AI) in the airline and aviation industry. Each notebook is accompanied by a Medium article that explains the airline/aviation news and AI concepts.

## Contents

- 10 Mar 2026 [Airspace Closure Impact Forecasting with a Lightweight LSTM](notebooks/airspace_closure.ipynb)
  ✈️ We train a small 2-layer LSTM in PyTorch to forecast the next 6 hours of UAE/Gulf hub flight cancellation rates from the prior 24 hours using synthetic airspace-closure recovery episodes.
  📖 [Read the Medium article](https://medium.com/@mqignacio/d6431e78d018?source=friends_link&sk=bdd9ff1dadd2da7a01239f28beb98b21)

- 05 Mar 2026 [Korean Air's AI-Powered Drone Swarms: Multi-Agent Reinforcement Learning for MRO Inspection](notebooks/drone_inspection.ipynb)
  ✈️ We train a 5-drone swarm with tabular multi-agent Q-learning to cover an aircraft inspection grid for MRO, reducing collisions and wasted steps.
  📖 [Read the Medium article](https://medium.com/@mqignacio/b0698d844e90?source=friends_link&sk=6334878e3b635a8e04ebc23a31890a0c)

- 28 Feb 2026 [Route Vulnerability Clustering: Which Canada-U.S. Air Routes Break First?](notebooks/route_clustering.ipynb)
  ✈️ We run K-Means and hierarchical clustering with UMAP on a small local Canada-U.S. route dataset, then overlay WestJet’s Summer 2026 cancellations to surface fragile route archetypes.
  📖 [Read the Medium article](https://medium.com/@mqignacio/38a09f0f9f52?source=friends_link&sk=3f368e19e75c442d02f34367e5916ffb)

- 18 Feb 2026 [AI Incident Response Agent: SunExpress 737 Gear Collapse at Antalya](notebooks/incident_mgmt.ipynb)
  ✈️ We implement a local AI agent using Ollama and LangChain to automate incident response checklists, draft communications, and log actions for a taxiway gear collapse scenario.
  📖 [Read the Medium article](https://medium.com/@mqignacio/7015d4e097be?source=friends_link&sk=8f08d2d03a1d5a6c007026c0f9b0c721)

- 12 Feb 2026 [Baggage X-ray Anomaly Detection with Convolutional Autoencoders](notebooks/xray_anomaly.ipynb)
  ✈️ We build a lightweight PyTorch convolutional autoencoder on synthetic baggage X-ray images to learn normal patterns and flag anomalies via reconstruction error—mirroring DXB’s AI-assisted hand-luggage screening.
  📖 [Read the Medium article](https://medium.com/@mqignacio/95b6f454c209?source=friends_link&sk=3ddca1b27cfc857c32aa09973ee33703)

- 09 Feb 2026 [Agentic AI for Airline Hub Disruption Management](notebooks/ops_control.ipynb)
  ✈️ We build a local multi-agent system (CrewAI + Ollama) that queries a read-only hub ops SQLite snapshot to draft a storm disruption action plan with crew duty-limit checks.
  📖 [Read the Medium article](https://medium.com/@mqignacio/033584c256af?source=friends_link&sk=efddfd3428b4caa71c49a8315cb96868)

- 04 Feb 2026 [Autonomous Ground Handling at Changi Airport with Multi-Agent RL](notebooks/autonomous_tractor.ipynb)
  ✈️ We allow autonomous baggage tractors to learn safety and coordination rules using multi-agent Q-learning in a simulation of Changi's airside operations.
  📖 [Read the Medium article](https://medium.com/@mqignacio/8d707bdf1394?source=friends_link&sk=83f13d82e717c1c03f7f9b284a78243a)

- 29 Jan 2026 [Flight Delay Cascade Prediction Using Temporal Convolutional Networks](notebooks/delay_cascade.ipynb)
  ✈️ We implement a Temporal Convolutional Network (TCN) to model and predict the 6-hour propagation of flight delays from connection hubs to spoke airports using synthetic data.
  📖 [Read the Medium article](https://medium.com/@mqignacio/149e476425c0?source=friends_link&sk=210d49e4fe5e4681f416d7eb8372dc90)

- 27 Jan 2026 [Real-Time Negotiation Sentiment Tracker: Porter Airlines Labor Crisis](notebooks/nego_sentiment.ipynb)
  ✈️ We build a local LLM pipeline to monitor Porter Airlines labor negotiations, converting news articles into structured sentiment data for a strike risk timeline.
  📖 [Read the Medium article](https://medium.com/@mqignacio/2a61f98c6bd6?source=friends_link&sk=92564ad97872ca65f6f203256297df13)

- 20 Jan 2026 [Probabilistic Risk Assessment of SAF Mandate Compliance with Bayesian Networks](notebooks/saf_risk.ipynb)  
  ✈️ We implement a Bayesian Network using `pgmpy` to quantify the probability of meeting Thailand’s 2026 SAF blending mandate under uncertain feedstock, logistics, and policy conditions.
  📖 [Read the Medium article](https://medium.com/@mqignacio/2352796e5c41?source=friends_link&sk=2dd0a66939d7f3987b400d785be87101)

- 15 Jan 2026 [Fleet Assignment Optimization with Reinforcement Learning (RL)](notebooks/fleet_optimization.ipynb)  
  ✈️ We train a PPO agent to optimize fleet assignment (737-10 vs 787-10) under demand and crew constraints, demonstrated on a synthetic network inspired by Alaska/Hawaiian’s 2026 announcements. 
  📖 [Read the Medium article](https://medium.com/@mqignacio/273db335f728?source=friends_link&sk=eaa02bd9b0f70768f1b115818934f4eb)

- 10 Jan 2026 [Network Optimization after Airline Mergers with XGBoost](notebooks/network_optimization.ipynb)  
  ✈️ We implement XGBoost regressor to predict route profitability score for rationalizing overlapping routes in the Korean Air-Asiana merger. 
  📖 [Read the Medium article](https://medium.com/@mqignacio/korean-air-asiana-asias-mega-carrier-takes-flight-2198649fb5bc?source=friends_link&sk=e9afa5e4decf3ed9f0ce38db9ab28f91)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests for improvements or new notebooks.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

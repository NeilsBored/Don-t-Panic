# Don-t Panic 
# Directed, Oracular Networked Time-series: Predictive Analytics for Networked Influence &amp; Causality

Space is big. You just won't believe how vastly, hugely, mind-bogglingly big it is. I mean, you may think it's a long way down the road to the chemist's, but that's just peanuts to space. 
- Douglas Adams


<b>What is this?</b>

DON’T PANIC (Path B only) is a supply-chain-aware forecasting toolkit built on IBM Granite Time Series Foundation Models (TSFM). It uses Tiny Time Mixer (TTM) models with mix-channel decoding to learn cross-series influence (e.g., supplier → customer). The project is JSON-first, Docker-ready, and comes with a small FastAPI service.

<b>You get:</b>

JSON data pipeline (prices + supply-chain graph → tidy features)

Fine-tuning support with decoder_mode="mix_channel"

Zero-shot inference for quick sanity checks

Minimal CLI/API to serve forecasts as JSON

Plots optional; repo focuses on API + modeling core

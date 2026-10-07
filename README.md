### Hi, I'm George

Junior data scientist / ML engineer. I build small end-to-end ML systems and write down honestly how well they work: baselines, intervals, negative results and limitations included.

#### Projects

Three systems, each split into repositories that link to one another. Every README starts with what it demonstrates, how to run it, and where it falls short.

| Project | What it is | Numbers it reports | Repositories |
|---|---|---|---|
| **Pinance**: [live](https://pinance.katzer.ru) | Real-time crypto price forecasting with a confidence corridor, and a UI that shows the measured hit rate next to every forecast | walk-forward validation against naive baselines; directional accuracy about 52 % on a 5-minute horizon, reported as it is | [training](https://github.com/GKatzer/Pinance_ml_training) · [inference](https://github.com/GKatzer/Pinance_ml_inference) · [backend](https://github.com/GKatzer/Pinance_backend) · [frontend](https://github.com/GKatzer/Pinance_frontend) |
| **Defish**: [live](https://defish.katzer.ru) | Finds fish in aquarium photos and flags visible signs of disease: YOLOv8 detector, DINOv2 classifier with a confidence gate, ONNX service, async API, web client | detector AP50 0.66 against 0.55 on a leak-free split; classifier accuracy 0.57 (top-3 0.84) over 138 crops, with the small-sample caveat | [ML](https://github.com/GKatzer/Defish-ML-train) · [inference](https://github.com/GKatzer/Defish-inference) · [backend](https://github.com/GKatzer/Defish-backend) · [frontend](https://github.com/GKatzer/Defish-frontend) |
| **Graph Series**: [live](https://graph-series.katzer.ru) | Search over about 56,000 TV series by meaning, title or person, and a knowledge graph that grows on a canvas | Hit@1 0.606 and MRR 0.648 on 500 title queries; graph re-ranking effect measured with a paired bootstrap | [ETL](https://github.com/GKatzer/graph-series_ETL) · [backend](https://github.com/GKatzer/graph-series_backend) · [web app](https://github.com/GKatzer/graph-series_ml) |

#### Tools I use

Python, pandas, scikit-learn, LightGBM, PyTorch and ONNX Runtime · FastAPI, PostgreSQL and TimescaleDB, Redis, RabbitMQ, Neo4j, Qdrant · Docker · React and Next.js · pytest and Vitest.

#### Contact

Telegram: [@denisov_george](https://t.me/denisov_george)

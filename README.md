# TantyBot-Pro

A smart construction cost estimating chatbot with a static web interface, designed for natural conversation and reliable estimates.

## Features
- Chat interface with Enter key support
- Cost estimates using a mock data model (items, assemblies, rates, crews, markups)
- RAG-like retrieval for similar items and assemblies
- Price inquiries via Cost DB (no hallucination)
- Casual yet dependable tone

## Usage
- Visit the live site after deployment.
- Start with "Hi" or ask for an estimate (e.g., "location: Manila", "square footage: 1000").
- Try "price of concrete" or "update with premium materials."

## Deployment
- Enable GitHub Pages in Settings > Pages, selecting the main branch.
- Access at https://<your-username>.github.io/TantyBot-Pro/.

## Future Plans
- Migrate to Next.js + Tailwind for dynamic UI.
- Add FastAPI backend with Estimator Agent (Document Parser, Quantity Extractor, etc.).
- Integrate Postgres, DuckDB, Redis, and Milvus for data layers.
- Implement learning loop with CSV ingestion and model training.

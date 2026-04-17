# AI SOC Architecture (Low-Level)

Interactive, single-page architecture diagram for a modern AI-driven SOC, including:
- Logical vs Technical/Deployment views
- Click-through component details (responsibilities + inputs/outputs)
- Filters, search, and curated “Concepts” + “Insights” overlays

## Live

https://shanjulmittal.github.io/ai-soc-architecture-low-level-/

## Run locally

Open [index.html](file:///Users/shanjulmittal/AI-SOC/index.html) directly in a browser, or serve the folder:

```bash
python3 -m http.server 8001
```

Then open http://localhost:8001/

## Usage

- Use the **Logical** / **Technical / Deployment** toggle to switch viewpoints.
- Click a component box to see details in the right panel; edges highlight for the selected node.
- Use **Concepts** for the “how it wins” mental model, and **Insights** for scoreboard, threat coverage, GRC, EA, and review tabs.

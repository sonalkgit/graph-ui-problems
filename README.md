# 🌐 Graph Crafter Hackathon: Visualize the Knowledge

Welcome to **Graph Crafter**, a frontend-focused hackathon hosted by **ZySec AI**. Your challenge is to build a powerful, elegant, and interactive **Graph UI** from structured JSON data — similar to tools like Neo4j, Memgraph, or network visualizations used in security, compliance, and knowledge management.

---

## 📘 Background

Graphs are everywhere — from policy engines and user access systems to social networks and LLM knowledge graphs. But visualizing them clearly and interactively is a hard UI/UX problem.

This hackathon challenges you to build a **modern, reactive, and insightful Graph UI** that reads a JSON representation of nodes and edges, and turns it into an interactive visualization.

---

## 🚩 Problem Statement

> Build a web-based **Graph UI** that reads a structured JSON file describing nodes, edges, metadata, and styling — and renders it into an interactive, pannable, zoomable, and understandable graph.

Your UI must:
- Visualize labeled nodes and edges
- Support directional edges and metadata tooltips
- Respect styles (e.g., shape, color, dashed lines)
- Allow node/edge interactions (hover/click)
- Be responsive and user-friendly

---

## 📦 JSON Input Format

The UI must accept input like this:

```json
{
  "nodes": [
    {
      "id": "user_1",
      "label": "Alice",
      "type": "Person",
      "properties": {
        "email": "alice@example.com",
        "role": "Analyst"
      },
      "style": {
        "color": "#4CAF50",
        "shape": "circle"
      },
      "group": "Team A"
    },
    {
      "id": "doc_1",
      "label": "Report Q1",
      "type": "Document",
      "properties": {
        "created": "2024-03-01",
        "status": "approved"
      },
      "style": {
        "color": "#2196F3",
        "shape": "rectangle"
      },
      "group": "Documents"
    }
  ],
  "edges": [
    {
      "source": "user_1",
      "target": "doc_1",
      "label": "authored",
      "direction": "one-way",
      "style": {
        "dashed": false,
        "color": "#555"
      }
    }
  ],
  "meta": {
    "title": "Knowledge Graph - Access Control",
    "description": "Sample graph representing users, documents, and policies."
  }
}




Here’s your complete Graph UI Hackathon README.md, titled Graph Crafter: Visualize the Knowledge — styled for a hackathon, using the detailed JSON schema you approved:

⸻



# 🌐 Graph Crafter Hackathon: Visualize the Knowledge

Welcome to **Graph Crafter**, a frontend-focused hackathon hosted by **ZySec AI**. Your challenge is to build a powerful, elegant, and interactive **Graph UI** from structured JSON data — similar to tools like Neo4j, Memgraph, or network visualizations used in security, compliance, and knowledge management.

---

## 📘 Background

Graphs are everywhere — from policy engines and user access systems to social networks and LLM knowledge graphs. But visualizing them clearly and interactively is a hard UI/UX problem.

This hackathon challenges you to build a **modern, reactive, and insightful Graph UI** that reads a JSON representation of nodes and edges, and turns it into an interactive visualization.

---

## 🚩 Problem Statement

> Build a web-based **Graph UI** that reads a structured JSON file describing nodes, edges, metadata, and styling — and renders it into an interactive, pannable, zoomable, and understandable graph.

Your UI must:
- Visualize labeled nodes and edges
- Support directional edges and metadata tooltips
- Respect styles (e.g., shape, color, dashed lines)
- Allow node/edge interactions (hover/click)
- Be responsive and user-friendly

---

## 📦 JSON Input Format

The UI must accept input like this:

```json
{
  "nodes": [
    {
      "id": "user_1",
      "label": "Alice",
      "type": "Person",
      "properties": {
        "email": "alice@example.com",
        "role": "Analyst"
      },
      "style": {
        "color": "#4CAF50",
        "shape": "circle"
      },
      "group": "Team A"
    },
    {
      "id": "doc_1",
      "label": "Report Q1",
      "type": "Document",
      "properties": {
        "created": "2024-03-01",
        "status": "approved"
      },
      "style": {
        "color": "#2196F3",
        "shape": "rectangle"
      },
      "group": "Documents"
    }
  ],
  "edges": [
    {
      "source": "user_1",
      "target": "doc_1",
      "label": "authored",
      "direction": "one-way",
      "style": {
        "dashed": false,
        "color": "#555"
      }
    }
  ],
  "meta": {
    "title": "Knowledge Graph - Access Control",
    "description": "Sample graph representing users, documents, and policies."
  }
}



⸻

✅ Must-Have Features
	•	🎯 Render nodes and edges using input JSON
	•	🖱️ Pan and zoom
	•	📌 Node labels and types
	•	🔄 Directional edges (arrows or icons)
	•	🧠 Tooltip on hover (show properties)
	•	🎨 Respect optional style attributes (color, shape, dashed lines)
	•	🧱 Grouping or clustering (optional)

⸻

💡 Tech Suggestions (Optional)

You may use:
	•	D3.js, Cytoscape.js, Vis.js, React Flow, Sigma.js, or any graph rendering engine
	•	React, Vue, Svelte, or vanilla JS
	•	Tailwind, SCSS, or your own styling approach

⸻

🛠️ Deliverables
	1.	Fork this repository
	2.	Create a new branch:

graphcrafter_<github-username>


	3.	Add your work to:

submissions/<github-username>/



Your folder must include:
	•	src/: Your full working project code
	•	README.md: With your:
	•	Full name
	•	GitHub username
	•	Email
	•	Libraries/tools used
	•	Short description of design decisions
	•	(Optional) Deployed link (e.g., Netlify/Vercel)
	•	(Optional) Demo video (3–5 minutes)

	4.	Submit a Pull Request (PR) with the title:

[Graph Crafter] Submission - <Your Name>



⸻

🧪 Scoring Rubric (100 Points)

Category	Points	Description
Graph Rendering	25	Visual clarity, accuracy, responsiveness
Interactivity & UX	20	Tooltips, zoom, pan, click behavior
Styling & Theming	15	Use of color, shapes, consistency
Code Quality	15	Modularity, naming, comments
JSON Handling	15	Dynamic parsing, robustness
Bonus Features	10	Groups, search, dark mode, edge animation



⸻

🏆 Rewards
	•	🥇 Top Winner: Interview for a full-time role at ZySec AI
	•	🏅 Top 4 Finalists: Each receives $100 USD
	•	🖼️ Best entries featured on ZySec’s website & socials

⸻

📬 Contact

Organizer: Venkatesh Siddi
Company: ZySec AI

⸻

“Craft the graph. Create clarity. Control complexity.” 🔗

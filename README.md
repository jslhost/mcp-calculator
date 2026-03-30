Initialiser le projet : 

```uv init mcp-server```

```cd mcp-server```

Ajouter MCP :

```uv add "mcp[cli]"```

Pour lancer le serveur local :

```uv run --with mcp mcp-calculator.py```

Pour l'ajouter sur Claude :

```claude mcp add --transport http my-server http://localhost:8000/mcp```

project/
├── agents/
│   ├── agent_manager.py   # AgentManager (interaction utilisateur)
│   ├── agent_researcher.py # AgentResearcher (recherche via function calling)
│   ├── agent_analyzer.py  # AgentAnalyzer (validation)
│   └── agent_coder.py     # AgentCoder (génération de code)
├── orchestrator.py         # Coordonne les interactions entre agents
├── interface/
│   ├── user_chat.py        # Interface utilisateur
│   ├── agent_chat.py       # Log des interactions des agents
├── memory.py               # Gestion du contexte utilisateur et mémoire partagée
├── requirements.txt        # Dépendances
└── main.py                 # Point d'entrée principal

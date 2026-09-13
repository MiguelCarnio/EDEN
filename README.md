🧪 EDEN — Estudo e Descoberta de Elementos Naturais

O EDEN (Estudo e Descoberta de Elementos Naturais) é uma proposta de projeto para o desenvolvimento de um simulador sandbox interativo de química que combina a Godot Engine com Python e PyTorch.

A ideia do projeto é oferecer um ambiente virtual intuitivo em 2D/3D onde o usuário possa manipular frascos, misturar elementos e observar transformações visuais em tempo real, enquanto um modelo preditivo em PyTorch roda em segundo plano calculando e gerenciando as propriedades, estabilidades e produtos das combinações químicas.

📌 Ideia do Projeto

Simulação Sandbox Interativa: Espaço livre na Godot Engine para o usuário manipular recipientes e misturar substâncias através de mecânicas de drag-and-drop.

Inteligência no Backend: Processamento em Python + PyTorch para prever comportamentos de misturas, estimar reações e determinar os resultados químicos.

Feedback Visual Dinâmico: Respostas visuais diretas (mudança de cor, fumaça, fogo, efervescência) acionadas na Godot com base nos dados gerados pelo backend.

Interface Direta: Inventário de substâncias, bancada de testes e diário de descobertas para salvar o progresso e o catálogo do usuário.

🛠️ Tecnologias Planejadas

Interface e Frontend: Godot Engine 4.x (GDScript)

Processamento e Backend: Python 3.10+

Modelagem e Redes Neurais: PyTorch

Comunicação Frontend/Backend: Integração via WebSockets, HTTP local (FastAPI) ou chamadas de processo (IPC)

🧭 Roadmap (Ideias de Recursos Futuros)

[ ] Criar a bancada principal e a interface do laboratório na Godot Engine.

[ ] Implementar a mecânica de arrastar e soltar (Drag-and-Drop) para os recipientes e ferramentas.

[ ] Desenvolver a API / script em Python com PyTorch para processamento das combinações.

[ ] Estabelecer a comunicação de rede/processo entre a Godot Engine e o servidor em Python.

[ ] Configurar efeitos visuais de partículas (GPUParticles) para animação das reações.

[ ] Implementar o diário de descobertas (logbook) para catalogar as misturas já encontradas pelo usuário.

📄 Licença

Projeto conceitual idealizado para fins de estudo, pesquisa e desenvolvimento integrando Godot Engine e Inteligência Artificial.

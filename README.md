#  EDEN — Estudo e Descoberta de Elementos Naturais

O **EDEN** (*Estudo e Descoberta de Elementos Naturais*) é uma proposta de projeto para o desenvolvimento de um simulador *sandbox* de química interativo que une a **Godot Engine** com **Python** e **PyTorch**.

A ideia é criar um ambiente inteligente em 2D/3D onde o usuário possa interagir com elementos, misturar compostos e observar transformações visuais em tempo real, enquanto um modelo em PyTorch roda por trás para processar as regras, combinações e predições das reações.

---

##  Ideia do Projeto

* **Simulação Sandbox Interativa:** Espaço livre na Godot Engine para o usuário manipular recipientes e misturar substâncias.
* **Inteligência no Backend:** Uso de Python e PyTorch para calcular reações, prever comportamentos de misturas e gerenciar as propriedades dos compostos.
* **Feedback Visual em Tempo Real:** Respostas visuais diretas (mudança de cor, efervescência, fumaça, fogo) acionadas na Godot a partir das respostas do modelo.
* **Interface Direta:** Controle de inventário, bancada de testes e um diário de descobertas para registrar o que já foi sintetizado.

---

##  Tecnologias Planejadas

* **Interface e Frontend (Jogo):** Godot Engine 4.x (`GDScript`)
* **Lógica e Inteligência (Backend):** Python 3.10+
* **Modelagem e Redes Neurais:** PyTorch
* **Comunicação:** Integração entre Godot e Python via HTTP/WebSockets ou chamadas de sistema (IPC)

---

##  Ideias de Recursos Futuros (Roadmap)

- [ ] Criar a bancada principal do laboratório na Godot Engine.
- [ ] Implementar a mecânica de arrastar e soltar (Drag and Drop) para os recipientes.
- [ ] Desenvolver a API/script em Python com PyTorch para processar as combinações de elementos.
- [ ] Conectar a comunicação entre a Godot Engine e o servidor Python.
- [ ] Adicionar efeitos visuais de partículas (`GPUParticles`) para representar as reações calculadas.
- [ ] Criar diário de descobertas (*logbook*) para salvar o progresso do usuário.

---

## 📄 Licença

Projeto conceitual idealizado para fins de estudo e desenvolvimento em Godot Engine e Inteligência Artificial.

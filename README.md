# Directory Organizer Engine

Um organizador automático de arquivos multiplataforma com uma interface moderna e intuitiva.

## 🚀 Funcionalidades

- **Organização Inteligente**: Categoriza arquivos por extensão em pastas específicas (PDFs, Imagens, Vídeos, etc.).
- **Multiplataforma**: Funciona em Windows, Linux e macOS graças ao uso de `pathlib`.
- **Prevenção de Conflitos**: Renomeia automaticamente arquivos com o mesmo nome para evitar sobrescrita.
- **Interface Moderna**: Desenvolvida com `ttkbootstrap` (tema Darkly).
- **Logs em Tempo Real**: Veja exatamente o que está acontecendo durante o processo.
- **Feedback Visual**: Barra de progresso e notificações de conclusão.

## 🛠️ Tecnologias

- Python 3.10+
- [ttkbootstrap](https://ttkbootstrap.readthedocs.io/)
- Pathlib (Standard Library)
- Shutil (Standard Library)

## 📁 Estrutura do Projeto

```text
Directory-Organizer-Engine/
├── engine/
│   ├── application/    # Controlador e integração UI/Service
│   ├── config/         # Configurações de extensões e temas
│   ├── service/        # Lógica central de organização
│   ├── ui/             # Componentes da interface gráfica
│   └── utils/          # Funções auxiliares (renomeação)
├── main.py             # Ponto de entrada da aplicação
├── requirements.txt    # Dependências do projeto
└── verify_logic.py     # Script de teste de lógica
```

## ⚙️ Como Usar

1. Certifique-se de ter o Python instalado.
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute a aplicação:
   ```bash
   python main.py
   ```

## 📝 Configurações

Você pode personalizar as categorias de arquivos e os nomes das pastas editando o arquivo `engine/config/settings.py`.

---
Desenvolvido como um motor de organização de arquivos eficiente e seguro.
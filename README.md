<p align="center">
  <img src="assets/logo.png" width="200" alt="Directory Organizer Engine Logo">
</p>

<h1 align="center">Directory Organizer Engine</h1>

<p align="center">
  <strong>Um motor de organização de arquivos potente, seguro e multiplataforma.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Version">
  <img src="https://img.shields.io/badge/UI-ttkbootstrap-blue?style=for-the-badge" alt="UI Framework">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge" alt="Platforms">
</p>

---

## 🌟 Visão Geral

O **Directory Organizer Engine** é uma ferramenta desenvolvida para resolver a desordem digital. Com uma interface moderna e intuitiva, ele automatiza a tarefa tediosa de classificar arquivos, movendo-os para pastas categorizadas com base em suas extensões, garantindo que sua área de trabalho e pastas de downloads permaneçam sempre limpas.

<p align="center">
<img width="798" height="625" alt="image" src="https://github.com/user-attachments/assets/319cac29-6437-4584-a3ff-2b2e0e171f9c" />

</p>

## 🚀 Funcionalidades Principais

- 🧠 **Organização Inteligente**: Detecta e move arquivos automaticamente para categorias como Documentos, Imagens, Vídeos, Executáveis, etc.
- 🛡️ **Segurança de Arquivos**: Sistema anti-conflito que renomeia arquivos duplicados em vez de sobrescrevê-los.
- 🎨 **Interface Premium**: Interface baseada em `ttkbootstrap` com tema escuro nativo e feedback visual em tempo real.
- 📊 **Monitoramento**: Logs detalhados e barra de progresso para acompanhar cada movimento do sistema.
- ⚙️ **Altamente Customizável**: Altere temas, categorias e extensões facilmente através do arquivo de configuração.

## 🛠️ Tecnologias

O projeto utiliza o que há de melhor no ecossistema Python para garantir performance e portabilidade:

- **Linguagem**: [Python 3.10+](https://www.python.org/)
- **Interface Gráfica**: [ttkbootstrap](https://ttkbootstrap.readthedocs.io/) (Temas modernos para Tkinter)
- **Manipulação de Arquivos**: `pathlib` e `shutil` (Bibliotecas padrão robustas)
- **Logging**: Sistema de log integrado para auditoria de operações.

## 📁 Estrutura do Projeto

A arquitetura segue princípios de modularidade para facilitar a manutenção:

```text
Directory-Organizer-Engine/
├── assets/             # Recursos visuais (Logos, Mockups)
├── engine/
│   ├── application/    # Camada de controle (MainApp)
│   ├── config/         # Configurações globais (Extensões, Temas)
│   ├── service/        # Lógica de negócio (OrganizerService)
│   ├── ui/             # Componentes visuais e janelas
│   └── utils/          # Utilitários de sistema e tratamento de nomes
├── main.py             # Ponto de entrada
└── requirements.txt    # Dependências do projeto
```

## ⚙️ Como Começar

### Pré-requisitos
- Python 3.10 ou superior instalado.

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Davii13/Directory-Organizer-Engine.git
   cd Directory-Organizer-Engine
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute a aplicação:
   ```bash
   python main.py
   ```

## 📝 Configuração Personalizada

Você pode ajustar o comportamento do motor editando `engine/config/settings.py`:

```python
# Exemplo: Adicionar uma nova categoria
FILE_CATEGORIES = {
    'Projetos': ['.py', '.js', '.html', '.css'],
    # ... outras categorias
}

# Alterar o tema visual
APP_THEME = 'darkly' # Opções: cyborg, solar, vapor, etc.
```

## 🤝 Contribuição

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Insira suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---
<p align="center">
  Desenvolvido com ❤️ por <a href="https://github.com/Davii13">Davii13</a>
</p>

# Dashboard de Salários na Área de Dados

Um dashboard interativo em **Streamlit** para explorar dados salariais na área de dados, com filtros por ano, senioridade, tipo de contrato e tamanho da empresa.

🔗 **Acesse o app online:**  
https://imersao-dados-python2026-alura.streamlit.app/

---

## 📊 Funcionalidades

- Filtros dinâmicos por ano, senioridade, contrato e tamanho da empresa
- KPIs com salário médio, máximo e cargo mais frequente
- Gráficos interativos com Plotly
- Mapa com salário médio de Data Scientists por país
- Tabela completa dos dados filtrados

---

## 🧰 Tecnologias

- Python
- Streamlit
- Pandas
- Plotly

---

## ▶️ Como rodar localmente

```bash
# 1) Clone o repositório
git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

# 2) Crie e ative um ambiente virtual (opcional)
python -m venv .venv
[Activate.ps1](http://_vscodecontentref_/0)

# 3) Instale as dependências
pip install -r [requirements.txt](http://_vscodecontentref_/1)

# 4) Execute o app
streamlit run [app.py](http://_vscodecontentref_/2)
```

---

## 📁 Como criar uma pasta nova no projeto

### Criando pastas via linha de comando

Para criar uma nova pasta (diretório) no projeto, você pode usar o comando `mkdir`:

```bash
# Criar uma única pasta
mkdir nome-da-pasta

# Criar múltiplas pastas de uma vez
mkdir pasta1 pasta2 pasta3

# Criar uma estrutura de pastas aninhadas
mkdir -p pasta-pai/pasta-filho/pasta-neto
```

### Estrutura de pastas sugerida

O projeto já possui algumas pastas organizadas:

```
imersao-dados-python/
├── data/          # Arquivos de dados (.csv, .json, etc)
├── docs/          # Documentação adicional
├── src/           # Módulos e código fonte adicional
├── app.py         # Aplicação principal do Streamlit
├── README.md      # Este arquivo
└── requirements.txt
```

### Exemplos de organização

Você pode criar pastas para organizar melhor seu projeto:

```bash
# Pasta para imagens e recursos visuais
mkdir assets

# Pasta para notebooks de análise
mkdir notebooks

# Pasta para testes
mkdir tests

# Pasta para scripts auxiliares
mkdir scripts
```

### Nota sobre Git

- Pastas vazias não são rastreadas pelo Git automaticamente
- Para manter uma pasta vazia no repositório, adicione um arquivo `.gitkeep` dentro dela:
  ```bash
  mkdir minha-pasta
  touch minha-pasta/.gitkeep
  git add minha-pasta/.gitkeep
  ```

### Usando IDEs

Se você estiver usando uma IDE como VS Code, PyCharm ou similar, também pode:
1. Clicar com botão direito no explorador de arquivos
2. Selecionar "Nova Pasta" ou "New Folder"
3. Digite o nome da pasta e pressione Enter

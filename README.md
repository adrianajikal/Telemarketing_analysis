# Telemarketing Analysis App

Este é um projeto de análise de dados de campanhas de telemarketing desenvolvido utilizando **Python** e **Streamlit**. O objetivo da aplicação é permitir que o usuário carregue um arquivo de dados de campanhas, aplique filtros, visualize proporções e gráficos, e baixe os dados filtrados em formato Excel ou CSV.

---

## 🎯 **Funcionalidades**
1. **Upload de Arquivo:**
   - Suporte para arquivos CSV e Excel.
   - Carregamento de dados de campanhas de marketing bancário.

2. **Filtros Dinâmicos:**
   - Idade (slider).
   - Profissão.
   - Estado civil.
   - Possui empréstimo ou financiamento.
   - Meio de contato.
   - Mês e dia da semana.

3. **Visualizações:**
   - Gráficos de barras ou pizza para proporção de sucesso da campanha.
   - Visualização de dados brutos e filtrados.

4. **Exportação de Dados:**
   - Baixe os dados filtrados em formato Excel (.xlsx) ou CSV (.csv).

---

## 🛠️ **Tecnologias Utilizadas**
- **Streamlit:** Interface interativa para visualização de dados.
- **Pandas:** Manipulação e análise de dados.
- **Seaborn e Matplotlib:** Criação de gráficos e visualizações.
- **XlsxWriter:** Exportação para Excel.
- **Pillow:** Exibição de imagens na interface.

---

## 🚀 **Como Executar o Projeto**

### Pré-requisitos:
- Python 3.9 ou superior.
- Bibliotecas listadas no arquivo `requirements.txt`.


## 📂 **Estrutura do Projeto**
```plaintext
telemarketing-analysis/
│
├── app_telemarketing_analysis.py   # Código principal da aplicação
├── requirements.txt                # Dependências do projeto
├── Bank-Branding.jpg               # Imagem usada na barra lateral
├── README.md                       # Documentação do projeto
└── data/                           # (Opcional) Pasta para armazenar datasets de exemplo
```

---

## 📊 **Exemplo de Dados**
O dataset esperado deve conter as seguintes colunas:
- **age:** Idade do cliente.
- **job:** Profissão do cliente.
- **marital:** Estado civil.
- **default:** Possui default no histórico de crédito.
- **housing:** Possui financiamento imobiliário.
- **loan:** Possui empréstimo.
- **contact:** Meio de contato utilizado.
- **month:** Mês do contato.
- **day_of_week:** Dia da semana do contato.
- **y:** Resposta da campanha (aceitou ou não).

---

## ✨ **Funcionalidades em Detalhe**

### 1. **Upload de Arquivo**
- O usuário pode carregar arquivos no formato `.csv` ou `.xlsx`. A aplicação automaticamente identifica o tipo de separador.

### 2. **Filtros Interativos**
- A barra lateral permite que o usuário ajuste os filtros dinamicamente:
  - Faixa etária com um slider.
  - Seleção múltipla de profissões, estado civil, entre outros.

### 3. **Gráficos**
- **Gráficos de barras:** Mostram a proporção de aceitação em relação ao total de contatos.
- **Gráficos de pizza:** Alternativa para visualizar proporções.

### 4. **Exportação**
- Dados filtrados podem ser exportados para:
  - **Excel:** `.xlsx`.
  - **CSV:** `.csv`.

---

## 🖼️ **Interface**
### Sidebar:
- Upload do arquivo.
- Filtros de dados (idade, profissão, estado civil, etc.).
- Botão de aplicação dos filtros.

### Página Principal:
- Visualização dos dados brutos.
- Dados filtrados.
- Gráficos interativos.
- Botões para download.

---

## ⚠️ **Requisitos do Dataset**
Certifique-se de que o dataset segue o padrão esperado. Colunas adicionais serão ignoradas, mas as colunas principais são obrigatórias para que a aplicação funcione corretamente.

---

## 📜 **Licença**
Este projeto é licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais informações.

---

## 🙋‍♂️ **Contribuições**
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Basta abrir uma **pull request** ou relatar um problema na seção **Issues** do repositório.

---

### Contato:
- **Email:** adrijikal.com
- **GitHub:** [adrianajikal](https://github.com/adrianajikal)
```



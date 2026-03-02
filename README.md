# 🏡 Tiny House Generator — Cerrado

Gera plantas técnicas, layouts paisagísticos e análises ergonômicas para micro-habitação modular no Cerrado brasileiro (RESEX Recanto das Araras, GO).

## Sobre o Projeto
- **Sistema construtivo:** Light Steel Frame
- **Implantação:** Diagonal 45°
- **Saneamento:** Permacultural, segregação de efluentes por cor
- **Referência:** Projeto.md (PT/EN/ES)

## Funcionalidades
- Extração automática de parâmetros do projeto
- Planta técnica principal e 4 variações
- Código de cores dos efluentes
- Fluxograma de segregação na origem
- Fundações e perfil geotécnico
- Análise bioclimática (insolação × fachadas)
- Painel de PANCs por ecossistema
- 10 layouts paisagísticos (poços, jardins, hortas)
- 6 layouts ergonômicos + heatmaps + radar
- Comparação multivariada e exportação PNG/SVG

## Como usar
1. **Pré-requisitos:**
   - Python 3.11+
   - `matplotlib`, `numpy`, `scipy`
2. **Execução:**
   - Execute o script principal:
     ```bash
     python tiny_house_generator.py
     ```
   - Ou abra o notebook `tiny_house_generator.ipynb` no Jupyter.
3. **Saída:**
   - Imagens geradas em PNG/SVG na pasta do projeto
   - Visualizações interativas no notebook

## Estrutura dos arquivos
- `tiny_house_generator.py` — Script principal auto-gerado
- `tiny_house_generator.ipynb` — Notebook organizado
- `Projeto.md` — Documento técnico de referência
- `README.md` — Este guia

## Créditos
- Projeto original: RESEX Recanto das Araras, Goiás
- Código: Arquitetura, permacultura e Python

---

> Para dúvidas, sugestões ou contribuições, entre em contato!

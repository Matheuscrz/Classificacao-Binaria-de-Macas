# Classificação Binária de Maçãs 🍏🍎

Projeto final da disciplina de Processamento Digital de Imagens.

**Autor:** Matheus Lima da Cruz  
**Matrícula:** 202100073219

---

## 🎬 Apresentação em Vídeo

Assista à apresentação do projeto no YouTube:

[![Assista no YouTube](https://img.youtube.com/vi/SEU_VIDEO_ID_AQUI/0.jpg)](https://www.youtube.com/watch?v=SEU_VIDEO_ID_AQUI)

---

## 📝 Descrição

Este projeto implementa um sistema de classificação automática de maçãs (vermelha/madura ou verde) a partir de imagens, utilizando técnicas clássicas de processamento digital de imagens.

O pipeline completo realiza:

1. **Conversão para escala de cinza**
2. **Remoção de ruído** (Filtro de Mediana)
3. **Suavização Gaussiana**
4. **Detecção de bordas** (Sobel)
5. **Morfologia matemática** (Abertura e Fechamento)
6. **Detecção de círculos** (Transformada de Hough)
7. **Classificação da maçã** (análise dos canais R e G)

---

## 📂 Estrutura

- `Projeto_Final.ipynb`: Notebook principal com todo o pipeline e explicações.
- `images/`: Pasta para colocar as imagens de teste.

---

## 🚀 Como Executar

1. Instale as dependências:

   ```bash
   pip install numpy matplotlib scipy scikit-image
   ```

2. Coloque suas imagens na pasta `images/` (ex: `vermelha.jpg`).

3. Abra e execute o notebook `Projeto_Final.ipynb` no Jupyter ou VS Code.

4. Ajuste os parâmetros no início do notebook conforme necessário:
   - Caminho da imagem
   - Raio mínimo/máximo
   - Limiar de borda

---

## 📊 Resultados

O notebook mostra todas as etapas do processamento, com visualização intermediária e final, além da classificação automática de cada maçã detectada.

---

## 📚 Técnicas Utilizadas

- Filtros espaciais (mediana, gaussiano, Sobel)
- Morfologia matemática (abertura, fechamento)
- Transformada de Hough para círculos
- Análise de cor para classificação

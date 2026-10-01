# Projeto com Assets Corrigidos

Este é um modelo de projeto com a estrutura de caminhos (paths) corrigida para exibição de imagens e vídeos no GitHub.

## 📸 Imagens

### 1. Sintaxe Markdown (Caminho Relativo)
![Demonstração do Portfólio](assets/portfolio-preview.gif)

### 2. Sintaxe HTML (Para controlar largura/altura)
<p align="center">
  <img src="assets/portfolio-preview.gif" alt="Demonstração do Portfólio" width="80%">
</p>

---

## 🎥 Vídeos

### Tag HTML `<video>` (Vídeo Local no Repositório)
<video src="assets/demonstracao.mp4" controls width="100%"></video>

---

## 🛠️ Boas Práticas para Reduzir Erros no GitHub

1. **Case Sensitivity:** Mantenha os nomes de pastas e extensões em minúsculas (`assets/imagem.png` e não `Assets/Imagem.PNG`).
2. **Atente-se ao `.gitignore`:** Certifique-se de que formatos como `.png`, `.gif` e `.mp4` não estejam bloqueados.
3. **Caracteres Especiais:** Evite espaços ou acentos nos nomes dos arquivos (use `portfolio-preview.png` ao invés de `Prévia do Portfólio.png`).

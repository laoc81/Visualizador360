# Visualizador 360º
### Visualizador Esférico 360° 

[cite_start]O **Visualizador360** é uma ferramenta desenvolvida para suprir a lacuna de suporte nativo a imagens esféricas no Sistema Eletrônico de Informações (SEI)[cite: 8, 9]. [cite_start]Ele permite converter imagens 360° captadas por drones em arquivos HTML autocontidos, onde a imagem é embutida via Base64, garantindo que o registro possa ser visualizado em qualquer navegador sem dependência de internet ou softwares externos[cite: 9, 10].

---

## ⚖️ Nota de Autoria e Modificação
**Este projeto é uma versão modificada e aprimorada a partir do código original.**

* [cite_start]**Autor e Idealizador Original:** Gilberto Milhomem Marinho Filho[cite: 36, 82].
* **Modificações e Evolução de Interface (2026):** Kuriakin Toscan.
* [cite_start]**Instituição:** IBAMA — Instituto Brasileiro do Meio Ambiente e dos Recursos Naturais Renováveis[cite: 3, 82].
* [cite_start]**Unidade de Origem:** DIPAM-TO — Divisão de Proteção Ambiental do Tocantins[cite: 3, 82].

---

## 🎯 Objetivo
[cite_start]Democratizar a visualização de imagens 360° dentro do ambiente SEI, transformando registros aéreos imersivos em evidências documentais acessíveis a qualquer servidor público com acesso ao processo[cite: 11].

## 🛠️ Características Técnicas
* [cite_start]**Arquitetura Zero Dependências:** O visualizador gerado é autossuficiente e funciona em máquinas offline[cite: 13, 17].
* [cite_start]**Motor de Renderização:** Utiliza a biblioteca **Three.js (r128)** para projeção esférica via WebGL[cite: 18, 20].
* [cite_start]**Alta Fidelidade:** Esfera configurada com 96×64 segmentos para minimizar distorções nos polos da imagem[cite: 26].
* [cite_start]**Navegação Suave:** Implementação de interpolação de movimento (lerp) para evitar saltos bruscos no arraste[cite: 28].

## 🚀 Como Utilizar

### 1. Gerar o Visualizador
1.  [cite_start]Abra o arquivo `360_Gerador.html` no Google Chrome ou Microsoft Edge[cite: 41, 52].
2.  [cite_start]Arraste a sua imagem 360° (proporção 2:1) para a área indicada[cite: 43, 52].
3.  [cite_start]Confira os metadados e o nome de saída[cite: 52].
4.  [cite_start]Clique em **"Gerar Visualizador 360°"** e baixe o arquivo HTML final[cite: 52].

### 2. Anexar no SEI
1.  [cite_start]No processo desejado, selecione **"Incluir Documento"** e escolha a opção **"Externo"**[cite: 64].
2.  [cite_start]No campo "Formato", selecione obrigatoriamente **"Nato-digital"**[cite: 64].
3.  [cite_start]Faça o upload do arquivo HTML gerado[cite: 64].
4.  [cite_start]Ao clicar no documento na árvore do processo, o SEI abrirá o visualizador interativo diretamente no navegador[cite: 64, 65].

## ⚠️ Solução de Problemas
* [cite_start]**Imagem Distorcida:** Verifique se a foto original foi captada no modo "Esférico/Panorâmico" do drone (proporção 2:1)[cite: 73].
* **Arquivo Muito Grande para o SEI:** O limite prático de upload costuma ser de 5 a 8 MB. [cite_start]Se necessário, redimensione a imagem original para 4096×2048 px antes de processar no gerador[cite: 70, 71].
* [cite_start]**Tela Preta no Visualizador:** Pode indicar que a biblioteca Three.js não foi carregada devido a bloqueios de rede no domínio da CDN[cite: 73].

## 📜 Licença
[cite_start]Este projeto é distribuído sob a **Licença MIT**[cite: 37, 75].

---
[cite_start]*Tocantins — Co Yvy Ore Retama — Esta Terra É Nossa* [cite: 35, 83]*

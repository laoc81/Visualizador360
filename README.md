# Visualizador 360º 

[cite_start]Ferramenta desenvolvida para converter registros fotográficos 360° (equirretangulares) captados por drones em arquivos HTML interativos e autocontidos, permitindo a anexação como documentos externos no **Sistema Eletrônico de Informações (SEI)** sem dependência de internet ou softwares adicionais[cite: 9, 10].

---

## ⚖️ Autoria e Licença

Este projeto é uma evolução visual e funcional baseada no trabalho original do **TO-360**.

* [cite_start]**Idealizador e Autor Original:** Gilberto Milhomem Marinho Filho (IBAMA/DIPAM-TO, 2025)[cite: 82].
* **Modificações e UI Design (2026):** Kuriakin Toscan.
* [cite_start]**Licença:** MIT License (Permissiva para uso institucional)[cite: 75, 76].

---

## 🚀 Como Funciona?

O **Visualizador360** resolve a limitação do SEI em visualizar arquivos esféricos. [cite_start]Ele embuti a imagem em formato **Base64** dentro de um único arquivo HTML autossuficiente[cite: 9, 23].

### Passo a Passo:
1.  [cite_start]Abra o arquivo `360_Gerador.html` no seu navegador (Chrome ou Edge)[cite: 52].
2.  Arraste a sua foto 360° para a área de upload.
3.  [cite_start]Confirme se a proporção da imagem é **2:1** (ideal para evitar distorções)[cite: 43].
4.  Clique em **Gerar Visualizador** e baixe o arquivo `.html` resultante.
5.  [cite_start]No **SEI**, inclua este novo arquivo como **Documento Externo**, formato **Nato-digital**[cite: 64].

## 🛠️ Especificações Técnicas
* [cite_start]**Renderização:** Biblioteca Three.js (r128) via WebGL[cite: 20].
* [cite_start]**Compatibilidade:** Navegadores modernos com suporte a GPU acelerada[cite: 46].
* **Interface:** Design responsivo utilizando fontes Inter e Phosphor Icons.

---
[cite_start]*Tocantins — Co Yvy Ore Retama — Esta Terra É Nossa* [cite: 83]

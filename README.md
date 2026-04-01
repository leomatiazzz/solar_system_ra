# 🪐 Sistema Solar em Realidade Aumentada – WebAR

Aplicação educativa de **Realidade Aumentada via navegador (WebAR)** que projeta o Sistema Solar sobre o marcador Hiro e permite explorar informações sobre cada astro por toque ou clique.

> **Projeto Final – Desenvolvimento para RA** · Setor de aplicação: Educação

---

## ✨ Funcionalidades

- Renderização do Sistema Solar 3D sobre o marcador Hiro em tempo real
- Toque/clique em qualquer astro para exibir um painel informativo (Sol, Mercúrio, Vênus, Terra, Lua, Marte, Júpiter, Saturno, Urano, Netuno e Plutão)
- Modo de **órbitas físicas** com velocidades angulares proporcionais aos períodos reais dos planetas
- Controle de **pausa / retomar** da animação
- Controle de **velocidade orbital** (0,25× até 10×)
- Animação de **rotação axial** individualizada por planeta (incluindo rotação retrógrada de Vênus e Urano)
- Lua orbitando a Terra com período proporcional ao real (~27,3 dias)
- Atmosfera da Terra com rotação levemente diferenciada

---

## 🚀 Como usar

1. Imprima ou exiba o **marcador Hiro** em uma tela secundária:  
   [https://raw.githack.com/AR-js-org/AR.js/master/data/images/HIRO.jpg](https://raw.githack.com/AR-js-org/AR.js/master/data/images/HIRO.jpg)
2. Abra o arquivo `index.html` (ou o link hospedado) em um dispositivo com câmera.
3. Conceda permissão de acesso à câmera quando solicitado.
4. Clique em **"Iniciar Experiência"** na tela de boas-vindas.
5. Aponte a câmera para o marcador Hiro — o Sistema Solar aparecerá sobre ele.
6. **Toque em qualquer planeta** para exibir informações sobre ele.
7. Use os botões no canto superior direito para:
   - **🔄 Iniciar Órbitas** — ativa animação orbital física
   - **⏸ Pausar / ▶ Retomar** — pausa ou retoma a animação
   - **− / +** — reduz ou aumenta a velocidade orbital

> **Requisito:** o arquivo `high_resolution_solar_system.glb` deve estar na mesma pasta que `index.html`.

---

## 🗂️ Estrutura do projeto

```
solar_system_ra/
├── index.html                       # Aplicação principal (WebAR)
├── high_resolution_solar_system.glb # Modelo 3D do Sistema Solar
├── README.md
└── LEIA-ME.txt
```

---

## 🛠️ Tecnologias utilizadas

| Biblioteca | Versão | Finalidade |
|---|---|---|
| [A-Frame](https://aframe.io) | 1.3.0 | Framework de WebXR/WebVR |
| [AR.js](https://ar-js-org.github.io/AR.js-Docs/) | latest | Rastreamento de marcador via webcam |
| [aframe-extras](https://github.com/donmccurdy/aframe-extras) | 6.1.1 | Suporte a `animation-mixer` para modelos GLB |

---

## 🎨 Créditos do modelo 3D

| Campo | Informação |
|---|---|
| Modelo | High Resolution Solar System |
| Autor | Pedro B. Goulart (Pebegou) |
| Página | [Sketchfab](https://sketchfab.com/3d-models/high-resolution-solar-system-59fcc3e1dc634ef192215a7e485f147e) |
| Licença | [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) |

---

## 📄 Licença

O código-fonte desta aplicação é disponibilizado para fins educacionais.  
O modelo 3D está sujeito à licença **CC BY 4.0** — atribuição obrigatória ao autor original.

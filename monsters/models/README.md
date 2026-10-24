# Modelos 3D de Monstros (.dae / .glb / .gltf)

Esta pasta é dedicada a armazenar os modelos 3D dos monstros de Yu-Gi-Oh! extraídos diretamente de jogos como *Yu-Gi-Oh! The Duelists of the Roses (PS2)*, para projeção na Arena 3D e inspeção 360°.

---

### 🚀 Suporte Nativo a COLLADA (.dae) e GLTF (.glb)

O jogo possui carregador nativo para **arquivos `.dae` (COLLADA)** e **`.glb` / `.gltf`** via Three.js (`ColladaLoader` e `GLTFLoader`), **sem necessidade de converter para `.glb` no Blender**!

Quando você baixa um monstro do **The Models Resource**:
1. O arquivo `.zip` vem com o modelo `NomeDoMonstro.dae` e as texturas em `.png` acompanhadas.
2. Basta extrair a pasta aqui dentro de `public/monsters/models/<id>/` (por exemplo: `public/monsters/models/bsd/`).
3. Registre no catálogo `MONSTER_3D_CATALOG` em `src/components/monster3dLoader.js`.

---

### 📂 Exemplo Já Integrado: Dragão Caveira Negra (Black Skull Dragon)
- **Pasta:** `public/monsters/models/bsd/`
- **Arquivo 3D:** `B. Skull Dragon.dae`
- **Texturas:** `46e727e3427873af-XA128.png`, `56400109b982b700-XA128.png`, etc.
- **Visualizador 360°:** Disponível no inspetor de cartas clicando no botão **🐉 Ver Modelo 3D PS2 (360°)**.
- **Arena 3D:** Quando invocado no campo com "Monstros em Campo (3D)" ativado, o Dragão Caveira Negra autêntico do PS2 surge em cima da carta com iluminação e sombras em tempo real.

---

### ⚙️ Como Ativar no Jogo:
Nas **Configurações do Jogo** (no Menu Inicial):
* Alterne a opção **"Monstros em Campo (3D)"** para **LIGADO**.
* Se o modelo 3D existir para a carta, o jogo carrega o modelo 3D real autêntico!


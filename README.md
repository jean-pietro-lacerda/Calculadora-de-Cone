# Calculadora-de-Cone
# 📐 Calculadora de Cone em 3D (ASCII)

Uma calculadora matemática interativa que não apenas descobre os valores ausentes de um cone (Volume, Área, Geratriz, etc.), mas também renderiza uma versão 3D animada da figura usando arte em caracteres ASCII.

## ✨ Funcionalidades

* **Cálculos Dinâmicos:** Insira os valores que você possui (ex: Raio e Altura) e o algoritmo calcula automaticamente o restante: Diâmetro, Geratriz, Área da Base, Área Lateral, Área Total e Volume.
* **Validação Geométrica:** O script faz a checagem das propriedades do cone (aplicando o Teorema de Pitágoras) para garantir que as proporções da geratriz, raio e altura sejam fisicamente possíveis.
* **Renderização 3D em ASCII:** Criação de uma cena 3D diretamente no navegador, estilizada com o efeito `AsciiEffect`, dando um visual retrô estilo terminal.
* **Câmera Interativa:** Integração com `TrackballControls` para que o usuário possa girar, afastar e aproximar o modelo 3D usando o mouse.

## 🚀 Tecnologias Utilizadas

* **HTML5 / CSS3:** Estrutura base da página e estilização da interface de informações.
* **JavaScript (Vanilla):** Lógica matemática de geometria espacial e manipulação do DOM.
* **[Three.js](https://threejs.org/):** Biblioteca principal para a criação do ambiente 3D (Cena, Câmera, Luzes e a malha do Cone).
* **Módulos do Three.js:** `AsciiEffect.js` para o visual de texto e `TrackballControls.js` para a interatividade.

## 🛠️ Como rodar o projeto localmente

Como o código faz a importação de módulos ES diretamente da web usando o *Import Map* (`<script type="importmap">`), abrir o arquivo `index.html` dando dois cliques direto da sua pasta pode gerar bloqueios de segurança do navegador (CORS). 

Para rodar perfeitamente:

1. Faça o clone deste repositório ou baixe o arquivo `index.html`.
2. Abra a pasta no seu editor de código preferido (como o VS Code).
3. Inicie um servidor local. Se estiver no VS Code, recomendo usar a extensão **Live Server**.
4. O projeto abrirá no seu navegador.

## 🎮 Como usar

1. Ao carregar a página, caixas de diálogo (*prompts*) pedirão os parâmetros do cone.
2. Digite os valores numéricos que você conhece. **Para os valores que não souber, digite `0`.**
3. É preciso fornecer no mínimo dois valores base (ex: Raio + Altura ou Raio + Geratriz) para que a figura seja montada.
4. Os resultados matemáticos precisos aparecerão no canto superior esquerdo da tela.
5. Clique e arraste o mouse pela tela para explorar o cone em 3D!



Feito em colaboração para trabalho escolar no Instituto Federal de Vitoria de Santo Antão/

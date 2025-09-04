# BB-8 Webots Controller

Este projeto implementa um controlador para o robô **BB-8** no simulador [Webots](https://cyberbotics.com/).  
O controlador permite alternar entre **modo manual** (usando o teclado) e **modo piloto automático**, simulando movimentos autônomos do robô.

---

## 🚀 Como executar

### Pré-requisitos
- [Webots R2023a ou superior](https://cyberbotics.com/)
- Compilador C (GCC/Clang) configurado no ambiente
- (Opcional) Python 3.10+ caso queira adaptar o projeto para Python

### Clonando o repositório
```bash
git clone https://github.com/vitor-souza-ime/bb8.git
cd bb8
````

### Executando no Webots

1. Abra o **Webots**.
2. Carregue o mundo do projeto (`.wbt`) correspondente ao robô BB-8.
3. Defina o controlador do robô para `main` (o arquivo principal do projeto é `main.c`, mas pode ser adaptado para `main.py`).
4. Execute a simulação.

---

## 🎮 Controles

No **modo manual**, os seguintes comandos podem ser usados no teclado:

* **↑ / ↓**: move o BB-8 para frente/trás
* **← / →**: gira o BB-8 para esquerda/direita
* **Espaço**: para o movimento
* **A**: alterna entre **piloto automático** e **manual**

No **modo piloto automático**, o robô anda para frente e gira suavemente em um padrão oscilatório.

---

## 📂 Estrutura do projeto

```
bb8/
│── main.c        # Código principal do controlador (atualmente em C)
│── main.py       # Versão Python (placeholder/adaptação futura)
│── README.md     # Este arquivo
│── worlds/       # Arquivos do mundo Webots
│── protos/       # Definições do robô
```

---

## 📖 Referências

* [Documentação oficial do Webots](https://cyberbotics.com/doc/guide/index)
* [API do Webots C](https://cyberbotics.com/doc/reference/c-api)

---

## 📜 Licença

Este projeto segue a licença [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

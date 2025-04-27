# 📝 Formulário com Modo Dark e Light

Este projeto é um **Formulário de Contato** simples que permite alternar entre os modos **Claro (Light)** e **Escuro (Dark)**.  
Foi desenvolvido utilizando **HTML**, **CSS** e **JavaScript** puro, sem bibliotecas externas.

---

## 🚀 Funcionalidades

- Formulário com campos básicos:
    - Nome
    - E-mail
    - Password
- Botão para alternar entre o modo **Light** e **Dark**.
- Estilo visual adaptado para cada tema.
- Responsividade: compatível com telas de diferentes tamanhos.
- Alteração dinâmica do tema sem recarregar a página.

---

## 📁 Estrutura de Arquivos

```
formulario-dark-light/ 
├── index.html # Estrutura do formulário 
├── style.css # Estilos para os modos Light e Dark 
└── script.js # Lógica para alternar os temas
```

---

## 🛠️ Tecnologias Utilizadas

- HTML5 – Estrutura dos elementos do formulário.
- CSS3 – Estilização para os modos claro e escuro.
- JavaScript – Controle da mudança dinâmica de tema.

---

## 🎨 Como funciona o modo Dark/Light

- Existe um botão para alternar entre os temas.
- O JavaScript adiciona ou remove uma classe (dark-mode) no elemento body.
- O CSS aplica estilos diferentes dependendo da presença dessa classe.
    - Exemplo de controle no JavaScript:

```
const mode = document.getElementById('mode_icon');

mode.addEventListener('click', () => {
    const form = document.getElementById('login_form');
    if(mode.classList.contains('fa-moon')) {
        mode.classList.remove('fa-moon');
        mode.classList.add('fa-sun');
        form.classList.add('dark');
        return;
    }

    mode.classList.add('fa-moon');
    mode.classList.remove('fa-sun');
    form.classList.remove('dark');
});
```

---

## 🎨 Paleta de Cores Utilizada

### 🌞 Modo Light
| Elemento              | Cor            | Código Hexadecimal              |
|-----------------------|----------------|---------------------------------|
| Fundo Principal       | Roxos          | `#7c3aed, #a855f7, #bf47eb` |
| Texto Principal       | cinza          | `#797984`                       |
| Icones                | Preto          | `#000`                          |
| Light                 | Branca         | `#f8fafc`                       |

### 🌙 Modo Dark
| Elemento              | Cor              | Código Hexadecimal |
|-----------------------|------------------|--------------------------------|
| Fundo Principal       | Roxos            | `#7c3aed, #a855f7, #bf47eb`|
| Texto Principal       | Cinza            | `#797984`                      |
| Icones                | Branco           | `#f8fafc`                      |
| Dark                  | Preto            | `#000`                         |

> Essas cores garantem contraste e boa legibilidade em ambos os modos.

---

## 📸 Captura de Tela

- Modo Light:
![alt text](assets/img/image.png)

- Modo Dark:
![alt text](assets/img/image-1.png)

---

## 📸 Prévia do projeto

(https://neginterprises.github.io/Formul-rio-com-modo-dark-e-light/)

---

## 👨‍💻 Autores

- Natiele Nogueira de Paula
- Gabriel Vanço Gandolfi
# 👋 Olá! Eu sou o LucianoDev

[![GitHub followers](https://img.shields.io/github/followers/lucianopsilvadev?label=Seguidores&style=social)](https://github.com/lucianopsilvadev)

Sou um desenvolvedor front-end apaixonado por criar interfaces web modernas, responsivas e funcionais. Estou em constante evolução, mergulhando fundo no JavaScript moderno.

---

## 🚀 Tecnologias que domino

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" height="50" title="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" height="50" title="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" height="50" title="JavaScript"/>
</div>

---

## 📚 O que estou estudando agora

Atualmente estou **aprofundando meus conhecimentos em JavaScript**:

| Conceito | O que significa | O que estou praticando |
|----------|----------------|------------------------|
| **ES6+** | JavaScript moderno | Arrow functions, template literals, destructuring, spread/rest, modules |
| **Promises** | Operações assíncronas | fetch API, Promise.all, encadeamento de promises |
| **Async/Await** | Código assíncrono limpo | try/catch, fluxos assíncronos, tratamento de erros |

### 📝 Exemplo do que estou codificando

```javascript
// Buscando dados de uma API com async/await
async function buscarUsuarios() {
  try {
    const resposta = await fetch('https://api.exemplo.com/usuarios');
    const dados = await resposta.json();
    console.log('✅ Usuários carregados:', dados);
  } catch (erro) {
    console.error('❌ Erro na requisição:', erro);
  }
}

# ✅ To-Do Vue 3

![Vue.js](https://img.shields.io/badge/Vue.js_3-4FC08D?logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

Lista de tarefas refatorada de **JavaScript puro para Vue 3**, usando reatividade no lugar de manipulação manual do DOM.

🔗 **Demo online:** https://rafaelwilliam2808.github.io/todo-vue3/

## ✨ Funcionalidades

- Adicionar tarefas pelo botão ou pela tecla **Enter**
- Marcar e desmarcar tarefas como concluídas com um clique
- Remover tarefas
- Ignorar entradas vazias

## 🧠 O que este projeto demonstra

| Conceito | Onde aparece |
|---|---|
| Composition API (`setup`, `ref`) | Estado reativo da lista e do campo de texto |
| `v-model` | Ligação bidirecional do campo de nova tarefa |
| `v-for` com `:key` | Renderização da lista |
| `:class` dinâmico | Estilo de tarefa concluída |
| `@click`, `@keyup.enter`, `.stop` | Eventos e modificadores |

O ponto principal da refatoração: nenhum `getElementById`, `createElement` ou `appendChild`. A interface é derivada do estado.

## 🚀 Como rodar

Não precisa instalar nada. O Vue 3 é carregado via CDN.

```bash
git clone https://github.com/RafaelWilliam2808/todo-vue3.git
cd todo-vue3
```

Depois, abra o `index.html` no navegador.

## 🗺️ Próximos passos

- [ ] Salvar as tarefas no `localStorage`
- [ ] Filtros: todas, pendentes e concluídas
- [ ] Migrar para Vite com Single File Components (`.vue`)

## 👤 Autor

**Rafael William**, estudante de Engenharia de Software no CEUB · [LinkedIn](https://www.linkedin.com/in/rafael-william-5190b33a8/)

Projeto desenvolvido na disciplina de Desenvolvimento Web.

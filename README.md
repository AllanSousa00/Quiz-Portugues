# Quiz Português

Projeto web de um quiz sobre Língua Portuguesa, com visual inspirado nas telas desenhadas em PNG e funcionamento completo em navegador.

O app foi organizado para manter separado o que é código do que é material de referência.

## Recursos

- tela inicial, configurações, quiz e resultado final
- tema claro e escuro com troca em tempo real
- música de fundo com ligar/desligar e efeitos leves de acerto e erro
- progresso salvo localmente para continuar de onde parou
- embaralhamento de perguntas e alternativas
- revisão final com erros para estudar depois
- placar de desempenho no fim da partida
- modo professor para cadastrar novas perguntas sem mexer no código
- importação e exportação de banco de perguntas em JSON
- layout adaptado para computador, celular e tela cheia

## Estrutura

```text
Quiz Português/
├── Aplicativo/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── Referências/
│   ├── Design Claro/
│   ├── Design Escuro/
│   └── PDF/
└── README.md
```

## Como abrir

1. Entre na pasta `Aplicativo`.
2. Abra o arquivo `index.html` no navegador.

Não é necessário instalar dependências nem rodar servidor para usar a versão atual.

## Como personalizar

### Pelo próprio app

Use o botão `Modo Professor` na tela de configurações para:

- adicionar perguntas novas
- definir alternativas e resposta correta
- escrever uma explicação para o aluno
- exportar ou importar perguntas em JSON

### Pelo código

As perguntas iniciais ficam em `Aplicativo/script.js`, no bloco `DEFAULT_QUESTIONS`.

## Tecnologias

- HTML5
- CSS3
- JavaScript puro
- `localStorage` para persistência
- Web Audio API para música e efeitos sonoros

## Materiais de referência

As imagens usadas como base visual estão em `Referências/Design Claro` e `Referências/Design Escuro`.

O PDF com a base das perguntas está em `Referências/PDF`.

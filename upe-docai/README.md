# UPE DocAI — Automação de Documentos Administrativos

Projeto acadêmico desenvolvido para a **Atividade Prática AV1** da disciplina de desenvolvimento Front-End.

## Problema escolhido

**DesafioPE:** Como podemos automatizar a geração de documentos administrativos com inteligência artificial privada e integrá-los ao SEI da UPE?

Referência fornecida na atividade: https://share.google/WED8CX3ilSXwzc3VR

## Solução proposta

O **UPE DocAI** é um protótipo Web em React que auxilia na criação, revisão, organização e exportação de documentos administrativos, reduzindo o trabalho repetitivo. Oferece modelos de ofício, memorando, declaração e requerimento, com preenchimento guiado e geração automática de rascunhos.

**Limitações importantes:** nesta versão de AV1, a geração é baseada em modelos locais e **não utiliza um modelo de inteligência artificial real**. Os documentos ficam armazenados no `localStorage` do navegador, sem criptografia e sem sincronização entre dispositivos. A página de integração SEI é **demonstrativa**: não há acesso, envio ou autenticação real com o SEI da UPE. 

## Funcionalidades

- Dashboard com indicadores e acesso rápido aos modelos.
- Formulário de geração de documentos com campos validados.
- Editor de texto para revisar e ajustar os rascunhos.
- Exportação dos documentos para PDF.
- Histórico local, pesquisa, edição e exclusão.
- Página explicativa do fluxo de integração futura com SEI.
- Interface responsiva para desktop e celular.

## Tecnologias

React, JavaScript, HTML, CSS, Vite, lucide-react e jsPDF. O projeto utiliza componentes, props, `useState`, eventos e `localStorage`.

## Como executar

Requisitos: **Node.js 18 ou superior** e npm.

```bash
npm install
npm run dev
```

Abra a URL exibida no terminal (normalmente `http://localhost:5173`).

Para gerar a versão de produção:

```bash
npm run build
npm run preview
```

## Estrutura do projeto

```text
upe-docai/
├── index.html
├── package.json
├── vite.config.js
├── .gitignore
├── README.md
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── styles.css
    └── components/
        └── Sidebar.jsx
```

## Integrantes

| Nome | Matrícula |
|---|---|
| Douglas Weslley de Oliveira Silva | 01820366 |
| Matheus Rocha Sinfronio | 01809730 |
| João Victor Lopes de Araújo | 01819184 |
| Marcos André de Farias Soares Filho | 01809049 |
| João Tomaz da Silva Neto | 01792879 |
| Kauã Araújo Xávier |   01701661  | 





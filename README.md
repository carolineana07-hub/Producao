# 🦷 Controle de Produção Odontológica

App web simples para controlar produção odontológica: atendimentos com comissão, prontuário protético por etapas, materiais/EPIs em falta e observações de pacientes. Exporta o mês em CSV ou Excel (.xlsx).

- HTML, CSS e JavaScript puros, em um único arquivo (`index.html`).
- Os dados ficam salvos **só no navegador do aparelho** (localStorage). Nada é enviado para servidor.
- Use "Config → Baixar backup" de vez em quando.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `producao-odontologica`).
2. Envie os arquivos `index.html` e `README.md` (botão **Add file → Upload files**).
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**. Salve.
5. Após 1 a 2 minutos, o site fica em `https://SEU-USUARIO.github.io/producao-odontologica/`.

## Usar no celular

Abra o link no navegador e use **Compartilhar → Adicionar à Tela de Início** (iPhone) ou **Menu → Instalar app / Adicionar à tela inicial** (Android).

## Observações

- Os dados são por navegador e por aparelho: não passam sozinhos do celular para o computador.
- Apagar os dados do navegador apaga os registros. Faça backup.
- O arquivo Excel (.xlsx) carrega a biblioteca SheetJS da internet. Sem internet, use o CSV, que abre no Excel.
- Não coloque dados de pacientes dentro do repositório. O site público é só o app vazio.

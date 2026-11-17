# Prova T2 — montar o Code-OSS no GitHub Actions (macOS)

Mede quanto tempo leva montar o editor Code-OSS (o VS Code de código aberto, licença MIT) numa máquina macOS padrão
do GitHub Actions. Só compila o código público do repositório `microsoft/vscode`; não há nada privado aqui.

- Workflow: [`.github/workflows/build-code-oss-macos.yml`](.github/workflows/build-code-oss-macos.yml)
- Rodar: aba **Actions** → "T2 - montar Code-OSS (macOS arm64)" → **Run workflow** (ou `gh workflow run`).
- Resultado: o app montado fica para download por 7 dias (artefato da execução).

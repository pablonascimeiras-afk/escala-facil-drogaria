# Escala Fácil — Drogaria

Aplicativo web instalável (PWA) para administrador, baseado na planilha `escala_drogaria_42h_final.xlsx`.

## Recursos
- Escala semanal importada da planilha original (20 colaboradores/linhas válidas).
- Visão semanal e calendário mensal que repete a escala padrão.
- Cadastro e edição de funcionários e turnos.
- Registro diário de entrada, intervalo e saída.
- Exportação CSV para abrir no Excel/Google Planilhas.
- Exportação/importação de backup JSON.
- Impressão ou “Salvar como PDF” pelo navegador.
- Armazenamento local e cache offline após primeira abertura HTTPS.

## Publicar gratuitamente no GitHub Pages
1. Extraia o ZIP no celular ou computador.
2. Envie `index.html`, `manifest.webmanifest` e `sw.js` para a raiz do repositório GitHub.
3. No GitHub, abra Settings → Pages.
4. Em Build and deployment, escolha Deploy from a branch, branch `main`, pasta `/(root)`, e salve.
5. Quando o endereço estiver disponível, abra `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/` no Chrome do Moto G54.
6. Menu ⋮ do Chrome → “Instalar app” ou “Adicionar à tela inicial”.

## Limitações importantes
- Acesso somente administrativo significa, nesta versão, que os dados ficam no navegador do dispositivo. Não há login real; não publique informações confidenciais em dispositivo compartilhado.
- Dados não sincronizam entre celulares. Faça backups regulares.
- O total de jornada exibido no ponto é estimado. Confira as regras legais, convenção coletiva e validação profissional antes de usar como controle oficial.
- Domingo está marcado como FECHADO conforme a planilha de origem. O calendário mensal replica a escala semanal e não contém um editor de exceções por data.

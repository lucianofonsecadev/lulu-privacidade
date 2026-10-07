# lulu-privacidade
Política de privacidade e informações sobre exclusão de dados do aplicativo Lulu Finanças.

A página pública está em `index.html`, com versão de **7 de outubro de 2026**. Usa apenas HTML/CSS e fontes do sistema, sem scripts, cookies próprios, analytics, formulários ou dependências.

`termos.html` contém a **minuta para revisão dos Termos de Uso**, também de 7 de outubro de 2026, com o mesmo estilo e links entre as duas páginas. O documento precisa de revisão e aprovação antes de adoção. O fluxo de aceite foi preparado no código, mas permanece desativado, sem versão aprovada para adoção; abrir a página ou continuar usando o app não é apresentado como aceite desta minuta.

## Visualizar localmente

Abra `index.html` ou `termos.html` no navegador. Para testar por HTTP, na raiz do repositório execute:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Acesse `http://127.0.0.1:8000` e encerre o servidor com `Ctrl+C`. Confira também em tela de 320–390 pixels, com zoom e navegação por teclado. Não é necessário compilar nem instalar pacotes.

## Revisar antes da publicação

A página incorpora as informações confirmadas pelo responsável: Hostinger para a caixa de contato e envio de autenticação via SMTP do Supabase; Supabase para autenticação e banco de dados no plano Free; dados mantidos enquanto a conta existir, sem exclusão automática por inatividade; pedidos de exclusão por e-mail acompanhados pelo próprio responsável, com verificação de titularidade. Senhas, códigos de autenticação e dados financeiros completos não são solicitados por e-mail. Arquivos exportados e conversas no WhatsApp não são apagados pela exclusão no serviço. WhatsApp e IA permanecem em preparação.

O banco principal está em us-west-2 (Oregon, Estados Unidos), sem comprovação da localização de todos os demais serviços, logs ou suboperadores. O painel informa que o plano Free não inclui backups de projeto, e Luciano não realiza backups manuais do banco; isso não comprova ausência de cópias internas do provedor ou logs. O aplicativo permite exportar backup JSON para o destino escolhido pelo usuário. Pelo lado do Lulu, somente Luciano possui acesso administrativo ao Supabase e à caixa de e-mail, sem excluir eventual acesso autorizado pelos provedores. O serviço é destinado a maiores de 18 anos; não foi confirmada verificação de idade.

Luciano precisa cumprir o compromisso de apagar e-mails de suporte comum em até 90 dias após encerrar o atendimento, incluindo a lixeira. Esse prazo não abrange pedidos de privacidade/exclusão nem logs ou cópias internas dos provedores. A redação não afirma que essa limpeza seja automática ou já implementada no aplicativo.

O e-mail será usado para autenticação, recuperação de acesso, suporte, privacidade e avisos necessários de segurança, funcionamento ou atualização do serviço, sem promoções ou ofertas. No Supabase principal, “Write audit logs to the database” está desativado; isso não comprova ausência de logs do provedor.

Os relatórios da Hostinger mostram acesso (horário, caixa, IP, status e protocolo) e entrega (horário, remetente, destinatário e status). Segundo resposta do suporte da Hostinger de 07/10/2026 fornecida pelo responsável, esses registros aparecem no painel por 30 dias e são retidos por 180 dias; o conteúdo da caixa e seus backups são armazenados no EEE. Essas respostas não foram verificadas independentemente em documentação pública. Os 180 dias não são prazo de retenção das mensagens nem substituem a limpeza do suporte comum em até 90 dias após encerrar o atendimento.

Para finalizar a política, ainda faltam: bases legais por finalidade; retenção dos pedidos de privacidade/exclusão e mensagens de autenticação e avisos necessários; categorias e retenção de logs e cópias internas do Supabase; localização dos registros de acesso/entrega e permanência das mensagens excluídas nos backups da Hostinger; demais locais de processamento e mecanismos de transferência internacional; detalhes da verificação de titularidade e da conclusão da remoção. Leia `REVISAO-PRIVACIDADE.md`, que separa informações confirmadas, compromissos operacionais, pendências atuais e pendências para ativação futura do WhatsApp/IA.

Esse arquivo não aparece na navegação da página, mas estará visível no repositório se ele for público e pode ser servido pela hospedagem. Não inclua dados pessoais de usuários, credenciais ou informações privadas nele.

Para adotar os termos, ainda é necessário revisar a redação jurídica e definir apresentação/aceite, registro da versão, comunicação de alterações, atendimento a falhas e procedimento proporcional para lidar com abuso. Essas decisões constam da revisão e não foram transformadas em funcionalidades existentes. Não foram criadas regras comerciais sobre cobranças, assinaturas ou reembolsos.

## Publicar posteriormente no GitHub Pages

Nenhuma publicação é feita por estas instruções automaticamente.

1. Após a revisão, envie os arquivos aprovados à branch que deseja publicar, por seu fluxo habitual de Git.
2. No GitHub, abra **Settings → Pages** do repositório.
3. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
4. Selecione a branch com `index.html` (por exemplo, `main`) e a pasta **/ (root)**. Salve.
5. Aguarde a implantação do Pages e abra o endereço informado nessa tela. Para um site de projeto, o formato usual é `https://<usuario>.github.io/<repositorio>/`.
6. Confira as duas páginas publicadas, links entre elas e de seções, endereço de e-mail e apresentação no celular. A disponibilidade do Pages depende das condições do repositório e da conta. Mantenha a identificação de minuta nos termos enquanto não houver aprovação para sua adoção.

Os links internos usam âncoras e funcionam sob o caminho do repositório. Não é necessário configurar domínio personalizado, workflow ou dependências para esta página.

Documentação oficial: [publicação por branch no GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

# EVDash — releases

Distribuição pública do EVDash para Android/BYD. Este repositório contém somente notas e arquivos de instalação publicados nas Releases. O código-fonte do aplicativo permanece privado.

[Baixar a versão mais recente](https://github.com/rrrabadan/evdash-releases/releases/latest)

A primeira versão com atualizador é a **0.1.15-alpha**. Quem usa uma versão anterior precisa instalar esse APK uma vez; depois, o botão **Atualizar versão** do app consulta as novas releases públicas.

O app consulta `https://github.com/rrrabadan/evdash-releases/releases/latest/download/latest.json`, confere o tamanho e o SHA-256 e exige a mesma assinatura Android da versão instalada. A instalação automática requer a autorização ADB local do EVDash e veículo parado em P. Após instalar, verifica o AutoStart BYD; se a verificação não puder ser concluída, orienta a conferir EVDash DESL na tela “Desativar AutoStart”.

As versões alpha são distribuídas explicitamente pelo canal latest. A publicação dos binários não representa validação de funcionamento em movimento no veículo.

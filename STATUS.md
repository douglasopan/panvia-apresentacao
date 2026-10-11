# Estado atual

Conferência: **11 de outubro de 2026**. Este documento distingue o que está disponível, o alcance das verificações e o que ainda depende de entrega ou validação.

## Disponível

O [site da Panvia](https://panvia.online/) apresenta jogos e programas, busca e filtros, páginas de produtos, logo e thumbnail independentes, galeria de fotos e vídeos e devlogs. O fluxo de propostas permite enviar projetos para revisão e consultar respostas dentro da plataforma.

O painel administrativo é restrito a administradores autenticados e oferece edição de metadados e upload de mídia. A plataforma também conta com importação de projetos, imagens e devlogs do GitHub, nos fluxos correspondentes. Essas funções não representam acesso administrativo para todos os criadores.

A [prévia Windows review.24](https://github.com/douglasopan/panvia-releases/releases/tag/v0.5.0-native-review.24) está publicada. Ela inclui o catálogo de programas e a apresentação compartilhada de mídia, seleção de versões e aquisição de pacotes qualificados. Requer Windows x64 e WebView2; é experimental e não possui assinatura digital.

O catálogo apresenta as edições [Colônia 2D](https://panvia.online/#game/thepan-art/colonia), [Colônia 2.5D](https://panvia.online/#game/thepan-art/colonia-25d) e [Colônia 3D](https://panvia.online/#game/thepan-art/colonia-3d). Os downloads foram conferidos. A 2.5D inclui servidor dedicado experimental; capacidade de 100 jogadores em produção não está certificada. O desenvolvimento da 3D está pausado.

## Alcance das verificações

Foram conferidos a publicação e a integridade dos pacotes Windows, os downloads das três edições de Colônia e a apresentação pública de mídia. As páginas da 2.5D e 3D incluem capturas reais.

Os testes de código cobriram mídia, preservação de rascunhos e sessão do painel, além do comportamento do campo de pasta após extração. O teste desse campo usou uma ponte sintética: ele não comprova o funcionamento de um novo instalador ou de uma atualização real no Windows.

A aquisição genérica de um ZIP verifica e extrai o pacote. A execução depende do fluxo aplicável ao produto; a extração, por si só, não executa um assistente nem concede uma licença. A indicação selecionável da pasta extraída está preparada no renderer e publicada no site, mas ainda precisa chegar ao aplicativo instalado por uma nova distribuição Windows.

## Pendências

- Instalação e abertura automática das novas edições Colônia 2.5D e 3D.
- Nova distribuição Windows e verificação real do caminho apresentado após extração.
- Login Google completo na web e no aplicativo Windows.
- Licenças operacionais de software e vínculos aprovados por produto.
- Notificações de propostas por e-mail.
- Validação de primeiro início, atualização e rollback em ambiente Windows limpo, preservando dados do usuário.
- Entrega e validação do candidato privado de autenticação opcional por aplicativo autenticador.

Diablo3D possui apresentação e devlog no catálogo, mas seu pacote de distribuição continua privado. A publicação depende de direitos de redistribuição, integridade e validação do fluxo real. Não há download público qualificado anunciado nesta apresentação.

Recursos sociais, mensagens, voz, sincronização de saves e instalação ou atualização universal permanecem no roadmap. A presença de um produto no catálogo não certifica esses recursos, nem a segurança ou os direitos de todos os seus ativos.

## Ritmo atual

Novas funcionalidades estão em espera. A prioridade atual é a marca, o site e os clientes da THEPAN.ART. Esta pausa preserva o trabalho existente e não estabelece data de retomada.

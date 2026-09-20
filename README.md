# Deskly — instaladores

[Deskly](https://github.com/deskly-ai/core) é um escritório de agentes de IA: você monta o time,
cada agente cuida de um cargo (Frontend, Backend, DevOps, Marketing...), e eles trabalham nos seus
projetos como colegas de verdade — pedindo ajuda uns aos outros, revisando o trabalho um do outro,
avisando quando terminam.

Este repositório guarda só os **instaladores**. O código-fonte fica em
[`deskly-ai/core`](https://github.com/deskly-ai/core), privado.

## Baixar

Pegue sempre a versão mais recente na página de **[Releases](../../releases/latest)**.

| Sistema | Arquivo |
| --- | --- |
| macOS (Apple Silicon) | `Deskly-<versão>-arm64.dmg` |
| Windows (64 bits) | `Deskly-<versão>-x64-setup.exe` |

Ainda não tem instalador para Mac Intel nem Windows 32 bits.

Os arquivos `latest-mac.yml`, `latest.yml` e os `.blockmap` não são para baixar à mão: é por eles
que o app descobre sozinho que existe versão nova e baixa só a parte que mudou.

## Licença

O Deskly é pago. Ao abrir pela primeira vez, ele pede uma **chave de licença** — sem uma, o app
não roda. Cada chave vale para um computador: a primeira ativação registra a máquina, e a mesma
chave não abre em outra. Trocou de computador? Fale com o suporte para liberar o assento.

## Atualização

Depois de instalado, o Deskly se atualiza sozinho. Ele confere a cada 6 horas; quando a versão
nova termina de baixar, aparece uma faixa no topo do app e você escolhe quando reiniciar.

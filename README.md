# Passômetro — Enfermaria / SCLS

Artefato web autocontido: abre no navegador, funciona **offline** depois de
carregado e guarda os dados **só no `localStorage` do próprio navegador**.

**Não é prontuário eletrônico. Nenhum dado sai do navegador de quem usa.**

Publicado em <https://batistazz.github.io/passometro/>.

## O que ele faz

- A grade na tela **é** o passômetro: o que você edita é o que sai no papel.
- **DIH** e **dia do antimicrobiano** se calculam sozinhos, a partir da data de
  internação e da data de início de cada droga. Nunca envelhecem.
- Antimicrobiano sem data de início aparece como **"falta data de início"** —
  o dia não é chutado.
- Medicação suspensa fica **riscada** e legível.
- Impressão em A4 paisagem, **3 pacientes por folha**, com cabeçalho e
  numeração em todas as páginas.
- **Salvar arquivo / Abrir arquivo** levam os dados de um computador a outro.

## Limites, ditos de frente

- **Um por navegador.** Duas pessoas em máquinas diferentes têm duas cópias
  separadas; não há edição simultânea. Quem precisa disso usa o sistema com
  servidor, que é outro projeto.
- Limpar os dados do navegador apaga tudo. Use **Salvar arquivo**.
- A folha impressa tem nome de paciente: descarte adequadamente.

## Privacidade

Esta página é pública e **não contém nenhum dado de paciente** — é o
aplicativo vazio. Tudo o que for digitado fica no navegador de quem digitou.

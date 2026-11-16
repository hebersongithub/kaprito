# Kaprito Online — Digitar, ligar e limpar

Aplicativo web para digitar um número de telefone e abrir o discador do celular, sem importar agenda.

**Site:** https://hebersongithub.github.io/kaprito/

## Modo rápido (sem CSV ou VCF)

1. Digite o número, de preferência com DDD, no campo **Número de telefone**.
2. Toque em **Ligar**. O site solicita ao navegador que abra o discador (`tel:`).
3. Realize a ligação no aplicativo Telefone.
4. Volte ao Kaprito e toque em **Liguei: limpar da tela**.
5. Confirme para retirar o número digitado da tela. Você pode repetir com outro.

> O navegador não informa de forma confiável se a ligação realmente aconteceu ou terminou. Por segurança, a confirmação é manual. O site **não exclui contatos reais do Android ou histórico de chamadas**.

## Modo opcional: contatos por arquivo VCF

Para trabalhar com vários contatos, use **Importar VCF**. A lista é processada localmente no próprio navegador; o site não recebe uma cópia dos contatos. Permite encontrar duplicados, ligar, retirar telefones selecionados da cópia e exportar VCF limpo.

O formato **CSV não é exigido** para ligar no modo rápido, e a importação de CSV ainda não é compatível. Importar VCF limpo no Android não substitui nem apaga automaticamente os contatos antigos.

## Privacidade e acesso

- Não publique arquivos da sua agenda no repositório GitHub. Importe-os somente pelo navegador.
- O site é público; o código-fonte não contém números particulares.
- O botão Ligar pode ser bloqueado por ambientes incorporados, inclusive dentro do ChatGPT. Abra o endereço do site no Chrome ou navegador padrão do celular.
- No computador, é necessário que exista um programa compatível com links de telefone.

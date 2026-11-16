# Kaprito Online — Ligar e Limpar

Aplicativo web para organizar cópias de contatos em **VCF**. Todo o processamento acontece **localmente no navegador**; nenhuma agenda é enviada ao GitHub.

## Abrir no navegador

Site GitHub Pages **após habilitar a publicação**: https://hebersongithub.github.io/kaprito/

Caso o link ainda não esteja disponível, vá em [Settings → Pages](https://github.com/hebersongithub/kaprito/settings/pages), escolha **Source: GitHub Actions** e salve. Confira o resultado em [Actions](https://github.com/hebersongithub/kaprito/actions).

## Funções

- **Testar exemplo** sem carregar contatos pessoais.
- **Importar VCF** exportado do app Contatos Android.
- Pesquisar por nome ou 6+ dígitos.
- Identificar números duplicados.
- **Ligar**: solicita abertura do discador via `tel:`; não funciona em todos os ambientes incorporados.
- **Liguei: limpar número**: exige confirmação e remove apenas aquele telefone da **cópia importada**.
- Desfazer limpeza; baixar backup original; exportar VCF limpo.

## Limitações

O navegador não pode comprovar o fim da ligação, editar contatos reais do Android, nem apagar chamadas ou SMS. A importação de um VCF limpo **não substitui nem apaga** automaticamente contatos já existentes no aparelho.

**Atenção:** este repositório é público e contém apenas o aplicativo. Não envie sua agenda VCF para o GitHub; importe-a somente no navegador.

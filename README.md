# Kadabra PDV · downloads

Este repositório guarda só as **versões publicadas** do Kadabra PDV: o
instalador do Windows, o pacote do Linux, o `SHA256SUMS.txt` e a assinatura
dele. Não há código-fonte aqui.

- **Baixar:** <https://kadabra-pdv.vercel.app> (ou a aba
  [Releases](https://github.com/allpines-bussines/kadabra-lp/releases)).
- **Quem já tem o app** recebe o aviso de versão nova dentro dele e atualiza
  num clique.

## Conferir um download

Cada release traz o `SHA256SUMS.txt` com o SHA-256 dos pacotes e o
`SHA256SUMS.txt.sig`, a assinatura Ed25519 desse arquivo. O app confere os
dois sozinho antes de instalar uma atualização. À mão:

```
sha256sum -c SHA256SUMS.txt
```

Uma release publicada não muda: correção sai como versão nova.

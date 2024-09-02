# Gerador de Carteira Bitcoin

Este projeto é um gerador de carteiras Bitcoin para a rede de testes (testnet). Ele utiliza BIP39 para gerar uma mnemônica e BIP32 para derivar chaves a partir dessa mnemônica. O código também gera um endereço Bitcoin e sua chave privada correspondente.

## Requisitos

Certifique-se de ter o Node.js e o npm instalados. Você pode verificar se já os possui com os seguintes comandos:

```bash
node -v
npm -v
```

```bash
git clone https://github.com/jacsonbleite/btc-wallet-node.git
cd seurepositorio
npm install
```

### excutando o projeto
```bash
node src/createWallet.js
```

Exemplo de saída no console

```
Carteira gerada
Endereço:  tb1qpl6r56tq3k2rkjyqgzj0jk9vfsm03tq0d8wfp90zd9dscq7ulccy44hlg5
Chave privada:  cPWTZks52qfGJhNq9f9Xxi4xAn8fKtbkQme31pZz2fo8m8t1iywz
Seed: apple banana cherry date egg frog grape hat iron jug kite lion

```
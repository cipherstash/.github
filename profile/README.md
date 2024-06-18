# Hey, we're CipherStash

## We protect data, not just systems.

<img align="right" src="https://github.com/cipherstash/ore.rs/assets/12306/6a797496-f59c-4942-ac98-00f47e09268a">

Increase the security, reliability and performance of your database with a single tool. Deploy the CipherStash Proxy Docker container now, and connect to your existing database.

```
docker run -p 6432:6432 \
 -e CS_DATABASE__NAME=postgres \
 -e CS_DATABASE__HOST=172.17.0.1 \
 -e CS_DATABASE__USERNAME=admin \
 -e CS_DATABASE__PASSWORD=pw \
 cipherstash/cipherstash-proxy
```

CipherStash Proxy is free to use, and you can and you can add our Audit and Encrypt modules as you need them.

## Encryption should be scrutinized

We believe that the only encryption you can trust is **encryption developed in public**.

Check out our encryption libraries:

- [ore.rs](https://github.com/cipherstash/ore.rs) – a Rust implementation of [Order Revealing Encryption](https://eprint.iacr.org/2016/612.pdf)
- [envelopers](https://github.com/cipherstash/envelopers) - a simple envelope encryption library

## Because data protection is a team sport. 

Want to learn more about CipherStash? 

* Read our [docs](https://cipherstash.com/docs), particularly the [getting started guide](https://cipherstash.com/docs/getting-started/cipherstash-proxy).
* [Read our whitepaper](https://cipherstash.com/whitepaper), to learn more abaout our technology and how it can help you.
* Check out our website at [cipherstash.com](https://cipherstash.com).

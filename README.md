# CLI tool for brute-forcing private keys with DEK headers

This is a CLI tool that tries to use multiple passphrases from a given wordlist to decrypt an encrypted private key that has a DEK header.

## Usage

```bash
Usage of ./x509bf:
 -c uint     level of concurrency, number of cores is the default (default 8)
 -k string   path to the encrypted PEM file
 -l string   path to the wordlist to try, e.g. /usr/share/wordlists/rockyou.txt
 -v          verbose logging (slower)
```

## Disclaimer

This tool is supposed to be used for research purposes only and must be NOT used for illegal actions.

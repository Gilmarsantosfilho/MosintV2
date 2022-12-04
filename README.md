# ***MosintV2***

## O que é o MOSINT

MOSINT é uma ferramenta OSINT para e-mails. Ele ajuda você a coletar informações sobre o e-mail de destino.

#### Características: :olhos:

* Validação de e-mail
* Verifique contas sociais com Socialscan e Holehe
* Verifique violações de dados e vazamentos de senha
* Encontre e-mails e domínios relacionados
* Scan Pastebin e Despejos de Throwbin
* Pesquisa do Google
* Pesquisa de DNS
* Pesquisa de IP
* Saída para arquivo de texto

# key: chave de API necessária

\[não é necessário para executar o programa\]


| Service | Function | Status |
| :--- | :--- | :--- |
| [ipapi.co](https://ipapi.co/) - Public | More Information About Domain | :white\_check\_mark: |
| [hunter.io](https://hunter.io/) - Public | Related Emails | :white\_check\_mark: :key: |
| [emailrep.io](https://emailrep.io/) - Public | Breached Sites Names | :white\_check\_mark: :key: |
| [scylla.so](https://scylla.so/) - Public | Database Leaks | :construction: |
| [breachdirectory.org](https://breachdirectory.org/) - Public | Password Leaks | :white\_check\_mark: :key: |
| [Intelligence X](https://intelx.io/)| Password Leaks | :white\_check\_mark: :key: |


## Serviços (APIs):

\[Já Vem com minhas Chave api\]

| Serviço | Função | Estado |
| :--- | :--- | :--- |
| [hunter.io](https://hunter.io/) - Público | API Key": "ff91e7e53d0ac705c99e755b398b80b9b17b75d5", | :white\_check\_mark: :key: |
| [emailrep.io](https://emailrep.io/) - Público | api embreve | :white\_check\_mark: :key: |
| [breachdirectory.org](https://breachdirectory.org/) - Público | API Key": "be2b2ce0-7289-11ed-a5d1-99f90d862581", | :white\_check\_mark: :key: |
| [Inteligência X](https://intelx.io/)| API Key": "0ccf7d4d-28bc-4dde-83b5-b02801a631d2" | :white\_check\_mark: :key: |


#### Testado em:

- [x] Termux
- [x] Linux

# Como instalar - [x] Termux

***Necessario ter a linguem "golang"***

```
pip install -U pip

apt install golang
```

**INSTALAR PYTHON SE NÃO TIVER***
```
apt install python

apt install python2

apt install python3
```

# Clonar o repositorio

```
git clone https://github.com/Gilmarsantosfilho/MosintV2
cd /MosintV2
```

```
pip3 install -r requirements.txt
```

***Modo de uso***

```
python3 mosint.py -e gilmartikinho270@gmail.com
```




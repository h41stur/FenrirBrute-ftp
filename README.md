<img src="https://raw.githubusercontent.com/leonardor666/images/main/fenrir.jpg"  height="600" />

# FenrirCrack é uma ferramenta de bruteforce de FTP

FenrirBrute-ftp é uma ferramenta para bruteforce de FTP que permite ataques com usuário e lista de senhas, lista de usuários e lista de senhas e também ataque spray, com uma senha e uma lista de usuários.

## Instalação

**Faça o download da ultima versão**
```
git clone https://github.com/suiteloki/FenrirBrute-ftp.git
```
**Mude para o diretorio do TwinCrows**
```
cd FenrirBrute-ftp
```
**Dê permissão de execussão**
```
chmod +x FenrirBrute-ftp.py
```
## Modo de uso
```
./FenrirBrute-ftp.py -a <host> -U <user list> -S <pass list>
```
**Exemplo**
```
./FenrirBrute-ftp.py -a 192.168.1.8 -U users.txt -S pass_list.txt
```

## Opções

|Opção|descrição|
|-----|---------|
| -a | Endereço do host alvo|
| -p | Porta do serviço ftp, padrão é 21|
| -u | Usuário|
| -U | Lista de usuários|
| -s | Senha única|
| -S | Lista de senhas|
| -v | Modo verbose, mostra todas as tentativas de login|
| -h | Exibe a ajuda|



![FB](https://raw.githubusercontent.com/leonardor666/images/main/fb/fb1.jpg)

![FB](https://raw.githubusercontent.com/leonardor666/images/main/fb/fb2.jpg)

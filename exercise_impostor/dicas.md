# Exercício 1 - Encontre o Impostor

Neste exercício você é um adminsitrador de redes, e se depara com alguns PC's dentro da rede que estão representando uma ameaça. Então seu papel é encontrar quais são os PC's da rede e desligar sua porta de acesso.

## **Lista de comandos**

- Comando para apresenta a tabela de MAC do roteador.

```bash
show mac address
```

- Utilize o comando abaixo para encontrar switches vizinhos conectados.

```bash
show cdp neighborhood
show cdp n
```

- Utilize o comando abaixo para desligar a porta

```bash
conf t
int FaX/X
shut
```

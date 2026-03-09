![GitHub License](https://img.shields.io/github/license/danielvdo/lab-redes01?style=flat)

# Laboratório de Redes 01 - Projeto de Rede Local
Projeto desenvolvido na disciplina de Redes de Computadores no Curso Técnico de Informática do SENAC

- Aluno: daniel vieira de oliveira
- Professor: josé de Assis
- Data: 09/03/2026

---

## 1. Objetivo
Implementar uma rede local simples conectando 3 notebooks a um roteador wireless com switch integrado e uma impressora de rede.

O projeto será realizado em duas etapas: 

1. simulação da rede no Cisco Packet Tracer
2. Implementação da rede no laboratório real

---

## 2. Equipamentos Utilizados neste Laboratório

- 3 notebooks
- 1 roteador wireless com 1 porta de WAN e 4 portas de LAN
- 1 impressora de rede
- cabos de rede

---

## 3. Topologia da Rede
Diagrama lógico da rede utilizada nesse laboratório:

```mermaid
graph TD

WAN[Internet / WAN Provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]

WAN --> |Porta WAN| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer                                                  
```

---
# Imagem da topologia utilizada no laboratório:

![](Topologia.png)

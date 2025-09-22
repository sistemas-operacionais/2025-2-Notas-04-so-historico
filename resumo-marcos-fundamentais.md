# Resumo: Marcos Fundamentais da Computação

## Sistemas Operacionais - Ciências da Computação

### Principais Paradigmas na Evolução dos Sistemas Operacionais

## 1️⃣ Era dos Sistemas Batch (1950s-1960s)
**Características:**
- Processamento em lotes (batch processing)
- Usuário submete job e aguarda resultado
- Nenhuma interação durante execução
- **Exemplo**: IBM 7094 com IBSYS

**Hardware típico:** Mainframes com cartões perfurados

---

## 2️⃣ Era dos Sistemas de Tempo Compartilhado (1960s-1970s)
**Características:**
- Múltiplos usuários simultaneamente
- Ilusão de uso exclusivo do computador
- **Time-slicing** e **scheduling**
- **Exemplo**: CTSS (MIT), Multics, UNIX

**Conceitos introduzidos:**
- Multiprogramação
- Memória virtual
- Sistema de arquivos hierárquico
- Proteção de memória

---

## 3️⃣ Era dos Computadores Pessoais (1980s-1990s)
**Características:**
- Um usuário, um computador
- Interface gráfica (GUI)
- **Exemplo**: MS-DOS, Windows, Mac OS

**Inovações:**
- Desktop metaphor
- Mouse e janelas
- Plug and Play
- Multitarefas cooperativas → preemptivas

---

## 4️⃣ Era das Redes e Internet (1990s-2000s)
**Características:**
- Sistemas conectados em rede
- Computação cliente-servidor
- **Exemplo**: Windows NT, Linux, Solaris

**Novos conceitos:**
- Network File Systems (NFS)
- Remote Procedure Calls (RPC)
- Segurança de rede
- Serviços distribuídos

---

## 5️⃣ Era Mobile e Ubíqua (2000s-2010s)
**Características:**
- Sistemas para dispositivos móveis
- Energia limitada
- **Exemplo**: iOS, Android, Windows Mobile

**Adaptações:**
- Power management
- Touch interfaces
- App stores
- Location services

---

## 6️⃣ Era Cloud e Containers (2010s-2020s)
**Características:**
- Virtualização massiva
- Microserviços
- **Exemplo**: Docker, Kubernetes, AWS Lambda

**Paradigmas:**
- Infrastructure as Code
- Containerização
- Orchestração automática
- Serverless computing

---

## 🔧 Conceitos Fundamentais por Década

### 1960s - **Multiprogramação**
- Vários programas na memória simultaneamente
- CPU alterna entre processos
- **Benefício**: Melhor utilização de recursos

### 1970s - **Memória Virtual**
- Abstração de memória maior que a física
- Paginação e segmentação
- **Benefício**: Programa pode ser maior que RAM

### 1980s - **Interface Gráfica**
- WIMP (Windows, Icons, Menus, Pointers)
- Event-driven programming
- **Benefício**: Facilidade de uso

### 1990s - **Multithreading**
- Múltiplas threads por processo
- Programação concorrente
- **Benefício**: Melhor responsividade

### 2000s - **Virtualização**
- Múltiplos SOs no mesmo hardware
- Hypervisors
- **Benefício**: Isolamento e utilização eficiente

### 2010s - **Containerização**
- Aplicações isoladas sem SO completo
- Menor overhead que VMs
- **Benefício**: Portabilidade e eficiência

---

## 📊 Métricas de Evolução

### Performance de Hardware
| Década | CPU (MIPS) | RAM (MB) | Storage (GB) |
|---------|-----------|----------|--------------|
| 1970s   | 0.5       | 0.001    | 0.001       |
| 1980s   | 1-10      | 0.1-1    | 0.01        |
| 1990s   | 10-100    | 1-16     | 0.1-1       |
| 2000s   | 100-1000  | 16-512   | 1-100       |
| 2010s   | 1000+     | 512-8192 | 100-1000    |
| 2020s   | 10000+    | 8192+    | 1000+       |

### Evolução dos Sistemas de Arquivos
- **1960s**: Flat files, sequential access
- **1970s**: Hierarchical directories (UNIX)
- **1980s**: FAT, NTFS - metadata
- **1990s**: Journaling (ext3, NTFS)
- **2000s**: Distributed filesystems (GFS, HDFS)
- **2010s**: Object storage (S3, Swift)
- **2020s**: Container-native storage

---

## 🎯 Tendências Atuais e Futuras

### Computação Quântica
- **Algoritmos quânticos** para problemas específicos
- **Simulação** de sistemas quânticos
- **Impacto**: Criptografia, otimização, machine learning

### Inteligência Artificial Integrada
- **SOs com IA nativa**: Windows Copilot, macOS Intelligence
- **Otimização automática** de recursos
- **Interfaces conversacionais**

### Edge Computing
- **Processamento próximo aos dados**
- **Baixa latência** para IoT
- **Sistemas operacionais distribuídos**

### Sustentabilidade
- **Green Computing**: Eficiência energética
- **Carbon-aware computing**: Scheduling baseado em energia limpa
- **Hardware sustentável**: Longer lifecycles

---

## 🔍 Perguntas de Reflexão

1. **Como a evolução do hardware influenciou o design dos SOs?**
2. **Quais conceitos dos anos 1960s ainda são relevantes hoje?**
3. **Por que alguns sistemas "antigos" como UNIX ainda são populares?**
4. **Como os SOs se adaptaram à mobilidade e limitações de energia?**
5. **Qual será o próximo grande paradigma na computação?**

---

## 📚 Leituras Complementares

### Artigos Clássicos
- Dijkstra, E. W. (1968). "The structure of the 'THE' multiprogramming system"
- Lampson, B. W. (1974). "Protection"
- Ritchie, D. M. & Thompson, K. (1974). "The UNIX Time-Sharing System"

### Livros de Referência
- Tanenbaum, A. S. "Modern Operating Systems"
- Silberschatz, A. "Operating System Concepts" 
- McKusick, M. K. "The Design and Implementation of the FreeBSD Operating System"

### Documentários
- "The Code" (2001) - History of Linux and Open Source
- "Revolution OS" (2001) - GNU/Linux movement
- "Something Ventured" (2011) - Silicon Valley history

---

*Resumo preparado para apoiar o estudo da [História Completa da Computação](historico-computacao.md)*
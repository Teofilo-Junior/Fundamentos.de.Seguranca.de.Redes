# 📘  MINIGUIA DE ESTUDO — SEGURANÇA DE REDES
## 📌 1. Contexto e Objetivo da criação do MINIGUIA
Este projeto tem como objetivo estudar os fundamentos de Segurança de Redes utilizando o NotebookLM como ferramenta de apoio.
Mais do que apenas compreender o conteúdo, o foco foi desenvolver um processo de aprendizado baseado em:
- uso estratégico de Inteligência Artificial
- engenharia de prompts
- análise crítica das respostas geradas
-  construção de um material de revisão reutilizável

## 🎯 2. Objetivos de estudo
- Compreender os fundamentos da segurança de redes
- Identificar principais ameaças e vulnerabilidades
- Entender mecanismos de proteção (firewall, criptografia, etc.)
- Aplicar conceitos em contextos práticos
- Desenvolver pensamento crítico no uso de IA

## 📚 3. Curadoria de Fontes
As seguintes fontes foram utilizadas no NotebookLM:
- [Segurança em redes de computadores - IFF](https://arandu.iffarroupilha.edu.br/handle/itemid/213)
- [Segurança em redes de computadores - FatecAssis](https://acesse.one/0b9y7qb)
- [Segurança em redes de computadores - UFF](https://sl1nk.com/d70pync)
- [Cartilha de segurança para internet - Cert](https://cartilha.cert.br/livro/cartilha-seguranca-internet.pdf)

As fontes foram escolhidas por combinarem base acadêmica (UFF, IFF) com material aplicado (CERT.br), permitindo uma visão equilibrada entre teoria e prática.

## 📊 4. Resumos estruturados

### 🔹 O que é Segurança de Redes
 - Conjunto de práticas e tecnologias voltadas à proteção de redes contra acessos não autorizados, ataques e falhas.

### 🔹 Princípios básicos
- Confidencialidade
- Integridade
- Disponibilidade

### 🔹 Principais ameaças
- Malware
- Phishing
- DDoS
- Sniffing

### 🔹 Mecanismos de proteção
- Firewalls
- Criptografia
- Autenticação
- Monitoramento

## 📚 5. Glossário
- Firewall → sistema que controla o tráfego da rede
- Malware → software malicioso
- DDoS → ataque de sobrecarga de servidores
- Criptografia → proteção de dados por codificação
- Phishing → tentativa de roubo de dados por engano

## 🧠 6. Engenharia de prompts e “cicatrizes”
### 🔹 Exemplo 1
**Prompt inicial:**

> "Explique segurança de redes"

**Retorno:**

**"A segurança de redes é um campo essencial que visa garantir a confidencialidade, integridade e disponibilidade dos dados e sistemas interconectados.
Com a evolução da tecnologia e a transição de sistemas centralizados para abordagens distribuídas, a necessidade de investimentos nessa área tornou-se crítica devido ao aumento de invasões e infecções por códigos maliciosos."**

 **Problema:**
- Resposta genérica;
- Pouca profundidade;
- Esse prompt se torna vago por não direcionar o modelo em relação à aplicação ou citar exemplos de como o modelo deveria retornar o que foi solicitado, o que pode ser observado no segundo exemplo nos campos: "contexto","instruções" e "formato de resposta".

**Ajuste utilizando um prompt completo**
### 👉 Baseado em: componentes de um prompt da engenharia de prompts

>"Explique o conceito de segurança de redes de forma clara e didática para iniciantes.

*Contexto:*
*Estou estudando segurança de redes em nível introdutório e preciso de uma explicação fácil de entender, sem termos excessivamente técnicos.*

 Instruções:
> - Apresente uma definição simples do conceito
> - Dê pelo menos um exemplo prático do dia a dia
> - Explique os principais riscos ou ameaças relacionados
> - Cite aplicações reais da segurança de redes

 Formato da resposta:
> - Organize em tópicos
> - Use linguagem simples
> - Seja objetivo e claro"


**Retorno:**


### "O que é Segurança de Redes?

*- A segurança de redes é a área que abrange estratégias e ferramentas para prevenir, detectar e resolver incidentes relacionados ao tráfego de informações entre computadores*

*- Seu objetivo principal é criar barreiras de proteção contra softwares mal-intencionados que tentam roubar dados ou causar o caos na rede*

*- Ela se baseia em três pilares fundamentais, conhecidos como a tríade da segurança: Confidencialidade (apenas quem deve ver a informação tem acesso), Integridade (a mensagem não é alterada no caminho) e Disponibilidade (o serviço está sempre acessível aos usuários)*

### Exemplo Prático
*- Imagine que você está fazendo uma compra em uma loja virtual*

*- Ao utilizar o protocolo HTTPS, seu navegador "tranca" as informações do seu cartão de crédito usando criptografia antes de enviá-las*

*- Isso garante que, mesmo que um invasor (chamado de intruso ou "Trudy" em termos técnicos) consiga capturar os dados no meio do caminho, ele não conseguirá "entender" ou ler o conteúdo, pois a mensagem está codificada*

### Possíveis Riscos (Ameaças)
As redes estão expostas a diversos perigos que podem comprometer seus dados:

*-Malware: Programas como vírus (que precisam de um hospedeiro), worms (que se espalham sozinhos) e cavalos de troia (que parecem programas inofensivos, mas executam funções maliciosas)*

*- Sniffing: Uma técnica de "grampo" onde o invasor usa programas para interceptar e capturar informações sensíveis (como senhas) que viajam por conexões inseguras e sem criptografia*

*- Engenharia Social (Phishing): Golpes que tentam enganar o usuário através de mensagens falsas para que ele forneça dados financeiros ou clique em links maliciosos voluntariamente*

*- Negação de Serviço (DoS/DDoS): Ataques que visam sobrecarregar os recursos de um servidor até que ele fique indisponível para os usuários legítimos*

### Principais Aplicações (Ferramentas de Proteção)
Para combater esses riscos, utilizam-se diversos mecanismos:

*- Firewall: Funciona como uma barreira que isola a rede interna de uma organização da Internet, permitindo apenas o tráfego autorizado*

*- Antivírus e Antimalware: Softwares instalados na máquina capazes de detectar, anular e remover códigos maliciosos*

*- Redes Virtuais Privadas (VPN): Criam um túnel seguro e criptografado para que o tráfego viaje pela Internet pública com sigilo*

*- Assinatura e Certificado Digital: Métodos para confirmar a identidade de uma pessoa ou site e garantir a autenticidade da comunicação no mundo virtual."*

### Resultado:

- Mais claro;
- Mais útil para estudo;
- Mais fácil de ser compreendido e absorvido;
- O modelo respondeu de forma mais alinhada aos objetivos devido à estrutura do prompt, mas ainda depende da qualidade das instruções e pode apresentar limitações.

## 🧠 🔧 7. Prompts reutilizáveis

### 1.Prompt com divisão de tarefa
👉 Baseado na técnica de dividir tarefa

>"Explique [ex: segurança de redes] dividindo em etapas:
>1. O que é
>2. Para que serve
>3. Como funciona na prática
>4. Exemplos reais"

**Objetivo:**
Organiza e explica um conceito em partes lógicas e progressivas.

**Quando usar:**
- Quando o conteúdo parece confuso ou “embaralhado”
- Ao estudar um tema pela primeira vez
- Quando respostas anteriores vieram desorganizadas
- Para revisar conteúdos antes de prova
- Quando você precisa garantir que nenhuma parte importante foi ignorada

**Resultado esperado:**
- Resposta mais estruturada e sequencial
- Melhor separação entre teoria e prática
- Redução de explicações vagas ou incompletas
- Maior clareza na progressão do raciocínio
- Facilidade para memorização e revisão

### 2.Prompt para análise crítica
👉 Baseado em: pensamento crítico

>"Quais são as limitações das técnicas de [ex: segurança de redes?]"

**Objetivo:**
Desenvolver pensamento crítico sobre o tema, indo além da visão "natural" de buscar apenas as soluções e esquecendo dos pontos fracos.

**Quando usar** 
- Após já entender os conceitos básicos
- Em fase de revisão ou aprofundamento
- Ao comparar diferentes soluções de segurança
- Para preparar trabalhos, provas ou discussões mais analíticas

**Resultado esperado:**
- Respostas que exploram limitações reais (ex: firewall não protege contra engenharia social)
- apresentam cenários de falha
- mostram dependência de configuração correta
- destacam fatores humanos (erro do usuário)
- trazem visão mais próxima do mundo real

### 3. Prompt com restrições (guardrails)
👉 Baseado em: restrições e limitações

>Explique [ex: segurança de redes em até 150 palavras.]
>- Foque apenas nos conceitos mais importantes e evite detalhes avançados.

**Objetivo:**
- Forçar o modelo a priorizar informações essenciais
- Evitar respostas longas e dispersas
- Criar resumos objetivos e diretos
- Melhorar a retenção do conteúdo

**Quando usar:**
- Revisão rápida antes de prova
- Quando o conteúdo está confuso ou muito extenso
- Para criar resumos finais do miniguia
- Quando você quer evitar explicações técnicas demais

**Resultado esperado:**
- Respostas mais curtas e focadas
- Maior clareza conceitual
- Redução de “ruído” (informações desnecessárias)
- Conteúdo mais fácil de memorizar

### 4. Prompt com comparação
👉 Baseado em: análise crítica

>"Compare [ex: firewall e antivírus:]
>- principais diferenças
>- quando usar cada um
>- limitações de cada abordagem"

**Objetivo:**
Desenvolver pensamento analítico ao comparar duas tecnologias ou conceitos de segurança de redes, identificando diferenças, aplicações e limitações de cada abordagem.

**Quando usar:**
- Quando houver dois conceitos semelhantes que podem gerar confusão
- Durante revisões para consolidar entendimento
- Para aprofundar o conhecimento além de definições básicas
- Em preparação para provas ou trabalhos que exigem análise crítica

**Resultado esperado:**
- Resposta estruturada e comparativa
- Clareza sobre o papel de cada tecnologia
- Identificação de cenários de uso reais
- Compreensão das limitações (evitando visão superficial ou idealizada)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-escuro.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-claro.png">
  <img src="assets/banner-escuro.png" alt="Davidson Walker · Engenheiro de IA · Gestor de Automação" width="100%">
</picture>

## >_ Olá, eu sou o Davidson

Engenheiro de IA e gestor de automação em Palmas, TO. Em 2024 fundei a [Audz AI](https://audzai.com), onde construo agentes de IA que atendem, vendem e dão suporte pelo WhatsApp. Já trabalhei com infoprodutores, escolas, construtoras, e-commerce e proteção veicular.

Cuido do projeto inteiro: arquitetura, desenvolvimento, infraestrutura e a operação depois que o agente entra no ar. Também treino o time do cliente para acompanhar o atendimento e ajustar a IA no dia a dia.

## >_ O que já foi pro ar

| Agente | Cliente | O que faz | Resultado |
| --- | --- | --- | --- |
| **Roberta** | Academia Rafael Toro de Finanças | Tira dúvidas dos alunos de CFP e CPA-20 em cerca de 20 grupos de WhatsApp, com RAG sobre o material do curso | 5 mil+ alunos, 2+ anos no ar |
| **Daniela** | Raiz da Solução | Recupera carrinho abandonado e checkout, com follow-up em áudio na voz do infoprodutor | +R$350 mil em 7 dias |
| **Sueli & Rita** | Comu RT | Multiagente: a Sueli cuida das vendas e a Rita do suporte técnico | −70% de dúvidas no time humano |
| **SDRs sob medida** | RealSmart · APS · NSA | Qualificam com SPIN selling, agendam por API e mandam link de venda com cupom | — |

Também montei agentes de venda consultiva de alto ticket para lançamentos do Érico Rocha e da Fernanda Landeiro, com picos de milhares de requisições por minuto na abertura de carrinho.

## >_ Como eu monto

```text
WhatsApp ─▶ Evolution API ─▶ n8n (modo worker) ─▶ LangChain / LangGraph ─▶ GPT · Claude · Gemini
                                                                            via OpenRouter
rastreio   Langfuse
filas      Redis · RabbitMQ
dados      PostgreSQL · Qdrant · pgvector
infra      Docker Swarm · Traefik · Portainer
```

## >_ Stack

**IA e agentes**<br>
<img src="https://img.shields.io/badge/OpenAI-151515?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2YwZWNlOCIgZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D" alt="OpenAI">
<img src="https://img.shields.io/badge/Claude-151515?style=flat-square&logo=claude&logoColor=f0ece8" alt="Claude">
<img src="https://img.shields.io/badge/Gemini-151515?style=flat-square&logo=googlegemini&logoColor=f0ece8" alt="Gemini">
<img src="https://img.shields.io/badge/OpenRouter-151515?style=flat-square&logo=openrouter&logoColor=f0ece8" alt="OpenRouter">
<img src="https://img.shields.io/badge/LangChain-151515?style=flat-square&logo=langchain&logoColor=f0ece8" alt="LangChain">
<img src="https://img.shields.io/badge/LangGraph-151515?style=flat-square&logo=langgraph&logoColor=f0ece8" alt="LangGraph">
<img src="https://img.shields.io/badge/CrewAI-151515?style=flat-square&logo=crewai&logoColor=f0ece8" alt="CrewAI">
<img src="https://img.shields.io/badge/MCP-151515?style=flat-square&logo=modelcontextprotocol&logoColor=f0ece8" alt="MCP">
<img src="https://img.shields.io/badge/Ollama-151515?style=flat-square&logo=ollama&logoColor=f0ece8" alt="Ollama">
<img src="https://img.shields.io/badge/ElevenLabs-151515?style=flat-square&logo=elevenlabs&logoColor=f0ece8" alt="ElevenLabs">

**Automação e dados**<br>
<img src="https://img.shields.io/badge/n8n-151515?style=flat-square&logo=n8n&logoColor=f0ece8" alt="n8n">
<img src="https://img.shields.io/badge/Evolution%20API-151515?style=flat-square&logo=whatsapp&logoColor=f0ece8" alt="Evolution API">
<img src="https://img.shields.io/badge/Supabase-151515?style=flat-square&logo=supabase&logoColor=f0ece8" alt="Supabase">
<img src="https://img.shields.io/badge/PostgreSQL-151515?style=flat-square&logo=postgresql&logoColor=f0ece8" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Redis-151515?style=flat-square&logo=redis&logoColor=f0ece8" alt="Redis">
<img src="https://img.shields.io/badge/RabbitMQ-151515?style=flat-square&logo=rabbitmq&logoColor=f0ece8" alt="RabbitMQ">
<img src="https://img.shields.io/badge/Qdrant-151515?style=flat-square&logo=qdrant&logoColor=f0ece8" alt="Qdrant">

**Infra e código**<br>
<img src="https://img.shields.io/badge/Docker%20Swarm-151515?style=flat-square&logo=docker&logoColor=f0ece8" alt="Docker Swarm">
<img src="https://img.shields.io/badge/Traefik-151515?style=flat-square&logo=traefikproxy&logoColor=f0ece8" alt="Traefik">
<img src="https://img.shields.io/badge/Portainer-151515?style=flat-square&logo=portainer&logoColor=f0ece8" alt="Portainer">
<img src="https://img.shields.io/badge/Google%20Cloud-151515?style=flat-square&logo=googlecloud&logoColor=f0ece8" alt="Google Cloud">
<img src="https://img.shields.io/badge/Python-151515?style=flat-square&logo=python&logoColor=f0ece8" alt="Python">
<img src="https://img.shields.io/badge/TypeScript-151515?style=flat-square&logo=typescript&logoColor=f0ece8" alt="TypeScript">
<img src="https://img.shields.io/badge/Node.js-151515?style=flat-square&logo=nodedotjs&logoColor=f0ece8" alt="Node.js">

## >_ Estudando agora

Certificações em andamento: Google Cloud Generative AI Leader · AWS Certified AI Practitioner · Microsoft Azure AI Fundamentals (AI-901) · Oracle OCI AI Foundations · Anthropic Academy (Claude, Claude Code e MCP) · cursos oficiais do n8n.

## >_ Contato

<a href="https://www.linkedin.com/in/davidson-walker"><img src="https://img.shields.io/badge/LinkedIn-151515?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2YwZWNlOCIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMCAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMSAxIDIuMDYzIDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjIyIDBoLjAwM3oiLz48L3N2Zz4%3D" alt="LinkedIn"></a>
<a href="https://audzai.com"><img src="https://img.shields.io/badge/Audz%20AI-151515?style=flat-square&logo=googlechrome&logoColor=f0ece8" alt="Audz AI"></a>
<a href="https://www.instagram.com/audz.ai/"><img src="https://img.shields.io/badge/Instagram-151515?style=flat-square&logo=instagram&logoColor=f0ece8" alt="Instagram"></a>
<a href="mailto:contato@audzai.com"><img src="https://img.shields.io/badge/contato%40audzai.com-151515?style=flat-square&logo=gmail&logoColor=f0ece8" alt="contato@audzai.com"></a>

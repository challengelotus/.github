# ☁️ Nimbus – Inteligência que acelera decisões

Somos uma startup fictícia criada para o desafio **Ford FIAP 2026**.  
Nosso propósito é transformar dados dispersos em inteligência competitiva de alto valor, com soluções leves, modernas e orientadas a serviços.

---

## 🚗 Projeto: Ford Commercial Intelligence

**Desafio 01 – Inteligência Competitiva Automotiva**  
Automatizar a coleta e padronização de fichas técnicas de veículos concorrentes, utilizando **web scraping**, **LLM local** e uma **API RESTful** para consulta e cache de resultados.

> De 1 hora por versão (manual) para segundos com IA.

---

## 🧠 Stack tecnológica

| Camada           | Tecnologia                                                       |
| ---------------- | ---------------------------------------------------------------- |
| Frontend         | React + Tailwind CSS                                             |
| Backend (API)    | Python + FastAPI                                                 |
| Coleta de dados  | Requests + BeautifulSoup (Selenium opcional)                    |
| IA / NLP         | Ollama + Llama 3.2 (local e gratuito)                            |
| Banco de dados   | SQLite (cache de resultados)                                     |
| Documentação API | Swagger UI + ReDoc (automático)                                  |
| Versionamento    | Git + GitHub                                                     |

---

## 🧱 Arquitetura enxuta (MVP)
[React] → [FastAPI] → [SQLite cache] → (se necessário) → [Scrapers] → [LLM local]
- Backend síncrono e minimalista (sem filas ou orquestradores complexos)
- Cache inteligente evita reprocessamento do mesmo veículo
- Pronto para evoluir para microsserviços no futuro

---

## 📦 Repositórios do projeto

| Repositório                         | Descrição                                         |
| ----------------------------------- | ------------------------------------------------- |
| `nimbus/ford-commercial-intel`      | Código principal (backend + frontend)            |
| `nimbus/llm-models` (opcional)      | Configuração do Ollama e modelos baixados         |
| `nimbus/docs`                       | Diagramas, slides e documentação acadêmica       |

---

## 👥 Colaboradores

Equipe responsável pela concepção, desenvolvimento e entrega do desafio.

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">

<a href="https://github.com/Malice112" target="_blank" style="text-align: center; text-decoration: none; color: inherit;">
  <img loading="lazy" src="https://ih1.redbubble.net/image.2517271799.2840/bg,f8f8f8-flat,750x,075,f-pad,750x1000,f8f8f8.jpg" width="100" style="border-radius: 50%;">
  <p><strong>Maria Alice</strong><br>RM557516</p>
</a>

<a href="https://github.com/jaoAprendiz" target="_blank" style="text-align: center; text-decoration: none; color: inherit;">
  <img loading="lazy" src="https://i.pinimg.com/736x/32/6a/4e/326a4e68de3f5e63327464e7c703994d.jpg" width="100" style="border-radius: 50%;">
  <p><strong>João Victor</strong><br>RM557595</p>
</a>

<a href="https://github.com/pehenmendes" target="_blank" style="text-align: center; text-decoration: none; color: inherit;">
  <img loading="lazy" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3Qhc8gyUfQcl0imXGLOUNamU8ugmXW_iSbA&s" width="100" style="border-radius: 50%;">
  <p><strong>Pedro Henrique</strong><br>RM555332</p>
</a>

<a href="https://github.com/uBittencourt" target="_blank" style="text-align: center; text-decoration: none; color: inherit;">
  <img loading="lazy" src="https://i.pinimg.com/736x/0e/93/da/0e93da007f33d609bd71043eec7c9213.jpg" width="100" style="border-radius: 50%;">
  <p><strong>Vinicius Bittencourt</strong><br>RM??????</p>
</a>

<a href="https://github.com/rt-lucena" target="_blank" style="text-align: center; text-decoration: none; color: inherit;">
  <img loading="lazy" src="https://i.pinimg.com/736x/18/0e/fc/180efc3227b70e92b88fd3e71826fbad.jpg" width="100" style="border-radius: 50%;">
  <p><strong>Rafael Lucena</strong><br>RM??????</p>
</a>

</div>

---

## 📄 Licença

Este projeto é acadêmico e sem vínculo comercial direto. Todos os dados coletados são de fontes públicas e utilizados exclusivamente para fins educacionais.

---

## 🏁 Status

✅ Estrutura definida  
⏳ Em desenvolvimento ativo  
🎯 Entrega prevista: conforme cronograma FIAP 2026

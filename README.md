```markdown
# 🚦 RL - Roteamento Estático com 6 Roteadores

Bem-vindo(a)! Este repositório contém artefatos (scripts, topologias e documentação) para um exercício/experimento de roteamento estático envolvendo 6 roteadores. O objetivo é demonstrar conceitos de roteamento estático, tabelas de encaminhamento e testes básicos de conectividade. 🧭✨

## 🔍 Visão geral
- Tema: Roteamento estático em uma topologia com 6 roteadores.
- Foco: Configuração de rotas estáticas, verificação de conectividade e documentação dos passos.
- Público-alvo: Estudantes e entusiastas de redes que queiram entender comportamento de rotas estáticas em topologias pequenas. 🎓

## 📁 Estrutura sugerida do repositório
(Verifique os nomes dos diretórios no repositório; adapte conforme necessário)
- `topologias/` — arquivos de definição da topologia (ex.: scripts de Mininet, diagramas). 📐
- `scripts/` — scripts para criar a topologia, configurar rotas e executar testes (ping, traceroute). 🛠️
- `configs/` — arquivos com configurações de roteadores (ex.: configurações CLI ou arquivos de configuração). 🗂️
- `docs/` — documentação adicional, relatórios e diagramas. 📝
- `README.md` — este arquivo. ✅

## ⚙️ Requisitos (exemplo)
- Linux (recomendado)
- Python 3.8+ (se os scripts forem em Python)
- Ferramentas de rede (ex.: Mininet, iproute2) — instale conforme os scripts/README internos. 🖥️
- Permissões de root para manipular interfaces e roteamento (dependendo do ambiente). ⚠️

## ▶️ Como começar (exemplo genérico)
1. Clone o repositório:
   ```
   git clone https://github.com/leandroFilipy/RL-roteamento-estatico-com-6-roteadores.git
   ```
2. Entre no diretório:
   ```
   cd RL-roteamento-estatico-com-6-roteadores
   ```
3. Leia os arquivos em `topologias/` e `scripts/` para entender os comandos específicos. 📚  
4. Execute o script principal (substitua pelo nome real do script, se houver):
   ```
   sudo python3 scripts/boot_topology.py
   ```
5. Configure rotas estáticas conforme os arquivos em `configs/` ou usando os scripts auxiliares.  
6. Teste conectividade:
   - ping entre hosts
   - traceroute para verificar caminhos

Obs.: Ajuste os comandos conforme os nomes reais de scripts neste repositório.

## ✅ Exemplos de comandos úteis
- Ver tabela de rotas no Linux:
  ```
  ip route show
  ```
- Adicionar rota estática:
  ```
  sudo ip route add <rede> via <next-hop>
  ```
- Ping:
  ```
  ping -c 4 <endereço>
  ```
- Traceroute:
  ```
  traceroute <endereço>
  ```

## 🧾 O que documentar nos seus testes
- Topologia usada (diagrama + lista de interfaces)
- Rotas estáticas aplicadas em cada roteador
- Resultado dos pings e traceroutes
- Observações sobre falhas e correções

## 🤝 Contribuições
Contribuições são bem-vindas! Abra uma issue ou envie um pull request com:
- Correções de scripts
- Melhorias na documentação
- Novos testes e automações

## 📬 Contato
Autor: leandroFilipy  
Sinta-se à vontade para abrir issues no repositório para dúvidas ou sugestões. ✉️

## 🧾 Licença
Adicione aqui a licença do projeto (por exemplo, MIT) ou mantenha conforme desejar. 📜

```

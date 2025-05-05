# covid-data-engineering-pipeline

🧩 Componentes que você vai construir:
✅ covid_api.py
Usa a API pública do Brasil.IO

Coleta dados por estado ou data

Suporte à paginação

✅ clean_data.py
Filtra colunas relevantes

Remove nulos

Agrega por estado/data, se necessário

✅ save_sqlite.py
Conecta com banco covid.db

Cria tabela se não existir

Insere ou atualiza registros com base em chave (ex: data, estado)

✅ db_handler.py
Funções para criar conexão, rodar comandos, verificar tabelas

✅ prefect_flow.py
Usa Prefect 2.x para orquestrar as etapas

Tarefas encadeadas: extract → transform → load

✅ Testes
Usa pytest

Testes com mock de API

Teste transformação (input → output esperado)

Teste SQLite com banco em memória (sqlite://:memory:)

🧪 Extras que você pode adicionar depois:
Logging com loguru

Retry automático em caso de falha de API

Versionamento de dados (arquivos ou DB)

🎯 Resultado Esperado:
Esse projeto vai servir como:

Demonstração de engenharia de dados prática

Comprovação de conhecimento em testes e orquestração

Base para projetos mais avançados com pipelines em produção


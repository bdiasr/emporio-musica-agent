# Empório da Música · Agente de atendimento

Protótipo de agente de mensagens de texto que atende clientes da Empório da Música
(loja de instrumentos musicais em Campo Grande/MS). Desafio técnico de AI Engineer.

## Como rodar

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate   |   Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
pip install -e .
cp .env.example .env        # preencha a chave do provedor
python scripts/indexar_politicas.py
python -m emporio.cli
```

Testes: `pytest`

## Arquitetura

## Decisões técnicas

Resumo aqui; detalhes em [docs/decisoes.md](docs/decisoes.md).

## Tratamento dos dados

## Suposições

Ver [docs/suposicoes.md](docs/suposicoes.md).

## Avaliação

## Exemplos de conversa

Ver [exemplos/](exemplos/).

## Limitações conhecidas

## Com mais tempo eu faria

## Uso de assistentes de IA

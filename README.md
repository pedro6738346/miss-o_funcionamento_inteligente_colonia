# 🪐 Sistema Inteligente de Gerenciamento de Colônia

Sistema desenvolvido em Python para monitorar e gerenciar os recursos de uma colônia em ambiente hostil, integrando organização de dados, lógica de decisão, previsão por regressão linear e análise de energia.

---

## ⚙️ Funcionalidades

- **Organização de dados:** estrutura hierárquica dos sistemas da colônia e dados operacionais em tempo real
- **Lógica de decisão:** regras automáticas que avaliam o nível de energia e consumo e geram alertas
- **Previsão de energia:** regressão linear simples que estima a energia gerada com base na velocidade do vento
- **Análise de energia:** comparação entre geração e consumo, com sugestões de ação

---

## ▶️ Como executar

1. Clone o repositório
2. Execute o arquivo principal:
```bash
python sistema_colonia.py
```

---

## 📥 Exemplo de entrada

```python
dados_operacionais = {
    "Energia Atual": 60,
    "Consumo Atual": 80,
    "Vento": 15,
    "Clima": "Nublado"
}
```

## 📤 Exemplo de saída

```
=======================================================
   SISTEMA DE GERENCIAMENTO DA COLÔNIA
=======================================================

📋 SISTEMAS DA COLÔNIA:
  Sistema Energético: ['Solar', 'Eólico']
  Sistema de Alimentação: ['Câmara de Plantação', 'Sistema de Irrigação', 'Câmara de Sementes']
  Sistema Médico: ['Sistema de Atendimento Emergencial', 'Sistema de Atendimento Geral']

⚡ DECISÃO DO SISTEMA:
  SITUAÇÃO: ATIVAR RESERVA DE EMERGÊNCIA E LIGAR PAINÉIS SOLARES | Suporte de Vida: ATIVADO

🔋 PREVISÃO DE ENERGIA (vento=15 m/s): 22.88 unidades

📊 ANÁLISE DE ENERGIA:
  ALERTA! ATIVAR RESERVA DE ENERGIA!
=======================================================
```

---

## 🗂️ Estrutura do projeto

```
sistema_colonia.py   # código principal
README.md            # documentação
```

# Thiago Ramos — Transporte Executivo e Corporativo

Site de página única com calculadora do valor da corrida (quilometragem × tempo de serviço).

## Configurar tarifas e WhatsApp

Edite o bloco `TARIFA` no final do `index.html`:

| Campo | Descrição |
|---|---|
| `whatsapp` | Número com DDI + DDD, só dígitos (ex.: `5511999999999`) |
| `bandeirada` | Taxa fixa de partida (R$) |
| `porKm` | Valor por km rodado (R$) |
| `porMinuto` | Valor por minuto de deslocamento (R$) |
| `esperaHora` | Valor por hora de espera / à disposição (R$) |
| `taxaAeroporto` | Adicional para corridas de aeroporto (R$) |
| `noturno` / `feriado` | Percentuais adicionais (0.20 = 20%) |
| `minimo` | Valor mínimo da corrida (R$) |

## Publicar

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.

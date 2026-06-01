# Operadoras — Geotab Add-In

Add-in para MyGeotab que analisa a cobertura de operadoras de telefonia na frota.

## Funcionalidades

- Carrega dispositivos do Geotab via `DeviceStatusInfo`
- Importa antenas de operadoras por planilha (XLSX/CSV) ou do servidor
- Analisa cobertura Vivo 3G/4G e outras operadoras no raio de 5 km e 20 km
- Exibe mapa com círculos de cobertura e marcadores de antenas
- Sugere ações: ✅ Vivo 3G, 📶 Trocar 4G, 🤝 Reaproveitar 3G, 🔄 Trocar operadora, ❌ Sem cobertura

## Deploy

O site está hospedado no GitHub Pages:

```
https://brunofelisbino.github.io/operadorasgeotab/
```

## Como usar no MyGeotab

1. Acesse **Administration → System → Add-Ins**
2. Clique em **Adicionar**
3. Cole o conteúdo abaixo:

```json
{
  "name": "Operadoras",
  "supportEmail": "bruno@rotagyn.com.br",
  "version": "1.0",
  "isSigned": false,
  "items": [
    {
      "url": "https://brunofelisbino.github.io/operadorasgeotab/",
      "path": "ActivityLink/",
      "menuName": {
        "en": "Operadoras",
        "pt-BR": "Operadoras"
      }
    }
  ]
}
```

## Repositório

[https://github.com/BrunoFelisbino/operadorasgeotab](https://github.com/BrunoFelisbino/operadorasgeotab)

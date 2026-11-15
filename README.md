# Survivors: Endless Apocalypse

Protótipo de jogo de sobrevivência roguelite para navegador, com controles mobile e visual em Canvas.

## Executar localmente
Abra `index.html` em um navegador moderno ou sirva a pasta por HTTP:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Controles
- Celular: joystick virtual no canto inferior esquerdo.
- Computador: WASD ou setas.
- Ataques automáticos; ESC pausa no computador.

## Sistemas presentes no protótipo
- 3 regiões selecionáveis e 5 personagens desbloqueáveis.
- 12 armas, 8 passivas e melhorias escolhidas ao subir de nível.
- 15 arquétipos de inimigos, elites e chefe após 10 minutos.
- XP, moedas, vida, dano, projéteis, drops e tela de resultado.
- Melhorias permanentes e salvamento local.

## Estado e limitações
Esta é uma primeira versão jogável, não uma versão final de produção. A arte é procedural em Canvas, o áudio é sintetizado, e ainda faltam evoluções dedicadas de armas, conquistas, padrões avançados de chefes e QA em aparelhos físicos. Não foi realizado teste físico em iPhone nesta entrega.

## Publicação
O projeto está configurado para publicação pelo GitHub Pages usando GitHub Actions. Após o primeiro push, confirme em **Settings → Pages** que a origem está configurada como **GitHub Actions**.

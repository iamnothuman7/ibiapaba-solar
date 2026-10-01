# Ibiapaba Solar

Simulador web de economia com energia solar compartilhada para a Associação Ibiapaba Solar. Permite informar consumo ou valor da fatura e consultar uma comparação calculada no navegador.

[Abrir demonstração](https://iamnothuman7.github.io/ibiapaba-solar/)

## Funcionamento

HTML, CSS e JavaScript estão reunidos em `index.html`; a marca usada pela interface está em `logo.png`. O cálculo usa constantes no código, incluindo tarifas e contribuição de iluminação, e oferece encaminhamento para contato por WhatsApp.

As constantes não são atualizadas automaticamente. Os resultados são simulações com os parâmetros implementados, não promessa de economia, proposta comercial vinculante ou validação de regras tarifárias atuais.

## Executar localmente

```sh
git clone https://github.com/iamnothuman7/ibiapaba-solar.git
cd ibiapaba-solar
python -m http.server 8000 --bind 127.0.0.1
```

Abra `http://127.0.0.1:8000/`. Não há etapa de build ou servidor de aplicação.

## Manutenção e validação

Antes de uso comercial, revise as constantes em `calculateEconomy`, as premissas da associação e o destino de contato. Teste entradas vazias, valores inválidos, os dois modos de entrada e telas pequenas. Não há suíte automatizada de testes neste repositório.

Esta versão tem `index.html` na raiz. O repositório [ibiapaba-solar-calculator](https://github.com/iamnothuman7/ibiapaba-solar-calculator) preserva outra apresentação do simulador; [calculadora](https://github.com/iamnothuman7/calculadora) é um protótipo inicial. Os históricos foram mantidos separados.

## Uso

Não há licença de redistribuição declarada. Marca, imagens e dados comerciais devem ser usados somente com autorização dos responsáveis.

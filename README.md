# Stop Auto Center · site (Template 4 Moderno, personalizado)

Oficina mecânica na Alameda Tuca, 222, Jardim Ipês, Cotia - SP.
WhatsApp (11) 91221-4510 · Instagram @stopautocenter.cotia

## Arquivos

```
index.html  → estrutura e textos
style.css   → visual (cores e fontes em :root; ajustes do cliente no fim do arquivo)
script.js   → interações (WhatsApp e intervalos de revisão no objeto CONFIG)
img/        → logo, favicon, fotos recortadas dos posts e posts da seção "Dicas"
```

## O que mudou em relação ao template

- Identidade da marca: preto #0D0D0D, vermelho #D53116, títulos em Anton e texto em Poppins (as mesmas famílias visuais dos posts).
- Seção de depoimentos trocada por "Dicas da Stop", com os posts do Instagram. Para adicionar um post novo, salve a imagem em img/ e copie um bloco `<a class="post">`.
- Calculadora de revisão com opção de uso severo (5.000 km ou 6 meses).
- Correção: o template bloqueava datas passadas em todos os campos de data, o que impedia preencher a "data da última revisão". Agora campos com `data-passado` aceitam só até hoje.
- Perguntas frequentes informativas, no tom dos posts.
- Mapa do Google embutido e dados estruturados (schema.org AutoRepair) para busca local.

## Confirmar com o cliente

- Link do Facebook (usei facebook.com/stopautocenter.cotia).
- E-mail e CNPJ, se quiser exibir (foram retirados por não terem sido informados).
- Horário de funcionamento.
- Se faz orçamento antes do serviço e se oferece garantia (a garantia foi retirada dos textos).

## Ao publicar

Troque `img/hero.jpg` em `og:image` e no JSON-LD pelo endereço completo (ex.: https://dominio.com.br/img/hero.jpg) para a prévia aparecer no WhatsApp.

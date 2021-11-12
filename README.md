![uideveloper](https://user-images.githubusercontent.com/14277806/141522969-4dbebbdb-4e78-407a-b88e-f40558f68bb3.png)

Estamos muito felizes por você querer fazer parte da Nuvemshop / Tiendanube 🎉

Este é um pequeno teste para entendermos sobre seu processo de pensamento, como você estrutura seu trabalho e como você maximiza seu tempo e habilidades. 

# A tarefa: Desenvolver o nosso aplicativo de viagem no tempo.

Já se perguntou como era o mundo há 200 anos? que tal 2.000? Que tal 20.000? 

Agora as pessoas podem viajar no tempo e ver por si mesmas. Nós inventamos uma tecnologia (Fictícia por enquanto 🤷 ) que permite que você viaje para qualquer ano que desejar 😱 😱 😱 😱 😱.


## Agora você precisa resolver o seguinte problema:

O design do aplicativo foi atualizado e o serviço já existe. Agora precisamos aplicar a UI em duas telas do nosso Web App.

### Detalhes de implementação

1. O produto precisa ser 100% Web e Mobile Only 📱 ❤️;
2. O design system está disponível somente no figma, então você precisará lidar com reutilização de componentes;
3. Temos a liberdade de utilizar ReactJS (Gatsby/NextJS) ou mesmo podemos utilizar Vanilla JS 👍;
4. O nosso CMS trás parte do conteúdo da página através de uma API;
5. Keep it simple!


# Entregáveis

- Gostaríamos de ver um protótipo online. Você pode hospedar em algum host gratuito como [Heroku](https://heroku.com) ou [Vercel](https://vercel.com/);
- Gostaríamos de ter acesso ao repositório Git que você utilizou.


# Critérios de avaliação

- Qualidade na execução (você não precisa desenvolver testes);
- Capacidade de popular uma página de conteúdo com dados vindos de API;
- Capacidade de simplificar uma solução. `A simplicidade é o último grau da sofisticação`


Divirta-se, queremos você no time ❤️ 


# Recusos técnicos

## UI
- [Link para telas](https://www.figma.com/file/0RVWcfnRct81SW6RsPrWcC/UI-Development-test?node-id=0%3A1)
- [Link para protótipo navegável](https://www.figma.com/proto/0RVWcfnRct81SW6RsPrWcC/UI-Development-test?page-id=0%3A1&node-id=18%3A6644&viewport=241%2C48%2C0.24&scaling=scale-down&starting-point-node-id=18%3A6644&show-proto-sidebar=1)


## API

[Link para API](https://uideveloper-api.herokuapp.com/api/data)

### Uma requisição get retornará esse esquema de dados:
```
{
  "available_places": [
    {
      "place": "Washington, D.C. - EUA",
      "img": "//d2r9epyceweg5n.cloudfront.net/assets/blog_pt/IhaveadreamMarines.jpeg",
      "date": "1963-09-28T00:00:00.000Z",
      "event_name": "Luther King speech",
      "likes": "1k"
    }
    ...
  ],
  "editors_pick": [
    {
      "title": "A day in the Jurassic",
      "content": "The Jurassic is a geologic period and stratigraphic system that spanned from the end of the Triassic Period 201.3 million years ago (Mya) to the beginning of the Cretaceous Period, approximately 145 ...",
      "img": "//d2r9epyceweg5n.cloudfront.net/assets/blog_pt/i7524.webp"
    }
  ],
  "travellers": [
    {
      "name": "SanchezRick",
      "img": "//d2r9epyceweg5n.cloudfront.net/assets/blog_pt/Rick_Sanchez.png"
    },
    {
      "name": "MortySmith",
      "img": "//d2r9epyceweg5n.cloudfront.net/assets/blog_pt/Morty501.png"
    }
  ]
}
```


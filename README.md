# burguerapp
Aplicativo Android para uma hamburgueria fictícia com funcionalidades de pedidos, cardápio, promoções e localização.
## 📱 Funcionalidades

- Tela inicial com logo da hamburgueria
- Login e cadastro de usuários com Firebase Authentication
- Visualização de cardápio com imagens e descrição
- Montar seu hambúrguer com ingredientes customizáveis
- Carrinho de compras
- Pedido com acompanhamento de status em tempo real
- Notificações push de promoções (Firebase Cloud Messaging)
- Localização da loja com Google Maps API
- Chat com atendimento ao cliente
- Integração completa com Firebase Firestore

---

## 🛠️ Tecnologias Utilizadas

| Recurso                     | Tecnologia                        |
|----------------------------|-----------------------------------|
| Linguagem                  | Kotlin                            |
| IDE                        | Android Studio                    |
| Backend                    | Firebase Firestore                |
| Autenticação               | Firebase Authentication           |
| Notificações               | Firebase Cloud Messaging (FCM)    |
| Mapa                       | Google Maps API                   |
| Versionamento              | Git + GitHub                      |
| Protótipo (UI/UX)          | Figma                             |


BurgerApp/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/burgerapp/
│ │ │ │ ├── data/model/
│ │ │ │ ├── ui/auth/
│ │ │ │ ├── ui/home/
│ │ │ │ ├── ui/menu/
│ │ │ │ ├── ui/cart/
│ │ │ │ ├── ui/order/
│ │ │ │ ├── ui/chat/
│ │ │ │ └── utils/
│ │ │ ├── res/layout/
│ │ │ ├── res/drawable/
│ │ │ ├── res/values/
│ │ │ ├── AndroidManifest.xml
├── build.gradle
├── google-services.json
└── README.md



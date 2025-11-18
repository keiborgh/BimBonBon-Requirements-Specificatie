```mermaid
classDiagram
    class Klant
    class Product
    class Handleiding
    class Update
    class Chat
    class ChatBericht
    class Ticket

    Klant "1" --> "*" Product
    Product "1" --> "1" Handleiding
    Product "1" --> "*" Update
    Klant "1" --> "*" Chat
    Chat "1" --> "*" ChatBericht
    Klant "1" --> "*" Ticket
```
```mermaid
classDiagram
    class Klant {
        +int klantID
        +string naam
        +string email
        +registreerProduct()
        +verstuurFeedback()
    }
    class Product {
        +int productID
        +string naam
        +string serienummer
        +date aankoopdatum
        +controleerStatus()
    }
    class Handleiding {
        +int handleidingID
        +string titel
        +string inhoud
        +zoek()
    }
    class Update {
        +int updateID
        +string titel
        +date datum
        +updateStatus()
    }
    class Chat {
        +int chatID
        +date startDatum
        +startChat()
    }
    class ChatBericht {
        +int berichtID
        +string inhoud
        +date tijdstip
        +verzendBericht()
    }
    class Ticket {
        +int ticketID
        +string onderwerp
        +string status
        +updateStatus()
        +sluitTicket()
    }

    Klant "1" --> "*" Product : bezit
    Product "1" --> "1" Handleiding : heeft
    Product "1" --> "*" Update : ontvangt
    Klant "1" --> "*" Chat : start
    Chat "1" --> "*" ChatBericht : bevat
    Klant "1" --> "*" Ticket : maakt aan

```


```

# API contracts
## CRUD operations needed for:
#### Du endpoint'ai Read. Vienas grąžina list'ą, kitas grąžina vieną item'ą
- Employee
- Discount (susikuria kartu ir EventTime eilutė, jeigu reikia)
- Order
- Product
- Business
- GiftCard
- Reservation
- ProductVariation
- User
- Inventory
- Restaurant (susikuria kartu ir address eilutė)
- Payment


## Other endpoints
### Order
- CloseOrder
- CancelOrder
- RefundOrder

### Reservation
- CancelReservation

---
### TODO:

- Dominykas: Employee, GiftCard, Restaurant
- Rytis: Discount, Reservation, Payment
- Brigita: Order, ProductVariation, CloseOrder, CancelOrder, RefundOrder
- Dovydas: Product, User, CancelReservation
- Gabrielis: Business, Inventory

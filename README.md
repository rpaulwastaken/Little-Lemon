# Meta: Back-End Developer Capstone

- This is the final assignment of the Meta Backend Developer Professional Certificate on Coursera

## API Endpoints testing 🔄 

▷ The API app comes with a total of 4 endpoints, plus you'll find Djoser endpoints ready to use as well.

- Check out all the menu items or craft a unique addition
```
http://127.0.0.1:8000/api/menu/items
```

| Method | Action                  | TOKEN AUTH | STATUS CODE |
|--------|-------------------------|------------|-------------|
| GET    | Retrieve all menu items | No         | 200         |
| POST   | Create a menu item      | No         | 201         |

- Discover, update, partially modify, or bid farewell to that special dish
```
http://127.0.0.1:8000/api/menu/items/{itemId}
```

| Method | Action                           | TOKEN AUTH | STATUS CODE |
|--------|----------------------------------|------------|-------------|
| GET    | Retrieves the menu item details  | No         | 200         |
| PUT    | Update the menu item             | No         | 200         |
| PATCH  | Partially update the menu item   | No         | 200         |
| DELETE | Delete the menu item             | No         | 200         |

- Explore, update, partially adjust, or remove that special table
```
http://127.0.0.1:8000/api/booking/tables
```

| Method | Action                 | TOKEN AUTH | STATUS CODE |
|--------|------------------------|------------|-------------|
| GET    | Retrieve all bookings  | Yes        | 200         |
| POST   | Create a booking       | Yes        | 201         |

- Check it out, update, partially modify, or bid farewell to that one special table
```
http://127.0.0.1:8000/api/booking/tables/{bookingId}
```

| Method | Action                        | TOKEN AUTH | STATUS CODE |
|--------|-------------------------------|------------|-------------|
| GET    | Retrieve the booking details  | Yes        | 200         |
| PUT    | Update the booking            | Yes        | 200         |
| PATCH  | Partially update the booking  | Yes        | 200         |
| DELETE | Delete the booking            | Yes        | 200         |

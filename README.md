# Financepal
App for managing finances

<table>
   <tr>
      <td><img src="assets/1.png" height="500px"></td>
      <td><img src="assets/2.png" height="500px"></td>
      <td><img src="assets/3.png" height="500px"></td>
   </tr>
   <tr>
      <td><img src="assets/4.png" height="500px"></td>
      <td><img src="assets/5.png" height="500px"></td>
      <td><img src="assets/6.png" height="500px"></td>
   </tr>
</table>

# Backend

## Debug token
* endrju - `Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxIn0.eSArqeSJ4EtfNxr1IPpIyk2YFs9IFz-cWynIKyWyL7k`
* dodo - `Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIyIn0.BHuk4FoBbQkceI_rbnUrv2c45FOtNYxY4vjMShzM9bM`
* syra - `Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIzIn0.l5NfayRHN-8D7DYkBorr-dYZF9QrjkPS53xk0kRCSRY`

## How to start the app
1. Install Docker
2. On main project directory run `docker compose up --build`
3. API is working under [http://localhost:8080](http://localhost:8080)
4. To access the API docs open [http://localhost:8080/docs/](http://localhost:8080/docs/)

## Mock data
1. `GET /reset_db/` - resets database and inserts mock data
2. Login with test credentials:
   ```json
   {
    "username": "endrju",
    "password": "Password123"
   }
   ```

# Mobile

## How to start the app
1. Install Flutter.
2. On mobile project directory run `flutter run`.
3. App is working on your device.


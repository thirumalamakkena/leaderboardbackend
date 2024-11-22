
To run the backend server, follow these steps:

1. **Navigate to the backend directory**:
    ```sh
    cd backend/src
    ```
2. **Install backend dependencies**:
    ```sh
    npm install
    ```
3. **Start the backend server**:
    ```sh
    npm run server
    ```

The backend server will start on `http://localhost:7000`.

### Routes

- `PATCH`: `http://localhost:7000/api/user/v1/claim-points` to update the points for a user.
- `POST`: `http://localhost:7000/api/user/v1/your-history` to retrieve a user’s point history.
- `GET`: `http://localhost:7000/api/user/v1/get-users` to fetch the list of all users for the leaderboard.
- `GET`: `http://localhost:7000/api/user/v1/get-users-info-id` to retrieve the logged-in user's information.



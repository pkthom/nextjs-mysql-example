# Next.js + MySQL Example

This is a simple example of using Next.js with MySQL via Docker Compose.

## How to Run

```bash
docker-compose up --build
```
Access the app:
```
http://localhost:3000
```
You will see a list of users from MySQL:
- Alice
- Bob
- Charlie

## Structure
- `db/init.sql` – MySQL table & sample data
- `next-app/pages/index.js` – Frontend
- `next-app/pages/api/users.js` – API to fetch users
- `docker-compose.yaml` – App + DB setup

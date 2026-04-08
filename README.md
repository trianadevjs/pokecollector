# 📘 Pokémon TCG Binder

A web application designed to manage and visualize a personal Pokémon Trading Card Game (TCG) collection. This project simulates a digital binder, allowing users to organize, explore, and track their cards efficiently.
Built with NestJS, this project focuses on scalable backend architecture, API integration, and clean code practices.

---
- 🚀 Features
- 📂 Digital binder view for card collections
- 🔍 Search and filter Pokémon cards
- ⭐ Mark favorite cards
- 📊 Track owned cards and quantities
- 🔄 Manage tradeable cards
- 🔐 Authentication with JWT (planned)
- ⚡ API caching for performance (planned)
---
# 🧱 Tech Stack
- Backend: NestJS (Node.js, TypeScript)
- Database: (TBD – PostgreSQL / SQLite / MongoDB)
- ORM: (TypeORM / Prisma)
- API Integration: Pokémon TCG API
- Authentication: JWT (planned)
- Testing: Jest
- Documentation: Swagger
---
# 🏗️ Architecture
The project follows a modular architecture using NestJS best practices:

```
src/
│
├── auth/
├── users/
├── cards/
├── collection/
├── sets/
├── binder/
│
├── common/
├── config/
└── main.ts
```

Each module encapsulates its own logic, controllers, and services, promoting scalability and maintainability.

---
📦 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/pokemon-tcg-binder.git

# Navigate into the project
cd pokemon-tcg-binder

# Install dependencies
npm install
```
---
▶️ Running the app
```bash
# Development
npm run start:dev

# Production
npm run build
npm run start:prod
```
---
🧪 Running tests
```bash
# Unit tests
npm run test

# e2e tests
npm run test:e2e

# Coverage
npm run test:cov
```
---
# 🔌 API Integration

This project consumes data from the Pokémon TCG API to retrieve card information such as:
- Name
- Type
- Set
- Rarity
- Images
- Caching strategies may be implemented to reduce external API calls and improve performance.

---
# 📘 API Documentation
Once the application is running, Swagger documentation will be available at:

```
http://localhost:3000/api
```
---
# 🎯 Project Goals
This project is part of a personal effort to:
Strengthen backend development skills using NestJS
Practice scalable architecture and modular design
Work with real-world API integrations
Build a portfolio-ready project

---
# 🛠️ Roadmap

- [ ] Implement authentication (JWT)
- [ ] Add advanced filters and pagination
- [ ] Integrate caching (Redis)
- [ ] Dockerize the application
- [ ] Add user profiles
- [ ] Enable card trading between users

---
# 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

---
#📄 License
This project is licensed under the MIT License.

---
# 👨‍💻 Author
Antonio Triana  
Backend Developer | QA Engineer

---
# ⭐ Acknowledgements
Pokémon TCG API for providing card data

NestJS team for the amazing framework
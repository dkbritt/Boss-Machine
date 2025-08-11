# 🧠 Boss Machine API

Boss Machine is a full-stack API built to power a satirical management platform for the world's most diabolical entrepreneurs. It handles CRUD operations for minions, million-dollar ideas, and meetings—plus bonus functionality for managing minion work backlogs.

## 🚀 Features

### Minions
- `GET /api/minions` — Retrieve all minions
- `POST /api/minions` — Add a new minion
- `GET /api/minions/:minionId` — Get a specific minion
- `PUT /api/minions/:minionId` — Update a minion
- `DELETE /api/minions/:minionId` — Remove a minion

### Ideas
- `GET /api/ideas` — Retrieve all ideas
- `POST /api/ideas` — Add a new idea
- `GET /api/ideas/:ideaId` — Get a specific idea
- `PUT /api/ideas/:ideaId` — Update an idea
- `DELETE /api/ideas/:ideaId` — Remove an idea

💡 Includes custom middleware `checkMillionDollarIdea` to validate idea profitability.

### Meetings
- `GET /api/meetings` — Retrieve all meetings
- `POST /api/meetings` — Generate a new meeting
- `DELETE /api/meetings` — Clear all meetings

### Bonus: Minion Work
- `GET /api/minions/:minionId/work` — Get all work for a minion
- `POST /api/minions/:minionId/work` — Add new work
- `PUT /api/minions/:minionId/work/:workId` — Update work
- `DELETE /api/minions/:minionId/work/:workId` — Remove work

## 🧪 Testing

Includes a comprehensive test suite to validate all endpoints and edge cases.

---

Built with Express.js and a mock database for rapid prototyping. Perfect for practicing RESTful API design, middleware logic, and modular routing.
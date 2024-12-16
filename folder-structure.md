### 1. Special Characters Drawing List

<table>
  <tr>
    <th>Character</th>
    <th>Keyboard Input</th>
    <th>Name</th>
    <th>Purpose/Example</th>
  </tr>
  <tr>
    <td><code>├──</code></td>
    <td>Alt + 195</td>
    <td>Box Drawing (Branching)</td>
    <td>Used to represent a branching point. Example: File trees.</td>
  </tr>
  <tr>
    <td><code>│</code></td>
    <td>Alt + 179</td>
    <td>Vertical Line</td>
    <td>Represents vertical continuation. Example: File hierarchy.</td>
  </tr>
  <tr>
    <td><code>└──</code></td>
    <td>Alt + 192</td>
    <td>Box Drawing (End Branch)</td>
    <td>Represents the last item in a branch. Example: File trees.</td>
  </tr>
  <tr>
    <td><code>─</code></td>
    <td>Alt + 196</td>
    <td>Horizontal Line</td>
    <td>Used as a connecting line. Example: Branch or division.</td>
  </tr>
  <tr>
    <td><code>┬</code></td>
    <td>Alt + 194</td>
    <td>T-shaped Connector</td>
    <td>Shows a junction or split. Example: Connecting multiple branches.</td>
  </tr>
  <tr>
    <td><code>┐</code></td>
    <td>Alt + 191</td>
    <td>Top-right Corner</td>
    <td>Represents a corner. Example: Box corners in ASCII art.</td>
  </tr>
  <tr>
    <td><code>┘</code></td>
    <td>Alt + 217</td>
    <td>Bottom-right Corner</td>
    <td>Another box corner. Example: End of a box or frame.</td>
  </tr>
  <tr>
    <td><code>┌</code></td>
    <td>Alt + 218</td>
    <td>Top-left Corner</td>
    <td>Represents the top-left corner of a box. Example: ASCII frames.</td>
  </tr>
  <tr>
    <td><code>└</code></td>
    <td>Alt + 192</td>
    <td>Bottom-left Corner</td>
    <td>Represents the bottom-left corner of a box. Example: ASCII frames.</td>
  </tr>
</table>

---

### 2. File Tree Representation:

```
project/
├── README.md
├── package.json
├── .gitignore
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   ├── favicon.ico
│   │   └── robots.txt
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   └── Navbar.module.css
│   │   │   ├── Footer/
│   │   │   │   ├── Footer.jsx
│   │   │   │   └── Footer.module.css
│   │   │   └── Button.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── About.jsx
│   │   │   └── Contact.jsx
│   │   ├── App.jsx
│   │   ├── index.js
│   │   └── styles/
│   │       ├── global.css
│   │       └── variables.css
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── userController.js
│   │   │   └── productController.js
│   │   ├── models/
│   │   │   ├── userModel.js
│   │   │   └── productModel.js
│   │   ├── routes/
│   │   │   ├── userRoutes.js
│   │   │   └── productRoutes.js
│   │   ├── middlewares/
│   │   │   ├── authMiddleware.js
│   │   │   └── errorHandler.js
│   │   ├── utils/
│   │   │   ├── dbConnect.js
│   │   │   └── logger.js
│   │   ├── app.js
│   │   └── server.js
│   ├── .env
│   └── package.json
├── database/
│   ├── migrations/
│   │   ├── 20240101_create_users_table.sql
│   │   └── 20240102_create_products_table.sql
│   ├── seeds/
│   │   ├── seedUsers.js
│   │   └── seedProducts.js
│   └── dbConfig.js
└── tests/
    ├── frontend/
    │   ├── components/
    │   │   └── Navbar.test.js
    │   └── pages/
    │       └── Home.test.js
    ├── backend/
    │   ├── controllers/
    │   │   └── userController.test.js
    │   └── routes/
    │       └── userRoutes.test.js
    └── jest.config.js
```

---

### 3. Explanation of Structure:

<table>
  <tr>
    <th>Folder/File</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td><code>frontend/</code></td>
    <td>Contains all front-end code (React).</td>
  </tr>
  <tr>
    <td><code>backend/</code></td>
    <td>Contains all back-end code (Express.js, Node.js).</td>
  </tr>
  <tr>
    <td><code>database/</code></td>
    <td>Handles database migrations, seeds, and configurations.</td>
  </tr>
  <tr>
    <td><code>tests/</code></td>
    <td>Includes test files for both front-end and back-end (e.g., Jest tests).</td>
  </tr>
  <tr>
    <td><code>public/</code></td>
    <td>Contains static files served by the front-end (e.g., HTML, icons).</td>
  </tr>
  <tr>
    <td><code>src/</code></td>
    <td>Source code for both front-end and back-end.</td>
  </tr>
  <tr>
    <td><code>controllers/</code></td>
    <td>Back-end logic for handling routes and data flow.</td>
  </tr>
  <tr>
    <td><code>models/</code></td>
    <td>Schema definitions for databases (e.g., MongoDB, Sequelize).</td>
  </tr>
  <tr>
    <td><code>routes/</code></td>
    <td>Back-end route definitions.</td>
  </tr>
  <tr>
    <td><code>middlewares/</code></td>
    <td>Custom middleware for authentication, error handling, etc.</td>
  </tr>
  <tr>
    <td><code>utils/</code></td>
    <td>Utility functions like database connections and logging.</td>
  </tr>
  <tr>
    <td><code>migrations/</code></td>
    <td>SQL files for database schema creation.</td>
  </tr>
  <tr>
    <td><code>seeds/</code></td>
    <td>Scripts to populate initial database data.</td>
  </tr>
</table>

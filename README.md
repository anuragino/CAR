# 🚗 **Car-Manager**  
Car Manager is a sleek web app powered by MongoDB, React, and Express for efficient car management. Users can add, edit, delete, and search car listings with details like titles, descriptions, tags, and images. Its intuitive design ensures seamless inventory management for individuals and businesses.


## 🛠️ Technologies Used

- **React (Frontend):** JavaScript library for dynamic UIs, component-based, promotes reusability.
- **Node.js (Runtime Environment):** Server-side JavaScript runtime, enables backend development with JavaScript.
- **Express.js (Backend):** Minimalist Node.js framework for building scalable, efficient backend APIs.
- **MongoDB (Database):** NoSQL database, flexible JSON-like documents, high performance, scalability.

## 🌟 **Features**   
- **Add Cars**: Easily add new cars by providing a title, description, tags, and uploading up to 10 images for each listing.
- **Edit & Update**: Update car details effortlessly to keep listings accurate and up-to-date. 
- **Search**: Quickly locate cars using a robust search feature by title, description, or tags.
- **Delete**: Remove cars that are no longer needed with a simple action. 

## 🚦 Running the Project

1. **Clone the Repository:** `git clone https://github.com/anuragino/Car-Manager`
2. **Navigate to the Project Directory:** `cd Car-Manager/client` and `cd Car-Manager/Server`
3. **Install Dependencies:** `npm install` in both Directory.
4. Run in Server `npm server.js` to start the server.
5. Run in Client `npm run dev` to get the project started.

---

## 📖 **API Endpoints**  

### **Authentication**  
| Method | Endpoint            | Description          |
|--------|---------------------|----------------------|
| POST   | `/api/auth/register` | Register a new user |
| POST   | `/api/auth/login`    | Login an existing user |

### **Cars**  
| Method | Endpoint               | Description                     |
|--------|------------------------|---------------------------------|
| GET    | `/api/cars`            | Fetch all cars of the user      |
| POST   | `/api/cars`            | Add a new car                   |
| GET    | `/api/cars/:id`        | Fetch details of a specific car |
| PUT    | `/api/cars/:id`        | Update details of a specific car |
| DELETE | `/api/cars/:id`        | Delete a specific car           |

---

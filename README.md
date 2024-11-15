# 🚗 **Car Management Application**  
Effortlessly manage your cars with an elegant, user-friendly web application.

![1](https://github.com/user-attachments/assets/913ea076-f8da-42db-9d68-3d646cb875da)
![2](https://github.com/user-attachments/assets/5cd6f36d-bc07-43cf-bcc1-4e8fdc6b818a)
![3](https://github.com/user-attachments/assets/8304565e-6633-42a0-b12d-53dbe5106344)

---

## 🌟 **Features**  

### 🔑 **Authentication**  
- **Secure Login & Registration**: Protect your data with user authentication.  
- **Session Management**: Stay logged in during active sessions.  

### 🚘 **Car Management**  
- **Add Cars**: Include titles, descriptions, tags, and up to 10 images.  
- **Edit & Update**: Modify existing car details with ease.  
- **Delete**: Remove cars no longer needed.  
- **Search**: Quickly find cars by title, description, or tags.

### 🌐 **Responsive Design**  
- Optimized for desktop, tablet, and mobile devices.

---

## 🚀 **Technologies Used**  

### **Frontend**  
- [React.js](https://reactjs.org/) - User Interface.  
- [React Router](https://reactrouter.com/) - Navigation and routing.  
- [Axios](https://axios-http.com/) - API communication.  
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling.

### **Backend**  
- [Node.js](https://nodejs.org/) - Server-side runtime.  
- [Express.js](https://expressjs.com/) - Backend framework.  
- [MongoDB](https://www.mongodb.com/) - Database for persistent storage.  
- [Mongoose](https://mongoosejs.com/) - ODM for MongoDB.

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

## 🎯 **Future Enhancements**  
- **Role-based Access Control**: Admin vs Regular User.  
- **Car Pagination**: Efficiently handle large datasets.  
- **Image Uploads**: Integrate with AWS S3 or Cloudinary.  
- **Improved Search**: Add fuzzy search capabilities.  

---

### 👨‍💻 **Developed By**  
Anurag Kumar  [LinkedIn](https://www.linkedin.com/in/anuragino/)

---

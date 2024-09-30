



##  GeoUsers

### **Description**:
**GeoUsers** is a web application built with React that allows users to browse through a list of profiles and interactively explore their addresses on a map. This platform combines profile management with geographic visualization to provide an intuitive, user-friendly experience for both users and administrators. Users can easily search, filter, and view the location of each profile on a map, while an admin panel allows for profile management.



### **Key Features**:
- **Profile Display**: Displays profiles with essential details like name, photo, and a short description.
- **Interactive Map**: A dynamic map to visualize profile addresses.
- **Search and Filter**: Functionality to search and filter profiles based on name, location, or other attributes.
- **Admin Panel**: CRUD functionality (Create, Read, Update, Delete) for managing profiles.
- **Responsive Design**: The app is optimized for use on both desktop and mobile devices.
- **Error Handling**: Robust error handling for managing failed requests and invalid data.
- **Loading Indicators**: Visual feedback while data is being fetched or maps are rendered.
- **Profile Details View**: Additional profile details such as contact info, hobbies, and more.



### **Tech Stack**:
- **Frontend**: React, React Router, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Map Integration**: Google Maps API or Mapbox
- **State Management**: React Context API or Redux
- **Tools**: Vite, Axios, Postman



### **Setup and Installation**:

#### **1. Clone the Repository:**

```bash
git clone https://github.com/username/GeoUsers.git
cd GeoUsers
```

#### **2. Install Dependencies:**

```bash
npm install
```

#### **3. Set up Environment Variables:**

Create a `.env` file in the root of the project and add the following variables:

```bash
REACT_APP_GOOGLE_MAPS_API_KEY=<your-google-maps-api-key>
```

#### **4. Run the Application:**

```bash
npm start
```

The app will be live at `http://localhost:3000/`.

---




### **Features and Usage**:

1. **Profile Display**:
   - Profiles with name, photo, and description are listed on the homepage.
   - Users can click the "Summary" button to view the address on the map.

2. **Interactive Map**:
   - Upon clicking a profile’s summary button, the map dynamically loads with a marker showing the user's address.

3. **Admin Panel**:
   - Admins have access to a dashboard for profile management, including adding, updating, and deleting profiles.

4. **Search and Filter**:
   - Users can search and filter profiles based on specific criteria like location, name, or interests.

---

### **Contributing**:
If you’d like to contribute to **GeoUsers**, feel free to fork the repository and submit a pull request for review.

---


### **Contact**:
For any questions or feedback, please contact [ishangawande55@gmail.com].

---


# MiniUrl

MiniUrl is a web application designed to shorten lengthy URLs into concise links while offering an integrated analytics feature to track visit counts for each shortened link.  

## Features  
- **Dynamic HTML Rendering:** Utilized Embedded JS (.ejs) for seamless server-side rendering of URLs and analytics data.  
- **Responsive UI:** Styled using CSS within .ejs templates for a modern and user-friendly interface.  
- **Robust Backend:** Built with Node.js and Express.js to handle URL shortening, redirection, and analytics management.  
- **Secure Authentication:** Integrated JWT (JsonWebTokens) to authenticate users securely.  
- **Efficient Data Storage:** Used MongoDB Atlas for mapping URLs and storing visit counts.  
- **Deployment:** Deployed on Railway for seamless access and scalability.  

---

## Installation  

Follow these steps to set up MiniUrlD on your local machine:  

1. **Clone the Repository:**  
   ```bash  
   git clone https://github.com/vish2002/MiniUrlD
   ```  

2. **Navigate to the Project Folder:**  
   ```bash  
   cd <project-folder-name>  
   ```  

3. **Install Dependencies:**  
   ```bash  
   npm install  
   ```
    

4. **Start the Server:**  
   ```bash  
   npm start  
   ```  

5. **Access the Application:**  
   Open your browser and visit:  
   [http://localhost:8001](http://localhost:8001)  

---

## Usage  

1. Enter a lengthy URL in the input field.  
2. Generate a shortened URL.  
3. Use the shortened URL to redirect to the original link.  
4. Track the visit count for each shortened URL in the analytics section.  

---

## Tech Stack  

- **Frontend:** Embedded JS (EJS), CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Authentication:** JWT (JsonWebTokens)  
- **Deployment:** Railway  

---

Feel free to contribute or report issues. Let's make MiniUrlD better together! 😊  

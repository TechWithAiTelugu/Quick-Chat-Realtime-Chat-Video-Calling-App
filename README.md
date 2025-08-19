# Quick Chat 💬

> A sleek, real-time chat and video calling web application with **friend requests**, **communities**, **QR code sharing**, and **voice/video calling** — built with **vanilla JavaScript**, **Firebase**, and **WebRTC**.

🎥 [Watch on YouTube](https://youtu.be/FM_e1K6ejz0?si=F490eqcDby-PG9mP)

---

## ✨ Features

### 🔐 Authentication & Profile
- **Email/Password & Google Sign-In** via Firebase
- **5-Digit User ID** for easy friend discovery
- **Profile Management**: Edit name and upload avatar
- **QR Code Sharing**: Share your ID by scanning

### 💬 Messaging System
- **Realtime 1-on-1 Chat**: Powered by Firebase Realtime Database
- **Group Communities**: Create and join group chats
- **Message Bubbles**: Sent/received styling with sender name (in groups)
- **Typing Simulation**: Smooth UI with loading indicators

### 👥 Friend & Community System
- **Add Friends by ID**: Send/receive friend requests
- **Community Chats**: Create/join public or private groups
- **Friend List**: View online/offline status in real time

### 📞 Voice & Video Calling
- **Audio Calls**: One-tap calling with mic control
- **Video Calls**: Full video chat with local preview
- **WebRTC Signaling**: Peer-to-peer via Firebase
- **Call History**: Logs for incoming, outgoing, missed, and rejected calls
- **Call Timer**: Shows duration once connected

### 🎨 UI & UX
- **Fully Responsive**: Works on mobile, tablet, and desktop
- **Material Design**: Clean layout with FAB buttons, icons, and smooth transitions
- **No Frameworks**: Built with pure HTML, CSS, and JavaScript — lightweight and fast
- **Toast Notifications**: Real-time alerts for actions and errors

---

## 📸 Screenshots

### Home Screen
![Home Screen](https://techwithai.github.io/Quick-Chat-Realtime-Chat-Video-Calling-App/Images/home.png)  
*Friend list with online status and floating action button*

### Chat Interface
![Chat Interface](https://techwithai.github.io/Quick-Chat-Realtime-Chat-Video-Calling-App/Images/chat.png)  
*Clean message bubbles with call options in header*

### Call
![ Call](https://techwithai.github.io/Quick-Chat-Realtime-Chat-Video-Calling-App/Images/calls.png)  
*Full-screen calling UI with remote and local video*

### Add Friend & QR
![Add Friend](https://techwithai.github.io/Quick-Chat-Realtime-Chat-Video-Calling-App/Images/profile.png)  
*Add friends using 5-digit ID or share your QR code*

---

## 🚀 How to Run

### Prerequisites
- Modern browser (Chrome, Firefox, Edge)
- Firebase account (for authentication and database)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/techwithai/Quick-Chat-Realtime-Chat-Video-Calling-App.git
   cd tournament-manager
   ```

2. Set up Firebase:
   - Create a new project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Realtime Database
   - Copy your Firebase configuration

3. Configure Firebase:
   - Open `index.html`
   - Replace the Firebase configuration object with your own:
     ```javascript
     const firebaseConfig = {
         apiKey: "YOUR_API_KEY",
         authDomain: "YOUR_AUTH_DOMAIN",
         projectId: "YOUR_PROJECT_ID",
         storageBucket: "YOUR_STORAGE_BUCKET",
         messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
         appId: "YOUR_APP_ID"
     };
     ```

4. Deploy to web hosting:
   - Use Firebase Hosting, GitHub Pages, or any static web hosting service
   - Ensure both admin and user interfaces are accessible

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [@techwithai](https://youtube.com/@techwitai1?si=nbFi4SpBRd-RiOuf)

Project Link: [https://github.com/yourusername/tournament-manager](https://github.com/techwithai/Quick-Chat-Realtime-Chat-Video-Calling-App.git)

## Acknowledgements

- [Font Awesome](https://fontawesome.com/) for the amazing icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font
- [Firebase](https://firebase.google.com/) for the backend services

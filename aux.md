<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.11/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.6.11/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyB-2hhsGFg8aF4YNsq-aUfzGSI9q3FDWlw",
    authDomain: "macmantenimiento-dbd5b.firebaseapp.com",
    projectId: "macmantenimiento-dbd5b",
    storageBucket: "macmantenimiento-dbd5b.appspot.com",
    messagingSenderId: "607987159282",
    appId: "1:607987159282:web:428b4bc530fc05e598406b",
    measurementId: "G-7BBERGLQ42"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
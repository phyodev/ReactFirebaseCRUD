# React-Firebase-CRUD (Simple Project)

## Guide

Before you install the project you should create Firebase Account for backend system and then clone the project and add configuration inside <mark>firebase-config.js</mark> file.

### Example -

```
import { initializeApp } from "firebase/app";
import { getFirestore } from "@firebase/firestore";

const firebaseConfig = {
    apiKey: "kajsd;fjoewirjoii389u420234",
    authDomain: "react-app-test.firebaseapp.com",
    projectId: "react-app-test",
    storageBucket: "react-app-test3.appspot.com",
    messagingSenderId: "7987989798789",
    appId: "4:8979789798789:web:aieuoijidiefj7897879",
    measurementId: "G-30GEDECL"
  };

const app = initializeApp(firebaseConfig);

export const db = getFirestore(app);
```

### Note -
Change only <mark>const firebaseConfig</mark>
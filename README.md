# Netflix Clone

#### inisialisasi project menggunakan CRA dan redux template
```
npx create-react-app netflix-clone --template redux
```

#### pindah ke directory project
```
cd netflix-clone
```

#### set up firebase

- buat project di firebase
```
https://firebase.google.com/?hl=id
```

- masuk ke konsol
- project settings
- registrasi web ke firebase
- pilih config
- copy firebase confignya

```
const firebaseConfig = {
  apiKey: "**************************",
  authDomain: "**************************",
  projectId: "**************************",
  storageBucket: "**************************",
  messagingSenderId: "**************************",
  appId: "**************************"
};
```

- buat file ```firebase.js```
- paste firebase config


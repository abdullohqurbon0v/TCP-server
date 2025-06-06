# 🌐 Server README
## 📖 Project Overview
This project allows you to create your own **TCP server** in **C**.

---

## ✅ Requirements
- **minGW**

---

## 🚀 Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/abdullohqurbon0v/TCP-server.git
    ```

---

## 🛠️ Usage
Start the server:
```bash
gcc tcp -o tcp
./tcp
```

### Example Output:
```bash
****@****:~/tcp/$ gcc tcp -o tcp
****@****:~/tcp/$ ./tcp
🎉 Listening on 0.0.0.0:8080
```

### Check Active Connections:
```bash
****@****:~/tcp/$ netstat -an | grep LISTEN
tcp        0      0 0.0.0.0:8080            0.0.0.0:*               LISTEN    $SELECTION_PLACEHOLDER$
```

---
Enjoy building your TCP server! 🚀
```

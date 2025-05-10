# 💊 Unity Pharmacy Hub

Unity Pharmacy Hub is a Django-based web application designed to streamline pharmacy management. It includes essential features such as user authentication, drug inventory management, and role-based access for pharmacies.

---

## 🚀 Features

✅ User Signup & Login
✅ Django's built-in user authentication system
✅ User Logout
🚧 Password Reset via Twilio (To be implemented)
✅ View drug inventory
✅ Add and edit drug entries
✅ Pharmacy-specific user authorization

---

## 🛠️ Getting Started

Follow the steps below to set up the project on your local machine.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SasikaA073/duothon-team.git
cd duothon-team
```

### 2️⃣ Set Up the Python Environment

#### 🔹 On Linux/macOS:

```bash
virtualenv --python=python3 ~/venv/UnityPharmacyEnv
source ~/venv/UnityPharmacyEnv/bin/activate
```

#### 🔹 On Windows:

```bash
python -m venv ENV
ENV\Scripts\activate
```

> ✅ You’ll know it’s activated when your terminal shows a prefix like: `(ENV) C:\Users\YourName>`

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Development Server

```bash
python manage.py runserver
```

Then open your browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📌 To-Do / In Progress

* [ ] Implement Twilio-based password reset functionality
* [ ] Add unit tests for all major functionalities
* [ ] Improve UI/UX for the inventory dashboard
* [ ] Add search/filter options for inventory

---

## 👨‍💻 Contributing

Feel free to fork the repo and submit pull requests! If you're interested in contributing, check out the [issues](https://github.com/SasikaA073/duothon-team/issues) tab to see what needs work.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

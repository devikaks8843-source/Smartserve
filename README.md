# SmartServe

SmartServe is a web-based service management platform that connects users with local service providers. It features a robust multi-role portal for Users, Service Providers, and Administrators, enabling seamless booking, provider verification, and payment processing.

---

## 🌟 Key Features

### 👤 User Features
- **User Registration & Login**: Account creation and secure login.
- **Service Browsing & Booking**: View available service providers and book time slots.
- **Booking Management**: View past and active bookings, payment status, and service details.

### 🛠️ Service Provider Features
- **Provider Registration**: Register profile details and upload verification certificates.
- **Verification Status**: Account activation requires admin approval.
- **Booking Management**: View assigned bookings and update completion status.

### 🛡️ Admin Features
- **Provider Verification**: Review submitted certificates and approve or reject service providers.
- **Platform Analytics & Overviews**: Monitor all users, providers, bookings, and payment transactions.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask, PyMongo, Werkzeug, Gunicorn
- **Frontend**: HTML5, CSS3, JavaScript, Jinja2 Templates
- **Database**: MongoDB

---

## 📁 Project Structure

```text
smartserve/
│
├── backend/
│   ├── app.py               # Flask application & routes
│   ├── database.py          # MongoDB database connection & collections
│   ├── Procfile             # Deployment configuration
│   └── static/              # Static assets and uploaded certificates
│
├── frontend/
│   └── templates/           # Jinja2 HTML templates
│       ├── admin/           # Admin dashboard templates
│       ├── auth/            # Login and registration templates
│       ├── provider/        # Service provider templates
│       └── user/            # User templates
│
├── .gitignore               # Ignored files (cache, environments, etc.)
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ installed
- MongoDB installed and running locally on port `27017` (or configured connection string)

### Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/devikaks8843-source/Smartserve.git
   cd Smartserve
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python backend/app.py
   ```

5. **Access the App**:
   Open your browser and navigate to `http://127.0.0.1:5000`.

---

## 📝 License

This project is developed for educational and demonstration purposes.

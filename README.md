# 🌾 KisanX — D2C Agricultural Marketplace

> **Built by [Saniya Farooqui](https://www.saniya.me) — Co-Founder & Full-Stack Developer**
> 
> A live Direct-to-Consumer (D2C) agricultural marketplace connecting Indian farmers directly with buyers — eliminating middlemen and ensuring fair pricing for farmers.
>
> 🏆 **Selected at Avishkar Research Convention, University of Mumbai**

[![Portfolio](https://img.shields.io/badge/Portfolio-saniya.me-brightgreen?style=for-the-badge&logo=vercel)](https://www.saniya.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saniya%20Farooqui-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/saniya-farooqui-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-Saniya1207-black?style=for-the-badge&logo=github)](https://github.com/Saniya1207)

---

## 👩‍💻 About the Developer

**Saniya Farooqui** — Full-Stack Developer & Co-Founder of KisanX
- 🌐 Portfolio: [saniya.me](https://www.saniya.me)
- 💼 LinkedIn: [Saniya Farooqui](https://www.linkedin.com/in/saniya-farooqui-dev/)
- ✍️ DEV.to: [@saniya1207](https://dev.to/saniya1207)
- 📧 saniya122400@gmail.com

I conceptualised, designed and built KisanX as a full-stack web and mobile platform from the ground up — handling backend architecture (PHP + MySQL), frontend UI (HTML/CSS/JS), REST API design, farmer dashboard, cart system, order tracking, multi-language support, and the React Native mobile app.

---

## 🚀 What is KisanX?

KisanX is a **live, production-ready D2C agricultural marketplace** built to solve a real problem: Indian farmers lose 30–40% of their income to middlemen. KisanX lets farmers list their produce directly and sell to consumers — keeping profits where they belong.

**Live Features:**
- 🧑‍🌾 Farmer dashboard — list products, manage inventory, track sales
- 🛒 Consumer marketplace — browse, search, add to cart, checkout
- 📦 Order tracking system with real-time progress updates
- 🗣️ Multi-language support (English, Hindi, Marathi)
- 📍 Location-based product discovery
- 📰 Agri-news section for farmers
- 🔐 Secure authentication (register/login/logout)
- 📱 React Native mobile app (Android & iOS)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | PHP 8, MySQL |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Mobile** | React Native |
| **Database** | MySQL (relational schema for users, products, orders, cart) |
| **Auth** | PHP Sessions |
| **Language i18n** | Custom PHP i18n (English / Hindi / Marathi) |

---

## 📁 Project Structure

```
kisanX/
├── index.php              # Homepage — product listings
├── farmer_dashboard.php   # Farmer portal — manage listings
├── products.php           # Product catalogue
├── cart.php               # Shopping cart
├── checkout.php           # Order placement
├── my_orders.php          # Order history
├── order_details.php      # Single order view
├── track.php              # Live order tracking
├── register.php           # User registration
├── login.php              # Authentication
├── about.php              # Platform info
├── faq.php                # FAQ
├── news.php               # Agri news for farmers
├── db.php                 # Database connection
├── header.php / footer.php # Layout components
├── en.php / hi.php / mr.php # Language files (EN/HI/MR)
├── init.sql               # Database schema
└── style.css              # Global styles
```

---

## ⚙️ Local Setup

### Prerequisites
- PHP 8.0+
- MySQL 5.7+ or MariaDB
- Apache / XAMPP / WAMP / Laragon

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/Saniya1207/kisanX.git
cd kisanX

# 2. Import the database
mysql -u root -p < init.sql

# 3. Configure database connection
#    Edit db.php with your MySQL credentials

# 4. Start your local server (XAMPP / Laragon)
#    Place the project in your htdocs folder

# 5. Visit http://localhost/kisanX/
```

---

## 🏆 Recognition

**Avishkar Research Convention — University of Mumbai**
KisanX was selected and presented at Avishkar, the annual inter-university research competition organised by the University of Mumbai. Avishkar is one of the largest research festivals in India, covering science, technology, humanities, and social sciences.

---

## 🔗 More About This Project

Read the full technical breakdown on DEV Community:
📖 [How I Built KisanX — A Full-Stack Agricultural Marketplace](https://dev.to/saniya1207)

See it in my portfolio:
🌐 [saniya.me/#projects](https://www.saniya.me/#projects)

---

## 📄 License

This project is open-source. See individual file headers for details.

---

<p align="center">
  Built with ❤️ by <a href="https://www.saniya.me"><strong>Saniya Farooqui</strong></a> — Full-Stack Developer from Mumbai, India
</p>

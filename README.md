#  E-commerce Website using Django, MongoDB, Redis, Bootstrap

##  Objective

Build a fully functional e-commerce web application using Django, styled with Bootstrap, and powered by MongoDB


##  Technologies Used

| Layer        | Technology                 |
|--------------|----------------------------|
| Frontend     | HTML, CSS, Bootstrap       |
| Backend      | Python (Django)            |
| Database     | MongoDB (NoSQL via Djongo) |
| Session/Cache| Redis                      |
| Dev Tools    | PyCharm / VS Code, Postman, MongoDB Compass |


##  Setup Instructions

###  Clone the Repository
`bash`
`git clone <your-repo-url>
cd ecommerce`

##  Create a Virtual Environment & Activate

`bash`
`python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows`


##  Install Dependencies

`bash`
`pip install -r requirements.txt`

##  Run Migrations

`bash`
`python manage.py makemigrations
python manage.py migrate`

## Run the Development Server

`bash`
`python manage.py runserver`

## 🧾 Project Structure

ecommerce/
│
├── ecommerce/               "# **Project settings**"
├── store/                   "# **Main Django App**"


│   ├── models/
│   │   ├── category.py
│   │   ├── product.py
│   │   ├── customer.py
│   │   └── order.py


│   ├── views/
│   │   ├── home.py
│   │   ├── login.py
│   │   ├── signup.py
│   │   ├── cart.py
│   │   ├── checkout.py
│   │   └── orders.py


│   ├── templates/
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── signup.html
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   └── orders.html


│   └── admin.py

├── manage.py
└── requirements.txt

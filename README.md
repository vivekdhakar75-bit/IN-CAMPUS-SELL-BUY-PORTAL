
# IN CAMPUS SELL & BUY PORTAL

### A Web-Based Marketplace for Students

## Project Description

IN CAMPUS SELL & BUY PORTAL, also known as CampusCart, is a web-based marketplace developed to connect buyers and sellers within a university campus.

The platform allows students to buy and sell academic books, electronics, furniture, accessories and other useful products through a common online platform.

## Project Team

- Vivek Dhakar (BETN1CS23085)
- Agam Singh Kalra (BETN1CS23107)
- Yatendra Dhakar (BETN1CS23149)

## Project Guidance

**Guide:** Dr. Jyoti Bala Kaundal  
Assistant Professor of Physics

**Co-Guide:** Dr. Nidhi Dandotiya  
Associate Professor

## Technologies Used

- Python
- Flask
- HTML5
- CSS3
- SQLite
- Jinja2
- Werkzeug

## Main Features

1. Student Registration and Login
2. Student Dashboard
3. Product Upload with Images
4. Browse Available Products
5. Search Products
6. Product Details
7. Seller Contact Information
8. My Listings
9. Edit and Delete Products
10. Mark Products as Sold

## Project Structure

```text
campuscart_project/
│
├── app.py
├── campuscart.db
├── requirements.txt
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   ├── dashboard.html
│   ├── products.html
│   ├── product_details.html
│   ├── sell.html
│   ├── my_listings.html
│   └── edit_product.html
│
└── static/
    ├── css/
    │   └── style.css
    └── uploads/
```

## Installation and Execution

1. Download or clone this repository.
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Start the Flask application:

```bash
python app.py
```

4. Open the following address in your browser:

```text
http://127.0.0.1:5000/
```

The SQLite database is created automatically when the application starts.

## Database

The application uses SQLite with two main tables:

- Users: Stores student account information.
- Products: Stores product details, prices, categories and image filenames.

## Development Environment

Google Colab

## Project Purpose

To provide students with a simple, organised and accessible platform for buying and selling products within their university campus.

## Future Enhancements

- University email verification
- Online payment integration
- Real-time student communication
- Product ratings and reviews
- Administrator dashboard
- Permanent cloud deployment


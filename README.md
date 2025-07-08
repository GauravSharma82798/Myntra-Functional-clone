# Myntra-Functional-clone
A static front-end clone of the popular Indian e-commerce platform Myntra, built using HTML, CSS, and JavaScript. This project aims to simulate a functional user experience for browsing products, adding them to a shopping bag, and viewing pricing details — just like the real Myntra website.
# Feature
.Homepage with Navbar
Browse across categories like Men, Women, Kids, and more.

->Product Listing Page
Displays products dynamically from JavaScript data including:

.Brand name

.Product title

.Prices (MRP, discounted)

.Discount %

.User rating and review count

->Shopping Bag Page

.Add/remove items from the bag (using localStorage)

.View total MRP, discount, convenience fee

.Calculate total payable amount

.Responsive styling and real-time UI updates
# Tech Stack
.HTML – Page structure and layout

.CSS – Custom styles for layout, components, and responsiveness

.JavaScript (Vanilla) – DOM manipulation, dynamic product rendering, localStorage management

# How it Works
.On load, items are rendered dynamically from items.js.

.Clicking "Add to Bag" stores item ID in localStorage.

.The Bag icon updates with the count of items added.

.Bag page (pages/bag.html) retrieves those IDs and calculates:

.Total MRP

.Total discount

.Convenience fee

.Final payable amount

# Limitations
.Static Only – No backend integration (no login, payment, or real checkout)

.Not mobile-optimized – Best viewed on desktop/laptop

.Hardcoded Data – Product details are not fetched from an API

# Credits
Project inspired by the real Myntra UI/UX.
Built as a practice project to improve front-end skills.


# D-ryno - Premium Clothing Brand

D-ryno is a Premium Clothing Brand that sells minimalistic styled comfortable clothing for men and women. An E-commerce website that allows users to buy products from the brand like Nike and Puma.

## Objectives
An E-commerce website that allows users to buy products from the brand like Nike and Puma.

## Frontend

### Tech Stack
* NextJS
* TailwindCSS
* TypeScript
* React Icons
* Lucide React
* Framer Motion
* Functional Styling Components used by Acertinity UI

### Frontend Explained
*(Keep responsive in mind for mobile, tablet, and desktop viewports)*

#### Mode
* Dark Mode (Default)
* Light Mode

#### Landing Page (/)
* Navbar
  * Logo (Left) (For now, Name: D-ryno)
  * Middle: Links (Shop, About, Contact, Other Categories and Pages)
  * Right: Search Icon (Dropdown Search Bar), Cart Icon (Side Cart Bar on-click)
  * Mobile View: Hamburger Menu Icon (Side Navigation Bar on-click) along with search icon and cart icon
* Hero Section
* Recent Products
* Offer Collection Catalogs
* Offer Banner Section
* Offer Banner 2 Section
* Newsletter Section
* Footer Section
  * Column 1: Logo, Company Name, Address
  * Column 2: Links pages
  * Column 3: Site Pages (Privacy Policy, Terms of Service, Return Policy, FAQ, Contact Us, About Us)
  * Column 4: Social Media Links (Facebook, Instagram, Twitter, LinkedIn, Pinterest, YouTube)
* Copyright Section

#### Products Page (/shop)
* Left under header: Sidebar Filter Section
  * Gender
  * Categories
  * Price Range
  * Color
  * Size
  * Sorting
  * Tags
  * Miscellaneous
* Right Under Header: Title of Page like Products or Category Name or Tag Name or Search Results
* Under Title: Grid of Products
  * 15 Products per page
  * 3 rows
  * Cards: Image with a Tag, Name, Price, Category
* Under Grid: Pagination
  * 1, 2, 3, 4, 5
  * Current Page: 1
  * Next Page, Previous Page

#### Product Details Page (/product/:id)
* Top Left: All Images Gallery in Vertical to select the image, and Main Image aside
* Top Right:
  * Title
  * Price
  * Quantity
  * Variants
  * Add to Cart Button
  * Add to Wishlist Button
  * Share Button
* Under Right: Additional Information (Size, Color, Material, Care, etc.) in Accordion Format
* Bottom: Description, Specifications, Related Products

#### Cart Page (/cart)
* Left: Added Products with
  * Image
  * Name
  * Price
  * Quantity
  * Total Price
  * Remove Button
* Right: Summary of Order with
  * Subtotal
  * Shipping
  * Tax
  * Total Price with Checkout Button

#### Checkout Page (/checkout)
* Later for Payment gateway integration
* Right now:
  * Address Form
  * Shipping Method
  * Payment Method
  * Order Summary
* Then: Place Order Button

#### Order Confirmation Page (/order-confirmation/:id)
* Top: Green Checkmark Icon, Order Placed Successfully
* Left: Order Details with
  * Order ID
  * Date
  * Time
  * Total Price
  * Payment Method
  * Shipping Method
  * Address
* Right: Order Items with
  * Image
  * Name
  * Price
  * Quantity
  * Total Price

#### Account Page (/account)
* Section 1: Top: Account Information with Profile Picture, Name, Email, My Orders and Wishlist Button
* Section 2:
  * Left: Sidebar with Options (Orders, Inbox, Addresses, Notifications, Settings)
  * Right: Content Section (If Empty, Show Message to Buy Something with search bar and button)

------ Rest Components will be added later ------











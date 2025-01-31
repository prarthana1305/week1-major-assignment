# AI Recruitment Platform - CSS Breakdown

##  Overview
This project is a **responsive AI recruitment platform** built using **HTML & CSS**.  
It includes a structured layout for **navigation, hero section, features, benefits, testimonials, partners, contact, and footer**.


##  CSS Structure

### **Global Styles (`body`, `fonts`, `colors`)**
- Imported **Google Fonts**: `Inter`, `Poppins`, `Lato`, `DM Sans` for a modern look.
- Applied `display: flex; flex-direction: column; align-items: center;` to **center the page content**.
- Set `background-color: #f8f9fa;` for a **clean, professional look**.

---

### **Header & Navigation (`.header`, `.navbar`)**
- **Fixed Position** (`position: fixed; top: 0; left: 0;`) ensures it remains **visible on scroll**.
- **Flexbox Layout** (`display: flex; justify-content: center; align-items: center;`) aligns navigation items horizontally.
- **Spacing & Gaps** (`gap: 60px; padding-right: 460px;`) for evenly spaced navigation links.

---

### ** Hero Section (`.content-wrapper`)**
- **Text Styling**
  - `font-size: 36px; font-weight: bold; color: #222;` for title emphasis.
  - `background: #f0f5ff; box-shadow: 0 4px 10px rgba(0, 0, 255, 0.2);` for a standout tagline.
- **Buttons**
  - `.explore-btn` and `.talent-btn` have **hover effects** (`background-color: #4CAF50; transition: 0.3s ease-in-out;`).
- **Image Styling**
  - `.image-container` uses `position: relative; text-align: center;` for **centering images and overlays**.

---

### **Features Section (`.feature-container`)**
- **Grid Layout** (`display: flex; justify-content: center;`) to align feature cards.
- **Feature Box Styling**
  - `border-radius: 16px; padding: 16px;` for **modern rounded cards**.
  - `text-align: center;` for **proper content alignment**.

---

### **Benefits Section (`.benefits-section`)**
- **Two-Column Layout**
  - Left: **Title & CTA Button**
  - Right: **List of Benefits with Icons**
- **Gradient Background**
  - `background: linear-gradient(92.69deg, rgba(255, 255, 255, 0.075) 6.01%, rgba(255, 255, 255, 0.175) 90.83%);`
- **Icons**
  - Wrapped in `.icon-container` with `backdrop-filter: blur(12px);`.

---

### ** Testimonials Section (`.testimonial-wrapper`)**
- **Scrolling Animation**
  - `animation: scroll 30s linear infinite;` enables **auto-scrolling testimonials**.
  - Hovering **pauses the scrolling** (`animation-play-state: paused;`).
- **Testimonial Cards**
  - `box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);` for a **soft shadow effect**.

---

### **Partner Logos (`.partner-container`)**
- **Flexbox for Grid Layout**
  - `display: flex; flex-wrap: wrap; gap: 20px;` aligns partner logos **evenly**.
- **Image Styling**
  - `object-fit: contain; width: 187px; height: 48px;` for **consistent logo sizes**.

---

### **Contact Form (`.contact-form`)**
- **Form Styling**
  - `border-bottom: 2px solid #1F64FF;` for **underline input fields**.
  - `background: #fff; border-radius: 8px;` for a **clean form layout**.
- **Submit Button**
  - `.send-message-btn` has **hover effects** and **smooth color transitions**.

---

### **Footer (`.footer-section`)**
- **Structured Layout**
  - `.footer-text-container` uses **flexbox for organized links**.
  - `.footer-bottom` aligns **copyright text centrally**.
- **Social Media Icons**
  - `transform: scale(1.1);` enlarges **icons on hover**.

---

## **Responsive Design (`@media`)**
- Applied `@media (max-width: 1024px)`**:
  - **Navigation & Footer:** Items **stack vertically**.
  - **Forms & Features:** Adjusted **padding & alignment**.
  - **Images:** `max-width: 100%;` for **better scalability**.

---

##  **Key Features**
**Fully Responsive Design**  
**Modern UI with Flexbox**  
**Smooth Hover Effects & Animations**  
**Optimized for Performance & Readability**  

---




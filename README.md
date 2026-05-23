# Travel-booking-website
A modern travel booking website built using HTML and CSS with destination cards, booking forms, tables and responsive design.

# TravelX ✈️🌍

A modern travel booking website built using HTML and CSS featuring destination cards, booking forms, tour packages, contact section and responsive design.

---

# Features

- Sticky navigation bar
- Hero section
- Destination cards
- Travel package table
- Booking form
- Contact section
- Responsive layout
- Hover effects
- Modern travel UI

---

# Technologies Used

- HTML5
- CSS3

---

# Folder Structure

```text
TravelBookingWebsite/
│
├── travel.html
├── README.md
```

---

# How To Run

Step 1:

Download or clone project

Step 2:

Open project folder

Step 3:

Open:

```text
travel.html
```

using:

- Chrome
- Edge
- Firefox

Website runs directly in browser.

---

# Project Structure

## Header + Navigation

```html
<header>

<nav>

Home
Destinations
Bookings
Contact

</nav>

</header>
```

Purpose:

Navigation helps users move through sections.

Concept learned:

```css
position:sticky;
top:0;
```

Sticky navbar remains visible while scrolling.

---

# Hero Section

Hero section is the first large section of website.

Contains:

- Website title
- Travel slogan
- Banner image
- Description
- Buttons

Example:

```text
Meenish Travel Booking Website

Explore • Dream • Travel

Image

Buttons
```

Most modern websites use Hero sections.

---

# Destination Cards

Example:

```html
<div class="destination-card">

Image

Goa

Beach destination

₹8999

Book Now

</div>
```

Purpose:

Cards organize travel places.

Concept learned:

```css
display:grid;
```

Grid automatically aligns cards.

---

# Grid Concept

```css
.destination-grid{

display:grid;

grid-template-columns:
repeat(auto-fit,minmax(250px,1fr));

}
```

Purpose:

Automatically adjusts card layout.

Creates:

```text
□ □ □

□ □ □
```

instead of messy layouts.

---

# Hover Effect

```css
.destination-card:hover{

transform:translateY(-10px);

}
```

Purpose:

Cards move slightly upward.

Makes website interactive.

---

# Booking Form

Form fields:

- Package Selection
- Full Name
- Email
- Travel Date
- Number of People
- Additional Requests

Concepts used:

```html
<input>

<select>

<textarea>
```

Purpose:

Collect booking information.

---

# Table Section

Package table:

```html
<table>
```

Columns:

- Package
- Days
- Price

Purpose:

Shows available travel plans.

---

# CSS Concepts Learned

margin

Space outside elements

padding

Space inside elements

border-radius

Rounded corners

display:flex

Creates row/column layouts

display:grid

Creates card layouts

position:sticky

Sticky navbar

object-fit:cover

Prevents image stretching

hover

Interactive effects

---

# Mistakes I Fixed

Wrong image URL

Example:

```html
photo-1506744038136-462>73834
```

Extra symbols break image loading.

Corrected image paths.

Avoided inline styling:

Wrong:

```html
<button style="">
```

Better:

```html
<button class="submit">
```

Use CSS classes.

---

# Areas I Need To Improve

- CSS Grid mastery
- Responsive design
- Better layouts
- JavaScript
- UI thinking

---

# Future Improvements

- Search destinations
- Add dark/light mode
- Add payment page
- Add login system
- Add JavaScript validation

---

# What I Learned

Through this project I practiced:

- Hero sections
- Navigation bars
- Cards
- Forms
- Tables
- CSS Grid
- Layout structure
- Better naming conventions

---
#Note 
Add your own images 

# Author

Meenish

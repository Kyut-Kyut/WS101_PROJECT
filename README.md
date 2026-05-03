# Sira-an Hot Spring — Tourism Website

## Designer
**Mary Artheal S. Seduco – BSIT 3B**

---

## URL / Domain

[https://ws-101-project-livid.vercel.app/](https://ws-101-project-livid.vercel.app/)

---

## Framework Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **Tailwind CSS** (CDN) | Utility-first styling and responsive layout |
| **Vanilla JavaScript** | Interactivity, animations, and dynamic behavior |
| **Google Fonts** | Typography — Playfair Display, DM Sans, Inter |
| **Google Maps Embed API** | Location map on the Visit page |
| **VS Code + Live Server** | Development environment and local preview |

---

## Short Overview

The **Sira-an Hot Spring** website is a multi-page tourism website that promotes and provides information about Sira-an Hot Spring Resort, a natural geothermal coastal retreat located in Brgy. Nato, Anini-y, Antique, Philippines. The website serves as a digital front for the resort, allowing visitors to explore the resort's features, view accommodations, browse a photo gallery, and submit a booking inquiry. It consists of seven pages — **Home, About, Experience, Gallery, Stay, Visit,** and **Book Now** — each designed with a consistent dark coastal aesthetic using deep teal and gold tones. The site includes interactive features such as a typewriter text animation across hero sections, a photo modal system for feature and room cards, a filterable image gallery with lightbox, and a booking inquiry form with a success popup.

---

## Pages & Features

### Home (`index.html`)
- Full-screen hero section with a background image and call-to-action buttons
- Four clickable feature cards (Hot Springs, Ocean Views, Sunsets, Accommodation) that open an image modal with photo thumbnails, descriptions, and highlights

### About (`about.html`)
- Hero section with a typewriter animation cycling through resort facts
- Overlapping image layout and resort statistics (pools, temperature, attractions, days open)

### Experience (`experience.html`)
- Hero section with a typewriter animation about the hot spring experience
- Three experience cards covering Natural Hot Springs, Ocean Views, and Sunset Soaking
- A full-width photo banner section

### Gallery (`gallery.html`)
- Filterable photo grid with category buttons (All, Pools, Views, Sunsets, Rooms)
- Lightbox modal for full-size image viewing with navigation

### Stay (`stay.html`)
- Hero section with a typewriter animation about accommodations
- Three clickable room cards (Standard Twin, Deluxe Double, Family Triple) with image zoom on hover and a room detail modal showing photos, amenities, pricing, and a Book Now button

### Visit (`visit.html`)
- Hero section with a typewriter animation about visiting the resort
- Travel directions, operating hours, entrance fee, and location details alongside a Google Maps embed
- Five clickable "Explore Nearby" attraction cards (Nogas Island, Punta Nasog, Baroque Church, Mt. Aliw-Liw, Tampada Beach) each opening a photo modal with descriptions and highlights

### Book Now (`booknow.html`)
- Inquiry form with full name, email, check-in date (auto-filled to today), guest count, and room type selection
- Success popup summarizing the submitted inquiry details

---

## Use of AI Tools

AI tools played a significant role in the development of this project, particularly in building and refining the user interface and writing clean, functional code.

### Claude (Anthropic)
Claude AI was the primary AI assistant used throughout the development of this website. It was used to:
- **Generate and debug HTML, CSS, and JavaScript** code for all seven pages
- **Build interactive features** including the typewriter animation, photo modals with thumbnail switching, the booking form popup, and the filterable gallery
- **Implement the nearby attractions modal system** in the Visit page, mapping real resort images to each location
- **Refine UI design decisions** such as card layout centering, hover effects, placeholder hint styling for form fields, and consistent header patterns across pages
- **Write and improve page content** including attraction descriptions, room highlights, and typewriter phrases tailored to each page's context

### Gemini (Google)
Gemini was used as a supplementary reference tool to:
- **Research information** about the nearby tourist attractions (Nogas Island, Punta Nasog, Baroque Church, Mt. Aliw-Liw, Le Grande Bayo) including historical and geographical details used in the modal descriptions
- **Brainstorm content ideas** for page copy and visitor-facing text
- **Cross-check travel and location details** such as directions from Iloilo City and operating hour conventions for resort websites

---

## Project Structure

```
Siraan_HotSpring/
├── html/
│   ├── index.html          # Home page
│   ├── about.html          # About the resort
│   ├── experience.html     # Experience highlights
│   ├── gallery.html        # Photo gallery with filter
│   ├── stay.html           # Room accommodations
│   ├── visit.html          # Directions & nearby attractions
│   └── booknow.html        # Booking inquiry form
├── images/
│   └── (all .webp photos)  # Resort, rooms, nature, and nearby places
├── css/
│   └── style.css           # Shared styles (home hero, feature cards)
└── README.md
```

---

## Location

**Brgy. Nato, Anini-y, Antique 5717, Philippines**

> *A natural geothermal coastal retreat — where the Earth breathes warmth.*

# QR Code Generator Studio

A full-featured, high-performance QR Code Generator web application built for modern digital workflows and print-ready distribution.  
Designed with a sleek utility workspace aesthetic, the application provides advanced QR customization, batch generation, vector exports, and offline template management — all fully client-side with zero backend dependency.

---

# ✨ Features

## 🎨 Adaptive Styling Studio

Deep QR appearance customization with multiple rendering systems:

- Classic square modules
- Sphere / circular dot modules
- Organic smooth nodes
- Heavy pill styles
- Custom eye borders:
  - Rounded
  - Circular
  - Leaf-point styles
- Unified linear & radial gradients
- Transparent background support
- Fine-grained spacing and scaling controls

---

## 🛡️ Emblem Overlay & Smart Protection Masking

Safely embed logos directly into QR codes without compromising scan reliability.

### Supported Upload Formats

- PNG
- SVG
- JPG / JPEG

### Built-In Emblems

- Website
- Email
- Wi-Fi
- Phone
- Social actions

### Smart Rendering Engine

The renderer dynamically calculates center-grid masking zones to:

- Prevent data modules from bleeding through transparent logos
- Preserve QR scan integrity
- Maintain high correction reliability

---

# ⚡ Form Payload Formatters

Built-in quick generators for common QR actions.

## Website Links

Automatically formats valid URL payloads.

## Wi-Fi Login Cards

Generate auto-connect QR codes using:

- SSID
- Password
- Security type

## Email Templates

Pre-populated:

- Recipient
- Subject
- Body

## Phone Dialer Actions

Instant call QR generation.

---

# 🖨️ High-DPI Multi-Format Export System

Professional export pipeline optimized for both digital and print production.

## PNG Export

Supports:

- 512px
- 1024px
- 2048px
- 4096px print-density rendering

Includes transparent canvas export support.

## SVG Export

Pure vector path output with:

- Embedded gradients
- Infinite scaling
- Print-safe vector rendering

## PDF Export

Print-ready flyer generation using jsPDF:

- 105mm × 105mm layouts
- High-resolution embedded QR rendering
- Professional print formatting

---

# 📦 High-Volume Batch Compression Engine

Bulk-generate hundreds of QR codes simultaneously.

## Features

- CSV row parsing
- Parallel generation
- Background-thread rendering
- Structured ZIP packaging via JSZip
- Auto-labeled outputs
- Off-screen canvas optimization

Ideal for:

- Marketing campaigns
- Inventory systems
- Event management
- Product labeling

---

# 💾 Offline-First Template Vault

Persistent browser-based workspace backups using localStorage.

## Vault Features

- Save custom templates
- Import/export configurations
- JSON workspace backups
- Restore previous design presets
- Fully offline capable

---

# 🎨 Sleek Interface Theme

The application has been fully redesigned with the **Sleek Interface** theme.

## Design Language

- Minimal light workspace
- Indigo accent palette
- Slate-gray controls
- Soft shadows & layered surfaces
- High readability spacing
- Modern rounded UI components

## Typography Stack

- **Space Grotesk** → Display headings
- **Inter** → UI controls & forms
- **JetBrains Mono** → Metrics & technical displays

---

# 🧩 Tech Stack

## Frontend

- React
- TypeScript
- Vite

## Rendering & Utilities

- QR rendering engine
- jsPDF
- JSZip
- LocalStorage APIs
- Canvas rendering APIs

---

# 🚀 Getting Started

## 1. Install Dependencies

```bash
npm install
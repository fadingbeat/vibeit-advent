# 📅 VibeIT Tech Advent Calendar

## ✨ Project Title: VibeIT Winter Code Fest

A fun, interactive Advent Calendar built for the tech community to share valuable developer tools, libraries, and resources throughout December. Each day unlocks a new, curated "gift" to discover!

**Live Demo:** [https://vibeit-advent.vercel.app](https://vibeit-advent.vercel.app)

## 💡 Concept

This project transforms the traditional December Advent Calendar into a knowledge-sharing platform. Instead of chocolate or toys, each virtual "house" reveals a hidden link to a great, free technical tool, library, or resource used and recommended by the VibeIT team. It's digital gift-giving for developers!

## ⚙️ Key Features

- **Date-Based Unlocking:** Only the current day's house (and previous days) can be opened, maintaining the traditional Advent experience.
- **3D Interactive Doors:** Clicking a house triggers a smooth 3D flip animation, revealing the tool's name and a link to its website.
- **Cyber-Winter Aesthetic:** The design uses the VibeIT brand colors (`#151127`, `#AC3347`, `#A1C2CD`) combined with a custom snowfall particle effect for an immersive, festive, and tech-friendly look.
- **Persistent State:** Uses `localStorage` to remember which houses the user has already opened.
- **Responsive Design:** Optimized for mobile, tablet, and desktop viewing.

## 🛠️ Technology Stack

This is a pure, single-file static application for maximum speed and simplicity.

- **HTML5**
- **CSS3 (Tailwind CSS)** for responsive styling and aesthetics.
- **JavaScript (Vanilla JS)** for the calendar logic, date checking, persistence, and snowfall effects.
- **FontAwesome** for the tech icons.

## 🚀 Getting Started

Since this is a single static HTML file, deployment is exceptionally fast, especially using Vercel.

### Deployment (Recommended Method)

The fastest way is to deploy it as a Standalone Static Project on Vercel:

1.  **Initialize Git:** Create a new local repository containing only the `index.html` file.
2.  **Push to GitHub/GitLab:** Push the repository to your chosen Git provider.
3.  **Deploy on Vercel:**

    - Log into Vercel and import the new repository.
    - Vercel will automatically detect it as a **Static** project.
    - Click **"Deploy."**

Your site will be live within seconds!

### Customizing the Links

All the content (the tool names, descriptions, icons, and URLs) is defined within the `<script>` tag in `index.html`.

To customize your calendar, find the `const adventData` array (around line 200) and modify the objects:

    const adventData = [
        { day: 1, title: "Next.js", icon: "fa-brands fa-react", url: "https://nextjs.org", desc: "The React Framework" },
        { day: 2, title: "Tailwind", icon: "fa-brands fa-css3-alt", url: "https://tailwindcss.com", desc: "Utility-first CSS" },
        // ... continue for days 3 to 24
    ];

Made with ❤️ by [VibeIT](https://www.vibeit.hr/en)

# Social-UI-Button

<p>
  🚀 Follow <a href="https://www.instagram.com/wearepixelflow/" target="_blank"><strong>@wearepixelflow</strong></a> on Instagram for more premium UI animations and web development content.
</p>

<img width="320" height="270" alt="CuteGIF" src="https://github.com/user-attachments/assets/f98be517-08ed-4493-8721-7a1e0db1dd9a" />


# Social Flip Button

A modern **3D Social Flip Button** built with **React**, **Framer Motion**, **Tailwind CSS**, and **React Icons**. Each button displays a letter on the front and smoothly flips to reveal its corresponding social media icon when hovered. The component also features animated tooltips and subtle border animations for a premium UI experience.

## ✨ Features

* 🎴 Smooth 3D flip animation
* 🚀 Built with Framer Motion
* 🎨 Tailwind CSS styling
* 💬 Animated tooltips
* 🌙 Light & Dark mode support
* ⚡ Sequential hover animation
* 🔗 Supports links and custom click handlers
* 🧩 Easily customizable
* 📱 Responsive design

---

## Preview

👉 <a href="https://www.instagram.com/p/DaNP_nlB_Fi/" target="_blank">
   Click here 
</a>
to watch the animation
---

## Technologies Used

* React
* TypeScript
* Framer Motion
* Tailwind CSS
* React Icons

---

## Installation

Clone the repository:

```bash
git clone https://github.com/wearepixelflow/social-cta.git
```

Navigate into the project:

```bash
cd social-flip-button
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

---

## Dependencies

```bash
npm install framer-motion react-icons
```

---

## Folder Structure

```
src/
│
├── components/
│   └── SocialFlipButton.tsx
│
├── lib/
│   └── utils.ts
│
└── app/
    └── page.tsx
```

---

## Usage

Import the component:

```tsx
import SocialFlipButton from "@/components/SocialFlipButton";
```

Render it:

```tsx
<SocialFlipButton />
```

---

## Custom Buttons

You can provide your own social items.

```tsx
const items = [
  {
    letter: "G",
    icon: <FaGithub />,
    label: "GitHub",
    href: "https://github.com",
  },
  {
    letter: "X",
    icon: <FaTwitter />,
    label: "Twitter",
    href: "https://twitter.com",
  },
];

<SocialFlipButton items={items} />;
```

---

## Props

| Prop             | Type           | Description               |
| ---------------- | -------------- | ------------------------- |
| `items`          | `SocialItem[]` | Custom social buttons     |
| `className`      | `string`       | Wrapper styling           |
| `itemClassName`  | `string`       | Individual button styling |
| `frontClassName` | `string`       | Front face customization  |
| `backClassName`  | `string`       | Back face customization   |

---

## Customization

You can easily customize:

* Colors
* Border radius
* Animation speed
* Spring physics
* Tooltip style
* Icons
* Labels
* Container spacing
* Button size
* Hover delay

---

## Built With

* **React**
* **TypeScript**
* **Framer Motion**
* **Tailwind CSS**
* **React Icons**

---



## Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---


## Author

Made by Pixelflow with ❤️ for developers who love creating beautiful UI interactions.

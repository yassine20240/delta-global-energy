  
/* Fonts */
:root {
  --default-font: "Roboto",  system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", "Liberation Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --heading-font: "Raleway",  sans-serif;
  --nav-font: "Poppins",  sans-serif;
}

/* Global Colors - The following color variables are used throughout the website. Updating them here will change the color scheme of the entire website */
:root { 
  --background-color: #ffffff; /* Background color for the entire website, including individual sections */
  --default-color: #444444; /* Default color used for the majority of the text content across the entire website */
  --heading-color: #111111; /* Color for headings, subheadings and title throughout the website */
  --accent-color: #e03a3c; /* Accent color that represents your brand on the website. It's used for buttons, links, and other elements that need to stand out */
  --surface-color: #ffffff; /* The surface color is used as a background of boxed elements within sections, such as cards, icon boxes, or other elements that require a visual separation from the global background. */
  --contrast-color: #ffffff; /* Contrast color for text, ensuring readability against backgrounds of accent, heading, or default colors. */
}

/* Nav Menu Colors - The following color variables are used specifically for the navigation menu. They are separate from the global colors to allow for more customization options */
:root {
  --nav-color: #212529;  /* The default color of the main navmenu links */
  --nav-hover-color: #e03a3c; /* Applied to main navmenu links when they are hovered over or active */
  --nav-mobile-background-color: #ffffff; /* Used as the background color for mobile navigation menu */
  --nav-dropdown-background-color: #ffffff; /* Used as the background color for dropdown items that appear when hovering over primary navigation items */
  --nav-dropdown-color: #212529; /* Used for navigation links of the dropdown items in the navigation menu. */
  --nav-dropdown-hover-color: #e03a3c; /* Similar to --nav-hover-color, this color is applied to dropdown navigation links when they are hovered over. */
}

/* Color Presets - These classes override global colors when applied to any section or element, providing reuse of the sam color scheme. */

.light-background {
  --background-color: #f9f9f9;
  --surface-color: #ffffff;
}

.dark-background {
  --background-color: #1b1b1b;
  --default-color: #ffffff;
  --heading-color: #ffffff;
  --surface-color: #353535;
  --contrast-color: #ffffff;
}

/* Smooth scroll */
:root {
  scroll-behavior: smooth;
}
--------------------------------------------------------------

 /* ================================
   Fonts
================================ */
:root {
  --default-font: "Inter", system-ui, -apple-system, "Segoe UI",
    "Helvetica Neue", Arial, sans-serif;

  --heading-font: "Montserrat", sans-serif;
  --nav-font: "Poppins", sans-serif;
}

/* ================================
   Global Colors (Brand Identity)
================================ */
:root {
  --background-color: #ffffff;        /* Main background */
  --default-color: #475569;           /* Body text */
  --heading-color: #0f172a;           /* Dark Navy headings */
  --accent-color: #0b3c5d;            /* Navy Blue (Primary brand color) */
  --surface-color: #ffffff;           /* Cards, boxes */
  --contrast-color: #ffffff;          /* Text on dark / accent */
}

/* ================================
   Secondary Accent (optional)
   Use manually in buttons/icons
================================ */
:root {
  --accent-secondary: #0ea5a4;         /* Teal (Data / Maritime tech) */
}

/* ================================
   Navigation Menu Colors
================================ */
:root {
  --nav-color: #0f172a;                /* Menu links */
  --nav-hover-color: #0ea5a4;          /* Hover / Active */
  --nav-mobile-background-color: #ffffff;
  --nav-dropdown-background-color: #ffffff;
  --nav-dropdown-color: #0f172a;
  --nav-dropdown-hover-color: #0ea5a4;
}

/* ================================
   Background Presets
================================ */

/* Light sections */
.light-background {
  --background-color: #f8fafc;
  --surface-color: #ffffff;
}

/* Dark / Maritime sections */
.dark-background {
  --background-color: #0f172a;         /* Deep Navy */
  --default-color: #e5e7eb;
  --heading-color: #ffffff;
  --surface-color: #1e293b;
  --contrast-color: #ffffff;
}

/* ================================
   Utility Accent Classes
================================ */

/* Primary CTA */
.btn-accent {
  background-color: var(--accent-color);
  color: var(--contrast-color);
}

/* Secondary CTA */
.btn-accent-secondary {
  background-color: var(--accent-secondary);
  color: #ffffff;
}

/* Accent text */
.text-accent {
  color: var(--accent-color);
}

.text-accent-secondary {
  color: var(--accent-secondary);
}

/* ================================
   Smooth Scroll
================================ */
:root {
  scroll-behavior: smooth;
}

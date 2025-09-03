# VerifyNow Website — SaaS Demo

This repository contains a five-page static website for the VerifyNow SaaS product (email verification API with OTP).

Pages included:
- index.html (Home)
- pricing.html (Pricing)
- api.html (API Documentation)
- contact.html (Contact)
- login.html (Login)

Technical notes and how-to:
- Theme: dark, neon blue accents (#0ea5e9 / #22d3ee) for a tech-focused aesthetic.
- Layout: consistent header and footer across pages; mobile-responsive navigation with a hamburger menu.
- Hero & sections: scroll-triggered subtle animations using lightweight intersection observers.
- Placeholder data:
  - Location: Hyderabad, India, used for address placeholders on the contact page.
  - PayPal integration: default integration path implied by the site; this template does not implement actual payments but provides a consistent pattern for integration.
- Accessibility: semantic HTML, alt attributes for images, ARIA labels on navigation and modals.
- Content: substantial, industry-specific text for a SaaS product focusing on email verification and OTP delivery.

How to run locally:
- Open the HTML files directly in a browser. No server is required for the static version.
- If you want to enable a local dev server, you can serve the folder with a simple static server (e.g., via Python's http.server or similar).

Notes on customization:
- Replace placeholder images with actual assets as needed.
- Update placeholder fonts by replacing the {{font: Font Name}} token; server-side processing will replace with a Google Font URL.
- Update placeholder image URLs using the https://images.unsplash.com/photo-1683193063549-b8a50825cbc0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw3fHwuLi58ZW58MHwwfHx8MTc1NjgxMzYyNHww&ixlib=rb-4.1.0&q=80&w=1080 format; server-side processing should inject actual assets.

End of README.
# Development Team Templates

This repository serves as a centralized collection of frontend templates and boilerplates for the development team. 

**Goal:** To accelerate project initialization, standardize our project structures, and share best practices across the team.

## 🎯 Purpose

- **Quick Start:** Reduce setup time for new projects by providing ready-to-use starting points.
- **Flexibility:** While primarily focused on frontend technologies (React, Next.js, Vue, etc.), this repository welcomes any template useful for our development workflow (e.g., configurations, scripts, backend starters).
- **Collaboration:** A shared space for the team to contribute and improve our foundational tools.

## 📂 Available Templates

| Template Name | Description | Path |
| :--- | :--- | :--- |
| **Next.js Admin Dashboard** | A modern admin dashboard template built with **Next.js 14+** and **Tailwind CSS**. Features a responsive layout, sidebar navigation, dark/light mode support, and essential UI components. Ideal for building internal tools or SaaS dashboards. | [`./nextjs-tailwind-admin`](./nextjs-tailwind-admin) |

## 🚀 Usage

To use a template, clone this repository and copy the desired template folder to your new project location.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sparkfn/templates_nextjs.git
   ```

2. **Copy the specific template:**
   ```bash
   # Example: Using the Next.js Admin template
   cp -r templates_nextjs/nextjs-tailwind-admin ./my-new-project
   
   # Navigate to your new project
   cd my-new-project
   
   # Install dependencies
   npm install
   # or
   yarn install
   ```

## 🤝 Contributing

We encourage everyone to add useful templates!

1. **Add your template:** Create a new folder in the root directory with a descriptive name (e.g., `vue-landing-page`, `express-api-starter`).
2. **Document it:** Ensure your template has its own local `README.md` explaining how to install, run, and build it.
3. **Update the Index:** Add your new template to the "Available Templates" table in this main `README.md`.
4. **Submit a PR:** Push your changes and open a Pull Request for review.

---
*Maintained by the SparkFn Development Team.*

Your EnergyYour Energy is a modern, responsive Single Page Application (SPA) designed for fitness enthusiasts to discover exercises, filter them by muscle groups or equipment, and manage their personal favorites. 

Built with a focus on performance and accessibility, the application provides a seamless experience for tracking daily fitness goals.

Features
1. Dynamic Exercise Catalog Filterable Categories: Browse exercises by Muscles, Body Parts, or Equipment. Search Functionality: Find specific exercises using keywords.Server-side Pagination: Efficiently navigate through large sets of data.
2. Interactive ModalsDetailed View: Access complete exercise info, including descriptions, burned calories, and video demonstrations.Rating System: Rate exercises via a dedicated modal with built-in email validation.Favorites Management: Add or remove exercises from your personal list with one click.
3. Personal Favorites PageA dedicated section to view and manage saved exercises, persisted via localStorage.Direct access to exercise details or quick removal from the list.
4. Daily InspirationQuote of the Day: A daily motivational quote fetched from the API and cached in localStorage for 24 hours to optimize performance.
5. Newsletter SubscriptionIntegrated footer form allowing users to subscribe to updates with real-time validation and API integration.
6. Responsive Design & AccessibilityAdaptive Header: Fully functional navigation with a burger menu for mobile users.A11y Compliant: Semantic HTML, ARIA labels, and keyboard-friendly navigation.

🛠 Tech StackLogic: Pure (Vanilla) 
JavaScriptBundler: ViteStyling: CSS3 (Modern layouts, Flexbox, Grid)
Markup: HTML5 (using partials for modularity)
API: REST API integration via Swagger documentation
Deployment: GitHub Pages (Automated via GitHub Actions)

📂 Project StructureThe project follows a modular structure to ensure maintainability:Plaintextyour-energy/
├── assets/             # Static assets (icons, global images)
├── src/                # Source files
│   ├── css/            # Stylesheets
│   ├── img/            # Component-specific images
│   ├── partials/       # HTML fragments (Header, Footer, etc.)
│   ├── public/         # Static public files
│   ├── index.html      # Main entry point
│   ├── main.js         # Main JS entry point
│   ├── page-2.html     # Favorites page
│   └── page-3.html     # Additional sub-pages
├── package.json        # Dependencies and scripts
└── vite.config.js      # Vite configuration

🔧 Installation & SetupTo run this project locally, follow these steps:Clone the repository:
Bashgit clone https://github.com/your-username/your-energy.git
Navigate to the project folder:
cd your-energy
Install dependencies:
hnpm install
Start the development server:
hnpm run dev
Build for production:
npm run build

🤝 AcknowledgmentsDeveloped as a capstone project for the GoIT Academy course. Special thanks to the mentors and the community for providing the API and Figma designs.

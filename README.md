# Mat-salector
Electrical Safety mat selector
This is a specialized, single-file React application designed to assist factory managers and safety officers in Pakistan with Accord Pakistan and IEC 61111 compliance.

It calculates the correct Class, Thickness, and Dimensions for electrical insulation mats based on the voltage of Distribution Boards (DBs), helping facilities avoid Corrective Action Plans (CAPs) during safety audits.

# Features
Voltage to Class Mapping: Automatically maps system voltage (220V, 400V, 11kV, 33kV) to the correct IEC 61111 Class (0-4).

Safety Visualizer: Visualizes the required mat size relative to a standard DB.

Specification Generator: One-click copy function to generate text for Purchase Orders (POs).

Crash Protection: Built-in error boundary to prevent "White Screen of Death" if invalid data is entered.

UsageSystem Voltage: Enter the maximum Phase-to-Phase voltage of your panel.

Panel Width: Enter the physical width of the DB.

Get Specs: The app will display the required IEC Class and dimensions (width x 1000mm depth).

# Technology
React 18 (via CDN for zero-build deployment)
Tailwind CSS (via CDN for styling)
Babel (In-browser transpilation)

# Deployment
This application is a static HTML file. It requires no build process (no npm run build).

Entry Point: index.html

Hosting: Can be hosted on Netlify, GitHub Pages, or any static file server.

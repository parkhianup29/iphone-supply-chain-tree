# iPhone Supply Chain Interactive Tree

A responsive D3.js tree visualization for iPhone supply chain hierarchy with interactive controls and smooth animations.

## Features

- **Interactive Nodes**: Click to expand/collapse branches
- **Dual Orientation**: Switch between vertical and horizontal layouts
- **Expand/Collapse All**: Quick bulk operations
- **Smart Zoom Reset**: Auto-centers tree in viewport
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Touch Support**: Pan and pinch-to-zoom gestures

## Quick Start

1. Clone the repository:
  ```bash
  git clone https://github.com/yourusername/iphone-supply-chain-tree.git

Open index.html in your web browser

No build process required!
Tree Structure
iPhone (Root)
├── LG → iPhone 13
├── Samsung → iPhone 12, iPhone 15
└── BOE → iPhone X
Controls

Orientation: Toggle between vertical/horizontal layouts
Expand All: Show all nodes
Collapse All: Hide all children
Reset Zoom: Center and fit tree in viewport
Click Nodes: Individual expand/collapse
Drag: Pan around tree
Mouse Wheel: Zoom in/out

Customization
Edit the treeData object in index.html:
javascriptconst treeData = {
    name: "Root Node",
    stage: 1,
    children: [
        {
            name: "Child Node",
            stage: 2,
            children: [
                { name: "Grandchild", stage: 3 }
            ]
        }
    ]
};
Technologies

D3.js v7
HTML5/CSS3
Vanilla JavaScript

Browser Support
Chrome, Firefox, Safari, Edge (latest versions)
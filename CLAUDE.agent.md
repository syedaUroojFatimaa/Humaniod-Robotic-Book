# Physical AI & Humanoid Robotics Course Development Guidelines

Auto-generated from all feature plans. Last updated: 2025-12-24

## Active Technologies

- Docusaurus (static site generator for documentation)
- Markdown (content format)
- Node.js (runtime environment)
- GitHub Pages (deployment platform)
- ROS 2 (robotics middleware)
- Gazebo (physics simulation)
- NVIDIA Isaac (AI robotics platform)
- JavaScript/TypeScript (for Docusaurus customization)

## Project Structure

```text
docs/
├── module-1-ros2/
│   ├── intro-to-ros2-for-physical-ai.md
│   ├── ros2-communication-model.md
│   └── robot-structure-with-urdf.md
├── module-2-gazebo/
│   ├── physics-simulation-with-gazebo.md
│   ├── human-robot-interaction-in-unity.md
│   └── sensor-simulation.md
├── module-3-isaac/
│   ├── nvidia-isaac-sim.md
│   ├── isaac-ros.md
│   └── nav2-for-humanoid-movement.md
├── module-4-vla/
│   ├── voice-to-action.md
│   ├── cognitive-planning-with-llms.md
│   └── capstone-project-the-autonomous-humanoid.md
├── intro.md
└── getting-started.md

src/
├── components/
├── pages/
└── css/

static/
├── img/
└── assets/

docusaurus.config.js
package.json
sidebar.js
```

## Commands

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build static site
npm run build

# Deploy to GitHub Pages
npm run deploy
```

## Code Style

- Use Markdown format for all content files
- Follow Docusaurus documentation best practices
- Include proper headings hierarchy (#, ##, ###)
- Use code blocks with appropriate language specification
- Add alt text for images
- Write accessible content for all users

## Recent Changes

- Course structure created with 4 modules covering ROS 2, Gazebo, NVIDIA Isaac, and VLA
- Docusaurus project initialized with proper documentation structure
- Content organized into progressive learning modules with 3-4 chapters each

<!-- MANUAL ADDITIONS START -->
<!-- MANUAL ADDITIONS END -->
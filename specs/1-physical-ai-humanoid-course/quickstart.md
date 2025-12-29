# Quickstart Guide: Physical AI & Humanoid Robotics Course

## Prerequisites

Before starting this course, you should have:
- Basic programming knowledge (Python recommended)
- Understanding of fundamental robotics concepts
- A computer capable of running simulation software
- Git installed for version control

## Setup Docusaurus Project

1. **Install Node.js and npm** (if not already installed):
   ```bash
   # Install Node.js from https://nodejs.org/
   # Verify installation:
   node --version
   npm --version
   ```

2. **Initialize Docusaurus project**:
   ```bash
   npx create-docusaurus@latest course-physical-ai-humanoid-robotics classic
   cd course-physical-ai-humanoid-robotics
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start development server**:
   ```bash
   npm start
   ```

## Create Course Structure

1. **Create module directories**:
   ```bash
   mkdir docs/module-1-ros2
   mkdir docs/module-2-gazebo
   mkdir docs/module-3-isaac
   mkdir docs/module-4-vla
   ```

2. **Add initial content files**:
   ```bash
   # Module 1 - ROS 2
   touch docs/module-1-ros2/intro-to-ros2-for-physical-ai.md
   touch docs/module-1-ros2/ros2-communication-model.md
   touch docs/module-1-ros2/robot-structure-with-urdf.md

   # Module 2 - Gazebo
   touch docs/module-2-gazebo/physics-simulation-with-gazebo.md
   touch docs/module-2-gazebo/human-robot-interaction-in-unity.md
   touch docs/module-2-gazebo/sensor-simulation.md

   # Module 3 - Isaac
   touch docs/module-3-isaac/nvidia-isaac-sim.md
   touch docs/module-3-isaac/isaac-ros.md
   touch docs/module-3-isaac/nav2-for-humanoid-movement.md

   # Module 4 - VLA
   touch docs/module-4-vla/voice-to-action.md
   touch docs/module-4-vla/cognitive-planning-with-llms.md
   touch docs/module-4-vla/capstone-project-the-autonomous-humanoid.md
   ```

## Configure Sidebar

Update `sidebars.js` to include your course modules:

```javascript
module.exports = {
  docs: [
    'intro',
    {
      type: 'category',
      label: 'Module 1: The Robotic Nervous System (ROS 2)',
      items: [
        'module-1-ros2/intro-to-ros2-for-physical-ai',
        'module-1-ros2/ros2-communication-model',
        'module-1-ros2/robot-structure-with-urdf'
      ],
    },
    {
      type: 'category',
      label: 'Module 2: The Digital Twin (Gazebo & Unity)',
      items: [
        'module-2-gazebo/physics-simulation-with-gazebo',
        'module-2-gazebo/human-robot-interaction-in-unity',
        'module-2-gazebo/sensor-simulation'
      ],
    },
    {
      type: 'category',
      label: 'Module 3: The AI-Robot Brain (NVIDIA Isaac™)',
      items: [
        'module-3-isaac/nvidia-isaac-sim',
        'module-3-isaac/isaac-ros',
        'module-3-isaac/nav2-for-humanoid-movement'
      ],
    },
    {
      type: 'category',
      label: 'Module 4: Vision-Language-Action (VLA)',
      items: [
        'module-4-vla/voice-to-action',
        'module-4-vla/cognitive-planning-with-llms',
        'module-4-vla/capstone-project-the-autonomous-humanoid'
      ],
    },
  ],
};
```

## Build and Deploy

1. **Build the static site**:
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages**:
   - Push your code to GitHub
   - Go to repository Settings > Pages
   - Select source as GitHub Actions
   - Use the provided workflow file to automate deployment

## Next Steps

1. Begin with Module 1 content: "Introduction to ROS 2 for Physical AI"
2. Follow the progressive learning path through all 4 modules
3. Complete hands-on exercises in each chapter
4. Work on the capstone project integrating all concepts
# Glowing Flower Blueprint Project

This Unreal Engine blueprint creates a glowing flower effect using dynamic materials and timelines.

## Project Overview

This setup controls the emission intensity of the flower petals, making them glow over time. It leverages two key elements:
1. **Dynamic Material Instances**: Allows for runtime changes in material parameters.
2. **Timeline Node**: Gradually adjusts the emission value, creating a pulsing glow effect.

## Key Features

- **Material Instances for Outer and Inner Petals**:  
  Separate material instances for outer and inner petals enable independent control over glow intensity.
  
- **Glow Control**:  
  The timeline adjusts the "Emission" parameter to create a gentle pulsing glow effect for the flower.

- **Adjustable Intensity**:  
  Emission values can be tweaked to customize the glow brightness and speed.

## How It Works

- **Event BeginPlay** initializes the dynamic material instances for both outer and inner petals.
- **Timeline** node updates the emission value periodically, linked to both material instances, to achieve the glow effect.

---


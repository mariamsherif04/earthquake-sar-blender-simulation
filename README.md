# Virtual Search-and-Rescue Operations in Blender
### Earthquake Disaster Response Simulation

![Blender Version](https://img.shields.io/badge/Blender-4.5%20LTS-orange)
![License](https://img.shields.io/badge/License-Educational-blue)
![Status](https://img.shields.io/badge/Status-Complete-green)

A comprehensive 3D virtual environment for earthquake search-and-rescue (SAR) training developed using Blender 4.5 LTS. This simulation provides an immersive, narrative-driven experience visualizing the complete disaster response chain from initial earthquake impact to definitive hospital care.

---

## 📹 Demo Video
**Full Simulation (11 Scenes):**  
🎥 [Watch on Google Drive](https://drive.google.com/file/d/1jAvcEp8GBo5djOjBJkzzOFg0gwMNpOJ2/view?usp=drive_link)
---

## 📄 Technical Report
**IEEE Conference Paper:**  
📑 [Download PDF](https://drive.google.com/drive/folders/1VDIJaLkzfc7LegXnjD-Wd1nOXPUuWfZH?usp=drive_link)

---

## 🎯 Project Overview

This project demonstrates a complete earthquake SAR operation through **11 sequential scenes**, each depicting critical phases of disaster response:

1. **Earthquake Impact** - Ground fracture and building collapse
2. **Civilian Panic** - Evacuation under extreme stress
3. **Heavy Stone Rescue** - Debris removal to free trapped victim
4. **Falling Debris Hazard** - Continuous environmental dangers
5. **Victim Extraction** - Safe transport through unstable terrain
6. **Ambulance Arrival** - Emergency medical service deployment
7. **Damaged Road Transport** - Navigation through destruction
8. **CPR Administration** - Life-saving medical intervention
9. **Paramedic Triage** - Professional medical handoff
10. **Nighttime Stretcher Transport** - Extended operation timeline
11. **Hospital Care** - Definitive medical treatment

---

## ✨ Key Features

### 🎬 **Realistic Disaster Simulation**
- Physics-based building collapse using **RBD Lab**
- Ground fracture with rigid body mesh constraints
- Continuous falling debris and environmental hazards
- Day-to-night lighting transition across scenes

### 👥 **Professional Character Animation**
- **Mixamo** motion-captured animations
- Anatomically accurate movements (running, lifting, CPR)
- Multiple character types: rescuers, civilians, paramedics
- Realistic panic, evacuation, and medical procedure animations

### 🌫️ **Atmospheric Effects**
- Dense dust and fog using **Alt Tab Easy Fog**
- Volumetric scattering reducing visibility to 5-10 meters
- Light beam scattering from flashlights and vehicle beacons
- Authentic post-earthquake atmospheric conditions

### 🎥 **Dynamic Cinematography**
- **Shakify Camera** for realistic earthquake motion
- Procedural camera shake during seismic events
- Smooth tracking shots following rescue operations
- Documentary-style handheld camera work

### 💡 **Advanced Lighting**
- Sun light for global daylight illumination
- 4 point lights for emergency vehicles and night scenes
- Temporal progression from afternoon to night
- Realistic emergency vehicle beacon animations

---

## 🛠️ Technical Stack

### Software & Tools
- **Blender 4.5 LTS** - Primary development platform
- **Cycles Render Engine** - Final output rendering
- **Eevee** - Real-time preview during development

### Specialized Add-ons
| Add-on | Purpose |
|--------|---------|
| **Mixamo** | Character import & animation library |
| **RBD Lab** | Advanced fracture & destruction simulation |
| **Alt Tab Easy Fog** | Volumetric fog and dust effects |
| **Shakify Camera** | Dynamic camera movement & shake |
| **Node Wrangler** | Efficient material/texture workflow |

### Asset Sources
- **3D Models:** Sketchfab, Free3DModels, CGTrader, BlenderKit
- **Textures:** Poly Haven (PBR), Freepik
- **Characters & Animations:** Adobe Mixamo

---

## 🎨 Scene Breakdown

### Initial Disaster Response (Scenes 1-3)
Ground rupture, building collapse, civilian evacuation, and immediate rescue operations under extreme stress.

### Rescue Operations (Scenes 4-6)
Persistent environmental hazards, victim extraction through unstable terrain, and emergency vehicle arrival.

### Medical Response (Scenes 7-9)
Transport through damaged infrastructure, life-saving CPR, and professional paramedic intervention.

### Final Care (Scenes 10-11)
Nighttime stretcher transport and definitive hospital treatment showing complete operational timeline.

---

## ⚙️ Technical Implementation

### Physics Simulation
```
Ground: Rigid Body (Mesh + Constraint)
Buildings: Rigid Body (Convex Hull) + RBD Lab fracture
Debris: Active Rigid Bodies with realistic mass/friction
Simulation: Baked to keyframes for stable playback
```

### Lighting Configuration
```
Sun Light: Primary daylight source (early scenes)
Point Lights (4): Emergency beacons, flashlights, night illumination
Day→Night Transition: Scenes 1-5 (day) → Scenes 10-11 (night)
```

### Materials & Textures
- **Diffuse surfaces:** Concrete, plaster
- **Medium reflectance:** Painted metal, vehicle paint
- **Specular surfaces:** Polished metal, glass
- All materials use PBR workflow with albedo, normal, roughness maps

---

## 🎓 Educational Applications

This simulation is designed for:

- ✅ **SAR Team Training** - Pre-deployment familiarization
- ✅ **Medical Personnel** - Disaster triage and CPR protocols
- ✅ **Emergency Management** - Coordination exercise scenarios
- ✅ **Public Education** - Earthquake preparedness awareness
- ✅ **Academic Instruction** - Disaster medicine courses
- ✅ **Inter-Agency Coordination** - Fire, EMS, rescue collaboration

---

## 📊 Operational Difficulties Simulated

1. **Dust Environment** - Severely reduced visibility (5-10m)
2. **Falling Debris** - Continuous hazards requiring situational awareness
3. **Heavy Object Manipulation** - Realistic physics for debris removal
4. **Indoor Rescue** - Confined space constraints
5. **Day-Night Operations** - Extended timeline challenges
6. **Time-Critical Medical Care** - CPR under field conditions

---

## 🚀 Future Enhancements

### Interactive Elements
- [ ] Real-time user controls for navigation and decision-making
- [ ] Performance scoring based on speed, safety, and accuracy
- [ ] Dynamic scenario outcomes based on user choices

### VR Integration
- [ ] Port to VR platforms (Oculus, HTC Vive)
- [ ] First-person immersive rescue operations
- [ ] Hand-tracked medical procedure training

### Expanded Scenarios
- [ ] Multiple disaster types (fire, flood, industrial)
- [ ] Procedurally generated building collapse patterns
- [ ] Variable victim distribution and injury severity

### Multi-User Collaboration
- [ ] Networked team coordination training
- [ ] Role-specific gameplay (rescuer, paramedic, command)
- [ ] Communication protocol practice

---

## 👥 Development Team

| Team Member | Email |
|-------------|------|-------|
| **Alhussein Ayman Hanafi** | alhussienaymanhanafy@gmail.com |
| **Ahmed Wael Shenif** | email@placeholder.com |
| **AbdelRahman Reda Khalaf** | email@placeholder.com |
| **Sarah Sameh Mohamed** | sarah.mohamed03@eng-st.cu.edu.eg |
| **Menna Allah Ashraf** | menaashrafalymohamed@gmail.com |
| **Mariam Sherif Mohamed** | mariam.awwad04@eng-st.cu.edu.eg |

---

**Built with ❤️ using Blender 4.5 LTS and the power of open-source tools**

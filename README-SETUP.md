# Grab GenAI Impact Navigator - Setup Instructions

## 🚀 Quick Start (2 minutes)

### Step 1: Setup
1. **Unzip** this folder to your Desktop or any location
2. **Open Terminal** (Mac) or **Command Prompt** (Windows)
3. **Navigate to the dist folder:**
   ```bash
   cd path/to/unzipped-folder/dist
   ```

### Step 2: Launch
**Mac/Linux:**
```bash
python3 -m http.server 8000
```

**Windows:**
```bash
python -m http.server 8000
```

### Step 3: Open Browser
- Go to: **http://localhost:8000**
- The application will load immediately

---

## ✨ Features Overview

### 📊 Interactive Use Case Management
- **Edit Everything**: Title, description, team, effort, ROI, scores, reasoning
- **Real-time Updates**: Changes reflect immediately across all pages
- **Persistent Changes**: Edits save during your session

### 🎯 Three-Phase Experience
1. **Use Cases**: Detailed exploration and editing
2. **Matrix**: Visual impact vs feasibility positioning  
3. **Analytics**: Portfolio insights with team filtering

### 🔧 Key Capabilities
- ✅ **Comprehensive Editing** - Modify any use case field
- ✅ **Smart Matrix** - Auto-positioning based on scores
- ✅ **Team Filtering** - Finance vs Legal team views
- ✅ **Responsive Design** - Works on desktop and mobile
- ✅ **Offline Ready** - No internet required

---

## 🎯 Perfect For
- **Client Presentations** - Professional Anthropic x Grab branding
- **Workshop Sessions** - Interactive use case prioritization
- **Strategic Planning** - Visual portfolio analysis
- **Stakeholder Demos** - Real-time scenario planning

---

## 🛠️ Troubleshooting

**Can't access localhost:8000?**
- Try: `http://127.0.0.1:8000`
- Make sure nothing else is using port 8000

**Python not found?**
- Install Python from python.org
- Or try: `python` instead of `python3`

**Changes not saving?**
- Changes persist during session only
- Refresh = reset to original data
- Each browser session is independent

---

## 📝 Notes for Anthropic Team

### Customization
- Each team member gets independent copy
- Modify scores/descriptions for different scenarios  
- Perfect for tailored client presentations

### Data Structure
- 20 carefully calibrated use cases
- Realistic impact/feasibility scores
- MECE categorization (Knowledge, External, Quantitative, Workflow)
- Balanced across Finance and Legal teams

### Technical Details
- React + TypeScript frontend
- Zustand state management
- Tailwind CSS styling
- Vite build system
- Static file hosting

---

**Questions? Contact: [Your Name/Email]**
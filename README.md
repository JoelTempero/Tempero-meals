# Tempero Meals 🍽️🥗

A couples meal prep planning app for Rachel and Joel!

## Features

- 🔐 **PIN protected** (4-digit code: 3489)
- 📅 **Weekly Calendar** - Plan lunch & dinner for each day
- 👥 **Assign meals** - Who's eating & who's cooking
- 🍽️ **Meal Library** - 25 starter meals with recipes
- 🏷️ **Tags** - Fresh, Frozen, Fast Food, Bulk Prep, Vegetarian, Quick, Comfort, Healthy
- 📝 **Full Recipes** - Ingredients list & step-by-step instructions
- 🎰 **Meal Picker** - Spin the wheel for random meal selection!
- 🔍 **Filter** - By tags or ingredients
- 🛒 **Shopping Cart** - Add ingredients from meals or custom items
- ✅ **Check off items** as you shop
- 🏆 **100 Badges** - Achievement milestones for both users
- ⚙️ **Customizable** - Add your own people, meals, and tags
- 📱 **PWA** - Install on your phone's home screen

## Color Palette 🌿

Fresh food inspired theme:
- **Background**: Forest green (#1a472a)
- **Cards**: Sage green (#2d5a3d)
- **Primary**: Fresh mint (#4ade80)
- **Secondary**: Carrot orange (#fb923c)
- **Accent**: Golden honey (#fbbf24)
- **Rachel**: Pink (#f472b6)
- **Joel**: Blue (#60a5fa)

## Setup

### 1. Create your GitHub repo

Create a new repository called `Tempero-Meals` on GitHub.

### 2. Upload these files

Upload all files from this folder to your repo:
- `index.html`
- `manifest.json`
- `icon-192.png` (create or use existing)
- `icon-512.png`

### 3. Create the data folder structure

Create a folder called `data` and add an empty `meals.json` file:
```json
{}
```

### 4. Enable GitHub Pages

1. Go to your repo → Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` (or `master`), folder: `/ (root)`
4. Save

Your site will be live at: `https://YOUR-USERNAME.github.io/Tempero-Meals/`

### 5. Create a Personal Access Token (PAT)

1. GitHub → Settings → Developer settings → Personal access tokens → Fine-grained tokens
2. Generate new token
3. Name: "Tempero Meals"
4. Repository access: Only select repositories → `Tempero-Meals`
5. Permissions → Repository permissions → Contents: Read and write
6. Generate token
7. Copy the token (starts with `github_pat_`)

### 6. Configure the app

1. Open your app URL
2. Enter PIN: `3489`
3. Tap ⚙️ Settings
4. Paste your PAT
5. Add/edit people names if needed
6. Save

### 7. Install on your phone

**iPhone:**
1. Open the URL in Safari
2. Tap Share → Add to Home Screen

**Android:**
1. Open in Chrome
2. Tap menu → Add to Home Screen

## Changing the PIN

Edit `index.html` and change this line:
```javascript
const CONFIG = {
    PIN: '3489',  // ← Change this
```

## Starter Meals Included

1. 🍝 Spaghetti Bolognese
2. 🥘 Chicken Stir Fry
3. 🌮 Beef Tacos
4. 🍛 Vegetable Curry
5. 🐟 Grilled Salmon
6. 🍕 Margherita Pizza
7. 🥗 Caesar Salad
8. 🍚 Fried Rice
9. 🍔 Beef Burgers
10. 🍲 Chicken Soup
11. 🐟 Fish and Chips
12. 🍜 Pad Thai
13. 🍝 Lasagna
14. 🥗 Greek Salad
15. 🍗 Chicken Parmesan
16. 🍜 Ramen
17. 🌯 Quesadillas
18. 🥧 Shepherd's Pie
19. 🥞 Pancakes
20. 🥙 Burrito Bowl
21. 🍞 French Toast
22. 🍝 Meatballs
23. 🥪 BLT Sandwich
24. 🧀 Mac and Cheese
25. 🍗 Teriyaki Chicken

## Badge Categories (100 total)

- **Cooking Milestones**: First Meal → Legendary Chef (1-500 meals)
- **Fresh Food**: Fresh Start → Fresh Master
- **Vegetarian**: Veggie Lover → Veggie Legend
- **Quick Meals**: Quick Cook → Lightning Chef
- **Comfort Food**: Comfort Seeker → Comfort King
- **Healthy Eating**: Health Nut → Health Champion
- **Bulk Prep**: Bulk Beginner → Bulk Master
- **Planning**: Week Planner, Month Planner
- **Streaks**: Consistent Cook → Diamond Streak
- **Meal Picker**: Lucky Spin, Spin Master
- **Shopping**: First Shop → Shopping Legend
- **Recipe Creation**: Recipe Creator → Recipe Master
- **No Fast Food**: Week → 3 Months
- **Ingredient-based**: Garlic Guru, Cheese Please, etc.
- **And many more!**

---

Built with 🥗💚 for Rachel & Joel

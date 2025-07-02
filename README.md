# Fresh Faces

**Keep your contacts looking fresh with yearly profile picture updates.**

Fresh Faces is a local-first, privacy-focused contact photo manager that helps you update your Google Contacts profile photos annually by scraping and updating them using public profiles. It is built with:

- **Frontend:** Next.js + TailwindCSS
- **Backend:** FastAPI
- **Database:** SQLite
- **Local-first:** No cloud storage, all processing and images stored locally.

---

## Features

✅ Import Google Contacts and view them in a clean dashboard  
✅ Scrape fresh profile pictures from public sources (Twitter, Instagram, LinkedIn, etc.)  
✅ Update your Google Contacts profile images directly  
✅ Track last updated date per contact  
✅ Local-first privacy, your data stays on your device  
✅ Works offline after initial setup  

---

## Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/itthipho1/fresh-faces.git
cd fresh-faces
```

### 2️⃣ Backend Setup
```bash
cd backend
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### 4️⃣ Open in Browser
Frontend: [http://localhost:3000](http://localhost:3000)  
Backend API: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## Roadmap
- [x] Import Google Contacts via OAuth
- [x] Display contacts in a dashboard
- [x] Manual update with new images
- [ ] Automated scraping of fresh images
- [ ] One-click update to Google Contacts
- [ ] Local image cache management

---

## License
MIT

---

## Contributing
PRs and suggestions welcome to improve and expand Fresh Faces.

---

## Maintainer
[@itthipho1](https://github.com/itthipho1)

**Keep your contacts looking fresh!**

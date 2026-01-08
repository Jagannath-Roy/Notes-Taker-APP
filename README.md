# 📝 Notes Taker App

A simple and lightweight **Notes Taking Web Application** built using **Node.js, Express, EJS, and JavaScript**.  
This app allows users to create, view, and manage notes, which are stored as text files on the server using Node’s `fs` module.

---

## 🚀 Features

- Create notes with a title and description
- View all saved notes in a card layout
- Read full note content
- Edit existing notes
- File-based storage using Node.js `fs` module
- Clean and minimal UI
- No external database required

---

## 🛠 Tech Stack

| Layer      | Technology |
|------------|------------|
| Frontend   | HTML, CSS, JavaScript |
| Templating | EJS |
| Backend    | Node.js, Express |
| Storage    | File System (`fs` module) |
| Protocol   | HTTP |

---

## 📂 Project Structure

```bash
notestakerapp/
│
├── files/            # Stored notes (.txt files)
├── public/           # Static assets (CSS, JS)
├── views/            # EJS templates
│   ├── index.ejs
│   ├── edit.ejs
│   └── show.ejs
│
├── index.js          # Main server file
├── package.json
└── README.md

```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/Jagannath-Roy/Notes-Taker-APP.git
cd notestakerapp
npm install
node index.js
http://localhost:3000

```

---

## Usage

- Open the browser and go to http://localhost:3000

- Enter a title and description for your note

- Click Create

- Your note will appear as a card below

- Click Read More to view the full note

- Use Edit to modify the note if needed

---

## Future Improvements

- Delete notes feature

- Search and filter notes

- Markdown support

- User authentication

- Cloud database integration (MongoDB / Firebase)

---

## Contributing

- Contributions are welcome!

- Fork the repository

- Create a feature branch (feature/new-feature)

- Commit your changes

- Push to the branch

- Open a Pull Request

---

## License

This project is licensed under the MIT License.

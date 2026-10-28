# 📚 BookHive — Online Bookstore

**Discover Stories. Explore Knowledge. Find Your Next Favourite Book.**

BookHive is a modern, responsive online bookstore website built using HTML5 and CSS3. It provides a clean interface for browsing books, exploring categories, viewing book details, and discovering sample book recommendations.

The project focuses on attractive UI design, simple navigation, reusable CSS styling, and a responsive layout for desktop, tablet, and mobile devices.

---

## ✨ Features

### 🏠 1. Home Page
- Attractive hero section.
- Bookstore introduction and promotional content.
- Featured books and categories.
- Navigation to other website pages.
- Call-to-action buttons to explore books.

### 📚 2. Books Catalogue
- Display of books in a responsive card layout.
- Book covers, titles, authors, descriptions, and prices.
- Book categories such as fiction, biography, self-help, and technology.
- Links to individual book detail pages.
- Category navigation for browsing the catalogue.

### 🤖 3. AI-Style Book Finder
- Dedicated BookHive Smart Picks interface.
- Input field for describing reading interests.
- Dropdown for selecting a reading mood or goal.
- AI-inspired visual design and book illustrations.
- Sample recommendation cards for discovering books.

**Note:** The AI Book Finder is a front-end demonstration. It does not connect to a live AI model or generate personalized recommendations.

### 📖 4. Book Details Page
- Dedicated details page for a selected book.
- Book cover, title, author, description, and listed price.
- Book information and learning highlights.
- Sample book specifications.
- Related book recommendation cards.
- Links to browse the complete catalogue.

### 🛒 5. Shopping Cart Interface
- A dedicated cart page for demonstrating the shopping experience.
- Navigation from the book pages to the cart.

**Note:** Cart storage, automatic price calculation, checkout, and payment processing are not implemented.

### 🔐 6. Login and Sign-Up Pages
- Login page interface.
- Sign-up page interface.
- Form fields for user input.
- Consistent styling with the overall website.

**Note:** User authentication and account storage are not implemented.

### ℹ️ 7. About Page
- Introduction to BookHive.
- Project purpose and bookstore concept.
- Consistent website layout.

### ✉️ 8. Contact Page
- Contact information and contact form interface.
- Simple, user-friendly layout.

**Note:** The contact form does not send messages to a server.

### 📱 9. Responsive Design
- Responsive book cards and category grids.
- Mobile-friendly page layouts.
- CSS media queries for different screen sizes.
- Consistent buttons, colours, typography, and spacing.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts, animations, and responsiveness |
| Visual Studio Code | Code editor |
| Live Server | Local website preview |
| Git and GitHub | Version control and project hosting |
| Netlify | Website deployment |

**Project constraint:** This version uses only HTML and CSS. No JavaScript or backend is included.

---

## 📁 Project Structure

```text
BookHive/
│
├── index.html
├── books.html
├── book.html
├── cart.html
├── login.html
├── signup.html
├── about.html
├── contact.html
│
├── css/
│   └── style.css
│
└── README.md
```

### File Description

| File | Description |
|---|---|
| `index.html` | Homepage |
| `books.html` | Book catalogue, categories, and AI-style Book Finder |
| `book.html` | Individual book details and related recommendations |
| `cart.html` | Shopping cart demonstration page |
| `login.html` | Login interface |
| `signup.html` | Registration interface |
| `about.html` | About BookHive |
| `contact.html` | Contact page |
| `css/style.css` | Shared styles and responsive layouts |
| `README.md` | Project documentation |

---

## 🚀 How to Run the Project

### Step 1: Download or Clone the Repository

Clone the repository using Git:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

Alternatively, download the repository as a ZIP file and extract it.

### Step 2: Open in Visual Studio Code

1. Open Visual Studio Code.
2. Select **File → Open Folder**.
3. Choose the `BookHive` project folder.
4. Make sure all HTML files and the `css` folder are present.

### Step 3: Install Live Server

1. Open the Extensions panel in VS Code.
2. Search for **Live Server**.
3. Install the extension.

### Step 4: Run the Website

1. Open `index.html`.
2. Right-click inside the editor.
3. Select **Open with Live Server**.

The website will open in your default browser.

---

## 🌐 Deploy on Netlify

You can deploy BookHive using Netlify.

### Option 1: Deploy Through GitHub

1. Push your project to a GitHub repository.
2. Log in to Netlify.
3. Select the option to add a new site and import an existing project.
4. Connect your GitHub account and choose the BookHive repository.
5. For a plain HTML/CSS project, leave the build command empty.
6. Set the publish directory to the project root, where `index.html` is located.
7. Deploy the site.

### Option 2: Manual Deployment

1. Open Netlify and log in.
2. Open the manual deployment option.
3. Drag and drop your project folder containing `index.html`, the other HTML files, and the `css` folder.
4. Wait for deployment to finish.
5. Open the generated website URL to test your pages.

Keep all file and folder paths unchanged so the links and stylesheet work correctly.

---

## 🔄 Push Updates to GitHub

After editing your project, open the VS Code terminal in the project folder and run:

```bash
git add .
git commit -m "Update BookHive pages and styles"
git push
```

If your Netlify site is connected to GitHub, it can automatically redeploy after you push changes.

---

## 🎨 Design Highlights

- Modern bookstore-inspired interface.
- Purple and indigo accent colours.
- Rounded cards and buttons.
- Clear typography and spacing.
- Book cover imagery.
- AI-inspired visual elements.
- Responsive grids and layouts.
- Reusable CSS components.

---

## ⚠️ Current Limitations

This is a front-end website demonstration. The following features require additional technologies to become fully functional:

- Live AI recommendations require an AI service or backend integration.
- Cart management requires application logic and storage.
- Login and sign-up require authentication and a backend.
- Checkout and payments require a secure payment integration.
- Contact form submission requires a server or form service.
- Book search and filtering require additional interactive logic.

External book cover images also require an internet connection.

---

## 🔮 Future Enhancements

- Integrate a live AI book recommendation service.
- Add interactive search and category filtering.
- Implement a functional shopping cart.
- Add user authentication and profile management.
- Connect a database for book information.
- Add a secure checkout process.
- Create an admin dashboard to manage books.
- Add customer reviews and ratings.
- Improve accessibility and SEO.

---

## 🎯 Project Objective

The objective of BookHive is to demonstrate front-end web development skills through a multi-page online bookstore. The project showcases HTML page structure, CSS styling, responsive design, navigation, catalogue layouts, book detail sections, and an AI-inspired recommendation interface.

---

## 👩‍💻 Author

**Developed as a Web Development Project**

Technologies: HTML5 and CSS3

---

## 📄 License

This project is intended for educational and portfolio purposes. Ensure that book cover images, fonts, and other third-party assets are used in accordance with their respective licences.

---

**BookHive — Every Book Opens a New World.** 📚

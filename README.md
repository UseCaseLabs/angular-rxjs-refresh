Angular RxJS Refresh 🚀
A simple Angular app demonstrating how to use RxJS Subjects to refresh a list after Create, Update, and Delete actions.

📌 Features
✅ Fetches a list from JSONPlaceholder (mock API)
✅ Displays the list dynamically
✅ RxJS Subjects for live updates (without full-page reloads)
✅ Angular Material pop-up dialog for adding items
✅ Reactive programming with Observables & BehaviorSubjects

🛠 Tech Stack
Angular (latest)
RxJS (Subjects & Observables)
Angular Material (UI components)
JSONPlaceholder API (for mock data)
🚀 Setup & Run
1️⃣ Clone the repo

sh
Copy
Edit
git clone https://github.com/UseCaseLabs/angular-rxjs-refresh.git
cd angular-rxjs-refresh
2️⃣ Install dependencies

sh
Copy
Edit
npm install
3️⃣ Run the app

sh
Copy
Edit
ng serve
4️⃣ Open in browser
Visit http://localhost:4200/

📝 How It Works
On load, the app fetches a list of items from JSONPlaceholder.
Clicking "Add Item" opens a popup dialog to mock-create a new item.
After adding an item, the list updates instantly via an RxJS Subject.
📷 Screenshots (Add screenshots later to showcase the app)
📌 Future Enhancements (Ideas)
🔹 Add edit & delete functionality
🔹 Improve UI/UX
🔹 Implement a real backend

📜 License
This project is open-source under the MIT License.

📩 Questions or Contributions?
Feel free to open an issue or submit a pull request!

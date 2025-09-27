
---

# Django Chat Room

A real-time chat application, enabling users to join chat rooms and communicate instantly.

## 📌 Features

* **User Authentication**: Secure login and registration with Django's built-in authentication system.
* **Dynamic Chat Rooms**: Users can create and join multiple chat rooms.
* **Responsive Interface**: Mobile-friendly design using Bootstrap.
* **Message Persistence**: Chat history is saved and accessible upon reconnecting.

## 🛠 Installation & Running Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/bomberman2099/django-chatRoom.git
   cd django-chatRoom
   ```

2. **Set Up Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

   Access the application at `http://localhost:8000`.

## 📄 Project Structure

* `chat/`: Contains models, consumers, and templates for chat functionality.
* `templates/`: HTML templates for rendering pages.
* `static/`: CSS, JavaScript, and image files.
* `db.sqlite3`: SQLite database file.

## 🔧 Technologies Used

* **Backend**: Python, Django, Django Channels
* **Frontend**: HTML5, CSS3, Bootstrap
* **Real-Time Communication**: WebSockets
* **Database**: SQLite (default), can be configured to PostgreSQL or MySQL

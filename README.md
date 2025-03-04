## API Endpoints

### Categories

- **Get all categories**
    - **Method:** `GET`
    - **URL:** `http://127.0.0.1:8000/api/categories`

- **Create a new category**
    - **Method:** `POST`
    - **URL:** `http://127.0.0.1:8000/api/categories`
    - **Headers:** `Content-Type: application/json`
    - **Body:**
        ```json
        {
            "name": "Web Development",
            "description": "Kategori kursus untuk pengembangan web"
        }
        ```

- **Get category by ID**
    - **Method:** `GET`
    - **URL:** `http://127.0.0.1:8000/api/categories/1`

- **Update category**
    - **Method:** `PUT`
    - **URL:** `http://127.0.0.1:8000/api/categories/1`
    - **Headers:** `Content-Type: application/json`
    - **Body:**
        ```json
        {
            "name": "Updated Web Development",
            "description": "Kategori kursus yang telah diperbarui"
        }
        ```

- **Delete category**
    - **Method:** `DELETE`
    - **URL:** `http://127.0.0.1:8000/api/categories/1`

Dengan langkah-langkah ini, Service Repository Pattern telah diterapkan untuk tabel Categories, membuat kode lebih terstruktur dan mudah dipelihara.

### Courses

- **Get all courses**
    - **Method:** `GET`
    - **URL:** `http://127.0.0.1:8000/api/courses`

- **Create a new course**
    - **Method:** `POST`
    - **URL:** `http://127.0.0.1:8000/api/courses`
    - **Headers:** `Content-Type: application/json`
    - **Body:**
        ```json
        {
            "title": "Belajar Laravel",
            "description": "Kursus Laravel untuk pemula",
            "category_id": 1
        }
        ```

- **Get course by ID**
    - **Method:** `GET`
    - **URL:** `http://127.0.0.1:8000/api/courses/1`

- **Update course**
    - **Method:** `PUT`
    - **URL:** `http://127.0.0.1:8000/api/courses/1`
    - **Headers:** `Content-Type: application/json`
    - **Body:**
        ```json
        {
            "title": "Updated Laravel Course",
            "description": "Kursus Laravel dengan materi lebih lengkap",
            "category_id": 1
        }
        ```

- **Delete course**
    - **Method:** `DELETE`
    - **URL:** `http://127.0.0.1:8000/api/courses/1`

Dengan langkah-langkah ini, Service Repository Pattern telah diterapkan untuk Courses, membuat kode lebih modular, terstruktur, dan mudah dipelihara.

## API Endpoints

### Categories

- **Get all categories**
    - **Method:** GET
    - **URL:** <http://127.0.0.1:8000/api/categories>

- **Create a new category**
    - **Method:** POST
    - **URL:** <http://127.0.0.1:8000/api/categories>
    - **Headers:** Content-Type: application/json
    - **Body:**
        ```json
        {
            "name": "Web Development",
            "description": "Kategori kursus untuk pengembangan web"
        }
        ```

- **Get category by ID**
    - **Method:** GET
    - **URL:** <http://127.0.0.1:8000/api/categories/1>

- **Update category**
    - **Method:** PUT
    - **URL:** <http://127.0.0.1:8000/api/categories/1>
    - **Headers:** Content-Type: application/json
    - **Body:**
        ```json
        {
            "name": "Updated Web Development",
            "description": "Kategori kursus yang telah diperbarui"
        }
        ```

- **Delete category**
    - **Method:** DELETE
    - **URL:** <http://127.0.0.1:8000/api/categories/1>

Dengan langkah-langkah ini, Service Repository Pattern telah diterapkan untuk tabel Categories, membuat kode lebih terstruktur dan mudah dipelihara.

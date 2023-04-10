Percobaan dockerfile menjalankan streamlit (folder tutorial/exercise.py)

Untuk melakukan create image 
docker build -t my-streamlit-app .

Untuk menjalankan image
docker run -p 8501:8501 my-streamlit-app

Untuk melihat hasilnya di local
http://localhost:8501

searching for IP Address fastapi in localhost -> dilihat yg bagian gateway
docker network inspect bridge
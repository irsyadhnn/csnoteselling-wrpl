# csnoteselling-wrpl

Langkah2 running:

- conda info --envs # cek info env
- conda activate WRPL # aktifkan env (yg terinstal flask)

BE (terminal 1):

- cd backend
- python app.py

FE (terminal 2):

- cd frontend
- npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

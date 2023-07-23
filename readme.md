# Conda export Env

conda env export --no-builds | findstr -v "prefix" > environment.yml

# Basic Python

- https://www.cp.eng.chula.ac.th/~somchai/python101/00-01.html"# fast-kickstart-crud"
  "# fast-kickstart-crud"
# Anaconda Env
- https://www.anaconda.com/download/
# Step Start
1. docker compose up -d
2. run initial_data.py
3. python.exe -m uvicorn app.main:app --reload 
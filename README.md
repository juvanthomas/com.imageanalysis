## How to Run the Project Locally
Make a virtual environment and
Clone the repository to your local machine:

```bash
git clone https://github.com/juvanthomas/com.imageanalysis.git
```

Install the requirements:

```bash
pip3 install -r requirements.txt
```

Apply the migrations:

```bash
python3 manage.py migrate
```

Finally, run the development server:

```bash
python3 manage.py runserver
```

The project will be available at **127.0.0.1:8000**.

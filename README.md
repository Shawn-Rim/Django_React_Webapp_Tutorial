# Django_React_Webapp_Tutorial

This project is a product from following along a Youtube video [Django & React Webapp Tutorial](https://www.youtube.com/watch?v=c-QsfbznSXI) by TechWithTim.

## Installation

1. Navigate into the frontend directory.

```
cd frontend
```

2. Install all the required modules.

```
npm i
```

3. Navigate into the backend directory.

```
cd ..
cd backend
```

4. install all the required modules again.

```
pip install -r requirements.txt
```

## Usage

### Backend(Server)

1. Navigate to the backend directory.
2. Use following commands to run the server.

```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```

3. Copy the developement server url address.

### Frontend

1. Navigate to the frontend directory
2. Create .env file and paste the development server url address.

```
VITE_API_URL=YOUR_DEVELOPMENT_SERVER_URL_ADDRESS
```

3. Run local development server.

```
npm run dev
```

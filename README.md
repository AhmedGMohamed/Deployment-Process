# Udagram

---

## Hosted Website Link

You can access the website using this [link](http://udacityprojectfrontend.s3-website-us-east-1.amazonaws.com)

## Running the Application Locally

In order to run the application locally you'll need to follow a few steps

#### 1. Installing Front-end Dependencies

To install the dependencies needed for the front-end, run `npm run frontend:install`

#### 2. Installing the Back-end Dependencies

To install the dependencies needed for the back-end, run `npm run backend:install`

#### 3. Setup Environment Variables

You need to create a .env file inside the udagram-api folder with the following variables:
|Key|Value|
|---|-----|
|AWS_ACCESS_KEY_ID| Your AWS Access Key ID
|AWS_SECRET_ACCESS_KEY| Your AWS Secret Access Key
|AWS_DEFAULT_REGION| The Default Region where you use your account
|AWS_REGION| The Region where you deploy your applications
|JWT_SECRET| Secret key used for authentication
|POSTGRES_DB| Your PostgreSQL database name
|POSTGRES_HOST| Your PostgreSQL database address EG.:'127.0.0.1'
|POSTGRES_USERNAME| Your PostgreSQL username
|POSTGRES_PASSWORD| Your PostgreSQL password
|PORT| Your PostgresSQL Database port
|SERVER_PORT| The port you'd like the backend to listen to
|URL|The URL to the Backend API

#### 4. Run the application

- Navigate to `udagram-api` and run `npm run dev` in your terminal
- Navigate to `udagram-frontend` and run `npm run start` in your terminal

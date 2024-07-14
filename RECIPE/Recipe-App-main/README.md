
### Installation

1.  Install frontend dependencies

	`cd client`  
	`npm install` 

2.  Install backend dependencies

	`cd ../server`  
	`npm install` 

3.  Set up environment variables
	-   Create a `.env` file in the backend directory with the following variables:

		`MONGODB_URI=<your-mongodb-uri>`  
		`CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>`  
		`CLOUDINARY_API_KEY=<your-cloudinary-api-key>`  
		`CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>`   
		`PORT=8080<or-port-of-your-choice>`

	-   Create a `.env.local` file in the frontend directory with the following variables:

		`REACT_APP_GOOGLE_CLIENT_ID=<your-google-client-id>`

	-   If you are not sure how to get these API keys by yourself, you can refer to this [youtube video](https://youtu.be/k4lHXIzCEkM?si=FKRVJ9OysXzi5rQb) from JSMastery, where I get my inspiration for Let'em Cook, on how to setup the project locally, it includes the detail steps on how to setup MongoDB, Cloudinary, and Google OAuth with Refine, and store those API keys into the client folder's .env.local, and server's .env file. Specifically, you will want to check out the [Setup](https://youtu.be/k4lHXIzCEkM?si=Zlv5LN3rKSISGzQQ&t=339), and the [Backend Setup](https://youtu.be/k4lHXIzCEkM?si=Zlv5LN3rKSISGzQQ&t=6520) chapters.  

4.  Start the backend server

	`cd server`  
	`npm run start` 

5.  Start the frontend server

	`cd ../client`  
	`npm run dev` 

6.  Open [http://localhost:3000](http://localhost:3000/) in your browser to see the app



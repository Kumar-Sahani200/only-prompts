Installation:
After cloning the project, cd into it and install all the dependencies using npm install.

Set up:
Open the project in your compiler and create a .env file in the root directory and add the following variable in the .env file

GOOGLE_ID=
GOOGLE_CLIENT_SECRET=

MONGODB_URI=

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET= 


Here how you can get the following value for the above variables:

GOOGLE_ID and GOOGLE_CLIENT_SECRET:
You can go to console.cloud.google.com and generate these keys from your own google account

MONGODB_URI:
Make a account in mongoDB atlas and create a cluster, project, database and then connect with that database using the driver's URI

NEXTAUTH_SECRET
For mac, in your terminal you can simply run:
openssl rand -base64 32 
But for windows you can try the same command in online open ssl

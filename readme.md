Server (backend);
    cd server --to move server dir
        run npm i or npm install in termianl
        1-"npm run dev" to start development server
        2- "npm start" to start production server
    add .env file in root server dir 
        add variables in env:
           ----PORT  = 4000
              MONGO_URI = mongodb://127.0.0.1:27017 (change this for mongoAltas server)
              FRONTEND_URL = http://localhost:3000
              JWT_SECRET = "VwyUz2qw6uLV46NZDcmpBkLHTmXiLjfZWRAf0M2xoB4=" 
    Super admin credentials:
             email: "admin@test.com",
             password: "admin123

client (frotend)
    cd client to move client dir
    run npm i -f (using next js 15 -rc not stable so use -f)
        1-"npm run dev" to start development server
        2- "npm start" to start production server
       add .env file in root client dir
 add below variables to .env
       NEXT_PUBLIC_BACKEND_URL = "http://localhost:4000"
       NEXT_PUBLIC_CLIENT_URL = "http://localhost:3000" 

for any error or conflicts 
contact me 
email : vishalgupta91998@gmail.com 
phone  : 82866243614

thanks!




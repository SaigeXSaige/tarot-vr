TarotVr is an immersive VR experience created with a Rails backend and a React frontend. This project was designed by Chris Junker and Saige Leslie for educational purposes. 

To run it, open each directory in seperate terminals. For the frontend, run `npm install && npm start`. The backend is ran using a postgresQL database. To run it, make sure you have a Postgres (https://www.postgresql.org/download/) installed. Then run `rake db:create && rake db:migrate && rake db:seed && rails s`. This will initialize the database with Tarot cards and a place to store user information. 

This project is a combination of two Github repositories which can be originally found here: 

tarot-vr-frontend: https://github.com/cjunks94/mod4proj
tarot-vr-backend: https://github.com/SaigeXSaige/tarot-vr-api
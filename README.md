![lasvegas-list cover image](https://github.com/wo1vin/lasvegas-list/blob/main/assets/lasvegas-list-cover.png?raw=true)

# Introduction

The project was built to take the hassle out of where to go in Las Vegas so that tourists can spend more time having fun and less time browsing the internet.
Initially developed collaboratively with a small, global team of software developers implementing the MVC Architecture and "authorization" so folx can sign up and personalize their experience.  

---

# Objectives

- Build a MVP (Most Viable Product) that enables users to create a list of Las Vegas attractions, and cross out other pre-stored locations categorized into other lists.

---

# Who is this for? 

- Built for Las Vegas tourists of all walks of life. Wether they want the classic tourist experiences or something more tailored to their interests.

---

# Packages/Dependencies used 

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

# MVC Structure

![lasvegas-list MVC Structure](https://github.com/wo1vin/lasvegas-list/blob/main/assets/lasvegas-list-mvc.png?raw=true)

---

# Developers❗️ 

- ❗️ Create a .env file in the config/ folder and store your `PORT` and `DB_String` variables in it.❗️

- Install all the dependencies or node packages used for development via Terminal with `npm install`.

---

# Future Optimizations

- Enable users to view more details and options when they click on a pre-stored location such as:
    - Add attraction to their custom list
    - Like/heart/favorite attraction
    - See the location's address, hours, phone, or website
    - Follow link to Yelp/Google Reviews
- Map that pinpoints attractions or their pickup locations. Lets users click pinpoint to view location info, gives the option to 'add to list' or 'save'.
- Enable users to add known locations to their list by integrating a map API so it auto populates the right information. Ex: 
    - User starts typing "Stea"
    - A drop-down appears of the nearest steakhouses
    - User selects one from drop-down
    - The app pulls the location data (address, #, etc) and submits it to the Attractions model.


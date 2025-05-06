# Description


* Developed a full-stack expense tracking web application using Spring Boot, React.js, and MySQL, facilitating seamless management of day-to-day finances.
 * Developed intuitive user dashboards, transaction management, upcoming/recurring transactions tracking, monthly summaries, and statistics, budget management.
 * Developed categories, users and transactions management for administrators.
 
# How to run?

### Step 1: Fork and Clone the Repository

<small>1.  Fork the repository to your GitHub account.</small><br/>
<small>2.  Clone the forked repository to your local machine.</small>


### Step 2: Setting up e-mail and database configurations

<small>Configure the following credentials in the application.properties file.</small>

```
spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.mail.username=YOUR_USERNAME
spring.mail.password=YOUR_PASSWORD
```
### Step 3: Run the backend
* Run the backend application. It will automatically create the required tables.
* Add some custom data manually in the categories table for both type expense and income.
* To start as admin, Insert a new user manually with role admin in users table.

### Step 4: Run the frontend
1. Navigate to frontend direcory.
```
cd frontend
```
2. Install dependencies.

```
npm install
```

3. Run the app

```
npm start
```


😎 Access the application at [http://localhost:3000/](http://localhost:3000/). To get started create a new account using your email.

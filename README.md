
# Packt Assessment (Frontend/Customer Facing Portal)

A project is about to build a Customer Facing Portal (Frotnend) for the bookstore where admin can add, edit, delete the books and customers can search for a book and see the whole details about the book through beautiful User Interface.

## Author

- [@ronaksolanki10](https://github.com/ronaksolanki10)


## Tech Stack

**Framework:** Vue.js (The Progressive JavaScript Framework), Bootstrap



## Installation

Below is the steps to install the project

1. Clone the project
```bash
  git clone https://github.com/ronaksolanki10/interview_packt_frontend.git
```
2. Install dependencies


```base
    npm install
```
3. Create ``` .env``` file & add below Environment variable in it

```base
    VUE_APP_API_BASE_URL=<API_BASE_URL>/api
    VUE_APP_NAME="Book Store Management"
    VUE_APP_ADMIN_API_URL="${VUE_APP_API_BASE_URL}/admin"
    VUE_APP_FRONTEND_API_URL="${VUE_APP_API_BASE_URL}"
```
#Note:

1. Replace ```<API_BASE_URL>``` with API Base URL (A URL of the project where backend/API project has been setup)
2. You can also create a seperate ```env``` file for different different Environment like ```.env.local```, ```.env.development ```, ```.env.production ```
## Run/Deploy Project

To run the project in local machine

```base
    npm run serve
```
To deploy the project run

```bash
  npm run build
```
and upload files created under ```/dist``` folder


## Portal Access

 1. Admin

URL - https://domain.com/admin

Login Credential
- Email: admin@packtinterview.com
- Password: admin!15@45

###

2. Customer/Frontend

URL - https://domain.com

Note: Replace ``` domain.com``` with the domain name where the projects are installed



## Screenshots of the customer facing screens

1. Books listing with filter
![App Screenshot](https://i.imgur.com/yjUSg23.png)

2. Book Details

![App Screenshot](https://i.imgur.com/AptquW0.png)
## Feedback

If you have any feedback or query, please feel free to reach out to me at ronaksolanki1310@gmail.com


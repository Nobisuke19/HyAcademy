
# HYAcademy

HyAcademy is basically an online learning plantform liike udemy or courseera


## Authors

- [@Nobisuke19](https://github.com/Nobisuke19)


## Installation

Install my-project with npm

```bash
  git clone https://github.com/Nobisuke19/HyAcademy.git
  cd HyAcademy
```

Install Dependencies

```bash
npm install
```




Run the project 
```bash
npm run dev
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`

`CLERK_SECRET_KEY`

`NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in`
`NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up`
`NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/`
`NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/`


`DATABASE_URL="mysql://root:@localhost:3306/hyacademy"`

`UPLOADTHING_SECRET=`
`UPLOADTHING_APP_ID=`

`MUX_TOKEN_ID = `
`MUX_TOKEN_SECRET = `

`STRIPE_API_KEY = `

`NEXT_PUBLIC_APP_URL = http://localhost:3000`

`STRIPE_WEBHOOK_SECRET = `

`NEXT_PUBLIC_TEACHER_ID =`

## Documentation

admin(Teacher):
gmail:subham019650@gmail.com
password : Admin@193102


## Features

- Admin panel / Teacher Mode
- Add couse, delete course, update course publish course
- Can enroll by paying through stripe
- Fully responsive


## Tech Stack

**Client:** Next, , TailwindCSS, typescript

**Server:** Node, Express, axios

**DB:** mySql, prisma

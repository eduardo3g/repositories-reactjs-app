# repositories-reactjs-app

<p align="center"><img src="https://media.licdn.com/dms/image/C4D22AQG_mILl0Ej69g/feedshare-shrink_1280/0?e=1575504000&v=beta&t=GejBSeYXjtTrkt1kS2Zs2LvRubKmqIW_NSKeXdUcnbk"></p>

# GitHub Repositories using ReactJS

This is a simple web application consming GitHub's public API and list all issues of all added repositories.

# What I used to develop this application:

- ReactJS
- Babel
- Webpack
- Webpack Dev Server
- Styled Components
- React Router DOM

# Tools

- Just VS Code as usual.

# Features

- User management (Administrators and Students)
- JWT Authentication (Tokens)
- Session management via token
- Plan management (e.g: Basic Plan - U$D45,00/month - Duration: 3 months)
- Registration management: having a student on the database doesn't mean he/she has a registry. Each user can have a registry in the gym containing his ID, plan information, start date, end date and price calculated automatically
- When a user is registered he/she receives a e-mail (Nodemailer) containing useful information (plan, start date, end date and price)
- Help orders management: students can send question to the gym staff. Whenever it is answered the student receives an e-mail with his question and answer.
- The e-mail system is managed using Queues in order avoid latency to the final user.
- Checkin management: user can checkin when they arrive at the gym, but they can only apply five checkins in a period of seven days.

- Access GitHub public API
- Retrieve repository data
- List all of the repository issues
- Pagination on issue list page
- Filter issues by opened, closed or all of them

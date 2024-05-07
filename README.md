# bodhi-challenge
Challenge assignment for bodhi-software

Create a responsive React / NextJS application that allows for user creation as well as management of created users / user details. The creation process should include a multi-step form, that persists data across the steps. User Management page should include a full featured table. Application should include at least one example of overriding / custom CSS. API Information is provided below storing / retrieving the users. The API will provide one default user, that should be prohibited from being able to be modified (User will be “Default User”). Information about the Default User will be randomly updated on the API side and events will be emitted through the SSE endpoint below. In addition, any create / update / delete to a user will also trigger an event.

Points of Review may include but not limited to the following items –

· State Management

· Code Organization

· Error Handling / Validation

· End User Experience

Feel free to add any additional logic / behavior / testing that you feel would contribute to a production ready application.

The task time allotment is three hours to complete as much as possible. The code should be submitted via a Github Repo. At minimum there should be an initial commit at the start of the challenge, and a final one when complete and/or at the three-hour mark. Additional commits throughout the challenge are suggested.

API Information – URL - https://challenge.bodhilabs.dev

Auth Scheme: Basic

Login Credentials – User: test Password: user

Supported User Endpoints

findAll – GET /users

findOne – GET /users/resourceId

create – POST /users

update – PATCH /users/resourceId

delete – DELETE /users/resourceId

SSE for Live Updates – GET /users/events (This endpoint is not protected at this time) 

# DTO image
<img width="633" alt="image" src="https://github.com/RobOsipo/bodhi-challenge/assets/90695804/c9018934-6ff8-4062-a748-c363c1796a8e">

# DTO image continued...
<img width="633" alt="image" src="https://github.com/RobOsipo/bodhi-challenge/assets/90695804/8c6b312a-140f-45ca-8f0d-5ecd35477bbe">



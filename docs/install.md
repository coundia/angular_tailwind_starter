mkdir -p src/app/core
mkdir -p src/app/shared
mkdir -p src/app/features

ng g service core/services/auth
ng g service core/services/api


touch src/app/core/models/message.model.ts
touch src/app/core/models/user.model.ts

ng g component features/auth/login-page --standalone
ng g component features/auth/register-page --standalone


touch src/app/app.routes.ts
touch src/app/features/auth/auth.routes.ts

ng g guard core/guards/auth --implements CanActivate


npm install @angular/material socket.io-client rxjs 

[https://tailwindcss.com/docs/installation/framework-guides/angular](https://tailwindcss.com/docs/installation/framework-guides/angular)

npm install -D tailwindcss @tailwindcss/postcss postcss --force


npx tailwindcss init --postcss

 

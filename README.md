# Admin Dashboard - Store Challenge

Develop a SPA (Single Page Application) using Angular to manager products, orders using public API (FakeStoreAP['https://fakestoreapi.com/']) and implement a clean architecture with NgRx and RxJS

The goals of the challenge:

- Knowledge in state management with NgRx
- Use of RxJS operators
- Good practices of Angular architecture
- Clean code and organized project
- Autonomy and technical decision-making capacity

You have 1 week to develop the challenge and in the end 30 minutes to make a presentation of the project
The goal is not the UI/UX but the architecture, organization and good practices of Angular + Ngrx or RxJS (you're welcome to use any visual library you want since you can justify your option)

Presentation idea:
- 10 min: Functional Demo
- 15 min: Technical Explanation (architecture, NgRx, RxJS and code decisions)
- 5 min: Questions & Doubts


# Functional Requeriments

[ ] Display Products

- Use Ngrx (Actions, Reducer, Selectors, Effects) to seacrh and store the Products
- Create a filter to filter by category (using RxJS operators)

[ ] Details of Product

- Click on a product item, we can navigate to another screen: Details of the Products
- Should search product information using Effect (don't allow to make the request inside the component)

[ ] Shopping Cart

- Add or delete products
- The state management must be persisted using @ngrx/store-localstorage or localStorage

[ ] Errors handlers and loading states

- Display loading or errors from state manegement of Ngrx

# Good practices

- Using modular structure
- Use standalone components or signals (if it's necessary)
- Create clean architecture between (UI, state management, services and components)

# References

- Angular['https://angular.dev/']
- Ngrx['https://ngrx.io/']
- RxJS ['https://rxjs.dev/']
- Ngrx-Spinner ['https://www.npmjs.com/package/ngx-spinner']
- Redux DevTools ['https://chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd']

# Before start

- Create a fork repository in your own Github and use your personal repository to make all the changes
 (**It's really important create the repository and send to us the url link to follow the evolution of the development during the week of the challenge**)

# Tips

- You can use Redux DevTools to help you to check the state management of the application

# Bonus

- Create documentation explained the architecture and decisions
- Use a clean UX (loading, display of errors and display messages feedbacks)
- Use NgRx Entity
- Use lazy loading (if you think it's necessary)
- Use OnPush or Async Pipe
- Create guards routers considering the state management
- Implement unit tests of reducers, selectors, services and components
- Deploy the application on some platform as StackBlitz, Vercel, Netlify or others

# Setup

npm install
npm start


# Good luck!
We're interesting in know how you think and structure an Angular application. More than a visual look, we would like to see your technical reasoning and architectural decisions.

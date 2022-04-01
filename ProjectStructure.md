```
─ src
  ├─ api => For calling API functions
  │  ├─ axiosClient.ts  => Create a custom axios object to handle request and response
  │  ├─ cityApi.ts => For each purpose create a specific api file
  │  └─ studentApi.ts
  ├─ app
  │  ├─ hooks.ts
  │  ├─ rootSaga.ts => This file import all feature saga files
  │  ├─ store.ts
  ├─ App.css
  ├─ App.test.tsx
  ├─ App.tsx
  ├─ components => For common components, layouts, etc.
  │  ├─ Common
  │  │  ├─ Header.tsx
  │  │  ├─ index.ts
  │  │  ├─ NotFound.tsx
  │  │  ├─ PrivateRoute.tsx => Custom route for authenticate route(need to login to use)
  │  │  └─ Sidebar.tsx
  │  ├─ FormFields
  │  │  ├─ index.ts
  │  │  ├─ InputField.tsx
  │  │  ├─ RadioGroupField.tsx
  │  │  └─ SelectField.tsx
  │  └─ Layout
  │     ├─ Admin.tsx
  │     └─ index.ts
  ├─ features
  │  ├─ auth  => Each feature we create a specific folder
  │  │  ├─ authSaga.ts  => Set up Saga for feature
  │  │  ├─ authSlice.ts => Set up redux's actions and reduce for feature
  │  │  └─ pages => If there are many pages, store in this folder
  │  │     └─ LoginPage.tsx
  │  ├─ city
  │  │  ├─ citySaga.ts
  │  │  └─ citySlice.ts
  │  ├─ counter
  │  │  ├─ Counter.module.css
  │  │  ├─ Counter.tsx
  │  │  ├─ counterAPI.ts
  │  │  ├─ counterSaga.ts
  │  │  ├─ counterSlice.spec.ts
  │  │  └─ counterSlice.ts
  │  ├─ dashboard
  │  │  ├─ components => If there are many components, store in this folder
  │  │  │  ├─ StatisticItem.tsx
  │  │  │  ├─ StudentRankingList.tsx
  │  │  │  └─ Widget.tsx
  │  │  ├─ dashboardSaga.ts
  │  │  ├─ dashboardSlice.ts
  │  │  └─ index.tsx
  │  └─ student
  │     ├─ components
  │     │  ├─ StudentFilters.tsx
  │     │  ├─ StudentForm.tsx
  │     │  └─ StudentTable.tsx
  │     ├─ index.tsx
  │     ├─ pages
  │     │  ├─ AddEditPage.tsx
  │     │  └─ ListPage.tsx
  │     ├─ studentSaga.ts
  │     └─ studentSlice.ts
  ├─ index.css
  ├─ index.tsx
  ├─ logo.svg
  ├─ models => For typeScript, save type of data recieve from server
  │  ├─ city.ts
  │  ├─ common.ts
  │  ├─ index.ts
  │  ├─ student.ts
  │  └─ user.ts
  ├─ react-app-env.d.ts
  ├─ serviceWorker.ts
  ├─ setupTests.ts
  └─ utils
     ├─ common.ts
     ├─ history.ts => settup for custom history
     └─ index.ts

```
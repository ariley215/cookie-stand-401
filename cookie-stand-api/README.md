# api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

# Feature Tasks

All features from versions 1 an 2 should be complete.
The specs for lab are screen shots Cookie Stand Admin Version 3 and Cookie Stand Admin Login
pages/index.js should export a <Home> component.
<Home> requirements
If user is NOT logged in then <LoginForm> should render.
If user IS logged in then <CookieStandAdmin> component should render.
<LoginForm> requirements
Should receive a function passed in to call when form is submitted.
The function should be called with username and password arguments.
<CookieStandAdmin> requirements
When user fills out form to add location then the data should be posted to API
When API response is complete then <CookieStandTable> should render latest data immediately.
Should NOT require a page refresh.
<CookieStandTable> requirements
Component should continue to display Cookie Stand info as in version 2
Add a delete icon in each stand’s location cell.
Clicking delete icon should immediately delete the Cookie Stand.
Should NOT require a page refresh.
Continue to style all components using TailwindCSS utility classes to match spec.

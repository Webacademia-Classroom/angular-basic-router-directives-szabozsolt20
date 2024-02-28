# Practices

## Setup the project

- Set the current directory as the workspace: `code ./ -r`
- Install dependencies: `npm i`
- Run the development server: `npm start`
- Open the product page in the browser: http://localhost:4200

## Tasks
- You work only in the AppComponent and TopNavComponent
1. Generate a component for the navigation:
  - TopNavComponent: common/top-nav
  - Include a primary navigation in it: 
  https://getbootstrap.com/docs/5.3/components/navbar/#nav

2. Setup routerLinks in the TopNavComponent based on the settings 
in the [app.routes.ts](src/app/app.routes.ts) file

3. Place TopNavComponent into the AppComponent on the top
4. Place the RouterLink at the bottom of the AppComponent template

## Testing

- `npm test`

## Further helps

__WARNING! You must include RouterModule in the import array of components that use routerLink or router-outlet.__

### Setting up routerLinks

- Valid setup of the RouterLink directive (links always start with /):

```html
<a class="nav-link" routerLink="/about">About</a>
```

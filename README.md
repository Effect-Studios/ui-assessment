# UI Assessment

# Design file
https://www.figma.com/file/fO9SrIq6PCQSoJ8iqT0A3O/Sample-UI?node-id=1%3A2

# Assets
- [Icons](./assets/icons)
- [Images](./assets/images)

### Font
[Montserrat](https://fonts.google.com/specimen/Montserrat?query=mont)

# API
Docs: https://camiestas-futbol.effectstudios.co/api/docs <br>
Base URL: https://camiestas-futbol.effectstudios.co/api

#### Banners
```shell
GET https://camiestas-futbol.effectstudios.co/api/v1/banner
```
#### Popular products
```shell
GET https://camiestas-futbol.effectstudios.co/api/v1/popular-products
```
#### Product collections/categories
Slugs for `Country Leagues` and `Other Collections` can be found in the results returned from this endpoint
```shell
GET https://camiestas-futbol.effectstudios.co/api/v1/product-category
```
#### Single collection/category
```shell
GET https://camiestas-futbol.effectstudios.co/api/v1/product-category-slug/{slug}
```
#### Single product details/information
```shell
GET https://camiestas-futbol.effectstudios.co/api/v1/product-single/{slug}
```

# Objectives
- Build the UI to match the design as closely as possible.
- Integrate the UI with the backend using the API provided above.
- Animations/Micro-interactions are not required but would be a plus.

# Requirements
### Programming Language
- Typescript
  
### Web Framework (Any of)
- [Nextjs](https://nextjs.org/)
- [Nuxt 3](https://v3.nuxtjs.org/)

### UI library (Any of) 
- [TailwindCSS](https://tailwindcss.com/)
- Vanilla CSS or SCSS

# Deadline
72hrs after you've accepted the invitation to the Figma file.

If you have any questions, do leave them in the discussions panel and mention @pyplacca in it. You can also send an email to the correspondent.

# Submission Instructions
1. Create a deployment link.
2. [E-mail](mailto:david@effectstudios.co?subject=Submission:%20Frontend%20Developer%20Assessment) the links of the deployment and Github repository.

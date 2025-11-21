# We love web - Trystian Offerman 

## Design system

### Inleiding
- A retail sports company
- French company
- Active in 79 countries: online and offline
- Offices in Lille, Partis, Nates and Amsterdam
- In amsterdam maken ze een e-commerce website voor de 16 grootste landen. 
- Amsterdam Hub: gericht op de data en e-commerce


### E-commerce
- Upper funnel: alles tot de checkout, totdat je gaat betalen. Homepagina, search, listpage. Bestaat uit een navigatie teaM, Product oage, inspire price and promo, CMS team (Gaat om snelheid, anders verlies je klanten), recommendations, product API, Catalog, search and raking, SEO. 
- Lower funnel: basket, login, check-out

### Product page team
- Engineering manager
- Product manager: gaat over de features die ze gaan aanbieden op een product page. werkt samen met de designers
- Designers
- Content design
- UX Design
- Frontend developers


### The frontend Stack
- Next.js: js via typescript. verwachtingsmanagement van het systeem. Is a react framework for building full-stack web applications. It combines server-side rendering, static site generation, routing, and data fetching into a single developer experience, making modern apps faster to build and easier to deploy
- React voor componenten
- Node: voor de back-end

### One repository
- A deploy every dat to all countries


## What about design systems?

### Defintion of a design system
- A design sytem is a central, shared source of thruth that contains the visual, interaction and code standards used to build a consistent user experience. Vitamin play is the design system by Declaton. 


### What is on our design system?
- A suite of guidelines, reusable components, modules and templates including: Embedded design okens, multi platform and internationalization, accessibility compliance, theming and modes.


### The styleguide of decathlon
- Brand kleuren
- Accent kleuren 
- Neutral kleuren
- Typography: web en print hebebn eigen font
- Spacings
- Responsive grids
- Icons
- Assets
- Email kit

### These foundations are converted in design tokens
- Cobalt-500 (essential design elements)
- Deze kleuren komen ook terug in code en figma
- Design and engineering speak the same language because the design tokens are used in Vitamine play - native design.


### Wht did we move to a design system
- Its an huge investment
- Consistency: consistent and cohesive experience across our products and platforms
- Eddiciency: streamlines design and development process. Enabling faster products
- Scalability: Easy to scale design and development without sacrificing quality. nadeel dat als het design systeem stuk is dat dan andere dingen ook stuk gaan
- Improved collaboration: better collaboration between design and development, you speak the same language
- Quality: Enhancing quality of the user interfaces, by using established design best practices: niet iets wat iemand snel heeft bedacht
- Accessibility: components from the design systems are engineerd with accessinility in mind. So its not an after thought.
- Onboarding and traning

### Code
- Frameworks: React, Svelte, Vue. Would not recommend to use three frameworks in a design system. 
- Sveltekit: Gehele checkout is gebouwd in svelte. Interne discussie of alles wordt omgezet in react of svelte of een combinatie. 

## Front-end libary
- Foundations: colors, assets, icons, typograpght, border, spacing, motion
- Components: buttons, 
- WHhen rendered in the broweser ist has all the normal button properies and is made accessibily.


### Make sure your components are..
- Composale
- flexible
- Accessible
- Themed
- Well documented: wat doet het component, hoe maak je ze accessible
- Consistent: overal hetzelfde uitzien
- Stable and predictable

### What should not be in a design system
- Page specific of flow specific UIs
- Complete pages
- Highly coupled to backend/domain logic: iets wat ook maar te maken heeft met de backend
- One offs
- Experiments
- Things which are specific to one product


### Developer portal
- Guidelines welke properties er op een component zitten en welke properties je kan gebruiken. 
- Gekoppeld met typescript zodat er geen fouten in staat. 



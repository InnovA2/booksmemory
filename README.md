<h1 align="center">
  <img src="https://user-images.githubusercontent.com/8389829/114069915-ca870380-989f-11eb-9685-0f5bbe44ee9b.png" alt="BooksMemory" width="25%"/>
  <br>
  <i>BooksMemory</i>
</h1>

Web service with a complete dabatase of books to fetch information about them by ISBN, search...

*Project WIP : The project is currently in development and is only used by [MyBooksMemory](https://github.com/InnovA2/mybooksmemory). It will soon be open to the public.*

- [Modules](#gear-modules)
  - [BooksMemoryApi](#booksmemoryapi)
  - [BooksMemoryFront](#booksmemoryfront)
  - [BooksMemoryScraper](#booksmemoryscraper)
  - [BooksMemoryAdminPortal](#booksmemoryadminportal)
  - [BooksMemoryDevPortal](#booksmemorydevportal)
- [Public links](#link-public-links)
- [Authors](#busts_in_silhouette-authors)

## :gear: Modules
### BooksMemoryApi
This is the main entry point for our project. Using this service requires an API key that can be retrieved through the [BooksMemoryDevPortal](#booksmemorydevportal), which is currently under development. For the moment, only our 2nd project, [MyBooksMemory](https://github.com/InnovA2/mybooksmemory) has a developer account. This web service allows to:
- retrieve lists of series and books through different search modes
- retrieve upcoming book releases
- retrieve the complete information of a book via its ISBN
- discover a book in a random way
- add missing books in our database

Technologies used:
- NestJS
- TypeScript

### BooksMemoryFront
This module is a showcase site whose objective is to present the concepts of the project.

Technologies used:
- Angular
- Ngx Materialize

### BooksMemoryScraper
This module allows us to orchestrate the recovery of information from books on the web, ensuring a certain quality of the data.

Technologies used:
- Symfony
- Goutte (using Symfony DomCrawler component)

### BooksMemoryAdminPortal
This module allows us to manipulate all information relating to books, like the creation / modification / deletion of books and series but also approval of books added by developer accounts.

Technologies used:
- Angular
- PrimeNG

### BooksMemoryDevPortal
The developer portal allows developers to register in order to retrieve an API key and manage their API call quota. They thus have access to the list of calls made via their API key.

Technologies used:
- Angular
- PrimeNG

## :link: Public links
- [Front](#) - WIP : coming soon
- [API](#) - WIP : coming with Developer Portal
- [Developer Portal](#) - WIP : coming with API

## :busts_in_silhouette: Authors
- [Adrien MARTINEAU](https://github.com/WaZeR-Adrien)
- [Angéline TOUSSAINT](https://github.com/AngelineToussaint)

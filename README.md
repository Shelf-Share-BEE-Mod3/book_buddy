# Book Buddy

A microservice for looking up book information by ISBN. Built to support [the ShelfShare app](https://github.com/Shelf-Share-BEE-Mod3/shelf-share-rails).
ShelfShare and Book Buddy were built in 9 days for a Turing School of Software and Design - Module 3 group project.

Complies to the [JSON API Spec](https://jsonapi.org/).

## Versions

sinatra (2.1.0)

ruby 2.5.3

## Setup and Installation

## Usage and Endpoints

Search for a book by ISBN_13

`GET https://still-ridge-56956.herokuapp.com/search?isbn=<YOUR_BOOK_ISBN>`

### Example Request and Response

`GET https://still-ridge-56956.herokuapp.com/search?isbn=9781775417415`

```JSON
{
  "data": {
    "id": null,
    "type": "book",
    "attributes": {
      "title": "The Wings of the Dove",
      "author": "Henry James",
      "description": "Young Londoners Kate and Merton are engaged, but have no money to marry on. When the wealthy but terminally ill American heiress Milly arrives in London, Kate schemes for a way to inherit her fortune. But when Kate achieves all she had hoped for, she finds that the money and the gentle, beautiful Milly have changed everything.",
      "thumbnail": "http://books.google.com/books/content?id=iTeEpRJogFMC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api",
      "isbn": "9781775417415",
      "category": "Fiction"
    }
  }
}
```


## Contact

     Phillip S - [![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/phillipstrom/) - [GitHub](https://github.com/Strompy) - [Email](mailto:phillip.strom@gmail.com)

     AJ Tran - [![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/ajtran-dev/) - [GitHub](https://github.com/ajtran303) - [Email](mailto:anh.jamietran@gmail.com)

    Lito White - [![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/litowhite/) - [GitHub](https://github.com/ljwhite) - [Email](mailto:leland.white@gmail.com)

 Jonathan Wilson - [![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/jonathan--wilson/) - [GitHub](https://github.com/Jonathan-M-Wilson) - [Email](mailto:jonathanmorrillwilson@gmail.com)
 
 
 <!-- MARKDOWN LINKS & IMAGES -->

 [linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555


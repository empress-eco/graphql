<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Empress-eco GraphQL logo">
</div>

<p align="center">
Empress-eco GraphQL provides a robust and efficient API layer for the Framework
<br />
<a href="https://empress.eco/"><strong>Explore the Docs »</strong></a>
<br />
<br />
<a href="https://github.com/empress-eco/graphql/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/graphql/issues">Request Feature</a>
</p>

## About The Project

Empress-eco GraphQL is a powerful API layer built specifically for the Framework. It introduces a structured and efficient way to fetch and manipulate data from your Empress applications using GraphQL. This project is ideal for developers who work with Empress applications and need a streamlined programmatic interaction interface.

### Key Features
- Query individual Documents and obtain a filtered doctype list
- Access Field Linked Documents in nested queries
- Restrict Query/Mutation depth for optimized performance
- Use Subscriptions to get real-time updates via Empress's SocketIO
- Upload Files following the GraphQL multipart request specification
- Integrated RolePermission for enhanced security
- Standard Mutations: set_value, save_doc & delete_doc
- Implement Pagination using cursor-based technique
- Support Extensions via Hooks for further customization

### Built With
Empress-eco GraphQL is built using:
- [Python](https://www.python.org/)
- [GraphQL](https://graphql.org/)

## Getting Started

To get started with Empress-eco GraphQL, ensure you have a running Empress application. 

### Installation

Clone the repository using the link below:
```
https://github.com/empress-eco/graphql.git
```

Next, generate the sdl's:
```sh
$ bench --site test_site graphql generate_sdl
```
Now, you can start making your GraphQL requests against:
```sh
/api/method/graphql
```

## Usage

You can query a single document by its name using `<doctype>` query. Similarly, a list of documents can be fetched by querying `<doctype-plural>`. Filters and sorting details can be passed as arguments. 

To access Field Linked Documents in nested queries, all Link fields return the respective document. Add `__name` suffix to the link field name to get the link name.

For detailed examples and usage instructions, refer to the [documentation](https://empress.eco/).

## Contributing

We warmly welcome contributions! Here's how you can contribute:

1. [Fork the Project](https://github.com/empress-eco/graphql/fork)
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is under the MIT License. Your contributions are also licensed under the MIT License.

## Acknowledgements

We extend our heartfelt thanks to all contributors who have helped make Empress-eco GraphQL a reality. Your efforts have significantly contributed to the success of this project. 

Special thanks also goes to the Empress Community, the architects behind the essential tools that power this project. Your innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for your pioneering work and ongoing support.
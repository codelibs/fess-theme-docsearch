# Fess Theme: Doc Search

This project provides the `Doc Search` view template for the Fess Theme. For more details, visit [docsearch.codelibs.org](https://docsearch.codelibs.org/).

## Getting Started

### Installation

To install the Fess Theme, please refer to the [Plugin Guide](https://fess.codelibs.org/14.14/admin/plugin-guide.html).

### Configuration

To configure and use the installed theme, follow these steps:

1. Set the `Host` parameter in the General Configuration's [Virtual Host](https://fess.codelibs.org/14.14/admin/general-guide.html#virtual-hosts) section:

```
Host:localhost:8080=docsearch
```

2. Add `docsearch` to the [Virtual Host](https://fess.codelibs.org/14.14/admin/webconfig-guide.html#virtual-hosts) section of the Crawling Configuration.

## Additional Information

### File Structure

- **src/main/resources/view**: Contains JSP files.
- **src/main/resources/images**: Contains image files.
- **src/main/resources/css**: Contains CSS files.

For further details and support, visit the [Fess Documentation](https://fess.codelibs.org/).

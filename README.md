# Crawler.net

Very simple web crawler using automatas
Actually Mails and URLs are implemented (at least, parcially)

## Usage

Clone the repository and use the `dotnet` CLI to run.

Example

```bash
git clone https://github.com/EdsonReza/Crawler.net.git
cd Crawler.net

dotnet run -- https://google.com/
```

The automatas implementation is in `Classes/Automatas`

## ToDo

- [ ] Fix search in depth
- [ ] support for the ability to recognize if the url does not belong to a resource like images, pdf, etc

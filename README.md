# CS200

Access information available on Wikipedia in a way that is optimized for consumption. Instead of parsing a Wikipedia page for keywords, symbols, and nuanced content, let CS200 access, process, and provide that information in the best way possible. 

## Installation 
Windows:
```
    pip install cs200
```
Ubuntu:
```
    [sudo] pip3 install cs200 
```

Now use the tool provided by the application to install any missing requirements.
``` 

cs200-install

```

## Usage
The following command will optimize the Wikipedia page computer programming, or related articles, and limit the response (if possible) to 3 units of content. Finally, it will output this into a file of your choice (using the --output directive)
```bash 
     cs200 --concept "computer programming" --limit 3 --output results.txt
```

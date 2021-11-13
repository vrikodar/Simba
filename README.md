# Simba

<p align="center" >
  <img src="https://github.com/SxNade/Simba/blob/main/simba.png" width="400"/>
</p>

**Simba is a web headers security scanner**

## Installing and Running Simba 💻

```bash
$ git clone https://github.com/SxNade/Simba
$ cd Simba
$ chmod +x simba

$ ./simba --help
```

## Simba Options 🐯

**Listing Help**
```bash
$ ./simba --help
```

### Specifying File containing website URLs `one at each line` or `individual links`
```bash
$ ./simba --file /path/to/file.txt

$ ./simba --link https://google.com/ 
```
### Specifying Proxy for connections made `protocol://<IP>:<port>` 
```bash
$ ./simba -l https://google.com/ --proxy socks5://127.0.0.1:1080
                  
                    or

$ ./simba -f file.txt -p socks5://127.0.0.1:8080
```

### Specifying custom user agent Header `Default is None` 
```bash
$ ./simba -l https://google.com/ --useragent chrome_win    {you can see all available options by choosing a random non-existent option xd}

                or

$ ./simba -l https://google.com/ -u firefox_mac            {there are a number of useragents available, write a wrong one to get a list all that are available!}
```

## Demo 💻

![](https://github.com/SxNade/SxNade.github.io/blob/main/simba.gif)

# Future Updates 🕒

**Note:** Options such as specifying proxies etc.. and much more would be addded in future updates


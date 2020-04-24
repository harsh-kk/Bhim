<h1 align="center">
  <br>
  <a href="https://github.com/harsh-kk/Bhim"><img src="https://i.ibb.co/2j8C1M2/gada.png" alt="Bhim"></a>
  <br>
  Bhim
  <br>
</h1>

<h4 align="center">HTTP Parameter Discovery Engine</h4>

<p align="center">
  <a href="https://github.com/harsh-kk/Bhim/releases">
    <img src="https://img.shields.io/badge/release-1.1-yellowgreen">
  </a>
  <a href="https://twitter.com/xploitprotocol">
      <img src="https://img.shields.io/twitter/url?logoColor=green&style=social&url=https%3A%2F%2Ftwitter.com%2Fxploitprotocol">
  </a>
</p>

![demo](https://i.ibb.co/g9hm3c3/Screenshot-from-2020-04-24-18-05-13.png)

### Introduction
Web applications use parameters (or queries) to accept user input, take the following example into consideration

`http://api.example.com/v2/userinfo?id=751658590`

This URL seems to load user information for a specific user id, but what if there exists a parameter named `admin` which when set to `True` makes the endpoint provide more information about the user?\
This is what Bhim does, it finds valid HTTP parameters with a huge default dictionary of 25,980 parameter names.

The best part? It takes less than 30 seconds to go through this huge list while making just 50-60 requests to the target.\
Want to know how Bhim does that? [Here's how](https://github.com/harsh-kk/Bhim/wiki/How-does-Bhim-works%3F).

### Features
- Multi-threading
- Thorough detection
- Automatic rate limit handling
- A typical scan takes 30 seconds
- `GET/POST/JSON` methods supported
- Huge list of 25,980 parameter names

> **Note:** Bhim doesn't work with python < 3.4

#### How to use Bhim?

A detailed usage guide is available on [Usage](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim) section of the Wiki.

An index of options is given below:

- [Scanning a single URL](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#scanning-a-single-url)
- [Scanning multiple URLs](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#scanning-multiple-urls)
- [Choosing number of threads](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#multi-threading)
- [Handling Delay between requests](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#delay-between-requests)
- [Handling Rate limits](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#handling-rate-limits)
- [Delay between requests](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#delay-between-requests)
- [Including Presistent data](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#including-persistent-data)
- [Saving Output to a file](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#saving-output-to-a-file)
- [Adding custom HTTP headers](https://github.com/harsh-kk/Bhim/wiki/How-to-use-Bhim#adding-http-headers)

##### Credits
The parameter names are taken from [@SecLists](https://github.com/danielmiessler/SecLists).

#### contact
> Get in touch [twitter](https://twitter.com/xploitprotocol)

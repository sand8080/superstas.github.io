# io.Reader custom implementations
##### What is it?
A list of custom io.Reader implementations from based on public github.com repositories.

##### Why?
I've often wondered how often developers write their own io.Reader implementations and why?

##### How?
1. Pulled a thousand repos by a filter: "language:Go+stars:>50"
2. The implementations were found with grep by Read signature. Some implementations like tests, dependencies(vendor, dep, etc.), unused code, etc. were filtered as well.

---
* [The list](https://github.com/superstas/superstas.github.io/blob/master/io_stats/custom_readers.md) of custom io.Reader implementations
* Github API responses can be found at resp_*.json files
* There is a prepared glide.yaml file to pull all found repos
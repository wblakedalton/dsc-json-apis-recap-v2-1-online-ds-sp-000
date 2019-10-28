
# JSON and APIs - Recap

## Introduction
In this section, you learned about the JSON file format, how to parse and navigate JSON files using the `json` Python module. You also learned about the HTTP request/response cycle and using APIs. APIs are critical to software development, and they can be powerful tools for gathering data for data scientists.

Before JSON files were widely adopted, XML files were used. You'll have a chance to learn about XML files in the Appendix for this section.

 

## Key Takeaways

In this section, we dug into a key format for storing and transferring data between applications - the JSON file format. We also covered APIs, which can provide access to a wide range of data that you might need as a data scientist.

Key takeaways include:

* JSON (JavaScript Object Notation) is a widely adopted format for storing and accessing data. It requires slightly less typing than XML to represent the same information so it has become increasingly popular over the last 10-15 years. 

* The JSON standard library in Python, `json`, is used for interacting with JSON data: https://docs.python.org/3.6/library/json.html

* While there are many other kinds of APIs, as a data scientist, you'll typically be working with web APIs. 

* The `requests` library in Python is a great starting point for making HTTP requests to APIs. 

* The two most common HTTP methods you'll use when accessing APIs are GET (to retrieve information) and POST (to send information). 

* Typically, you'll need to authenticate in some manner to gain access to most APIs - one common method for doing so is using OAuth. 

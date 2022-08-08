# REST
## Introduction to REST 
We are web developers and the moment we hear the word REST the image that pops up in our heads is not that of taking a break from work or having a nap, instead it is of REST API. It is also called Representational State Transfer. Nowadays it has become a necessity for building web platforms, mainly because it is easy to assemble and consume ability. First, let us understand what it does. REST API is basically a process of accessing web services in a simple manner and we don't have to undergo a lot of processing which reduces a lot of loads from our platform and saves a lot of time in useless processing. There is one more term that you should be familiar with and that is SOAP (Simple Object Access Protocol). It is basically a data sharing protocol, and it helps in exchanging structured data between various nodes. It works in a specific format to exchange messages. It is basically a layer above protocols like HTML and SMTP for transmission. It is not system dependent like it does not depend on the operating system, language, or platform you are using in your system. It works in its own virtual layer. It is used to retrieve or provide information from a web service. However, it is important to note that all the communications which are done through REST API are executed through HTTP requests. 

## Now let us understand the working of REST API. 
Suppose there is a client server which is in contact with main server, and it sends a request to the server in the form of web URL and there can be different methods of sending a request like HTTP GET/POST/PUT/DELETE request. Then once the main server has received the request then it sends back a response in the form of data which was request on the request. The format can be anything ranking from HTML, XML, Image, or it could be JSON format as well. JSON is the most used format across web platforms for exchanging data. 
There are 5 main methods which are used in REST architecture, and I've mentioned them in the above paragraph as well and I quote them again. 

1. POST
2. GET
3. PUT
4. PATCH
5. DELETE

It's not like these are the only methods used, there are more methods which are used like HEAD, OPTIONS etc. but they are not used much as compared to the above-mentioned ones. 

## Now let us understand the usage of the above-mentioned methods. 
1. POST: It is usually used to create a completely new resource. On successful creation of the resource, it responds back with HTTP status 201 and returns with the link of the newly created resource. 

2. GET: This method is used to read or retrieve information or resource. It returns with a HTTP response of 200 on success and comes back with the data which can be in the format of XML, JSON etc.

3. PUT: It is basically used to update the already present resource in the web apps. Although in some specific cases it can also be used to create a altogether new resource. If we update a resource, then on completion it responds with 200 HTTP status and if we are creating a new resource then it responds with HTTP status of 201. 

4. PATCH: It is like PUT method the only difference is that we only send the details that we want to change not the complete resource. 

5. DELETE: It is the simplest to understand, it is used to delete a resource and returns with HTTP req of 200 on succession. 

After reading this article, I hope you must have gained some understanding of the REST API and this would help you further in the journey of learning about APIs and REST.

## Some importent links 
https://www.redhat.com/en/topics/api/what-is-a-rest-api
https://www.ibm.com/cloud/learn/rest-apis

Thank You 

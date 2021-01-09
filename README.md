# sosi_crawler_api_controller
API Controller for SoSI's Crawlers

This is the documentation for SoSI's Crawler API Controller.

The main purpose of this component is to handle crawler's request to another APIs by posting & managing, asynchronously, the responses. This component **is not developed to handle requests towards the crawlers**, but **from the crawlers** -- to see the SoSI's Crawler Architecture, please refer to [this link](https://github.com/leonidasnascimento/sosi_crawler_executor). 

This component is supposed to meet the following technical requirements:
 - **Communication Pattern**
 - **Security**
 - **Synchronicity** 
 - **Logging**
 - **Throughput** 
 - **Error Handling**

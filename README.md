# sosi_crawler_api_controller
This is the documentation for SoSI's Crawler API Controller.

The main purpose of this component is to handle crawler's request to another APIs by posting & managing, asynchronously, the responses. This component **is not developed to handle requests towards the crawlers**, but **from the crawlers** -- to see the SoSI's Crawler Architecture, please refer to [this link](https://github.com/leonidasnascimento/sosi_crawler_executor). 

This component is supposed to meet the following technical requirements:
 - **Communication Pattern**: 
	 - Use JSON as message pattern;
	 - Prefer asynchronous message rather than synchronous. This should be the default behavior, transparent to the consumer, but easy to change;  
 - **Security**:
	 - All request from this component should be sent along with a secret, time span and the Crawler's ID. The secret should be a key identifying that the crawler is from SoSI platform; 
 - **Logging**
 - **Throughput** 
 - **Error Handling**

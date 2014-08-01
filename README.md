# Social media metatags templates

Social media metatags allows you to add social information to your website or contents.

When you are sharing an url to social networks, they will find the social information which you defined between head tags. It's with this feature that you can show a custom image when you share something on Facebook for instance.

In order to easily handle this routine on every project, we gather all the right metatags on this repository.

### Basics
```
	<title>Page Title. Maximum length 60-70 characters</title>
	<meta name="description" content="Page description. No longer than 155 characters." />
```

### Facebook
```
	<meta property="og:title" content="Title Here" />
	<meta property="og:type" content="article" />
	<meta property="og:url" content="http://www.example.com/" />
	<meta property="og:image" content="http://example.com/image.jpg" />
	<meta property="og:description" content="Description Here" />
	<meta property="og:site_name" content="Site Name" />
	<meta property="fb:admins" content="Facebook numeric ID" />
```

### Twitter
```
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:site" content="@publisher_handle">
	<meta name="twitter:title" content="Page Title">
	<meta name="twitter:description" content="Page description less than 200 characters">
	<meta name="twitter:creator" content="@author_handle">
	<meta name="twitter:image:src" content="http://www.example.com/image.html">
```

### Google + / Pinterest
```
	<meta itemprop="name" content="The Name or Title Here">
	<meta itemprop="description" content="This is the page description">
	<meta itemprop="image" content="http://www.example.com/image.jpg">
```    

### Google authorship
```
	<link rel="author" href="https://plus.google.com/[Google+_Profile]/posts"/>
	<link rel="publisher" href="https://plus.google.com/[Google+_Page_Profile]"/>
``

#How to test your metadatas

Each platform has his own tool to debug your metadatas 

## Facebook Debugger

https://developers.facebook.com/tools/debug

## Twitter validation tool

https://dev.twitter.com/docs/cards/validation/validator

## Google Structured Data Testing Tool

http://www.google.com/webmasters/tools/richsnippets

## Pinterest Rich Pins Validator

http://developers.pinterest.com/rich_pins/validator/
# __Full-Text Search__

Full-Text Search is a search engine, which helps to find a word or text in database documents specified by a user. Full-text search has three types,

* Natural-language Full-Text Search
* Boolean Full-Text Search
* Query Full-Text Search

The process of full-text search involves two tasks, namely **_index_** and **_search_**.

#### __INDEX:__

An Index is a process of listing all text or words related to the word specified by the user.

#### __SEARCH:__

Search is a process in which, it goes through the index listings instead of searching throughout all database documents.

### The popular search engines of Full-Text Search are __*Lucene*__, __*Solr*__, and __*Elastic*__ search engines

## __LUCENE__

* It is a Java library providing powerful indexing and search features, as well as spellchecking, hit highlighting and advanced analysis/tokenization capabilities.
* Both Apache Solr and Elasticsearch use Lucene as their search engine.
* It is a technique, that can be used for an application that needs a full-text engine.
* It is also useful for cross-platform applications (mobile apps).
* Object Pascal, Perl, C#, C++, Python, Ruby, and PHP are the programming languages that have been adapted to Lucene.
* It is used by __Linkedin__, __Twitter__, and many more.

## __ELASTIC SEARCH__

* Elastic search is a __*Lucene*__-based search engine, which uses JSON-based REST API for using Lucene functions.
* Elastic search is a search and analytics engine.
* It is a document-oriented database, which can store, search data quickly in a short period of time.
* It can deal with higher volumes of documents in a short period of time. This is because, it does not search text or word directly, and searches the index instead.

## __SOLR__

* It is a search platform that is built using _Apache Lucene_.
* Many of the world's major websites use Solr to power their search and to use the functions of navigation.
* Solr is a REST-like enterprise search server that runs on its own.
* The features of solr are database integration, indexing, full-text search, and also it can deal with Word and PDF documents.

----

__Differences between _Lucene_, _Solr_, and _Elastic_ Search__

Solr | Lucene | Elastic search
---- | ------ | --------------
It is built using Apache Lucene | It is developed using JAVA | It is a Lucene-based search engine
It can be used even without the knowledge of programming languages (JAVA) |It can be used only if JAVA is known | It can be used with knowledge of JAVA
Unlike Lucene, It cannot be used to build our own search engine | It can be used to create our own search engines like text analysis | It cannot be used to build our own search engine
Solr is a REST-like enterprise search server that runs on its own. | It is based on JAVA API | It is based on JSON based REST API

----

### __Reference  Links__

1. <https://solr.apache.org/> - Solr website
2. <https://lucene.apache.org/> - Lucene website
3. <https://www.elastic.co/> - Elastic search website
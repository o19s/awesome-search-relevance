# awesome-search-relevance

Tools and other things for people who work on search relevance &amp; information retrieval

# Tools

The "plungers" we use in our job day-to-day.

## Offline Search Relevance Testing

- [Quepid](http://quepid.com) - test driven relevance browser sandbox using a small set of judgments
- [Splainer](http://splainer.io) - debug a single Solr or Elasticsearch query
- [Rated Ranking Evaluator](https://github.com/SeaseLtd/rated-ranking-evaluator) - Maven based relevance testing tool against a Solr or Elasticsearch config
- [Quaerite](https://github.com/mitre/quaerite) - Search relevance evaluation framework

## Search Engines

- [Apache Solr](http://lucene.apache.org/solr/)
- [Elasticsearch](https://www.elastic.co/downloads/elasticsearch)
- [Vespa](http://vespa.ai)

## Learning to Rank Tooling

Tooling for doing machine learning to optimize relevance

### Search Engine Plugins

- [Elasticsearch Learning to Rank](http://github.com/o19s/elasticsearch-learning-to-rank) - supports storing and logging features (ES queries), uploading models, and executing Ranklib and XGBoost models
- [Solr Learning to Rank](https://lucene.apache.org/solr/guide/6_6/learning-to-rank.html) - supports storing and logging features (Solr queries), uploading models, and executing a range of models

### Learning to Rank Training Models

- [Ranklib](https://sourceforge.net/p/lemur/wiki/RankLib/) - original implementation of LambdaMART and other algorithms
- [RankyMcRankFace](https://github.com/o19s/RankyMcRankFace) - Ranklib fork with a few extra features
- [XGBoost](https://xgboost.readthedocs.io/en/latest/) - eXtreme Gradient Boosting - scalably train a MART ranking model
- [LightGBM](https://github.com/Microsoft/LightGBM) - Microsoft's gradient boosting library
- [TFRanking](https://github.com/tensorflow/ranking) - Tensorflow ranking

## NLP

- [Gensim](https://radimrehurek.com/gensim/) - Topic modeling, and other useful NLP tasks like collocation detection, word2vec, and others

## Analytics

- [Search Collector](https://github.com/searchhub/search-collector) - Collecting behavioral signals from a browser

## Rule Systems

- [Querqy](http://github.com/renekrie/querqy) - Query preprocessing & search rule system for applying query-specific boosts, filters, downboosts, etc (ie downboost 'case' category when user searches for 'iPhone')

# Blogs

- [Lucidworks Blog](http://lucidworks.com/blog) - Fusion & Solr
- [OpenSource Connections Blog](http://opensourceconnections.com/blog) - open source relevance blogging

# Conferences & Meetups

- [Haystack](http://haystackconf.com) - Haystack the Search Relevance conference
- [Activate](http://activate-conf.com) - formerly Lucene/Solr Revolution, focus on Solr+AI
- [SIGIR](http://sigir.org/) - ACM's Information Retrieval conference. Academic focused with an industry day
- [ECIR](http://ecir2019.org/) - European Conference on Information Retrieval
- [MICES](http://mices.co) - MIx Camp E-commerce Search, focused on E-commerce industry across technologists and product managers
- [Search Solutions](https://irsg.bcs.org/) - British Computer Society day covering search and information retrieval

## Past Conference Videos

- [Haystack US 2019] (https://www.youtube.com/playlist?list=PLCoJWKqBHERu9Fe0W12D7XKwGT2eoJJNU) - Youtube Playlist of Haystack 2019 talks.   

# Training

- [OpenSource Connections Training](http://opensourceconnections.com/events/training) - Solr &amp; Elasticsearch relevance, Learning to rank, NLP training and others
- [Elastic training](https://www.elastic.co/training/) - a smattering of classes that can help with relevance like deep diving into analyzers, etc
- [Lucidworks training](http://lucidworks.com/training) - classes covering Solr + Lucidworks Fusion

# Hosted Cloud Based Open Source Search

Cloud-based Solr, Elasticsearch

- [Bonsai](http://bonsai.io)
- [MeasuredSearch](http://measuredsearch.com)
- [Elastic Cloud](https://www.elastic.co/cloud/)

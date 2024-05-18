## command

### start neo4J
neo4j 5.19.0 (pay attention, if the version is lower than 5.15, it doesn't support vector index, if the version lower than 5.17, you can't use genai pugin)
link: https://neo4j.com/docs/cypher-manual/current/genai-integrations/

However: GenAI is only available in the enterprise edition of Neo4j. It's available in aura and aura free, which is probably what the training is using for the neo4j backend. The error message could definitely be better though.

plugin APOC 5.19.0(the way to install is click the DB(when you start the DB, click the bar) in neo4j desktop and there is pugin option, use that to install)
search engine and fetch information: Community detection 

plugin Graph Data Science Library for similarity search.
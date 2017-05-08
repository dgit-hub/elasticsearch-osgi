# elasticsearch-osgi
This Maven build will generate an elasticsearch-osgi bundle that contains:

 * **Export-Package:** of **com.elasticsearch*** packages
 * **Export-Package:** of **org.apache.lucene.search.join&version=[lucene.version]**
   required when using the **org.elasticsearch.index.query.QueryBuilders.nestedQuery(...)** function
 * The [Elasticsearch Java REST API Client](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/index.html)

## Motivation
This was developed to extend the work performed in ServiceMix https://git-wip-us.apache.org/repos/asf?p=servicemix-bundles.git for the additional requirements listed above.

## Contributors
https://git-wip-us.apache.org/repos/asf?p=servicemix-bundles.git

## License
http://www.apache.org/licenses/LICENSE-2.0
